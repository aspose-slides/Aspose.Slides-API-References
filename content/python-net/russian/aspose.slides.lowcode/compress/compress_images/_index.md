---
title: compress_images method
second_title: Aspose.Slides для Python через .NET API Справка
description: 
type: docs
url: /ru/aspose.slides.lowcode/compress/compress_images/
weight: 20
---
## compress_images(presentation, resolution) {#ipresentation-asposeslidesexportpicturescompression}
Уменьшает разрешение изображений в презентации и удаляет их обрезанные области, аналогично функции «Compress Pictures» в PowerPoint, применяемой ко всем изображениям. Изображения на слайдах, шаблонах слайдов и мастер-слайдах обрабатываются, включая изображения внутри групповых фигур и заполнения фигур изображениями.

```python
@staticmethod
def compress_images(presentation, resolution):
    ...
```

| Параметр | Тип | Описание |
| :- | :- | :- |
| presentation | [`IPresentation`](/slides/python-net/ru/aspose.slides/ipresentation) | Презентация для обработки. |
| resolution | [`PicturesCompression`](/slides/python-net/ru/aspose.slides.export/picturescompression) | Целевое разрешение относительно размера, в котором отображается каждое изображение.<br/><br/>[`PicturesCompression.DOCUMENT_RESOLUTION`](/slides/python-net/ru/aspose.slides.export/picturescompression/DOCUMENT_RESOLUTION) оставляет изображения без изменений. |

### Примечания

Изображения, уже имеющие целевое разрешение или ниже его, остаются без изменений; изображения никогда не увеличиваются.

Не обрабатываются: фоны слайдов, заливки ячеек таблиц, диаграммы, SmartArt, GIF-изображения (для сохранения анимации), SVG и метафайлы (EMF/WMF).

Обрезанные области удаляются окончательно и не могут быть восстановлены в PowerPoint.

### Исключения

| Исключение | Описание |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentNullException))** | `presentation` равен `None`. |

### См. также
* класс [`Compress`](/slides/python-net/ru/aspose.slides.lowcode/compress)
* класс [`IPresentation`](/slides/python-net/ru/aspose.slides/ipresentation)
* перечисление [`PicturesCompression`](/slides/python-net/ru/aspose.slides.export/picturescompression)
* модуль [`aspose.slides.lowcode`](/slides/python-net/ru/aspose.slides.lowcode)
* библиотека [`Aspose.Slides`](/slides/python-net)