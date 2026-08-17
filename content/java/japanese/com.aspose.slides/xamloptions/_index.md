---
title: XamlOptions
second_title: Aspose.Slides for Java API リファレンス
description: XAML ドキュメントの保存方法を制御するオプション。
type: docs
url: /ja/com.aspose.slides/xamloptions/
---
**継承:**
java.lang.Object, [com.aspose.slides.SaveOptions](../../com.aspose.slides/saveoptions)

**実装されているすべてのインターフェイス:**
[com.aspose.slides.IXamlOptions](../../com.aspose.slides/ixamloptions)
```
public class XamlOptions extends SaveOptions implements IXamlOptions
```

XAML ドキュメントの保存方法を制御するオプション。

--------------------

> ```
> Presentation pres = new Presentation("pres.pptx");
>  try {
>      XamlOptions xamlOptions = new XamlOptions();
>      xamlOptions.setExportHiddenSlides(true);
> 
>      pres.save(xamlOptions);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```
## コンストラクター

| コンストラクター | 説明 |
| --- | --- |
| [XamlOptions()](#XamlOptions--) | XamlOptions インスタンスを作成します。 |
## メソッド

| メソッド | 説明 |
| --- | --- |
| [getExportHiddenSlides()](#getExportHiddenSlides--) | 非表示スライドがエクスポートされるかどうかを決定します。 |
| [setExportHiddenSlides(boolean value)](#setExportHiddenSlides-boolean-) | 非表示スライドがエクスポートされるかどうかを決定します。 |
| [getOutputSaver()](#getOutputSaver--) | IOutputSaver インターフェイスの実装を表します。 |
| [setOutputSaver(IXamlOutputSaver value)](#setOutputSaver-com.aspose.slides.IXamlOutputSaver-) | IOutputSaver インターフェイスの実装を表します。 |
### XamlOptions() {#XamlOptions--}
```
public XamlOptions()
```

XamlOptions インスタンスを作成します。

### getExportHiddenSlides() {#getExportHiddenSlides--}
```
public final boolean getExportHiddenSlides()
```

非表示スライドがエクスポートされるかどうかを決定します。

--------------------

> ```
> Presentation pres = new Presentation("pres.pptx");
>  try {
>      XamlOptions xamlOptions = new XamlOptions();
>      xamlOptions.setExportHiddenSlides(true);
> 
>      pres.save(xamlOptions);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**戻り値:**
boolean
### setExportHiddenSlides(boolean value) {#setExportHiddenSlides-boolean-}
```
public final void setExportHiddenSlides(boolean value)
```

非表示スライドがエクスポートされるかどうかを決定します。

--------------------

> ```
> Presentation pres = new Presentation("pres.pptx");
>  try {
>      XamlOptions xamlOptions = new XamlOptions();
>      xamlOptions.setExportHiddenSlides(true);
> 
>      pres.save(xamlOptions);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | boolean |  |

### getOutputSaver() {#getOutputSaver--}
```
public final IXamlOutputSaver getOutputSaver()
```

IOutputSaver インターフェイスの実装を表します。

**戻り値:**
[IXamlOutputSaver](../../com.aspose.slides/ixamloutputsaver)
### setOutputSaver(IXamlOutputSaver value) {#setOutputSaver-com.aspose.slides.IXamlOutputSaver-}
```
public final void setOutputSaver(IXamlOutputSaver value)
```

IOutputSaver インターフェイスの実装を表します。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | [IXamlOutputSaver](../../com.aspose.slides/ixamloutputsaver) |  |