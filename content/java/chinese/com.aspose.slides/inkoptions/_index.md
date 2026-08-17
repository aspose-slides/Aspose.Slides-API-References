---
title: InkOptions
second_title: Aspose.Slides for Java API 参考
description: 提供控制导出文档中 Ink 对象外观的选项。
type: docs
url: /zh/com.aspose.slides/inkoptions/
---
**继承：**
java.lang.Object

**所有实现的接口：**
[com.aspose.slides.IInkOptions](../../com.aspose.slides/iinkoptions)
```
public class InkOptions implements IInkOptions
```

提供控制导出文档中 Ink 对象外观的选项。
## 方法

| 方法 | 描述 |
| --- | --- |
| [getHideInk()](#getHideInk--) | 在导出文档中显示或隐藏 Ink 元素。 |
| [setHideInk(boolean value)](#setHideInk-boolean-) | 在导出文档中显示或隐藏 Ink 元素。 |
| [getInterpretMaskOpAsOpacity()](#getInterpretMaskOpAsOpacity--) | 使用 ROP 操作或不透明度来渲染笔刷。 |
| [setInterpretMaskOpAsOpacity(boolean value)](#setInterpretMaskOpAsOpacity-boolean-) | 使用 ROP 操作或不透明度来渲染笔刷。 |
### getHideInk() {#getHideInk--}
```
public final boolean getHideInk()
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

默认值为 false。

**返回：**
boolean
### setHideInk(boolean value) {#setHideInk-boolean-}
```
public final void setHideInk(boolean value)
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

默认值为 false。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | boolean |  |

### getInterpretMaskOpAsOpacity() {#getInterpretMaskOpAsOpacity--}
```
public final boolean getInterpretMaskOpAsOpacity()
```


使用 ROP 操作或不透明度来渲染笔刷。

--------------------

> ```
> 下一个示例演示如何使用 ROP 设置导出 Ink 元素:
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

默认值为 true。

**返回：**
boolean
### setInterpretMaskOpAsOpacity(boolean value) {#setInterpretMaskOpAsOpacity-boolean-}
```
public final void setInterpretMaskOpAsOpacity(boolean value)
```


使用 ROP 操作或不透明度来渲染笔刷。

--------------------

> ```
> 下一个示例演示如何使用 ROP 设置导出 Ink 元素:
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

默认值为 true。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | boolean |  |