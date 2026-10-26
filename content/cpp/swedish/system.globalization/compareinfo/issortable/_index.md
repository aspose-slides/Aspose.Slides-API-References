---
title: IsSortable()
second_title: Aspose.Slides för C++ API-referens
description: Kontrollerar om ett angivet tecken är sorteringsbart.
type: docs
weight: 196
url: /sv/system.globalization/compareinfo/issortable/
---
## CompareInfo::IsSortable(char16_t) metod


Kontrollerar om ett angivet tecken är sorteringsbart.

```cpp
static bool System::Globalization::CompareInfo::IsSortable(char16_t ch)
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| ch | char16_t | Unicode-tecken. |

### Returvärde

Sant om **ch** är sorteringsbart; annars falskt.

## CompareInfo::IsSortable(const String\&) metod


Kontrollerar om en angiven sträng är sorteringsbar.

```cpp
static bool System::Globalization::CompareInfo::IsSortable(const String &text)
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| text | const [String](../../../system/string/)\& | En sträng. |

### Returvärde

Sant om **text** inte är tom och alla tecken i **text** är sorteringsbara; annars falskt.

## Se även

* Klass [CompareInfo](../)
* Klass [String](../../../system/string/)
* Namnrymd [System::Globalization](../../)
* Bibliotek [Aspose.Slides](../../../)