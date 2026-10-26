---
title: ITextStyle
second_title: Aspose.Slides برای Android از طریق Java API Reference
description: خواص قالب‌بندی سبک متن.
type: docs
url: /fa/com.aspose.slides/itextstyle/
---```
public interface ITextStyle
```

خواص قالب‌بندی سبک متن.

## متدها

| متد | توضیح |
| --- | --- |
| [getLevel(int index)](#getLevel-int-) | اگر سطح سبک وجود داشته باشد آن را برمی‌گرداند، در غیر این صورت null برمی‌گرداند. |
| [getDefaultParagraphFormat()](#getDefaultParagraphFormat--) | خصوصیات پیش‌فرض پاراگراف. |
| [getEffective()](#getEffective--) | داده‌های قالب‌بندی سبک متن مؤثر را با اعمال ارث‌بری دریافت می‌کند. |

### getLevel(int index) {#getLevel-int-}
```
public abstract IParagraphFormat getLevel(int index)
```

اگر سطح سبک وجود داشته باشد آن را برمی‌گرداند، در غیر این صورت null برمی‌گرداند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| index | int | اندیس مبتنی بر صفر سطح. باید در بازه 0..8 باشد. |

**بازگشت:**
[IParagraphFormat](../../com.aspose.slides/iparagraphformat) - قالب‌بندی سطح [IParagraphFormat](../../com.aspose.slides/iparagraphformat).

### getDefaultParagraphFormat() {#getDefaultParagraphFormat--}
```
public abstract IParagraphFormat getDefaultParagraphFormat()
```

خصوصیات پیش‌فرض پاراگراف. فقط‌خواندنی [IParagraphFormat](../../com.aspose.slides/iparagraphformat).

**بازگشت:**
[IParagraphFormat](../../com.aspose.slides/iparagraphformat)

### getEffective() {#getEffective--}
```
public abstract ITextStyleEffectiveData getEffective()
```

داده‌های قالب‌بندی سبک متن مؤثر را با اعمال ارث‌بری دریافت می‌کند.

**بازگشت:**
[ITextStyleEffectiveData](../../com.aspose.slides/itextstyleeffectivedata) - یک [ITextStyleEffectiveData](../../com.aspose.slides/itextstyleeffectivedata).