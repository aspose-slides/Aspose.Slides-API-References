---
title: HolderInitializer
second_title: Aspose.Slides för C++ API-referens
description: Denna klass används för att få en bestående referens till objektinstansen, oavsett om det är ett lvalue eller rvalue. För att erhålla en sådan referens, använd metoden 'HoldIfTemporary' som har tre överlagringar. Två av dem tar ett rvalue som parameter och returnerar bara referensen till det. Den tredje, i motsats, tar ett lvalue som parameter, gör en pekarkopia och returnerar referensen till den kopian. Klassen har också metoden 'Hold' för att hålla det passerade värdet ovillkorligt (används för att kopiera värden från lokala stackvariabler eller deras underreferenser)
type: docs
weight: 1639
url: /sv/system/holderinitializer/
---
## HolderInitializer struct

Denna klass används för att få en bestående referens till objektinstansen, oavsett om det är ett lvalue eller rvalue. För att erhålla en sådan referens, använd metoden 'HoldIfTemporary' som har tre överlagringar. Två av dem tar ett rvalue som parameter och returnerar bara referensen till det. Den tredje, i motsats, tar ett lvalue som parameter, gör en pekarkopia och returnerar referensen till den kopian. Klassen har också metoden 'Hold' för att hålla det passerade värdet ovillkorligt (används för att kopiera värden från lokala stackvariabler eller deras underreferenser).

```cpp
template<typename T,bool>class HolderInitializer
```

### Mallparametrar

| Parameter | Beskrivning |
| --- | --- |
| T | Typen på objektet som ska hållas. |
| R | True, om T är en referenstyp ([SmartPtr](../smartptr/) specialisering eller [System::String](../string/) typ), och tillfälliga referenser faktiskt måste hållas, annars false. |

## Metoder

| Metod | Beskrivning |
| --- | --- |
| const T\& [Hold](./hold/)(const T\&) | Kopierar passerat lvalue till hållaren och returnerar sedan referensen till hållaren. Anroparen bör använda denna metod för att ovillkorligt hålla det passerade värdet. |
|  [HolderInitializer](./holderinitializer/)(T\&) | Initierar hållarreferensen med det passerade värdet. |
| const T\& [HoldIfTemporary](./holdiftemporary/)(const T\&) | Returnerar referens till rvalue (const) |
| const T\& [HoldIfTemporary](./holdiftemporary/)(T\&) | Returnerar referens till rvalue (icke-const) |
| const T\& [HoldIfTemporary](./holdiftemporary/)(T\&&) | Kopierar passerat lvalue till hållaren och returnerar sedan referensen till hållaren. |

## Se även

* Namnrymd [System](../)
* Bibliotek [Aspose.Slides](../../)