---
title: GetNumericValue()
second_title: Aspose.Slides för C++ API-referens
description: Hämtar det numeriska värdet som är associerat med det angivna tecknet.
type: docs
weight: 27
url: /sv/system.globalization/charunicodeinfo/getnumericvalue/
---
## CharUnicodeInfo::GetNumericValue(char16_t) metod


Hämtar det numeriska värdet som är associerat med det angivna tecknet.

```cpp
static double System::Globalization::CharUnicodeInfo::GetNumericValue(char16_t ch)
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| ch | char16_t | Unicode-tecken. |

### Returvärde

Det numeriska värdet eller -1 om det angivna tecknet inte är ett numeriskt tecken.

## CharUnicodeInfo::GetNumericValue(const String\&, int) metod


Hämtar det numeriska värdet som är associerat med tecknet på det angivna indexet i strängen.

```cpp
static double System::Globalization::CharUnicodeInfo::GetNumericValue(const String &str, int index)
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| str | const [String](../../../system/string/)\& | Strängen som innehåller unicode-tecken. |
| index | int | Indexet för unicode-tecknet. |

### Returvärde

Det numeriska värdet eller -1 om det angivna tecknet inte är ett numeriskt tecken.

## Se även

* Klass [CharUnicodeInfo](../)
* Klass [String](../../../system/string/)
* Namnrymd [System::Globalization](../../)
* Bibliotek [Aspose.Slides](../../../)