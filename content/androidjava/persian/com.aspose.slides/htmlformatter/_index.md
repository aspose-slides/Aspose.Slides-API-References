---
title: HtmlFormatter
second_title: Aspose.Slides برای اندروید از طریق مرجع API جاوا
description: قالب فایل HTML را نشان می‌دهد.
type: docs
url: /fa/com.aspose.slides/htmlformatter/
---
**ارث‌بری:**  
java.lang.Object

**تمام رابط‌های پیاده‌سازی‌شده:**  
[com.aspose.slides.IHtmlFormatter](../../com.aspose.slides/ihtmlformatter)  
```
public final class HtmlFormatter implements IHtmlFormatter
```

قالب فایل HTML را نشان می‌دهد.

## متدها

| متد | توضیح |
| --- | --- |
| [createDocumentFormatter(String css, boolean showSlideTitle)](#createDocumentFormatter-java.lang.String-boolean-) | یک فرمت‌کننده HTML برای نمای سند ساده که شامل دنباله‌ای از اسلایدها به صورت زیر هم قرار گرفته است، ایجاد و برمی‌گرداند. |
| [createSlideShowFormatter(String css, boolean showSlideTitle)](#createSlideShowFormatter-java.lang.String-boolean-) | یک فرمت‌کننده HTML برای نمایش اسلایدشو ساده که اسلایدها را یکی پس از دیگری نشان می‌دهد، ایجاد و برمی‌گرداند. |
| [createCustomFormatter(IHtmlFormattingController formattingController)](#createCustomFormatter-com.aspose.slides.IHtmlFormattingController-) | یک فرمت‌کننده HTML برای تولید html سفارشی مبتنی بر کال‌بک، ایجاد و برمی‌گرداند. |

### createDocumentFormatter(String css, boolean showSlideTitle) {#createDocumentFormatter-java.lang.String-boolean-}
```
public static HtmlFormatter createDocumentFormatter(String css, boolean showSlideTitle)
```

یک فرمت‌کننده HTML برای نمای سند ساده که شامل دنباله‌ای از اسلایدها به صورت زیر هم قرار گرفته است، ایجاد و برمی‌گرداند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| css | java.lang.String | CSS را برای این فایل مشخص می‌کند. |
| showSlideTitle | boolean | اگر عنوان اسلایدی بالای تصویر اسلاید وجود دارد، عنوان اسلاید اضافه می‌شود. |

**بازگشت:**  
[HtmlFormatter](../../com.aspose.slides/htmlformatter) - شیء [HtmlFormatter](../../com.aspose.slides/htmlformatter).

### createSlideShowFormatter(String css, boolean showSlideTitle) {#createSlideShowFormatter-java.lang.String-boolean-}
```
public static HtmlFormatter createSlideShowFormatter(String css, boolean showSlideTitle)
```

یک فرمت‌کننده HTML برای نمایش اسلایدشو ساده که اسلایدها را یکی پس از دیگری نشان می‌دهد، ایجاد و برمی‌گرداند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| css | java.lang.String | آدرس URL فایل CSS مورد استفاده را مشخص می‌کند. |
| showSlideTitle | boolean | اگر عنوان اسلایدی بالای تصویر اسلاید وجود دارد، عنوان اسلاید اضافه می‌شود. |

**بازگشت:**  
[HtmlFormatter](../../com.aspose.slides/htmlformatter) - شیء [HtmlFormatter](../../com.aspose.slides/htmlformatter).

### createCustomFormatter(IHtmlFormattingController formattingController) {#createCustomFormatter-com.aspose.slides.IHtmlFormattingController-}
```
public static HtmlFormatter createCustomFormatter(IHtmlFormattingController formattingController)
```

یک فرمت‌کننده HTML برای تولید html سفارشی مبتنی بر کال‌بک، ایجاد و برمی‌گرداند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| formattingController | [IHtmlFormattingController](../../com.aspose.slides/ihtmlformattingcontroller) | رابط callback که تولید فایل html را کنترل می‌کند. |

**بازگشت:**  
[HtmlFormatter](../../com.aspose.slides/htmlformatter) - شیء [HtmlFormatter](../../com.aspose.slides/htmlformatter).