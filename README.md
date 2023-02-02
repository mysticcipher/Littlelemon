Home page: restaurant/

(POST) Register user: auth/users/
body:
{
	"username": "nick",
	"email": "nick@littlelemon.com",
	"password": "nick@1234"
}

(POST) Get login token: auth/token/login
body:
{
	"username":"nick",
	"password":"nick@1234"
}

(POST) Add menu: restaurant/menu/
body:
{
	"title": "Burger",
	"price": "75.00",
	"inventory": 10
}

(GET) Menu list: restaurant/menu/

(POST) Booking a table: restaurant/booking/tables
body:
{
	"id":1,
	"name":"henry",
	"no_of_guests":5,
	"booking_date": "2023-04-12"
}

(GET) Booked table list: restaurant/booking/tables
