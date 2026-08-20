---
title: InkOptions
second_title: Aspose.Slides for Java API 參考
description: 提供控制匯出文件中 Ink 物件外觀的選項。
type: docs
url: /zh-hant/com.aspose.slides/inkoptions/
---
**繼承：**
java.lang.Object

**所有已實作的介面：**
[com.aspose.slides.IInkOptions](../../com.aspose.slides/iinkoptions)
```
public class InkOptions implements IInkOptions
```

提供控制匯出文件中 Ink 物件外觀的選項。

## 方法

| 方法 | 描述 |
| --- | --- |
| [getHideInk()](#getHideInk--) | 在匯出文件中顯示或隱藏 Ink 元素。 |
| [setHideInk(boolean value)](#setHideInk-boolean-) | 在匯出文件中顯示或隱藏 Ink 元素。 |
| [getInterpretMaskOpAsOpacity()](#getInterpretMaskOpAsOpacity--) | 使用 ROP 運算或不透明度來繪製筆刷。 |
| [setInterpretMaskOpAsOpacity(boolean value)](#setInterpretMaskOpAsOpacity-boolean-) | 使用 ROP 運算或不透明度來繪製筆刷。 |
### getHideInk() {#getHideInk--}
```
public final boolean getHideInk()
```


在匯出文件中顯示或隱藏 Ink 元素。

--------------------

> ```
> Next example demonstrates how to hide Ink elements in exported PDF document:
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      PdfOptions pdfOptions = new PdfOptions();
>      pdfOptions.getInkOptions().setHideInk(true);
>      pres.save("output.pptx", SaveFormat.Pdf, pdfOptions);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

--------------------

預設值為 false。

**回傳：**
boolean
### setHideInk(boolean value) {#setHideInk-boolean-}
```
public final void setHideInk(boolean value)
```


在匯出文件中顯示或隱藏 Ink 元素。

--------------------

> ```
> Next example demonstrates how to hide Ink elements in exported PDF document:
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      PdfOptions pdfOptions = new PdfOptions();
>      pdfOptions.getInkOptions().setHideInk(true);
>      pres.save("output.pptx", SaveFormat.Pdf, pdfOptions);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

--------------------

預設值為 false。

**參數：**
| 參數 | 類型 | 描述 |
| --- | --- | --- |
| value | boolean |  |

### getInterpretMaskOpAsOpacity() {#getInterpretMaskOpAsOpacity--}
```
public final boolean getInterpretMaskOpAsOpacity()
```


使用 ROP 運算或不透明度來繪製筆刷。

--------------------

> ```
> Next example demonstrates how to set using ROP for expotring Ink elements:
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      PdfOptions pdfOptions = new PdfOptions();
>      pdfOptions.getInkOptions().setInterpretMaskOpAsOpacity(false);
>      pres.save("output.pptx", SaveFormat.Pdf, pdfOptions);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

--------------------

預設值為 true。

**回傳：**
boolean
### setInterpretMaskOpAsOpacity(boolean value) {#setInterpretMaskOpAsOpacity-boolean-}
```
public final void setInterpretMaskOpAsOpacity(boolean value)
```


使用 ROP 運算或不透明度來繪製筆刷。

--------------------

> ```
> Next example demonstrates how to set using ROP for expotring Ink elements:
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      PdfOptions pdfOptions = new PdfOptions();
>      pdfOptions.getInkOptions().setInterpretMaskOpAsOpacity(false);
>      pres.save("output.pptx", SaveFormat.Pdf, pdfOptions);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

--------------------

預設值為 true。

**參數：**
| 參數 | 類型 | 描述 |
| --- | --- | --- |
| value | boolean |  |