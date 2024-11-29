Behavior
- go live
- open index.html
- test chat
- add ?something=Hola in URL 

Hack
- try xss in chat with some common payloads (script,img etc)
- try xss in url (ej. ?something=<img src="x" onerror=alert(1)>)


Mitigation
- go to sanitize() method in index.html and enable the manual sanitization
- go to sanitize() method in index.html and enable the DOMPurify sanitization