---
title: TextToHtmlConversionOptions
second_title: Aspose.Slides برای Android از طریق مرجع API Java
description: گزینه‌هایی برای استخراج HTML از متن Pptx.
type: docs
url: /fa/com.aspose.slides/texttohtmlconversionoptions/
---
**وراثت:**  
java.lang.Object

**تمام رابط‌های پیاده‌سازی‌شده:**  
[com.aspose.slides.ITextToHtmlConversionOptions](../../com.aspose.slides/itexttohtmlconversionoptions)  
```
public final class TextToHtmlConversionOptions implements ITextToHtmlConversionOptions
```

گزینه‌های استخراج HTML از متن Pptx.

## سازنده‌ها

| سازنده | توضیح |
| --- | --- |
| [TextToHtmlConversionOptions()](#TextToHtmlConversionOptions--) |  |

## متدها

| متد | توضیح |
| --- | --- |
| [getAddClipboardFragmentHeader()](#getAddClipboardFragmentHeader--) | Returns or sets value, indicating if Clipboard headers should be added. |
| [setAddClipboardFragmentHeader(boolean value)](#setAddClipboardFragmentHeader-boolean-) | Returns or sets value, indicating if Clipboard headers should be added. |
| [getTextInheritanceLimit()](#getTextInheritanceLimit--) | Returns or sets inhering depth for text properties. |
| [setTextInheritanceLimit(int value)](#setTextInheritanceLimit-int-) | Returns or sets inhering depth for text properties. |
| [getLinkEmbedController()](#getLinkEmbedController--) | Returns or sets a callback object which controlls how external object will be stored. |
| [setLinkEmbedController(ILinkEmbedController value)](#setLinkEmbedController-com.aspose.slides.ILinkEmbedController-) | Returns or sets a callback object which controlls how external object will be stored. |
| [getEncodingName()](#getEncodingName--) | Returns or sets html encoding name. |
| [setEncodingName(String value)](#setEncodingName-java.lang.String-) | Returns or sets html encoding name. |

### TextToHtmlConversionOptions() {#TextToHtmlConversionOptions--}
```
public TextToHtmlConversionOptions()
```

### getAddClipboardFragmentHeader() {#getAddClipboardFragmentHeader--}
```
public final boolean getAddClipboardFragmentHeader()
```

مقدار را برمی‌گرداند یا تنظیم می‌کند که نشان می‌دهد آیا سرصفحه‌های Clipboard باید اضافه شوند. Read/write boolean.

**بازگشت:**  
boolean

### setAddClipboardFragmentHeader(boolean value) {#setAddClipboardFragmentHeader-boolean-}
```
public final void setAddClipboardFragmentHeader(boolean value)
```

مقدار را برمی‌گرداند یا تنظیم می‌کند که نشان می‌دهد آیا سرصفحه‌های Clipboard باید اضافه شوند. Read/write boolean.

**پارامترها:**  
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | boolean |  |

### getTextInheritanceLimit() {#getTextInheritanceLimit--}
```
public final int getTextInheritanceLimit()
```

عمق ارث‌بری برای ویژگی‌های متن را برمی‌گرداند یا تنظیم می‌کند. Read/write [TextInheritanceLimit](../../com.aspose.slides/textinheritancelimit).

**بازگشت:**  
int

### setTextInheritanceLimit(int value) {#setTextInheritanceLimit-int-}
```
public final void setTextInheritanceLimit(int value)
```

عمق ارث‌بری برای ویژگی‌های متن را برمی‌گرداند یا تنظیم می‌کند. Read/write [TextInheritanceLimit](../../com.aspose.slides/textinheritancelimit).

**پارامترها:**  
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | int |  |

### getLinkEmbedController() {#getLinkEmbedController--}
```
public final ILinkEmbedController getLinkEmbedController()
```

یک شیء callback را برمی‌گرداند یا تنظیم می‌کند که کنترل می‌کند چگونه شیء خارجی ذخیره شود. Read/write [ILinkEmbedController](../../com.aspose.slides/ilinkembedcontroller).

**بازگشت:**  
[ILinkEmbedController](../../com.aspose.slides/ilinkembedcontroller)

### setLinkEmbedController(ILinkEmbedController value) {#setLinkEmbedController-com.aspose.slides.ILinkEmbedController-}
```
public final void setLinkEmbedController(ILinkEmbedController value)
```

یک شیء callback را برمی‌گرداند یا تنظیم می‌کند که کنترل می‌کند چگونه شیء خارجی ذخیره شود. Read/write [ILinkEmbedController](../../com.aspose.slides/ilinkembedcontroller).

**پارامترها:**  
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | [ILinkEmbedController](../../com.aspose.slides/ilinkembedcontroller) |  |

### getEncodingName() {#getEncodingName--}
```
public final String getEncodingName()
```

نام رمزگذاری html را برمی‌گرداند یا تنظیم می‌کند. این مقدار در فایل HTML تولید شده ذخیره خواهد شد، اما این به عهده فراخوانی‌کننده است که اطمینان حاصل کند فایل با این رمزگذاری ذخیره شود. Read/write String.

**بازگشت:**  
java.lang.String

### setEncodingName(String value) {#setEncodingName-java.lang.String-}
```
public final void setEncodingName(String value)
```

نام رمزگذاری html را برمی‌گرداند یا تنظیم می‌کند. این مقدار در فایل HTML تولید شده ذخیره خواهد شد، اما این به عهده فراخوانی‌کننده است که اطمینان حاصل کند فایل با این رمزگذاری ذخیره شود. Read/write String.

**پارامترها:**  
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | java.lang.String |  |