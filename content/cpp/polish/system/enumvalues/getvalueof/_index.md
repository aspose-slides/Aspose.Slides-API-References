---
title: GetValueOf()
second_title: Odwołanie API Aspose.Slides dla C++
description: Zwraca wartość opakowaną stałej wyliczeniowej o podanej nazwie.
type: docs
weight: 53
url: /pl/system/enumvalues/getvalueof/
---
## EnumValues::GetValueOf(const String\&, bool) const metoda


Zwraca wartość opakowaną stałej wyliczeniowej o określonej nazwie.

```cpp
virtual SharedPtr<Object> System::EnumValues<E, Guard>::GetValueOf(const String &str, bool ignoreCase) const override
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| str | const [String](../../string/)\& | Nazwa stałej wyliczeniowej |
| ignoreCase | **bool** | Określa, czy przy interpretacji nazwy stałej wyliczeniowej ma być ignorowana wielkość liter |

### Wartość zwracana

Wartość opakowana stałej wyliczeniowej, której nazwa jest podana w **str**.

## EnumValues::GetValueOf(long) const metoda


Zwraca wartość opakowaną stałej wyliczeniowej o określonej wartości.

```cpp
virtual SharedPtr<Object> System::EnumValues<E, Guard>::GetValueOf(long val) const override
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| val | long | Wartość stałej wyliczeniowej |

### Wartość zwracana

Wartość opakowana stałej wyliczeniowej, której wartość jest podana w **str**.

## Zobacz także

* Typedef [SharedPtr](../../sharedptr/)
* Class [Object](../../object/)
* Class [String](../../string/)
* Class [EnumValues](../)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)