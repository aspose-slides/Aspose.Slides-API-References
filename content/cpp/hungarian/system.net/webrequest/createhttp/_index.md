---
title: CreateHttp()
second_title: Aspose.Slides C++ API referencia
description: Új példányt hoz létre a WebRequest osztályból a megadott URI használatával.
type: docs
weight: 79
url: /hu/system.net/webrequest/createhttp/
---
## WebRequest::CreateHttp(String) metódus

Új példányt hoz létre a [WebRequest](../) osztályból a megadott URI használatával.

```cpp
static System::SharedPtr<HttpWebRequest> System::Net::WebRequest::CreateHttp(String requestUriString)
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| requestUriString | [String](../../../system/string/) | Az URI, amelyet a [WebRequest](../) osztály új példányának létrehozásához használnak. |

### Visszatérési érték

Újonnan létrehozott WebRequest osztálypéldány.

## Megjegyzések

NotSupportedException kerül dobásra, ha a megadott URI bármely séma szerint kezdődik, kivéve a [http://](http://) vagy [https://](https://) esetén.

## WebRequest::CreateHttp(System::SharedPtr\<Uri\>) metódus

Új példányt hoz létre a [WebRequest](../) osztályból a megadott URI használatával.

```cpp
static System::SharedPtr<HttpWebRequest> System::Net::WebRequest::CreateHttp(System::SharedPtr<Uri> requestUri)
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| requestUri | [System::SharedPtr](../../../system/sharedptr/)\<[Uri](../../../system/uri/)\> | Az URI, amelyet a [WebRequest](../) osztály új példányának létrehozásához használnak. |

### Visszatérési érték

Újonnan létrehozott WebRequest osztálypéldány.

## Megjegyzések

NotSupportedException kerül dobásra, ha a megadott URI bármely séma szerint kezdődik, kivéve a [http://](http://) vagy [https://](https://) esetén.

## Lásd még

* Typedef [SharedPtr](../../../system/sharedptr/)
* Osztály [HttpWebRequest](../../httpwebrequest/)
* Osztály [String](../../../system/string/)
* Osztály [WebRequest](../)
* Osztály [Uri](../../../system/uri/)
* Névtér [System::Net](../../)
* Könyvtár [Aspose.Slides](../../../)