---
title: Hyperlink
second_title: مرجع API Aspose.Slides برای Java
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
| [Hyperlink(String url)](#Hyperlink-java.lang.String-) | یک نمونه از پیوند ایجاد می‌کند. |
| [Hyperlink(ISlide slide)](#Hyperlink-com.aspose.slides.ISlide-) | یک نمونه از پیوندی که به اسلاید خاصی اشاره می‌کند ایجاد می‌کند. |
| [Hyperlink(Hyperlink source, String targetFrame, String tooltip, boolean history, boolean stopSoundsOnClick, boolean highlightClick)](#Hyperlink-com.aspose.slides.Hyperlink-java.lang.String-java.lang.String-boolean-boolean-boolean-) | یک نمونه از پیوند با استفاده از پیوند دیگر به عنوان منبع ایجاد می‌کند و ویژگی‌های ثانویه را بازنویسی می‌کند. |
## متدها

| متد | توضیح |
| --- | --- |
| [getVersion()](#getVersion--) |  |
| [getNoAction()](#getNoAction--) | یک پیوند خاص «کاری نکن» را برمی‌گرداند. |
| [getMedia()](#getMedia--) | یک پیوند خاص «پخش فایل‌م رسانه» را برمی‌گرداند. |
| [getNextSlide()](#getNextSlide--) | یک پیوند به اسلاید بعدی را برمی‌گرداند. |
| [getPreviousSlide()](#getPreviousSlide--) | یک پیوند به اسلاید قبلی را برمی‌گرداند. |
| [getFirstSlide()](#getFirstSlide--) | یک پیوند به اولین اسلاید ارائه را برمی‌گرداند. |
| [getLastSlide()](#getLastSlide--) | یک پیوند به آخرین اسلاید ارائه را برمی‌گرداند. |
| [getLastVievedSlide()](#getLastVievedSlide--) | یک پیوند به آخرین اسلاید مشاهده شده را برمی‌گرداند. |
| [getEndShow()](#getEndShow--) | یک پیوند که نمایش را خاتمه می‌دهد را برمی‌گرداند. |
| [getActionType()](#getActionType--) | نوع عمل پیوند را برمی‌گرداند. |
| [getExternalUrl()](#getExternalUrl--) | URL خارجی را مشخص می‌کند. |
| [getTargetSlide()](#getTargetSlide--) | اگر پیوند به اسلاید خاصی هدف داشته باشد، همان اسلاید را برمی‌گرداند. |
| [getExternalUrlOriginal()](#getExternalUrlOriginal--) | یک پیوند را نشان می‌دهد که برای این بخش تنظیم شده بدون در نظر گرفتن محتوای واقعی بخش. |
| [getTargetFrame()](#getTargetFrame--) | قاب داخل مجموعه فریم‌های HTML والد برای هدف پیوند والد را (در صورت وجود) برمی‌گرداند. |
| [setTargetFrame(String value)](#setTargetFrame-java.lang.String-) | قاب داخل مجموعه فریم‌های HTML والد برای هدف پیوند والد را (در صورت وجود) برمی‌گرداند. |
| [getTooltip()](#getTooltip--) | رشته‌ای را که ممکن است در رابط کاربری به عنوان مرتبط با پیوند والد نمایش داده شود، برمی‌گرداند. |
| [setTooltip(String value)](#setTooltip-java.lang.String-) | رشته‌ای را که ممکن است در رابط کاربری به عنوان مرتبط با پیوند والد نمایش داده شود، برمی‌گرداند. |
| [getHistory()](#getHistory--) | مشخص می‌کند که آیا هدف پیوند والد باید به فهرست پیوندهای مشاهده‌شده افزوده شود هنگامی که فراخوانی می‌شود. |
| [setHistory(boolean value)](#setHistory-boolean-) | مشخص می‌کند که آیا هدف پیوند والد باید به فهرست پیوندهای مشاهده‌شده افزوده شود هنگامی که فراخوانی می‌شود. |
| [getHighlightClick()](#getHighlightClick--) | مشخص می‌کند که آیا پیوند باید روی کلیک برجسته شود. |
| [setHighlightClick(boolean value)](#setHighlightClick-boolean-) | مشخص می‌کند که آیا پیوند باید روی کلیک برجسته شود. |
| [getStopSoundOnClick()](#getStopSoundOnClick--) | مشخص می‌کند که آیا صدا باید هنگام کلیک بر روی پیوند متوقف شود. |
| [setStopSoundOnClick(boolean value)](#setStopSoundOnClick-boolean-) | مشخص می‌کند که آیا صدا باید هنگام کلیک بر روی پیوند متوقف شود. |
| [getSound()](#getSound--) | صدای در حال پخش پیوند را نشان می‌دهد. |
| [setSound(IAudio value)](#setSound-com.aspose.slides.IAudio-) | صدای در حال پخش پیوند را نشان می‌دهد. |
| [getColorSource()](#getColorSource--) | منبع رنگ پیوند را نشان می‌دهد — یا سبک‌ها یا قالب بخش. |
| [setColorSource(int value)](#setColorSource-int-) | منبع رنگ پیوند را نشان می‌دهد — یا سبک‌ها یا قالب بخش. |
| [equals(Object obj)](#equals-java.lang.Object-) | مشخص می‌کند آیا دو نمونهٔ Hyperlink برابر هستند. |
| [equals(IHyperlink hlink)](#equals-com.aspose.slides.IHyperlink-) | مشخص می‌کند آیا دو نمونهٔ Hyperlink برابر هستند. |
| [op_Equality(Hyperlink hlink1, Hyperlink hlink2)](#op-Equality-com.aspose.slides.Hyperlink-com.aspose.slides.Hyperlink-) | دو پیوند را برای برابری آزمون می‌کند. |
| [op_Inequality(Hyperlink hlink1, Hyperlink hlink2)](#op-Inequality-com.aspose.slides.Hyperlink-com.aspose.slides.Hyperlink-) | دو پیوند را برای نامساوی بودن آزمون می‌کند. |
| [hashCode()](#hashCode--) | به عنوان تابع هش برای یک نوع خاص عمل می‌کند، مناسب برای استفاده در الگوریتم‌های هش و ساختارهای داده‌ای مانند جدول هش. |
| [getParent_Immediate()](#getParent-Immediate--) |  |
### Hyperlink(String url) {#Hyperlink-java.lang.String-}
```
public Hyperlink(String url)
```

یک نمونه از پیوند ایجاد می‌کند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| url | java.lang.String | URL پیوند. |

### Hyperlink(ISlide slide) {#Hyperlink-com.aspose.slides.ISlide-}
```
public Hyperlink(ISlide slide)
```

یک نمونه از پیوندی که به اسلاید خاصی اشاره می‌کند ایجاد می‌کند. توجه: پیوند ایجاد شده باید به شی‌ای از همان ارائه اختصاص یابد، در غیر این صورت لینک به‌صورت NoAction ذخیره خواهد شد.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| slide | [ISlide](../../com.aspose.slides/islide) | اسلاید هدف. |

### Hyperlink(Hyperlink source, String targetFrame, String tooltip, boolean history, boolean stopSoundsOnClick, boolean highlightClick) {#Hyperlink-com.aspose.slides.Hyperlink-java.lang.String-java.lang.String-boolean-boolean-boolean-}
```
public Hyperlink(Hyperlink source, String targetFrame, String tooltip, boolean history, boolean stopSoundsOnClick, boolean highlightClick)
```

یک نمونه از پیوند با استفاده از پیوند دیگر به عنوان منبع ایجاد می‌کند و ویژگی‌های ثانویه را بازنویسی می‌کند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| source | [Hyperlink](../../com.aspose.slides/hyperlink) | پیوند منبع |
| targetFrame | java.lang.String | قاب هدف |
| tooltip | java.lang.String | متن توضیح ابزار |
| history | boolean | مشخص می‌کند که آیا هدف پیوند والد باید به فهرست پیوندهای مشاهده‌شده افزوده شود هنگامی که فراخوانی می‌شود. |
| stopSoundsOnClick | boolean | مشخص می‌کند که آیا صدا باید هنگام کلیک بر روی پیوند متوقف شود. |
| highlightClick | boolean | مشخص می‌کند که آیا پیوند باید روی کلیک برجسته شود. |

### getVersion() {#getVersion--}
```
public long getVersion()
```

نسخه. فقط خواندنی long.

**بازگرداندن:**
long
### getNoAction() {#getNoAction--}
```
public static Hyperlink getNoAction()
```

یک پیوند خاص «کاری نکن» را برمی‌گرداند. فقط خواندنی [Hyperlink](../../com.aspose.slides/hyperlink).

**بازگرداندن:**
[Hyperlink](../../com.aspose.slides/hyperlink)
### getMedia() {#getMedia--}
```
public static Hyperlink getMedia()
```

یک پیوند خاص «پخش فایل‌م رسانه» را برمی‌گرداند. در AudioFrame و VideoFrame استفاده می‌شود. فقط خواندنی [Hyperlink](../../com.aspose.slides/hyperlink).

**بازگرداندن:**
[Hyperlink](../../com.aspose.slides/hyperlink)
### getNextSlide() {#getNextSlide--}
```
public static Hyperlink getNextSlide()
```

یک پیوند به اسلاید بعدی را برمی‌گرداند. فقط خواندنی [Hyperlink](../../com.aspose.slides/hyperlink).

**بازگرداندن:**
[Hyperlink](../../com.aspose.slides/hyperlink)
### getPreviousSlide() {#getPreviousSlide--}
```
public static Hyperlink getPreviousSlide()
```

یک پیوند به اسلاید قبلی را برمی‌گرداند. فقط خواندنی [Hyperlink](../../com.aspose.slides/hyperlink).

**بازگرداندن:**
[Hyperlink](../../com.aspose.slides/hyperlink)
### getFirstSlide() {#getFirstSlide--}
```
public static Hyperlink getFirstSlide()
```

یک پیوند به اولین اسلاید ارائه را برمی‌گرداند. فقط خواندنی [Hyperlink](../../com.aspose.slides/hyperlink).

**بازگرداندن:**
[Hyperlink](../../com.aspose.slides/hyperlink)
### getLastSlide() {#getLastSlide--}
```
public static Hyperlink getLastSlide()
```

یک پیوند به آخرین اسلاید ارائه را برمی‌گرداند. فقط خواندنی [Hyperlink](../../com.aspose.slides/hyperlink).

**بازگرداندن:**
[Hyperlink](../../com.aspose.slides/hyperlink)
### getLastVievedSlide() {#getLastVievedSlide--}
```
public static Hyperlink getLastVievedSlide()
```

یک پیوند به آخرین اسلاید مشاهده شده را برمی‌گرداند. فقط خواندنی [Hyperlink](../../com.aspose.slides/hyperlink).

**بازگرداندن:**
[Hyperlink](../../com.aspose.slides/hyperlink)
### getEndShow() {#getEndShow--}
```
public static Hyperlink getEndShow()
```

یک پیوند که نمایش را خاتمه می‌دهد را برمی‌گرداند. فقط خواندنی [Hyperlink](../../com.aspose.slides/hyperlink).

**بازگرداندن:**
[Hyperlink](../../com.aspose.slides/hyperlink)
### getActionType() {#getActionType--}
```
public final int getActionType()
```

نوع عمل پیوند را برمی‌گرداند. فقط خواندنی [HyperlinkActionType](../../com.aspose.slides/hyperlinkactiontype).

**بازگرداندن:**
int
### getExternalUrl() {#getExternalUrl--}
```
public final String getExternalUrl()
```

URL خارجی را مشخص می‌کند. فقط خواندنی String.

**بازگرداندن:**
java.lang.String
### getTargetSlide() {#getTargetSlide--}
```
public final ISlide getTargetSlide()
```

اگر پیوند به اسلاید خاصی هدف داشته باشد، همان اسلاید را برمی‌گرداند. فقط خواندنی [ISlide](../../com.aspose.slides/islide).

**بازگرداندن:**
[ISlide](../../com.aspose.slides/islide)
### getExternalUrlOriginal() {#getExternalUrlOriginal--}
```
public final String getExternalUrlOriginal()
```

یک پیوند را نشان می‌دهد که برای این بخش تنظیم شده بدون در نظر گرفتن محتوای واقعی بخش.

--------------------

PowerPoint برای پیوندها و متن متناظرشان در یک بخش رفتار خاصی دارد. این امکان را می‌دهد که متن پیوند به صورت URL معتبر باشد، متفاوت از آدرس واقعی لینک. در این حالت، وقتی لینک را در پنجره ویرایش مشاهده می‌کنید، متن به‌صورت متن بخش تغییر می‌کند. این ویژگی مقدار اصلی پیوند را نشان می‌دهد.

**بازگرداندن:**
java.lang.String
### getTargetFrame() {#getTargetFrame--}
```
public final String getTargetFrame()
```

قاب داخل مجموعه فریم‌های HTML والد برای هدف پیوند والد را (در صورت وجود) برمی‌گرداند. خواندنی/نوشتنی String.

**بازگرداندن:**
java.lang.String
### setTargetFrame(String value) {#setTargetFrame-java.lang.String-}
```
public final void setTargetFrame(String value)
```

قاب داخل مجموعه فریم‌های HTML والد برای هدف پیوند والد را (در صورت وجود) برمی‌گرداند. خواندنی/نوشتنی String.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | java.lang.String |  |

### getTooltip() {#getTooltip--}
```
public final String getTooltip()
```

رشته‌ای را که ممکن است در رابط کاربری به عنوان مرتبط با پیوند والد نمایش داده شود، برمی‌گرداند. خواندنی/نوشتنی String.

**بازگرداندن:**
java.lang.String
### setTooltip(String value) {#setTooltip-java.lang.String-}
```
public final void setTooltip(String value)
```

رشته‌ای را که ممکن است در رابط کاربری به عنوان مرتبط با پیوند والد نمایش داده شود، برمی‌گرداند. خواندنی/نوشتنی String.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | java.lang.String |  |

### getHistory() {#getHistory--}
```
public final boolean getHistory()
```

مشخص می‌کند که آیا هدف پیوند والد باید به فهرست پیوندهای مشاهده‌شده افزوده شود هنگامی که فراخوانی می‌شود. خواندنی/نوشتنی boolean.

**بازگرداندن:**
boolean
### setHistory(boolean value) {#setHistory-boolean-}
```
public final void setHistory(boolean value)
```

مشخص می‌کند که آیا هدف پیوند والد باید به فهرست پیوندهای مشاهده‌شده افزوده شود هنگامی که فراخوانی می‌شود. خواندنی/نوشتنی boolean.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | boolean |  |

### getHighlightClick() {#getHighlightClick--}
```
public final boolean getHighlightClick()
```

مشخص می‌کند که آیا پیوند باید روی کلیک برجسته شود. خواندنی/نوشتنی boolean.

**بازگرداندن:**
boolean
### setHighlightClick(boolean value) {#setHighlightClick-boolean-}
```
public final void setHighlightClick(boolean value)
```

مشخص می‌کند که آیا پیوند باید روی کلیک برجسته شود. خواندنی/نوشتنی boolean.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | boolean |  |

### getStopSoundOnClick() {#getStopSoundOnClick--}
```
public final boolean getStopSoundOnClick()
```

مشخص می‌کند که آیا صدا باید هنگام کلیک بر روی پیوند متوقف شود. خواندنی/نوشتنی boolean.

**بازگرداندن:**
boolean
### setStopSoundOnClick(boolean value) {#setStopSoundOnClick-boolean-}
```
public final void setStopSoundOnClick(boolean value)
```

مشخص می‌کند که آیا صدا باید هنگام کلیک بر روی پیوند متوقف شود. خواندنی/نوشتنی boolean.

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
>          // استخراج صدای پیوند به‌صورت آرایه بایتی
>          byte[] audioData = link.getSound().getBinaryData();
>      }
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```

**بازگرداندن:**
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
>          // استخراج صدای پیوند به‌صورت آرایه بایتی
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

**بازگرداندن:**
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

مشخص می‌کند آیا دو نمونهٔ Hyperlink برابر هستند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| obj | java.lang.Object | Hyperlink برای مقایسه با Hyperlink فعلی. |

**بازگرداندن:**
boolean - **true** اگر Hyperlink مشخص‌شده برابر با Hyperlink فعلی باشد؛ در غیر این صورت **false**.
### equals(IHyperlink hlink) {#equals-com.aspose.slides.IHyperlink-}
```
public final boolean equals(IHyperlink hlink)
```

مشخص می‌کند آیا دو نمونهٔ Hyperlink برابر هستند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| hlink | [IHyperlink](../../com.aspose.slides/ihyperlink) | Hyperlink برای مقایسه با Hyperlink فعلی. |

**بازگرداندن:**
boolean - **true** اگر Hyperlink مشخص‌شده برابر با Hyperlink فعلی باشد؛ در غیر این صورت **false**.
### op_Equality(Hyperlink hlink1, Hyperlink hlink2) {#op-Equality-com.aspose.slides.Hyperlink-com.aspose.slides.Hyperlink-}
```
public static boolean op_Equality(Hyperlink hlink1, Hyperlink hlink2)
```

دو پیوند را برای برابری آزمون می‌کند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| hlink1 | [Hyperlink](../../com.aspose.slides/hyperlink) | اولین پیوند برای آزمایش. |
| hlink2 | [Hyperlink](../../com.aspose.slides/hyperlink) | دومین پیوند برای آزمایش. |

**بازگرداندن:**
boolean - **true** اگر پیوندها برابر باشند.
### op_Inequality(Hyperlink hlink1, Hyperlink hlink2) {#op-Inequality-com.aspose.slides.Hyperlink-com.aspose.slides.Hyperlink-}
```
public static boolean op_Inequality(Hyperlink hlink1, Hyperlink hlink2)
```

دو پیوند را برای نامساوی بودن آزمون می‌کند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| hlink1 | [Hyperlink](../../com.aspose.slides/hyperlink) | اولین پیوند برای آزمایش. |
| hlink2 | [Hyperlink](../../com.aspose.slides/hyperlink) | دومین پیوند برای آزمایش. |

**بازگرداندن:**
boolean - **false** اگر پیوندها برابر باشند.
### hashCode() {#hashCode--}
```
public int hashCode()
```

به عنوان تابع هش برای یک نوع خاص عمل می‌کند، مناسب برای استفاده در الگوریتم‌های هش و ساختارهای داده‌ای مانند جدول هش.

**بازگرداندن:**
int - کد هش برای یک URL.
### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```

شی Parent_Immediate را برمی‌گرداند. فقط خواندنی IDOMObject.

**بازگرداندن:**
com.aspose.slides.IDOMObject