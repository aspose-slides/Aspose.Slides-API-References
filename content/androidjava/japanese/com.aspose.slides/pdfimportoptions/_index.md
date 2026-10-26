---
title: PdfImportOptions
second_title: Java API リファレンスによる Android 用 Aspose.Slides
description: PDF インポート オプションを表します
type: docs
url: /ja/com.aspose.slides/pdfimportoptions/
---
**継承:**
java.lang.Object
```
public class PdfImportOptions
```

PDFインポートオプションを表します
## コンストラクター

| コンストラクタ | 説明 |
| --- | --- |
| [PdfImportOptions()](#PdfImportOptions--) |  |
## メソッド

| メソッド | 説明 |
| --- | --- |
| [getDetectTables()](#getDetectTables--) | PDFファイルのインポート時にテーブルを検出するかどうかを決定します。 |
| [setDetectTables(boolean value)](#setDetectTables-boolean-) | PDFファイルのインポート時にテーブルを検出するかどうかを決定します。 |
### PdfImportOptions() {#PdfImportOptions--}
```
public PdfImportOptions()
```

### getDetectTables() {#getDetectTables--}
```
public final boolean getDetectTables()
```

PDFファイルのインポート時にテーブルを検出するかどうかを決定します。

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
>          // テーブル検出を設定
>          pres.getSlides().addFromPdf(stream, pdfImportOptions);
>      }
> 
>      pres.save("fromPdfDocument.pptx", SaveFormat.Pptx);
>  } catch (IOException e) {
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**戻り値:**
boolean
### setDetectTables(boolean value) {#setDetectTables-boolean-}
```
public final void setDetectTables(boolean value)
```

PDFファイルのインポート時にテーブルを検出するかどうかを決定します。

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
>          // テーブル検出を設定
>          pres.getSlides().addFromPdf(stream, pdfImportOptions);
>      }
> 
>      pres.save("fromPdfDocument.pptx", SaveFormat.Pptx);
>  } catch (IOException e) {
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | boolean |  |