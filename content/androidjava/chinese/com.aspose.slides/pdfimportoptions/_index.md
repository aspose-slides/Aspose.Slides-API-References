---
title: PdfImportOptions
second_title: Aspose.Slides for Android via Java API 参考
description: 表示 PDF 导入选项
type: docs
url: /zh/com.aspose.slides/pdfimportoptions/
---
**继承：**
java.lang.Object
```
public class PdfImportOptions
```

表示 PDF 导入选项
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [PdfImportOptions()](#PdfImportOptions--) |  |
## 方法

| 方法 | 描述 |
| --- | --- |
| [getDetectTables()](#getDetectTables--) | 确定在导入 PDF 文件时是否检测表格。 |
| [setDetectTables(boolean value)](#setDetectTables-boolean-) | 确定在导入 PDF 文件时是否检测表格。 |
### PdfImportOptions() {#PdfImportOptions--}
```
public PdfImportOptions()
```


### getDetectTables() {#getDetectTables--}
```
public final boolean getDetectTables()
```


确定在导入 PDF 文件时是否检测表格。

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
>          // set detecting tables
>          pres.getSlides().addFromPdf(stream, pdfImportOptions);
>      }
> 
>      pres.save("fromPdfDocument.pptx", SaveFormat.Pptx);
>  } catch (IOException e) {
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Returns:**
boolean
### setDetectTables(boolean value) {#setDetectTables-boolean-}
```
public final void setDetectTables(boolean value)


确定在导入 PDF 文件时是否检测表格。

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
>          // set detecting tables
>          pres.getSlides().addFromPdf(stream, pdfImportOptions);
>      }
> 
>      pres.save("fromPdfDocument.pptx", SaveFormat.Pptx);
>  } catch (IOException e) {
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | boolean |  |