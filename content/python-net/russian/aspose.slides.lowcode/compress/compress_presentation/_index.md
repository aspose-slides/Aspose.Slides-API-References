---
title: compress_presentation method
second_title: Aspose.Slides для Python через .NET справочник API
description: 
type: docs
url: /ru/aspose.slides.lowcode/compress/compress_presentation/
weight: 30
---
## compress_presentation(presentation) {#presentation}
Уменьшает размер презентации, применяя все доступные шаги сжатия:
            
* Удаляет неиспользуемые мастер-слайды **Aspose.Slides.LowCode.Compress.RemoveUnusedMasterSlides(Aspose.Slide**.
* Удаляет неиспользуемые макетные слайды **Aspose.Slides.LowCode.Compress.RemoveUnusedLayoutSlides(Aspose.Slide**.
* Оставляет только глифы, действительно используемые во встроенных шрифтах **Aspose.Slides.LowCode.Compress.CompressEmbeddedFonts(Aspose.Slide**.
* Уменьшает разрешение изображений до 150 DPI и удаляет обрезанные области изображений **Aspose.Slides.LowCode.Compress.CompressImages(Aspose.Slides.IPresentation,Aspose.Slides.Expor**.


```python
@staticmethod
def compress_presentation(presentation):
    ...
```


| Параметр | Тип | Описание |
| :- | :- | :- |
| presentation | [`Presentation`](/slides/python-net/ru/aspose.slides/presentation) | Презентация для сжатия. |

### Замечания

Чтобы настроить сжатие, например использовать другое разрешение изображений или пропустить шаг, вызовите указанные выше методы по отдельности вместо этого. Обрезанные области изображений удаляются навсегда и не могут быть восстановлены в PowerPoint.

### Исключения

| Исключение | Описание |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentNullException))** | `presentation` равно `None`. |



### См. также
* класс [`Compress`](/slides/python-net/ru/aspose.slides.lowcode/compress)
* класс [`Presentation`](/slides/python-net/ru/aspose.slides/presentation)
* модуль [`aspose.slides.lowcode`](/slides/python-net/ru/aspose.slides.lowcode)
* библиотека [`Aspose.Slides`](/slides/python-net)