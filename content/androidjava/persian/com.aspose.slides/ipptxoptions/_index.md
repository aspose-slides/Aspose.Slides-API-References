---
title: IPptxOptions
second_title: مرجع API جاوا برای Aspose.Slides برای اندروید
description: گزینه‌هایی را برای ذخیره‌سازی ارائه‌های OpenXml (PPTX, PPSX, POTX, PPTM, PPSM, POTM) نشان می‌دهد.
type: docs
url: /fa/com.aspose.slides/ipptxoptions/
---
**تمام واسط‌های پیاده‌سازی‌شده:**  
[com.aspose.slides.ISaveOptions](../../com.aspose.slides/isaveoptions)
```
public interface IPptxOptions extends ISaveOptions
```

نمایش گزینه‌ها برای ذخیره‌سازی ارائه‌های OpenXml (PPTX, PPSX, POTX, PPTM, PPSM, POTM).
## متدها

| متد | توضیح |
| --- | --- |
| [getConformance()](#getConformance--) | مشخص می‌کند که کلاس سازگاری که سند Presentation به آن متعهد است چیست. |
| [setConformance(int value)](#setConformance-int-) | مشخص می‌کند که کلاس سازگاری که سند Presentation به آن متعهد است چیست. |
| [getZip64Mode()](#getZip64Mode--) | مشخص می‌کند که آیا فرمت ZIP64 برای سند Presentation استفاده می‌شود یا خیر. |
| [setZip64Mode(int value)](#setZip64Mode-int-) | مشخص می‌کند که آیا فرمت ZIP64 برای سند Presentation استفاده می‌شود یا خیر. |
| [getRefreshThumbnail()](#getRefreshThumbnail--) | مشخص می‌کند که آیا تصویر کوچک ارائه تازه‌سازی شود یا خیر. |
| [setRefreshThumbnail(boolean value)](#setRefreshThumbnail-boolean-) | مشخص می‌کند که آیا تصویر کوچک ارائه تازه‌سازی شود یا خیر. |
| [getCompressionLevel()](#getCompressionLevel--) | سطح فشرده‌سازی استفاده‌شده هنگام ذخیره سند ارائه را مشخص می‌کند. |
| [setCompressionLevel(int value)](#setCompressionLevel-int-) | سطح فشرده‌سازی استفاده‌شده هنگام ذخیره سند ارائه را مشخص می‌کند. |

### getConformance() {#getConformance--}
```
public abstract int getConformance()
```

مشخص می‌کند که کلاس سازگاری که سند Presentation به آن متعهد است چیست. مقدار پیش‌فرض [Conformance.Ecma376\_2006](../../com.aspose.slides/conformance\#Ecma376-2006)

**برگشت:**  
int

### setConformance(int value) {#setConformance-int-}
```
public abstract void setConformance(int value)
```

مشخص می‌کند که کلاس سازگاری که سند Presentation به آن متعهد است چیست. مقدار پیش‌فرض [Conformance.Ecma376\_2006](../../com.aspose.slides/conformance\#Ecma376-2006)

**پارامترها:**  
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | int |  |

### getZip64Mode() {#getZip64Mode--}
```
public abstract int getZip64Mode()
```

مشخص می‌کند که آیا فرمت ZIP64 برای سند Presentation استفاده می‌شود یا خیر. مقدار پیش‌فرض [Zip64Mode.IfNecessary](../../com.aspose.slides/zip64mode\#IfNecessary)

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
public abstract void setZip64Mode(int value)
```

مشخص می‌کند که آیا فرمت ZIP64 برای سند Presentation استفاده می‌شود یا خیر. مقدار پیش‌فرض [Zip64Mode.IfNecessary](../../com.aspose.slides/zip64mode\#IfNecessary)

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
public abstract boolean getRefreshThumbnail()
```

مشخص می‌کند که آیا تصویر کوچک ارائه تازه‌سازی شود یا خیر. بولین خواندنی/قابل نوشتن. مقدار پیش‌فرض **true**.

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

وقتی مقدار گزینه **true** باشد، تصویر کوچک جدید تولید می‌شود.  
وقتی مقدار گزینه **false** باشد، تصویر کوچک فعلی همان‌گونه ذخیره می‌شود.

**برگشت:**  
boolean

### setRefreshThumbnail(boolean value) {#setRefreshThumbnail-boolean-}
```
public abstract void setRefreshThumbnail(boolean value)
```

مشخص می‌کند که آیا تصویر کوچک ارائه تازه‌سازی شود یا خیر. بولین خواندنی/قابل نوشتن. مقدار پیش‌فرض **true**.

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

وقتی مقدار گزینه **true** باشد، تصویر کوچک جدید تولید می‌شود.  
وقتی مقدار گزینه **false** باشد، تصویر کوچک فعلی همان‌گونه ذخیره می‌شود.

**پارامترها:**  
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | boolean |  |

### getCompressionLevel() {#getCompressionLevel--}
```
public abstract int getCompressionLevel()
```

سطح فشرده‌سازی استفاده‌شده هنگام ذخیره سند ارائه را مشخص می‌کند. مقدار پیش‌فرض [CompressionLevel.Level6](../../com.aspose.slides/compressionlevel\#Level6).

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

سطوح فشرده‌سازی بالاتر فایل‌های کوچکتری تولید می‌کنند اما زمان پردازش بیشتری نیاز دارند. نسبت فشرده‌سازی واقعی به محتوای ارائه وابسته است.

**برگشت:**  
int

### setCompressionLevel(int value) {#setCompressionLevel-int-}
```
public abstract void setCompressionLevel(int value)
```

سطح فشرده‌سازی استفاده‌شده هنگام ذخیره سند ارائه را مشخص می‌کند. مقدار پیش‌فرض [CompressionLevel.Level6](../../com.aspose.slides/compressionlevel\#Level6).

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

سطوح فشرده‌سازی بالاتر فایل‌های کوچکتری تولید می‌کنند اما زمان پردازش بیشتری نیاز دارند. نسبت فشرده‌سازی واقعی به محتوای ارائه وابسته است.

**پارامترها:**  
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | int |  |