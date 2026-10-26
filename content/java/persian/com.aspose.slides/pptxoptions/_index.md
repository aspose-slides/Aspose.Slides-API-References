---
title: PptxOptions
second_title: مرجع API Aspose.Slides برای Java
description: نمایش گزینه‌ها برای ذخیرهٔ ارائه‌های OpenXml شامل PPTX، PPSX، POTX، PPTM، PPSM و POTM.
type: docs
url: /fa/com.aspose.slides/pptxoptions/
---
**ارث‌بری:**
java.lang.Object, [com.aspose.slides.SaveOptions](../../com.aspose.slides/saveoptions)

**تمام رابط‌های پیاده‌سازی‌شده:**
[com.aspose.slides.IPptxOptions](../../com.aspose.slides/ipptxoptions), java.lang.Cloneable
```
public final class PptxOptions extends SaveOptions implements IPptxOptions, Cloneable
```

نمایش گزینه‌ها برای ذخیرهٔ ارائه‌های OpenXml (PPTX, PPSX, POTX, PPTM, PPSM, POTM).

## سازنده‌ها

| سازنده | توضیح |
| --- | --- |
| [PptxOptions()](#PptxOptions--) | یک نمونه جدید از PptxOptions ایجاد می‌کند |

## متدها

| متد | توضیح |
| --- | --- |
| [getConformance()](#getConformance--) | کلاس همخوانی که سند Presentation به آن مطابقت دارد را مشخص می‌کند. |
| [setConformance(int value)](#setConformance-int-) | کلاس همخوانی که سند Presentation به آن مطابقت دارد را مشخص می‌کند. |
| [getZip64Mode()](#getZip64Mode--) | اینکه آیا فرمت ZIP64 برای سند Presentation استفاده می‌شود را مشخص می‌کند. |
| [setZip64Mode(int value)](#setZip64Mode-int-) | اینکه آیا فرمت ZIP64 برای سند Presentation استفاده می‌شود را مشخص می‌کند. |
| [getRefreshThumbnail()](#getRefreshThumbnail--) | اینکه آیا تصویر کوچک ارائه تازه‌سازی می‌شود را مشخص می‌کند. |
| [setRefreshThumbnail(boolean value)](#setRefreshThumbnail-boolean-) | اینکه آیا تصویر کوچک ارائه تازه‌سازی می‌شود را مشخص می‌کند. |
| [getCompressionLevel()](#getCompressionLevel--) | سطح فشرده‌سازی مورد استفاده هنگام ذخیرهٔ سند ارائه را مشخص می‌کند. |
| [setCompressionLevel(int value)](#setCompressionLevel-int-) | سطح فشرده‌سازی مورد استفاده هنگام ذخیرهٔ سند ارائه را مشخص می‌کند. |

### PptxOptions() {#PptxOptions--}
```
public PptxOptions()
```

یک نمونه جدید از PptxOptions ایجاد می‌کند

### getConformance() {#getConformance--}
```
public final int getConformance()
```

کلاس همخوانی که سند Presentation به آن مطابقت دارد را مشخص می‌کند. مقدار پیش‌فرض [Conformance.Ecma376\_2006](../../com.aspose.slides/conformance\#Ecma376-2006) است.

**بازگشت:**
int

### setConformance(int value) {#setConformance-int-}
```
public final void setConformance(int value)
```

کلاس همخوانی که سند Presentation به آن مطابقت دارد را مشخص می‌کند. مقدار پیش‌فرض [Conformance.Ecma376\_2006](../../com.aspose.slides/conformance\#Ecma376-2006) است.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | int |  |

### getZip64Mode() {#getZip64Mode--}
```
public final int getZip64Mode()
```

اینکه آیا فرمت ZIP64 برای سند Presentation استفاده می‌شود را مشخص می‌کند. مقدار پیش‌فرض [Zip64Mode.IfNecessary](../../com.aspose.slides/zip64mode\#IfNecessary) است.

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

**بازگشت:**
int

### setZip64Mode(int value) {#setZip64Mode-int-}
```
public final void setZip64Mode(int value)
```

اینکه آیا فرمت ZIP64 برای سند Presentation استفاده می‌شود را مشخص می‌کند. مقدار پیش‌فرض [Zip64Mode.IfNecessary](../../com.aspose.slides/zip64mode\#IfNecessary) است.

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

اینکه آیا تصویر کوچک ارائه تازه‌سازی می‌شود را مشخص می‌کند. متغیر بولی قابل خواندن/نوشتن. مقدار پیش‌فرض **true** است.

--------------------

> ```
> مثال:
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

زمانی که مقدار گزینه **true** باشد، تصویر کوچک جدید تولید می‌شود.

زمانی که مقدار گزینه **false** باشد، تصویر کوچک فعلی همان‌گونه ذخیره می‌شود.

**بازگشت:**
boolean

### setRefreshThumbnail(boolean value) {#setRefreshThumbnail-boolean-}
```
public final void setRefreshThumbnail(boolean value)
```

اینکه آیا تصویر کوچک ارائه تازه‌سازی می‌شود را مشخص می‌کند. متغیر بولی قابل خواندن/نوشتن. مقدار پیش‌فرض **true** است.

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

زمانی که مقدار گزینه **true** باشد، تصویر کوچک جدید تولید می‌شود.

زمانی که مقدار گزینه **false** باشد، تصویر کوچک فعلی همان‌گونه ذخیره می‌شود.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | boolean |  |

### getCompressionLevel() {#getCompressionLevel--}
```
public final int getCompressionLevel()
```

سطح فشرده‌سازی مورد استفاده هنگام ذخیرهٔ سند ارائه را مشخص می‌کند. مقدار پیش‌فرض [CompressionLevel.Level6](../../com.aspose.slides/compressionlevel\#Level6) است.

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

**بازگشت:**
int

### setCompressionLevel(int value) {#setCompressionLevel-int-}
```
public final void setCompressionLevel(int value)
```

سطح فشرده‌سازی مورد استفاده هنگام ذخیرهٔ سند ارائه را مشخص می‌کند. مقدار پیش‌فرض [CompressionLevel.Level6](../../com.aspose.slides/compressionlevel\#Level6) است.

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