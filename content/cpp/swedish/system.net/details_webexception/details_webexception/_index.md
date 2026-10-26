---
title: Details_WebException()
second_title: Aspose.Slides för C++ API-referens
description: Skapar en ny instans.
type: docs
weight: 40
url: /sv/system.net/details_webexception/details_webexception/
---
## Details_WebException::Details_WebException() konstruktor


Skapar en ny instans.

```cpp
System::Net::Details_WebException::Details_WebException()
```

## Details_WebException::Details_WebException(String) konstruktor


Skapar en ny instans.

```cpp
System::Net::Details_WebException::Details_WebException(String message)
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| message | [String](../../../system/string/) | Felbeskrivning. |

## Details_WebException::Details_WebException(String, Exception) konstruktor


Skapar en ny instans.

```cpp
System::Net::Details_WebException::Details_WebException(String message, Exception innerException)
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| message | [String](../../../system/string/) | Undantagsmeddelandet. |
| innerException | [Exception](../../../system/exception/) | Det inre undantaget. |

## Details_WebException::Details_WebException(String, WebExceptionStatus) konstruktor


Skapar en ny instans.

```cpp
System::Net::Details_WebException::Details_WebException(String message, WebExceptionStatus status)
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| message | [String](../../../system/string/) | Undantagsmeddelandet. |
| status | [WebExceptionStatus](../../webexceptionstatus/) | Statuskoden. |

## Details_WebException::Details_WebException(String, Exception, WebExceptionStatus, System::SharedPtr\<WebResponse\>) konstruktor


Skapar en ny instans.

```cpp
System::Net::Details_WebException::Details_WebException(String message, Exception innerException, WebExceptionStatus status, System::SharedPtr<WebResponse> response)
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| message | [String](../../../system/string/) | Undantagsmeddelandet. |
| innerException | [Exception](../../../system/exception/) | Det inre undantaget. |
| status | [WebExceptionStatus](../../webexceptionstatus/) | Statuskoden. |
| response | [System::SharedPtr](../../../system/sharedptr/)\<[WebResponse](../../webresponse/)\> | Webbresponsen som den aktuella undantaget är associerad med. |

## Se även

* Enum [WebExceptionStatus](../../webexceptionstatus/)
* Typedef [Exception](../../../system/exception/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Klass [Details_WebException](../)
* Klass [String](../../../system/string/)
* Klass [WebResponse](../../webresponse/)
* Namnrymd [System::Net](../../)
* Bibliotek [Aspose.Slides](../../../)