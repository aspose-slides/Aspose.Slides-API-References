---
title: GetDigitValue()
second_title: Aspose.Slides för C++ API-referens
description: Hämtar siffravärdet för det angivna tecknet.
type: docs
weight: 14
url: /sv/system.globalization/charunicodeinfo/getdigitvalue/
---
## CharUnicodeInfo::GetDigitValue(char16_t) metod

Hämtar siffravärdet för det angivna tecknet.

```cpp
static int System::Globalization::CharUnicodeInfo::GetDigitValue(char16_t ch)
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| ch | char16_t | Unicode-tecken. |

### Returvärde

Siffravärdet eller -1 om det angivna tecknet inte är en siffra.

## CharUnicodeInfo::GetDigitValue(const String\&, int) metod

Hämtar siffravärdet för tecknet på det angivna indexet i strängen.

```cpp
static int System::Globalization::CharUnicodeInfo::GetDigitValue(const String &str, int index)
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| str | const [String](../../../system/string/)\& | Strängen som innehåller unicode-tecken. |
| index | int | Indexet för unicode-tecknet. |

### Returvärde

Siffravärdet eller -1 om det angivna tecknet inte är en siffra.

## Se även

* Klass [CharUnicodeInfo](../)
* Klass [String](../../../system/string/)
* Namnrymd [System::Globalization](../../)
* Bibliotek [Aspose.Slides](../../../)