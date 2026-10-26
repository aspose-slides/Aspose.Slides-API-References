---
title: HttpRequestMessage()
second_title: Aspose.Slides för C++ API-referens
description: Skapar en ny instans.
type: docs
weight: 131
url: /sv/system.net.http/httprequestmessage/httprequestmessage/
---
## HttpRequestMessage::HttpRequestMessage() konstruktör


Skapar en ny instans.

```cpp
System::Net::Http::HttpRequestMessage::HttpRequestMessage()
```

## HttpRequestMessage::HttpRequestMessage(System::SharedPtr\<HttpMethod\>, System::SharedPtr\<Uri\>) konstruktör


Skapar en ny instans.

```cpp
System::Net::Http::HttpRequestMessage::HttpRequestMessage(System::SharedPtr<HttpMethod> method, System::SharedPtr<Uri> requestUri)
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| method | [System::SharedPtr](../../../system/sharedptr/)\<[HttpMethod](../../httpmethod/)\> | HTTP-metoden. |
| requestUri | [System::SharedPtr](../../../system/sharedptr/)\<[Uri](../../../system/uri/)\> | URI för den begärda resursen. |

## HttpRequestMessage::HttpRequestMessage(System::SharedPtr\<HttpMethod\>, String) konstruktör


Skapar en ny instans.

```cpp
System::Net::Http::HttpRequestMessage::HttpRequestMessage(System::SharedPtr<HttpMethod> method, String requestUri)
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| method | [System::SharedPtr](../../../system/sharedptr/)\<[HttpMethod](../../httpmethod/)\> | HTTP-metoden. |
| requestUri | [String](../../../system/string/) | URI för den begärda resursen. |

## Se även

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klass [HttpRequestMessage](../)
* Klass [HttpMethod](../../httpmethod/)
* Klass [Uri](../../../system/uri/)
* Klass [String](../../../system/string/)
* Namnrymd [System::Net::Http](../../)
* Library [Aspose.Slides](../../../)