---
title: GetHeight()
second_title: Aspose.Slides pro C++ API Reference
description: Vrací řádkování písma reprezentovaného aktuálním objektem v aktuální jednotce určeného objektu Graphics.
type: docs
weight: 14
url: /cs/system.drawing/font/getheight/
---
## Font::GetHeight(const SharedPtr\<Graphics\>\&) metoda

Vrací řádkování písma reprezentovaného aktuálním objektem v aktuální jednotce specifikovaného [Graphics](../../graphics/) objektu.

```cpp
float System::Drawing::Font::GetHeight(const SharedPtr<Graphics> &graphics)
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| graphics | const [SharedPtr](../../../system/sharedptr/)\<[Graphics](../../graphics/)\>\& | Objekt [Graphics](../../graphics/), který určuje jednotky měření |

## Font::GetHeight(float) metoda

Vrací výšku písma reprezentovaného aktuálním objektem při vykreslení na zobrazovací zařízení se specifikovaným vertikálním rozlišením.

```cpp
float System::Drawing::Font::GetHeight(float dpi=DEFAULT_FONT_OPERATIONS_DPI)
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| dpi | **float** | Vertikální rozlišení zobrazovacího zařízení |

### Návratová hodnota

Výška písma v pixelech

## Viz také

* Definice typu [SharedPtr](../../../system/sharedptr/)
* Třída [Graphics](../../graphics/)
* Třída [Font](../)
* Jmenný prostor [System::Drawing](../../)
* Knihovna [Aspose.Slides](../../../)