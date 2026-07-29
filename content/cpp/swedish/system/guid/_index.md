---
title: Guid
second_title: Aspose.Slides för C++ API-referens
description: "Representerar en globalt unik identifierare. Denna typ bör allokeras på stacken och skickas till funktioner som värde eller referens. Använd aldrig System::SmartPtr-klassen för att hantera objekt av denna typ."
type: docs
weight: 885
url: /sv/system/guid/
---
## Guid klass

Representerar en globalt unik identifierare som bör allokeras på stacken och skickas till funktioner som värde eller referens. Använd aldrig [System::SmartPtr](../smartptr/)-klassen för att hantera objekt av denna typ.

```cpp
class Guid
```

## Metoder

| Metod | Beskrivning |
| --- | --- |
| int [CompareTo](./compareto/)(const [Guid](./)\&) const | Utför aritmetisk jämförelse av de GUID:er som representeras av det aktuella och det angivna objektet. |
| **bool** [Equals](./equals/)(const [Guid](./)\&) const | Avgör om de GUID:er som representeras av det aktuella och det angivna objektet är lika. |
| int [GetHashCode](./gethashcode/)() const | Returnerar en hashkod för det aktuella objektet. |
|  [Guid](./guid/)() | Skapar ett objekt som representerar ett GUID bestående av enbart nollor. |
|  [Guid](./guid/)(const [ArrayPtr](../arrayptr/)\<**uint8_t**\>\&) | Skapar ett objekt som representerar ett GUID specificerat som en array av osignerade 8-bitars heltal. |
|  [Guid](./guid/)(const System::Details::ArrayView\<**uint8_t**\>\&) | Skapar ett objekt som representerar ett GUID specificerat som en arrayvy av osignerade 8-bitars heltal. |
|  [Guid](./guid/)(const [String](../string/)\&) | Skapar ett objekt som representerar ett GUID specificerat som en sträng. |
|  [Guid](./guid/)(**int32_t**, **int16_t**, **int16_t**, const [ArrayPtr](../arrayptr/)\<**uint8_t**\>\&) | Skapar en instans av [Guid](./) klass från de specificerade GUID-komponenterna. |
|  [Guid](./guid/)(**int32_t**, **int16_t**, **int16_t**, const System::Details::ArrayView\<**uint8_t**\>\&) | Skapar en instans av [Guid](./) klass från de specificerade GUID-komponenterna. |
|  [Guid](./guid/)(**int32_t**, **int16_t**, **int16_t**, **uint8_t**, **uint8_t**, **uint8_t**, **uint8_t**, **uint8_t**, **uint8_t**, **uint8_t**, **uint8_t**) | Skapar en instans av [Guid](./) klass från de specificerade osignerade heltalen och byten. |
|  [Guid](./guid/)(**uint32_t**, **uint16_t**, **uint16_t**, **uint8_t**, **uint8_t**, **uint8_t**, **uint8_t**, **uint8_t**, **uint8_t**, **uint8_t**, **uint8_t**) | Skapar en instans av [Guid](./) klass från de specificerade osignerade heltalen och byten. |
|  [Guid](./guid/)(const [Guid](./)\&) | Skapar ett objekt som representerar samma GUID som det specificerade objektet. |
| static [Guid](./) [NewGuid](./newguid/)() | Genererar ett nytt GUID och returnerar ett [Guid](./)-objekt som representerar det. |
| **bool** [operator!=](./operator_not_equal/)(const [Guid](./)\&) const | Avgör om de GUID:er som representeras av det aktuella och det angivna objektet inte är lika. |
| [Guid](./)\& [operator=](./operator_equal/)(const [Guid](./)\&) | Tilldelar det aktuella objektet GUID-värdet som representeras av det specificerade [Guid](./)-objektet. |
| **bool** [operator==](./operator_equal_equal/)(const [Guid](./)\&) const | Avgör om de GUID:er som representeras av det aktuella och det angivna objektet är lika. |
| static [Guid](./) [Parse](./parse/)(const [String](../string/)\&) | Konverterar den specificerade strängrepresentationen av ett GUID till motsvarande [Guid](./)-objekt. |
| [ArrayPtr](../arrayptr/)\<**uint8_t**\> [ToByteArray](./tobytearray/)() const | Konverterar GUID:et som representeras av det aktuella objektet till en array av byte. |
| [String](../string/) [ToString](./tostring/)() const | Konverterar GUID:et som representeras av det aktuella objektet till dess strängrepresentation. |
| [String](../string/) [ToString](./tostring/)(const [String](../string/)\&) const | Konverterar GUID:et som representeras av det aktuella objektet till dess strängrepresentation med det specificerade strängformatet. |
| [String](../string/) [ToString](./tostring/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) const | Konverterar GUID:et som representeras av det aktuella objektet till dess strängrepresentation med det specificerade strängformatet och kultur. |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, [Guid](./)\&) | Försöker konvertera den specificerade strängen till ett [Guid](./)-objekt. |
|  [~Guid](./~guid/)() | Destruktor. |

## Fält

| Fält | Beskrivning |
| --- | --- |
| static [Empty](./empty/) | Representerar ett GUID som har värdet 0. |

## Se även

* Namnrymd [System](../)
* Bibliotek [Aspose.Slides](../../)