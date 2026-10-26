---
title: InternalAdd()
second_title: Aspose.Slides C++ API referencia
description: Hozzáadja a megadott cookie-t a gyűjteményhez.
type: docs
weight: 118
url: /hu/system.net/cookiecollection/internaladd/
---
## CookieCollection::InternalAdd(System::SharedPtr\<Cookie\>, bool) metódus


Hozzáadja a megadott cookie-t a gyűjteményhez.

```cpp
int32_t System::Net::CookieCollection::InternalAdd(System::SharedPtr<Cookie> cookie, bool isStrict)
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| cookie | [System::SharedPtr](../../../system/sharedptr/)\<[Cookie](../../cookie/)\> | A hozzáadandó cookie. |
| isStrict | **bool** | Igaz, ha a megadott cookie-nak fel kell helyettesítenie a régit, egyébként hamis. |

### Visszatérési érték

0, ha a megadott cookie felülírta a régit, egyébként 1.

## Lásd még

* Typedef [SharedPtr](../../../system/sharedptr/)
* Osztály [Cookie](../../cookie/)
* Osztály [CookieCollection](../)
* Névtér [System::Net](../../)
* Könyvtár [Aspose.Slides](../../../)