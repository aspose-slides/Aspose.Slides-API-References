---
title: IInkOptions
second_title: Aspose.Slides for Android via Java API Reference
description: Provides options that control the look of Ink objects in exported document.
type: docs
url: /zh/com.aspose.slides/iinkoptions/
---```
public interface IInkOptions
```

提供用于控制导出文档中 Ink 对象外观的选项。

## 方法

| 方法 | 描述 |
| --- | --- |
| [getHideInk()](#getHideInk--) | 在导出文档中显示或隐藏 Ink 元素。 |
| [setHideInk(boolean value)](#setHideInk-boolean-) | 在导出文档中显示或隐藏 Ink 元素。 |
| [getInterpretMaskOpAsOpacity()](#getInterpretMaskOpAsOpacity--) | 使用 ROP 操作或不透明度渲染画笔。 |
| [setInterpretMaskOpAsOpacity(boolean value)](#setInterpretMaskOpAsOpacity-boolean-) | 使用 ROP 操作或不透明度渲染画笔。 |

### getHideInk() {#getHideInk--}
```
public abstract boolean getHideInk()
```

在导出文档中显示或隐藏 Ink 元素。

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

Default value is false.

**Returns:**
boolean
### setHideInk(boolean value) {#setHideInk-boolean-}
```
public abstract void setHideInk(boolean value)
```


Shows or hides Ink elements in exported document.

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

Default value is false.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getInterpretMaskOpAsOpacity() {#getInterpretMaskOpAsOpacity--}
```
public abstract boolean getInterpretMaskOpAsOpacity()
```


Uses ROP operation or Opacity for rendering brush.

--------------------

> ```
> Next example demonstrates how to set using ROP for exporting Ink elements:
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

Default value is true.

**Returns:**
boolean
### setInterpretMaskOpAsOpacity(boolean value) {#setInterpretMaskOpAsOpacity-boolean-}
```
public abstract void setInterpretMaskOpAsOpacity(boolean value)

Uses ROP operation or Opacity for rendering brush.

--------------------

> ```
> Next example demonstrates how to set using ROP for exporting Ink elements:
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


默认值为 true。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | boolean |  |