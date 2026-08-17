---
title: IXamlOptions
second_title: Aspose.Slides の Java API リファレンス
description: XAML ドキュメントの保存方法を制御するオプションです。
type: docs
url: /ja/com.aspose.slides/ixamloptions/
---
**実装されたすべてのインターフェイス:**
[com.aspose.slides.ISaveOptions](../../com.aspose.slides/isaveoptions)
```
public interface IXamlOptions extends ISaveOptions
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
## メソッド

| メソッド | 説明 |
| --- | --- |
| [getExportHiddenSlides()](#getExportHiddenSlides--) | 非表示スライドがエクスポートされるかどうかを決定します。 |
| [setExportHiddenSlides(boolean value)](#setExportHiddenSlides-boolean-) | 非表示スライドがエクスポートされるかどうかを決定します。 |
| [getOutputSaver()](#getOutputSaver--) | IOutputSaver インターフェイスの実装を表します。 |
| [setOutputSaver(IXamlOutputSaver value)](#setOutputSaver-com.aspose.slides.IXamlOutputSaver-) | IOutputSaver インターフェイスの実装を表します。 |
### getExportHiddenSlides() {#getExportHiddenSlides--}
```
public abstract boolean getExportHiddenSlides()
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
public abstract void setExportHiddenSlides(boolean value)
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
| パラメーター | タイプ | 説明 |
| --- | --- | --- |
| value | boolean |  |

### getOutputSaver() {#getOutputSaver--}
```
public abstract IXamlOutputSaver getOutputSaver()
```


IOutputSaver インターフェイスの実装を表します。

**戻り値:**
[IXamlOutputSaver](../../com.aspose.slides/ixamloutputsaver)
### setOutputSaver(IXamlOutputSaver value) {#setOutputSaver-com.aspose.slides.IXamlOutputSaver-}
```
public abstract void setOutputSaver(IXamlOutputSaver value)
```


IOutputSaver インターフェイスの実装を表します。

**パラメーター:**
| パラメーター | タイプ | 説明 |
| --- | --- | --- |
| value | [IXamlOutputSaver](../../com.aspose.slides/ixamloutputsaver) |  |