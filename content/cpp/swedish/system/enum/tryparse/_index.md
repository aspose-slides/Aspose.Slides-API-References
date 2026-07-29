---
title: TryParse()
second_title: Aspose.Slides för C++ API-referens
description: Försöker konvertera den angivna strängen till motsvarande enum-konstant.
type: docs
weight: 79
url: /sv/system/enum/tryparse/
---
## Enum::TryParse(const String\&, E\&) metod


Försöker konvertera den angivna strängen till motsvarande enum-konstant.

```cpp
static bool System::Enum<E, Guard>::TryParse(const String &str, E &result)
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| str | const [String](../../string/)\& | [String](../../string/) som tolkas som innehållande namnet på enum-konstanten |
| result | E\& | Den utdata-parametern som, om konverteringen lyckas, innehåller resultatet av konverteringen på funktionen |

### Returvärde

True om konverteringen lyckades, annars - false

## Enum::TryParse(const String\&, bool, E\&) metod


Försöker konvertera den angivna strängen till motsvarande enum-konstant.

```cpp
static bool System::Enum<E, Guard>::TryParse(const String &str, bool ignoreCase, E &result)
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| str | const [String](../../string/)\& | [String](../../string/) som tolkas som innehållande namnet på enum-konstanten |
| ignoreCase | **bool** | Anger om skiftläget ska ignoreras när strängen tolkas |
| result | E\& | Den utdata-parametern som, om konverteringen lyckas, innehåller resultatet av konverteringen vid funktionsretur |

### Returvärde

True om konverteringen lyckades, annars - false

## Se också

* Klass [String](../../string/)
* Struktur [Enum](../)
* Namnrymd [System](../../)
* Bibliotek [Aspose.Slides](../../../)