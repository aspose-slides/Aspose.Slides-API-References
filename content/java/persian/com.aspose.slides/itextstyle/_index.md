---
title: ITextStyle
second_title: Aspose.Slides for Java API Reference
description: Text style formatting properties.
type: docs
url: /fa/com.aspose.slides/itextstyle/
---```
public interface ITextStyle
```

Text style formatting properties.
## Methods

| Method | Description |
| --- | --- |
| [getLevel(int index)](#getLevel-int-) | اگر سطح سبک موجود باشد آن را برمی‌گرداند، در غیر اینصورت null برمی‌گردد. |
| [getDefaultParagraphFormat()](#getDefaultParagraphFormat--) | ویژگی‌های پیش‌فرض پاراگراف. |
| [getEffective()](#getEffective--) | داده‌های قالب‌بندی متن سبک مؤثر را با به‌کارگیری ارث‌بری دریافت می‌کند. |
### getLevel(int index) {#getLevel-int-}
```
public abstract IParagraphFormat getLevel(int index)
```


اگر سطح سبک موجود باشد آن را برمی‌گرداند، در غیر اینصورت null برمی‌گردد.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | ایندکس صفر-مبنا برای سطح. باید در بازه 0..8 باشد. |

**Returns:**
[IParagraphFormat](../../com.aspose.slides/iparagraphformat) - قالب‌بندی سطح [IParagraphFormat](../../com.aspose.slides/iparagraphformat).
### getDefaultParagraphFormat() {#getDefaultParagraphFormat--}
```
public abstract IParagraphFormat getDefaultParagraphFormat()
```


ویژگی‌های پیش‌فرض پاراگراف. فقط-خواندنی [IParagraphFormat](../../com.aspose.slides/iparagraphformat).

**Returns:**
[IParagraphFormat](../../com.aspose.slides/iparagraphformat)
### getEffective() {#getEffective--}
```
public abstract ITextStyleEffectiveData getEffective()
```


داده‌های قالب‌بندی متن سبک مؤثر را با به‌کارگیری ارث‌بری دریافت می‌کند.

**Returns:**
[ITextStyleEffectiveData](../../com.aspose.slides/itextstyleeffectivedata) - یک [ITextStyleEffectiveData](../../com.aspose.slides/itextstyleeffectivedata).