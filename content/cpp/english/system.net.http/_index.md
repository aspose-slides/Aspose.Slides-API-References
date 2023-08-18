---
title: "System::Net::Http"
second_title: Aspose.Slides for C++ API Reference
description: 
type: docs
weight: 625
url: /system.net.http/
---



## Classes

| Class | Description |
| --- | --- |
| [ByteArrayContent](./bytearraycontent/) | Represents HTTP content as a byte array. Objects of this class should only be allocated using [System::MakeObject()](../system/makeobject/) function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into [System::SmartPtr](../system/smartptr/) pointer and use this pointer to pass it to functions as argument. |
| [Details_HttpRequestException](./details_httprequestexception/) | The base exception class is thrown by the [HttpClient](./httpclient/) and [HttpMessageHandler](./httpmessagehandler/) classes. Never create instances of this class manually. Use the HttpRequestException class instead. Never wrap the HttpRequestException class instances into [System::SmartPtr](../system/smartptr/). |
| [HttpClient](./httpclient/) | Represents a base class of an HTTP client for sending requests and receiving responses. Objects of this class should only be allocated using [System::MakeObject()](../system/makeobject/) function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into [System::SmartPtr](../system/smartptr/) pointer and use this pointer to pass it to functions as argument. |
| [HttpClientHandler](./httpclienthandler/) | Represents the default message handler used by the [HttpClient](./httpclient/) class. Objects of this class should only be allocated using [System::MakeObject()](../system/makeobject/) function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into [System::SmartPtr](../system/smartptr/) pointer and use this pointer to pass it to functions as argument. |
| [HttpContent](./httpcontent/) | Represents content of an HTTP entity. [Object](../system/object/) of this class should only be allocated using [System::MakeObject()](../system/makeobject/) function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into [System::SmartPtr](../system/smartptr/) pointer and use this pointer to pass it to functions as argument. |
| [HttpMessageHandler](./httpmessagehandler/) | Represents a base type for the HTTP message handlers. Objects of this class should only be allocated using [System::MakeObject()](../system/makeobject/) function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into [System::SmartPtr](../system/smartptr/) pointer and use this pointer to pass it to functions as argument. |
| [HttpMessageInvoker](./httpmessageinvoker/) | Allows applications to call the Send method on an HTTP handler chain. Objects of this class should only be allocated using [System::MakeObject()](../system/makeobject/) function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into [System::SmartPtr](../system/smartptr/) pointer and use this pointer to pass it to functions as argument. |
| [HttpMethod](./httpmethod/) | Represents an HTTP method. Objects of this class should only be allocated using [System::MakeObject()](../system/makeobject/) function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into [System::SmartPtr](../system/smartptr/) pointer and use this pointer to pass it to functions as argument. |
| [HttpRequestMessage](./httprequestmessage/) | Represents an HTTP request message. Objects of this class should only be allocated using [System::MakeObject()](../system/makeobject/) function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into [System::SmartPtr](../system/smartptr/) pointer and use this pointer to pass it to functions as argument. |
| [HttpResponseMessage](./httpresponsemessage/) | Represents an HTTP response message. Objects of this class should only be allocated using [System::MakeObject()](../system/makeobject/) function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into [System::SmartPtr](../system/smartptr/) pointer and use this pointer to pass it to functions as argument. |
| [HttpUtilities](./httputilities/) | Contains the utility methods. |
| [StringContent](./stringcontent/) | Represents HTTP content as a string. Objects of this class should only be allocated using [System::MakeObject()](../system/makeobject/) function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into [System::SmartPtr](../system/smartptr/) pointer and use this pointer to pass it to functions as argument. |
## Functions

| Function | Description |
| --- | --- |
| **bool** [operator==](./operator_equal_equal/)([System::SharedPtr](../system/sharedptr/)\<[HttpMethod](./httpmethod/)\>, [System::SharedPtr](../system/sharedptr/)\<[HttpMethod](./httpmethod/)\>) |  |
| **bool** [operator!=](./operator_not_equal/)([System::SharedPtr](../system/sharedptr/)\<[HttpMethod](./httpmethod/)\>, [System::SharedPtr](../system/sharedptr/)\<[HttpMethod](./httpmethod/)\>) |  |
## Enums

| Enum | Description |
| --- | --- |
| [HttpCompletionOption](./httpcompletionoption/) | Indicates when an [HttpClient](./httpclient/) operation should be completed. |
| [HttpParseResult](./httpparseresult/) | Indicates the parsing result. |
## Typedefs

| Typedef | Description |
| --- | --- |
| [HttpRequestException](./httprequestexception/) |  |
