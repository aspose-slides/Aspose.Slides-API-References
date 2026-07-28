---
title: RegisterPrefix()
second_title: Aspose.Slides C++ API referencia
description: Regisztrálja a WebRequest leszármazottat a megadott URI-re.
type: docs
weight: 92
url: /hu/system.net/webrequest/registerprefix/
---
## WebRequest::RegisterPrefix(String, System::SharedPtr\<IWebRequestCreate\>) metódus


Regisztrálja a [WebRequest](../) leszármazottat a megadott URI-re.

```cpp
static bool System::Net::WebRequest::RegisterPrefix(String prefix, System::SharedPtr<IWebRequestCreate> creator)
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| prefix | [String](../../../system/string/) | Az URI vagy az URI előtagja. |
| creator | [System::SharedPtr](../../../system/sharedptr/)\<[IWebRequestCreate](../../iwebrequestcreate/)\> | Új példányokat hoz létre a [WebRequest](../) osztályból. |

### Visszatérési érték

Igaz, ha a [WebRequest](../) leszármazott sikeresen regisztrálva van a megadott URI-re, egyébként hamis.

## Lásd még

* Typedef [SharedPtr](../../../system/sharedptr/)
* Osztály [String](../../../system/string/)
* Osztály [IWebRequestCreate](../../iwebrequestcreate/)
* Osztály [WebRequest](../)
* Névtér [System::Net](../../)
* Könyvtár [Aspose.Slides](../../../)