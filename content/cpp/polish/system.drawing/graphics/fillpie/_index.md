---
title: FillPie()
second_title: Aspose.Slides dla C++ odniesienie API
description: Wypełnia określony wycinek koła przy użyciu określonego pędzla na powierzchni reprezentowanej przez bieżący obiekt.
type: docs
weight: 274
url: /pl/system.drawing/graphics/fillpie/
---
## Graphics::FillPie(const SharedPtr\<Brush\>\&, int, int, int, int, int, int) metoda

Wypełnia określony wycinek koła przy użyciu określonego pędzla na powierzchni reprezentowanej przez bieżący obiekt.

```cpp
void System::Drawing::Graphics::FillPie(const SharedPtr<Brush> &brush, int x, int y, int width, int height, int startAngle, int sweepAngle)
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| brush | const [SharedPtr](../../../system/sharedptr/)\<[Brush](../../brush/)\>\& | Pędzel używany do wypełniania wycinka koła |
| x | int | Współrzędna X lewego górnego rogu prostokąta definiującego elipsę |
| y | int | Współrzędna Y lewego górnego rogu prostokąta definiującego elipsę |
| width | int | Szerokość prostokąta definiującego elipsę |
| height | int | Wysokość prostokąta definiującego elipsę |
| startAngle | int | Kąt w stopniach mierzony zgodnie z ruchem wskazówek zegara od osi X do punktu początkowego wycinka koła |
| sweepAngle | int | Kąt w stopniach mierzony zgodnie z ruchem wskazówek zegara od **startAngle** do punktu końcowego wycinka koła |

## Graphics::FillPie(const SharedPtr\<Brush\>\&, float, float, float, float, float, float) metoda

Wypełnia określony wycinek koła przy użyciu określonego pędzla na powierzchni reprezentowanej przez bieżący obiekt.

```cpp
void System::Drawing::Graphics::FillPie(const SharedPtr<Brush> &brush, float x, float y, float width, float height, float startAngle, float sweepAngle)
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| brush | const [SharedPtr](../../../system/sharedptr/)\<[Brush](../../brush/)\>\& | Pędzel używany do wypełniania wycinka koła |
| x | **float** | Współrzędna X lewego górnego rogu prostokąta definiującego elipsę |
| y | **float** | Współrzędna Y lewego górnego rogu prostokąta definiującego elipsę |
| width | **float** | Szerokość prostokąta definiującego elipsę |
| height | **float** | Wysokość prostokąta definiującego elipsę |
| startAngle | **float** | Kąt w stopniach mierzony zgodnie z ruchem wskazówek zegara od osi X do punktu początkowego wycinka koła |
| sweepAngle | **float** | Kąt w stopniach mierzony zgodnie z ruchem wskazówek zegara od **startAngle** do punktu końcowego wycinka koła |

## Graphics::FillPie(const SharedPtr\<Brush\>\&, Rectangle, float, float) metoda

Wypełnia określony wycinek koła przy użyciu określonego pędzla na powierzchni reprezentowanej przez bieżący obiekt.

```cpp
void System::Drawing::Graphics::FillPie(const SharedPtr<Brush> &brush, Rectangle rect, float startAngle, float sweepAngle)
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| brush | const [SharedPtr](../../../system/sharedptr/)\<[Brush](../../brush/)\>\& | Pędzel używany do wypełniania wycinka koła |
| rect | [Rectangle](../../rectangle/) | Prostokąt definiujący elipsę |
| startAngle | **float** | Kąt w stopniach mierzony zgodnie z ruchem wskazówek zegara od osi X do punktu początkowego wycinka koła |
| sweepAngle | **float** | Kąt w stopniach mierzony zgodnie z ruchem wskazówek zegara od **startAngle** do punktu końcowego wycinka koła |

## Zobacz także

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasa [Brush](../../brush/)
* Klasa [Graphics](../)
* Klasa [Rectangle](../../rectangle/)
* Przestrzeń nazw [System::Drawing](../../)
* Library [Aspose.Slides](../../../)