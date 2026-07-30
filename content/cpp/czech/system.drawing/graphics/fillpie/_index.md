---
title: FillPie()
second_title: Aspose.Slides pro C++ API Reference
description: Vyplní zadaný výsek pomocí zadaného brush na ploše reprezentované aktuálním objektem.
type: docs
weight: 274
url: /cs/system.drawing/graphics/fillpie/
---
## Graphics::FillPie(const SharedPtr\<Brush\>\&, int, int, int, int, int, int) metoda

Vyplní zadaný výsek pomocí zadaného brush na ploše reprezentované aktuálním objektem.

```cpp
void System::Drawing::Graphics::FillPie(const SharedPtr<Brush> &brush, int x, int y, int width, int height, int startAngle, int sweepAngle)
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| brush | const [SharedPtr](../../../system/sharedptr/)\<[Brush](../../brush/)\>\& | brush, který se použije při vyplňování výseku |
| x | int | Souřadnice X levého horního rohu obdélníku, který určuje elipsu |
| y | int | Souřadnice Y levého horního rohu obdélníku, který určuje elipsu |
| width | int | Šířka obdélníku, který určuje elipsu |
| height | int | Výška obdélníku, který určuje elipsu |
| startAngle | int | Úhel ve stupních měřený po směru hodinových ručiček od osy X k počátečnímu bodu výseku |
| sweepAngle | int | Úhel ve stupních měřený po směru hodinových ručiček od **startAngle** k koncovému bodu výseku |

## Graphics::FillPie(const SharedPtr\<Brush\>\&, float, float, float, float, float, float) metoda

Vyplní zadaný výsek pomocí zadaného brush na ploše reprezentované aktuálním objektem.

```cpp
void System::Drawing::Graphics::FillPie(const SharedPtr<Brush> &brush, float x, float y, float width, float height, float startAngle, float sweepAngle)
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| brush | const [SharedPtr](../../../system/sharedptr/)\<[Brush](../../brush/)\>\& | brush, který se použije při vyplňování výseku |
| x | **float** | Souřadnice X levého horního rohu obdélníku, který určuje elipsu |
| y | **float** | Souřadnice Y levého horního rohu obdélníku, který určuje elipsu |
| width | **float** | Šířka obdélníku, který určuje elipsu |
| height | **float** | Výška obdélníku, který určuje elipsu |
| startAngle | **float** | Úhel ve stupních měřený po směru hodinových ručiček od osy X k počátečnímu bodu výseku |
| sweepAngle | **float** | Úhel ve stupních měřený po směru hodinových ručiček od **startAngle** k koncovému bodu výseku |

## Graphics::FillPie(const SharedPtr\<Brush\>\&, Rectangle, float, float) metoda

Vyplní zadaný výsek pomocí zadaného brush na ploše reprezentované aktuálním objektem.

```cpp
void System::Drawing::Graphics::FillPie(const SharedPtr<Brush> &brush, Rectangle rect, float startAngle, float sweepAngle)
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| brush | const [SharedPtr](../../../system/sharedptr/)\<[Brush](../../brush/)\>\& | brush, který se použije při vyplňování výseku |
| rect | [Rectangle](../../rectangle/) | Obdélník, který určuje elipsu |
| startAngle | **float** | Úhel ve stupních měřený po směru hodinových ručiček od osy X k počátečnímu bodu výseku |
| sweepAngle | **float** | Úhel ve stupních měřený po směru hodinových ručiček od **startAngle** k koncovému bodu výseku |

## Viz také

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Brush](../../brush/)
* Class [Graphics](../)
* Class [Rectangle](../../rectangle/)
* Namespace [System::Drawing](../../)
* Library [Aspose.Slides](../../../)