---
title: InternalAdd()
second_title: Aspose.Slides pro C++ reference API
description: Přidá zadaný cookie do kolekce.
type: docs
weight: 118
url: /cs/system.net/cookiecollection/internaladd/
---
## CookieCollection::InternalAdd(System::SharedPtr\<Cookie\>, bool) metoda

Přidá zadaný cookie do kolekce.

```cpp
int32_t System::Net::CookieCollection::InternalAdd(System::SharedPtr<Cookie> cookie, bool isStrict)
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| cookie | [System::SharedPtr](../../../system/sharedptr/)\<[Cookie](../../cookie/)\> | Cookie, který se má přidat. |
| isStrict | **bool** | True, když zadaný cookie musí nahradit starý, jinak false. |

### Návratová hodnota

0, když zadaný cookie nahradil starý, jinak 1.

## Viz také

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Cookie](../../cookie/)
* Class [CookieCollection](../)
* Namespace [System::Net](../../)
* Library [Aspose.Slides](../../../)