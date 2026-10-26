---
title: ITextToHtmlConversionOptions
second_title: Aspose.Slides for Android via Java API Reference
description: Options for extracting HTML from the Pptx text.
type: docs
url: /fa/com.aspose.slides/itexttohtmlconversionoptions/
---```
public interface ITextToHtmlConversionOptions
```

گزینه‌ها برای استخراج HTML از متن Pptx.
## متدها

| متد | توضیح |
| --- | --- |
| [getAddClipboardFragmentHeader()](#getAddClipboardFragmentHeader--) | مقدار را باز می‌گرداند یا تنظیم می‌کند که نشان می‌دهد آیا سرصفحه‌های Clipboard اضافه شوند یا نه. |
| [setAddClipboardFragmentHeader(boolean value)](#setAddClipboardFragmentHeader-boolean-) | مقدار را باز می‌گرداند یا تنظیم می‌کند که نشان می‌دهد آیا سرصفحه‌های Clipboard اضافه شوند یا نه. |
| [getTextInheritanceLimit()](#getTextInheritanceLimit--) | مقدار را باز می‌گرداند یا تنظیم می‌کند عمق وراثت برای ویژگی‌های متن. |
| [setTextInheritanceLimit(int value)](#setTextInheritanceLimit-int-) | مقدار را باز می‌گرداند یا تنظیم می‌کند عمق وراثت برای ویژگی‌های متن. |
| [getLinkEmbedController()](#getLinkEmbedController--) | مقدار را باز می‌گرداند یا تنظیم می‌کند یک شیء callback که نحوه ذخیره‌سازی شیء خارجی را کنترل می‌کند. |
| [setLinkEmbedController(ILinkEmbedController value)](#setLinkEmbedController-com.aspose.slides.ILinkEmbedController-) | مقدار را باز می‌گرداند یا تنظیم می‌کند یک شیء callback که نحوه ذخیره‌سازی شیء خارجی را کنترل می‌کند. |
| [getEncodingName()](#getEncodingName--) | مقدار را باز می‌گرداند یا تنظیم می‌کند نام رمزگذاری HTML. |
| [setEncodingName(String value)](#setEncodingName-java.lang.String-) | مقدار را باز می‌گرداند یا تنظیم می‌کند نام رمزگذاری HTML. |
### getAddClipboardFragmentHeader() {#getAddClipboardFragmentHeader--}
```
public abstract boolean getAddClipboardFragmentHeader()
```

مقدار را باز می‌گرداند یا تنظیم می‌کند که نشان می‌دهد آیا سرصفحه‌های Clipboard اضافه شوند یا نه. قابل خواندن/نوشتن boolean.

**بازمی‌گردد:**
boolean
### setAddClipboardFragmentHeader(boolean value) {#setAddClipboardFragmentHeader-boolean-}
```
public abstract void setAddClipboardFragmentHeader(boolean value)
```

مقدار را باز می‌گرداند یا تنظیم می‌کند که نشان می‌دهد آیا سرصفحه‌های Clipboard اضافه شوند یا نه. قابل خواندن/نوشتن boolean.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | boolean |  |
### getTextInheritanceLimit() {#getTextInheritanceLimit--}
```
public abstract int getTextInheritanceLimit()
```

مقدار را باز می‌گرداند یا تنظیم می‌کند عمق وراثت برای ویژگی‌های متن. قابل خواندن/نوشتن [TextInheritanceLimit](../../com.aspose.slides/textinheritancelimit)(\#getTextInheritanceLimit.getTextInheritanceLimit/\#setTextInheritanceLimit(int).setTextInheritanceLimit(int)).

**بازمی‌گردد:**
int
### setTextInheritanceLimit(int value) {#setTextInheritanceLimit-int-}
```
public abstract void setTextInheritanceLimit(int value)
```

مقدار را باز می‌گرداند یا تنظیم می‌کند عمق وراثت برای ویژگی‌های متن. قابل خواندن/نوشتن [TextInheritanceLimit](../../com.aspose.slides/textinheritancelimit)(\#getTextInheritanceLimit.getTextInheritanceLimit/\#setTextInheritanceLimit(int).setTextInheritanceLimit(int)).

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | int |  |
### getLinkEmbedController() {#getLinkEmbedController--}
```
public abstract ILinkEmbedController getLinkEmbedController()
```

مقدار را باز می‌گرداند یا تنظیم می‌کند یک شیء callback که نحوه ذخیره‌سازی شیء خارجی را کنترل می‌کند. قابل خواندن/نوشتن [ILinkEmbedController](../../com.aspose.slides/ilinkembedcontroller).

**بازمی‌گردد:**
[ILinkEmbedController](../../com.aspose.slides/ilinkembedcontroller)
### setLinkEmbedController(ILinkEmbedController value) {#setLinkEmbedController-com.aspose.slides.ILinkEmbedController-}
```
public abstract void setLinkEmbedController(ILinkEmbedController value)
```

مقدار را باز می‌گرداند یا تنظیم می‌کند یک شیء callback که نحوه ذخیره‌سازی شیء خارجی را کنترل می‌کند. قابل خواندن/نوشتن [ILinkEmbedController](../../com.aspose.slides/ilinkembedcontroller).

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | [ILinkEmbedController](../../com.aspose.slides/ilinkembedcontroller) |  |
### getEncodingName() {#getEncodingName--}
```
public abstract String getEncodingName()
```

مقدار را باز می‌گرداند یا تنظیم می‌کند نام رمزگذاری HTML. این مقدار در فایل HTML تولید شده ذخیره می‌شود، اما تضمین این‌که فایل با همین رمزگذاری ذخیره شود بر عهدهٔ فراخوان است. قابل خواندن/نوشتن String.

**بازمی‌گردد:**
java.lang.String
### setEncodingName(String value) {#setEncodingName-java.lang.String-}
```
public abstract void setEncodingName(String value)
```

مقدار را باز می‌گرداند یا تنظیم می‌کند نام رمزگذاری HTML. این مقدار در فایل HTML تولید شده ذخیره می‌شود، اما تضمین این‌که فایل با همین رمزگذاری ذخیره شود بر عهدهٔ فراخوان است. قابل خواندن/نوشتن String.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | java.lang.String |  |