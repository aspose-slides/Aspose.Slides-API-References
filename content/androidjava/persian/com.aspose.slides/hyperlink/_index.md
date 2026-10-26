---
title: Hyperlink
second_title: Aspose.Slides برای Android از طریق مرجع API جاوا
description: یک پیوند را نشان می‌دهد.
type: docs
url: /fa/com.aspose.slides/hyperlink/
---
**وراثت:**  
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject)

**تمام رابط‌های پیاده‌سازی‌شده:**  
[com.aspose.slides.IHyperlink](../../com.aspose.slides/ihyperlink), com.aspose.slides.IDOMObject  
```
public final class Hyperlink extends PVIObject implements IHyperlink, IDOMObject
```

یک پیوند را نشان می‌دهد.

## سازنده‌ها

| سازنده | توضیح |
| --- | --- |
| [Hyperlink(String url)](#Hyperlink-java.lang.String-) | یک نمونه از یک پیوند ایجاد می‌کند. |
| [Hyperlink(ISlide slide)](#Hyperlink-com.aspose.slides.ISlide-) | یک نمونه از یک پیوند که به اسلاید خاصی اشاره می‌کند ایجاد می‌کند. |
| [Hyperlink(Hyperlink source, String targetFrame, String tooltip, boolean history, boolean stopSoundsOnClick, boolean highlightClick)](#Hyperlink-com.aspose.slides.Hyperlink-java.lang.String-java.lang.String-boolean-boolean-boolean-) | یک نمونه از یک پیوند با استفاده از پیوند دیگر به عنوان منبع، با بازنویسی ویژگی‌های ثانویه ایجاد می‌کند. |

## متدها

| متد | توضیح |
| --- | --- |
| [getVersion()](#getVersion--) |  |
| [getNoAction()](#getNoAction--) | یک پیوند ویژه «کاری نکردن» را برمی‌گرداند. |
| [getMedia()](#getMedia--) | یک پیوند ویژه «پخش فایل رسانه‌ای» را برمی‌گرداند. |
| [getNextSlide()](#getNextSlide--) | یک پیوند به اسلاید بعدی را برمی‌گرداند. |
| [getPreviousSlide()](#getPreviousSlide--) | یک پیوند به اسلاید قبلی را برمی‌گرداند. |
| [getFirstSlide()](#getFirstSlide--) | یک پیوند به اولین اسلاید ارائه را برمی‌گرداند. |
| [getLastSlide()](#getLastSlide--) | یک پیوند به آخرین اسلاید ارائه را برمی‌گرداند. |
| [getLastVievedSlide()](#getLastVievedSlide--) | یک پیوند به آخرین اسلاید مشاهده‌شده را برمی‌گرداند. |
| [getEndShow()](#getEndShow--) | یک پیوند که نمایش را پایان می‌دهد را برمی‌گرداند. |
| [getActionType()](#getActionType--) | نوع عمل پیوند را برمی‌گرداند. |
| [getExternalUrl()](#getExternalUrl--) | URL خارجی را مشخص می‌کند. |
| [getTargetSlide()](#getTargetSlide--) | اگر پیوند به اسلاید خاصی هدف داشته باشد، آن اسلاید را برمی‌گرداند. |
| [getExternalUrlOriginal()](#getExternalUrlOriginal--) | یک پیوند را نشان می‌دهد که برای این بخش تنظیم شده بدون در نظر گرفتن محتوای واقعی بخش. |
| [getTargetFrame()](#getTargetFrame--) | قاب داخل مجموعه‌فریم HTML والد برای هدف پیوند والد را برمی‌گرداند، در صورتی که موجود باشد. |
| [setTargetFrame(String value)](#setTargetFrame-java.lang.String-) | قاب داخل مجموعه‌فریم HTML والد برای هدف پیوند والد را برمی‌گرداند، در صورتی که موجود باشد. |
| [getTooltip()](#getTooltip--) | رشته‌ای که ممکن است در رابط کاربری به عنوان مرتبط با پیوند والد نمایش داده شود را برمی‌گرداند. |
| [setTooltip(String value)](#setTooltip-java.lang.String-) | رشته‌ای که ممکن است در رابط کاربری به عنوان مرتبط با پیوند والد نمایش داده شود را برمی‌گرداند. |
| [getHistory()](#getHistory--) | تشخیص می‌دهد آیا هدف پیوند والد هنگام فراخوانی به فهرست پیوندهای مشاهده‌شده اضافه شود یا نه. |
| [setHistory(boolean value)](#setHistory-boolean-) | تشخیص می‌دهد آیا هدف پیوند والد هنگام فراخوانی به فهرست پیوندهای مشاهده‌شده اضافه شود یا نه. |
| [getHighlightClick()](#getHighlightClick--) | تشخیص می‌دهد آیا پیوند هنگام کلیک باید برجسته شود یا نه. |
| [setHighlightClick(boolean value)](#setHighlightClick-boolean-) | تشخیص می‌دهد آیا پیوند هنگام کلیک باید برجسته شود یا نه. |
| [getStopSoundOnClick()](#getStopSoundOnClick--) | تشخیص می‌دهد آیا صوت باید هنگام کلیک بر پیوند متوقف شود یا نه. |
| [setStopSoundOnClick(boolean value)](#setStopSoundOnClick-boolean-) | تشخیص می‌دهد آیا صوت باید هنگام کلیک بر پیوند متوقف شود یا نه. |
| [getSound()](#getSound--) | صدای در حال پخش پیوند را نشان می‌دهد. |
| [setSound(IAudio value)](#setSound-com.aspose.slides.IAudio-) | صدای در حال پخش پیوند را نشان می‌دهد. |
| [getColorSource()](#getColorSource--) | منبع رنگ پیوند را نشان می‌دهد — یا سبک‌ها یا قالب بخش. |
| [setColorSource(int value)](#setColorSource-int-) | منبع رنگ پیوند را نشان می‌دهد — یا سبک‌ها یا قالب بخش. |
| [equals(Object obj)](#equals-java.lang.Object-) | تشخیص می‌دهد آیا دو نمونهٔ پیوند برابر هستند یا نه. |
| [equals(IHyperlink hlink)](#equals-com.aspose.slides.IHyperlink-) | تشخیص می‌دهد آیا دو نمونهٔ پیوند برابر هستند یا نه. |
| [op_Equality(Hyperlink hlink1, Hyperlink hlink2)](#op-Equality-com.aspose.slides.Hyperlink-com.aspose.slides.Hyperlink-) | دو پیوند را برای برابری آزمون می‌کند. |
| [op_Inequality(Hyperlink hlink1, Hyperlink hlink2)](#op-Inequality-com.aspose.slides.Hyperlink-com.aspose.slides.Hyperlink-) | دو پیوند را برای نابرابری آزمون می‌کند. |
| [hashCode()](#hashCode--) | به عنوان یک تابع هش برای یک نوع خاص عمل می‌کند، مناسب برای استفاده در الگوریتم‌های هش و ساختارهای داده‌ای مانند جدول هش. |
| [getParent_Immediate()](#getParent-Immediate--) |  |

### Hyperlink(String url) {#Hyperlink-java.lang.String-}
```
public Hyperlink(String url)
```

یک نمونه از یک پیوند ایجاد می‌کند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| url | java.lang.String | URL پیوند. |

### Hyperlink(ISlide slide) {#Hyperlink-com.aspose.slides.ISlide-}
```
public Hyperlink(ISlide slide)
```

یک نمونه از یک پیوند که به اسلاید خاصی اشاره می‌کند ایجاد می‌کند. توجه: پیوند ایجاد شده باید به شی‌ای از همان ارائه اختصاص یابد، در غیر این صورت لینک به عنوان NoAction ذخیره خواهد شد.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| slide | [ISlide](../../com.aspose.slides/islide) | اسلاید هدف. |

### Hyperlink(Hyperlink source, String targetFrame, String tooltip, boolean history, boolean stopSoundsOnClick, boolean highlightClick) {#Hyperlink-com.aspose.slides.Hyperlink-java.lang.String-java.lang.String-boolean-boolean-boolean-}
```
public Hyperlink(Hyperlink source, String targetFrame, String tooltip, boolean history, boolean stopSoundsOnClick, boolean highlightClick)
```

یک نمونه از یک پیوند با استفاده از پیوند دیگر به عنوان منبع، با بازنویسی ویژگی‌های ثانویه ایجاد می‌کند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| source | [Hyperlink](../../com.aspose.slides/hyperlink) | پیوند منبع |
| targetFrame | java.lang.String | قاب هدف |
| tooltip | java.lang.String | متن راهنمای ابزار |
| history | boolean | تشخیص می‌دهد آیا هدف پیوند والد هنگام فراخوانی به فهرست پیوندهای مشاهده‌شده اضافه شود یا نه. |
| stopSoundsOnClick | boolean | تشخیص می‌دهد آیا صوت باید هنگام کلیک بر پیوند متوقف شود یا نه. |
| highlightClick | boolean | تشخیص می‌دهد آیا پیوند هنگام کلیک باید برجسته شود یا نه. |

### getVersion() {#getVersion--}
```
public long getVersion()
```

نسخه. فقط خواندنی long.

**برگشت:**  
long

### getNoAction() {#getNoAction--}
```
public static Hyperlink getNoAction()
```

یک پیوند ویژه «کاری نکردن» را برمی‌گرداند. فقط خواندنی [Hyperlink](../../com.aspose.slides/hyperlink).

**برگشت:**  
[Hyperlink](../../com.aspose.slides/hyperlink)

### getMedia() {#getMedia--}
```
public static Hyperlink getMedia()
```

یک پیوند ویژه «پخش فایل رسانه‌ای» را برمی‌گرداند. در AudioFrame و VideoFrame استفاده می‌شود. فقط خواندنی [Hyperlink](../../com.aspose.slides/hyperlink).

**برگشت:**  
[Hyperlink](../../com.aspose.slides/hyperlink)

### getNextSlide() {#getNextSlide--}
```
public static Hyperlink getNextSlide()
```

یک پیوند به اسلاید بعدی را برمی‌گرداند. فقط خواندنی [Hyperlink](../../com.aspose.slides/hyperlink).

**برگشت:**  
[Hyperlink](../../com.aspose.slides/hyperlink)

### getPreviousSlide() {#getPreviousSlide--}
```
public static Hyperlink getPreviousSlide()
```

یک پیوند به اسلاید قبلی را برمی‌گرداند. فقط خواندنی [Hyperlink](../../com.aspose.slides/hyperlink).

**برگشت:**  
[Hyperlink](../../com.aspose.slides/hyperlink)

### getFirstSlide() {#getFirstSlide--}
```
public static Hyperlink getFirstSlide()
```

یک پیوند به اولین اسلاید ارائه را برمی‌گرداند. فقط خواندنی [Hyperlink](../../com.aspose.slides/hyperlink).

**برگشت:**  
[Hyperlink](../../com.aspose.slides/hyperlink)

### getLastSlide() {#getLastSlide--}
```
public static Hyperlink getLastSlide()
```

یک پیوند به آخرین اسلاید ارائه را برمی‌گرداند. فقط خواندنی [Hyperlink](../../com.aspose.slides/hyperlink).

**برگشت:**  
[Hyperlink](../../com.aspose.slides/hyperlink)

### getLastVievedSlide() {#getLastVievedSlide--}
```
public static Hyperlink getLastVievedSlide()
```

یک پیوند به آخرین اسلاید مشاهده‌شده را برمی‌گرداند. فقط خواندنی [Hyperlink](../../com.aspose.slides/hyperlink).

**برگشت:**  
[Hyperlink](../../com.aspose.slides/hyperlink)

### getEndShow() {#getEndShow--}
```
public static Hyperlink getEndShow()
```

یک پیوند که نمایش را پایان می‌دهد را برمی‌گرداند. فقط خواندنی [Hyperlink](../../com.aspose.slides/hyperlink).

**برگشت:**  
[Hyperlink](../../com.aspose.slides/hyperlink)

### getActionType() {#getActionType--}
```
public final int getActionType()
```

نوع عمل پیوند را برمی‌گرداند. فقط خواندنی [HyperlinkActionType](../../com.aspose.slides/hyperlinkactiontype).

**برگشت:**  
int

### getExternalUrl() {#getExternalUrl--}
```
public final String getExternalUrl()
```

URL خارجی را مشخص می‌کند. فقط خواندنی String.

**برگشت:**  
java.lang.String

### getTargetSlide() {#getTargetSlide--}
```
public final ISlide getTargetSlide()
```

اگر پیوند به اسلاید خاصی هدف داشته باشد، آن اسلاید را برمی‌گرداند. فقط خواندنی [ISlide](../../com.aspose.slides/islide).

**برگشت:**  
[ISlide](../../com.aspose.slides/islide)

### getExternalUrlOriginal() {#getExternalUrlOriginal--}
```
public final String getExternalUrlOriginal()
```

یک پیوند را نشان می‌دهد که برای این بخش تنظیم شده بدون در نظر گرفتن محتوای واقعی بخش.

--------------------

PowerPoint برای لینک‌ها و متن متناظرشان در یک بخش رفتار خاصی دارد. این امکان را می‌دهد که متن پیوند به شکل URL معتبر ساخته شود، متفاوت از آدرس واقعی لینک. در این حالت، هنگام مشاهده لینک در پنجره ویرایش، متن به بخش متن تغییر می‌کند. این ویژگی مقدار اصلی پیوند را نشان می‌دهد.

**برگشت:**  
java.lang.String

### getTargetFrame() {#getTargetFrame--}
```
public final String getTargetFrame()
```

قاب داخل مجموعه‌فریم HTML والد برای هدف پیوند والد را برمی‌گرداند، در صورتی که موجود باشد. خواندنی/نوشتنی String.

**برگشت:**  
java.lang.String

### setTargetFrame(String value) {#setTargetFrame-java.lang.String-}
```
public final void setTargetFrame(String value)
```

قاب داخل مجموعه‌فریم HTML والد برای هدف پیوند والد را برمی‌گرداند، در صورتی که موجود باشد. خواندنی/نوشتنی String.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | java.lang.String |  |

### getTooltip() {#getTooltip--}
```
public final String getTooltip()
```

رشته‌ای که ممکن است در رابط کاربری به عنوان مرتبط با پیوند والد نمایش داده شود را برمی‌گرداند. خواندنی/نوشتنی String.

**برگشت:**  
java.lang.String

### setTooltip(String value) {#setTooltip-java.lang.String-}
```
public final void setTooltip(String value)
```

رشته‌ای که ممکن است در رابط کاربری به عنوان مرتبط با پیوند والد نمایش داده شود را برمی‌گرداند. خواندنی/نوشتنی String.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | java.lang.String |  |

### getHistory() {#getHistory--}
```
public final boolean getHistory()
```

تشخیص می‌دهد آیا هدف پیوند والد هنگام فراخوانی به فهرست پیوندهای مشاهده‌شده اضافه شود یا نه. خواندنی/نوشتنی boolean.

**برگشت:**  
boolean

### setHistory(boolean value) {#setHistory-boolean-}
```
public final void setHistory(boolean value)
```

تشخیص می‌دهد آیا هدف پیوند والد هنگام فراخوانی به فهرست پیوندهای مشاهده‌شده اضافه شود یا نه. خواندنی/نوشتنی boolean.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | boolean |  |

### getHighlightClick() {#getHighlightClick--}
```
public final boolean getHighlightClick()
```

تشخیص می‌دهد آیا پیوند هنگام کلیک باید برجسته شود یا نه. خواندنی/نوشتنی boolean.

**برگشت:**  
boolean

### setHighlightClick(boolean value) {#setHighlightClick-boolean-}
```
public final void setHighlightClick(boolean value)
```

تشخیص می‌دهد آیا پیوند هنگام کلیک باید برجسته شود یا نه. خواندنی/نوشتنی boolean.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | boolean |  |

### getStopSoundOnClick() {#getStopSoundOnClick--}
```
public final boolean getStopSoundOnClick()
```

تشخیص می‌دهد آیا صوت باید هنگام کلیک بر پیوند متوقف شود یا نه. خواندنی/نوشتنی boolean.

**برگشت:**  
boolean

### setStopSoundOnClick(boolean value) {#setStopSoundOnClick-boolean-}
```
public final void setStopSoundOnClick(boolean value)
```

تشخیص می‌دهد آیا صوت باید هنگام کلیک بر پیوند متوقف شود یا نه. خواندنی/نوشتنی boolean.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | boolean |  |

### getSound() {#getSound--}
```
public final IAudio getSound()
```

صدای در حال پخش پیوند را نشان می‌دهد. خواندنی/نوشتنی [IAudio](../../com.aspose.slides/iaudio).

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

**برگشت:**  
[IAudio](../../com.aspose.slides/iaudio)

### setSound(IAudio value) {#setSound-com.aspose.slides.IAudio-}
```
public final void setSound(IAudio value)
```

صدای در حال پخش پیوند را نشان می‌دهد. خواندنی/نوشتنی [IAudio](../../com.aspose.slides/iaudio).

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
public final int getColorSource()
```

منبع رنگ پیوند را نشان می‌دهد — یا سبک‌ها یا قالب بخش. خواندنی/نوشتنی [HyperlinkColorSource](../../com.aspose.slides/hyperlinkcolorsource).

**برگشت:**  
int

### setColorSource(int value) {#setColorSource-int-}
```
public final void setColorSource(int value)
```

منبع رنگ پیوند را نشان می‌دهد — یا سبک‌ها یا قالب بخش. خواندنی/نوشتنی [HyperlinkColorSource](../../com.aspose.slides/hyperlinkcolorsource).

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | int |  |

### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```

تشخیص می‌دهد آیا دو نمونهٔ پیوند برابر هستند یا نه.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| obj | java.lang.Object | پیوندی که با پیوند جاری مقایسه می‌شود. |

**برگشت:**  
boolean - **true** if the specified Hyperlink is equal to the current Hyperlink; otherwise, **false**.

### equals(IHyperlink hlink) {#equals-com.aspose.slides.IHyperlink-}
```
public final boolean equals(IHyperlink hlink)
```

تشخیص می‌دهد آیا دو نمونهٔ پیوند برابر هستند یا نه.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| hlink | [IHyperlink](../../com.aspose.slides/ihyperlink) | پیوندی که با پیوند جاری مقایسه می‌شود. |

**برگشت:**  
boolean - **true** if the specified Hyperlink is equal to the current Hyperlink; otherwise, **false**.

### op_Equality(Hyperlink hlink1, Hyperlink hlink2) {#op-Equality-com.aspose.slides.Hyperlink-com.aspose.slides.Hyperlink-}
```
public static boolean op_Equality(Hyperlink hlink1, Hyperlink hlink2)
```

دو پیوند را برای برابری آزمون می‌کند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| hlink1 | [Hyperlink](../../com.aspose.slides/hyperlink) | اولین پیوند برای آزمون. |
| hlink2 | [Hyperlink](../../com.aspose.slides/hyperlink) | دومین پیوند برای آزمون. |

**برگشت:**  
boolean - **true** if hyperlinks are equal.

### op_Inequality(Hyperlink hlink1, Hyperlink hlink2) {#op-Inequality-com.aspose.slides.Hyperlink-com.aspose.slides.Hyperlink-}
```
public static boolean op_Inequality(Hyperlink hlink1, Hyperlink hlink2)
```

دو پیوند را برای نابرابری آزمون می‌کند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| hlink1 | [Hyperlink](../../com.aspose.slides/hyperlink) | اولین پیوند برای آزمون. |
| hlink2 | [Hyperlink](../../com.aspose.slides/hyperlink) | دومین پیوند برای آزمون. |

**برگشت:**  
boolean - **false** if hyperlinks are equal.

### hashCode() {#hashCode--}
```
public int hashCode()
```

به عنوان یک تابع هش برای یک نوع خاص عمل می‌کند، مناسب برای استفاده در الگوریتم‌های هش و ساختارهای داده‌ای مانند جدول هش.

**برگشت:**  
int - Hash code for an URL.

### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```

شی Parent_Immediate را برمی‌گرداند. فقط خواندنی IDOMObject.

**برگشت:**  
com.aspose.slides.IDOMObject