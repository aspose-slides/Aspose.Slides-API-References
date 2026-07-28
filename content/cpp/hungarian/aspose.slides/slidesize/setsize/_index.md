---
title: SetSize()
second_title: Aspose.Slides C++ API hivatkozás
description: Beállítja a dia méretét típus alapján, és átméretezi a meglévő tartalmat.
type: docs
weight: 53
url: /hu/aspose.slides/slidesize/setsize/
---
## SlideSize::SetSize(SlideSizeType, SlideSizeScaleType) metódus


Beállítja a dia méretét típus alapján, és átméretezi a meglévő tartalmat.

```cpp
void Aspose::Slides::SlideSize::SetSize(SlideSizeType type, SlideSizeScaleType scaleType) override
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| type | [SlideSizeType](../../slidesizetype/) | Az alkalmazandó előre definiált dia méret. |
| scaleType | [SlideSizeScaleType](../../slidesizescaletype/) | A használandó tartalom skálázási mód. |
## Megjegyzések


A(z) [SlideSizeType::Custom](../../slidesizetype/) kivételével bármely érték hozzárendelése a [SlideSize::get_Size](../get_size/)-t a kiválasztott típus alapján állítja be, miközben megőrzi a [SlideSize::get_Orientation](../get_orientation/)-t. 

## SlideSize::SetSize(float, float, SlideSizeScaleType) metódus


Kifejezetten beállítja a dia méreteit, és átméretezi a meglévő tartalmat.

```cpp
void Aspose::Slides::SlideSize::SetSize(float width, float height, SlideSizeScaleType scaleType) override
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| width | **float** | Az új dia szélessége pontban. |
| height | **float** | Az új dia magassága pontban. |
| scaleType | [SlideSizeScaleType](../../slidesizescaletype/) | A használandó tartalom skálázási mód. |
## Megjegyzések


Ez visszaállítja a [SlideSize::get_Type](../get_type/) tulajdonságot [SlideSizeType::Custom](../../slidesizetype/) értékére, és beállítja a [Orientation](../../orientation/)-t. 

## Lásd még

* Enum [SlideSizeType](../../slidesizetype/)
* Enum [SlideSizeScaleType](../../slidesizescaletype/)
* Osztály [SlideSize](../)
* Névtér [Aspose::Slides](../../)
* Könyvtár [Aspose.Slides](../../../)