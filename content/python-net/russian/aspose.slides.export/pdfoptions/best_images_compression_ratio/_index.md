---
title: best_images_compression_ratio property
second_title: Aspose.Slides для Python через .NET API Reference
description: 
type: docs
url: /ru/aspose.slides.export/pdfoptions/best_images_compression_ratio/
weight: 60
---
## best_images_compression_ratio свойство
Указывает, должна ли для каждого изображения автоматически выбираться наиболее эффективная компрессия (вместо используемой по умолчанию) 
            автоматически. Если значение установлено в **bool**.true, для каждого изображения в презентации будет выбран наиболее подходящий алгоритм компрессии 
            выбран, что приведёт к уменьшению размера получаемого PDF-документа. 
            Выбор оптимального уровня компрессии изображений требует значительных вычислительных ресурсов и 
            дополнительного объёма ОЗУ, при этом эта опция по умолчанию равна **bool**.false.

### Примечания

По умолчанию **bool**.false.

### Определение:
```python
@property
def best_images_compression_ratio(self):
    ...

@best_images_compression_ratio.setter
def best_images_compression_ratio(self, value):
    ...
```

### Смотрите также
* класс [`PdfOptions`](/slides/python-net/ru/aspose.slides.export/pdfoptions)
* модуль [`aspose.slides.export`](/slides/python-net/ru/aspose.slides.export)
* библиотека [`Aspose.Slides`](/slides/python-net)