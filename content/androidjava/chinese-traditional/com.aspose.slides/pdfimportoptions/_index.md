---
title: PdfImportOptions
second_title: Aspose.Slides for Android 透過 Java API 參考
description: 表示 PDF 匯入選項
type: docs
url: /zh-hant/com.aspose.slides/pdfimportoptions/
---
**繼承：**
java.lang.Object
```
public class PdfImportOptions
```

表示 PDF 匯入選項
## 建構函式

| 建構函式 | 說明 |
| --- | --- |
| [PdfImportOptions()](#PdfImportOptions--) |  |
## 方法

| 方法 | 說明 |
| --- | --- |
| [getDetectTables()](#getDetectTables--) | 判斷在匯入 PDF 檔案時是否偵測表格。 |
| [setDetectTables(boolean value)](#setDetectTables-boolean-) | 判斷在匯入 PDF 檔案時是否偵測表格。 |
### PdfImportOptions() {#PdfImportOptions--}
```
public PdfImportOptions()
```


### getDetectTables() {#getDetectTables--}
```
public final boolean getDetectTables()
```


判斷在匯入 PDF 檔案時是否偵測表格。

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
>          // 設定偵測表格
>          pres.getSlides().addFromPdf(stream, pdfImportOptions);
>      }
> 
>      pres.save("fromPdfDocument.pptx", SaveFormat.Pptx);
>  } catch (IOException e) {
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**傳回值：**
boolean
### setDetectTables(boolean value) {#setDetectTables-boolean-}
```
public final void setDetectTables(boolean value)
```


判斷在匯入 PDF 檔案時是否偵測表格。

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
>          // 設定偵測表格
>          pres.getSlides().addFromPdf(stream, pdfImportOptions);
>      }
> 
>      pres.save("fromPdfDocument.pptx", SaveFormat.Pptx);
>  } catch (IOException e) {
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | boolean |  |