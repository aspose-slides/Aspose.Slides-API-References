---
title: Details_WebException()
second_title: Aspose.Slides für C++ API-Referenz
description: Erstellt eine neue Instanz.
type: docs
weight: 40
url: /de/system.net/details_webexception/details_webexception/
---
## Details_WebException::Details_WebException() Konstruktor

Erstellt eine neue Instanz.

```cpp
System::Net::Details_WebException::Details_WebException()
```

## Details_WebException::Details_WebException(String) Konstruktor

Erstellt eine neue Instanz.

```cpp
System::Net::Details_WebException::Details_WebException(String message)
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| message | [String](../../../system/string/) | Die Fehlerbeschreibung. |

## Details_WebException::Details_WebException(String, Exception) Konstruktor

Erstellt eine neue Instanz.

```cpp
System::Net::Details_WebException::Details_WebException(String message, Exception innerException)
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| message | [String](../../../system/string/) | Die Ausnahmemeldung. |
| innerException | [Exception](../../../system/exception/) | Die innere Ausnahme. |

## Details_WebException::Details_WebException(String, WebExceptionStatus) Konstruktor

Erstellt eine neue Instanz.

```cpp
System::Net::Details_WebException::Details_WebException(String message, WebExceptionStatus status)
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| message | [String](../../../system/string/) | Die Ausnahmemeldung. |
| status | [WebExceptionStatus](../../webexceptionstatus/) | Der Statuscode. |

## Details_WebException::Details_WebException(String, Exception, WebExceptionStatus, System::SharedPtr\<WebResponse\>) Konstruktor

Erstellt eine neue Instanz.

```cpp
System::Net::Details_WebException::Details_WebException(String message, Exception innerException, WebExceptionStatus status, System::SharedPtr<WebResponse> response)
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| message | [String](../../../system/string/) | Die Ausnahmemeldung. |
| innerException | [Exception](../../../system/exception/) | Die innere Ausnahme. |
| status | [WebExceptionStatus](../../webexceptionstatus/) | Der Statuscode. |
| response | [System::SharedPtr](../../../system/sharedptr/)\<[WebResponse](../../webresponse/)\> | Die Webantwort, mit der die aktuelle Ausnahme verknüpft ist. |

## Siehe auch

* Enum [WebExceptionStatus](../../webexceptionstatus/)
* Typedef [Exception](../../../system/exception/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Details_WebException](../)
* Class [String](../../../system/string/)
* Class [WebResponse](../../webresponse/)
* Namespace [System::Net](../../)
* Library [Aspose.Slides](../../../)