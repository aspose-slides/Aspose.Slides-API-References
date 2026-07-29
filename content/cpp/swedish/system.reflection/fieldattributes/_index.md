---
title: FieldAttributes
second_title: Aspose.Slides för C++ API-referens
description: Reflekterade fältattribut.
type: docs
weight: 170
url: /sv/system.reflection/fieldattributes/
---
## FieldAttributes enum

Reflekterade fältattribut.

```cpp
enum class FieldAttributes
```

### Värden

| Namn | Värde | Beskrivning |
| --- | --- | --- |
| FieldAccessMask | 7 | Mask för medlemsåtkomst. Använd denna mask för att hämta åtkomstinformation. |
| PrivateScope | 0 | Icke-refererbara medlemmar. |
| Private | 1 | Privata medlemmar. |
| FamANDAssem | 2 | Privata medlemmar med assembly-omfång. |
| Assembly | 3 | Medlemmar med assembly-omfång. |
| Family | 4 | Medlemmar som är åtkomliga av typ och undertyper. |
| FamORAssem | 5 | Medlemmar som är åtkomliga av typ, undertyper och assembly. |
| Public | 6 | Medlemmar som är åtkomliga av alla. |
| Static | 16 | Statiska medlemmar i motsats till instansmedlemmar. |
| InitOnly | 32 | Konstanta medlemmar som bara kan initieras men inte ändras. |
| Literal | 64 | Medlemmar som är konstant vid kompilering. |
| NotSerialized | 128 | Medlemmar som inte serialiseras. |
| SpecialName | 512 | Specialfält med ett av namnen nedan. |
| PinvokeImpl | 8192 | Interop vidarebefordrad implementation. |
| ReservedMask | 38144 | Reserverade flaggor enbart för körning. |
| RTSpecialName | 1024 | Runtime bör kontrollera namnkodning. |
| HasFieldMarshal | 4096 | Marshallningsinformation finns. |
| HasDefault | 32768 | Standardvärde finns. |
| HasFieldRVA | 256 | RVA finns. |

## Se också

* Namnrymd [System::Reflection](../)
* Bibliotek [Aspose.Slides](../../)