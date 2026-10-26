---
title: XamlOptions
second_title: Aspose.Slides Java API 参考
description: 控制 XAML 文档保存方式的选项。
type: docs
url: /zh/com.aspose.slides/xamloptions/
---
**继承:**
java.lang.Object, [com.aspose.slides.SaveOptions](../../com.aspose.slides/saveoptions)

**所有已实现接口:**
[com.aspose.slides.IXamlOptions](../../com.aspose.slides/ixamloptions)
```
public class XamlOptions extends SaveOptions implements IXamlOptions
```

控制 XAML 文档保存方式的选项。

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
## Constructors

| 构造函数 | 描述 |
| --- | --- |
| [XamlOptions()](#XamlOptions--) | 创建 XamlOptions 实例。 |
## Methods

| 方法 | 描述 |
| --- | --- |
| [getExportHiddenSlides()](#getExportHiddenSlides--) | 确定是否导出隐藏幻灯片。 |
| [setExportHiddenSlides(boolean value)](#setExportHiddenSlides-boolean-) | 确定是否导出隐藏幻灯片。 |
| [getOutputSaver()](#getOutputSaver--) | 表示 IOutputSaver 接口的实现。 |
| [setOutputSaver(IXamlOutputSaver value)](#setOutputSaver-com.aspose.slides.IXamlOutputSaver-) | 表示 IOutputSaver 接口的实现。 |
### XamlOptions() {#XamlOptions--}
```
public XamlOptions()
```

创建 XamlOptions 实例。

### getExportHiddenSlides() {#getExportHiddenSlides--}
```
public final boolean getExportHiddenSlides()
```

确定是否导出隐藏幻灯片。

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

确定是否导出隐藏幻灯片。

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

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | boolean |  |

### getOutputSaver() {#getOutputSaver--}
```
public final IXamlOutputSaver getOutputSaver()
```

表示 IOutputSaver 接口的实现。

**返回值:**
[IXamlOutputSaver](../../com.aspose.slides/ixamloutputsaver)
### setOutputSaver(IXamlOutputSaver value) {#setOutputSaver-com.aspose.slides.IXamlOutputSaver-}
```
public final void setOutputSaver(IXamlOutputSaver value)
```

表示 IOutputSaver 接口的实现。

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [IXamlOutputSaver](../../com.aspose.slides/ixamloutputsaver) |  |