---
title: Inflate()
second_title: Aspose.Slides för C++ API-referens
description: Ökar bredden och höjden på den rektangel som representeras av det aktuella objektet, samtidigt som den geometriska centrumpositionen för rektangeln bibehålls. Bredden och höjden ökas i båda riktningarna med de angivna värdena.
type: docs
weight: 261
url: /sv/system.drawing/rectangle/inflate/
---
## Rectangle::Inflate(int, int) metod

Ökar bredden och höjden på den rektangel som representeras av det aktuella objektet, samtidigt som rektangelns geometriska centrum hålls på samma plats. Bredden och höjden ökas i båda riktningarna med de angivna värdena.

```cpp
void System::Drawing::Rectangle::Inflate(int width, int height)
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| width | int | Mängden med vilken rektangelns bredd ska ökas i båda riktningarna |
| height | int | Mängden med vilken rektangelns höjd ska ökas i båda riktningarna |

## Rectangle::Inflate(const Size\&) metod

Ökar bredden och höjden på den rektangel som representeras av det aktuella objektet, samtidigt som rektangelns geometriska centrum hålls på samma plats. Bredden och höjden ökas i båda riktningarna med de mängder som anges av bredd- och höjdvärden i det angivna size-objektet.

```cpp
void System::Drawing::Rectangle::Inflate(const Size &size)
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| size | const [Size](../../size/)\& | Det [Size](../../size/)-objektet som specificerar mängderna för att öka rektangelns bredd och höjd med |

## Rectangle::Inflate(const Rectangle\&, int, int) metod

Ökar bredden och höjden på den rektangel som representeras av det angivna objektet, samtidigt som rektangelns geometriska centrum hålls på samma plats. Bredden och höjden ökas i båda riktningarna med de angivna värdena.

```cpp
static Rectangle System::Drawing::Rectangle::Inflate(const Rectangle &rect, int x, int y)
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| rect | const [Rectangle](../)\& | En rektangel att förstora |
| x | int | Mängden med vilken rektangelns bredd ska ökas i båda riktningarna |
| y | int | Mängden med vilken rektangelns höjd ska ökas i båda riktningarna |

### Returvärde

Det [Rectangle](../)-objektet som representerar den förstörda rektangeln

## Se även

* Klass [Rectangle](../)
* Klass [Size](../../size/)
* Namnrymd [System::Drawing](../../)
* Bibliotek [Aspose.Slides](../../../)