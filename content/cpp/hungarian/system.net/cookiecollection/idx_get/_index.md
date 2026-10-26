---
title: idx_get()
second_title: Aspose.Slides for C++ API hivatkozás
description: Visszaad egy sütit a cookie gyűjteményből a megadott indexen.
type: docs
weight: 40
url: /hu/system.net/cookiecollection/idx_get/
---
## CookieCollection::idx_get(int32_t) metódus


Visszaad egy sütit a cookie gyűjteményből a megadott indexen.

```cpp
System::SharedPtr<Cookie> System::Net::CookieCollection::idx_get(int32_t index)
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| index | **int32_t** | A visszaadandó süti indexe. |

### Visszatérési érték

Egy süti a megadott indexen.

## CookieCollection::idx_get(String) metódus


Visszaad egy sütit a cookie gyűjteményből a megadott név alapján.

```cpp
System::SharedPtr<Cookie> System::Net::CookieCollection::idx_get(String name)
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| name | [String](../../../system/string/) | A visszaadandó süti neve. |

### Visszatérési érték

Egy süti a cookie gyűjteményből a megadott név alapján, ha megtalálható, egyébként nullptr.

## Lásd még

* Typedef [SharedPtr](../../../system/sharedptr/)
* Osztály [Cookie](../../cookie/)
* Osztály [CookieCollection](../)
* Osztály [String](../../../system/string/)
* Névtér [System::Net](../../)
* Könyvtár [Aspose.Slides](../../../)