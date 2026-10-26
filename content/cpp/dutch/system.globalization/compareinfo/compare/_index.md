---
title: Compare()
second_title: Aspose.Slides voor C++ API-referentie
description: Vergelijkt strings. Niet geïmplementeerd.
type: docs
weight: 66
url: /nl/system.globalization/compareinfo/compare/
---
## CompareInfo::Compare(const String\&, const String\&) const methode

Vergelijkt strings. Niet geïmplementeerd.

```cpp
virtual int System::Globalization::CompareInfo::Compare(const String &string1, const String &string2) const
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| string1 | const [String](../../../system/string/)\& | LHS string. |
| string2 | const [String](../../../system/string/)\& | RHS string. |

### Retourwaarde

Negatieve waarde als LHS string vóór RHS string komt, nul als ze gelijk zijn, positieve waarde anders.

## CompareInfo::Compare(const String\&, const String\&, CompareOptions) const methode

Vergelijkt strings. Alleen Ordinal- en OrdinalIgnoreCase-modus worden ondersteund.

```cpp
virtual int System::Globalization::CompareInfo::Compare(const String &a, const String &b, CompareOptions options) const
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| a | const [String](../../../system/string/)\& | LHS string. |
| b | const [String](../../../system/string/)\& | RHS string. |
| options | [CompareOptions](../../compareoptions/) | [String](../../../system/string/) vergelijkingstype. |

### Retourwaarde

Negatieve waarde als LHS string vóór RHS string komt, nul als ze gelijk zijn, positieve waarde anders.

## CompareInfo::Compare(const String\&, int, int, const String\&, int, int) const methode

Vergelijkt een sectie van een string met een sectie van een tweede string. Niet geïmplementeerd.

```cpp
virtual int System::Globalization::CompareInfo::Compare(const String &string1, int offset1, int length1, const String &string2, int offset2, int length2) const
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| string1 | const [String](../../../system/string/)\& | Eerste string. |
| offset1 | int | Startindex van tekens in **string1**. |
| length1 | int | Aantal tekens in **string1** om te vergelijken. |
| string2 | const [String](../../../system/string/)\& | Tweede string. |
| offset2 | int | Startindex van tekens in **string2**. |
| length2 | int | Aantal tekens in **string2** om te vergelijken. |

### Retourwaarde

Negatieve waarde als eerste stringsectie vóór tweede stringsectie komt, nul als ze gelijk zijn, positieve waarde anders.

## CompareInfo::Compare(const String\&, int, const String\&, int, CompareOptions) const methode

Vergelijkt de eindsectie van een string met de eindsectie van een tweede string met behulp van stringvergelijkingsmethoden. Niet geïmplementeerd.

```cpp
virtual int System::Globalization::CompareInfo::Compare(const String &string1, int offset1, const String &string2, int offset2, CompareOptions options) const
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| string1 | const [String](../../../system/string/)\& | Eerste string. |
| offset1 | int | Startindex van tekens in **string1**. |
| string2 | const [String](../../../system/string/)\& | Tweede string. |
| offset2 | int | Startindex van tekens in **string2**. |
| options | [CompareOptions](../../compareoptions/) | [String](../../../system/string/) vergelijkingsopties. |

### Retourwaarde

Negatieve waarde als eerste stringsectie vóór tweede stringsectie komt, nul als ze gelijk zijn, positieve waarde anders.

## CompareInfo::Compare(const String\&, int, const String\&, int) const methode

Vergelijkt de eindsectie van een string met de eindsectie van een tweede string. Niet geïmplementeerd.

```cpp
virtual int System::Globalization::CompareInfo::Compare(const String &string1, int offset1, const String &string2, int offset2) const
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| string1 | const [String](../../../system/string/)\& | Eerste string. |
| offset1 | int | Startindex van tekens in **string1**. |
| string2 | const [String](../../../system/string/)\& | Tweede string. |
| offset2 | int | Startindex van tekens in **string2**. |

### Retourwaarde

Negatieve waarde als eerste stringsectie vóór tweede stringsectie komt, nul als ze gelijk zijn, positieve waarde anders.

## CompareInfo::Compare(const String\&, int, int, const String\&, int, int, CompareOptions) const methode

Vergelijkt een sectie van een string met een sectie van een tweede string met behulp van stringvergelijkingsmethoden. Niet geïmplementeerd.

```cpp
virtual int System::Globalization::CompareInfo::Compare(const String &string1, int offset1, int length1, const String &string2, int offset2, int length2, CompareOptions options) const
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| string1 | const [String](../../../system/string/)\& | Eerste string. |
| offset1 | int | Startindex van tekens in **string1**. |
| length1 | int | Aantal tekens in **string1** om te vergelijken. |
| string2 | const [String](../../../system/string/)\& | Tweede string. |
| offset2 | int | Startindex van tekens in **string2**. |
| length2 | int | Aantal tekens in **string2** om te vergelijken. |
| options | [CompareOptions](../../compareoptions/) | [String](../../../system/string/) vergelijkingsopties. |

### Retourwaarde

Negatieve waarde als eerste stringsectie vóór tweede stringsectie komt, nul als ze gelijk zijn, positieve waarde anders.

## Zie ook

* Enum [CompareOptions](../../compareoptions/)
* Klasse [String](../../../system/string/)
* Klasse [CompareInfo](../)
* Naamruimte [System::Globalization](../../)
* Bibliotheek [Aspose.Slides](../../../)