---
title: Details_WebException()
second_title: Aspose.Slides C++ API-referencia
description: Új példányt hoz létre.
type: docs
weight: 40
url: /hu/system.net/details_webexception/details_webexception/
---
## Details_WebException::Details_WebException() konstruktor


Új példányt hoz létre.

```cpp
System::Net::Details_WebException::Details_WebException()
```

## Details_WebException::Details_WebException(String) konstruktor


Új példányt hoz létre.

```cpp
System::Net::Details_WebException::Details_WebException(String message)
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| message | [String](../../../system/string/) | A hiba leírása. |

## Details_WebException::Details_WebException(String, Exception) konstruktor


Új példányt hoz létre.

```cpp
System::Net::Details_WebException::Details_WebException(String message, Exception innerException)
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| message | [String](../../../system/string/) | A kivétel üzenete. |
| innerException | [Exception](../../../system/exception/) | A belső kivétel. |

## Details_WebException::Details_WebException(String, WebExceptionStatus) konstruktor


Új példányt hoz létre.

```cpp
System::Net::Details_WebException::Details_WebException(String message, WebExceptionStatus status)
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| message | [String](../../../system/string/) | A kivétel üzenete. |
| status | [WebExceptionStatus](../../webexceptionstatus/) | Az állapotkód. |

## Details_WebException::Details_WebException(String, Exception, WebExceptionStatus, System::SharedPtr\<WebResponse\>) konstruktor


Új példányt hoz létre.

```cpp
System::Net::Details_WebException::Details_WebException(String message, Exception innerException, WebExceptionStatus status, System::SharedPtr<WebResponse> response)
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| message | [String](../../../system/string/) | A kivétel üzenete. |
| innerException | [Exception](../../../system/exception/) | A belső kivétel. |
| status | [WebExceptionStatus](../../webexceptionstatus/) | Az állapotkód. |
| response | [System::SharedPtr](../../../system/sharedptr/)\<[WebResponse](../../webresponse/)\> | A webválasz, amelyhez az aktuális kivétel kapcsolódik. |

## Lásd még

* Enum [WebExceptionStatus](../../webexceptionstatus/)
* Typedef [Exception](../../../system/exception/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Details_WebException](../)
* Class [String](../../../system/string/)
* Class [WebResponse](../../webresponse/)
* Namespace [System::Net](../../)
* Library [Aspose.Slides](../../../)