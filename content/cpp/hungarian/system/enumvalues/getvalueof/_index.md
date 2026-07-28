---
title: GetValueOf()
second_title: Aspose.Slides for C++ API referenciája
description: Visszaadja a megadott névvel rendelkező enum állandó dobozolt értékét.
type: docs
weight: 53
url: /hu/system/enumvalues/getvalueof/
---
## EnumValues::GetValueOf(const String\&, bool) const metódus


Returns boxed value of the enum constant with the specified name.

```cpp
virtual SharedPtr<Object> System::EnumValues<E, Guard>::GetValueOf(const String &str, bool ignoreCase) const override
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| str | const [String](../../string/)\& | Az enum állandó neve |
| ignoreCase | **bool** | Megadja, hogy az enum állandó nevének értelmezésekor figyelmen kívül kell-e hagyni a kis- és nagybetűket |

### Visszatérési érték

Az **str**-ben megadott névű enum állandó dobozolt értéke.

## EnumValues::GetValueOf(long) const metódus


Returns boxed value of the enum constant with the specified value.

```cpp
virtual SharedPtr<Object> System::EnumValues<E, Guard>::GetValueOf(long val) const override
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| val | long | Az enum állandó értéke |

### Visszatérési érték

Az **str**-ben megadott értékkel rendelkező enum állandó dobozolt értéke.

## Lásd még

* Typedef [SharedPtr](../../sharedptr/)
* Class [Object](../../object/)
* Class [String](../../string/)
* Class [EnumValues](../)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)