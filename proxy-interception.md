# Proxy Interception using Burp Suite

## Objective
Intercept HTTP traffic between browser and server.

## Environment
Tool: Burp Suite  
Browser: Firefox  
Proxy: 127.0.0.1:8080

## Steps Performed

1. Started Burp Suite.
2. Configured browser proxy to 127.0.0.1:8080.
3. Enabled intercept in Burp Proxy.
4. Opened a login page in the browser.
5. Captured the HTTP request before forwarding.

## Example HTTP Request

POST /login HTTP/1.1
Host: example.com
Content-Type: application/x-www-form-urlencoded

username=admin&password=12345

## Result

Successfully intercepted HTTP request and analyzed parameters.
