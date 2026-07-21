---
title: get_SaveMetafilesAsPng()
second_title: Справочник API Aspose.Slides для C++
description: True, чтобы преобразовать все метафайлы, используемые в презентации, в изображения PNG. Читать bool.
type: docs
weight: 326
url: /ru/aspose.slides.export/pdfoptions/get_savemetafilesaspng/
---
## PdfOptions::get_SaveMetafilesAsPng() метод

True, чтобы преобразовать все метафайлы, используемые в презентации, в изображения PNG. Читать **bool**.

```cpp
bool Aspose::Slides::Export::PdfOptions::get_SaveMetafilesAsPng() override
```

## Примечания

По умолчанию **true**. Документ Pdf может содержать векторную графику и растровые изображения. Если SaveMetafilesAsPng установлен в true, то исходное изображение Metafile преобразуется в формат Png и сохраняется в Pdf как растровое изображение. Если SaveMetafilesAsPng установлен в false, то исходный Metafile преобразуется в векторную графику Pdf. Каждый подход имеет преимущества и недостатки. Например, если Metafile преобразуется в PNG, возможна потеря качества при масштабировании полученного документа. Если Metafile преобразуется в векторную графику Pdf, возможны проблемы с производительностью в средство просмотра Pdf.

## См. также

* Класс [PdfOptions](../)
* Пространство имён [Aspose::Slides::Export](../../)
* Библиотека [Aspose.Slides](../../../)