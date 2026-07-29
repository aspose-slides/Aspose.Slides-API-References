---
title: RectangleF
second_title: Aspose.Slides för C++ API-referens
description: "Representerar ett rektangulärt område i en bild som definieras av enkelprecisionsflyttal för X- och Y-koordinaterna för dess övre vänstra hörn samt dess bredd och höjd. Denna typ bör allokeras på stacken och överföras till funktioner som värde eller referens. Använd aldrig klassen System::SmartPtr för att hantera objekt av denna typ."
type: docs
weight: 248
url: /sv/system.drawing/rectanglef/
---
## RectangleF klass

Representerar ett rektangulärt område i en bild som definieras av enkelflytprecisionens X- och Y-koordinater för dess övre vänstra hörn samt dess bredd och höjd. Denna typ bör allokeras på stacken och överföras till funktioner som värde eller referens. Använd aldrig klassen [System::SmartPtr](../../system/smartptr/) för att hantera objekt av denna typ.

```cpp
class RectangleF
```

## Metoder

| Metod | Beskrivning |
| --- | --- |
| **bool** [Contains](./contains/)(**float**, **float**) | Bestämmer om den angivna punkten ligger inom den rektangel som representeras av det aktuella objektet. |
| **bool** [Contains](./contains/)(const [PointF](../pointf/)\&) | Bestämmer om den angivna punkten ligger inom den rektangel som representeras av det aktuella objektet. |
| **bool** [Contains](./contains/)(const [RectangleF](./)\&) | Bestämmer om den angivna rektangeln ligger inom den rektangel som representeras av det aktuella objektet. |
| **bool** [Equals](./equals/)(const [RectangleF](./)\&) const | Bestämmer om de rektanglar som representeras av det aktuella och det angivna objektet är identiska. |
| static [RectangleF](./) [FromLTRB](./fromltrb/)(**float**, **float**, **float**, **float**) | Skapar ett nytt [RectangleF](./)-objekt som representerar en rektangel med de angivna kantpositionerna. |
| **float** [get_Bottom](./get_bottom/)() const | Returnerar y-koordinaten för rektangelns nedre kant som representeras av det aktuella objektet. |
| **float** [get_Height](./get_height/)() const | Returnerar höjden på rektangeln som representeras av det aktuella objektet. |
| **bool** [get_IsEmpty](./get_isempty/)() const | Bestämmer om X- och Y-koordinaterna för det aktuella objektets övre vänstra hörn samt dess bredd och höjd har värdet 0. |
| **float** [get_Left](./get_left/)() const | Returnerar X-koordinaten för rektangelns vänstra kant som representeras av det aktuella objektet. |
| [PointF](../pointf/) [get_Location](./get_location/)() const | Returnerar en instans av klassen [PointF](../pointf/) som specificerar platsen för det övre vänstra hörnet av rektangeln som representeras av det aktuella objektet. |
| **float** [get_Right](./get_right/)() const | Returnerar X-koordinaten för rektangelns högra kant som representeras av det aktuella objektet. |
| [SizeF](../sizef/) [get_Size](./get_size/)() const | Returnerar en instans av klassen [SizeF](../sizef/) som specificerar bredden och höjden på rektangeln som representeras av det aktuella objektet. |
| **float** [get_Top](./get_top/)() const | Returnerar Y-koordinaten för rektangelns övre kant som representeras av det aktuella objektet. |
| **float** [get_Width](./get_width/)() const | Returnerar bredden på rektangeln som representeras av det aktuella objektet. |
| **float** [get_X](./get_x/)() const | Returnerar X-koordinaten för det övre vänstra hörnet av rektangeln som representeras av det aktuella objektet. |
| **float** [get_Y](./get_y/)() const | Returnerar Y-koordinaten för det övre vänstra hörnet av rektangeln som representeras av det aktuella objektet. |
| int [GetHashCode](./gethashcode/)() const | Returnerar en hashkod för det aktuella objektet. |
| void [Inflate](./inflate/)(**float**, **float**) | Ökar bredden och höjden på rektangeln som representeras av det aktuella objektet, samtidigt som den geometriska centrumets position bibehålls. Bredden och höjden ökas i båda riktningarna med de angivna mängderna. |
| void [Inflate](./inflate/)(const [SizeF](../sizef/)\&) | Ökar bredden och höjden på rektangeln som representeras av det aktuella objektet, samtidigt som den geometriska centrumets position bibehålls. Bredden och höjden ökas i båda riktningarna med de mängder som motsvarar bredd- och höjdvärdena i det angivna storleksobjektet. |
| static [RectangleF](./) [Inflate](./inflate/)(const [RectangleF](./)\&, **float**, **float**) | Ökar bredden och höjden på rektangeln som representeras av det angivna objektet, samtidigt som den geometriska centrumets position bibehålls. Bredden och höjden ökas i båda riktningarna med de angivna mängderna. |
| void [Intersect](./intersect/)(const [RectangleF](./)\&) | Ersätter rektangeln som representeras av det aktuella objektet med den rektangel som erhålls genom dess skärning med den rektangel som representeras av det angivna objektet. |
| static [RectangleF](./) [Intersect](./intersect/)(const [RectangleF](./)\&, const [RectangleF](./)\&) | Returnerar en rektangel som är resultatet av skärningen av de angivna rektanglarna. |
| **bool** [IntersectsWith](./intersectswith/)(const [RectangleF](./)\&) | Bestämmer om de rektanglar som representeras av det aktuella och det angivna objektet skär varandra. |
| void [Offset](./offset/)(const [PointF](../pointf/)\&) | Förskjuter positionen för rektangeln som representeras av det aktuella objektet med de angivna värdena. |
| void [Offset](./offset/)(**float**, **float**) | Förskjuter positionen för rektangeln som representeras av det aktuella objektet med de angivna värdena. |
| **bool** [operator!=](./operator_not_equal/)(std::nullptr_t) const | Returnerar alltid true. |
| **bool** [operator==](./operator_equal_equal/)(std::nullptr_t) const | Returnerar alltid false. |
| [RectangleF](./rectanglef/)() | Skapar en ny instans av objektet [RectangleF](./) som representerar en rektangel med X- och Y-koordinater samt bredd- och höjdvärden satta till 0. |
| [RectangleF](./rectanglef/)(**float**, **float**, **float**, **float**) | Skapar en ny instans av objektet [RectangleF](./) som representerar en rektangel med de angivna koordinaterna för dess övre vänstra hörn samt bredd och höjd. |
| [RectangleF](./rectanglef/)(const [PointF](../pointf/)\&, const [SizeF](../sizef/)\&) | Skapar en ny instans av objektet [RectangleF](./) som representerar en rektangel med koordinaterna för dess övre vänstra hörn angivna som en instans av klassen [PointF](../pointf/) och dess bredd och höjd som en instans av klassen [SizeF](../sizef/). |
| explicit  [RectangleF](./rectanglef/)(const [Rectangle](../rectangle/)\&) | Skapar en ny instans av objektet [RectangleF](./) som representerar den rektangel som är ekvivalent med den angivna. |
| void [set_Height](./set_height/)(**float**) | Sätter höjden på rektangeln som representeras av det aktuella objektet. |
| void [set_Location](./set_location/)([PointF](../pointf/)) | Sätter platsen för rektangelns övre vänstra hörn som representeras av det aktuella objektet. |
| void [set_Size](./set_size/)([SizeF](../sizef/)) | Sätter bredden och höjden på rektangeln som representeras av det aktuella objektet. |
| void [set_Width](./set_width/)(**float**) | Sätter bredden på rektangeln som representeras av det aktuella objektet. |
| void [set_X](./set_x/)(**float**) | Sätter X-koordinaten för rektangelns övre vänstra hörn som representeras av det aktuella objektet. |
| void [set_Y](./set_y/)(**float**) | Sätter Y-koordinaten för rektangelns övre vänstra hörn som representeras av det aktuella objektet. |
| [System::String](../../system/string/) [ToString](./tostring/)() const | Returnerar strängrepresentationen av det aktuella objektet. |
| static [RectangleF](./) [Union](./union/)(const [RectangleF](./)\&, const [RectangleF](./)\&) | Returnerar en rektangel som är resultatet av föreningen av de angivna rektanglarna. |

## Fält

| Fält | Beskrivning |
| --- | --- |
| static [Empty](./empty/) | En tom rektangel, dvs. en rektangel vars plats- och storleksvärden är noll. |

## Se även

* Namnrymd [System::Drawing](../)
* Bibliotek [Aspose.Slides](../../)