---
title: GetValueOf()
second_title: Aspose.Slides för C++ API-referens
description: Returnerar det inloppade värdet av enum-konstanten med det angivna namnet.
type: docs
weight: 53
url: /sv/system/enumvalues/getvalueof/
---
## EnumValues::GetValueOf(const String\&, bool) const metod

Returnerar det inloppade värdet av enum-konstanten med det angivna namnet.

```cpp
virtual SharedPtr<Object> System::EnumValues<E, Guard>::GetValueOf(const String &str, bool ignoreCase) const override
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| str | const [String](../../string/)\& | Namnet på enum-konstanten |
| ignoreCase | **bool** | Anger om skiftläget ska ignoreras när namnet på enum-konstanten tolkas |

### Returvärde

Ett inloppat värde av enum-konstanten vars namn anges i **str**.

## EnumValues::GetValueOf(long) const metod

Returnerar det inloppade värdet av enum-konstanten med det angivna värdet.

```cpp
virtual SharedPtr<Object> System::EnumValues<E, Guard>::GetValueOf(long val) const override
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| val | long | Värdet av enum-konstanten |

### Returvärde

Ett inloppat värde av enum-konstanten vars värde anges i **str**.

## Se även

* Typedef [SharedPtr](../../sharedptr/)
* Klass [Object](../../object/)
* Klass [String](../../string/)
* Klass [EnumValues](../)
* Namnrymd [System](../../)
* Bibliotek [Aspose.Slides](../../../)