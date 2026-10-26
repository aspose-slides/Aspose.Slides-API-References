---
title: Size
second_title: Aspose.Slides för C++ API-referens
description: "Representerar ett par heltal som representerar bredd och höjd på en bild. Denna typ bör allokeras på stacken och skickas till funktioner per värde eller per referens. Använd aldrig System::SmartPtr-klassen för att hantera objekt av denna typ."
type: docs
weight: 274
url: /sv/system.drawing/size/
---
## Storleksklass

Representerar ett par heltal som representerar bildens bredd och höjd. Denna typ bör allokeras på stacken och skickas till funktioner per värde eller per referens. Använd aldrig [System::SmartPtr](../../system/smartptr/)-klassen för att hantera objekt av denna typ.

```cpp
class Size
```

## Metoder

| Metod | Beskrivning |
| --- | --- |
| static [Size](./) [Add](./add/)(const [Size](./)\&, const [Size](./)\&) | Returnerar ett nytt [Size](./)-objekt som är summan av det angivna [Size](./)-objektet, d.v.s. vars breddvärde är lika med summan av breddvärdena för de angivna objekten och höjdevärde är lika med summan av höjdevärdena för de angivna objekten. |
| static [Size](./) [Ceiling](./ceiling/)(const [SizeF](../sizef/)\&) | Skapar ett [Size](./)-objekt från det angivna [SizeF](../sizef/)-objektet genom att avrunda [SizeF](../sizef/)-objektets bredd- och höjdevärden till näst högre heltalsvärden. |
| **bool** [Equals](./equals/)(const [Size](./)\&) const | Bestämmer om det aktuella objektet och det angivna objektet är lika, d.v.s. representerar samma par av bredd- och hegihtvärden. |
| int [get_Height](./get_height/)() const | Returnerar värdet av heght som representeras av det aktuella objektet. |
| **bool** [get_IsEmpty](./get_isempty/)() const | Bestämmer om både bredd- och hegihtvärden är lika med 0. |
| int [get_Width](./get_width/)() const | Returnerar breddvärdet som representeras av det aktuella objektet. |
| **int32_t** [GetHashCode](./gethashcode/)() const | Returnerar en hashkod för det aktuella objektet. |
|  [operator Point](./operator_point/)() const | Skapar en instans av [Point](../point/)-objektet och initierar dess X- och Y-koordinater med det aktuella objektets bredd- och höjdevärden respektive. |
|  [operator SizeF](./operator_sizef/)() const | Skapar en instans av [SizeF](../sizef/)-objektet och initierar det med bredd- och hegihtvärden för det aktuella [Size](./)-objektet. |
| static [Size](./) [Round](./round/)(const [SizeF](../sizef/)\&) | Skapar ett [Size](./)-objekt från det angivna [SizeF](../sizef/)-objektet genom att avrunda [SizeF](../sizef/)-objektets bredd- och höjdevärden till närmaste heltalsvärden. |
| void [set_Height](./set_height/)(int) | Sätter värdet av höjden som representeras av det aktuella objektet. |
| void [set_Width](./set_width/)(int) | Sätter värdet av bredden som representeras av det aktuella objektet. |
|  [Size](./size/)() | Skapar ett nytt [Size](./)-objekt och initierar dess bredd- och höjdevärden med 0. |
|  [Size](./size/)(const [Point](../point/)\&) | Skapar ett nytt [Size](./)-objekt och initierar dess bredd- och höjdevärden med värdena av X- och Y-koordinaterna från den specifide punkten respektive. |
|  [Size](./size/)(int, int) | Skapar ett nytt [Size](./)-objekt och initierar det med det angivna värdet. |
| static [Size](./) [Subtract](./subtract/)(const [Size](./)\&, const [Size](./)\&) | Returnerar ett nytt [Size](./)-objekt som är resultatet av subctraction av **size2** från **size1**, d.v.s. vars breddvärde är resultatet av att subtrahera **size2**'s breddvärde från **size1**'s breddvärde och höjdevärde är resultatet av att subtrahera **size2**'s höjdevärde från **size1**'s höjdevärde. |
| [String](../../system/string/) [ToString](./tostring/)() const | Returnerar strängrepresentationen av paret av bredd- och hegihtvärden som representeras av det aktuella objektet. |
| static [Size](./) [Truncate](./truncate/)(const [SizeF](../sizef/)\&) | Skapar ett [Size](./)-objekt från det angivna [SizeF](../sizef/)-objektet genom att trunkera [SizeF](../sizef/)-objektets bredd- och höjdevärden till näst lägre heltalsvärden. |
## Fält

| Fält | Beskrivning |
| --- | --- |
| static [Empty](./empty/) | En tom instans av [Size](./)-klassen vars bredd- och höjdevärden är 0. |
## Se även

* Namnrymd [System::Drawing](../)
* Bibliotek [Aspose.Slides](../../)