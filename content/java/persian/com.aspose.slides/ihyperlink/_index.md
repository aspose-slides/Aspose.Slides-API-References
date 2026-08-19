---
title: IHyperlink
second_title: Aspose.Slides for Java API Reference
description: Represents a hyperlink.
type: docs
url: /fa/com.aspose.slides/ihyperlink/
---```
public interface IHyperlink
```

Represents a hyperlink.
## متدها

| Method | Description |
| --- | --- |
| [getActionType()](#getActionType--) | نوع عمل HyperLinkEx را برمی‌گرداند. |
| [getExternalUrl()](#getExternalUrl--) | آدرس URL خارجی را مشخص می‌کند. اگر این ویژگی مقدار غیر null شود، ویژگی TargetSlide مقدار null می‌شود. |
| [getExternalUrlOriginal()](#getExternalUrlOriginal--) | پیوندی را نشان می‌دهد که برای این بخش تنظیم شده است بدون در نظر گرفتن محتوای واقعی بخش. |
| [getTargetSlide()](#getTargetSlide--) | اگر HyperlinkEx به اسلاید خاصی هدف داشته باشد، این اسلاید را برمی‌گرداند. |
| [getTargetFrame()](#getTargetFrame--) | قاب داخل مجموعه‌فریم‌های HTML والد برای هدف پیوند والد را زمانی که موجود باشد برمی‌گرداند. |
| [setTargetFrame(String value)](#setTargetFrame-java.lang.String-) | قاب داخل مجموعه‌فریم‌های HTML والد برای هدف پیوند والد را زمانی که موجود باشد برمی‌گرداند. |
| [getTooltip()](#getTooltip--) | رشته‌ای را برمی‌گرداند که ممکن است در رابط کاربری به عنوان مرتبط با پیوند والد نمایش داده شود. |
| [setTooltip(String value)](#setTooltip-java.lang.String-) | رشته‌ای را برمی‌گرداند که ممکن است در رابط کاربری به عنوان مرتبط با پیوند والد نمایش داده شود. |
| [getHistory()](#getHistory--) | تشخیص می‌دهد آیا هدف پیوند والد هنگام فراخوانی به لیست پیوندهای مشاهده‌شده اضافه شود. |
| [setHistory(boolean value)](#setHistory-boolean-) | تشخیص می‌دهد آیا هدف پیوند والد هنگام فراخوانی به لیست پیوندهای مشاهده‌شده اضافه شود. |
| [getHighlightClick()](#getHighlightClick--) | تشخیص می‌دهد آیا پیوند هنگام کلیک هایلایت شود. |
| [setHighlightClick(boolean value)](#setHighlightClick-boolean-) | تشخیص می‌دهد آیا پیوند هنگام کلیک هایلایت شود. |
| [getStopSoundOnClick()](#getStopSoundOnClick--) | تشخیص می‌دهد آیا صدا هنگام کلیک بر روی پیوند متوقف شود. |
| [setStopSoundOnClick(boolean value)](#setStopSoundOnClick-boolean-) | تشخیص می‌دهد آیا صدا هنگام کلیک بر روی پیوند متوقف شود. |
| [getSound()](#getSound--) | صوت در حال پخش پیوند را نشان می‌دهد. |
| [setSound(IAudio value)](#setSound-com.aspose.slides.IAudio-) | صوت در حال پخش پیوند را نشان می‌دهد. |
| [getColorSource()](#getColorSource--) | منبع رنگ پیوند را نشان می‌دهد - یا استایل‌ها یا قالب‌بندی بخش. |
| [setColorSource(int value)](#setColorSource-int-) | منبع رنگ پیوند را نشان می‌دهد - یا استایل‌ها یا قالب‌بندی بخش. |
| [equals(IHyperlink hlink)](#equals-com.aspose.slides.IHyperlink-) | تشخیص می‌دهد آیا دو نمونه Hyperlink برابر هستند. |

### getActionType() {#getActionType--}
```
public abstract int getActionType()
```

نوع عمل HyperLinkEx را برمی‌گرداند. فقط‌خواندنی [HyperlinkActionType](../../com.aspose.slides/hyperlinkactiontype).

**باز می‌گردد:**  
int

### getExternalUrl() {#getExternalUrl--}
```
public abstract String getExternalUrl()
```

آدرس URL خارجی را مشخص می‌کند. اگر این ویژگی مقدار غیر null شود، ویژگی TargetSlide مقدار null می‌شود. فقط‌خواندنی String.

**باز می‌گردد:**  
java.lang.String

### getExternalUrlOriginal() {#getExternalUrlOriginal--}
```
public abstract String getExternalUrlOriginal()
```

پیوندی را نشان می‌دهد که برای این بخش تنظیم شده است بدون در نظر گرفتن محتوای واقعی بخش.

--------------------

PowerPoint به‌صورت خاصی با پیوندها و متن مربوط به آن‌ها در یک بخش رفتار می‌کند. این امکان را فراهم می‌کند که متن برای پیوند به شکل یک URL معتبر ساخته شود که متفاوت از آدرس واقعی پیوند است. در این حالت، هنگامی که پیوند را در پنجره ویرایش مشاهده می‌کنید، متن آن به‌گونه‌ای تغییر می‌کند که با بخش متن مطابقت داشته باشد. این ویژگی مقدار اصلی پیوند را نشان می‌دهد.

**باز می‌گردد:**  
java.lang.String

### getTargetSlide() {#getTargetSlide--}
```
public abstract ISlide getTargetSlide()
```

اگر HyperlinkEx به اسلاید خاصی هدف داشته باشد، این اسلاید را برمی‌گرداند. اگر این ویژگی مقدار غیر null شود، ویژگی ExternalUrl مقدار null می‌شود. فقط‌خواندنی [ISlide](../../com.aspose.slides/islide).

**باز می‌گردد:**  
[ISlide](../../com.aspose.slides/islide)

### getTargetFrame() {#getTargetFrame--}
```
public abstract String getTargetFrame()
```

قاب داخل مجموعه‌فریم‌های HTML والد برای هدف پیوند والد را زمانی که موجود باشد برمی‌گرداند. قابل‌نوشتن String.

**باز می‌گردد:**  
java.lang.String

### setTargetFrame(String value) {#setTargetFrame-java.lang.String-}
```
public abstract void setTargetFrame(String value)
```

قاب داخل مجموعه‌فریم‌های HTML والد برای هدف پیوند والد را زمانی که موجود باشد برمی‌گرداند. قابل‌نوشتن String.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | java.lang.String |  |

### getTooltip() {#getTooltip--}
```
public abstract String getTooltip()
```

رشته‌ای را برمی‌گرداند که ممکن است در رابط کاربری به عنوان مرتبط با پیوند والد نمایش داده شود. قابل‌نوشتن String.

**باز می‌گردد:**  
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

تشخیص می‌دهد آیا هدف پیوند والد هنگام فراخوانی به لیست پیوندهای مشاهده‌شده اضافه شود. قابل‌نوشتن boolean.

**باز می‌گردد:**  
boolean

### setHistory(boolean value) {#setHistory-boolean-}
```
public abstract void setHistory(boolean value)
```

تشخیص می‌دهد آیا هدف پیوند والد هنگام فراخوانی به لیست پیوندهای مشاهده‌شده اضافه شود. قابل‌نوشتن boolean.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | boolean |  |

### getHighlightClick() {#getHighlightClick--}
```
public abstract boolean getHighlightClick()
```

تشخیص می‌دهد آیا پیوند هنگام کلیک هایلایت شود. قابل‌نوشتن boolean.

**باز می‌گردد:**  
boolean

### setHighlightClick(boolean value) {#setHighlightClick-boolean-}
```
public abstract void setHighlightClick(boolean value)
```

تشخیص می‌دهد آیا پیوند هنگام کلیک هایلایت شود. قابل‌نوشتن boolean.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | boolean |  |

### getStopSoundOnClick() {#getStopSoundOnClick--}
```
public abstract boolean getStopSoundOnClick()
```

تشخیص می‌دهد آیا صدا هنگام کلیک بر روی پیوند متوقف شود. قابل‌نوشتن boolean.

**باز می‌گردد:**  
boolean

### setStopSoundOnClick(boolean value) {#setStopSoundOnClick-boolean-}
```
public abstract void setStopSoundOnClick(boolean value)
```

تشخیص می‌دهد آیا صدا هنگام کلیک بر روی پیوند متوقف شود. قابل‌نوشتن boolean.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | boolean |  |

### getSound() {#getSound--}
```
public abstract IAudio getSound()
```

صوت در حال پخش پیوند را نشان می‌دهد. قابل‌نوشتن [IAudio](../../com.aspose.slides/iaudio).

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>      ISlide slide = presentation.getSlides().get_Item(0);
> 
>      // دریافت اولین پیوند شکل
>      IHyperlink link = presentation.getSlides().get_Item(0).getShapes().get_Item(0).getHyperlinkClick();
> 
>      if (link.getSound() != null)
>      {
>          // استخراج صدای پیوند به صورت آرایه بایت
>          byte[] audioData = link.getSound().getBinaryData();
>      }
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
```

**باز می‌گردد:**  
[IAudio](../../com.aspose.slides/iaudio)

### setSound(IAudio value) {#setSound-com.aspose.slides.IAudio-}
```
public abstract void setSound(IAudio value)
```

صوت در حال پخش پیوند را نشان می‌دهد. قابل‌نوشتن [IAudio](../../com.aspose.slides/iaudio).

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>      ISlide slide = presentation.getSlides().get_Item(0);
> 
>      // دریافت اولین پیوند شکل
>      IHyperlink link = presentation.getSlides().get_Item(0).getShapes().get_Item(0).getHyperlinkClick();
> 
>      if (link.getSound() != null)
>      {
>          // استخراج صدای پیوند به صورت آرایه بایت
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

منبع رنگ پیوند را نشان می‌دهد - یا استایل‌ها یا قالب‌بندی بخش. قابل‌نوشتن [HyperlinkColorSource](../../com.aspose.slides/hyperlinkcolorsource).

**باز می‌گردد:**  
int

### setColorSource(int value) {#setColorSource-int-}
```
public abstract void setColorSource(int value)
```

منبع رنگ پیوند را نشان می‌دهد - یا استایل‌ها یا قالب‌بندی بخش. قابل‌نوشتن [HyperlinkColorSource](../../com.aspose.slides/hyperlinkcolorsource).

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | int |  |

### equals(IHyperlink hlink) {#equals-com.aspose.slides.IHyperlink-}
```
public abstract boolean equals(IHyperlink hlink)
```

تشخیص می‌دهد آیا دو نمونه Hyperlink برابر هستند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| hlink | [IHyperlink](../../com.aspose.slides/ihyperlink) | Hyperlink برای مقایسه با Hyperlink جاری. |

**باز می‌گردد:**  
boolean - **true** اگر Hyperlink مشخص شده برابر با Hyperlink جاری باشد؛ در غیر این صورت، **false**.