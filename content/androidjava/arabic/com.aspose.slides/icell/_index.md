---
title: ICell
second_title: Aspose.Slides لنظام Android عبر مرجع API للغة Java
description: يمثل خلية في جدول.
type: docs
url: /ar/com.aspose.slides/icell/
---
**All Implemented Interfaces:**
[com.aspose.slides.ISlideComponent](../../com.aspose.slides/islidecomponent)
```
public interface ICell extends ISlideComponent
```

يمثل خلية في جدول.
## الطرق

| الطريقة | الوصف |
| --- | --- |
| [getOffsetX()](#getOffsetX--) | يرجع مسافة من الجانب الأيسر للجدول إلى الجانب الأيسر للخلية. |
| [getOffsetY()](#getOffsetY--) | يرجع مسافة من الجانب العلوي للجدول إلى الجانب العلوي للخلية. |
| [getFirstRowIndex()](#getFirstRowIndex--) | يرجع فهرس الصف الأول الذي تغطيه الخلية. |
| [getFirstColumnIndex()](#getFirstColumnIndex--) | يرجع فهرس العمود الأول الذي تغطيه الخلية. |
| [getWidth()](#getWidth--) | يرجع عرض الخلية. |
| [getHeight()](#getHeight--) | يرجع ارتفاع الخلية. |
| [getMinimalHeight()](#getMinimalHeight--) | يرجع الحد الأدنى لارتفاع الخلية. |
| [getMarginLeft()](#getMarginLeft--) | يرجع أو يضع الهامش الأيسر في TextFrame. |
| [setMarginLeft(double value)](#setMarginLeft-double-) | يرجع أو يضع الهامش الأيسر في TextFrame. |
| [getMarginRight()](#getMarginRight--) | يرجع أو يضع الهامش الأيمن في TextFrame. |
| [setMarginRight(double value)](#setMarginRight-double-) | يرجع أو يضع الهامش الأيمن في TextFrame. |
| [getMarginTop()](#getMarginTop--) | يرجع أو يضع الهامش العلوي في TextFrame. |
| [setMarginTop(double value)](#setMarginTop-double-) | يرجع أو يضع الهامش العلوي في TextFrame. |
| [getMarginBottom()](#getMarginBottom--) | يرجع أو يضع الهامش السفلي في TextFrame. |
| [setMarginBottom(double value)](#setMarginBottom-double-) | يرجع أو يضع الهامش السفلي في TextFrame. |
| [getTextVerticalType()](#getTextVerticalType--) | يرجع أو يضع نوع النص العمودي. |
| [setTextVerticalType(byte value)](#setTextVerticalType-byte-) | يرجع أو يضع نوع النص العمودي. |
| [getTextAnchorType()](#getTextAnchorType--) | يرجع أو يضع نوع مرساة النص. |
| [setTextAnchorType(byte value)](#setTextAnchorType-byte-) | يرجع أو يضع نوع مرساة النص. |
| [getAnchorCenter()](#getAnchorCenter--) | يحدد ما إذا كان مربع النص مركَّزًا داخل الخلية أم لا. |
| [setAnchorCenter(boolean value)](#setAnchorCenter-boolean-) | يحدد ما إذا كان مربع النص مركَّزًا داخل الخلية أم لا. |
| [getFirstColumn()](#getFirstColumn--) | يحصل على العمود الأول للخلية. |
| [getFirstRow()](#getFirstRow--) | يحصل على الصف الأول للخلية. |
| [getColSpan()](#getColSpan--) | يرجع عدد أعمدة الشبكة في شبكة الجدول الأصل الذي يجب أن تغطيه الخلية الحالية. |
| [getRowSpan()](#getRowSpan--) | يرجع عدد الصفوف التي تغطيها الخلية المدمجة. |
| [getTextFrame()](#getTextFrame--) | يرجع إطار النص للخلية. |
| [getTable()](#getTable--) | يرجع كائن Table الأب للخلية. |
| [isMergedCell()](#isMergedCell--) | يرجع true إذا كانت الخلية مدمجة مع أي خلية معدلة، وإلا false. |
| [getCellFormat()](#getCellFormat--) | يرجع كائن CellFormat الذي يحتوي على خصائص التنسيق لهذه الخلية. |
| [splitByColSpan(int index)](#splitByColSpan-int-) | يقسم الخلية إلى خليتين وفقًا لفهرس العمود. |
| [splitByRowSpan(int index)](#splitByRowSpan-int-) | يقسم الخلية إلى خليتين وفقًا لفهرس الصف. |
| [splitByHeight(double height)](#splitByHeight-double-) | يقسم الخلية حسب الارتفاع. |
| [splitByWidth(double width)](#splitByWidth-double-) | يقسم الخلية حسب العرض. |

### getOffsetX() {#getOffsetX--}
```
public abstract double getOffsetX()
```


يرجع مسافة من الجانب الأيسر للجدول إلى الجانب الأيسر للخلية. للقراءة فقط double.

**الإرجاع:**
double

### getOffsetY() {#getOffsetY--}
```
public abstract double getOffsetY()
```


يرجع مسافة من الجانب العلوي للجدول إلى الجانب العلوي للخلية. للقراءة فقط double.

**الإرجاع:**
double

### getFirstRowIndex() {#getFirstRowIndex--}
```
public abstract int getFirstRowIndex()
```


يرجع فهرس الصف الأول الذي تغطيه الخلية. للقراءة فقط int.

**الإرجاع:**
int

### getFirstColumnIndex() {#getFirstColumnIndex--}
```
public abstract int getFirstColumnIndex()
```


يرجع فهرس العمود الأول الذي تغطيه الخلية. للقراءة فقط int.

**الإرجاع:**
int

### getWidth() {#getWidth--}
```
public abstract double getWidth()
```


يرجع عرض الخلية. للقراءة فقط double.

**الإرجاع:**
double

### getHeight() {#getHeight--}
```
public abstract double getHeight()
```


يرجع ارتفاع الخلية. للقراءة فقط double.

**الإرجاع:**
double

### getMinimalHeight() {#getMinimalHeight--}
```
public abstract double getMinimalHeight()
```


يرجع الحد الأدنى لارتفاع الخلية. هذا هو مجموع الارتفاعات الدنيا لجميع الصفوف التي تغطيها الخلية. للقراءة فقط double.

**الإرجاع:**
double

### getMarginLeft() {#getMarginLeft--}
```
public abstract double getMarginLeft()
```


يرجع أو يضع الهامش الأيسر في TextFrame. للقراءة والكتابة double.

**الإرجاع:**
double

### setMarginLeft(double value) {#setMarginLeft-double-}
```
public abstract void setMarginLeft(double value)
```


يرجع أو يضع الهامش الأيسر في TextFrame. للقراءة والكتابة double.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | double |  |

### getMarginRight() {#getMarginRight--}
```
public abstract double getMarginRight()
```


يرجع أو يضع الهامش الأيمن في TextFrame. للقراءة والكتابة double.

**الإرجاع:**
double

### setMarginRight(double value) {#setMarginRight-double-}
```
public abstract void setMarginRight(double value)
```


يرجع أو يضع الهامش الأيمن في TextFrame. للقراءة والكتابة double.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | double |  |

### getMarginTop() {#getMarginTop--}
```
public abstract double getMarginTop()
```


يرجع أو يضع الهامش العلوي في TextFrame. للقراءة والكتابة double.

**الإرجاع:**
double

### setMarginTop(double value) {#setMarginTop-double-}
```
public abstract void setMarginTop(double value)
```


يرجع أو يضع الهامش العلوي في TextFrame. للقراءة والكتابة double.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | double |  |

### getMarginBottom() {#getMarginBottom--}
```
public abstract double getMarginBottom()
```


يرجع أو يضع الهامش السفلي في TextFrame. للقراءة والكتابة double.

**الإرجاع:**
double

### setMarginBottom(double value) {#setMarginBottom-double-}
```
public abstract void setMarginBottom(double value)
```


يرجع أو يضع الهامش السفلي في TextFrame. للقراءة والكتابة double.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | double |  |

### getTextVerticalType() {#getTextVerticalType--}
```
public abstract byte getTextVerticalType()
```


يرجع أو يضع نوع النص العمودي. للقراءة والكتابة [TextVerticalType](../../com.aspose.slides/textverticaltype).

**الإرجاع:**
byte

### setTextVerticalType(byte value) {#setTextVerticalType-byte-}
```
public abstract void setTextVerticalType(byte value)
```


يرجع أو يضع نوع النص العمودي. للقراءة والكتابة [TextVerticalType](../../com.aspose.slides/textverticaltype).

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | byte |  |

### getTextAnchorType() {#getTextAnchorType--}
```
public abstract byte getTextAnchorType()
```


يرجع أو يضع نوع مرساة النص. للقراءة والكتابة [TextAnchorType](../../com.aspose.slides/textanchortype).

**الإرجاع:**
byte

### setTextAnchorType(byte value) {#setTextAnchorType-byte-}
```
public abstract void setTextAnchorType(byte value)
```


يرجع أو يضع نوع مرساة النص. للقراءة والكتابة [TextAnchorType](../../com.aspose.slides/textanchortype).

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | byte |  |

### getAnchorCenter() {#getAnchorCenter--}
```
public abstract boolean getAnchorCenter()
```


يحدد ما إذا كان مربع النص مركَّزًا داخل الخلية أم لا. للقراءة والكتابة boolean.

**الإرجاع:**
boolean

### setAnchorCenter(boolean value) {#setAnchorCenter-boolean-}
```
public abstract void setAnchorCenter(boolean value)
```


يحدد ما إذا كان مربع النص مركَّزًا داخل الخلية أم لا. للقراءة والكتابة boolean.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | boolean |  |

### getFirstColumn() {#getFirstColumn--}
```
public abstract IColumn getFirstColumn()
```


يحصل على العمود الأول للخلية. للقراءة فقط [IColumn](../../com.aspose.slides/icolumn).

**الإرجاع:**
[IColumn](../../com.aspose.slides/icolumn)

### getFirstRow() {#getFirstRow--}
```
public abstract IRow getFirstRow()
```


يحصل على الصف الأول للخلية. للقراءة فقط [IRow](../../com.aspose.slides/irow).

**الإرجاع:**
[IRow](../../com.aspose.slides/irow)

### getColSpan() {#getColSpan--}
```
public abstract int getColSpan()
```


يرجع عدد أعمدة الشبكة في شبكة جدول الجدول الأصل الذي يجب أن تغطيه الخلية الحالية. تمكن هذه الخاصية الخلايا من الظهور كأنها مدمجة، حيث تمتد عبر حدود الأعمدة العمودية للخلايا الأخرى في الجدول. للقراءة فقط int.

**الإرجاع:**
int

### getRowSpan() {#getRowSpan--}
```
public abstract int getRowSpan()
```


يرجع عدد الصفوف التي تغطيها الخلية المدمجة. يُستخدم هذا بالاشتراك مع سمة vMerge على خلايا أخرى لتحديد خلية البداية للدمج الأفقي. للقراءة فقط int.

**الإرجاع:**
int

### getTextFrame() {#getTextFrame--}
```
public abstract ITextFrame getTextFrame()
```


يرجع إطار النص للخلية. للقراءة فقط [ITextFrame](../../com.aspose.slides/itextframe).

**الإرجاع:**
[ITextFrame](../../com.aspose.slides/itextframe)

### getTable() {#getTable--}
```
public abstract ITable getTable()
```


يرجع كائن Table الأب للخلية. للقراءة فقط [ITable](../../com.aspose.slides/itable).

**الإرجاع:**
[ITable](../../com.aspose.slides/itable)

### isMergedCell() {#isMergedCell--}
```
public abstract boolean isMergedCell()
```


يرجع true إذا كانت الخلية مدمجة مع أي خلية معدلة، وإلا false. للقراءة فقط boolean.

**الإرجاع:**
boolean

### getCellFormat() {#getCellFormat--}
```
public abstract ICellFormat getCellFormat()
```


يرجع كائن CellFormat الذي يحتوي على خصائص التنسيق لهذه الخلية. للقراءة فقط [ICellFormat](../../com.aspose.slides/icellformat).

**الإرجاع:**
[ICellFormat](../../com.aspose.slides/icellformat)

### splitByColSpan(int index) {#splitByColSpan-int-}
```
public abstract void splitByColSpan(int index)
```


يقسم الخلية إلى خليتين وفقًا لفهرس العمود.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| index | int | فهرس العمود. |

### splitByRowSpan(int index) {#splitByRowSpan-int-}
```
public abstract void splitByRowSpan(int index)
```


يقسم الخلية إلى خليتين وفقًا لفهرس الصف.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| index | int | فهرس الصف. |

### splitByHeight(double height) {#splitByHeight-double-}
```
public abstract void splitByHeight(double height)
```


يقسم الخلية حسب الارتفاع.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| height | double | ارتفاع الصف. |

### splitByWidth(double width) {#splitByWidth-double-}
```
public abstract void splitByWidth(double width)
```


يقسم الخلية حسب العرض.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| width | double | عرض العمود. |