---
title: ICell
second_title: مرجع API Aspose.Slides برای جاوا
description: نمایانگر یک سلول در جدول.
type: docs
url: /fa/com.aspose.slides/icell/
---
**تمام رابط‌های پیاده‌سازی‌شده:**
[com.aspose.slides.ISlideComponent](../../com.aspose.slides/islidecomponent)
```
public interface ICell extends ISlideComponent
```

نمایانگر یک سلول در جدول است.
## متدها

| متد | توضیح |
| --- | --- |
| [getOffsetX()](#getOffsetX--) | فاصله‌ای را از سمت چپ جدول تا سمت چپ سلول برمی‌گرداند. |
| [getOffsetY()](#getOffsetY--) | فاصله‌ای را از بالای جدول تا بالای سلول برمی‌گرداند. |
| [getFirstRowIndex()](#getFirstRowIndex--) | شاخص ردیف اولی که توسط سلول پوشش داده می‌شود را برمی‌گرداند. |
| [getFirstColumnIndex()](#getFirstColumnIndex--) | شاخص ستون اولی که توسط سلول پوشش داده می‌شود را برمی‌گرداند. |
| [getWidth()](#getWidth--) | عرض سلول را برمی‌گرداند. |
| [getHeight()](#getHeight--) | ارتفاع سلول را برمی‌گرداند. |
| [getMinimalHeight()](#getMinimalHeight--) | حداقل ارتفاع سلول را برمی‌گرداند. |
| [getMarginLeft()](#getMarginLeft--) | حاشیه چپ در یک TextFrame را برمی‌گرداند یا تنظیم می‌کند. |
| [setMarginLeft(double value)](#setMarginLeft-double-) | حاشیه چپ در یک TextFrame را برمی‌گرداند یا تنظیم می‌کند. |
| [getMarginRight()](#getMarginRight--) | حاشیه راست در یک TextFrame را برمی‌گرداند یا تنظیم می‌کند. |
| [setMarginRight(double value)](#setMarginRight-double-) | حاشیه راست در یک TextFrame را برمی‌گرداند یا تنظیم می‌کند. |
| [getMarginTop()](#getMarginTop--) | حاشیه بالا در یک TextFrame را برمی‌گرداند یا تنظیم می‌کند. |
| [setMarginTop(double value)](#setMarginTop-double-) | حاشیه بالا در یک TextFrame را برمی‌گرداند یا تنظیم می‌کند. |
| [getMarginBottom()](#getMarginBottom--) | حاشیه پایین در یک TextFrame را برمی‌گرداند یا تنظیم می‌کند. |
| [setMarginBottom(double value)](#setMarginBottom-double-) | حاشیه پایین در یک TextFrame را برمی‌گرداند یا تنظیم می‌کند. |
| [getTextVerticalType()](#getTextVerticalType--) | نوع متن عمودی را برمی‌گرداند یا تنظیم می‌کند. |
| [setTextVerticalType(byte value)](#setTextVerticalType-byte-) | نوع متن عمودی را برمی‌گرداند یا تنظیم می‌کند. |
| [getTextAnchorType()](#getTextAnchorType--) | نوع لنگر متن را برمی‌گرداند یا تنظیم می‌کند. |
| [setTextAnchorType(byte value)](#setTextAnchorType-byte-) | نوع لنگر متن را برمی‌گرداند یا تنظیم می‌کند. |
| [getAnchorCenter()](#getAnchorCenter--) | تعیین می‌کند که آیا جعبه متن در داخل سلول مرکزی است یا خیر. |
| [setAnchorCenter(boolean value)](#setAnchorCenter-boolean-) | تعیین می‌کند که آیا جعبه متن در داخل سلول مرکزی است یا خیر. |
| [getFirstColumn()](#getFirstColumn--) | ستون اول سلول را دریافت می‌کند. |
| [getFirstRow()](#getFirstRow--) | ردیف اول سلول را دریافت می‌کند. |
| [getColSpan()](#getColSpan--) | تعداد ستون‌های شبکه در جدول والد را که باید توسط سلول فعلی پوشانده شوند، برمی‌گرداند. |
| [getRowSpan()](#getRowSpan--) | تعداد ردیف‌هایی که یک سلول ادغام‌شده پوشش می‌دهد را برمی‌گرداند. |
| [getTextFrame()](#getTextFrame--) | قاب متن سلول را برمی‌گرداند. |
| [getTable()](#getTable--) | شیء Table والد را برای یک سلول برمی‌گرداند. |
| [isMergedCell()](#isMergedCell--) | در صورتی که سلول با هر سلول تنظیم‌شده‌ای ادغام شده باشد، true برمی‌گرداند؛ در غیر این صورت false. |
| [getCellFormat()](#getCellFormat--) | شیء CellFormat که شامل ویژگی‌های قالب‌بندی برای این سلول است را برمی‌گرداند. |
| [splitByColSpan(int index)](#splitByColSpan-int-) | سلول را با توجه به شاخص ستون به دو سلول تقسیم می‌کند. |
| [splitByRowSpan(int index)](#splitByRowSpan-int-) | سلول را با توجه به شاخص ردیف به دو سلول تقسیم می‌کند. |
| [splitByHeight(double height)](#splitByHeight-double-) | سلول را بر حسب ارتفاع تقسیم می‌کند. |
| [splitByWidth(double width)](#splitByWidth-double-) | سلول را بر حسب عرض تقسیم می‌کند. |
### getOffsetX() {#getOffsetX--}
```
public abstract double getOffsetX()
```

فاصله‌ای را از سمت چپ جدول تا سمت چپ سلول برمی‌گرداند. فقط خواندنی double.

**بازگشت:**
double
### getOffsetY() {#getOffsetY--}
```
public abstract double getOffsetY()
```

فاصله‌ای را از بالای جدول تا بالای سلول برمی‌گرداند. فقط خواندنی double.

**بازگشت:**
double
### getFirstRowIndex() {#getFirstRowIndex--}
```
public abstract int getFirstRowIndex()
```

شاخص ردیف اولی که توسط سلول پوشش داده می‌شود را برمی‌گرداند. فقط خواندنی int.

**بازگشت:**
int
### getFirstColumnIndex() {#getFirstColumnIndex--}
```
public abstract int getFirstColumnIndex()
```

شاخص ستون اولی که توسط سلول پوشش داده می‌شود را برمی‌گرداند. فقط خواندنی int.

**بازگشت:**
int
### getWidth() {#getWidth--}
```
public abstract double getWidth()
```

عرض سلول را برمی‌گرداند. فقط خواندنی double.

**بازگشت:**
double
### getHeight() {#getHeight--}
```
public abstract double getHeight()
```

ارتفاع سلول را برمی‌گرداند. فقط خواندنی double.

**بازگشت:**
double
### getMinimalHeight() {#getMinimalHeight--}
```
public abstract double getMinimalHeight()
```

حداقل ارتفاع سلول را برمی‌گرداند. این مجموع حداقل ارتفاع تمام ردیف‌های تحت پوشش سلول است. فقط خواندنی double.

**بازگشت:**
double
### getMarginLeft() {#getMarginLeft--}
```
public abstract double getMarginLeft()
```

حاشیه چپ در یک TextFrame را برمی‌گرداند یا تنظیم می‌کند. قابل خواندن/نوشتن double.

**بازگشت:**
double
### setMarginLeft(double value) {#setMarginLeft-double-}
```
public abstract void setMarginLeft(double value)
```

حاشیه چپ در یک TextFrame را برمی‌گرداند یا تنظیم می‌کند. قابل خواندن/نوشتن double.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | double |  |

### getMarginRight() {#getMarginRight--}
```
public abstract double getMarginRight()
```

حاشیه راست در یک TextFrame را برمی‌گرداند یا تنظیم می‌کند. قابل خواندن/نوشتن double.

**بازگشت:**
double
### setMarginRight(double value) {#setMarginRight-double-}
```
public abstract void setMarginRight(double value)
```

حاشیه راست در یک TextFrame را برمی‌گرداند یا تنظیم می‌کند. قابل خواندن/نوشتن double.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | double |  |

### getMarginTop() {#getMarginTop--}
```
public abstract double getMarginTop()
```

حاشیه بالا در یک TextFrame را برمی‌گرداند یا تنظیم می‌کند. قابل خواندن/نوشتن double.

**بازگشت:**
double
### setMarginTop(double value) {#setMarginTop-double-}
```
public abstract void setMarginTop(double value)
```

حاشیه بالا در یک TextFrame را برمی‌گرداند یا تنظیم می‌کند. قابل خواندن/نوشتن double.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | double |  |

### getMarginBottom() {#getMarginBottom--}
```
public abstract double getMarginBottom()
```

حاشیه پایین در یک TextFrame را برمی‌گرداند یا تنظیم می‌کند. قابل خواندن/نوشتن double.

**بازگشت:**
double
### setMarginBottom(double value) {#setMarginBottom-double-}
```
public abstract void setMarginBottom(double value)
```

حاشیه پایین در یک TextFrame را برمی‌گرداند یا تنظیم می‌کند. قابل خواندن/نوشتن double.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | double |  |

### getTextVerticalType() {#getTextVerticalType--}
```
public abstract byte getTextVerticalType()
```

نوع متن عمودی را برمی‌گرداند یا تنظیم می‌کند. قابل خواندن/نوشتن [TextVerticalType](../../com.aspose.slides/textverticaltype).

**بازگشت:**
byte
### setTextVerticalType(byte value) {#setTextVerticalType-byte-}
```
public abstract void setTextVerticalType(byte value)
```

نوع متن عمودی را برمی‌گرداند یا تنظیم می‌کند. قابل خواندن/نوشتن [TextVerticalType](../../com.aspose.slides/textverticaltype).

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | byte |  |

### getTextAnchorType() {#getTextAnchorType--}
```
public abstract byte getTextAnchorType()
```

نوع لنگر متن را برمی‌گرداند یا تنظیم می‌کند. قابل خواندن/نوشتن [TextAnchorType](../../com.aspose.slides/textanchortype).

**بازگشت:**
byte
### setTextAnchorType(byte value) {#setTextAnchorType-byte-}
```
public abstract void setTextAnchorType(byte value)
```

نوع لنگر متن را برمی‌گرداند یا تنظیم می‌کند. قابل خواندن/نوشتن [TextAnchorType](../../com.aspose.slides/textanchortype).

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | byte |  |

### getAnchorCenter() {#getAnchorCenter--}
```
public abstract boolean getAnchorCenter()
```

تعیین می‌کند که آیا جعبه متن در داخل سلول مرکزی است یا خیر. خواندنی/قابل نوشتن boolean.

**بازگشت:**
boolean
### setAnchorCenter(boolean value) {#setAnchorCenter-boolean-}
```
public abstract void setAnchorCenter(boolean value)
```

تعیین می‌کند که آیا جعبه متن در داخل سلول مرکزی است یا خیر. خواندنی/قابل نوشتن boolean.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | boolean |  |

### getFirstColumn() {#getFirstColumn--}
```
public abstract IColumn getFirstColumn()
```

ستون اول سلول را دریافت می‌کند. فقط خواندنی [IColumn](../../com.aspose.slides/icolumn).

**بازگشت:**
[IColumn](../../com.aspose.slides/icolumn)
### getFirstRow() {#getFirstRow--}
```
public abstract IRow getFirstRow()
```

ردیف اول سلول را دریافت می‌کند. فقط خواندنی [IRow](../../com.aspose.slides/irow).

**بازگشت:**
[IRow](../../com.aspose.slides/irow)
### getColSpan() {#getColSpan--}
```
public abstract int getColSpan()
```

تعداد ستون‌های شبکه در جدول والد را که باید توسط سلول فعلی پوشانده شوند، برمی‌گرداند. این ویژگی امکان نمایش سلول‌ها به صورت ادغام‌شده را فراهم می‌کند، زیرا مرزهای عمودی سلول‌های دیگر را پوشش می‌دهد. فقط خواندنی int.

**بازگشت:**
int
### getRowSpan() {#getRowSpan--}
```
public abstract int getRowSpan()
```

تعداد ردیف‌هایی که یک سلول ادغام‌شده پوشش می‌دهد را برمی‌گرداند. این مقدار همراه با ویژگی vMerge در سلول‌های دیگر برای تعیین سلول شروع ادغام افقی استفاده می‌شود. فقط خواندنی int.

**بازگشت:**
int
### getTextFrame() {#getTextFrame--}
```
public abstract ITextFrame getTextFrame()
```

قاب متن سلول را برمی‌گرداند. فقط خواندنی [ITextFrame](../../com.aspose.slides/itextframe).

**بازگشت:**
[ITextFrame](../../com.aspose.slides/itextframe)
### getTable() {#getTable--}
```
public abstract ITable getTable()
```

شیء Table والد را برای یک سلول برمی‌گرداند. فقط خواندنی [ITable](../../com.aspose.slides/itable).

**بازگشت:**
[ITable](../../com.aspose.slides/itable)
### isMergedCell() {#isMergedCell--}
```
public abstract boolean isMergedCell()
```

در صورتی که سلول با هر سلول تنظیم‌شده‌ای ادغام شده باشد، true برمی‌گرداند؛ در غیر این صورت false. فقط خواندنی boolean.

**بازگشت:**
boolean
### getCellFormat() {#getCellFormat--}
```
public abstract ICellFormat getCellFormat()
```

شیء CellFormat که شامل ویژگی‌های قالب‌بندی برای این سلول است را برمی‌گرداند. فقط خواندنی [ICellFormat](../../com.aspose.slides/icellformat).

**بازگشت:**
[ICellFormat](../../com.aspose.slides/icellformat)
### splitByColSpan(int index) {#splitByColSpan-int-}
```
public abstract void splitByColSpan(int index)
```

سلول را با توجه به شاخص ستون به دو سلول تقسیم می‌کند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| index | int | شاخص ستون. |

### splitByRowSpan(int index) {#splitByRowSpan-int-}
```
public abstract void splitByRowSpan(int index)
```

سلول را با توجه به شاخص ردیف به دو سلول تقسیم می‌کند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| index | int | شاخص ردیف. |

### splitByHeight(double height) {#splitByHeight-double-}
```
public abstract void splitByHeight(double height)
```

سلول را بر حسب ارتفاع تقسیم می‌کند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| height | double | ارتفاع یک ردیف. |

### splitByWidth(double width) {#splitByWidth-double-}
```
public abstract void splitByWidth(double width)
```

سلول را بر حسب عرض تقسیم می‌کند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| width | double | عرض یک ستون. |