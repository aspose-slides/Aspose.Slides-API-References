---
title: ITextStyleEffectiveData
second_title: Aspose.Slides for Java API Reference
description: Immutable object which contains effective text style properties.
type: docs
url: /fa/com.aspose.slides/itextstyleeffectivedata/
---```
public interface ITextStyleEffectiveData
```

شیء ثابت که شامل ویژگی‌های سبک متن مؤثر است.

--------------------

این اینترفیس همراه با اینترفیس [ITextStyle](../../com.aspose.slides/itextstyle) برای بازگرداندن مقادیر قالب‌بندی مؤثر با اعمال ارث‌بری مورد استفاده قرار می‌گیرد.
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

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | Zero-based index of level. Must lay in 0..8 interval. |

**Returns:**
[IParagraphFormatEffectiveData](../../com.aspose.slides/iparagraphformateffectivedata) - Effective formatting of level [IParagraphFormatEffectiveData](../../com.aspose.slides/iparagraphformateffectivedata).
### getDefaultParagraphFormat() {#getDefaultParagraphFormat--}
```
public abstract IParagraphFormatEffectiveData getDefaultParagraphFormat()
```

قالب‌بندی پیش‌فرض پاراگراف مؤثر را برمی‌گرداند. فقط-خواندنی [IParagraphFormatEffectiveData](../../com.aspose.slides/iparagraphformateffectivedata).

**Returns:**
[IParagraphFormatEffectiveData](../../com.aspose.slides/iparagraphformateffectivedata)