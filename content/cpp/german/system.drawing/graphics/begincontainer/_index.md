---
title: BeginContainer()
second_title: Aspose.Slides für C++ API-Referenz
description: Speichert einen Container mit dem aktuellen Zustand dieses Objekts, öffnet und verwendet einen neuen Container und gibt den gespeicherten Container zurück.
type: docs
weight: 976
url: /de/system.drawing/graphics/begincontainer/
---
## Graphics::BeginContainer() Methode

Speichert einen Container mit dem aktuellen Zustand dieses Objekts, öffnet und verwendet einen neuen Container und gibt den gespeicherten Container zurück.

```cpp
SharedPtr<Drawing2D::GraphicsContainer> System::Drawing::Graphics::BeginContainer()
```

## Graphics::BeginContainer(Rectangle, Rectangle, GraphicsUnit) Methode

Speichert einen Container mit dem aktuellen Zustand dieses Objekts, öffnet und verwendet einen neuen Container und gibt den gespeicherten Container zurück.

```cpp
SharedPtr<Drawing2D::GraphicsContainer> System::Drawing::Graphics::BeginContainer(Rectangle dstrect, Rectangle srcrect, GraphicsUnit unit)
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| dstrect | [Rectangle](../../rectangle/) | Das Rechteck, das eine Skalierungstransformation des neuen Containers angibt. Wird zusammen mit **srcrect** verwendet |
| srcrect | [Rectangle](../../rectangle/) | Das Rechteck, das eine Skalierungstransformation des neuen Containers angibt. Wird zusammen mit **dstrect** verwendet |
| unit | [GraphicsUnit](../../graphicsunit/) | Der Wert, der die Maßeinheit des neuen Containers angibt |

## Graphics::BeginContainer(RectangleF, RectangleF, GraphicsUnit) Methode

Speichert einen Container mit dem aktuellen Zustand dieses Objekts, öffnet und verwendet einen neuen Container und gibt den gespeicherten Container zurück.

```cpp
SharedPtr<Drawing2D::GraphicsContainer> System::Drawing::Graphics::BeginContainer(RectangleF dstrect, RectangleF srcrect, GraphicsUnit unit)
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| dstrect | [RectangleF](../../rectanglef/) | Das Rechteck, das eine Skalierungstransformation des neuen Containers angibt. Wird zusammen mit **srcrect** verwendet |
| srcrect | [RectangleF](../../rectanglef/) | Das Rechteck, das eine Skalierungstransformation des neuen Containers angibt. Wird zusammen mit **dstrect** verwendet |
| unit | [GraphicsUnit](../../graphicsunit/) | Der Wert, der die Maßeinheit des neuen Containers angibt |

## Siehe auch

* Aufzählung [GraphicsUnit](../../graphicsunit/)
* Typdefinition [SharedPtr](../../../system/sharedptr/)
* Klasse [GraphicsContainer](../../../system.drawing.drawing2d/graphicscontainer/)
* Klasse [Graphics](../)
* Klasse [Rectangle](../../rectangle/)
* Klasse [RectangleF](../../rectanglef/)
* Namensraum [System::Drawing](../../)
* Bibliothek [Aspose.Slides](../../../)