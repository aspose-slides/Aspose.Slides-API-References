---
title: Cell
second_title: Aspose.Slides برای اندروید از طریق مرجع API جاوا
description: یک سلول از جدول را نشان می‌دهد.
type: docs
url: /fa/com.aspose.slides/cell/
---
**وراثت:**
java.lang.Object

**تمام رابط‌های پیاده‌سازی‌شده:**
com.aspose.slides.IDOMObject, [com.aspose.slides.ICell](../../com.aspose.slides/icell)
```
public class Cell implements IDOMObject, ICell
```

یک سلول از جدول را نشان می‌دهد.

## متدها

| متد | توضیح |
| --- | --- |
| [getOffsetX()](#getOffsetX--) | فاصله‌ای را از سمت چپ جدول تا سمت چپ سلول برمی‌گرداند. |
| [getOffsetY()](#getOffsetY--) | فاصله‌ای را از سمت بالا جدول تا سمت بالا سلول برمی‌گرداند. |
| [getFirstRowIndex()](#getFirstRowIndex--) | اندیس اولین ردیفی که توسط سلول پوشیده می‌شود را برمی‌گرداند. |
| [getFirstColumnIndex()](#getFirstColumnIndex--) | اندیس اولین ستونی که توسط سلول پوشیده می‌شود را برمی‌گرداند. |
| [getWidth()](#getWidth--) | عرض سلول را برمی‌گرداند. |
| [getHeight()](#getHeight--) | ارتفاع سلول را برمی‌گرداند. |
| [getMinimalHeight()](#getMinimalHeight--) | حداقل ارتفاع سلول را برمی‌گرداند. |
| [getMarginLeft()](#getMarginLeft--) | حاشیهٔ چپ را در یک TextFrame برمی‌گرداند یا تنظیم می‌کند. |
| [setMarginLeft(double value)](#setMarginLeft-double-) | حاشیهٔ چپ را در یک TextFrame برمی‌گرداند یا تنظیم می‌کند. |
| [getMarginRight()](#getMarginRight--) | حاشیهٔ راست را در یک TextFrame برمی‌گرداند یا تنظیم می‌کند. |
| [setMarginRight(double value)](#setMarginRight-double-) | حاشیهٔ راست را در یک TextFrame برمی‌گرداند یا تنظیم می‌کند. |
| [getMarginTop()](#getMarginTop--) | حاشیهٔ بالا را در یک TextFrame برمی‌گرداند یا تنظیم می‌کند. |
| [setMarginTop(double value)](#setMarginTop-double-) | حاشیهٔ بالا را در یک TextFrame برمی‌گرداند یا تنظیم می‌کند. |
| [getMarginBottom()](#getMarginBottom--) | حاشیهٔ پایین را در یک TextFrame برمی‌گرداند یا تنظیم می‌کند. |
| [setMarginBottom(double value)](#setMarginBottom-double-) | حاشیهٔ پایین را در یک TextFrame برمی‌گرداند یا تنظیم می‌کند. |
| [getTextVerticalType()](#getTextVerticalType--) | نوع متن عمودی را برمی‌گرداند یا تنظیم می‌کند. |
| [setTextVerticalType(byte value)](#setTextVerticalType-byte-) | نوع متن عمودی را برمی‌گرداند یا تنظیم می‌کند. |
| [getTextAnchorType()](#getTextAnchorType--) | نوع لنگر متن را برمی‌گرداند یا تنظیم می‌کند. |
| [setTextAnchorType(byte value)](#setTextAnchorType-byte-) | نوع لنگر متن را برمی‌گرداند یا تنظیم می‌کند. |
| [getAnchorCenter()](#getAnchorCenter--) | تعیین می‌کند که آیا جعبه متن درون سلول مرکز می‌شود یا نه. |
| [setAnchorCenter(boolean value)](#setAnchorCenter-boolean-) | تعیین می‌کند که آیا جعبه متن درون سلول مرکز می‌شود یا نه. |
| [getFirstRow()](#getFirstRow--) | اولین ردیف سلول را دریافت می‌کند. |
| [getFirstColumn()](#getFirstColumn--) | اولین ستون سلول را دریافت می‌کند. |
| [getColSpan()](#getColSpan--) | تعداد ستون‌های شبکهٔ جدول والد که توسط سلول فعلی پوشش می‌شود را برمی‌گرداند. |
| [getRowSpan()](#getRowSpan--) | تعداد ردیف‌هایی که یک سلول ترکیبی پوشش می‌دهد را برمی‌گرداند. |
| [getTextFrame()](#getTextFrame--) | قاب متن یک سلول را برمی‌گرداند. |
| [getTable()](#getTable--) | شیء Table والد را برای یک سلول برمی‌گرداند. |
| [isMergedCell()](#isMergedCell--) | اگر سلول با هر سلول تنظیم‌شده‌ای ترکیب شده باشد، true را برمی‌گرداند؛ در غیر این صورت false. |
| [getCellFormat()](#getCellFormat--) | شیء CellFormat را که شامل ویژگی‌های قالب‌بندی این سلول است برمی‌گرداند. |
| [splitByColSpan(int index)](#splitByColSpan-int-) | سلول را با استفاده از اندیس ستون به دو سلول تقسیم می‌کند. |
| [splitByRowSpan(int index)](#splitByRowSpan-int-) | سلول را با استفاده از اندیس ردیف به دو سلول تقسیم می‌کند. |
| [splitByHeight(double height)](#splitByHeight-double-) | سلول را بر اساس ارتفاع تقسیم می‌کند. |
| [splitByWidth(double width)](#splitByWidth-double-) | سلول را بر اساس عرض تقسیم می‌کند. |
| [getSlide()](#getSlide--) | اسلاید والد یک سلول را برمی‌گرداند. |
| [getPresentation()](#getPresentation--) | ارائهٔ والد یک سلول را برمی‌گرداند. |
| [getParent_Immediate()](#getParent-Immediate--) |  |

### getOffsetX() {#getOffsetX--}
```
public final double getOffsetX()
```

فاصله‌ای را از سمت چپ جدول تا سمت چپ سلول برمی‌گرداند. فقط خواندنی double.

**بازگشت:**
double

### getOffsetY() {#getOffsetY--}
```
public final double getOffsetY()
```

فاصله‌ای را از سمت بالا جدول تا سمت بالا سلول برمی‌گرداند. فقط خواندنی double.

**بازگشت:**
double

### getFirstRowIndex() {#getFirstRowIndex--}
```
public final int getFirstRowIndex()
```

اندیس اولین ردیفی که توسط سلول پوشیده می‌شود را برمی‌گرداند. فقط خواندنی int.

**بازگشت:**
int

### getFirstColumnIndex() {#getFirstColumnIndex--}
```
public final int getFirstColumnIndex()
```

اندیس اولین ستونی که توسط سلول پوشیده می‌شود را برمی‌گرداند. فقط خواندنی int.

**بازگشت:**
int

### getWidth() {#getWidth--}
```
public final double getWidth()
```

عرض سلول را برمی‌گرداند. فقط خواندنی double.

**بازگشت:**
double

### getHeight() {#getHeight--}
```
public final double getHeight()
```

ارتفاع سلول را برمی‌گرداند. فقط خواندنی double.

**بازگشت:**
double

### getMinimalHeight() {#getMinimalHeight--}
```
public final double getMinimalHeight()
```

حداقل ارتفاع سلول را برمی‌گرداند. این مقدار مجموع حداقل ارتفاع تمام ردیف‌های پوشیده‌شده توسط سلول است. فقط خواندنی double.

**بازگشت:**
double

### getMarginLeft() {#getMarginLeft--}
```
public final double getMarginLeft()
```

حاشیهٔ چپ را در یک TextFrame برمی‌گرداند یا تنظیم می‌کند. خواندنی/قابل نوشتن double.

**بازگشت:**
double

### setMarginLeft(double value) {#setMarginLeft-double-}
```
public final void setMarginLeft(double value)
```

حاشیهٔ چپ را در یک TextFrame برمی‌گرداند یا تنظیم می‌کند. خواندنی/قابل نوشتن double.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | double |  |

### getMarginRight() {#getMarginRight--}
```
public final double getMarginRight()
```

حاشیهٔ راست را در یک TextFrame برمی‌گرداند یا تنظیم می‌کند. خواندنی/قابل نوشتن double.

**بازگشت:**
double

### setMarginRight(double value) {#setMarginRight-double-}
```
public final void setMarginRight(double value)
```

حاشیهٔ راست را در یک TextFrame برمی‌گرداند یا تنظیم می‌کند. خواندنی/قابل نوشتن double.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | double |  |

### getMarginTop() {#getMarginTop--}
```
public final double getMarginTop()
```

حاشیهٔ بالا را در یک TextFrame برمی‌گرداند یا تنظیم می‌کند. خواندنی/قابل نوشتن double.

**بازگشت:**
double

### setMarginTop(double value) {#setMarginTop-double-}
```
public final void setMarginTop(double value)
```

حاشیهٔ بالا را در یک TextFrame برمی‌گرداند یا تنظیم می‌کند. خواندنی/قابل نوشتن double.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | double |  |

### getMarginBottom() {#getMarginBottom--}
```
public final double getMarginBottom()
```

حاشیهٔ پایین را در یک TextFrame برمی‌گرداند یا تنظیم می‌کند. خواندنی/قابل نوشتن double.

**بازگشت:**
double

### setMarginBottom(double value) {#setMarginBottom-double-}
```
public final void setMarginBottom(double value)
```

حاشیهٔ پایین را در یک TextFrame برمی‌گرداند یا تنظیم می‌کند. خواندنی/قابل نوشتن double.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | double |  |

### getTextVerticalType() {#getTextVerticalType--}
```
public final byte getTextVerticalType()
```

نوع متن عمودی را برمی‌گرداند یا تنظیم می‌کند. خواندنی/قابل نوشتن [TextVerticalType](../../com.aspose.slides/textverticaltype).

**بازگشت:**
byte

### setTextVerticalType(byte value) {#setTextVerticalType-byte-}
```
public final void setTextVerticalType(byte value)
```

نوع متن عمودی را برمی‌گرداند یا تنظیم می‌کند. خواندنی/قابل نوشتن [TextVerticalType](../../com.aspose.slides/textverticaltype).

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | byte |  |

### getTextAnchorType() {#getTextAnchorType--}
```
public final byte getTextAnchorType()
```

نوع لنگر متن را برمی‌گرداند یا تنظیم می‌کند. خواندنی/قابل نوشتن [TextAnchorType](../../com.aspose.slides/textanchortype).

**بازگشت:**
byte

### setTextAnchorType(byte value) {#setTextAnchorType-byte-}
```
public final void setTextAnchorType(byte value)
```

نوع لنگر متن را برمی‌گرداند یا تنظیم می‌کند. خواندنی/قابل نوشتن [TextAnchorType](../../com.aspose.slides/textanchortype).

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | byte |  |

### getAnchorCenter() {#getAnchorCenter--}
```
public final boolean getAnchorCenter()
```

تعیین می‌کند که آیا جعبه متن درون یک سلول مرکز می‌شود یا نه. خواندنی/قابل نوشتن boolean.

**بازگشت:**
boolean

### setAnchorCenter(boolean value) {#setAnchorCenter-boolean-}
```
public final void setAnchorCenter(boolean value)
```

تعیین می‌کند که آیا جعبه متن درون یک سلول مرکز می‌شود یا نه. خواندنی/قابل نوشتن boolean.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | boolean |  |

### getFirstRow() {#getFirstRow--}
```
public final IRow getFirstRow()
```

اولین ردیف سلول را دریافت می‌کند. فقط خواندنی [IRow](../../com.aspose.slides/irow).

**بازگشت:**
[IRow](../../com.aspose.slides/irow)

### getFirstColumn() {#getFirstColumn--}
```
public final IColumn getFirstColumn()
```

اولین ستون سلول را دریافت می‌کند. فقط خواندنی [IColumn](../../com.aspose.slides/icolumn).

**بازگشت:**
[IColumn](../../com.aspose.slides/icolumn)

### getColSpan() {#getColSpan--}
```
public final int getColSpan()
```

تعداد ستون‌های شبکهٔ جدول والد که توسط سلول فعلی پوشش می‌شود را برمی‌گرداند. این ویژگی اجازه می‌دهد سلول‌ها ظاهر ترکیب داشته باشند، زیرا مرزهای عمودی دیگر سلول‌ها را می‌پوشانند. فقط خواندنی int.

**بازگشت:**
int

### getRowSpan() {#getRowSpan--}
```
public final int getRowSpan()
```

تعداد ردیف‌هایی که یک سلول ترکیبی پوشش می‌دهد را برمی‌گرداند. این مقدار همراه با ویژگی vMerge در سلول‌های دیگر برای مشخص کردن سلول اولیه ترکیب افقی استفاده می‌شود. فقط خواندنی int.

**بازگشت:**
int

### getTextFrame() {#getTextFrame--}
```
public final ITextFrame getTextFrame()
```

قاب متن یک سلول را برمی‌گرداند. فقط خواندنی [ITextFrame](../../com.aspose.slides/itextframe).

**بازگشت:**
[ITextFrame](../../com.aspose.slides/itextframe)

### getTable() {#getTable--}
```
public final ITable getTable()
```

شیء Table والد را برای یک سلول برمی‌گرداند. فقط خواندنی [ITable](../../com.aspose.slides/itable).

**بازگشت:**
[ITable](../../com.aspose.slides/itable)

### isMergedCell() {#isMergedCell--}
```
public final boolean isMergedCell()
```

اگر سلول با هر سلول تنظیم‌شده‌ای ترکیب شده باشد، true را برمی‌گرداند؛ در غیر این صورت false. فقط خواندنی boolean.

**بازگشت:**
boolean

### getCellFormat() {#getCellFormat--}
```
public final ICellFormat getCellFormat()
```

شیء CellFormat را که شامل ویژگی‌های قالب‌بندی این سلول است برمی‌گرداند. فقط خواندنی [ICellFormat](../../com.aspose.slides/icellformat).

**بازگشت:**
[ICellFormat](../../com.aspose.slides/icellformat)

### splitByColSpan(int index) {#splitByColSpan-int-}
```
public final void splitByColSpan(int index)
```

سلول را با استفاده از اندیس ستون به دو سلول تقسیم می‌کند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| index | int | اندیس ستون. |

### splitByRowSpan(int index) {#splitByRowSpan-int-}
```
public final void splitByRowSpan(int index)
```

سلول را با استفاده از اندیس ردیف به دو سلول تقسیم می‌کند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| index | int | اندیس ردیف. |

### splitByHeight(double height) {#splitByHeight-double-}
```
public final void splitByHeight(double height)
```

سلول را بر اساس ارتفاع تقسیم می‌کند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| height | double | ارتفاع یک ردیف. |

### splitByWidth(double width) {#splitByWidth-double-}
```
public final void splitByWidth(double width)
```

سلول را بر اساس عرض تقسیم می‌کند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| width | double | عرض یک ستون. |

### getSlide() {#getSlide--}
```
public final IBaseSlide getSlide()
```

اسلاید والد یک سلول را برمی‌گرداند. فقط خواندنی [IBaseSlide](../../com.aspose.slides/ibaseslide).

**بازگشت:**
[IBaseSlide](../../com.aspose.slides/ibaseslide)

### getPresentation() {#getPresentation--}
```
public final IPresentation getPresentation()
```

ارائهٔ والد یک سلول را برمی‌گرداند. فقط خواندنی [IPresentation](../../com.aspose.slides/ipresentation).

**بازگشت:**
[IPresentation](../../com.aspose.slides/ipresentation)

### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```

شیء Parent_Immediate را برمی‌گرداند. فقط خواندنی IDOMObject.

**بازگشت:**
com.aspose.slides.IDOMObject