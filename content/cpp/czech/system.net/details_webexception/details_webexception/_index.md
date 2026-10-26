---
title: Details_WebException()
second_title: Aspose.Slides pro C++ - referenční příručka API
description: Vytvoří novou instanci.
type: docs
weight: 40
url: /cs/system.net/details_webexception/details_webexception/
---
## Details_WebException::Details_WebException() konstruktor


Vytvoří novou instanci.

```cpp
System::Net::Details_WebException::Details_WebException()
```

## Details_WebException::Details_WebException(String) konstruktor


Vytvoří novou instanci.

```cpp
System::Net::Details_WebException::Details_WebException(String message)
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| message | [String](../../../system/string/) | Popis chyby. |

## Details_WebException::Details_WebException(String, Exception) konstruktor


Vytvoří novou instanci.

```cpp
System::Net::Details_WebException::Details_WebException(String message, Exception innerException)
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| message | [String](../../../system/string/) | Zpráva výjimky. |
| innerException | [Exception](../../../system/exception/) | Vnitřní výjimka. |

## Details_WebException::Details_WebException(String, WebExceptionStatus) konstruktor


Vytvoří novou instanci.

```cpp
System::Net::Details_WebException::Details_WebException(String message, WebExceptionStatus status)
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| message | [String](../../../system/string/) | Zpráva výjimky. |
| status | [WebExceptionStatus](../../webexceptionstatus/) | Kód stavu. |

## Details_WebException::Details_WebException(String, Exception, WebExceptionStatus, System::SharedPtr\<WebResponse\>) konstruktor


Vytvoří novou instanci.

```cpp
System::Net::Details_WebException::Details_WebException(String message, Exception innerException, WebExceptionStatus status, System::SharedPtr<WebResponse> response)
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| message | [String](../../../system/string/) | Zpráva výjimky. |
| innerException | [Exception](../../../system/exception/) | Vnitřní výjimka. |
| status | [WebExceptionStatus](../../webexceptionstatus/) | Kód stavu. |
| response | [System::SharedPtr](../../../system/sharedptr/)\<[WebResponse](../../webresponse/)\> | Webová odpověď, ke které je aktuální výjimka přiřazena. |

## Viz také

* Enum [WebExceptionStatus](../../webexceptionstatus/)
* Typedef [Exception](../../../system/exception/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* třída [Details_WebException](../)
* třída [String](../../../system/string/)
* třída [WebResponse](../../webresponse/)
* jmenný prostor [System::Net](../../)
* knihovna [Aspose.Slides](../../../)