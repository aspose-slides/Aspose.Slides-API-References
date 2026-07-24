---
title: Compare()
second_title: Aspose.Slides für C++ API-Referenz
description: Vergleicht Zeichenketten. Nicht implementiert.
type: docs
weight: 66
url: /de/system.globalization/compareinfo/compare/
---
## CompareInfo::Compare(const String\&, const String\&) const Methode

Vergleicht Zeichenketten. Nicht implementiert.

```cpp
virtual int System::Globalization::CompareInfo::Compare(const String &string1, const String &string2) const
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| string1 | const [String](../../../system/string/)\& | Linker String. |
| string2 | const [String](../../../system/string/)\& | Rechter String. |

### Rückgabewert

Negativer Wert, wenn der linke String dem rechten vorausgeht, null, wenn sie übereinstimmen, sonst ein positiver Wert.

## CompareInfo::Compare(const String\&, const String\&, CompareOptions) const Methode

Vergleicht Zeichenketten. Nur die Modi Ordinal und OrdinalIgnoreCase werden unterstützt.

```cpp
virtual int System::Globalization::CompareInfo::Compare(const String &a, const String &b, CompareOptions options) const
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| a | const [String](../../../system/string/)\& | Linker String. |
| b | const [String](../../../system/string/)\& | Rechter String. |
| options | [CompareOptions](../../compareoptions/) | [String](../../../system/string/) Vergleichstyp. |

### Rückgabewert

Negativer Wert, wenn der linke String dem rechten vorausgeht, null, wenn sie übereinstimmen, sonst ein positiver Wert.

## CompareInfo::Compare(const String\&, int, int, const String\&, int, int) const Methode

Vergleicht einen Abschnitt einer Zeichenkette mit einem Abschnitt einer zweiten Zeichenkette. Nicht implementiert.

```cpp
virtual int System::Globalization::CompareInfo::Compare(const String &string1, int offset1, int length1, const String &string2, int offset2, int length2) const
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| string1 | const [String](../../../system/string/)\& | Erster String. |
| offset1 | int | Startindex der Zeichen in **string1**. |
| length1 | int | Anzahl der Zeichen in **string1**, die zu vergleichen sind. |
| string2 | const [String](../../../system/string/)\& | Zweiter String. |
| offset2 | int | Startindex der Zeichen in **string2**. |
| length2 | int | Anzahl der Zeichen in **string2**, die zu vergleichen sind. |

### Rückgabewert

Negativer Wert, wenn der erste Abschnitt der Zeichenkette dem zweiten Abschnitt der Zeichenkette vorausgeht, null, wenn sie übereinstimmen, sonst ein positiver Wert.

## CompareInfo::Compare(const String\&, int, const String\&, int, CompareOptions) const Methode

Vergleicht den Endabschnitt einer Zeichenkette mit dem Endabschnitt einer zweiten Zeichenkette mittels Zeichenkettenvergleichsmethoden. Nicht implementiert.

```cpp
virtual int System::Globalization::CompareInfo::Compare(const String &string1, int offset1, const String &string2, int offset2, CompareOptions options) const
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| string1 | const [String](../../../system/string/)\& | Erster String. |
| offset1 | int | Startindex der Zeichen in **string1**. |
| string2 | const [String](../../../system/string/)\& | Zweiter String. |
| offset2 | int | Startindex der Zeichen in **string2**. |
| options | [CompareOptions](../../compareoptions/) | [String](../../../system/string/) Vergleichsoptionen. |

### Rückgabewert

Negativer Wert, wenn der erste Abschnitt der Zeichenkette dem zweiten Abschnitt der Zeichenkette vorausgeht, null, wenn sie übereinstimmen, sonst ein positiver Wert.

## CompareInfo::Compare(const String\&, int, const String\&, int) const Methode

Vergleicht den Endabschnitt einer Zeichenkette mit dem Endabschnitt einer zweiten Zeichenkette. Nicht implementiert.

```cpp
virtual int System::Globalization::CompareInfo::Compare(const String &string1, int offset1, const String &string2, int offset2) const
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| string1 | const [String](../../../system/string/)\& | Erster String. |
| offset1 | int | Startindex der Zeichen in **string1**. |
| string2 | const [String](../../../system/string/)\& | Zweiter String. |
| offset2 | int | Startindex der Zeichen in **string2**. |

### Rückgabewert

Negativer Wert, wenn der erste Abschnitt der Zeichenkette dem zweiten Abschnitt der Zeichenkette vorausgeht, null, wenn sie übereinstimmen, sonst ein positiver Wert.

## CompareInfo::Compare(const String\&, int, int, const String\&, int, int, CompareOptions) const Methode

Vergleicht einen Abschnitt einer Zeichenkette mit einem Abschnitt einer zweiten Zeichenkette mittels Zeichenkettenvergleichsmethoden. Nicht implementiert.

```cpp
virtual int System::Globalization::CompareInfo::Compare(const String &string1, int offset1, int length1, const String &string2, int offset2, int length2, CompareOptions options) const
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| string1 | const [String](../../../system/string/)\& | Erster String. |
| offset1 | int | Startindex der Zeichen in **string1**. |
| length1 | int | Anzahl der Zeichen in **string1**, die zu vergleichen sind. |
| string2 | const [String](../../../system/string/)\& | Zweiter String. |
| offset2 | int | Startindex der Zeichen in **string2**. |
| length2 | int | Anzahl der Zeichen in **string2**, die zu vergleichen sind. |
| options | [CompareOptions](../../compareoptions/) | [String](../../../system/string/) Vergleichsoptionen. |

### Rückgabewert

Negativer Wert, wenn der erste Abschnitt der Zeichenkette dem zweiten Abschnitt der Zeichenkette vorausgeht, null, wenn sie übereinstimmen, sonst ein positiver Wert.

## Siehe auch

* Enum [CompareOptions](../../compareoptions/)
* Class [String](../../../system/string/)
* Class [CompareInfo](../)
* Namespace [System::Globalization](../../)
* Library [Aspose.Slides](../../../)