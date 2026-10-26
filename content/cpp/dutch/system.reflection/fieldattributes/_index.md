---
title: FieldAttributes
second_title: Aspose.Slides voor C++ API-referentie
description: Gereflecteerde veldkenmerken.
type: docs
weight: 170
url: /nl/system.reflection/fieldattributes/
---
## FieldAttributes enum


Gereflecteerde veldkenmerken.

```cpp
enum class FieldAttributes
```

### Waarden

| Naam | Waarde | Beschrijving |
| --- | --- | --- |
| FieldAccessMask | 7 | Lidtoegangsmasker. Gebruik dit masker om toegankelijkheidsinformatie op te halen. |
| PrivateScope | 0 | Niet-referentieerbare leden. |
| Private | 1 | Privéleden. |
| FamANDAssem | 2 | Privé- en assembly-gebonden leden. |
| Assembly | 3 | Assembly-gebonden leden. |
| Family | 4 | Leden toegankelijk via type en subtypes. |
| FamORAssem | 5 | Leden toegankelijk via type, subtypes en assembly. |
| Public | 6 | Leden toegankelijk voor iedereen. |
| Static | 16 | Statische leden in tegenstelling tot instantie-leden. |
| InitOnly | 32 | Constante leden die alleen kunnen worden geïnitialiseerd maar niet kunnen worden gewijzigd. |
| Literal | 64 | Compile-tijd constante leden. |
| NotSerialized | 128 | Niet-geserializeerde leden. |
| SpecialName | 512 | Speciaal veld met een van de onderstaande namen. |
| PinvokeImpl | 8192 | Interop-doorgestuurde implementatie. |
| ReservedMask | 38144 | Gereserveerde vlaggen uitsluitend voor runtime-gebruik. |
| RTSpecialName | 1024 | Runtime moet naamcodering controleren. |
| HasFieldMarshal | 4096 | Marshalling-informatie is aanwezig. |
| HasDefault | 32768 | Standaardwaarde is aanwezig. |
| HasFieldRVA | 256 | RVA is aanwezig. |

## Zie ook

* Naamruimte [System::Reflection](../)
* Bibliotheek [Aspose.Slides](../../)