---
title: InkOptions
second_title: Aspose.Slides for Android 透過 Java API 參考
description: 提供控制匯出文件中 Ink 物件外觀的選項。
type: docs
url: /zh-hant/com.aspose.slides/inkoptions/
---
**繼承:**  
java.lang.Object

**所有實作的介面:**  
[com.aspose.slides.IInkOptions](../../com.aspose.slides/iinkoptions)  
```
public class InkOptions implements IInkOptions
```

提供控制匯出文件中 Ink 物件外觀的選項。  
## 方法

| 方法 | 說明 |
| --- | --- |
| [getHideInk()](#getHideInk--) | 顯示或隱藏匯出文件中的 Ink 元素。 |
| [setHideInk(boolean value)](#setHideInk-boolean-) | 顯示或隱藏匯出文件中的 Ink 元素。 |
| [getInterpretMaskOpAsOpacity()](#getInterpretMaskOpAsOpacity--) | 使用 ROP 操作或不透明度來渲染筆刷。 |
| [setInterpretMaskOpAsOpacity(boolean value)](#setInterpretMaskOpAsOpacity-boolean-) | 使用 ROP 操作或不透明度來渲染筆刷。 |
### getHideInk() {#getHideInk--}
```
public final boolean getHideInk()
```

顯示或隱藏匯出文件中的 Ink 元素。

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

**傳回值:**  
boolean
### setHideInk(boolean value) {#setHideInk-boolean-}
```
public final void setHideInk(boolean value)
```

顯示或隱藏匯出文件中的 Ink 元素。

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

**參數:**
| 參數 | 型別 | 說明 |
| --- | --- | --- |
| value | boolean |  |

### getInterpretMaskOpAsOpacity() {#getInterpretMaskOpAsOpacity--}
```
public final boolean getInterpretMaskOpAsOpacity()
```

使用 ROP 操作或不透明度來渲染筆刷。

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

**傳回值:**  
boolean
### setInterpretMaskOpAsOpacity(boolean value) {#setInterpretMaskOpAsOpacity-boolean-}
```
public final void setInterpretMaskOpAsOpacity(boolean value)
```

使用 ROP 操作或不透明度來渲染筆刷。

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

**參數:**
| 參數 | 型別 | 說明 |
| --- | --- | --- |
| value | boolean |  |