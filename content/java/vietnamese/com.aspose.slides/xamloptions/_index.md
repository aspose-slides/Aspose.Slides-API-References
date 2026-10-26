---
title: XamlOptions
second_title: Tham chiếu API Aspose.Slides cho Java
description: Các tùy chọn điều khiển cách tài liệu XAML được lưu.
type: docs
url: /vi/com.aspose.slides/xamloptions/
---
**Kế thừa:**
java.lang.Object, [com.aspose.slides.SaveOptions](../../com.aspose.slides/saveoptions)

**Tất cả các giao diện đã triển khai:**
[com.aspose.slides.IXamlOptions](../../com.aspose.slides/ixamloptions)
```
public class XamlOptions extends SaveOptions implements IXamlOptions
```

Các tùy chọn điều khiển cách tài liệu XAML được lưu.

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
## Hàm tạo

| Hàm tạo | Mô tả |
| --- | --- |
| [XamlOptions()](#XamlOptions--) | Tạo instance XamlOptions. |
## Phương thức

| Phương thức | Mô tả |
| --- | --- |
| [getExportHiddenSlides()](#getExportHiddenSlides--) | Xác định xem các slide ẩn có được xuất hay không. |
| [setExportHiddenSlides(boolean value)](#setExportHiddenSlides-boolean-) | Xác định xem các slide ẩn có được xuất hay không. |
| [getOutputSaver()](#getOutputSaver--) | Biểu diễn một triển khai của giao diện IOutputSaver. |
| [setOutputSaver(IXamlOutputSaver value)](#setOutputSaver-com.aspose.slides.IXamlOutputSaver-) | Biểu diễn một triển khai của giao diện IOutputSaver. |
### XamlOptions() {#XamlOptions--}
```
public XamlOptions()
```


Tạo đối tượng XamlOptions.

### getExportHiddenSlides() {#getExportHiddenSlides--}
```
public final boolean getExportHiddenSlides()
```


Xác định xem các slide ẩn có được xuất hay không.

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

**Trả về:**
boolean
### setExportHiddenSlides(boolean value) {#setExportHiddenSlides-boolean-}
```
public final void setExportHiddenSlides(boolean value)
```


Xác định xem các slide ẩn có được xuất hay không.

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

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | boolean |  |

### getOutputSaver() {#getOutputSaver--}
```
public final IXamlOutputSaver getOutputSaver()
```


Biểu diễn một triển khai của giao diện IOutputSaver.

**Trả về:**
[IXamlOutputSaver](../../com.aspose.slides/ixamloutputsaver)
### setOutputSaver(IXamlOutputSaver value) {#setOutputSaver-com.aspose.slides.IXamlOutputSaver-}
```
public final void setOutputSaver(IXamlOutputSaver value)
```


Biểu diễn một triển khai của giao diện IOutputSaver.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | [IXamlOutputSaver](../../com.aspose.slides/ixamloutputsaver) |  |