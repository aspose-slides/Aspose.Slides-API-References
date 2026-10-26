---
title: Details_WebException()
second_title: Aspose.Slides voor C++ API-referentie
description: Maakt een nieuw exemplaar aan.
type: docs
weight: 40
url: /nl/system.net/details_webexception/details_webexception/
---
## Details_WebException::Details_WebException() constructor


Maakt een nieuw exemplaar aan.

```cpp
System::Net::Details_WebException::Details_WebException()
```

## Details_WebException::Details_WebException(String) constructor


Maakt een nieuw exemplaar aan.

```cpp
System::Net::Details_WebException::Details_WebException(String message)
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| message | [String](../../../system/string/) | De foutbeschrijving. |

## Details_WebException::Details_WebException(String, Exception) constructor


Maakt een nieuw exemplaar aan.

```cpp
System::Net::Details_WebException::Details_WebException(String message, Exception innerException)
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| message | [String](../../../system/string/) | Het exceptiebericht. |
| innerException | [Exception](../../../system/exception/) | De interne exceptie. |

## Details_WebException::Details_WebException(String, WebExceptionStatus) constructor


Maakt een nieuw exemplaar aan.

```cpp
System::Net::Details_WebException::Details_WebException(String message, WebExceptionStatus status)
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| message | [String](../../../system/string/) | Het exceptiebericht. |
| status | [WebExceptionStatus](../../webexceptionstatus/) | De statuscode. |

## Details_WebException::Details_WebException(String, Exception, WebExceptionStatus, System::SharedPtr\<WebResponse\>) constructor


Maakt een nieuw exemplaar aan.

```cpp
System::Net::Details_WebException::Details_WebException(String message, Exception innerException, WebExceptionStatus status, System::SharedPtr<WebResponse> response)
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| message | [String](../../../system/string/) | Het exceptiebericht. |
| innerException | [Exception](../../../system/exception/) | De interne exceptie. |
| status | [WebExceptionStatus](../../webexceptionstatus/) | De statuscode. |
| response | [System::SharedPtr](../../../system/sharedptr/)\<[WebResponse](../../webresponse/)\> | De webrespons waaraan de huidige exceptie is gekoppeld. |

## Zie ook

* Enum [WebExceptionStatus](../../webexceptionstatus/)
* Typedef [Exception](../../../system/exception/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [Details_WebException](../)
* Klasse [String](../../../system/string/)
* Klasse [WebResponse](../../webresponse/)
* Naamruimte [System::Net](../../)
* Library [Aspose.Slides](../../../)