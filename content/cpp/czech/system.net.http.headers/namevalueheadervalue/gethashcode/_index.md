---
title: GetHashCode()
second_title: Aspose.Slides pro C++ referenční příručka API
description: Analogie metody C# Object.GetHashCode(). Umožňuje hašování vlastních objektů.
type: docs
weight: 53
url: /cs/system.net.http.headers/namevalueheadervalue/gethashcode/
---
## NameValueHeaderValue::GetHashCode() const method

Analogie metody [Object.GetHashCode()](../../../system/object/gethashcode/) v C#. Umožňuje hašování vlastních objektů.

```cpp
int32_t System::Net::Http::Headers::NameValueHeaderValue::GetHashCode() const override
```

### Návratová hodnota

Hodnota hash kódu vypočtená odpovídající třídou.

## NameValueHeaderValue::GetHashCode(System::SharedPtr\<ObjectCollection\<System::SharedPtr\<NameValueHeaderValue\>\>\>) method

Vrací hash kód všech položek kolekce.

```cpp
static int32_t System::Net::Http::Headers::NameValueHeaderValue::GetHashCode(System::SharedPtr<ObjectCollection<System::SharedPtr<NameValueHeaderValue>>> values)
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| values | [System::SharedPtr](../../../system/sharedptr/)\<[ObjectCollection](../../objectcollection/)\<[System::SharedPtr](../../../system/sharedptr/)\<[NameValueHeaderValue](../)\>\>\> | Kolekce instancí NameValueHeaderValue-class. |

### Návratová hodnota

Hash kód všech položek kolekce.

## Viz také

* Typedef [SharedPtr](../../../system/sharedptr/)
* Třída [NameValueHeaderValue](../)
* Třída [ObjectCollection](../../objectcollection/)
* Jmenný prostor [System::Net::Http::Headers](../../)
* Knihovna [Aspose.Slides](../../../)