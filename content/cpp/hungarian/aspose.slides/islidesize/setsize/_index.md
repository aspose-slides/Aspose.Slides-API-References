---
title: SetSize()
second_title: Aspose.Slides C++ API referencia
description: "Beállítja a dia méretét típus alapján, és méretezni a meglévő tartalmat. A SlideSizeType::Custom kivételével bármely érték hozzárendelése a kiválasztott típus szerint módosítja az ISlideSize::get_Size értékét, miközben megőrzi az ISlideSize::get_Orientation értéket."
type: docs
weight: 53
url: /hu/aspose.slides/islidesize/setsize/
---
## ISlideSize::SetSize(SlideSizeType, SlideSizeScaleType) metódus

Beállítja a dia méretét típussal, és méretezése a meglévő tartalmat. A [SlideSizeType::Custom](../../slidesizetype/)-tól eltérő érték hozzárendelése a kiválasztott típus alapján módosítja a [ISlideSize::get_Size](../get_size/)-t, miközben megőrzi a [ISlideSize::get_Orientation](../get_orientation/)-t.

```cpp
virtual void Aspose::Slides::ISlideSize::SetSize(SlideSizeType type, SlideSizeScaleType scaleType)=0
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| type | [SlideSizeType](../../slidesizetype/) | A alkalmazandó előre definiált dia méret. |
| scaleType | [SlideSizeScaleType](../../slidesizescaletype/) | A használandó tartalom méretezési mód. |
## Megjegyzés

A [SlideSizeType::Custom](../../slidesizetype/)-tól eltérő érték hozzárendelése a kiválasztott típus alapján módosítja a [System::Drawing::Size](../../../system.drawing/size/)-t, miközben megőrzi a [Orientation](../../orientation/)-t. 

## ISlideSize::SetSize(float, float, SlideSizeScaleType) metódus

Explicit módon beállítja a dia dimenziókat, és méretezése a meglévő tartalmat. Ez visszaállítja a [ISlideSize::get_Type](../get_type/) értékét [SlideSizeType::Custom](../../slidesizetype/)-ra, és beállítja a [ISlideSize::get_Orientation](../get_orientation/)-t.

```cpp
virtual void Aspose::Slides::ISlideSize::SetSize(float width, float height, SlideSizeScaleType scaleType)=0
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| width | **float** | Az új dia szélessége pontban. |
| height | **float** | Az új dia magassága pontban. |
| scaleType | [SlideSizeScaleType](../../slidesizescaletype/) | A használni kívánt tartalom méretezési mód. |
## Megjegyzés

Ez visszaállítja a [ISlideSize::get_Type](../get_type/) tulajdonságot [SlideSizeType::Custom](../../slidesizetype/)-ra és beállítja a [Orientation](../../orientation/)-t. 

## Lásd még

* Enum [SlideSizeType](../../slidesizetype/)
* Enum [SlideSizeScaleType](../../slidesizescaletype/)
* Osztály [ISlideSize](../)
* Névtér [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)