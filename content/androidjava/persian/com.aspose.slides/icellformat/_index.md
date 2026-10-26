---
title: ICellFormat
second_title: Aspose.Slides برای Android از طریق مرجع API جاوا
description: سلول جدول فرمت را نشان می‌دهد.
type: docs
url: /fa/com.aspose.slides/icellformat/
---```
public interface ICellFormat
```

سلول جدول فرمت را نشان می‌دهد.
## متدها

| متد | توضیح |
| --- | --- |
| [getFillFormat()](#getFillFormat--) | یک شیء ویژگی‌های پر کردن سلول را برمی‌گرداند. |
| [getBorderLeft()](#getBorderLeft--) | یک شیء ویژگی‌های خط حاشیه چپ را برمی‌گرداند. |
| [getBorderTop()](#getBorderTop--) | یک شیء ویژگی‌های خط حاشیه بالا را برمی‌گرداند. |
| [getBorderRight()](#getBorderRight--) | یک شیء ویژگی‌های خط حاشیه راست را برمی‌گرداند. |
| [getBorderBottom()](#getBorderBottom--) | یک شیء ویژگی‌های خط حاشیه پایین را برمی‌گرداند. |
| [getBorderDiagonalDown()](#getBorderDiagonalDown--) | یک شیء ویژگی‌های خط قطری از بالا-چپ به پایین-راست را برمی‌گرداند. |
| [getBorderDiagonalUp()](#getBorderDiagonalUp--) | یک شیء ویژگی‌های خط قطری از پایین-چپ به بالا-راست را برمی‌گرداند. |
| [getTransparency()](#getTransparency--) | شفافیت رنگ پر کردن را دریافت یا تنظیم می‌کند. |
| [setTransparency(float value)](#setTransparency-float-) | شفافیت رنگ پر کردن را دریافت یا تنظیم می‌کند. |
| [getEffective()](#getEffective--) | ویژگی‌های قالب‌بندی مؤثر سلول جدول را با وراثت و سبک‌های جدول اعمال‌شده دریافت می‌کند. |
### getFillFormat() {#getFillFormat--}
```
public abstract IFillFormat getFillFormat()
```

یک شیء ویژگی‌های پر کردن سلول را برمی‌گرداند. فقط خواندنی [IFillFormat](../../com.aspose.slides/ifillformat).

**بازگشت:**
[IFillFormat](../../com.aspose.slides/ifillformat)
### getBorderLeft() {#getBorderLeft--}
```
public abstract ILineFormat getBorderLeft()
```

یک شیء ویژگی‌های خط حاشیه چپ را برمی‌گرداند. فقط خواندنی [ILineFormat](../../com.aspose.slides/ilineformat).

**بازگشت:**
[ILineFormat](../../com.aspose.slides/ilineformat)
### getBorderTop() {#getBorderTop--}
```
public abstract ILineFormat getBorderTop()
```

یک شیء ویژگی‌های خط حاشیه بالا را برمی‌گرداند. فقط خواندنی [ILineFormat](../../com.aspose.slides/ilineformat).

**بازگشت:**
[ILineFormat](../../com.aspose.slides/ilineformat)
### getBorderRight() {#getBorderRight--}
```
public abstract ILineFormat getBorderRight()
```

یک شیء ویژگی‌های خط حاشیه راست را برمی‌گرداند. فقط خواندنی [ILineFormat](../../com.aspose.slides/ilineformat).

**بازگشت:**
[ILineFormat](../../com.aspose.slides/ilineformat)
### getBorderBottom() {#getBorderBottom--}
```
public abstract ILineFormat getBorderBottom()
```

یک شیء ویژگی‌های خط حاشیه پایین را برمی‌گرداند. فقط خواندنی [ILineFormat](../../com.aspose.slides/ilineformat).

**بازگشت:**
[ILineFormat](../../com.aspose.slides/ilineformat)
### getBorderDiagonalDown() {#getBorderDiagonalDown--}
```
public abstract ILineFormat getBorderDiagonalDown()
```

یک شیء ویژگی‌های خط قطری از بالا-چپ به پایین-راست را برمی‌گرداند. فقط خواندنی [ILineFormat](../../com.aspose.slides/ilineformat).

**بازگشت:**
[ILineFormat](../../com.aspose.slides/ilineformat)
### getBorderDiagonalUp() {#getBorderDiagonalUp--}
```
public abstract ILineFormat getBorderDiagonalUp()
```

یک شیء ویژگی‌های خط قطری از پایین-چپ به بالا-راست را برمی‌گرداند. فقط خواندنی [ILineFormat](../../com.aspose.slides/ilineformat).

**بازگشت:**
[ILineFormat](../../com.aspose.slides/ilineformat)
### getTransparency() {#getTransparency--}
```
public abstract float getTransparency()
```

شفافیت رنگ پر کردن را دریافت یا تنظیم می‌کند. قابل خواندن/قابل نوشتن  float .

**بازگشت:**
float
### setTransparency(float value) {#setTransparency-float-}
```
public abstract void setTransparency(float value)
```

شفافیت رنگ پر کردن را دریافت یا تنظیم می‌کند. قابل خواندن/قابل نوشتن  float .

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | float |  |
### getEffective() {#getEffective--}
```
public abstract ICellFormatEffectiveData getEffective()
```

ویژگی‌های قالب‌بندی مؤثر سلول جدول را با وراثت و سبک‌های جدول اعمال‌شده دریافت می‌کند.

**بازگشت:**
[ICellFormatEffectiveData](../../com.aspose.slides/icellformateffectivedata) - یک [ICellFormatEffectiveData](../../com.aspose.slides/icellformateffectivedata).