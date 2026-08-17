---
title: IInkOptions
second_title: Aspose.Slides for Java API Reference
description: エクスポートされたドキュメント内の Ink オブジェクトの外観を制御するオプションを提供します。
type: docs
url: /ja/com.aspose.slides/iinkoptions/
---```
public interface IInkOptions
```

エクスポートされたドキュメント内の Ink オブジェクトの外観を制御するオプションを提供します。
## メソッド

| Method | 説明 |
| --- | --- |
| [getHideInk()](#getHideInk--) | エクスポートされたドキュメント内の Ink 要素を表示または非表示にします。 |
| [setHideInk(boolean value)](#setHideInk-boolean-) | エクスポートされたドキュメント内の Ink 要素を表示または非表示にします。 |
| [getInterpretMaskOpAsOpacity()](#getInterpretMaskOpAsOpacity--) | ブラシのレンダリングに ROP 操作または Opacity を使用します。 |
| [setInterpretMaskOpAsOpacity(boolean value)](#setInterpretMaskOpAsOpacity-boolean-) | ブラシのレンダリングに ROP 操作または Opacity を使用します。 |
### getHideInk() {#getHideInk--}
```
public abstract boolean getHideInk()
```


エクスポートされたドキュメント内の Ink 要素を表示または非表示にします。

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

デフォルト値は false です。

**戻り値:**
boolean
### setHideInk(boolean value) {#setHideInk-boolean-}
```
public abstract void setHideInk(boolean value)
```


エクスポートされたドキュメント内の Ink 要素を表示または非表示にします。

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

デフォルト値は false です。

**パラメータ:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getInterpretMaskOpAsOpacity() {#getInterpretMaskOpAsOpacity--}
```
public abstract boolean getInterpretMaskOpAsOpacity()
```


ブラシのレンダリングに ROP 操作または Opacity を使用します。

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

デフォルト値は true です。

**戻り値:**
boolean
### setInterpretMaskOpAsOpacity(boolean value) {#setInterpretMaskOpAsOpacity-boolean-}
```
public abstract void setInterpretMaskOpAsOpacity(boolean value)
```


ブラシのレンダリングに ROP 操作または Opacity を使用します。

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

デフォルト値は true です。

**パラメータ:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |