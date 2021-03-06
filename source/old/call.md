Provides access to the call log. The call log contains all the calls which have been made through Numbers under your control.

# GET /calls

Lists all the calls currently in the system for your account.

**Resource URL**
@note http://callpixels.com/calls.format

# GET /calls/from/2012/01/31/to/2012/02/28

Lists all the calls within the date range specified.

**Resource URL**
@note http://callpixels.com/calls/from/2012/01/31/to/2012/02/28.format

# GET /calls/addcf985-017e-4962-be34-cf5d55e74afc

Get a single call by UUID.

**Resource URL**
@note http://callpixels.com/calls/addcf985-017e-4962-be34-cf5d55e74afc.format

**Response**

~~~~
JSON
{
   "call":{
      "uuid":"addcf985-017e-4962-be34-cf5d55e74afc",
      "caller":"+17195220377",
      "caller_zip":"80920",
      "caller_state":"CO",
      "caller_city":"COLORADO SPRINGS",
      "caller_country":"US",
      "dialed_call_duration":193,
      "total_duration":204,
      "status":"finished",
      "start_time":"2012-04-29T12:29:40Z",
      "forwarded_time":"2012-04-29T12:29:51Z",
      "end_time":"2012-04-29T12:32:46Z",
      "cid":"0003",
      "afid":"03994",
      "sid":null,
      "dialed_number":"+18668987878",
      "updated_at":"2012-04-29T12:29:46Z",
      "created_at":"2012-04-29T12:29:40Z",
      "recording_url":"http://callpixels.com/recordings/87d43a5f5c88041687f9fd1bb6a58d6f/call_17192096019_1342303189.mp3"
   }
}
~~~~