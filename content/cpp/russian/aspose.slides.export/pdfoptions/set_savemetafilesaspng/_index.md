---
title: set_SaveMetafilesAsPng()
second_title: Aspose.Slides для C++ справочник API
description: True для конвертации всех метафайлов, используемых в презентации, в изображения PNG. Записать bool.
type: docs
weight: 339
url: /ru/aspose.slides.export/pdfoptions/set_savemetafilesaspng/
---
## PdfOptions::set_SaveMetafilesAsPng(bool) метод


True для конвертации всех метафайлов, используемых в презентации, в изображения PNG. Записать **bool**.

```cpp
void Aspose::Slides::Export::PdfOptions::set_SaveMetafilesAsPng(bool value) override
```

## Примечания


По умолчанию **true**. Документ Pdf может содержать векторную графику и растровые изображения. Если SaveMetafilesAsPng установлено в true, то исходное изображение Metafile конвертируется в формат Png и сохраняется в Pdf как растровое изображение. Если SaveMetafilesAsPng установлено в false, то исходный Metafile конвертируется во векторную графику Pdf. Каждый подход имеет преимущества и недостатки. Например, если Metafile конвертируется в PNG, возможна некоторая потеря качества при масштабировании полученного документа. Если Metafile конвертируется во векторную графику Pdf, возможны проблемы с производительностью в средстве просмотра Pdf.

## См. также

* Класс [PdfOptions](../)
* Пространство имён [Aspose::Slides::Export](../../)
* Библиотека [Aspose.Slides](../../../)