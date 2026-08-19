---
title: IPptxOptions
second_title: مرجع API Aspose.Slides برای جاوا
description: گزینه‌هایی را برای ذخیره‌سازی ارائه‌های OpenXml شامل PPTX، PPSX، POTX، PPTM، PPSM و POTM ارائه می‌دهد.
type: docs
url: /fa/com.aspose.slides/ipptxoptions/
---
**تمام رابط‌های پیاده‌سازی‌شده:**
[com.aspose.slides.ISaveOptions](../../com.aspose.slides/isaveoptions)
```
public interface IPptxOptions extends ISaveOptions
```

گزینه‌هایی را برای ذخیره‌سازی ارائه‌های OpenXml (PPTX، PPSX، POTX، PPTM، PPSM، POTM) ارائه می‌دهد.
## متدها

| متد | توضیح |
| --- | --- |
| [getConformance()](#getConformance--) | کلاسی از سازگاری را که سند Presentation به آن پایبند است مشخص می‌کند. |
| [setConformance(int value)](#setConformance-int-) | کلاسی از سازگاری را که سند Presentation به آن پایبند است مشخص می‌کند. |
| [getZip64Mode()](#getZip64Mode--) | مشخص می‌کند که آیا قالب ZIP64 برای سند Presentation استفاده می‌شود یا خیر. |
| [setZip64Mode(int value)](#setZip64Mode-int-) | مشخص می‌کند که آیا قالب ZIP64 برای سند Presentation استفاده می‌شود یا خیر. |
| [getRefreshThumbnail()](#getRefreshThumbnail--) | مشخص می‌کند که آیا تصویر بندانگشتی ارائه تازه‌سازی خواهد شد یا خیر. |
| [setRefreshThumbnail(boolean value)](#setRefreshThumbnail-boolean-) | مشخص می‌کند که آیا تصویر بندانگشتی ارائه تازه‌سازی خواهد شد یا خیر. |
| [getCompressionLevel()](#getCompressionLevel--) | سطح فشرده‌سازی مورد استفاده هنگام ذخیره‌سازی سند ارائه را مشخص می‌کند. |
| [setCompressionLevel(int value)](#setCompressionLevel-int-) | سطح فشرده‌سازی مورد استفاده هنگام ذخیره‌سازی سند ارائه را مشخص می‌کند. |
### getConformance() {#getConformance--}
```
public abstract int getConformance()
```

کلاسی از سازگاری را که سند Presentation به آن پایبند است مشخص می‌کند. مقدار پیش‌فرض [Conformance.Ecma376\_2006](../../com.aspose.slides/conformance\#Ecma376-2006) است.

**باز می‌گردد:**
int
### setConformance(int value) {#setConformance-int-}
```
public abstract void setConformance(int value)
```

کلاسی از سازگاری را که سند Presentation به آن پایبند است مشخص می‌کند. مقدار پیش‌فرض [Conformance.Ecma376\_2006](../../com.aspose.slides/conformance\#Ecma376-2006) است.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | int |  |
### getZip64Mode() {#getZip64Mode--}
```
public abstract int getZip64Mode()
```

مشخص می‌کند که آیا قالب ZIP64 برای سند Presentation استفاده می‌شود یا خیر. مقدار پیش‌فرض [Zip64Mode.IfNecessary](../../com.aspose.slides/zip64mode\#IfNecessary) است.

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

**باز می‌گردد:**
int
### setZip64Mode(int value) {#setZip64Mode-int-}
```
public abstract void setZip64Mode(int value)
```

مشخص می‌کند که آیا قالب ZIP64 برای سند Presentation استفاده می‌شود یا خیر. مقدار پیش‌فرض [Zip64Mode.IfNecessary](../../com.aspose.slides/zip64mode\#IfNecessary) است.

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

مشخص می‌کند که آیا تصویر بندانگشتی ارائه تازه‌سازی خواهد شد یا خیر. بولی قابل خواندن/نوشتن. مقدار پیش‌فرض **true** است.

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

زمانی که مقدار گزینه **true** باشد، تصویر بندانگشتی جدید تولید می‌شود.

زمانی که مقدار گزینه **false** باشد، تصویر بندانگشتی فعلی همان‌گونه ذخیره می‌شود.

**باز می‌گردد:**
boolean
### setRefreshThumbnail(boolean value) {#setRefreshThumbnail-boolean-}
```
public abstract void setRefreshThumbnail(boolean value)
```

مشخص می‌کند که آیا تصویر بندانگشتی ارائه تازه‌سازی خواهد شد یا خیر. بولی قابل خواندن/نوشتن. مقدار پیش‌فرض **true** است.

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

زمانی که مقدار گزینه **true** باشد، تصویر بندانگشتی جدید تولید می‌شود.

زمانی که مقدار گزینه **false** باشد، تصویر بندانگشتی فعلی همان‌گونه ذخیره می‌شود.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | boolean |  |
### getCompressionLevel() {#getCompressionLevel--}
```
public abstract int getCompressionLevel()
```

سطح فشرده‌سازی مورد استفاده هنگام ذخیره‌سازی سند ارائه را مشخص می‌کند. مقدار پیش‌فرض [CompressionLevel.Level6](../../com.aspose.slides/compressionlevel\#Level6) است.

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

سطوح فشرده‌سازی بالاتر فایل‌های کوچکتری تولید می‌کنند اما زمان پردازش بیشتری می‌طلبند. نسبت فشرده‌سازی واقعی به محتوای ارائه بستگی دارد.

**باز می‌گردد:**
int
### setCompressionLevel(int value) {#setCompressionLevel-int-}
```
public abstract void setCompressionLevel(int value)
```

سطح فشرده‌سازی مورد استفاده هنگام ذخیره‌سازی سند ارائه را مشخص می‌کند. مقدار پیش‌فرض [CompressionLevel.Level6](../../com.aspose.slides/compressionlevel\#Level6) است.

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

سطوح فشرده‌سازی بالاتر فایل‌های کوچکتری تولید می‌کنند اما زمان پردازش بیشتری می‌طلبند. نسبت فشرده‌سازی واقعی به محتوای ارائه بستگی دارد.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | int |  |