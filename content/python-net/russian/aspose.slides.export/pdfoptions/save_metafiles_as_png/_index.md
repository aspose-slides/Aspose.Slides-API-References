---
title: save_metafiles_as_png property
second_title: Aspose.Slides для Python через .NET справочник API
description: 
type: docs
url: /ru/aspose.slides.export/pdfoptions/save_metafiles_as_png/
weight: 200
---
## save_metafiles_as_png свойство
True, чтобы преобразовать все метафайлы, используемые в презентации, в изображения PNG.
            Чтение/запись **bool**.

### Примечания

Default is **true** .
            Документ PDF может содержать векторную графику и растровые изображения. 
            Если SaveMetafilesAsPng установлен в true, то исходное изображение Metafile 
            преобразуется в формат Png и сохраняется в Pdf как растровое 
            изображение. Если SaveMetafilesAsPng установлен в false, то исходный Metafile 
            преобразуется в векторную графику Pdf. Каждый подход имеет преимущества 
            и недостатки. Например, если Metafile преобразуется в PNG, 
            то возможна некоторая потеря качества при масштабировании 
            полученного документа. Если Metafile преобразуется в векторную графику Pdf, 
            то могут возникнуть проблемы с производительностью в инструменте просмотра Pdf.

### Определение:
```python
@property
def save_metafiles_as_png(self):
    ...

@save_metafiles_as_png.setter
def save_metafiles_as_png(self, value):
    ...
```

### См. также
* класс [`PdfOptions`](/slides/python-net/ru/aspose.slides.export/pdfoptions)
* модуль [`aspose.slides.export`](/slides/python-net/ru/aspose.slides.export)
* библиотека [`Aspose.Slides`](/slides/python-net)