---
title: PdfImportOptions
second_title: Java API 참조를 통한 Android용 Aspose.Slides
description: PDF 가져오기 옵션을 나타냅니다
type: docs
url: /ko/com.aspose.slides/pdfimportoptions/
---
**상속:**
java.lang.Object
```
public class PdfImportOptions
```

PDF 가져오기 옵션을 나타냅니다
## 생성자

| 생성자 | 설명 |
| --- | --- |
| [PdfImportOptions()](#PdfImportOptions--) |  |
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [getDetectTables()](#getDetectTables--) | PDF 파일을 가져올 때 테이블을 감지할지 여부를 결정합니다. |
| [setDetectTables(boolean value)](#setDetectTables-boolean-) | PDF 파일을 가져올 때 테이블을 감지할지 여부를 결정합니다. |
### PdfImportOptions() {#PdfImportOptions--}
```
public PdfImportOptions()
```


### getDetectTables() {#getDetectTables--}
```
public final boolean getDetectTables()
```


PDF 파일을 가져올 때 테이블을 감지할지 여부를 결정합니다.

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
>          // 테이블 감지를 설정
>          pres.getSlides().addFromPdf(stream, pdfImportOptions);
>      }
> 
>      pres.save("fromPdfDocument.pptx", SaveFormat.Pptx);
>  } catch (IOException e) {
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**반환값:**
boolean
### setDetectTables(boolean value) {#setDetectTables-boolean-}
```
public final void setDetectTables(boolean value)
```


PDF 파일을 가져올 때 테이블을 감지할지 여부를 결정합니다.

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
>          // 테이블 감지를 설정
>          pres.getSlides().addFromPdf(stream, pdfImportOptions);
>      }
> 
>      pres.save("fromPdfDocument.pptx", SaveFormat.Pptx);
>  } catch (IOException e) {
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | boolean |  |