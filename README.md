# TicketPass API Spec

![문서링크](https://stoplight.io/p/docs/gh/tikketpass/ticketpass-api-spec)

## Mock API

![https://stoplight.io/p/mocks/13955/154091//v1/users/{userId}/use-ticket](https://stoplight.io/p/mocks/13955/154091//v1/users/{userId}/use-ticket)

```
example

request:
	POST https://stoplight.io/p/mocks/13955/154091/v1/auth/sign-in
		BODY:
			{
				"email": "gildong@email.com",
				"password": "9f86d081884c7d659a2feaa0c55ad015a3bf4f1b2b0b822cd15d6c15b0f00a08",
				"role": "PARTICIPANT"
			}
response:
	{
		"accessToken": "eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJ1c2VySWQiOjEsInJvbGUiOiJQQVJUSUNJUEFOVCIsImV4cCI6MTYwNjA5NzE0MDU0Nn0.t9E6KvykkkIvlivwlyQjG9E7kTu81GMfI-mKohvj5Ro",
		"refreshToken": "eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJ1c2VySWQiOjEsInJvbGUiOiJQQVJUSUNJUEFOVCIsImV4cCI6MTY4Mzg1NzE1OTc3M30.SWT55JmoheoYhgWSjV3LYMCxbVG22t52ODvQAJKZBD0",
		"tokenType": "Bearer",
		"user": {
   			"id": 1,
 			"name": "홍길동",
 			"email:": "gildong@email.com"
		}
	}
	
```