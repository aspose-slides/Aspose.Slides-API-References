---
title: Parse()
second_title: Aspose.Slides für C++ API-Referenz
description: Kapselt den Wert der Aufzählungskonstanten der angegebenen Aufzählung mit dem angegebenen Namen. Ein Parameter gibt an, ob die Groß- und Kleinschreibung ignoriert werden soll, wenn die Zeichenfolge, die den Namen der Aufzählungskonstanten angibt, interpretiert wird.
type: docs
weight: 53
url: /de/system/boxedvaluebase/parse/
---
## BoxedValueBase::Parse(const TypeInfo\&, const String\&, bool) Methode

Kapselt den Wert der Aufzählungskonstanten der angegebenen Aufzählung mit dem angegebenen Namen. Ein Parameter gibt an, ob die Groß- und Kleinschreibung ignoriert werden soll, wenn die Zeichenfolge, die den Namen der Aufzählungskonstanten angibt, interpretiert wird.

```cpp
static SharedPtr<Object> System::BoxedValueBase::Parse(const TypeInfo &type, const String &str, bool ignoreCase)
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| type | const [TypeInfo](../../typeinfo/)\& | Gibt den Typ der Aufzählung an |
| str | const [String](../../string/)\& | Der Name der Aufzählungskonstanten, deren Wert gekapselt werden soll |
| ignoreCase | **bool** | Gibt an, ob die Groß- und Kleinschreibung ignoriert werden soll, wenn die Zeichenfolge, die den Namen der Aufzählungskonstanten darstellt, interpretiert wird |

### Rückgabewert

Ein Shared-Pointer auf das Objekt, das den gekapselten Wert der angegebenen Aufzählungskonstanten darstellt.

## BoxedValueBase::Parse(const TypeInfo\&, const String\&) Methode

Kapselt den Wert der Aufzählungskonstanten der angegebenen Aufzählung mit dem angegebenen Namen.

```cpp
static SharedPtr<Object> System::BoxedValueBase::Parse(const TypeInfo &type, const String &str)
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| type | const [TypeInfo](../../typeinfo/)\& | Gibt den Typ der Aufzählung an |
| str | const [String](../../string/)\& | Der Name der Aufzählungskonstanten, deren Wert gekapselt werden soll |

### Rückgabewert

Ein Shared-Pointer auf das Objekt, das den gekapselten Wert der angegebenen Aufzählungskonstanten darstellt.

## Siehe auch

* Typedef [SharedPtr](../../sharedptr/)
* Klasse [Object](../../object/)
* Klasse [TypeInfo](../../typeinfo/)
* Klasse [String](../../string/)
* Klasse [BoxedValueBase](../)
* Namensraum [System](../../)
* Library [Aspose.Slides](../../../)