---
title: ITextToHtmlConversionOptions
second_title: Aspose.Slides for Java API Reference
description: Options for extracting HTML from the Pptx text.
type: docs
url: /fa/com.aspose.slides/itexttohtmlconversionoptions/
---```
public interface ITextToHtmlConversionOptions
```

گزینه‌هایی برای استخراج HTML از متن Pptx.
## متدها

| متد | توضیح |
| --- | --- |
| [getAddClipboardFragmentHeader()](#getAddClipboardFragmentHeader--) | مقدار را برمی‌گرداند یا تنظیم می‌کند که نشان می‌دهد آیا سرآیندهای Clipboard باید اضافه شوند. |
| [setAddClipboardFragmentHeader(boolean value)](#setAddClipboardFragmentHeader-boolean-) | مقدار را برمی‌گرداند یا تنظیم می‌کند که نشان می‌دهد آیا سرآیندهای Clipboard باید اضافه شوند. |
| [getTextInheritanceLimit()](#getTextInheritanceLimit--) | مقدار عمق وراثت ویژگی‌های متن را برمی‌گرداند یا تنظیم می‌کند. |
| [setTextInheritanceLimit(int value)](#setTextInheritanceLimit-int-) | مقدار عمق وراثت ویژگی‌های متن را برمی‌گرداند یا تنظیم می‌کند. |
| [getLinkEmbedController()](#getLinkEmbedController--) | یک شیء callback را برمی‌گرداند یا تنظیم می‌کند که نحوه ذخیره‌سازی شیء خارجی را کنترل می‌کند. |
| [setLinkEmbedController(ILinkEmbedController value)](#setLinkEmbedController-com.aspose.slides.ILinkEmbedController-) | یک شیء callback را برمی‌گرداند یا تنظیم می‌کند که نحوه ذخیره‌سازی شیء خارجی را کنترل می‌کند. |
| [getEncodingName()](#getEncodingName--) | نام رمزگذاری HTML را برمی‌گرداند یا تنظیم می‌کند. |
| [setEncodingName(String value)](#setEncodingName-java.lang.String-) | نام رمزگذاری HTML را برمی‌گرداند یا تنظیم می‌کند. |
### getAddClipboardFragmentHeader() {#getAddClipboardFragmentHeader--}
```
public abstract boolean getAddClipboardFragmentHeader()
```

مقدار را برمی‌گرداند یا تنظیم می‌کند که نشان می‌دهد آیا سرآیندهای Clipboard باید اضافه شوند. قابل خواندن/نوشتن boolean.

**بازگشت:**  
boolean
### setAddClipboardFragmentHeader(boolean value) {#setAddClipboardFragmentHeader-boolean-}
```
public abstract void setAddClipboardFragmentHeader(boolean value)
```

مقدار را برمی‌گرداند یا تنظیم می‌کند که نشان می‌دهد آیا سرآیندهای Clipboard باید اضافه شوند. قابل خواندن/نوشتن boolean.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | boolean |  |
### getTextInheritanceLimit() {#getTextInheritanceLimit--}
```
public abstract int getTextInheritanceLimit()
```

مقدار عمق وراثت ویژگی‌های متن را برمی‌گرداند یا تنظیم می‌کند. قابل خواندن/نوشتن [TextInheritanceLimit](../../com.aspose.slides/textinheritancelimit)(\#getTextInheritanceLimit.getTextInheritanceLimit/\#setTextInheritanceLimit(int).setTextInheritanceLimit(int)).

**بازگشت:**  
int
### setTextInheritanceLimit(int value) {#setTextInheritanceLimit-int-}
```
public abstract void setTextInheritanceLimit(int value)
```

مقدار عمق وراثت ویژگی‌های متن را برمی‌گرداند یا تنظیم می‌کند. قابل خواندن/نوشتن [TextInheritanceLimit](../../com.aspose.slides/textinheritancelimit)(\#getTextInheritanceLimit.getTextInheritanceLimit/\#setTextInheritanceLimit(int).setTextInheritanceLimit(int)).

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | int |  |
### getLinkEmbedController() {#getLinkEmbedController--}
```
public abstract ILinkEmbedController getLinkEmbedController()
```

یک شیء callback را برمی‌گرداند یا تنظیم می‌کند که کنترل می‌کند چگونه شیء خارجی ذخیره شود. قابل خواندن/نوشتن [ILinkEmbedController](../../com.aspose.slides/ilinkembedcontroller).

**بازگشت:**  
[ILinkEmbedController](../../com.aspose.slides/ilinkembedcontroller)
### setLinkEmbedController(ILinkEmbedController value) {#setLinkEmbedController-com.aspose.slides.ILinkEmbedController-}
```
public abstract void setLinkEmbedController(ILinkEmbedController value)
```

یک شیء callback را برمی‌گرداند یا تنظیم می‌کند که کنترل می‌کند چگونه شیء خارجی ذخیره شود. قابل خواندن/نوشتن [ILinkEmbedController](../../com.aspose.slides/ilinkembedcontroller).

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | [ILinkEmbedController](../../com.aspose.slides/ilinkembedcontroller) |  |
### getEncodingName() {#getEncodingName--}
```
public abstract String getEncodingName()
```

نام رمزگذاری HTML را برمی‌گرداند یا تنظیم می‌کند. این مقدار در فایل HTML تولید شده ذخیره خواهد شد، اما مسئولیت اطمینان از ذخیرهٔ فایل با این رمزگذاری به عهدهٔ فراخوانی‌کننده است. قابل خواندن/نوشتن String.

**بازگشت:**  
java.lang.String
### setEncodingName(String value) {#setEncodingName-java.lang.String-}
```
public abstract void setEncodingName(String value)
```

نام رمزگذاری HTML را برمی‌گرداند یا تنظیم می‌کند. این مقدار در فایل HTML تولید شده ذخیره خواهد شد، اما مسئولیت اطمینان از ذخیرهٔ فایل با این رمزگذاری به عهدهٔ فراخوانی‌کننده است. قابل خواندن/نوشتن String.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | java.lang.String |  |