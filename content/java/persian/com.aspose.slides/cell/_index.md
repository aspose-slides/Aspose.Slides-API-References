---
title: Cell
second_title: مرجع API Aspose.Slides برای Java
description: نمایانگر یک سلول از جدول است.
type: docs
url: /fa/com.aspose.slides/cell/
---
**ارث‌بری:**  
java.lang.Object

**تمام اینترفیس‌های پیاده‌سازی شده:**  
com.aspose.slides.IDOMObject, [com.aspose.slides.ICell](../../com.aspose.slides/icell)  
```
public class Cell implements IDOMObject, ICell
```

نمایش‌دهنده یک سلول از جدول.

## متدها

| متد | توضیح |
| --- | --- |
| [getOffsetX()](#getOffsetX--) | فاصله‌ای از سمت چپ جدول تا سمت چپ سلول را برمی‌گرداند. |
| [getOffsetY()](#getOffsetY--) | فاصله‌ای از سمت بالای جدول تا سمت بالای سلول را برمی‌گرداند. |
| [getFirstRowIndex()](#getFirstRowIndex--) | شاخص اولین سطری که توسط سلول پوشش داده می‌شود را برمی‌گرداند. |
| [getFirstColumnIndex()](#getFirstColumnIndex--) | شاخص اولین ستونی که توسط سلول پوشش داده می‌شود را برمی‌گرداند. |
| [getWidth()](#getWidth--) | عرض سلول را برمی‌گرداند. |
| [getHeight()](#getHeight--) | ارتفاع سلول را برمی‌گرداند. |
| [getMinimalHeight()](#getMinimalHeight--) | حداقل ارتفاع یک سلول را برمی‌گرداند. |
| [getMarginLeft()](#getMarginLeft--) | حاشیه چپ را در یک TextFrame برمی‌گرداند یا مقداردهی می‌کند. |
| [setMarginLeft(double value)](#setMarginLeft-double-) | حاشیه چپ را در یک TextFrame برمی‌گرداند یا مقداردهی می‌کند. |
| [getMarginRight()](#getMarginRight--) | حاشیه راست را در یک TextFrame برمی‌گرداند یا مقداردهی می‌کند. |
| [setMarginRight(double value)](#setMarginRight-double-) | حاشیه راست را در یک TextFrame برمی‌گرداند یا مقداردهی می‌کند. |
| [getMarginTop()](#getMarginTop--) | حاشیه بالایی را در یک TextFrame برمی‌گرداند یا مقداردهی می‌کند. |
| [setMarginTop(double value)](#setMarginTop-double-) | حاشیه بالایی را در یک TextFrame برمی‌گرداند یا مقداردهی می‌کند. |
| [getMarginBottom()](#getMarginBottom--) | حاشیه پایینی را در یک TextFrame برمی‌گرداند یا مقداردهی می‌کند. |
| [setMarginBottom(double value)](#setMarginBottom-double-) | حاشیه پایینی را در یک TextFrame برمی‌گرداند یا مقداردهی می‌کند. |
| [getTextVerticalType()](#getTextVerticalType--) | نوع متن عمودی را برمی‌گرداند یا مقداردهی می‌کند. |
| [setTextVerticalType(byte value)](#setTextVerticalType-byte-) | نوع متن عمودی را برمی‌گرداند یا مقداردهی می‌کند. |
| [getTextAnchorType()](#getTextAnchorType--) | نوع لنگر متن را برمی‌گرداند یا مقداردهی می‌کند. |
| [setTextAnchorType(byte value)](#setTextAnchorType-byte-) | نوع لنگر متن را برمی‌گرداند یا مقداردهی می‌کند. |
| [getAnchorCenter()](#getAnchorCenter--) | تعیین می‌کند که آیا جعبه متن درون سلول مرکز‌گرا است یا خیر. |
| [setAnchorCenter(boolean value)](#setAnchorCenter-boolean-) | تعیین می‌کند که آیا جعبه متن درون سلول مرکز‌گرا است یا خیر. |
| [getFirstRow()](#getFirstRow--) | اولین سطر سلول را بازمی‌گرداند. |
| [getFirstColumn()](#getFirstColumn--) | اولین ستون سلول را بازمی‌گرداند. |
| [getColSpan()](#getColSpan--) | تعداد ستون‌های شبکه جدول اصلی که توسط سلول جاری پوشانده می‌شود را برمی‌گرداند. |
| [getRowSpan()](#getRowSpan--) | تعداد سطرهایی که یک سلول ادغام‌شده پوشش می‌دهد را برمی‌گرداند. |
| [getTextFrame()](#getTextFrame--) | فریم متن سلول را برمی‌گرداند. |
| [getTable()](#getTable--) | شیء Table والد را برای سلول برمی‌گرداند. |
| [isMergedCell()](#isMergedCell--) | در صورتی که سلول با هر سلول تنظیم‌شده‌ای ادغام شده باشد true برمی‌گرداند، در غیر این صورت false. |
| [getCellFormat()](#getCellFormat--) | شیء CellFormat حاوی ویژگی‌های قالب‌بندی این سلول را برمی‌گرداند. |
| [splitByColSpan(int index)](#splitByColSpan-int-) | سلول را بر اساس شاخص ستون به دو سلول تقسیم می‌کند. |
| [splitByRowSpan(int index)](#splitByRowSpan-int-) | سلول را بر اساس شاخص سطر به دو سلول تقسیم می‌کند. |
| [splitByHeight(double height)](#splitByHeight-double-) | سلول را بر اساس ارتفاع تقسیم می‌کند. |
| [splitByWidth(double width)](#splitByWidth-double-) | سلول را بر اساس عرض تقسیم می‌کند. |
| [getSlide()](#getSlide--) | اسلاید والد سلول را برمی‌گرداند. |
| [getPresentation()](#getPresentation--) | ارائه (presentation) والد سلول را برمی‌گرداند. |
| [getParent_Immediate()](#getParent-Immediate--) |  |

### getOffsetX() {#getOffsetX--}
```
public final double getOffsetX()
```

فاصله‌ای از سمت چپ جدول تا سمت چپ سلول را برمی‌گرداند. فقط-خواندنی double.

**بازگشت:**  
double

### getOffsetY() {#getOffsetY--}
```
public final double getOffsetY()
```

فاصله‌ای از سمت بالای جدول تا سمت بالای سلول را برمی‌گرداند. فقط-خواندنی double.

**بازگشت:**  
double

### getFirstRowIndex() {#getFirstRowIndex--}
```
public final int getFirstRowIndex()
```

شاخص اولین سطری که توسط سلول پوشش داده می‌شود را برمی‌گرداند. فقط-خواندنی int.

**بازگشت:**  
int

### getFirstColumnIndex() {#getFirstColumnIndex--}
```
public final int getFirstColumnIndex()
```

شاخص اولین ستونی که توسط سلول پوشش داده می‌شود را برمی‌گرداند. فقط-خواندنی int.

**بازگشت:**  
int

### getWidth() {#getWidth--}
```
public final double getWidth()
```

عرض سلول را برمی‌گرداند. فقط-خواندنی double.

**بازگشت:**  
double

### getHeight() {#getHeight--}
```
public final double getHeight()
```

ارتفاع سلول را برمی‌گرداند. فقط-خواندنی double.

**بازگشت:**  
double

### getMinimalHeight() {#getMinimalHeight--}
```
public final double getMinimalHeight()
```

حداقل ارتفاع یک سلول را برمی‌گرداند. این مقدار مجموع حداقل ارتفاع تمام سطرهای تحت پوشش سلول است. فقط-خواندنی double.

**بازگشت:**  
double

### getMarginLeft() {#getMarginLeft--}
```
public final double getMarginLeft()
```

حاشیه چپ را در یک TextFrame برمی‌گرداند یا مقداردهی می‌کند. قابل‌نوشتن double.

**بازگشت:**  
double

### setMarginLeft(double value) {#setMarginLeft-double-}
```
public final void setMarginLeft(double value)
```

حاشیه چپ را در یک TextFrame برمی‌گرداند یا مقداردهی می‌کند. قابل‌نوشتن double.

**پارامترها:**  
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | double |  |

### getMarginRight() {#getMarginRight--}
```
public final double getMarginRight()
```

حاشیه راست را در یک TextFrame برمی‌گرداند یا مقداردهی می‌کند. قابل‌نوشتن double.

**بازگشت:**  
double

### setMarginRight(double value) {#setMarginRight-double-}
```
public final void setMarginRight(double value)
```

حاشیه راست را در یک TextFrame برمی‌گرداند یا مقداردهی می‌کند. قابل‌نوشتن double.

**پارامترها:**  
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | double |  |

### getMarginTop() {#getMarginTop--}
```
public final double getMarginTop()
```

حاشیه بالایی را در یک TextFrame برمی‌گرداند یا مقداردهی می‌کند. قابل‌نوشتن double.

**بازگشت:**  
double

### setMarginTop(double value) {#setMarginTop-double-}
```
public final void setMarginTop(double value)
```

حاشیه بالایی را در یک TextFrame برمی‌گرداند یا مقداردهی می‌کند. قابل‌نوشتن double.

**پارامترها:**  
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | double |  |

### getMarginBottom() {#getMarginBottom--}
```
public final double getMarginBottom()
```

حاشیه پایینی را در یک TextFrame برمی‌گرداند یا مقداردهی می‌کند. قابل‌نوشتن double.

**بازگشت:**  
double

### setMarginBottom(double value) {#setMarginBottom-double-}
```
public final void setMarginBottom(double value)
```

حاشیه پایینی را در یک TextFrame برمی‌گرداند یا مقداردهی می‌کند. قابل‌نوشتن double.

**پارامترها:**  
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | double |  |

### getTextVerticalType() {#getTextVerticalType--}
```
public final byte getTextVerticalType()
```

نوع متن عمودی را برمی‌گرداند یا مقداردهی می‌کند. قابل‌نوشتن [TextVerticalType](../../com.aspose.slides/textverticaltype).

**بازگشت:**  
byte

### setTextVerticalType(byte value) {#setTextVerticalType-byte-}
```
public final void setTextVerticalType(byte value)
```

نوع متن عمودی را برمی‌گرداند یا مقداردهی می‌کند. قابل‌نوشتن [TextVerticalType](../../com.aspose.slides/textverticaltype).

**پارامترها:**  
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | byte |  |

### getTextAnchorType() {#getTextAnchorType--}
```
public final byte getTextAnchorType()
```

نوع لنگر متن را برمی‌گرداند یا مقداردهی می‌کند. قابل‌نوشتن [TextAnchorType](../../com.aspose.slides/textanchortype).

**بازگشت:**  
byte

### setTextAnchorType(byte value) {#setTextAnchorType-byte-}
```
public final void setTextAnchorType(byte value)
```

نوع لنگر متن را برمی‌گرداند یا مقداردهی می‌کند. قابل‌نوشتن [TextAnchorType](../../com.aspose.slides/textanchortype).

**پارامترها:**  
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | byte |  |

### getAnchorCenter() {#getAnchorCenter--}
```
public final boolean getAnchorCenter()
```

تعیین می‌کند که آیا جعبه متن درون سلول مرکزگرا است یا خیر. قابل‌نوشتن boolean.

**بازگشت:**  
boolean

### setAnchorCenter(boolean value) {#setAnchorCenter-boolean-}
```
public final void setAnchorCenter(boolean value)
```

تعیین می‌کند که آیا جعبه متن درون سلول مرکزگرا است یا خیر. قابل‌نوشتن boolean.

**پارامترها:**  
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | boolean |  |

### getFirstRow() {#getFirstRow--}
```
public final IRow getFirstRow()
```

دریافت اولین سطر سلول. فقط-خواندنی [IRow](../../com.aspose.slides/irow).

**بازگشت:**  
[IRow](../../com.aspose.slides/irow)

### getFirstColumn() {#getFirstColumn--}
```
public final IColumn getFirstColumn()
```

دریافت اولین ستون سلول. فقط-خواندنی [IColumn](../../com.aspose.slides/icolumn).

**بازگشت:**  
[IColumn](../../com.aspose.slides/icolumn)

### getColSpan() {#getColSpan--}
```
public final int getColSpan()
```

تعداد ستون‌های شبکه جدول اصلی که توسط سلول جاری پوشانده می‌شود را برمی‌گرداند. این ویژگی اجازه می‌دهد سلول‌ها ظاهر ادغام داشته باشند، زیرا مرزهای عمودی سلول‌های دیگر را می‌پوشانند. فقط-خواندنی int.

**بازگشت:**  
int

### getRowSpan() {#getRowSpan--}
```
public final int getRowSpan()
```

تعداد سطرهایی که یک سلول ادغام‌شده پوشش می‌دهد را برمی‌گرداند. این مقدار به‌همراه ویژگی vMerge در سلول‌های دیگر برای مشخص کردن سلول آغازین ادغام افقی استفاده می‌شود. فقط-خواندنی int.

**بازگشت:**  
int

### getTextFrame() {#getTextFrame--}
```
public final ITextFrame getTextFrame()
```

فریم متن سلول را برمی‌گرداند. فقط-خواندنی [ITextFrame](../../com.aspose.slides/itextframe).

**بازگشت:**  
[ITextFrame](../../com.aspose.slides/itextframe)

### getTable() {#getTable--}
```
public final ITable getTable()
```

شیء Table والد را برای سلول برمی‌گرداند. فقط-خواندنی [ITable](../../com.aspose.slides/itable).

**بازگشت:**  
[ITable](../../com.aspose.slides/itable)

### isMergedCell() {#isMergedCell--}
```
public final boolean isMergedCell()
```

در صورتی که سلول با هر سلول تنظیم‌شده‌ای ادغام شده باشد true برمی‌گرداند، در غیر این صورت false. فقط-خواندنی boolean.

**بازگشت:**  
boolean

### getCellFormat() {#getCellFormat--}
```
public final ICellFormat getCellFormat()
```

شیء CellFormat حاوی ویژگی‌های قالب‌بندی این سلول را برمی‌گرداند. فقط-خواندنی [ICellFormat](../../com.aspose.slides/icellformat).

**بازگشت:**  
[ICellFormat](../../com.aspose.slides/icellformat)

### splitByColSpan(int index) {#splitByColSpan-int-}
```
public final void splitByColSpan(int index)
```

سلول را بر اساس شاخص ستون به دو سلول تقسیم می‌کند.

**پارامترها:**  
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| index | int | شاخص ستون. |

### splitByRowSpan(int index) {#splitByRowSpan-int-}
```
public final void splitByRowSpan(int index)
```

سلول را بر اساس شاخص سطر به دو سلول تقسیم می‌کند.

**پارامترها:**  
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| index | int | شاخص سطر. |

### splitByHeight(double height) {#splitByHeight-double-}
```
public final void splitByHeight(double height)
```

سلول را بر اساس ارتفاع تقسیم می‌کند.

**پارامترها:**  
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| height | double | ارتفاع یک سطر. |

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

اسلاید والد سلول را برمی‌گرداند. فقط-خواندنی [IBaseSlide](../../com.aspose.slides/ibaseslide).

**بازگشت:**  
[IBaseSlide](../../com.aspose.slides/ibaseslide)

### getPresentation() {#getPresentation--}
```
public final IPresentation getPresentation()
```

ارائه (presentation) والد سلول را برمی‌گرداند. فقط-خواندنی [IPresentation](../../com.aspose.slides/ipresentation).

**بازگشت:**  
[IPresentation](../../com.aspose.slides/ipresentation)

### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```

شیء Parent_Immediate را برمی‌گرداند. فقط-خواندنی IDOMObject.

**بازگشت:**  
com.aspose.slides.IDOMObject