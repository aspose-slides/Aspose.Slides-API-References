---
title: Compress class
second_title: Aspose.Slides для Python через .NET API справочник
description: 
type: docs
url: /ru/aspose.slides.lowcode/compress/
---
## Compress класс

Представляет группу методов, предназначенных для сжатия [`Presentation`](/slides/python-net/ru/aspose.slides/presentation).

Тип Compress раскрывает следующие члены:

## Методы

| Method | Description |
| :- | :- |
| [`compress_presentation(presentation)`](/slides/python-net/ru/aspose.slides.lowcode/compress/compress_presentation/#presentation) | Уменьшает размер презентации, применяя все доступные шаги сжатия:<br/>            <br/>* Удаляет неиспользуемые мастер-слайды **Aspose.Slides.LowCode.Compress.RemoveUnusedMasterSlides(Aspose.Slide**.<br/>* Удаляет неиспользуемые макетные слайды **Aspose.Slides.LowCode.Compress.RemoveUnusedLayoutSlides(Aspose.Slide**.<br/>* Оставляет только глифы, действительно используемые во встроенных шрифтах **Aspose.Slides.LowCode.Compress.CompressEmbeddedFonts(Aspose.Slide**.<br/>* Снижает разрешение изображений до 150 DPI и удаляет обрезанные области изображений **Aspose.Slides.LowCode.Compress.CompressImages(Aspose.Slides.IPresentation,Aspose.Slides.Expor**. |
| [`remove_unused_master_slides(pres)`](/slides/python-net/ru/aspose.slides.lowcode/compress/remove_unused_master_slides/#presentation) | Выполняет сжатие [`Presentation`](/slides/python-net/ru/aspose.slides/presentation) путем удаления неиспользуемых мастер-слайдов. |
| [`remove_unused_layout_slides(pres)`](/slides/python-net/ru/aspose.slides.lowcode/compress/remove_unused_layout_slides/#presentation) | Выполняет сжатие [`Presentation`](/slides/python-net/ru/aspose.slides/presentation) путем удаления неиспользуемых макетных слайдов. |
| [`compress_embedded_fonts(pres)`](/slides/python-net/ru/aspose.slides.lowcode/compress/compress_embedded_fonts/#presentation) | Выполняет сжатие [`Presentation`](/slides/python-net/ru/aspose.slides/presentation) путем удаления неиспользуемых символов из встроенных шрифтов. |
| [`compress_images(presentation, resolution)`](/slides/python-net/ru/aspose.slides.lowcode/compress/compress_images/#ipresentation-asposeslidesexportpicturescompression) | Снижает разрешение изображений в презентации и удаляет их обрезанные области,<br/>            аналогично функции PowerPoint «Compress Pictures», применяемой ко всем изображениям.<br/>            Обрабатываются изображения на слайдах, макетных слайдах и мастер-слайдах, включая изображения внутри групповых фигур<br/>            и заполнения изображениями фигур. |

### См. также
* класс [`Presentation`](/slides/python-net/ru/aspose.slides/presentation)
* модуль [`aspose.slides.lowcode`](/slides/python-net/ru/aspose.slides.lowcode)
* библиотека [`Aspose.Slides`](/slides/python-net)