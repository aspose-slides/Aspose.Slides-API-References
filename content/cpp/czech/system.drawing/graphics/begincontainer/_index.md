---
title: BeginContainer()
second_title: Aspose.Slides pro C++ API Reference
description: Uloží kontejner s aktuálním stavem tohoto objektu, otevře a použije nový kontejner a vrátí uložený kontejner.
type: docs
weight: 976
url: /cs/system.drawing/graphics/begincontainer/
---
## Graphics::BeginContainer() metoda

Uloží kontejner s aktuálním stavem tohoto objektu, otevře a použije nový kontejner a vrátí uložený kontejner.

```cpp
SharedPtr<Drawing2D::GraphicsContainer> System::Drawing::Graphics::BeginContainer()
```

## Graphics::BeginContainer(Rectangle, Rectangle, GraphicsUnit) metoda

Uloží kontejner s aktuálním stavem tohoto objektu, otevře a použije nový kontejner a vrátí uložený kontejner.

```cpp
SharedPtr<Drawing2D::GraphicsContainer> System::Drawing::Graphics::BeginContainer(Rectangle dstrect, Rectangle srcrect, GraphicsUnit unit)
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| dstrect | [Rectangle](../../rectangle/) | Obdélník, který určuje měřítkovou transformaci nového kontejneru. Používá se společně s **srcrect** |
| srcrect | [Rectangle](../../rectangle/) | Obdélník, který určuje měřítkovou transformaci nového kontejneru. Používá se společně s **dstrect** |
| unit | [GraphicsUnit](../../graphicsunit/) | Hodnota určující jednotku měření nového kontejneru |

## Graphics::BeginContainer(RectangleF, RectangleF, GraphicsUnit) metoda

Uloží kontejner s aktuálním stavem tohoto objektu, otevře a použije nový kontejner a vrátí uložený kontejner.

```cpp
SharedPtr<Drawing2D::GraphicsContainer> System::Drawing::Graphics::BeginContainer(RectangleF dstrect, RectangleF srcrect, GraphicsUnit unit)
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| dstrect | [RectangleF](../../rectanglef/) | Obdélník, který určuje měřítkovou transformaci nového kontejneru. Používá se společně s **srcrect** |
| srcrect | [RectangleF](../../rectanglef/) | Obdélník, který určuje měřítkovou transformaci nového kontejneru. Používá se společně s **dstrect** |
| unit | [GraphicsUnit](../../graphicsunit/) | Hodnota určující jednotku měření nového kontejneru |

## Viz také

* Enum [GraphicsUnit](../../graphicsunit/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Třída [GraphicsContainer](../../../system.drawing.drawing2d/graphicscontainer/)
* Třída [Graphics](../)
* Třída [Rectangle](../../rectangle/)
* Třída [RectangleF](../../rectanglef/)
* jmenný prostor [System::Drawing](../../)
* Library [Aspose.Slides](../../../)