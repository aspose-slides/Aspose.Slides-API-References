---
title: SetColorMatrix()
second_title: Справочник API Aspose.Slides для C++
description: Устанавливает матрицу цветовой коррекции.
type: docs
weight: 183
url: /ru/system.drawing.imaging/imageattributes/setcolormatrix/
---
## ImageAttributes::SetColorMatrix(const SharedPtr\<ColorMatrix\>\&, ColorMatrixFlag, ColorAdjustType) метод


Устанавливает матрицу цветовой коррекции.

```cpp
void System::Drawing::Imaging::ImageAttributes::SetColorMatrix(const SharedPtr<ColorMatrix> &newColorMatrix, ColorMatrixFlag mode=ColorMatrixFlag::Default, ColorAdjustType type=ColorAdjustType::Default)
```


### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| newColorMatrix | const [SharedPtr](../../../system/sharedptr/)\<[ColorMatrix](../../colormatrix/)\>\& | Матрица цветовой коррекции, которую нужно установить |
| mode | [ColorMatrixFlag](../../colormatrixflag/) | Указывает тип изображения и цвета, которые будут затронуты матрицей цветовой коррекции |
| type | [ColorAdjustType](../../coloradjusttype/) | Указывает тип объектов, для которых устанавливается матрица цветовой коррекции |

## См. также

* Перечисление [ColorMatrixFlag](../../colormatrixflag/)
* Перечисление [ColorAdjustType](../../coloradjusttype/)
* Типовое определение [SharedPtr](../../../system/sharedptr/)
* Класс [ColorMatrix](../../colormatrix/)
* Класс [ImageAttributes](../)
* Пространство имён [System::Drawing::Imaging](../../)
* Библиотека [Aspose.Slides](../../../)