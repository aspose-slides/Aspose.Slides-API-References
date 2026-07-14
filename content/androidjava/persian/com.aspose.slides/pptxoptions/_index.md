---
title: PptxOptions
second_title: Aspose.Slides برای Android از طریق مرجع API جاوا
description: نمایش‌دهنده گزینه‌های ذخیره‌سازی ارائه‌های OpenXml با فرمت‌های PPTX، PPSX، POTX، PPTM، PPSM و POTM.
type: docs
url: /fa/com.aspose.slides/pptxoptions/
---
**وراثت:**
java.lang.Object, [com.aspose.slides.SaveOptions](../../com.aspose.slides/saveoptions)

**تمام رابط‌های پیاده‌سازی شده:**
[com.aspose.slides.IPptxOptions](../../com.aspose.slides/ipptxoptions), java.lang.Cloneable
```
public final class PptxOptions extends SaveOptions implements IPptxOptions, Cloneable
```

نمایش‌دهنده گزینه‌های ذخیره‌سازی ارائه‌های OpenXml (PPTX، PPSX، POTX، PPTM، PPSM، POTM).
## سازنده‌ها

| سازنده | توضیح |
| --- | --- |
| [PptxOptions()](#PptxOptions--) | Creates new instance of PptxOptions |
## متدها

| متد | توضیح |
| --- | --- |
| [getConformance()](#getConformance--) | Specifies the conformance class to which the Presentation document conforms. |
| [setConformance(int value)](#setConformance-int-) | Specifies the conformance class to which the Presentation document conforms. |
| [getZip64Mode()](#getZip64Mode--) | Specifies whether the ZIP64 format is used for the Presentation document. |
| [setZip64Mode(int value)](#setZip64Mode-int-) | Specifies whether the ZIP64 format is used for the Presentation document. |
| [getRefreshThumbnail()](#getRefreshThumbnail--) | Specifies whether the presentation thumbnail will be refreshed. |
| [setRefreshThumbnail(boolean value)](#setRefreshThumbnail-boolean-) | Specifies whether the presentation thumbnail will be refreshed. |
| [getCompressionLevel()](#getCompressionLevel--) | Specifies the compression level used when saving the presentation document. |
| [setCompressionLevel(int value)](#setCompressionLevel-int-) | Specifies the compression level used when saving the presentation document. |
### PptxOptions() {#PptxOptions--}
```
public PptxOptions()
```


یک نمونه جدید از PptxOptions ایجاد می‌کند

### getConformance() {#getConformance--}
```
public final int getConformance()
```


Specifies the conformance class to which the Presentation document conforms. Default value is [Conformance.Ecma376\_2006](../../com.aspose.slides/conformance\#Ecma376-2006)

**برگشت:**
int
### setConformance(int value) {#setConformance-int-}
```
public final void setConformance(int value)
```


Specifies the conformance class to which the Presentation document conforms. Default value is [Conformance.Ecma376\_2006](../../com.aspose.slides/conformance\#Ecma376-2006)

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | int |  |

### getZip64Mode() {#getZip64Mode--}
```
public final int getZip64Mode()
```


Specifies whether the ZIP64 format is used for the Presentation document. The default value is [Zip64Mode.IfNecessary](../../com.aspose.slides/zip64mode\#IfNecessary)

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation("demo.pptx");
>  try {
>      PptxOptions pptxOptions = new PptxOptions();
>      pptxOptions.setZip64Mode(Zip64Mode.Always);
>      pres.save("demo-zip64.pptx", SaveFormat.Pptx, pptxOptions);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**برگشت:**
int
### setZip64Mode(int value) {#setZip64Mode-int-}
```
public final void setZip64Mode(int value)
```


Specifies whether the ZIP64 format is used for the Presentation document. The default value is [Zip64Mode.IfNecessary](../../com.aspose.slides/zip64mode\#IfNecessary)

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation("demo.pptx");
>  try {
>      PptxOptions pptxOptions = new PptxOptions();
>      pptxOptions.setZip64Mode(Zip64Mode.Always);
>      pres.save("demo-zip64.pptx", SaveFormat.Pptx, pptxOptions);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | int |  |

### getRefreshThumbnail() {#getRefreshThumbnail--}
```
public final boolean getRefreshThumbnail()
```


Specifies whether the presentation thumbnail will be refreshed. Read/write boolean. Default value is **true**.

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation("demo.pptx");
>  try {
>      PptxOptions pptxOptions = new PptxOptions();
>      pptxOptions.setRefreshThumbnail(false);
>      pres.save("result_with_old_thumbnail.pptx", SaveFormat.Pptx, pptxOptions);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


--------------------

هنگامی که مقدار گزینه **true** باشد، تصویر کوچک جدید تولید می‌شود.

هنگامی که مقدار گزینه **false** باشد، تصویر کوچک فعلی به همان شکل ذخیره می‌شود.

**برگشت:**
boolean
### setRefreshThumbnail(boolean value) {#setRefreshThumbnail-boolean-}
```
public final void setRefreshThumbnail(boolean value)
```


Specifies whether the presentation thumbnail will be refreshed. Read/write boolean. Default value is **true**.

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation("demo.pptx");
>  try {
>      PptxOptions pptxOptions = new PptxOptions();
>      pptxOptions.setRefreshThumbnail(false);
>      pres.save("result_with_old_thumbnail.pptx", SaveFormat.Pptx, pptxOptions);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


--------------------

هنگامی که مقدار گزینه **true** باشد، تصویر کوچک جدید تولید می‌شود.

هنگامی که مقدار گزینه **false** باشد، تصویر کوچک فعلی به همان شکل ذخیره می‌شود.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | boolean |  |

### getCompressionLevel() {#getCompressionLevel--}
```
public final int getCompressionLevel()
```


Specifies the compression level used when saving the presentation document. The default value is [CompressionLevel.Level6](../../com.aspose.slides/compressionlevel\#Level6).

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation("demo.pptx");
>  try {
>      PptxOptions pptxOptions = new PptxOptions();
>      pptxOptions.setCompressionLevel(CompressionLevel.Level8);
>      pres.save("demo-level8.pptx", SaveFormat.Pptx, pptxOptions);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

--------------------

سطوح بالاتر فشرده‌سازی فایل‌های کوچکتری تولید می‌کنند اما زمان پردازش بیشتری نیاز دارند. نسبت فشرده‌سازی واقعی به محتوای ارائه بستگی دارد.

**برگشت:**
int
### setCompressionLevel(int value) {#setCompressionLevel-int-}
```
public final void setCompressionLevel(int value)
```


Specifies the compression level used when saving the presentation document. The default value is [CompressionLevel.Level6](../../com.aspose.slides/compressionlevel\#Level6).

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation("demo.pptx");
>  try {
>      PptxOptions pptxOptions = new PptxOptions();
>      pptxOptions.setCompressionLevel(CompressionLevel.Level8);
>      pres.save("demo-level8.pptx", SaveFormat.Pptx, pptxOptions);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

--------------------

سطوح بالاتر فشرده‌سازی فایل‌های کوچکتری تولید می‌کنند اما زمان پردازش بیشتری نیاز دارند. نسبت فشرده‌سازی واقعی به محتوای ارائه بستگی دارد.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | int |  |