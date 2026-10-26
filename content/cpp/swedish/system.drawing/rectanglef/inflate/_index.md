---
title: Inflate()
second_title: Aspose.Slides för C++ API-referens
description: Ökar bredden och höjden på rektangeln som representeras av det aktuella objektet, samtidigt som den geometriska mittpunkten för rektangeln behålls. Bredden och höjden ökas i båda riktningarna med de angivna mängderna.
type: docs
weight: 261
url: /sv/system.drawing/rectanglef/inflate/
---
## RectangleF::Inflate(float, float) metod


Ökar bredden och höjden på rektangeln som representeras av det aktuella objektet, samtidigt som den geometriska mittpunkten för rektangeln behålls. Bredden och höjden ökas i båda riktningarna med de angivna mängderna.

```cpp
void System::Drawing::RectangleF::Inflate(float width, float height)
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| width | **float** | Mängden med vilken rektangelns bredd ska ökas i båda riktningarna |
| height | **float** | Mängden med vilken rektangelns höjd ska ökas i båda riktningarna |

## RectangleF::Inflate(const SizeF\&) metod


Ökar bredden och höjden på rektangeln som representeras av det aktuella objektet, samtidigt som den geometriska mittpunkten för rektangeln behålls. Bredden och höjden ökas i båda riktningarna med de mängder som anges av bredd- och höjdvärdena i det angivna storleksobjektet.

```cpp
void System::Drawing::RectangleF::Inflate(const SizeF &size)
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| size | const [SizeF](../../sizef/)\& | [SizeF](../../sizef/)-objektet som specificerar de mängder som bredden och höjden på rektangeln ska ökas med |

## RectangleF::Inflate(const RectangleF\&, float, float) metod


Ökar bredden och höjden på rektangeln som representeras av det angivna objektet, samtidigt som den geometriska mittpunkten för rektangeln behålls. Bredden och höjden ökas i båda riktningarna med de angivna mängderna.

```cpp
static RectangleF System::Drawing::RectangleF::Inflate(const RectangleF &rect, float x, float y)
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| rect | const [RectangleF](../)\& | En rektangel att expandera |
| x | **float** | Mängden med vilken rektangelns bredd ska ökas i båda riktningarna |
| y | **float** | Mängden med vilken rektangelns höjd ska ökas i båda riktningarna |

### Returvärde

Objektet [RectangleF](../) som representerar den utökade rektangeln

## Se även

* Klass [RectangleF](../)
* Klass [SizeF](../../sizef/)
* Namnrymd [System::Drawing](../../)
* Bibliotek [Aspose.Slides](../../../)