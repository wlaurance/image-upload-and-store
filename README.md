image-upload-and-store
======================


##API

HTTP endpoint to upload and store images.

`POST /` with your bytes

returns URL where said bytes are

By nature of HTTP, a GET on the provided URL should warrant you the bytes.

##Implementation

This will be a Golang project with martini as the HTTP package. It will use postgres as the datastore, since
this is the best supported data store. Unless we run into crazy problems, this will be good.

##Why

Making this module as part of an adventure into micro services architecture. Tweet at me for more information
[@wlaurance](https://twitter.com/wlaurance)
