---
title: PdfImportOptions
second_title: Aspose.Slides для Android через справочник Java API
description: Представляет параметры импорта PDF
type: docs
url: /ru/com.aspose.slides/pdfimportoptions/
---
**Наследование:**
java.lang.Object
```
public class PdfImportOptions
```

Представляет параметры импорта PDF
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [PdfImportOptions()](#PdfImportOptions--) |  |
## Методы

| Метод | Описание |
| --- | --- |
| [getDetectTables()](#getDetectTables--) | Определяет, следует ли обнаруживать таблицы при импорте PDF-файла. |
| [setDetectTables(boolean value)](#setDetectTables-boolean-) | Определяет, следует ли обнаруживать таблицы при импорте PDF-файла. |
### PdfImportOptions() {#PdfImportOptions--}
```
public PdfImportOptions()
```


### getDetectTables() {#getDetectTables--}
```
public final boolean getDetectTables()
```


Определяет, следует ли обнаруживать таблицы при импорте PDF-файла.

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation();
>  try {
>      PdfImportOptions pdfImportOptions = new PdfImportOptions();
>      pdfImportOptions.setDetectTables(true);
> 
>      FileInputStream stream = new FileInputStream("document.pdf");
>      {
>          // установить обнаружение таблиц
>          pres.getSlides().addFromPdf(stream, pdfImportOptions);
>      }
> 
>      pres.save("fromPdfDocument.pptx", SaveFormat.Pptx);
>  } catch (IOException e) {
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Возвращаемое значение:**
boolean
### setDetectTables(boolean value) {#setDetectTables-boolean-}
```
public final void setDetectTables(boolean value)
```


Определяет, следует ли обнаруживать таблицы при импорте PDF-файла.

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation();
>  try {
>      PdfImportOptions pdfImportOptions = new PdfImportOptions();
>      pdfImportOptions.setDetectTables(true);
> 
>      FileInputStream stream = new FileInputStream("document.pdf");
>      {
>          // установить обнаружение таблиц
>          pres.getSlides().addFromPdf(stream, pdfImportOptions);
>      }
> 
>      pres.save("fromPdfDocument.pptx", SaveFormat.Pptx);
>  } catch (IOException e) {
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | boolean |  |