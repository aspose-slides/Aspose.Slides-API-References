---
title: PictureFillFormat class
second_title: Aspose.Slides для Python через .NET справочник API
description: 
type: docs
url: /ru/aspose.slides/picturefillformat/
---
## Класс PictureFillFormat

Представляет стиль заливки изображением.

**Наследование:**[`PictureFillFormat`](/slides/python-net/ru/aspose.slides/picturefillformat) → [`PVIObject`](/slides/python-net/ru/aspose.slides/pviobject)

Тип PictureFillFormat раскрывает следующие члены:

## Свойства

| Property | Description |
| :- | :- |
| [`dpi`](/slides/python-net/ru/aspose.slides/picturefillformat/dpi/) | Возвращает или задает dpi, используемый для заполнения изображения.<br/>            Чтение/запись **int**. |
| [`picture_fill_mode`](/slides/python-net/ru/aspose.slides/picturefillformat/picture_fill_mode/) | Возвращает или задает режим заливки изображением.<br/>            Чтение/запись [`PictureFillMode`](/slides/python-net/ru/aspose.slides/picturefillmode). |
| [`picture`](/slides/python-net/ru/aspose.slides/picturefillformat/picture/) | Возвращает изображение.<br/>            Только чтение [`ISlidesPicture`](/slides/python-net/ru/aspose.slides/islidespicture). |
| [`crop_left`](/slides/python-net/ru/aspose.slides/picturefillformat/crop_left/) | Возвращает или задает количество процентов реальной ширины изображения, которое обрезается слева от изображения.<br/>            Чтение/запись **float**. |
| [`crop_top`](/slides/python-net/ru/aspose.slides/picturefillformat/crop_top/) | Возвращает или задает количество процентов реальной высоты изображения, которое обрезается сверху изображения.<br/>            Чтение/запись **float**. |
| [`crop_right`](/slides/python-net/ru/aspose.slides/picturefillformat/crop_right/) | Возвращает или задает количество процентов реальной ширины изображения, которое обрезается справа от изображения.<br/>            Чтение/запись **float**. |
| [`crop_bottom`](/slides/python-net/ru/aspose.slides/picturefillformat/crop_bottom/) | Возвращает или задает количество процентов реальной высоты изображения, которое обрезается снизу изображения.<br/>            Чтение/запись **float**. |
| [`stretch_offset_left`](/slides/python-net/ru/aspose.slides/picturefillformat/stretch_offset_left/) | Возвращает или задает левый край прямоугольника заливки, определяемый процентным смещением от левого края ограничивающего блока фигуры.<br/>            Положительный процент задаёт вложение, отрицательный — выступ.<br/>            Чтение/запись **float**. |
| [`stretch_offset_top`](/slides/python-net/ru/aspose.slides/picturefillformat/stretch_offset_top/) | Возвращает или задает верхний край прямоугольника заливки, определяемый процентным смещением от верхнего края ограничивающего блока фигуры.<br/>            Положительный процент задаёт вложение, отрицательный — выступ.<br/>            Чтение/запись **float**. |
| [`stretch_offset_right`](/slides/python-net/ru/aspose.slides/picturefillformat/stretch_offset_right/) | Возвращает или задает правый край прямоугольника заливки, определяемый процентным смещением от правого края ограничивающего блока фигуры.<br/>            Положительный процент задаёт вложение, отрицательный — выступ.<br/>            Чтение/запись **float**. |
| [`stretch_offset_bottom`](/slides/python-net/ru/aspose.slides/picturefillformat/stretch_offset_bottom/) | Возвращает или задает нижний край прямоугольника заливки, определяемый процентным смещением от нижнего края ограничивающего блока фигуры.<br/>            Положительный процент задаёт вложение, отрицательный — выступ.<br/>            Чтение/запись **float**. |
| [`tile_offset_x`](/slides/python-net/ru/aspose.slides/picturefillformat/tile_offset_x/) | Возвращает или задает горизонтальное смещение текстуры от начала координат фигуры в пунктах.<br/>            Положительное значение перемещает текстуру вправо, отрицательное — влево.<br/>            Чтение/запись **float**. |
| [`tile_offset_y`](/slides/python-net/ru/aspose.slides/picturefillformat/tile_offset_y/) | Возвращает или задает вертикальное смещение текстуры от начала координат фигуры в пунктах.<br/>            Положительное значение перемещает текстуру вниз, отрицательное — вверх.<br/>            Чтение/запись **float**. |
| [`tile_scale_x`](/slides/python-net/ru/aspose.slides/picturefillformat/tile_scale_x/) | Возвращает или задает горизонтальный масштаб заполнения текстурой в процентах.<br/>            Чтение/запись **float**. |
| [`tile_scale_y`](/slides/python-net/ru/aspose.slides/picturefillformat/tile_scale_y/) | Возвращает или задает вертикальный масштаб заполнения текстурой в процентах.<br/>            Чтение/запись **float**. |
| [`tile_alignment`](/slides/python-net/ru/aspose.slides/picturefillformat/tile_alignment/) | Возвращает или задает способ выравнивания текстуры внутри фигуры. Эта настройка определяет начальную точку шаблона текстуры и способ её повторения по фигуре.<br/>            Чтение/запись [`RectangleAlignment`](/slides/python-net/ru/aspose.slides/rectanglealignment). |
| [`tile_flip`](/slides/python-net/ru/aspose.slides/picturefillformat/tile_flip/) | Переворачивает плитку текстуры по горизонтали, вертикали или обеим осям.<br/>            Чтение/запись [`TileFlip`](/slides/python-net/ru/aspose.slides/tileflip). |
| [`slide`](/slides/python-net/ru/aspose.slides/picturefillformat/slide/) |  |
| [`presentation`](/slides/python-net/ru/aspose.slides/picturefillformat/presentation/) |  |

## Методы

| Method | Description |
| :- | :- |
| [`compress_image(self, delete_cropped_areas_of_image, resolution)`](/slides/python-net/ru/aspose.slides/picturefillformat/compress_image/#bool-asposeslidesexportpicturescompression) | Сжимает изображение, уменьшая его размер в зависимости от размера фигуры и указанного разрешения. При желании также удаляет обрезанные области. |
| [`compress_image(self, delete_cropped_areas_of_image, resolution)`](/slides/python-net/ru/aspose.slides/picturefillformat/compress_image/#bool-float) | Сжимает изображение, уменьшая его размер в зависимости от размера фигуры и указанного разрешения. При желании также удаляет обрезанные области. |
| [`delete_picture_cropped_areas(self)`](/slides/python-net/ru/aspose.slides/picturefillformat/delete_picture_cropped_areas/#) | Удаляет обрезанные области заливки изображения. |

### См. также
* класс [`PictureFillFormat`](/slides/python-net/ru/aspose.slides/picturefillformat)
* класс [`PVIObject`](/slides/python-net/ru/aspose.slides/pviobject)
* модуль [`aspose.slides`](/slides/python-net/ru/aspose.slides)
* библиотека [`Aspose.Slides`](/slides/python-net)