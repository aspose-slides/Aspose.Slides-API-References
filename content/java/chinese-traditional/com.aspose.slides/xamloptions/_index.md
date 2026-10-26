---
title: XamlOptions
second_title: Aspose.Slides for Java API 參考
description: 控制 XAML 文件保存方式的選項。
type: docs
url: /zh-hant/com.aspose.slides/xamloptions/
---
**Inheritance:**
java.lang.Object, [com.aspose.slides.SaveOptions](../../com.aspose.slides/saveoptions)

**All Implemented Interfaces:**
[com.aspose.slides.IXamlOptions](../../com.aspose.slides/ixamloptions)
```
public class XamlOptions extends SaveOptions implements IXamlOptions
```

控制 XAML 文件保存方式的選項。

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
## 建構函式

| 建構函式 | 描述 |
| --- | --- |
| [XamlOptions()](#XamlOptions--) | 建立 XamlOptions 實例。 |
## 方法

| 方法 | 描述 |
| --- | --- |
| [getExportHiddenSlides()](#getExportHiddenSlides--) | 判斷是否匯出隱藏的投影片。 |
| [setExportHiddenSlides(boolean value)](#setExportHiddenSlides-boolean-) | 判斷是否匯出隱藏的投影片。 |
| [getOutputSaver()](#getOutputSaver--) | 表示 IOutputSaver 介面的實作。 |
| [setOutputSaver(IXamlOutputSaver value)](#setOutputSaver-com.aspose.slides.IXamlOutputSaver-) | 表示 IOutputSaver 介面的實作。 |
### XamlOptions() {#XamlOptions--}
```
public XamlOptions()
```


建立 XamlOptions 實例。

### getExportHiddenSlides() {#getExportHiddenSlides--}
```
public final boolean getExportHiddenSlides()
```


判斷是否匯出隱藏的投影片。

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

**返回值:**
boolean
### setExportHiddenSlides(boolean value) {#setExportHiddenSlides-boolean-}
```
public final void setExportHiddenSlides(boolean value)
```


判斷是否匯出隱藏的投影片。

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

**參數:**
| 參數 | 類型 | 描述 |
| --- | --- | --- |
| value | boolean |  |

### getOutputSaver() {#getOutputSaver--}
```
public final IXamlOutputSaver getOutputSaver()
```


表示 IOutputSaver 介面的實作。

**返回值:**
[IXamlOutputSaver](../../com.aspose.slides/ixamloutputsaver)
### setOutputSaver(IXamlOutputSaver value) {#setOutputSaver-com.aspose.slides.IXamlOutputSaver-}
```
public final void setOutputSaver(IXamlOutputSaver value)
```


表示 IOutputSaver 介面的實作。

**參數:**
| 參數 | 類型 | 描述 |
| --- | --- | --- |
| value | [IXamlOutputSaver](../../com.aspose.slides/ixamloutputsaver) |  |