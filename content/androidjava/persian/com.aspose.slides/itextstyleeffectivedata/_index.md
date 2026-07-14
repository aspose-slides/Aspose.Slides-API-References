---
title: ITextStyleEffectiveData
second_title: Aspose.Slides for Android via Java API Reference
description: شیء غیرقابل تغییر که شامل ویژگی‌های سبک متن مؤثر است.
type: docs
url: /fa/com.aspose.slides/itextstyleeffectivedata/
---```
public interface ITextStyleEffectiveData
```

شیء غیرقابل تغییر که شامل ویژگی‌های سبک متن مؤثر است.

--------------------

این رابط به همراه رابط [ITextStyle](../../com.aspose.slides/itextstyle) برای برگرداندن مقادیر قالب‌بندی مؤثر با اعمال وراثت استفاده می‌شود.
## متدها

| متد | توضیح |
| --- | --- |
| [getLevel(int index)](#getLevel-int-) | سطح سبک مؤثر را برمی‌گرداند. |
| [getDefaultParagraphFormat()](#getDefaultParagraphFormat--) | ویژگی‌های پیش‌فرض پاراگراف مؤثر را برمی‌گرداند. |
### getLevel(int index) {#getLevel-int-}
```
public abstract IParagraphFormatEffectiveData getLevel(int index)
```


سطح سبک مؤثر را برمی‌گرداند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| index | int | شاخص صفر مبنا برای سطح. باید در بازه 0..8 باشد. |

**بازگشت:**
[IParagraphFormatEffectiveData](../../com.aspose.slides/iparagraphformateffectivedata) - قالب‌بندی مؤثر سطح [IParagraphFormatEffectiveData](../../com.aspose.slides/iparagraphformateffectivedata).
### getDefaultParagraphFormat() {#getDefaultParagraphFormat--}
```
public abstract IParagraphFormatEffectiveData getDefaultParagraphFormat()
```


ویژگی‌های پیش‌فرض پاراگراف مؤثر را برمی‌گرداند. فقط-خواندنی [IParagraphFormatEffectiveData](../../com.aspose.slides/iparagraphformateffectivedata).

**بازگشت:**
[IParagraphFormatEffectiveData](../../com.aspose.slides/iparagraphformateffectivedata)