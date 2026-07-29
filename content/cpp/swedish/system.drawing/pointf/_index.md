---
title: PointF
second_title: Aspose.Slides för C++ API-referens
description: "Representerar ett par av enkelprecisionsflytande punkt X- och Y-koordinater för en punkt på ett tvådimensionellt plan. Denna typ bör allokeras på stacken och passeras till funktioner som värde eller referens. Använd aldrig System::SmartPtr-klassen för att hantera objekt av denna typ."
type: docs
weight: 222
url: /sv/system.drawing/pointf/
---
## PointF klass


Representerar ett par av enkelprecisions-flytande punkt X- och Y-koordinater för en punkt på ett tvådimensionellt plan. Denna typ bör allokeras på stacken och passeras till funktioner som värde eller referens. Använd aldrig [System::SmartPtr](../../system/smartptr/) klass för att hantera objekt av denna typ.

```cpp
class PointF
```

## Metoder

| Metod | Beskrivning |
| --- | --- |
| static [PointF](./) [Add](./add/)(const [PointF](./)\&, const [SizeF](../sizef/)\&) | Lägger till bredd- och höjdvärden för det angivna [SizeF](../sizef/)-objektet till X- och Y-koordinatvärdena för det angivna [PointF](./)-objektet på motsvarande sätt. |
| static [PointF](./) [Add](./add/)(const [PointF](./)\&, const [Size](../size/)\&) | Lägger till bredd- och höjdvärden för det angivna [Size](../size/)-objektet till X- och Y-koordinatvärdena för det angivna [PointF](./)-objektet på motsvarande sätt. |
| **bool** [Equals](./equals/)(const [PointF](./)\&) const | Bestämmer om det aktuella objektet och det angivna objektet är lika, dvs. representerar samma par av X- och Y-koordinatvärden. |
| **bool** [get_IsEmpty](./get_isempty/)() const | Bestämmer om både X- och Y-koordinatvärdena är lika med 0. |
| **float** [get_X](./get_x/)() const | Returnerar värdet av X-koordinaten som representeras av det aktuella objektet. |
| **float** [get_Y](./get_y/)() const | Returnerar värdet av Y-koordinaten som representeras av det aktuella objektet. |
| int [GetHashCode](./gethashcode/)() const | Returnerar en hashkod för det aktuella objektet. |
| **bool** [IsNull](./isnull/)() const | Returnerar alltid false. |
| explicit  [operator bool](./operator_bool/)() | Returnerar alltid true. |
|  [PointF](./pointf/)() | Skapar ett nytt [PointF](./)-objekt och initierar dess X- och Y-koordinatvärden till 0. |
|  [PointF](./pointf/)(**float**, **float**) | Skapar ett nytt [PointF](./)-objekt och initierar det med de angivna värdena. |
|  [PointF](./pointf/)(const [SizeF](../sizef/)\&) | Skapar ett nytt [PointF](./)-objekt och initierar dess X- och Y-koordinatvärden med bredd- och höjdvärdena från det angivna [SizeF](../sizef/)-objektet på motsvarande sätt. |
| void [set_X](./set_x/)(**float**) | Sätter värdet för X-koordinaten som representeras av det aktuella objektet. |
| void [set_Y](./set_y/)(**float**) | Sätter värdet för Y-koordinaten som representeras av det aktuella objektet. |
| static [PointF](./) [Subtract](./subtract/)(const [PointF](./)\&, const [SizeF](../sizef/)\&) | Subtraherar bredd- och höjdvärden för det angivna [SizeF](../sizef/)-objektet från X- och Y-koordinatvärdena för det angivna [PointF](./)-objektet på motsvarande sätt. |
| static [PointF](./) [Subtract](./subtract/)(const [PointF](./)\&, const [Size](../size/)\&) | Subtraherar bredd- och höjdvärden för det angivna [Size](../size/)-objektet från X- och Y-koordinatvärdena för det angivna [PointF](./)-objektet på motsvarande sätt. |
| [System::String](../../system/string/) [ToString](./tostring/)() const | Returnerar strängrepresentationen av paret X- och Y-koordinatvärden som representeras av det aktuella objektet. |

## Fält

| Fält | Beskrivning |
| --- | --- |
| static [Empty](./empty/) | En tom instans av [PointF](./) klass vars X- och Y-koordinatvärden är 0. |

## Se även

* Namnområde [System::Drawing](../)
* Bibliotek [Aspose.Slides](../../)