---
title: SizeF
second_title: Aspose.Slides för C++ API-referens
description: "Representerar ett par flyttal med enkel precision som representerar bildens bredd och höjd. Denna typ bör allokeras på stacken och skickas till funktioner som värde eller referens. Använd aldrig System::SmartPtr-klassen för att hantera objekt av denna typ."
type: docs
weight: 287
url: /sv/system.drawing/sizef/
---
## SizeF klass

Representerar ett par flyttal med enkel precision som representerar bredd och höjd på en bild. Denna typ bör allokeras på stacken och skickas till funktioner som värde eller referens. Använd aldrig [System::SmartPtr](../../system/smartptr/) klass för att hantera objekt av denna typ.

```cpp
class SizeF
```

## Metoder

| Metod | Beskrivning |
| --- | --- |
| static [SizeF](./) [Add](./add/)(const [SizeF](./)\&, const [SizeF](./)\&) | Returnerar ett nytt [SizeF](./)-objekt som är summan av de angivna [SizeF](./)-objekten, d.v.s. vars breddvärde är lika med summan av breddvärdena för de angivna objekten och höjdvärdet är lika med summan av höjdvärdena för de angivna objekten. |
| **bool** [Equals](./equals/)(const [SizeF](./)\&) const | Bestämmer om det aktuella objektet och det angivna objektet är lika, d.v.s. representerar samma par av bredd- och höjdvärden. |
| **float** [get_Height](./get_height/)() const | Returnerar höjdvärdet som representeras av det aktuella objektet. |
| **bool** [get_IsEmpty](./get_isempty/)() const | Bestämmer om både bredd- och höjdvärden är lika med 0. |
| **float** [get_Width](./get_width/)() const | Returnerar breddvärdet som representeras av det aktuella objektet. |
| **int32_t** [GetHashCode](./gethashcode/)() const | Returnerar en hashkod för det aktuella objektet. |
| [operator PointF](./operator_pointf/)() const | Konverterar det aktuella objektet till en instans av [Point](../point/)-objekt genom att initiera dess X- och Y-koordinater med det aktuella objektets bredd- och höjdvärden respektive. |
| [SizeF](./)\& [operator+=](./operator_plus_equal/)(const [SizeF](./)\&) | Lägger till den angivna [SizeF](./)-objektets bredd- och höjdvärden till bredd- och höjdvärden för det aktuella [SizeF](./)-objektet respektivt. |
| void [set_Height](./set_height/)(**float**) | Sätter värdet för höjden som representeras av det aktuella objektet. |
| void [set_Width](./set_width/)(**float**) | Sätter värdet för bredden som representeras av det aktuella objektet. |
| [SizeF](./sizef/)() | Skapar ett nytt [SizeF](./)-objekt och initierar dess bredd- och höjdvärden till 0. |
| [SizeF](./sizef/)(const [PointF](../pointf/)\&) | Skapar ett nytt [SizeF](./)-objekt och initierar dess bredd- och höjdvärden med värdena för X- och Y-koordinaterna i den angivna punkten respektive. |
| [SizeF](./sizef/)(**float**, **float**) | Skapar ett nytt [SizeF](./)-objekt och initierar det med det angivna värdet. |
| static [SizeF](./) [Subtract](./subtract/)(const [SizeF](./)\&, const [SizeF](./)\&) | Returnerar ett nytt [SizeF](./)-objekt som är resultatet av subtraktionen av **size2** från **size1**, d.v.s. vars breddvärde är resultatet av subtraktionen av **size2**'s breddvärde från **size1**'s breddvärde och höjdvärdet är resultatet av subtraktionen av **size2**'s höjdvärde från **size1**'s höjdvärde. |
| [PointF](../pointf/) [ToPointF](./topointf/)() const | Konverterar det aktuella objektet till en instans av [Point](../point/)-objekt genom att initiera dess X- och Y-koordinater med det aktuella objektets bredd- och höjdvärden respektive. |
| [Size](../size/) [ToSize](./tosize/)() const | Skapar ett [Size](../size/)-objekt från det aktuella [SizeF](./)-objektet genom att truncera [SizeF](./)-objektets bredd- och höjdvärden till nästa lägre heltalsvärden. |
| [System::String](../../system/string/) [ToString](./tostring/)() const | Returnerar strängrepresentationen av paret av bredd- och höjdvärden som representeras av det aktuella objektet. |

## Fält

| Fält | Beskrivning |
| --- | --- |
| static [Empty](./empty/) | En tom instans av [SizeF](./)-klass vars bredd- och höjdvärden är 0. |

## Se även

* Namnrymd [System::Drawing](../)
* Bibliotek [Aspose.Slides](../../)