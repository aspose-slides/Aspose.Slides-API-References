---
title: InkOptions
second_title: Android 向け Aspose.Slides（Java API リファレンス）
description: エクスポートされたドキュメント内の Ink オブジェクトの外観を制御するオプションを提供します。
type: docs
url: /ja/com.aspose.slides/inkoptions/
---
**継承:**
java.lang.Object

**実装されているすべてのインターフェイス:**
[com.aspose.slides.IInkOptions](../../com.aspose.slides/iinkoptions)
```
public class InkOptions implements IInkOptions
```

エクスポートされたドキュメントで Ink オブジェクトの外観を制御するオプションを提供します。
## メソッド

| メソッド | 説明 |
| --- | --- |
| [getHideInk()](#getHideInk--) | エクスポートされたドキュメントで Ink 要素を表示または非表示にします。 |
| [setHideInk(boolean value)](#setHideInk-boolean-) | エクスポートされたドキュメントで Ink 要素を表示または非表示にします。 |
| [getInterpretMaskOpAsOpacity()](#getInterpretMaskOpAsOpacity--) | ブラシの描画に ROP 操作または Opacity を使用します。 |
| [setInterpretMaskOpAsOpacity(boolean value)](#setInterpretMaskOpAsOpacity-boolean-) | ブラシの描画に ROP 操作または Opacity を使用します。 |
### getHideInk() {#getHideInk--}
```
public final boolean getHideInk()
```


エクスポートされたドキュメントで Ink 要素を表示または非表示にします。

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
public final void setHideInk(boolean value)
```


エクスポートされたドキュメントで Ink 要素を表示または非表示にします。

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

**パラメーター:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getInterpretMaskOpAsOpacity() {#getInterpretMaskOpAsOpacity--}
```
public final boolean getInterpretMaskOpAsOpacity()
```


ブラシの描画に ROP 操作または Opacity を使用します。

--------------------

> ```
> 次の例は、Ink 要素のエクスポートに ROP を使用する設定方法を示します:
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
public final void setInterpretMaskOpAsOpacity(boolean value)
```


ブラシの描画に ROP 操作または Opacity を使用します。

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

デフォルト値は true です。

**パラメーター:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |