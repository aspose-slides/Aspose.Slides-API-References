---
title: Guid
second_title: Aspose.Slides pro C++ API Reference
description: "Reprezentuje globálně jedinečný identifikátor. Tento typ by měl být alokován na zásobníku a předáván funkcím hodnotou nebo referencí. Nikdy nepoužívejte System::SmartPtr třídu pro správu objektů tohoto typu."
type: docs
weight: 885
url: /cs/system/guid/
---
## Guid třída

Reprezentuje globálně jedinečný identifikátor. Tento typ by měl být alokován na zásobníku a předáván funkcím hodnotou nebo referencí. Nikdy nepoužívejte třídu [System::SmartPtr](../smartptr/) pro správu objektů tohoto typu.

```cpp
class Guid
```

## Metody

| Metoda | Popis |
| --- | --- |
| int [CompareTo](./compareto/)(const [Guid](./)\&) const | Provádí aritmetické porovnání GUIDů reprezentovaných aktuálním a specifikovaným objektem. |
| **bool** [Equals](./equals/)(const [Guid](./)\&) const | Určuje, zda GUIDy reprezentované aktuálním a specifikovaným objektem jsou rovny. |
| int [GetHashCode](./gethashcode/)() const | Vrací hash kód pro aktuální objekt. |
|  [Guid](./guid/)() | Vytvoří objekt, který představuje GUID složený ze všech nul. |
|  [Guid](./guid/)(const [ArrayPtr](../arrayptr/)\<**uint8_t**\>\&) | Vytvoří objekt, který představuje GUID specifikovaný jako pole nezáporných 8-bitových celých čísel. |
|  [Guid](./guid/)(const System::Details::ArrayView\<**uint8_t**\>\&) | Vytvoří objekt, který představuje GUID specifikovaný jako pohled na pole nezáporných 8-bitových celých čísel. |
|  [Guid](./guid/)(const [String](../string/)\&) | Vytvoří objekt, který představuje GUID specifikovaný jako řetězec. |
|  [Guid](./guid/)(**int32_t**, **int16_t**, **int16_t**, const [ArrayPtr](../arrayptr/)\<**uint8_t**\>\&) | Vytvoří instanci třídy [Guid](./) z uvedených komponent GUID. |
|  [Guid](./guid/)(**int32_t**, **int16_t**, **int16_t**, const System::Details::ArrayView\<**uint8_t**\>\&) | Vytvoří instanci třídy [Guid](./) z uvedených komponent GUID. |
|  [Guid](./guid/)(**int32_t**, **int16_t**, **int16_t**, **uint8_t**, **uint8_t**, **uint8_t**, **uint8_t**, **uint8_t**, **uint8_t**, **uint8_t**, **uint8_t**) | Vytvoří instanci třídy [Guid](./) z uvedených nezáporných celých čísel a bajtů. |
|  [Guid](./guid/)(**uint32_t**, **uint16_t**, **uint16_t**, **uint8_t**, **uint8_t**, **uint8_t**, **uint8_t**, **uint8_t**, **uint8_t**, **uint8_t**, **uint8_t**) | Vytvoří instanci třídy [Guid](./) z uvedených nezáporných celých čísel a bajtů. |
|  [Guid](./guid/)(const [Guid](./)\&) | Vytvoří objekt, který představuje stejný GUID jako specifikovaný objekt. |
| static [Guid](./) [NewGuid](./newguid/)() | Vygeneruje nový GUID a vrátí objekt [Guid](./), který jej představuje. |
| **bool** [operator!=](./operator_not_equal/)(const [Guid](./)\&) const | Určuje, zda GUIDy reprezentované aktuálním a specifikovaným objektem nejsou rovny. |
| [Guid](./)\& [operator=](./operator_equal/)(const [Guid](./)\&) | Přiřadí aktuálnímu objektu GUID hodnotu reprezentovanou specifikovaným objektem [Guid](./). |
| **bool** [operator==](./operator_equal_equal/)(const [Guid](./)\&) const | Určuje, zda GUIDy reprezentované aktuálním a specifikovaným objektem jsou rovny. |
| static [Guid](./) [Parse](./parse/)(const [String](../string/)\&) | Převede specifikovanou řetězcovou reprezentaci GUIDu na ekvivalentní objekt [Guid](./). |
| [ArrayPtr](../arrayptr/)\<**uint8_t**\> [ToByteArray](./tobytearray/)() const | Převede GUID reprezentovaný aktuálním objektem na pole bajtů. |
| [String](../string/) [ToString](./tostring/)() const | Převede GUID reprezentovaný aktuálním objektem na jeho řetězcovou reprezentaci. |
| [String](../string/) [ToString](./tostring/)(const [String](../string/)\&) const | Převede GUID reprezentovaný aktuálním objektem na jeho řetězcovou reprezentaci pomocí specifikovaného formátu řetězce. |
| [String](../string/) [ToString](./tostring/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) const | Převede GUID reprezentovaný aktuálním objektem na jeho řetězcovou reprezentaci pomocí specifikovaného formátu řetězce a kultury. |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, [Guid](./)\&) | Pokouší se převést specifikovaný řetězec na objekt [Guid](./). |
|  [~Guid](./~guid/)() | Destruktor. |

## Pole

| Pole | Popis |
| --- | --- |
| static [Empty](./empty/) | Reprezentuje GUID, jehož hodnota je 0. |

## Viz také

* Jmenný prostor [System](../)
* Knihovna [Aspose.Slides](../../)