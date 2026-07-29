---
title: Point
second_title: Aspose.Slides för C++ API-referens
description: "Representerar ett par heltals-X- och Y-koordinater för en punkt på ett tvådimensionellt plan. Denna typ bör allokeras på stacken och skickas till funktioner som ett värde eller som referens. Använd aldrig System::SmartPtr-klassen för att hantera objekt av denna typ."
type: docs
weight: 209
url: /sv/system.drawing/point/
---
## Point klass


Representerar ett par heltals-X- och Y-koordinater för en punkt på ett tvådimensionellt plan. Denna typ bör allokeras på stacken och skickas till funktioner som ett värde eller som en referens. Använd aldrig [System::SmartPtr](../../system/smartptr/) klass för att hantera objekt av denna typ.

```cpp
class Point
```

## Metoder

| Metod | Beskrivning |
| --- | --- |
| static [Point](./) [Add](./add/)(const [Point](./)\&, const [Size](../size/)\&) | Lägger till bredd- och höjdför-värdena för det angivna [Size](../size/)-objektet till X- och Y-koordinatvärdena för det angivna [Point](./)-objektet respektive. |
| static [Point](./) [Ceiling](./ceiling/)(const [PointF](../pointf/)\&) | Skapar ett [Point](./)-objekt från det angivna [PointF](../pointf/)-objektet genom att avrunda [PointF](../pointf/)-objektets X- och Y-koordinatvärden till nästa högre heltal. |
| **bool** [Equals](./equals/)(const [Point](./)\&) const | Bestämmer om det aktuella objektet och det angivna objektet är lika, d.v.s. representerar samma par X- och Y-koordinatvärden. |
| **bool** [get_IsEmpty](./get_isempty/)() const | Bestämmer om både X- och Y-koordinatvärdena är lika med 0. |
| int [get_X](./get_x/)() const | Returnerar värdet för X-koordinaten som representeras av det aktuella objektet. |
| int [get_Y](./get_y/)() const | Returnerar värdet för Y-koordinaten som representeras av det aktuella objektet. |
| int [GetHashCode](./gethashcode/)() const | Returnerar en hash-kod för det aktuella objektet. |
| size_t [getStdHash](./getstdhash/)() const | Returnerar ett hash-värde för det aktuella objektet. |
| **bool** [IsNull](./isnull/)() const | Returnerar alltid false. |
| void [Offset](./offset/)(int, int) | Förskjuter X- och Y-koordinatvärdet som representeras av det aktuella objektet med de angivna värdena. |
| void [Offset](./offset/)([Point](./)) | Förskjuter X- och Y-koordinaterna som representeras av det aktuella objektet med X- och Y-koordinatvärdena som representeras av det angivna [Point](./)-objektet respektive. |
|  [operator PointF](./operator_pointf/)() const | Skapar en instans av [PointF](../pointf/)-objektet och initierar den med X- och Y-koordinatvärdena från det aktuella [Point](./)-objektet. |
|  [operator Size](./operator_size/)() const | Skapar en instans av [Size](../size/)-objektet och initierar dess bredd- och höjdför-värden med X- och Y-koordinatvärdena som representeras av det aktuella objektet respektive. |
|  [Point](./point/)() | Skapar ett nytt [Point](./)-objekt och initierar dess X- och Y-koordinatvärden med 0. |
|  [Point](./point/)(int, int) | Skapar ett nytt [Point](./)-objekt och initierar det med de angivna värdena. |
|  [Point](./point/)(const [Size](../size/)\&) | Skapar ett nytt [Point](./)-objekt och initierar dess X- och Y-koordinatvärden med bredd- och höjdvärdena från det angivna [SizeF](../sizef/)-objektet respektive. |
|  [Point](./point/)(int) | Skapar ett nytt [Point](./)-objekt och initierar dess X-koordinatvärde med ett värde bildat av de högsta 16 bitarna i det angivna 32-bit-heltalet och dess Y-koordinatvärde med ett värde bildat av de lägsta 16 bitarna i det angivna 32-bit-heltalet. |
| static [Point](./) [Round](./round/)(const [PointF](../pointf/)\&) | Skapar ett [Point](./)-objekt från det angivna [PointF](../pointf/)-objektet genom att avrunda [PointF](../pointf/)-objektets X- och Y-koordinatvärden till närmaste heltal. |
| void [set_X](./set_x/)(int) | Sätter värdet för X-koordinaten som representeras av det aktuella objektet. |
| void [set_Y](./set_y/)(int) | Sätter värdet för Y-koordinaten som representeras av det aktuella objektet. |
| static [Point](./) [Subtract](./subtract/)(const [Point](./)\&, const [Size](../size/)\&) | Subtraherar bredd- och höjdför-värdena för det angivna [Size](../size/)-objektet från X- och Y-koordinatvärdena för det angivna [Point](./)-objektet respektive. |
| [String](../../system/string/) [ToString](./tostring/)() const | Returnerar strängrepresentationen av paret X- och Y-koordinatvärden som representeras av det aktuella objektet. |
| static [Point](./) [Truncate](./truncate/)(const [PointF](../pointf/)\&) | Skapar ett [Point](./)-objekt från det angivna [PointF](../pointf/)-objektet genom att trunkera [PointF](../pointf/)-objektets X- och Y-koordinatvärden till nästa lägre heltal. |

## Fält

| Fält | Beskrivning |
| --- | --- |
| static [Empty](./empty/) | En tom instans av [Point](./) klass vars X- och Y-koordinatvärden är 0. |

## Se även

* Namnrymd [System::Drawing](../)
* Bibliotek [Aspose.Slides](../../)