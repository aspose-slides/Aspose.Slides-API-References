---
title: DrawRectangle()
second_title: Aspose.Slides pro C++ – reference API
description: Vykreslí zadaný obdélník pomocí zadaného pera na povrchu reprezentovaném aktuálním objektem.
type: docs
weight: 287
url: /cs/system.drawing/graphics/drawrectangle/
---
## Graphics::DrawRectangle(const SharedPtr\<Pen\>\&, int, int, int, int) metoda

Vykreslí zadaný obdélník pomocí zadaného pera na povrchu reprezentovaném aktuálním objektem.

```cpp
void System::Drawing::Graphics::DrawRectangle(const SharedPtr<Pen> &pen, int x, int y, int width, int height)
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| pen | const [SharedPtr](../../../system/sharedptr/)\<[Pen](../../pen/)\>\& | Pero, které se použije při kreslení obdélníku |
| x | int | Souřadnice X levého horního rohu obdélníku, který se má vykreslit |
| y | int | Souřadnice Y levého horního rohu obdélníku, který se má vykreslit |
| width | int | Šířka obdélníku, který se má vykreslit |
| height | int | Výška obdélníku, který se má vykreslit |

## Graphics::DrawRectangle(const SharedPtr\<Pen\>\&, float, float, float, float) metoda

Vykreslí zadaný obdélník pomocí zadaného pera na povrchu reprezentovaném aktuálním objektem.

```cpp
void System::Drawing::Graphics::DrawRectangle(const SharedPtr<Pen> &pen, float x, float y, float width, float height)
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| pen | const [SharedPtr](../../../system/sharedptr/)\<[Pen](../../pen/)\>\& | Pero, které se použije při kreslení obdélníku |
| x | **float** | Souřadnice X levého horního rohu obdélníku, který se má vykreslit |
| y | **float** | Souřadnice Y levého horního rohu obdélníku, který se má vykreslit |
| width | **float** | Šířka obdélníku, který se má vykreslit |
| height | **float** | Výška obdélníku, který se má vykreslit |

## Graphics::DrawRectangle(const SharedPtr\<Pen\>\&, Rectangle) metoda

Vykreslí zadaný obdélník pomocí zadaného pera na povrchu reprezentovaném aktuálním objektem.

```cpp
void System::Drawing::Graphics::DrawRectangle(const SharedPtr<Pen> &pen, Rectangle rect)
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| pen | const [SharedPtr](../../../system/sharedptr/)\<[Pen](../../pen/)\>\& | Pero, které se použije při kreslení obdélníku |
| rect | [Rectangle](../../rectangle/) | Objekt [Rectangle](../../rectangle/) určuje umístění a velikost obdélníku, který se má vykreslit |

## Viz také

* Typedef [SharedPtr](../../../system/sharedptr/)
* Třída [Pen](../../pen/)
* Třída [Graphics](../)
* Třída [Rectangle](../../rectangle/)
* Jmenný prostor [System::Drawing](../../)
* Knihovna [Aspose.Slides](../../../)