---
title: BeginContainer()
second_title: Aspose.Slides dla C++ Dokumentacja API
description: Zapisuje kontener z bieżącym stanem tego obiektu, otwiera i używa nowego kontenera oraz zwraca zapisany kontener.
type: docs
weight: 976
url: /pl/system.drawing/graphics/begincontainer/
---
## Graphics::BeginContainer() metoda

Zapisuje kontener z bieżącym stanem tego obiektu, otwiera i używa nowego kontenera oraz zwraca zapisany kontener.

```cpp
SharedPtr<Drawing2D::GraphicsContainer> System::Drawing::Graphics::BeginContainer()
```

## Graphics::BeginContainer(Rectangle, Rectangle, GraphicsUnit) metoda

Zapisuje kontener z bieżącym stanem tego obiektu, otwiera i używa nowego kontenera oraz zwraca zapisany kontener.

```cpp
SharedPtr<Drawing2D::GraphicsContainer> System::Drawing::Graphics::BeginContainer(Rectangle dstrect, Rectangle srcrect, GraphicsUnit unit)
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| dstrect | [Rectangle](../../rectangle/) | Prostokąt określający transformację skalowania nowego kontenera. Używany razem z **srcrect** |
| srcrect | [Rectangle](../../rectangle/) | Prostokąt określający transformację skalowania nowego kontenera. Używany razem z **dstrect** |
| unit | [GraphicsUnit](../../graphicsunit/) | Wartość określająca jednostkę miary nowego kontenera |

## Graphics::BeginContainer(RectangleF, RectangleF, GraphicsUnit) metoda

Zapisuje kontener z bieżącym stanem tego obiektu, otwiera i używa nowego kontenera oraz zwraca zapisany kontener.

```cpp
SharedPtr<Drawing2D::GraphicsContainer> System::Drawing::Graphics::BeginContainer(RectangleF dstrect, RectangleF srcrect, GraphicsUnit unit)
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| dstrect | [RectangleF](../../rectanglef/) | Prostokąt określający transformację skalowania nowego kontenera. Używany razem z **srcrect** |
| srcrect | [RectangleF](../../rectanglef/) | Prostokąt określający transformację skalowania nowego kontenera. Używany razem z **dstrect** |
| unit | [GraphicsUnit](../../graphicsunit/) | Wartość określająca jednostkę miary nowego kontenera |

## Zobacz także

* Enum [GraphicsUnit](../../graphicsunit/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [GraphicsContainer](../../../system.drawing.drawing2d/graphicscontainer/)
* Class [Graphics](../)
* Class [Rectangle](../../rectangle/)
* Class [RectangleF](../../rectanglef/)
* Namespace [System::Drawing](../../)
* Library [Aspose.Slides](../../../)