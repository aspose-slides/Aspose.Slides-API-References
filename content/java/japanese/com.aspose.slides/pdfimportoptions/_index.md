---
title: PdfImportOptions
second_title: Aspose.Slides の Java API リファレンス
description: PDF インポートオプションを表します
type: docs
url: /ja/com.aspose.slides/pdfimportoptions/
---
**継承:**
java.lang.Object
```
public class PdfImportOptions
```

PDF インポートオプションを表します
## コンストラクター

| コンストラクター | 説明 |
| --- | --- |
| [PdfImportOptions()](#PdfImportOptions--) |  |
## メソッド

| メソッド | 説明 |
| --- | --- |
| [getDetectTables()](#getDetectTables--) | PDF ファイルをインポートする際にテーブル検出を行うかどうかを決定します。 |
| [setDetectTables(boolean value)](#setDetectTables-boolean-) | PDF ファイルをインポートする際にテーブル検出を行うかどうかを決定します。 |
### PdfImportOptions() {#PdfImportOptions--}
```
public PdfImportOptions()
```


### getDetectTables() {#getDetectTables--}
```
public final boolean getDetectTables()
```


PDF ファイルをインポートする際にテーブル検出を行うかどうかを決定します。

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
>          // テーブル検出を設定する
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


PDF ファイルをインポートする際にテーブル検出を行うかどうかを決定します。

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
>          // テーブル検出を設定する
>          pres.getSlides().addFromPdf(stream, pdfImportOptions);
>      }
> 
>      pres.save("fromPdfDocument.pptx", SaveFormat.Pptx);
>  } catch (IOException e) {
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | boolean |  |