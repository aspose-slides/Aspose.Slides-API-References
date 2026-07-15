---
title: IXamlOptions
second_title: Aspose.Slides for Android via Java API 參考文件
description: 控制 XAML 文件儲存方式的選項。
type: docs
url: /zh-hant/com.aspose.slides/ixamloptions/
---
**所有已實作的介面：**
[com.aspose.slides.ISaveOptions](../../com.aspose.slides/isaveoptions)
```
public interface IXamlOptions extends ISaveOptions
```

控制 XAML 文件儲存方式的選項。

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
## 方法

| 方法 | 說明 |
| --- | --- |
| [getExportHiddenSlides()](#getExportHiddenSlides--) | 判斷是否會匯出隱藏投影片。 |
| [setExportHiddenSlides(boolean value)](#setExportHiddenSlides-boolean-) | 判斷是否會匯出隱藏投影片。 |
| [getOutputSaver()](#getOutputSaver--) | 表示 IOutputSaver 介面的實作。 |
| [setOutputSaver(IXamlOutputSaver value)](#setOutputSaver-com.aspose.slides.IXamlOutputSaver-) | 表示 IOutputSaver 介面的實作。 |
### getExportHiddenSlides() {#getExportHiddenSlides--}
```
public abstract boolean getExportHiddenSlides()
```


判斷是否會匯出隱藏投影片。

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

**傳回：**
boolean
### setExportHiddenSlides(boolean value) {#setExportHiddenSlides-boolean-}
```
public abstract void setExportHiddenSlides(boolean value)
```


判斷是否會匯出隱藏投影片。

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

**參數：**
| 參數 | 型別 | 說明 |
| --- | --- | --- |
| value | boolean |  |

### getOutputSaver() {#getOutputSaver--}
```
public abstract IXamlOutputSaver getOutputSaver()
```


表示 IOutputSaver 介面的實作。

**傳回：**
[IXamlOutputSaver](../../com.aspose.slides/ixamloutputsaver)
### setOutputSaver(IXamlOutputSaver value) {#setOutputSaver-com.aspose.slides.IXamlOutputSaver-}
```
public abstract void setOutputSaver(IXamlOutputSaver value)
```


表示 IOutputSaver 介面的實作。

**參數：**
| 參數 | 型別 | 說明 |
| --- | --- | --- |
| value | [IXamlOutputSaver](../../com.aspose.slides/ixamloutputsaver) |  |