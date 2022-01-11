# README

This README would normally document whatever steps are necessary to get the
application up and running.

Things you may want to cover:

* Ruby version

* System dependencies

* Configuration

rails new . --api -d postgresql
rails generate scaffold Post title:string body:text


* Database creation

rails db:create
rails db:seed

* Database initialization

* How to run the test suite

http://127.0.0.1:3000/posts

[{"id":1,"title":"title-0","body":"Foooooo0","created_at":"2022-01-11T01:39:04.767Z","updated_at":"2022-01-11T01:39:04.767Z"},{"id":2,"title":"title-1","body":"Foooooo1","created_at":"2022-01-11T01:39:04.796Z","updated_at":"2022-01-11T01:39:04.796Z"},{"id":3,"title":"title-2","body":"Foooooo2","created_at":"2022-01-11T01:39:04.803Z","updated_at":"2022-01-11T01:39:04.803Z"},{"id":4,"title":"title-3","body":"Foooooo3","created_at":"2022-01-11T01:39:04.810Z","updated_at":"2022-01-11T01:39:04.810Z"},{"id":5,"title":"title-4","body":"Foooooo4","created_at":"2022-01-11T01:39:04.817Z","updated_at":"2022-01-11T01:39:04.817Z"},{"id":6,"title":"title-5","body":"Foooooo5","created_at":"2022-01-11T01:39:04.825Z","updated_at":"2022-01-11T01:39:04.825Z"},{"id":7,"title":"title-6","body":"Foooooo6","created_at":"2022-01-11T01:39:04.833Z","updated_at":"2022-01-11T01:39:04.833Z"},{"id":8,"title":"title-7","body":"Foooooo7","created_at":"2022-01-11T01:39:04.841Z","updated_at":"2022-01-11T01:39:04.841Z"},{"id":9,"title":"title-8","body":"Foooooo8","created_at":"2022-01-11T01:39:04.849Z","updated_at":"2022-01-11T01:39:04.849Z"},{"id":10,"title":"title-9","body":"Foooooo9","created_at":"2022-01-11T01:39:04.856Z","updated_at":"2022-01-11T01:39:04.856Z"}]

OR
[{"id":1,"title":"title-0","body":"Foooooo0"},{"id":2,"title":"title-1","body":"Foooooo1"},{"id":3,"title":"title-2","body":"Foooooo2"},{"id":4,"title":"title-3","body":"Foooooo3"},{"id":5,"title":"title-4","body":"Foooooo4"},{"id":6,"title":"title-5","body":"Foooooo5"},{"id":7,"title":"title-6","body":"Foooooo6"},{"id":8,"title":"title-7","body":"Foooooo7"},{"id":9,"title":"title-8","body":"Foooooo8"},{"id":10,"title":"title-9","body":"Foooooo9"}]


POSTMAN.COM:


* Services (job queues, cache servers, search engines, etc.)

* Deployment instructions

* ...

