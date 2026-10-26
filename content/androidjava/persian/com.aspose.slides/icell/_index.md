---
title: ICell
second_title: Aspose.Slides برای Android از طریق مرجع API جاوا
description: نمایانگر یک سلول در جدول.
type: docs
url: /fa/com.aspose.slides/icell/
---
**تمام رابط‌های پیاده‌سازی شده:**
[com.aspose.slides.ISlideComponent](../../com.aspose.slides/islidecomponent)
```
public interface ICell extends ISlideComponent
```

نمایش یک cell در table.

## متدها

| متد | توضیح |
| --- | --- |
| [getOffsetX()](#getOffsetX--) | یک فاصله از سمت چپ table تا سمت چپ cell را بازمی‌گرداند. |
| [getOffsetY()](#getOffsetY--) | یک فاصله از سمت بالای table تا سمت بالای cell را بازمی‌گرداند. |
| [getFirstRowIndex()](#getFirstRowIndex--) | اندیس اولین ردیفی که توسط cell پوشش داده شده است را بازمی‌گرداند. |
| [getFirstColumnIndex()](#getFirstColumnIndex--) | اندیس اولین ستونی که توسط cell پوشش داده شده است را بازمی‌گرداند. |
| [getWidth()](#getWidth--) | عرض cell را بازمی‌گرداند. |
| [getHeight()](#getHeight--) | ارتفاع cell را بازمی‌گرداند. |
| [getMinimalHeight()](#getMinimalHeight--) | حداقل ارتفاع یک cell را بازمی‌گرداند. |
| [getMarginLeft()](#getMarginLeft--) | حاشیه چپ در TextFrame را بازمی‌گرداند یا تنظیم می‌کند. |
| [setMarginLeft(double value)](#setMarginLeft-double-) | حاشیه چپ در TextFrame را بازمی‌گرداند یا تنظیم می‌کند. |
| [getMarginRight()](#getMarginRight--) | حاشیه راست در TextFrame را بازمی‌گرداند یا تنظیم می‌کند. |
| [setMarginRight(double value)](#setMarginRight-double-) | حاشیه راست در TextFrame را بازمی‌گرداند یا تنظیم می‌کند. |
| [getMarginTop()](#getMarginTop--) | حاشیه بالای TextFrame را بازمی‌گرداند یا تنظیم می‌کند. |
| [setMarginTop(double value)](#setMarginTop-double-) | حاشیه بالای TextFrame را بازمی‌گرداند یا تنظیم می‌کند. |
| [getMarginBottom()](#getMarginBottom--) | حاشیه پایین در TextFrame را بازمی‌گرداند یا تنظیم می‌کند. |
| [setMarginBottom(double value)](#setMarginBottom-double-) | حاشیه پایین در TextFrame را بازمی‌گرداند یا تنظیم می‌کند. |
| [getTextVerticalType()](#getTextVerticalType--) | نوع متن عمودی را بازمی‌گرداند یا تنظیم می‌کند. |
| [setTextVerticalType(byte value)](#setTextVerticalType-byte-) | نوع متن عمودی را بازمی‌گرداند یا تنظیم می‌کند. |
| [getTextAnchorType()](#getTextAnchorType--) | نوع لنگر متن را بازمی‌گرداند یا تنظیم می‌کند. |
| [setTextAnchorType(byte value)](#setTextAnchorType-byte-) | نوع لنگر متن را بازمی‌گرداند یا تنظیم می‌کند. |
| [getAnchorCenter()](#getAnchorCenter--) | تعیین می‌کند که جعبه متن داخل یک cell مرکزگذاری شده است یا نه. |
| [setAnchorCenter(boolean value)](#setAnchorCenter-boolean-) | تعیین می‌کند که جعبه متن داخل یک cell مرکزگذاری شده است یا نه. |
| [getFirstColumn()](#getFirstColumn--) | ستون اولین cell را دریافت می‌کند. |
| [getFirstRow()](#getFirstRow--) | ردیف اولین cell را دریافت می‌کند. |
| [getColSpan()](#getColSpan--) | تعداد ستون‌های شبکه در جدول والد که باید توسط cell فعلی اشغال شود را بازمی‌گرداند. |
| [getRowSpan()](#getRowSpan--) | تعداد ردیف‌هایی که یک cell ادغام‌شده شامل می‌شود را بازمی‌گرداند. |
| [getTextFrame()](#getTextFrame--) | چارچوب متن یک cell را بازمی‌گرداند. |
| [getTable()](#getTable--) | شیء Table والد برای یک cell را بازمی‌گرداند. |
| [isMergedCell()](#isMergedCell--) | در صورت ادغام cell با هر cell تنظیم‌شده true و در غیر این صورت false بازمی‌گرداند. |
| [getCellFormat()](#getCellFormat--) | شیء CellFormat که شامل ویژگی‌های قالب‌بندی برای این cell است را بازمی‌گرداند. |
| [splitByColSpan(int index)](#splitByColSpan-int-) | cell را به دو cell بر اساس اندیس ستون تقسیم می‌کند. |
| [splitByRowSpan(int index)](#splitByRowSpan-int-) | cell را به دو cell بر اساس اندیس ردیف تقسیم می‌کند. |
| [splitByHeight(double height)](#splitByHeight-double-) | cell را بر اساس ارتفاع تقسیم می‌کند. |
| [splitByWidth(double width)](#splitByWidth-double-) | cell را بر اساس عرض تقسیم می‌کند. |
### getOffsetX() {#getOffsetX--}
```
public abstract double getOffsetX()
```

یک فاصله از سمت چپ table تا سمت چپ cell را بازمی‌گرداند. فقط خواندنی double.

**بازگشت:**
double
### getOffsetY() {#getOffsetY--}
```
public abstract double getOffsetY()
```

یک فاصله از سمت بالای table تا سمت بالای cell را بازمی‌گرداند. فقط خواندنی double.

**بازگشت:**
double
### getFirstRowIndex() {#getFirstRowIndex--}
```
public abstract int getFirstRowIndex()
```

اندیس اولین ردیفی که توسط cell پوشش داده شده است را بازمی‌گرداند. فقط خواندنی int.

**بازگشت:**
int
### getFirstColumnIndex() {#getFirstColumnIndex--}
```
public abstract int getFirstColumnIndex()
```

اندیس اولین ستونی که توسط cell پوشش داده شده است را بازمی‌گرداند. فقط خواندنی int.

**بازگشت:**
int
### getWidth() {#getWidth--}
```
public abstract double getWidth()
```

عرض cell را بازمی‌گرداند. فقط خواندنی double.

**بازگشت:**
double
### getHeight() {#getHeight--}
```
public abstract double getHeight()
```

ارتفاع cell را بازمی‌گرداند. فقط خواندنی double.

**بازگشت:**
double
### getMinimalHeight() {#getMinimalHeight--}
```
public abstract double getMinimalHeight()
```

حداقل ارتفاع یک cell را بازمی‌گرداند. این مجموع ارتفاع‌های حداقل تمام ردیف‌های تحت پوشش cell است. فقط خواندنی double.

**بازگشت:**
double
### getMarginLeft() {#getMarginLeft--}
```
public abstract double getMarginLeft()
```

حاشیه چپ در TextFrame را بازمی‌گرداند یا تنظیم می‌کند. قابل خواندن/نوشتن double.

**بازگشت:**
double
### setMarginLeft(double value) {#setMarginLeft-double-}
```
public abstract void setMarginLeft(double value)
```

حاشیه چپ در TextFrame را بازمی‌گرداند یا تنظیم می‌کند. قابل خواندن/نوشتن double.

**پارامترها:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | double |  |
### getMarginRight() {#getMarginRight--}
```
public abstract double getMarginRight()
```

حاشیه راست در TextFrame را بازمی‌گرداند یا تنظیم می‌کند. قابل خواندن/نوشتن double.

**بازگشت:**
double
### setMarginRight(double value) {#setMarginRight-double-}
```
public abstract void setMarginRight(double value)
```

حاشیه راست در TextFrame را بازمی‌گرداند یا تنظیم می‌کند. قابل خواندن/نوشتن double.

**پارامترها:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | double |  |
### getMarginTop() {#getMarginTop--}
```
public abstract double getMarginTop()
```

حاشیه بالای TextFrame را بازمی‌گرداند یا تنظیم می‌کند. قابل خواندن/نوشتن double.

**بازگشت:**
double
### setMarginTop(double value) {#setMarginTop-double-}
```
public abstract void setMarginTop(double value)
```

حاشیه بالای TextFrame را بازمی‌گرداند یا تنظیم می‌کند. قابل خواندن/نوشتن double.

**پارامترها:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | double |  |
### getMarginBottom() {#getMarginBottom--}
```
public abstract double getMarginBottom()
```

حاشیه پایین در TextFrame را بازمی‌گرداند یا تنظیم می‌کند. قابل خواندن/نوشتن double.

**بازگشت:**
double
### setMarginBottom(double value) {#setMarginBottom-double-}
```
public abstract void setMarginBottom(double value)
```

حاشیه پایین در TextFrame را بازمی‌گرداند یا تنظیم می‌کند. قابل خواندن/نوشتن double.

**پارامترها:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | double |  |
### getTextVerticalType() {#getTextVerticalType--}
```
public abstract byte getTextVerticalType()
```

نوع متن عمودی را بازمی‌گرداند یا تنظیم می‌کند. قابل خواندن/نوشتن [TextVerticalType](../../com.aspose.slides/textverticaltype).

**بازگشت:**
byte
### setTextVerticalType(byte value) {#setTextVerticalType-byte-}
```
public abstract void setTextVerticalType(byte value)
```

نوع متن عمودی را بازمی‌گرداند یا تنظیم می‌کند. قابل خواندن/نوشتن [TextVerticalType](../../com.aspose.slides/textverticaltype).

**پارامترها:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | byte |  |
### getTextAnchorType() {#getTextAnchorType--}
```
public abstract byte getTextAnchorType()
```

نوع لنگر متن را بازمی‌گرداند یا تنظیم می‌کند. قابل خواندن/نوشتن [TextAnchorType](../../com.aspose.slides/textanchortype).

**بازگشت:**
byte
### setTextAnchorType(byte value) {#setTextAnchorType-byte-}
```
public abstract void setTextAnchorType(byte value)
```

نوع لنگر متن را بازمی‌گرداند یا تنظیم می‌کند. قابل خواندن/نوشتن [TextAnchorType](../../com.aspose.slides/textanchortype).

**پارامترها:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | byte |  |
### getAnchorCenter() {#getAnchorCenter--}
```
public abstract boolean getAnchorCenter()
```

تعیین می‌کند که جعبه متن داخل یک cell مرکزگذاری شده است یا نه. قابل خواندن/نوشتن boolean.

**بازگشت:**
boolean
### setAnchorCenter(boolean value) {#setAnchorCenter-boolean-}
```
public abstract void setAnchorCenter(boolean value)
```

تعیین می‌کند که جعبه متن داخل یک cell مرکزگذاری شده است یا نه. قابل خواندن/نوشتن boolean.

**پارامترها:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |
### getFirstColumn() {#getFirstColumn--}
```
public abstract IColumn getFirstColumn()
```

ستون اولین cell را دریافت می‌کند. فقط خواندنی [IColumn](../../com.aspose.slides/icolumn).

**بازگشت:**
[IColumn](../../com.aspose.slides/icolumn)
### getFirstRow() {#getFirstRow--}
```
public abstract IRow getFirstRow()
```

ردیف اولین cell را دریافت می‌کند. فقط خواندنی [IRow](../../com.aspose.slides/irow).

**بازگشت:**
[IRow](../../com.aspose.slides/irow)
### getColSpan() {#getColSpan--}
```
public abstract int getColSpan()
```

تعداد ستون‌های شبکه در جدول والد که باید توسط cell فعلی اشغال شود را بازمی‌گرداند. این ویژگی اجازه می‌دهد تا cellها ظاهری شبیه به ادغام داشته باشند، زیرا مرزهای عمودی سایر cellهای جدول را پوشش می‌دهند. فقط خواندنی int.

**بازگشت:**
int
### getRowSpan() {#getRowSpan--}
```
public abstract int getRowSpan()
```

تعداد ردیف‌هایی که یک cell ادغام‌شده شامل می‌شود را بازمی‌گرداند. این برای ترکیب با ویژگی vMerge در سایر cellها به‌منظور مشخص کردن سلول شروع ادغام افقی استفاده می‌شود. فقط خواندنی int.

**بازگشت:**
int
### getTextFrame() {#getTextFrame--}
```
public abstract ITextFrame getTextFrame()
```

چارچوب متن یک cell را بازمی‌گرداند. فقط خواندنی [ITextFrame](../../com.aspose.slides/itextframe).

**بازگشت:**
[ITextFrame](../../com.aspose.slides/itextframe)
### getTable() {#getTable--}
```
public abstract ITable getTable()
```

شیء Table والد برای یک cell را بازمی‌گرداند. فقط خواندنی [ITable](../../com.aspose.slides/itable).

**بازگشت:**
[ITable](../../com.aspose.slides/itable)
### isMergedCell() {#isMergedCell--}
```
public abstract boolean isMergedCell()
```

در صورت ادغام cell با هر cell تنظیم‌شده true و در غیر این صورت false بازمی‌گرداند. فقط خواندنی boolean.

**بازگشت:**
boolean
### getCellFormat() {#getCellFormat--}
```
public abstract ICellFormat getCellFormat()
```

شیء CellFormat که شامل ویژگی‌های قالب‌بندی برای این cell است را بازمی‌گرداند. فقط خواندنی [ICellFormat](../../com.aspose.slides/icellformat).

**بازگشت:**
[ICellFormat](../../com.aspose.slides/icellformat)
### splitByColSpan(int index) {#splitByColSpan-int-}
```
public abstract void splitByColSpan(int index)
```

cell را به دو cell بر اساس اندیس ستون تقسیم می‌کند.

**پارامترها:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | اندیس ستون. |
### splitByRowSpan(int index) {#splitByRowSpan-int-}
```
public abstract void splitByRowSpan(int index)
```

cell را به دو cell بر اساس اندیس ردیف تقسیم می‌کند.

**پارامترها:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | اندیس ردیف. |
### splitByHeight(double height) {#splitByHeight-double-}
```
public abstract void splitByHeight(double height)
```

cell را بر اساس ارتفاع تقسیم می‌کند.

**پارامترها:**
| Parameter | Type | Description |
| --- | --- | --- |
| height | double | ارتفاع یک ردیف. |
### splitByWidth(double width) {#splitByWidth-double-}
```
public abstract void splitByWidth(double width)
```

cell را بر اساس عرض تقسیم می‌کند.

**پارامترها:**
| Parameter | Type | Description |
| --- | --- | --- |
| width | double | عرض یک ستون. |