---
title: EndsWith()
second_title: Aspose.Slides för C++ API-referens
description: Kontrollerar om strängen slutar med angiven delsträng.
type: docs
weight: 482
url: /sv/system/string/endswith/
---
## String::EndsWith(const String\&) const metod


Kontrollerar om strängen slutar med angiven delsträng.

```cpp
bool System::String::EndsWith(const String &value) const
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | const [String](../)\& | Söksträng. |

### Returvärde

true om strängen slutar med angiven delsträng, false annars.

## String::EndsWith(const String\&, System::StringComparison) const metod


Kontrollerar om strängen slutar med angiven delsträng.

```cpp
bool System::String::EndsWith(const String &value, System::StringComparison comparisonType) const
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | const [String](../)\& | Söksträng. |
| comparisonType | [System::StringComparison](../../stringcomparison/) | [Comparison](../../comparison/) läge, se [System::StringComparison](../../stringcomparison/) för detaljer. |

### Returvärde

true om strängen slutar med angiven delsträng, false annars.

## String::EndsWith(const String\&, bool, const SharedPtr\<System::Globalization::CultureInfo\>\&) const metod


Kontrollerar om strängen slutar med angiven delsträng.

```cpp
bool System::String::EndsWith(const String &value, bool ignoreCase, const SharedPtr<System::Globalization::CultureInfo> &culture=nullptr) const
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | const [String](../)\& | Söksträng. |
| ignoreCase | **bool** | Anger om jämförelsen är skiftlägesokänslig. |
| culture | const [SharedPtr](../../sharedptr/)\<[System::Globalization::CultureInfo](../../../system.globalization/cultureinfo/)\>\& | Kultur som ska användas vid strängjämförelse. |

### Returvärde

true om strängen slutar med angiven delsträng, false annars.

## Se även

* Enum [StringComparison](../../stringcomparison/)
* Typedef [SharedPtr](../../sharedptr/)
* klass [String](../)
* klass [CultureInfo](../../../system.globalization/cultureinfo/)
* namnrymd [System](../../)
* Library [Aspose.Slides](../../../)