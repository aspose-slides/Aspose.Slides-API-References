---
title: save_metafiles_as_png property
second_title: Aspose.Slides для Python через .NET справочник API
description: 
type: docs
url: /ru/aspose.slides.export/ipdfoptions/save_metafiles_as_png/
weight: 190
---
## save_metafiles_as_png свойство
True to convert all metafiles used in a presentation to the PNG images.
            Read/write **bool**.


### Примечания

По умолчанию **true** .
            Документ Pdf может содержать векторную графику и растровые изображения. 
            Если SaveMetafilesAsPng установлен в true, то исходное изображение Metafile преобразуется в формат Png и сохраняется в Pdf как растровое изображение. Если SaveMetafilesAsPng установлен в false, то исходный Metafile преобразуется в векторную графику Pdf. Каждый подход имеет свои преимущества и недостатки. Например, если Metafile преобразуется в PNG, то при масштабировании полученного документа возможна небольшая потеря качества. Если Metafile преобразуется в векторную графику Pdf, то возможны проблемы с производительностью в средстве просмотра Pdf.

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
* класс [`IPdfOptions`](/slides/python-net/ru/aspose.slides.export/ipdfoptions)
* модуль [`aspose.slides.export`](/slides/python-net/ru/aspose.slides.export)
* библиотека [`Aspose.Slides`](/slides/python-net)