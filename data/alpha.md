

files = {
    "purpose": (None,"assistants"),
    "file": open("portfolio.xlsx", "rb")}

uploads_res = requests.post(f"{base_url}/files", headers=headers, files=files)

{
  "error": {
    "message": "The server had an error processing your request. Sorry about that! You can retry your request, or contact us through our help center at help.openai.com if you keep seeing this error. (Please include the request ID 259f4a266b670900996a6b8f63e59235 in your email.)",
    "type": "server_error",
    "param": null,
    "code": null
  }
}