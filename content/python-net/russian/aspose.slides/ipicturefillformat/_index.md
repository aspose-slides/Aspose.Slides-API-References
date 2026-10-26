---
title: IPictureFillFormat class
second_title: Aspose.Slides для Python через .NET API Справочник
description: 
type: docs
url: /ru/aspose.slides/ipicturefillformat/
---
## IPictureFillFormat класс

Представляет стиль заполнения изображением.

Тип IPictureFillFormat раскрывает следующие члены:

## Свойства

| Свойство | Описание |
| :- | :- |
| [`dpi`](/slides/python-net/ru/aspose.slides/ipicturefillformat/dpi/) | Возвращает или задает значение dpi, которое используется для заполнения изображения.<br/>            Чтение/запись **int**. |
| [`picture_fill_mode`](/slides/python-net/ru/aspose.slides/ipicturefillformat/picture_fill_mode/) | Возвращает или задает режим заполнения изображения.<br/>            Чтение/запись [`PictureFillMode`](/slides/python-net/ru/aspose.slides/picturefillmode). |
| [`picture`](/slides/python-net/ru/aspose.slides/ipicturefillformat/picture/) | Возвращает изображение.<br/>            Только для чтения [`ISlidesPicture`](/slides/python-net/ru/aspose.slides/islidespicture). |
| [`crop_left`](/slides/python-net/ru/aspose.slides/ipicturefillformat/crop_left/) | Возвращает или задает количество процентов реальной ширины изображения, которое обрезается слева от картинки.<br/>            Чтение/запись **float**. |
| [`crop_top`](/slides/python-net/ru/aspose.slides/ipicturefillformat/crop_top/) | Возвращает или задает количество процентов реальной высоты изображения, которое обрезается сверху картинки.<br/>            Чтение/запись **float**. |
| [`crop_right`](/slides/python-net/ru/aspose.slides/ipicturefillformat/crop_right/) | Возвращает или задает количество процентов реальной ширины изображения, которое обрезается справа от картинки.<br/>            Чтение/запись **float**. |
| [`crop_bottom`](/slides/python-net/ru/aspose.slides/ipicturefillformat/crop_bottom/) | Возвращает или задает количество процентов реальной высоты изображения, которое обрезается снизу картинки.<br/>            Чтение/запись **float**. |
| [`stretch_offset_left`](/slides/python-net/ru/aspose.slides/ipicturefillformat/stretch_offset_left/) | Возвращает или задает левый край прямоугольника заполнения, определяемый процентным смещением <br/>            от левого края ограничивающего прямоугольника фигуры.<br/>            Положительный процент указывает на внутреннее смещение, отрицательный — на внешнее.<br/>            Чтение/запись **float**. |
| [`stretch_offset_top`](/slides/python-net/ru/aspose.slides/ipicturefillformat/stretch_offset_top/) | Возвращает или задает верхний край прямоугольника заполнения, определяемый процентным смещением <br/>            от верхнего края ограничивающего прямоугольника фигуры.<br/>            Положительный процент указывает на внутреннее смещение, отрицательный — на внешнее.<br/>            Чтение/запись **float**. |
| [`stretch_offset_right`](/slides/python-net/ru/aspose.slides/ipicturefillformat/stretch_offset_right/) | Возвращает или задает правый край прямоугольника заполнения, определяемый процентным смещением <br/>            от правого края ограничивающего прямоугольника фигуры.<br/>            Положительный процент указывает на внутреннее смещение, отрицательный — на внешнее.<br/>            Чтение/запись **float**. |
| [`stretch_offset_bottom`](/slides/python-net/ru/aspose.slides/ipicturefillformat/stretch_offset_bottom/) | Возвращает или задает нижний край прямоугольника заполнения, определяемый процентным смещением <br/>            от нижнего края ограничивающего прямоугольника фигуры.<br/>            Положительный процент указывает на внутреннее смещение, отрицательный — на внешнее.<br/>            Чтение/запись **float**. |
| [`tile_offset_x`](/slides/python-net/ru/aspose.slides/ipicturefillformat/tile_offset_x/) | Возвращает или задает горизонтальное смещение текстуры от начала фигуры в пунктах.<br/>            Положительное значение смещает текстуру вправо, отрицательное — влево.<br/>            Чтение/запись **float**. |
| [`tile_offset_y`](/slides/python-net/ru/aspose.slides/ipicturefillformat/tile_offset_y/) | Возвращает или задает вертикальное смещение текстуры от начала фигуры в пунктах.<br/>            Положительное значение смещает текстуру вниз, отрицательное — вверх.<br/>            Чтение/запись **float**. |
| [`tile_scale_x`](/slides/python-net/ru/aspose.slides/ipicturefillformat/tile_scale_x/) | Возвращает или задает горизонтальный масштаб заполнения текстурой в процентах.<br/>            Чтение/запись **float**. |
| [`tile_scale_y`](/slides/python-net/ru/aspose.slides/ipicturefillformat/tile_scale_y/) | Возвращает или задает вертикальный масштаб заполнения текстурой в процентах.<br/>            Чтение/запись **float**. |
| [`tile_alignment`](/slides/python-net/ru/aspose.slides/ipicturefillformat/tile_alignment/) | Возвращает или задает выравнивание текстуры внутри фигуры. Эта настройка определяет начальную точку шаблона текстуры и способ её повторения по фигуре.<br/>            Чтение/запись [`RectangleAlignment`](/slides/python-net/ru/aspose.slides/rectanglealignment). |
| [`tile_flip`](/slides/python-net/ru/aspose.slides/ipicturefillformat/tile_flip/) | Отражает плитку текстуры по горизонтальной, вертикальной или обеим осям.<br/>            Чтение/запись [`TileFlip`](/slides/python-net/ru/aspose.slides/tileflip). |

## Методы

| Метод | Описание |
| :- | :- |
| [`compress_image(self, delete_cropped_areas_of_image, resolution)`](/slides/python-net/ru/aspose.slides/ipicturefillformat/compress_image/#bool-asposeslidesexportpicturescompression) | Сжимает изображение, уменьшая его размер в зависимости от размеров фигуры и указанного разрешения. При необходимости также удаляет обрезанные области. |
| [`compress_image(self, delete_cropped_areas_of_image, resolution)`](/slides/python-net/ru/aspose.slides/ipicturefillformat/compress_image/#bool-float) | Сжимает изображение, уменьшая его размер в зависимости от размеров фигуры и указанного разрешения. При необходимости также удаляет обрезанные области. |
| [`delete_picture_cropped_areas(self)`](/slides/python-net/ru/aspose.slides/ipicturefillformat/delete_picture_cropped_areas/#) | Удаляет обрезанные области заполнения изображения. |

### См. также
* модуль [`aspose.slides`](/slides/python-net/ru/aspose.slides)
* библиотека [`Aspose.Slides`](/slides/python-net)