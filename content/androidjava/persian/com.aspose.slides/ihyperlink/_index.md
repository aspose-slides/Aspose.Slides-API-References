---
title: IHyperlink
second_title: Aspose.Slides for Android via Java API Reference
description: Represents a hyperlink.
type: docs
url: /fa/com.aspose.slides/ihyperlink/
---```
public interface IHyperlink
```

یک پیوند را نشان می‌دهد.
## متدها

| متد | توضیح |
| --- | --- |
| [getActionType()](#getActionType--) | نوع عمل HyperLinkEx را برمی‌گرداند. |
| [getExternalUrl()](#getExternalUrl--) | URL خارجی را مشخص می‌کند. اگر این ویژگی مقدار غیر null گیرد، ویژگی TargetSlide مقدار null می‌شود. |
| [getExternalUrlOriginal()](#getExternalUrlOriginal--) | یک پیوند را نشان می‌دهد که برای این بخش تنظیم شده بدون توجه به محتوای واقعی بخش. |
| [getTargetSlide()](#getTargetSlide--) | اگر HyperlinkEx به اسلاید خاصی هدف داشته باشد، این اسلاید را برمی‌گرداند. |
| [getTargetFrame()](#getTargetFrame--) | قاب داخل مجموعه فریم‌های HTML والد را برای هدف پیوند والد، در صورت وجود، برمی‌گرداند. |
| [setTargetFrame(String value)](#setTargetFrame-java.lang.String-) | قاب داخل مجموعه فریم‌های HTML والد را برای هدف پیوند والد، در صورت وجود، برمی‌گرداند. |
| [getTooltip()](#getTooltip--) | رشته‌ای را برمی‌گرداند که ممکن است در رابط کاربری به عنوان مرتبط با پیوند والد نمایش داده شود. |
| [setTooltip(String value)](#setTooltip-java.lang.String-) | رشته‌ای را برمی‌گرداند که ممکن است در رابط کاربری به عنوان مرتبط با پیوند والد نمایش داده شود. |
| [getHistory()](#getHistory--) | تعیین می‌کند آیا هدف پیوند والد هنگام فراخوانی به فهرست پیوندهای مشاهده‌شده اضافه شود. |
| [setHistory(boolean value)](#setHistory-boolean-) | تعیین می‌کند آیا هدف پیوند والد هنگام فراخوانی به فهرست پیوندهای مشاهده‌شده اضافه شود. |
| [getHighlightClick()](#getHighlightClick--) | تعیین می‌کند آیا پیوند هنگام کلیک برجسته شود. |
| [setHighlightClick(boolean value)](#setHighlightClick-boolean-) | تعیین می‌کند آیا پیوند هنگام کلیک برجسته شود. |
| [getStopSoundOnClick()](#getStopSoundOnClick--) | تعیین می‌کند آیا صدای مرتبط با پیوند هنگام کلیک متوقف شود. |
| [setStopSoundOnClick(boolean value)](#setStopSoundOnClick-boolean-) | تعیین می‌کند آیا صدای مرتبط با پیوند هنگام کلیک متوقف شود. |
| [getSound()](#getSound--) | صدای در حال پخش پیوند را نشان می‌دهد. |
| [setSound(IAudio value)](#setSound-com.aspose.slides.IAudio-) | صدای در حال پخش پیوند را نشان می‌دهد. |
| [getColorSource()](#getColorSource--) | منبع رنگ پیوند را نشان می‌دهد - یا استایل‌ها یا قالب بخش. |
| [setColorSource(int value)](#setColorSource-int-) | منبع رنگ پیوند را نشان می‌دهد - یا استایل‌ها یا قالب بخش. |
| [equals(IHyperlink hlink)](#equals-com.aspose.slides.IHyperlink-) | تعیین می‌کند آیا دو نمونه Hyperlink برابر هستند. |

### getActionType() {#getActionType--}
```
public abstract int getActionType()
```

نوع عمل HyperLinkEx را برمی‌گرداند. فقط‌خواندنی [HyperlinkActionType](../../com.aspose.slides/hyperlinkactiontype).

**برگرداند:**
int

### getExternalUrl() {#getExternalUrl--}
```
public abstract String getExternalUrl()
```

آدرس URL خارجی را مشخص می‌کند. اگر این ویژگی مقدار غیر null گیرد، ویژگی TargetSlide مقدار null می‌شود. فقط‌خواندنی String.

**برگرداند:**
java.lang.String

### getExternalUrlOriginal() {#getExternalUrlOriginal--}
```
public abstract String getExternalUrlOriginal()
```

یک پیوند را نشان می‌دهد که برای این بخش تنظیم شده بدون توجه به محتوای واقعی بخش.

--------------------

PowerPoint رفتار خاصی نسبت به پیوندها و متن متناظر آنها در یک بخش دارد. این امکان را می‌دهد تا متن پیوند به شکل یک URL معتبر ایجاد شود که متفاوت از آدرس واقعی لینک است. در این حالت، وقتی لینک را در پنجره ویرایش مشاهده می‌کنید، به متن بخش تبدیل می‌شود. این ویژگی مقدار اصلی پیوند را نمایان می‌کند.

**برگرداند:**
java.lang.String

### getTargetSlide() {#getTargetSlide--}
```
public abstract ISlide getTargetSlide()
```

اگر HyperlinkEx به اسلاید خاصی هدف داشته باشد، این اسلاید را برمی‌گرداند. اگر این ویژگی مقدار غیر null گیرد، ویژگی ExternalUrl مقدار null می‌شود. فقط‌خواندنی [ISlide](../../com.aspose.slides/islide).

**برگرداند:**
[ISlide](../../com.aspose.slides/islide)

### getTargetFrame() {#getTargetFrame--}
```
public abstract String getTargetFrame()
```

قاب داخل مجموعه فریم‌های HTML والد را برای هدف پیوند والد، در صورت وجود، برمی‌گرداند. قابل‌نوشتن String.

**برگرداند:**
java.lang.String

### setTargetFrame(String value) {#setTargetFrame-java.lang.String-}
```
public abstract void setTargetFrame(String value)
```

قاب داخل مجموعه فریم‌های HTML والد را برای هدف پیوند والد، در صورت وجود، برمی‌گرداند. قابل‌نوشتن String.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | java.lang.String |  |

### getTooltip() {#getTooltip--}
```
public abstract String getTooltip()
```

رشته‌ای را برمی‌گرداند که ممکن است در رابط کاربری به عنوان مرتبط با پیوند والد نمایش داده شود. قابل‌نوشتن String.

**برگرداند:**
java.lang.String

### setTooltip(String value) {#setTooltip-java.lang.String-}
```
public abstract void setTooltip(String value)
```

رشته‌ای را برمی‌گرداند که ممکن است در رابط کاربری به عنوان مرتبط با پیوند والد نمایش داده شود. قابل‌نوشتن String.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | java.lang.String |  |

### getHistory() {#getHistory--}
```
public abstract boolean getHistory()
```

تعیین می‌کند آیا هدف پیوند والد هنگام فراخوانی به فهرست پیوندهای مشاهده‌شده اضافه شود. قابل‌نوشتن boolean.

**برگرداند:**
boolean

### setHistory(boolean value) {#setHistory-boolean-}
```
public abstract void setHistory(boolean value)
```

تعیین می‌کند آیا هدف پیوند والد هنگام فراخوانی به فهرست پیوندهای مشاهده‌شده اضافه شود. قابل‌نوشتن boolean.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | boolean |  |

### getHighlightClick() {#getHighlightClick--}
```
public abstract boolean getHighlightClick()
```

تعیین می‌کند آیا پیوند هنگام کلیک برجسته شود. قابل‌نوشتن boolean.

**برگرداند:**
boolean

### setHighlightClick(boolean value) {#setHighlightClick-boolean-}
```
public abstract void setHighlightClick(boolean value)
```

تعیین می‌کند آیا پیوند هنگام کلیک برجسته شود. قابل‌نوشتن boolean.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | boolean |  |

### getStopSoundOnClick() {#getStopSoundOnClick--}
```
public abstract boolean getStopSoundOnClick()
```

تعیین می‌کند آیا صدای مرتبط با پیوند هنگام کلیک متوقف شود. قابل‌نوشتن boolean.

**برگرداند:**
boolean

### setStopSoundOnClick(boolean value) {#setStopSoundOnClick-boolean-}
```
public abstract void setStopSoundOnClick(boolean value)
```

تعیین می‌کند آیا صدای مرتبط با پیوند هنگام کلیک متوقف شود. قابل‌نوشتن boolean.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | boolean |  |

### getSound() {#getSound--}
```
public abstract IAudio getSound()
```

صدای در حال پخش پیوند را نشان می‌دهد. قابل‌نوشتن [IAudio](../../com.aspose.slides/iaudio).

--------------------

> ```java
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>      ISlide slide = presentation.getSlides().get_Item(0);
> 
>      // دریافت اولین پیوند shape
>      IHyperlink link = presentation.getSlides().get_Item(0).getShapes().get_Item(0).getHyperlinkClick();
> 
>      if (link.getSound() != null)
>      {
>          // استخراج صدای hyperlink به صورت آرایه بایت
>          byte[] audioData = link.getSound().getBinaryData();
>      }
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```

**برگرداند:**
[IAudio](../../com.aspose.slides/iaudio)

### setSound(IAudio value) {#setSound-com.aspose.slides.IAudio-}
```
public abstract void setSound(IAudio value)
```

صدای در حال پخش پیوند را نشان می‌دهد. قابل‌نوشتن [IAudio](../../com.aspose.slides/iaudio).

--------------------

> ``` 
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>      ISlide slide = presentation.getSlides().get_Item(0);
> 
>      // دریافت اولین پیوند shape
>      IHyperlink link = presentation.getSlides().get_Item(0).getShapes().get_Item(0).getHyperlinkClick();
> 
>      if (link.getSound() != null)
>      {
>          // استخراج صدای hyperlink به صورت آرایه بایت
>          byte[] audioData = link.getSound().getBinaryData();
>      }
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | [IAudio](../../com.aspose.slides/iaudio) |  |

### getColorSource() {#getColorSource--}
```
public abstract int getColorSource()
```

منبع رنگ پیوند را نشان می‌دهد - یا استایل‌ها یا قالب بخش. قابل‌نوشتن [HyperlinkColorSource](../../com.aspose.slides/hyperlinkcolorsource).

**برگرداند:**
int

### setColorSource(int value) {#setColorSource-int-}
```
public abstract void setColorSource(int value)
```

منبع رنگ پیوند را نشان می‌دهد - یا استایل‌ها یا قالب بخش. قابل‌نوشتن [HyperlinkColorSource](../../com.aspose.slides/hyperlinkcolorsource).

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | int |  |

### equals(IHyperlink hlink) {#equals-com.aspose.slides.IHyperlink-}
```
public abstract boolean equals(IHyperlink hlink)
```

تعیین می‌کند آیا دو نمونه Hyperlink برابر هستند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| hlink | [IHyperlink](../../com.aspose.slides/ihyperlink) | Hyperlink برای مقایسه با Hyperlink فعلی. |

**برگرداند:**
boolean - **true** اگر Hyperlink مشخص شده برابر با Hyperlink فعلی باشد؛ در غیر این صورت **false**.