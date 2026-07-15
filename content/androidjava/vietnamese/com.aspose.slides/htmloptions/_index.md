---
title: HtmlOptions
second_title: Aspose.Slides cho Android qua Tham khảo API Java
description: Đại diện cho các tùy chọn xuất HTML.
type: docs
url: /vi/com.aspose.slides/htmloptions/
---
**Inheritance:**
java.lang.Object, [com.aspose.slides.SaveOptions](../../com.aspose.slides/saveoptions)

**All Implemented Interfaces:**
[com.aspose.slides.IHtmlOptions](../../com.aspose.slides/ihtmloptions)
```
public class HtmlOptions extends SaveOptions implements IHtmlOptions
```

Represents a HTML exporting options.
## Hàm tạo

| Constructor | Mô tả |
| --- | --- |
| [HtmlOptions(ILinkEmbedController linkEmbedController)](#HtmlOptions-com.aspose.slides.ILinkEmbedController-) | Creates a new HtmlOptions object specifiing callback. |
| [HtmlOptions()](#HtmlOptions--) | Creates a new HtmlOptions object for saving into single HTML file. |
## Phương thức

| Method | Mô tả |
| --- | --- |
| [getSlidesLayoutOptions()](#getSlidesLayoutOptions--) | Gets or sets the mode in which slides are placed on the page when exporting a presentation [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions). |
| [setSlidesLayoutOptions(ISlidesLayoutOptions value)](#setSlidesLayoutOptions-com.aspose.slides.ISlidesLayoutOptions-) | Gets or sets the mode in which slides are placed on the page when exporting a presentation [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions). |
| [getInkOptions()](#getInkOptions--) | Provides options that control the look of Ink objects in exported document. |
| [getShowHiddenSlides()](#getShowHiddenSlides--) | Specifies whether the generated document should include hidden slides or not. |
| [setShowHiddenSlides(boolean value)](#setShowHiddenSlides-boolean-) | Specifies whether the generated document should include hidden slides or not. |
| [getHtmlFormatter()](#getHtmlFormatter--) | Returns or sets HTML template. |
| [setHtmlFormatter(IHtmlFormatter value)](#setHtmlFormatter-com.aspose.slides.IHtmlFormatter-) | Returns or sets HTML template. |
| [getDisableFontLigatures()](#getDisableFontLigatures--) | Gets or sets a value indicating whether text is rendered without using ligatures. |
| [setDisableFontLigatures(boolean value)](#setDisableFontLigatures-boolean-) | Gets or sets a value indicating whether text is rendered without using ligatures. |
| [getSlideImageFormat()](#getSlideImageFormat--) | Returns or sets slide image format options. |
| [setSlideImageFormat(ISlideImageFormat value)](#setSlideImageFormat-com.aspose.slides.ISlideImageFormat-) | Returns or sets slide image format options. |
| [getJpegQuality()](#getJpegQuality--) | Returns or sets a value determining the quality of the JPEG images inside PDF document. |
| [setJpegQuality(byte value)](#setJpegQuality-byte-) | Returns or sets a value determining the quality of the JPEG images inside PDF document. |
| [getPicturesCompression()](#getPicturesCompression--) | Represents the pictures compression level |
| [setPicturesCompression(int value)](#setPicturesCompression-int-) | Represents the pictures compression level |
| [getDeletePicturesCroppedAreas()](#getDeletePicturesCroppedAreas--) | A boolean flag indicates if the cropped parts remain as part of the document. |
| [setDeletePicturesCroppedAreas(boolean value)](#setDeletePicturesCroppedAreas-boolean-) | A boolean flag indicates if the cropped parts remain as part of the document. |
| [getSvgResponsiveLayout()](#getSvgResponsiveLayout--) | True to exclude width and height attributes from svg container - that will make layout responsive. |
| [setSvgResponsiveLayout(boolean value)](#setSvgResponsiveLayout-boolean-) | True to exclude width and height attributes from svg container - that will make layout responsive. |
### HtmlOptions(ILinkEmbedController linkEmbedController) {#HtmlOptions-com.aspose.slides.ILinkEmbedController-}
```
public HtmlOptions(ILinkEmbedController linkEmbedController)
```

Tạo một đối tượng HtmlOptions mới, chỉ định callback.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| linkEmbedController | [ILinkEmbedController](../../com.aspose.slides/ilinkembedcontroller) | Callback object which controls saving project. |

### HtmlOptions() {#HtmlOptions--}
```
public HtmlOptions()
```

Tạo một đối tượng HtmlOptions mới để lưu vào một tệp HTML duy nhất.

### getSlidesLayoutOptions() {#getSlidesLayoutOptions--}
```
public final ISlidesLayoutOptions getSlidesLayoutOptions()
```

Gets or sets the mode in which slides are placed on the page when exporting a presentation [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions).

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      HtmlOptions options = new HtmlOptions();
>      HandoutLayoutingOptions slidesLayoutOptions = new HandoutLayoutingOptions();
>      slidesLayoutOptions.setHandout(HandoutType.Handouts4Horizontal);
>      options.setSlidesLayoutOptions(slidesLayoutOptions);
> 
>      pres.save("pres.html", SaveFormat.Html, options);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Trả về:**
[ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions)
### setSlidesLayoutOptions(ISlidesLayoutOptions value) {#setSlidesLayoutOptions-com.aspose.slides.ISlidesLayoutOptions-}
```
public final void setSlidesLayoutOptions(ISlidesLayoutOptions value)
```

Gets or sets the mode in which slides are placed on the page when exporting a presentation [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions).

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      HtmlOptions options = new HtmlOptions();
>      HandoutLayoutingOptions slidesLayoutOptions = new HandoutLayoutingOptions();
>      slidesLayoutOptions.setHandout(HandoutType.Handouts4Horizontal);
>      options.setSlidesLayoutOptions(slidesLayoutOptions);
> 
>      pres.save("pres.html", SaveFormat.Html, options);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions) |  |

### getInkOptions() {#getInkOptions--}
```
public final IInkOptions getInkOptions()
```

Provides options that control the look of Ink objects in exported document. **Chỉ đọc** [IInkOptions](../../com.aspose.slides/iinkoptions)

**Trả về:**
[IInkOptions](../../com.aspose.slides/iinkoptions)
### getShowHiddenSlides() {#getShowHiddenSlides--}
```
public final boolean getShowHiddenSlides()
```

Specifies whether the generated document should include hidden slides or not. Default is false.

**Trả về:**
boolean
### setShowHiddenSlides(boolean value) {#setShowHiddenSlides-boolean-}
```
public final void setShowHiddenSlides(boolean value)
```

Specifies whether the generated document should include hidden slides or not. Default is false.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | boolean |  |

### getHtmlFormatter() {#getHtmlFormatter--}
```
public final IHtmlFormatter getHtmlFormatter()
```

Returns or sets HTML template. **Đọc/ghi** [IHtmlFormatter](../../com.aspose.slides/ihtmlformatter).

**Trả về:**
[IHtmlFormatter](../../com.aspose.slides/ihtmlformatter)
### setHtmlFormatter(IHtmlFormatter value) {#setHtmlFormatter-com.aspose.slides.IHtmlFormatter-}
```
public final void setHtmlFormatter(IHtmlFormatter value)
```

Returns or sets HTML template. **Đọc/ghi** [IHtmlFormatter](../../com.aspose.slides/ihtmlformatter).

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | [IHtmlFormatter](../../com.aspose.slides/ihtmlformatter) |  |

### getDisableFontLigatures() {#getDisableFontLigatures--}
```
public final boolean getDisableFontLigatures()
```

Gets or sets a value indicating whether text is rendered without using ligatures. When set to true, ligatures will be disabled in the rendered output. By default, this property is set to false.

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      HtmlOptions options = new HtmlOptions();
>      options.setDisableFontLigatures(true);
>      pres.save("presentation.html", SaveFormat.Html, options);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Trả về:**
boolean
### setDisableFontLigatures(boolean value) {#setDisableFontLigatures-boolean-}
```
public final void setDisableFontLigatures(boolean value)
```

Gets or sets a value indicating whether text is rendered without using ligatures. When set to true, ligatures will be disabled in the rendered output. By default, this property is set to false.

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      HtmlOptions options = new HtmlOptions();
>      options.setDisableFontLigatures(true);
>      pres.save("presentation.html", SaveFormat.Html, options);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | boolean |  |

### getSlideImageFormat() {#getSlideImageFormat--}
```
public final ISlideImageFormat getSlideImageFormat()
```

Returns or sets slide image format options. **Đọc/ghi** [ISlideImageFormat](../../com.aspose.slides/islideimageformat).

**Trả về:**
[ISlideImageFormat](../../com.aspose.slides/islideimageformat)
### setSlideImageFormat(ISlideImageFormat value) {#setSlideImageFormat-com.aspose.slides.ISlideImageFormat-}
```
public final void setSlideImageFormat(ISlideImageFormat value)
```

Returns or sets slide image format options. **Đọc/ghi** [ISlideImageFormat](../../com.aspose.slides/islideimageformat).

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | [ISlideImageFormat](../../com.aspose.slides/islideimageformat) |  |

### getJpegQuality() {#getJpegQuality--}
```
public final byte getJpegQuality()
```

Returns or sets a value determining the quality of the JPEG images inside PDF document. **Đọc/ghi** byte.

--------------------

Has effect only when a document contains JPEG images.

Use this property to get or set the quality of the images inside a document when saving in PDF format. The value may vary from 0 to 100 where 0 means worst quality but maximum compression and 100 means best quality but minimum compression.

The default value is **95**.

**Trả về:**
byte
### setJpegQuality(byte value) {#setJpegQuality-byte-}
```
public final void setJpegQuality(byte value)
```

Returns or sets a value determining the quality of the JPEG images inside PDF document. **Đọc/ghi** byte.

--------------------

Has effect only when a document contains JPEG images.

Use this property to get or set the quality of the images inside a document when saving in PDF format. The value may vary from 0 to 100 where 0 means worst quality but maximum compression and 100 means best quality but minimum compression.

The default value is **95**.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | byte |  |

### getPicturesCompression() {#getPicturesCompression--}
```
public final int getPicturesCompression()
```

Represents the pictures compression level

**Trả về:**
int
### setPicturesCompression(int value) {#setPicturesCompression-int-}
```
public final void setPicturesCompression(int value)
```

Represents the pictures compression level

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | int |  |

### getDeletePicturesCroppedAreas() {#getDeletePicturesCroppedAreas--}
```
public final boolean getDeletePicturesCroppedAreas()
```

A boolean flag indicates if the cropped parts remain as part of the document. If true the cropped parts will removed, if false they will be serialized in the document (which can possible lead to a larger file)

**Trả về:**
boolean
### setDeletePicturesCroppedAreas(boolean value) {#setDeletePicturesCroppedAreas-boolean-}
```
public final void setDeletePicturesCroppedAreas(boolean value)
```

A boolean flag indicates if the cropped parts remain as part of the document. If true the cropped parts will removed, if false they will be serialized in the document (which can possible lead to a larger file)

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | boolean |  |

### getSvgResponsiveLayout() {#getSvgResponsiveLayout--}
```
public final boolean getSvgResponsiveLayout()
```

True to exclude width and height attributes from svg container - that will make layout responsive. False - otherwise. **Đọc/ghi** boolean.

**Trả về:**
boolean
### setSvgResponsiveLayout(boolean value) {#setSvgResponsiveLayout-boolean-}
```
public final void setSvgResponsiveLayout(boolean value)
```

True to exclude width and height attributes from svg container - that will make layout responsive. False - otherwise. **Đọc/ghi** boolean.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | boolean |  |