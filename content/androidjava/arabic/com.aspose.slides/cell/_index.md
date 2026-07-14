---
title: Cell
second_title: مرجع Aspose.Slides لنظام Android عبر Java API
description: يمثل خلية في جدول.
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

يمثل خلية في جدول.

## الطرق

| الطريقة | الوصف |
| --- | --- |
| [getOffsetX()](#getOffsetX--) | يعيد مسافة من الجانب الأيسر للجدول إلى الجانب الأيسر للخلية. |
| [getOffsetY()](#getOffsetY--) | يعيد مسافة من الجانب العلوي للجدول إلى الجانب العلوي للخلية. |
| [getFirstRowIndex()](#getFirstRowIndex--) | يعيد فهرس الصف الأول الذي تغطيه الخلية. |
| [getFirstColumnIndex()](#getFirstColumnIndex--) | يعيد فهرس العمود الأول الذي تغطيه الخلية. |
| [getWidth()](#getWidth--) | يعيد عرض الخلية. |
| [getHeight()](#getHeight--) | يعيد ارتفاع الخلية. |
| [getMinimalHeight()](#getMinimalHeight--) | يعيد الحد الأدنى للارتفاع للخلية. |
| [getMarginLeft()](#getMarginLeft--) | يعيد أو يضبط الهامش الأيسر في TextFrame. |
| [setMarginLeft(double value)](#setMarginLeft-double-) | يعيد أو يضبط الهامش الأيسر في TextFrame. |
| [getMarginRight()](#getMarginRight--) | يعيد أو يضبط الهامش الأيمن في TextFrame. |
| [setMarginRight(double value)](#setMarginRight-double-) | يعيد أو يضبط الهامش الأيمن في TextFrame. |
| [getMarginTop()](#getMarginTop--) | يعيد أو يضبط الهامش العلوي في TextFrame. |
| [setMarginTop(double value)](#setMarginTop-double-) | يعيد أو يضبط الهامش العلوي في TextFrame. |
| [getMarginBottom()](#getMarginBottom--) | يعيد أو يضبط الهامش السفلي في TextFrame. |
| [setMarginBottom(double value)](#setMarginBottom-double-) | يعيد أو يضبط الهامش السفلي في TextFrame. |
| [getTextVerticalType()](#getTextVerticalType--) | يعيد أو يضبط نوع النص العمودي. |
| [setTextVerticalType(byte value)](#setTextVerticalType-byte-) | يعيد أو يضبط نوع النص العمودي. |
| [getTextAnchorType()](#getTextAnchorType--) | يعيد أو يضبط نوع ‎anchor‎ للنص. |
| [setTextAnchorType(byte value)](#setTextAnchorType-byte-) | يعيد أو يضبط نوع ‎anchor‎ للنص. |
| [getAnchorCenter()](#getAnchorCenter--) | يحدد ما إذا كان صندوق النص مُركزاً داخل الخلية أم لا. |
| [setAnchorCenter(boolean value)](#setAnchorCenter-boolean-) | يحدد ما إذا كان صندوق النص مُركزاً داخل الخلية أم لا. |
| [getFirstRow()](#getFirstRow--) | يحصل على الصف الأول للخلية. |
| [getFirstColumn()](#getFirstColumn--) | يحصل على العمود الأول للخلية. |
| [getColSpan()](#getColSpan--) | يعيد عدد أعمدة الشبكة في جدول الجدول الأب التي ينبغي أن تمتد عبرها الخلية الحالية. |
| [getRowSpan()](#getRowSpan--) | يعيد عدد الصفوف التي تمتد عبرها الخلية المدمجة. |
| [getTextFrame()](#getTextFrame--) | يعيد إطار النص للخلية. |
| [getTable()](#getTable--) | يعيد كائن Table الأب للخلية. |
| [isMergedCell()](#isMergedCell--) | يعيد true إذا كانت الخلية مدمجة مع أي خلية مُعدلة، وإلا false. |
| [getCellFormat()](#getCellFormat--) | يعيد كائن CellFormat الذي يحتوي على خصائص التنسيق لهذه الخلية. |
| [splitByColSpan(int index)](#splitByColSpan-int-) | يقسم الخلية إلى خليتين حسب فهرس العمود. |
| [splitByRowSpan(int index)](#splitByRowSpan-int-) | يقسم الخلية إلى خليتين حسب فهرس الصف. |
| [splitByHeight(double height)](#splitByHeight-double-) | يقسم الخلية حسب الارتفاع. |
| [splitByWidth(double width)](#splitByWidth-double-) | يقسم الخلية حسب العرض. |
| [getSlide()](#getSlide--) | يعيد الشريحة الأب للخلية. |
| [getPresentation()](#getPresentation--) | يعيد العرض التقديمي الأب للخلية. |
| [getParent_Immediate()](#getParent-Immediate--) |  |

### getOffsetX() {#getOffsetX--}
```
public final double getOffsetX()
```

يعيد مسافة من الجانب الأيسر للجدول إلى الجانب الأيسر للخلية. قيمة مزدوجة للقراءة فقط.

**الإرجاع:**  
double

### getOffsetY() {#getOffsetY--}
```
public final double getOffsetY()
```

يعيد مسافة من الجانب العلوي للجدول إلى الجانب العلوي للخلية. قيمة مزدوجة للقراءة فقط.

**الإرجاع:**  
double

### getFirstRowIndex() {#getFirstRowIndex--}
```
public final int getFirstRowIndex()
```

يعيد فهرس الصف الأول الذي تغطيه الخلية. قيمة صحيحة للقراءة فقط.

**الإرجاع:**  
int

### getFirstColumnIndex() {#getFirstColumnIndex--}
```
public final int getFirstColumnIndex()
```

يعيد فهرس العمود الأول الذي تغطيه الخلية. قيمة صحيحة للقراءة فقط.

**الإرجاع:**  
int

### getWidth() {#getWidth--}
```
public final double getWidth()
```

يعيد عرض الخلية. قيمة مزدوجة للقراءة فقط.

**الإرجاع:**  
double

### getHeight() {#getHeight--}
```
public final double getHeight()
```

يعيد ارتفاع الخلية. قيمة مزدوجة للقراءة فقط.

**الإرجاع:**  
double

### getMinimalHeight() {#getMinimalHeight--}
```
public final double getMinimalHeight()
```

يعيد الحد الأدنى لارتفاع الخلية. هذا هو مجموع الحدود الدنيا لارتفاع جميع الصفوف التي تغطيها الخلية. قيمة مزدوجة للقراءة فقط.

**الإرجاع:**  
double

### getMarginLeft() {#getMarginLeft--}
```
public final double getMarginLeft()
```

يعيد أو يضبط الهامش الأيسر في TextFrame. قيمة مزدوجة للقراءة والكتابة.

**الإرجاع:**  
double

### setMarginLeft(double value) {#setMarginLeft-double-}
```
public final void setMarginLeft(double value)
```

يعيد أو يضبط الهامش الأيسر في TextFrame. قيمة مزدوجة للقراءة والكتابة.

**المعلمات:**  
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| value | double |  |

### getMarginRight() {#getMarginRight--}
```
public final double getMarginRight()
```

يعيد أو يضبط الهامش الأيمن في TextFrame. قيمة مزدوجة للقراءة والكتابة.

**الإرجاع:**  
double

### setMarginRight(double value) {#setMarginRight-double-}
```
public final void setMarginRight(double value)
```

يعيد أو يضبط الهامش الأيمن في TextFrame. قيمة مزدوجة للقراءة والكتابة.

**المعلمات:**  
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| value | double |  |

### getMarginTop() {#getMarginTop--}
```
public final double getMarginTop()
```

يعيد أو يضبط الهامش العلوي في TextFrame. قيمة مزدوجة للقراءة والكتابة.

**الإرجاع:**  
double

### setMarginTop(double value) {#setMarginTop-double-}
```
public final void setMarginTop(double value)
```

يعيد أو يضبط الهامش العلوي في TextFrame. قيمة مزدوجة للقراءة والكتابة.

**المعلمات:**  
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| value | double |  |

### getMarginBottom() {#getMarginBottom--}
```
public final double getMarginBottom()
```

يعيد أو يضبط الهامش السفلي في TextFrame. قيمة مزدوجة للقراءة والكتابة.

**الإرجاع:**  
double

### setMarginBottom(double value) {#setMarginBottom-double-}
```
public final void setMarginBottom(double value)
```

يعيد أو يضبط الهامش السفلي في TextFrame. قيمة مزدوجة للقراءة والكتابة.

**المعلمات:**  
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| value | double |  |

### getTextVerticalType() {#getTextVerticalType--}
```
public final byte getTextVerticalType()
```

يعيد أو يضبط نوع النص العمودي. قيمة بايت للقراءة والكتابة [TextVerticalType](../../com.aspose.slides/textverticaltype).

**الإرجاع:**  
byte

### setTextVerticalType(byte value) {#setTextVerticalType-byte-}
```
public final void setTextVerticalType(byte value)
```

يعيد أو يضبط نوع النص العمودي. قيمة بايت للقراءة والكتابة [TextVerticalType](../../com.aspose.slides/textverticaltype).

**المعلمات:**  
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| value | byte |  |

### getTextAnchorType() {#getTextAnchorType--}
```
public final byte getTextAnchorType()
```

يعيد أو يضبط نوع ‎anchor‎ للنص. قيمة بايت للقراءة والكتابة [TextAnchorType](../../com.aspose.slides/textanchortype).

**الإرجاع:**  
byte

### setTextAnchorType(byte value) {#setTextAnchorType-byte-}
```
public final void setTextAnchorType(byte value)
```

يعيد أو يضبط نوع ‎anchor‎ للنص. قيمة بايت للقراءة والكتابة [TextAnchorType](../../com.aspose.slides/textanchortype).

**المعلمات:**  
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| value | byte |  |

### getAnchorCenter() {#getAnchorCenter--}
```
public final boolean getAnchorCenter()
```

يحدد ما إذا كان صندوق النص مُركزاً داخل الخلية أم لا. قيمة منطقية للقراءة والكتابة.

**الإرجاع:**  
boolean

### setAnchorCenter(boolean value) {#setAnchorCenter-boolean-}
```
public final void setAnchorCenter(boolean value)
```

يحدد ما إذا كان صندوق النص مُركزاً داخل الخلية أم لا. قيمة منطقية للقراءة والكتابة.

**المعلمات:**  
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| value | boolean |  |

### getFirstRow() {#getFirstRow--}
```
public final IRow getFirstRow()
```

يحصل على الصف الأول للخلية. قيمة [IRow](../../com.aspose.slides/irow) للقراءة فقط.

**الإرجاع:**  
[IRow](../../com.aspose.slides/irow)

### getFirstColumn() {#getFirstColumn--}
```
public final IColumn getFirstColumn()
```

يحصل على العمود الأول للخلية. قيمة [IColumn](../../com.aspose.slides/icolumn) للقراءة فقط.

**الإرجاع:**  
[IColumn](../../com.aspose.slides/icolumn)

### getColSpan() {#getColSpan--}
```
public final int getColSpan()
```

يعيد عدد أعمدة الشبكة في جدول الجدول الأب التي ينبغي أن تمتد عبرها الخلية الحالية. تسمح هذه الخاصية للخلية بمظهر مدمج عبر امتدادها على حدود خلايا أخرى في الجدول. قيمة صحيحة للقراءة فقط.

**الإرجاع:**  
int

### getRowSpan() {#getRowSpan--}
```
public final int getRowSpan()
```

يعيد عدد الصفوف التي تمتد عبرها الخلية المدمجة. يُستخدم هذا بالتزامن مع سمة vMerge على خلايا أخرى لتحديد الخلية البادئة للدمج الأفقي. قيمة صحيحة للقراءة فقط.

**الإرجاع:**  
int

### getTextFrame() {#getTextFrame--}
```
public final ITextFrame getTextFrame()
```

يعيد إطار النص للخلية. قيمة [ITextFrame](../../com.aspose.slides/itextframe) للقراءة فقط.

**الإرجاع:**  
[ITextFrame](../../com.aspose.slides/itextframe)

### getTable() {#getTable--}
```
public final ITable getTable()
```

يعيد كائن Table الأب للخلية. قيمة [ITable](../../com.aspose.slides/itable) للقراءة فقط.

**الإرجاع:**  
[ITable](../../com.aspose.slides/itable)

### isMergedCell() {#isMergedCell--}
```
public final boolean isMergedCell()
```

يعيد true إذا كانت الخلية مدمجة مع أي خلية مُعدلة، وإلا false. قيمة منطقية للقراءة فقط.

**الإرجاع:**  
boolean

### getCellFormat() {#getCellFormat--}
```
public final ICellFormat getCellFormat()
```

يعيد كائن CellFormat الذي يحتوي على خصائص التنسيق لهذه الخلية. قيمة [ICellFormat](../../com.aspose.slides/icellformat) للقراءة فقط.

**الإرجاع:**  
[ICellFormat](../../com.aspose.slides/icellformat)

### splitByColSpan(int index) {#splitByColSpan-int-}
```
public final void splitByColSpan(int index)
```

يقسم الخلية إلى خليتين حسب فهرس العمود.

**المعلمات:**  
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| index | int | فهرس العمود. |

### splitByRowSpan(int index) {#splitByRowSpan-int-}
```
public final void splitByRowSpan(int index)
```

يقسم الخلية إلى خليتين حسب فهرس الصف.

**المعلمات:**  
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| index | int | فهرس الصف. |

### splitByHeight(double height) {#splitByHeight-double-}
```
public final void splitByHeight(double height)
```

يقسم الخلية حسب الارتفاع.

**المعلمات:**  
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| height | double | ارتفاع الصف. |

### splitByWidth(double width) {#splitByWidth-double-}
```
public final void splitByWidth(double width)
```

يقسم الخلية حسب العرض.

**المعلمات:**  
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| width | double | عرض العمود. |

### getSlide() {#getSlide--}
```
public final IBaseSlide getSlide()
```

يعيد الشريحة الأب للخلية. قيمة [IBaseSlide](../../com.aspose.slides/ibaseslide) للقراءة فقط.

**الإرجاع:**  
[IBaseSlide](../../com.aspose.slides/ibaseslide)

### getPresentation() {#getPresentation--}
```
public final IPresentation getPresentation()
```

يعيد العرض التقديمي الأب للخلية. قيمة [IPresentation](../../com.aspose.slides/ipresentation) للقراءة فقط.

**الإرجاع:**  
[IPresentation](../../com.aspose.slides/ipresentation)

### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```

يعيد كائن Parent_Immediate. قيمة IDOMObject للقراءة فقط.

**الإرجاع:**  
com.aspose.slides.IDOMObject