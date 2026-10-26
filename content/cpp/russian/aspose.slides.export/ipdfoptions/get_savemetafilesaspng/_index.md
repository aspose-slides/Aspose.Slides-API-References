---
title: get_SaveMetafilesAsPng()
second_title: Справочник API Aspose.Slides для C++
description: True, если нужно преобразовать все метафайлы, используемые в презентации, в изображения PNG. Чтение bool.
type: docs
weight: 287
url: /ru/aspose.slides.export/ipdfoptions/get_savemetafilesaspng/
---
## IPdfOptions::get_SaveMetafilesAsPng() метод

True, если нужно преобразовать все метафайлы, используемые в презентации, в изображения PNG. Чтение **bool**.

```cpp
virtual bool Aspose::Slides::Export::IPdfOptions::get_SaveMetafilesAsPng()=0
```

## Примечания

По умолчанию **true**. Pdf документ может содержать векторную графику и растровые изображения. Если SaveMetafilesAsPng установлено в true, то исходное изображение Metafile преобразуется в формат Png и сохраняется в Pdf как растровое изображение. Если SaveMetafilesAsPng установлено в false, то исходный Metafile преобразуется в векторную графику Pdf. Каждый подход имеет свои преимущества и недостатки. Например, если Metafile преобразуется в PNG, возможна потеря качества при масштабировании полученного документа. Если Metafile преобразуется в векторную графику Pdf, возможны проблемы с производительностью в средстве просмотра Pdf.

## См. также

* Класс [IPdfOptions](../)
* Пространство имён [Aspose::Slides::Export](../../)
* Библиотека [Aspose.Slides](../../../)