---
title: Cell
second_title: مرجع API لـ Aspose.Slides للغة Java
description: يمثل خلية من جدول.
type: docs
url: /ar/com.aspose.slides/cell/
---
**الوراثة:**
java.lang.Object

**جميع الواجهات المنفذة:**
com.aspose.slides.IDOMObject, [com.aspose.slides.ICell](../../com.aspose.slides/icell)
```
public class Cell implements IDOMObject, ICell
```

يمثل خلية من جدول.
## الأساليب

| الطريقة | الوصف |
| --- | --- |
| [getOffsetX()](#getOffsetX--) | إرجاع المسافة من الجانب الأيسر للجدول إلى الجانب الأيسر للخلية. |
| [getOffsetY()](#getOffsetY--) | إرجاع المسافة من الجانب العلوي للجدول إلى الجانب العلوي للخلية. |
| [getFirstRowIndex()](#getFirstRowIndex--) | إرجاع فهرس الصف الأول الذي تغطيه الخلية. |
| [getFirstColumnIndex()](#getFirstColumnIndex--) | إرجاع فهرس العمود الأول الذي يغطيه الخلية. |
| [getWidth()](#getWidth--) | إرجاع عرض الخلية. |
| [getHeight()](#getHeight--) | إرجاع ارتفاع الخلية. |
| [getMinimalHeight()](#getMinimalHeight--) | إرجاع الحد الأدنى لارتفاع الخلية. |
| [getMarginLeft()](#getMarginLeft--) | إرجاع أو تعيين الهامش الأيسر في TextFrame. |
| [setMarginLeft(double value)](#setMarginLeft-double-) | إرجاع أو تعيين الهامش الأيسر في TextFrame. |
| [getMarginRight()](#getMarginRight--) | إرجاع أو تعيين الهامش الأيمن في TextFrame. |
| [setMarginRight(double value)](#setMarginRight-double-) | إرجاع أو تعيين الهامش الأيمن في TextFrame. |
| [getMarginTop()](#getMarginTop--) | إرجاع أو تعيين الهامش العلوي في TextFrame. |
| [setMarginTop(double value)](#setMarginTop-double-) | إرجاع أو تعيين الهامش العلوي في TextFrame. |
| [getMarginBottom()](#getMarginBottom--) | إرجاع أو تعيين الهامش السفلي في TextFrame. |
| [setMarginBottom(double value)](#setMarginBottom-double-) | إرجاع أو تعيين الهامش السفلي في TextFrame. |
| [getTextVerticalType()](#getTextVerticalType--) | إرجاع أو تعيين نوع النص العمودي. |
| [setTextVerticalType(byte value)](#setTextVerticalType-byte-) | إرجاع أو تعيين نوع النص العمودي. |
| [getTextAnchorType()](#getTextAnchorType--) | إرجاع أو تعيين نوع مرساة النص. |
| [setTextAnchorType(byte value)](#setTextAnchorType-byte-) | إرجاع أو تعيين نوع مرساة النص. |
| [getAnchorCenter()](#getAnchorCenter--) | تحديد ما إذا كان مربع النص مركَّزًا داخل الخلية. |
| [setAnchorCenter(boolean value)](#setAnchorCenter-boolean-) | تحديد ما إذا كان مربع النص مركَّزًا داخل الخلية. |
| [getFirstRow()](#getFirstRow--) | الحصول على الصف الأول للخلية. |
| [getFirstColumn()](#getFirstColumn--) | الحصول على العمود الأول للخلية. |
| [getColSpan()](#getColSpan--) | إرجاع عدد أعمدة الشبكة في شبكة الجدول الأصلية التي يجب أن تمتد عبرها الخلية الحالية. |
| [getRowSpan()](#getRowSpan--) | إرجاع عدد الصفوف التي تمتد عبرها الخلية المدمجة. |
| [getTextFrame()](#getTextFrame--) | إرجاع إطار النص للخلية. |
| [getTable()](#getTable--) | إرجاع كائن Table الأصل للخلية. |
| [isMergedCell()](#isMergedCell--) | إرجاع true إذا كانت الخلية مدمجة مع أي خلية مُعدلة، وإلا false. |
| [getCellFormat()](#getCellFormat--) | إرجاع كائن CellFormat الذي يحتوي على خصائص التنسيق لهذه الخلية. |
| [splitByColSpan(int index)](#splitByColSpan-int-) | تقسيم الخلية إلى خلين بحسب فهرس العمود. |
| [splitByRowSpan(int index)](#splitByRowSpan-int-) | تقسيم الخلية إلى خلين بحسب فهرس الصف. |
| [splitByHeight(double height)](#splitByHeight-double-) | تقسيم الخلية بحسب الارتفاع. |
| [splitByWidth(double width)](#splitByWidth-double-) | تقسيم الخلية بحسب العرض. |
| [getSlide()](#getSlide--) | إرجاع الشريحة الأصل للخلية. |
| [getPresentation()](#getPresentation--) | إرجاع العرض التقديمي الأصل للخلية. |
| [getParent_Immediate()](#getParent-Immediate--) |  |

### getOffsetX() {#getOffsetX--}
```
public final double getOffsetX()
```

إرجاع المسافة من الجانب الأيسر للجدول إلى الجانب الأيسر للخلية. قابل للقراءة فقط double.

**إرجاع:**
double

### getOffsetY() {#getOffsetY--}
```
public final double getOffsetY()
```

إرجاع المسافة من الجانب العلوي للجدول إلى الجانب العلوي للخلية. قابل للقراءة فقط double.

**إرجاع:**
double

### getFirstRowIndex() {#getFirstRowIndex--}
```
public final int getFirstRowIndex()
```

إرجاع فهرس الصف الأول الذي تغطيه الخلية. قابل للقراءة فقط int.

**إرجاع:**
int

### getFirstColumnIndex() {#getFirstColumnIndex--}
```
public final int getFirstColumnIndex()
```

إرجاع فهرس العمود الأول الذي يغطيه الخلية. قابل للقراءة فقط int.

**إرجاع:**
int

### getWidth() {#getWidth--}
```
public final double getWidth()
```

إرجاع عرض الخلية. قابل للقراءة فقط double.

**إرجاع:**
double

### getHeight() {#getHeight--}
```
public final double getHeight()
```

إرجاع ارتفاع الخلية. قابل للقراءة فقط double.

**إرجاع:**
double

### getMinimalHeight() {#getMinimalHeight--}
```
public final double getMinimalHeight()
```

إرجاع الحد الأدنى لارتفاع الخلية. هذا هو مجموع الحد الأدنى لارتفاع جميع الصفوف التي تغطيها الخلية. قابل للقراءة فقط double.

**إرجاع:**
double

### getMarginLeft() {#getMarginLeft--}
```
public final double getMarginLeft()
```

إرجاع أو تعيين الهامش الأيسر في TextFrame. قابل للقراءة والكتابة double.

**إرجاع:**
double

### setMarginLeft(double value) {#setMarginLeft-double-}
```
public final void setMarginLeft(double value)
```

إرجاع أو تعيين الهامش الأيسر في TextFrame. قابل للقراءة والكتابة double.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | double |  |

### getMarginRight() {#getMarginRight--}
```
public final double getMarginRight()
```

إرجاع أو تعيين الهامش الأيمن في TextFrame. قابل للقراءة والكتابة double.

**إرجاع:**
double

### setMarginRight(double value) {#setMarginRight-double-}
```
public final void setMarginRight(double value)
```

إرجاع أو تعيين الهامش الأيمن في TextFrame. قابل للقراءة والكتابة double.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | double |  |

### getMarginTop() {#getMarginTop--}
```
public final double getMarginTop()
```

إرجاع أو تعيين الهامش العلوي في TextFrame. قابل للقراءة والكتابة double.

**إرجاع:**
double

### setMarginTop(double value) {#setMarginTop-double-}
```
public final void setMarginTop(double value)
```

إرجاع أو تعيين الهامش العلوي في TextFrame. قابل للقراءة والكتابة double.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | double |  |

### getMarginBottom() {#getMarginBottom--}
```
public final double getMarginBottom()
```

إرجاع أو تعيين الهامش السفلي في TextFrame. قابل للقراءة والكتابة double.

**إرجاع:**
double

### setMarginBottom(double value) {#setMarginBottom-double-}
```
public final void setMarginBottom(double value)
```

إرجاع أو تعيين الهامش السفلي في TextFrame. قابل للقراءة والكتابة double.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | double |  |

### getTextVerticalType() {#getTextVerticalType--}
```
public final byte getTextVerticalType()
```

إرجاع أو تعيين نوع النص العمودي. قابل للقراءة والكتابة [TextVerticalType](../../com.aspose.slides/textverticaltype).

**إرجاع:**
byte

### setTextVerticalType(byte value) {#setTextVerticalType-byte-}
```
public final void setTextVerticalType(byte value)
```

إرجاع أو تعيين نوع النص العمودي. قابل للقراءة والكتابة [TextVerticalType](../../com.aspose.slides/textverticaltype).

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | byte |  |

### getTextAnchorType() {#getTextAnchorType--}
```
public final byte getTextAnchorType()
```

إرجاع أو تعيين نوع مرساة النص. قابل للقراءة والكتابة [TextAnchorType](../../com.aspose.slides/textanchortype).

**إرجاع:**
byte

### setTextAnchorType(byte value) {#setTextAnchorType-byte-}
```
public final void setTextAnchorType(byte value)
```

إرجاع أو تعيين نوع مرساة النص. قابل للقراءة والكتابة [TextAnchorType](../../com.aspose.slides/textanchortype).

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | byte |  |

### getAnchorCenter() {#getAnchorCenter--}
```
public final boolean getAnchorCenter()
```

تحديد ما إذا كان مربع النص مركَّزًا داخل الخلية. قابل للقراءة والكتابة boolean.

**إرجاع:**
boolean

### setAnchorCenter(boolean value) {#setAnchorCenter-boolean-}
```
public final void setAnchorCenter(boolean value)
```

تحديد ما إذا كان مربع النص مركَّزًا داخل الخلية. قابل للقراءة والكتابة boolean.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | boolean |  |

### getFirstRow() {#getFirstRow--}
```
public final IRow getFirstRow()
```

الحصول على الصف الأول للخلية. قابل للقراءة فقط [IRow](../../com.aspose.slides/irow).

**إرجاع:**
[IRow](../../com.aspose.slides/irow)

### getFirstColumn() {#getFirstColumn--}
```
public final IColumn getFirstColumn()
```

الحصول على العمود الأول للخلية. قابل للقراءة فقط [IColumn](../../com.aspose.slides/icolumn).

**إرجاع:**
[IColumn](../../com.aspose.slides/icolumn)

### getColSpan() {#getColSpan--}
```
public final int getColSpan()
```

إرجاع عدد أعمدة الشبكة في شبكة الجدول الأصلية التي يجب أن تمتد عبرها الخلية الحالية. تسمح هذه الخاصية للخلية بأن تبدو مدمجة، حيث تمتد عبر حدود خلايا أخرى في الجدول. قابل للقراءة فقط int.

**إرجاع:**
int

### getRowSpan() {#getRowSpan--}
```
public final int getRowSpan()
```

إرجاع عدد الصفوف التي تمتد عبرها الخلية المدمجة. يستخدم هذا بالتزامن مع سمة vMerge في خلايا أخرى لتحديد الخلية البداية للدمج الأفقي. قابل للقراءة فقط int.

**إرجاع:**
int

### getTextFrame() {#getTextFrame--}
```
public final ITextFrame getTextFrame()
```

إرجاع إطار النص للخلية. قابل للقراءة فقط [ITextFrame](../../com.aspose.slides/itextframe).

**إرجاع:**
[ITextFrame](../../com.aspose.slides/itextframe)

### getTable() {#getTable--}
```
public final ITable getTable()
```

إرجاع كائن Table الأصل للخلية. قابل للقراءة فقط [ITable](../../com.aspose.slides/itable).

**إرجاع:**
[ITable](../../com.aspose.slides/itable)

### isMergedCell() {#isMergedCell--}
```
public final boolean isMergedCell()
```

إرجاع true إذا كانت الخلية مدمجة مع أي خلية مُعدلة، وإلا false. قابل للقراءة فقط boolean.

**إرجاع:**
boolean

### getCellFormat() {#getCellFormat--}
```
public final ICellFormat getCellFormat()
```

إرجاع كائن CellFormat الذي يحتوي على خصائص التنسيق لهذه الخلية. قابل للقراءة فقط [ICellFormat](../../com.aspose.slides/icellformat).

**إرجاع:**
[ICellFormat](../../com.aspose.slides/icellformat)

### splitByColSpan(int index) {#splitByColSpan-int-}
```
public final void splitByColSpan(int index)
```

تقسيم الخلية إلى خلين بحسب فهرس العمود.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| index | int | فهرس العمود. |

### splitByRowSpan(int index) {#splitByRowSpan-int-}
```
public final void splitByRowSpan(int index)
```

تقسيم الخلية إلى خلين بحسب فهرس الصف.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| index | int | فهرس الصف. |

### splitByHeight(double height) {#splitByHeight-double-}
```
public final void splitByHeight(double height)
```

تقسيم الخلية بحسب الارتفاع.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| height | double | ارتفاع الصف. |

### splitByWidth(double width) {#splitByWidth-double-}
```
public final void splitByWidth(double width)
```

تقسيم الخلية بحسب العرض.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| width | double | عرض العمود. |

### getSlide() {#getSlide--}
```
public final IBaseSlide getSlide()
```

إرجاع الشريحة الأصل للخلية. قابل للقراءة فقط [IBaseSlide](../../com.aspose.slides/ibaseslide).

**إرجاع:**
[IBaseSlide](../../com.aspose.slides/ibaseslide)

### getPresentation() {#getPresentation--}
```
public final IPresentation getPresentation()
```

إرجاع العرض التقديمي الأصل للخلية. قابل للقراءة فقط [IPresentation](../../com.aspose.slides/ipresentation).

**إرجاع:**
[IPresentation](../../com.aspose.slides/ipresentation)

### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```

إرجاع كائن Parent_Immediate. قابل للقراءة فقط IDOMObject.

**إرجاع:**
com.aspose.slides.IDOMObject