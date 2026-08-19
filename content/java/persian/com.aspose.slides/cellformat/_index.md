---
title: CellFormat
second_title: مرجع API Aspose.Slides برای Java
description: قالب یک سلول جدول را نمایش می‌دهد.
type: docs
url: /fa/com.aspose.slides/cellformat/
---
**ارث‌بری:**
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject)

**تمام اینترفیس‌های پیاده‌سازی‌شده:**
[com.aspose.slides.ICellFormat](../../com.aspose.slides/icellformat)
```
public final class CellFormat extends PVIObject implements ICellFormat
```

قالب یک سلول جدول را نمایش می‌دهد.
## متدها

| متد | توضیح |
| --- | --- |
| [getVersion()](#getVersion--) |  |
| [getFillFormat()](#getFillFormat--) | یک شیء ویژگی‌های پر کردن سلول را برمی‌گرداند. |
| [getBorderLeft()](#getBorderLeft--) | یک شیء ویژگی‌های خط حاشیهٔ چپ را برمی‌گرداند. |
| [getBorderTop()](#getBorderTop--) | یک شیء ویژگی‌های خط حاشیهٔ بالا را برمی‌گرداند. |
| [getBorderRight()](#getBorderRight--) | یک شیء ویژگی‌های خط حاشیهٔ راست را برمی‌گرداند. |
| [getBorderBottom()](#getBorderBottom--) | یک شیء ویژگی‌های خط حاشیهٔ پایین را برمی‌گرداند. |
| [getBorderDiagonalDown()](#getBorderDiagonalDown--) | یک شیء ویژگی‌های خط مورب از بالا-چپ به پایین-راست را برمی‌گرداند. |
| [getBorderDiagonalUp()](#getBorderDiagonalUp--) | یک شیء ویژگی‌های خط مورب از پایین-چپ به بالا-راست را برمی‌گرداند. |
| [getEffective()](#getEffective--) | ویژگی‌های فرمت‌بندی موثر سلول جدول را با ارث‌بری و سبک‌های جدول اعمال‌شده دریافت می‌کند. |
| [getTransparency()](#getTransparency--) | شفافیت رنگ پر کردن را دریافت یا تنظیم می‌کند. |
| [setTransparency(float value)](#setTransparency-float-) | شفافیت رنگ پر کردن را دریافت یا تنظیم می‌کند. |
### getVersion() {#getVersion--}
```
public long getVersion()
```

Version. فقط-خواندنی long.

**Returns:**
long
### getFillFormat() {#getFillFormat--}
```
public final IFillFormat getFillFormat()
```

یک شیء ویژگی‌های پر کردن سلول را برمی‌گرداند. فقط-خواندنی [IFillFormat](../../com.aspose.slides/ifillformat).

**Returns:**
[IFillFormat](../../com.aspose.slides/ifillformat)
### getBorderLeft() {#getBorderLeft--}
```
public final ILineFormat getBorderLeft()
```

یک شیء ویژگی‌های خط حاشیهٔ چپ را برمی‌گرداند. فقط-خواندنی [ILineFormat](../../com.aspose.slides/ilineformat).

**Returns:**
[ILineFormat](../../com.aspose.slides/ilineformat)
### getBorderTop() {#getBorderTop--}
```
public final ILineFormat getBorderTop()
```

یک شیء ویژگی‌های خط حاشیهٔ بالا را برمی‌گرداند. فقط-خواندنی [ILineFormat](../../com.aspose.slides/ilineformat).

**Returns:**
[ILineFormat](../../com.aspose.slides/ilineformat)
### getBorderRight() {#getBorderRight--}
```
public final ILineFormat getBorderRight()
```

یک شیء ویژگی‌های خط حاشیهٔ راست را برمی‌گرداند. فقط-خواندنی [ILineFormat](../../com.aspose.slides/ilineformat).

**Returns:**
[ILineFormat](../../com.aspose.slides/ilineformat)
### getBorderBottom() {#getBorderBottom--}
```
public final ILineFormat getBorderBottom()
```

یک شیء ویژگی‌های خط حاشیهٔ پایین را برمی‌گرداند. فقط-خواندنی [ILineFormat](../../com.aspose.slides/ilineformat).

**Returns:**
[ILineFormat](../../com.aspose.slides/ilineformat)
### getBorderDiagonalDown() {#getBorderDiagonalDown--}
```
public final ILineFormat getBorderDiagonalDown()
```

یک شیء ویژگی‌های خط مورب از بالا-چپ به پایین-راست را برمی‌گرداند. فقط-خواندنی [ILineFormat](../../com.aspose.slides/ilineformat).

**Returns:**
[ILineFormat](../../com.aspose.slides/ilineformat)
### getBorderDiagonalUp() {#getBorderDiagonalUp--}
```
public final ILineFormat getBorderDiagonalUp()
```

یک شیء ویژگی‌های خط مورب از پایین-چپ به بالا-راست را برمی‌گرداند. فقط-خواندنی [ILineFormat](../../com.aspose.slides/ilineformat).

**Returns:**
[ILineFormat](../../com.aspose.slides/ilineformat)
### getEffective() {#getEffective--}
```
public final ICellFormatEffectiveData getEffective()
```

ویژگی‌های فرمت‌بندی موثر سلول جدول را با ارث‌بری و سبک‌های جدول اعمال‌شده دریافت می‌کند.

--------------------

> ```
> This example demonstrates getting effective fill format for different table logic parts.
>  Please note that cell formatting always has higher priority than row formatting, row - higher than column, column - higher that whole table.
>  So finally CellFormatEffectiveData properties always used to draw the table. The following code is just an example of API.
>  
>  Presentation pres = new Presentation(@"MyPresentation.pptx");
>  try
>  {
>      ITable tbl = (ITable) pres.getSlides().get_Item(0).getShapes().get_Item(0);
>      IFillFormatEffectiveData tableFillFormatEffective = tbl.getTableFormat().getEffective().getFillFormat();
>      IFillFormatEffectiveData rowFillFormatEffective = tbl.getRows().get_Item(0).RowFormat.GetEffective().getFillFormat();
>      IFillFormatEffectiveData columnFillFormatEffective = tbl.getColumns().get_Item(0).getColumnFormat().getEffective().getFillFormat();
>      IFillFormatEffectiveData cellFillFormatEffective = tbl.get_Item(0, 0).getCellFormat().getEffective().getFillFormat();
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Returns:**
[ICellFormatEffectiveData](../../com.aspose.slides/icellformateffectivedata) - A [ICellFormatEffectiveData](../../com.aspose.slides/icellformateffectivedata).
### getTransparency() {#getTransparency--}
```
public final float getTransparency()
```

شفافیت رنگ پر کردن را دریافت یا تنظیم می‌کند. قابل-خواندن/نوشتن  float .

**Returns:**
float
### setTransparency(float value) {#setTransparency-float-}
```
public final void setTransparency(float value)
```

شفافیت رنگ پر کردن را دریافت یا تنظیم می‌کند. قابل-خواندن/نوشتن  float .

**Parameters:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | float |  |