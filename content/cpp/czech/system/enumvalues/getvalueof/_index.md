---
title: GetValueOf()
second_title: Aspose.Slides pro C++ API Reference
description: Vrací zabalenou hodnotu výčtové konstanty se zadaným názvem.
type: docs
weight: 53
url: /cs/system/enumvalues/getvalueof/
---
## EnumValues::GetValueOf(const String\&, bool) const metoda


Vrací zabalenou hodnotu výčtové konstanty se zadaným názvem.

```cpp
virtual SharedPtr<Object> System::EnumValues<E, Guard>::GetValueOf(const String &str, bool ignoreCase) const override
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| str | const [String](../../string/)\& | Název výčtové konstanty |
| ignoreCase | **bool** | Určuje, zda má být při interpretaci názvu výčtové konstanty ignorována velikost písmen |

### Návratová hodnota

Zabalená hodnota výčtové konstanty, jejíž název je určen v **str**.

## EnumValues::GetValueOf(long) const metoda


Vrací zabalenou hodnotu výčtové konstanty se zadanou hodnotou.

```cpp
virtual SharedPtr<Object> System::EnumValues<E, Guard>::GetValueOf(long val) const override
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| val | long | Hodnota výčtové konstanty |

### Návratová hodnota

Zabalená hodnota výčtové konstanty, jejíž hodnota je určena v **str**.

## Viz také

* Typedef [SharedPtr](../../sharedptr/)
* Třída [Object](../../object/)
* Třída [String](../../string/)
* Třída [EnumValues](../)
* Jmenný prostor [System](../../)
* Knihovna [Aspose.Slides](../../../)