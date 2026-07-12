---
title: IInkOptions
second_title: Aspose.Slides for Android via Java API Reference
description: エクスポートされたドキュメントで Ink オブジェクトの外観を制御するオプションを提供します。
type: docs
url: /ja/com.aspose.slides/iinkoptions/
---```
public interface IInkOptions
```

エクスポートされたドキュメントで Ink オブジェクトの外観を制御するオプションを提供します。
## メソッド

| メソッド | 説明 |
| --- | --- |
| [getHideInk()](#getHideInk--) | エクスポートされたドキュメントで Ink 要素を表示または非表示にします。 |
| [setHideInk(boolean value)](#setHideInk-boolean-) | エクスポートされたドキュメントで Ink 要素を表示または非表示にします。 |
| [getInterpretMaskOpAsOpacity()](#getInterpretMaskOpAsOpacity--) | ブラシの描画に ROP 操作または不透明度を使用します。 |
| [setInterpretMaskOpAsOpacity(boolean value)](#setInterpretMaskOpAsOpacity-boolean-) | ブラシの描画に ROP 操作または不透明度を使用します。 |
### getHideInk() {#getHideInk--}
```
public abstract boolean getHideInk()
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
public abstract void setHideInk(boolean value)
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

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | boolean |  |
### getInterpretMaskOpAsOpacity() {#getInterpretMaskOpAsOpacity--}
```
public abstract boolean getInterpretMaskOpAsOpacity()
```

ブラシの描画に ROP 操作または不透明度を使用します。

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

ブラシの描画に ROP 操作または不透明度を使用します。

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
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | boolean |  |