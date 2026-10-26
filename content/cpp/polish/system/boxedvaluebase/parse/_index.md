---
title: Parse()
second_title: Aspose.Slides dla C++ – Dokumentacja API
description: Opakowuje wartość stałej wyliczeniowej określonego wyliczenia o podanej nazwie. Parametr określa, czy wielkość liter ma być ignorowana podczas interpretacji łańcucha określającego nazwę stałej wyliczeniowej.
type: docs
weight: 53
url: /pl/system/boxedvaluebase/parse/
---
## BoxedValueBase::Parse(const TypeInfo\&, const String\&, bool) metoda

Opakowuje wartość stałej wyliczeniowej określonego wyliczenia o podanej nazwie. Parametr określa, czy wielkość liter ma być ignorowana podczas interpretacji łańcucha określającego nazwę stałej wyliczeniowej.

```cpp
static SharedPtr<Object> System::BoxedValueBase::Parse(const TypeInfo &type, const String &str, bool ignoreCase)
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| type | const [TypeInfo](../../typeinfo/)\& | Określa typ wyliczenia |
| str | const [String](../../string/)\& | Nazwa stałej wyliczeniowej, której wartość ma zostać opakowana |
| ignoreCase | **bool** | Określa, czy wielkość liter ma być ignorowana podczas interpretacji łańcucha reprezentującego nazwę stałej wyliczeniowej |

### Wartość zwracana

Współdzielony wskaźnik do obiektu reprezentującego opakowaną wartość określonej stałej wyliczeniowej

## BoxedValueBase::Parse(const TypeInfo\&, const String\&) metoda

Opakowuje wartość stałej wyliczeniowej określonego wyliczenia o podanej nazwie.

```cpp
static SharedPtr<Object> System::BoxedValueBase::Parse(const TypeInfo &type, const String &str)
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| type | const [TypeInfo](../../typeinfo/)\& | Określa typ wyliczenia |
| str | const [String](../../string/)\& | Nazwa stałej wyliczeniowej, której wartość ma zostać opakowana |

### Wartość zwracana

Współdzielony wskaźnik do obiektu reprezentującego opakowaną wartość określonej stałej wyliczeniowej

## Zobacz również

* Typedef [SharedPtr](../../sharedptr/)
* Klasa [Object](../../object/)
* Klasa [TypeInfo](../../typeinfo/)
* Klasa [String](../../string/)
* Klasa [BoxedValueBase](../)
* Przestrzeń nazw [System](../../)
* Library [Aspose.Slides](../../../)