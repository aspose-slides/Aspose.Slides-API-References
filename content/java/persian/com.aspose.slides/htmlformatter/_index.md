---
title: HtmlFormatter
second_title: مرجع API Aspose.Slides برای جاوا
description: قالب فایل HTML را نمایندگی می‌کند.
type: docs
url: /fa/com.aspose.slides/htmlformatter/
---
**ارث‌بری:**
java.lang.Object

**تمام اینترفیس‌های پیاده‌سازی‌شده:**
[com.aspose.slides.IHtmlFormatter](../../com.aspose.slides/ihtmlformatter)
```
public final class HtmlFormatter implements IHtmlFormatter
```

نماینده قالب فایل HTML.
## متدها

| متد | توضیح |
| --- | --- |
| [createDocumentFormatter(String css, boolean showSlideTitle)](#createDocumentFormatter-java.lang.String-boolean-) | یک فرمت‌کننده HTML را برای نمای ساده سند که شامل توالی اسلایدها به صورت یکی زیر دیگری است، ایجاد می‌کند و باز می‌گرداند. |
| [createSlideShowFormatter(String css, boolean showSlideTitle)](#createSlideShowFormatter-java.lang.String-boolean-) | یک فرمت‌کننده HTML برای یک اسلاید شو ساده ایجاد می‌کند و برمی‌گرداند که اسلایدها را یکی پس از دیگری نمایش می‌دهد. |
| [createCustomFormatter(IHtmlFormattingController formattingController)](#createCustomFormatter-com.aspose.slides.IHtmlFormattingController-) | یک فرمت‌کننده HTML برای تولید سفارشی با رانده شدن توسط کال‌بک ایجاد می‌کند و برمی‌گرداند. |
### createDocumentFormatter(String css, boolean showSlideTitle) {#createDocumentFormatter-java.lang.String-boolean-}
```
public static HtmlFormatter createDocumentFormatter(String css, boolean showSlideTitle)
```

یک فرمت‌کننده HTML برای نمای سند ساده ایجاد می‌کند و برمی‌گرداند که شامل توالی‌ای از اسلایدها به‌صورت یک زیر دیگری است.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| css | java.lang.String | CSS این فایل را مشخص می‌کند. |
| showSlideTitle | boolean | اگر عنوان اسلایدی بالای تصویر اسلاید وجود داشته باشد، عنوان اسلاید را اضافه کنید. |

**مقدار بازگشتی:**
[HtmlFormatter](../../com.aspose.slides/htmlformatter) - The [HtmlFormatter](../../com.aspose.slides/htmlformatter) object.
### createSlideShowFormatter(String css, boolean showSlideTitle) {#createSlideShowFormatter-java.lang.String-boolean-}
```
public static HtmlFormatter createSlideShowFormatter(String css, boolean showSlideTitle)
```

یک فرمت‌کننده HTML برای نمایش اسلاید ساده که اسلایدها را یکی پس از دیگری نشان می‌دهد، ایجاد و بر می‌گرداند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| css | java.lang.String | URL فایل CCS مورد استفاده را مشخص می‌کند. |
| showSlideTitle | boolean | اگر عنوان اسلایدی بالای تصویر اسلاید وجود داشته باشد، عنوان اسلاید را اضافه می‌کند. |

**باز می‌گرداند:**
[HtmlFormatter](../../com.aspose.slides/htmlformatter) - The [HtmlFormatter](../../com.aspose.slides/htmlformatter) object.
### createCustomFormatter(IHtmlFormattingController formattingController) {#createCustomFormatter-com.aspose.slides.IHtmlFormattingController-}
```
public static HtmlFormatter createCustomFormatter(IHtmlFormattingController formattingController)
```

یک فرمت‌کننده HTML برای تولید سفارشی بر پایهٔ فراخوانی‌های بازگشتی ایجاد و باز می‌گرداند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| formattingController | [IHtmlFormattingController](../../com.aspose.slides/ihtmlformattingcontroller) | رابط فراخوانی که تولید فایل HTML را کنترل می‌کند. |

**باز می‌گرداند:**
[HtmlFormatter](../../com.aspose.slides/htmlformatter) - The [HtmlFormatter](../../com.aspose.slides/htmlformatter) object.