---
title: ICell
second_title: مرجع API Aspose.Slides للغة Java
description: يمثل خلية في جدول.
type: docs
url: /ar/com.aspose.slides/icell/
---
**جميع الواجهات المنفذة:**
[com.aspose.slides.ISlideComponent](../../com.aspose.slides/islidecomponent)
```
public interface ICell extends ISlideComponent
```

يمثل خلية في جدول.

## الطرق

| الطريقة | الوصف |
| --- | --- |
| [getOffsetX()](#getOffsetX--) | إرجاع مسافة من الجانب الأيسر للجدول إلى الجانب الأيسر للخلية. |
| [getOffsetY()](#getOffsetY--) | إرجاع مسافة من الجانب العلوي للجدول إلى الجانب العلوي للخلية. |
| [getFirstRowIndex()](#getFirstRowIndex--) | إرجاع فهرس الصف الأول المغطى بالخلية. |
| [getFirstColumnIndex()](#getFirstColumnIndex--) | إرجاع فهرس العمود الأول المغطى بالخلية. |
| [getWidth()](#getWidth--) | إرجاع عرض الخلية. |
| [getHeight()](#getHeight--) | إرجاع ارتفاع الخلية. |
| [getMinimalHeight()](#getMinimalHeight--) | إرجاع الحد الأدنى لارتفاع الخلية. |
| [getMarginLeft()](#getMarginLeft--) | إرجاع أو ضبط الهامش الأيسر في TextFrame. |
| [setMarginLeft(double value)](#setMarginLeft-double-) | إرجاع أو ضبط الهامش الأيسر في TextFrame. |
| [getMarginRight()](#getMarginRight--) | إرجاع أو ضبط الهامش الأيمن في TextFrame. |
| [setMarginRight(double value)](#setMarginRight-double-) | إرجاع أو ضبط الهامش الأيمن في TextFrame. |
| [getMarginTop()](#getMarginTop--) | إرجاع أو ضبط الهامش العلوي في TextFrame. |
| [setMarginTop(double value)](#setMarginTop-double-) | إرجاع أو ضبط الهامش العلوي في TextFrame. |
| [getMarginBottom()](#getMarginBottom--) | إرجاع أو ضبط الهامش السفلي في TextFrame. |
| [setMarginBottom(double value)](#setMarginBottom-double-) | إرجاع أو ضبط الهامش السفلي في TextFrame. |
| [getTextVerticalType()](#getTextVerticalType--) | إرجاع أو ضبط نوع النص العمودي. |
| [setTextVerticalType(byte value)](#setTextVerticalType-byte-) | إرجاع أو ضبط نوع النص العمودي. |
| [getTextAnchorType()](#getTextAnchorType--) | إرجاع أو ضبط نوع مرساة النص. |
| [setTextAnchorType(byte value)](#setTextAnchorType-byte-) | إرجاع أو ضبط نوع مرساة النص. |
| [getAnchorCenter()](#getAnchorCenter--) | تحديد ما إذا كان صندوق النص مركّزًا داخل الخلية أم لا. |
| [setAnchorCenter(boolean value)](#setAnchorCenter-boolean-) | تحديد ما إذا كان صندوق النص مركّزًا داخل الخلية أم لا. |
| [getFirstColumn()](#getFirstColumn--) | الحصول على العمود الأول للخلية. |
| [getFirstRow()](#getFirstRow--) | الحصول على الصف الأول للخلية. |
| [getColSpan()](#getColSpan--) | إرجاع عدد أعمدة الشبكة في شبكة جدول الجدول الأب التي يجب أن يمتد عبرها الخلية الحالية. |
| [getRowSpan()](#getRowSpan--) | إرجاع عدد الصفوف التي يغطيها خلية مدمجة. |
| [getTextFrame()](#getTextFrame--) | إرجاع إطار النص للخلية. |
| [getTable()](#getTable--) | إرجاع كائن Table الأب للخلية. |
| [isMergedCell()](#isMergedCell--) | إرجاع true إذا كانت الخلية مدمجة مع أي خلية معدلة، وإلا false. |
| [getCellFormat()](#getCellFormat--) | إرجاع كائن CellFormat الذي يحتوي على خصائص التنسيق لهذه الخلية. |
| [splitByColSpan(int index)](#splitByColSpan-int-) | تقسيم الخلية إلى خيليتين حسب فهرس العمود. |
| [splitByRowSpan(int index)](#splitByRowSpan-int-) | تقسيم الخلية إلى خيليتين حسب فهرس الصف. |
| [splitByHeight(double height)](#splitByHeight-double-) | تقسيم الخلية حسب الارتفاع. |
| [splitByWidth(double width)](#splitByWidth-double-) | تقسيم الخلية حسب العرض. |

### getOffsetX() {#getOffsetX--}
```
public abstract double getOffsetX()
```

إرجاع مسافة من الجانب الأيسر للجدول إلى الجانب الأيسر للخلية. للقراءة فقط double.

**الإرجاع:**
double

### getOffsetY() {#getOffsetY--}
```
public abstract double getOffsetY()
```

إرجاع مسافة من الجانب العلوي للجدول إلى الجانب العلوي للخلية. للقراءة فقط double.

**الإرجاع:**
double

### getFirstRowIndex() {#getFirstRowIndex--}
```
public abstract int getFirstRowIndex()
```

إرجاع فهرس الصف الأول المغطى بالخلية. للقراءة فقط int.

**الإرجاع:**
int

### getFirstColumnIndex() {#getFirstColumnIndex--}
```
public abstract int getFirstColumnIndex()
```

إرجاع فهرس العمود الأول المغطى بالخلية. للقراءة فقط int.

**الإرجاع:**
int

### getWidth() {#getWidth--}
```
public abstract double getWidth()
```

إرجاع عرض الخلية. للقراءة فقط double.

**الإرجاع:**
double

### getHeight() {#getHeight--}
```
public abstract double getHeight()
```

إرجاع ارتفاع الخلية. للقراءة فقط double.

**الإرجاع:**
double

### getMinimalHeight() {#getMinimalHeight--}
```
public abstract double getMinimalHeight()
```

إرجاع الحد الأدنى لارتفاع الخلية. هذا مجموع الارتفاعات الدنيا لجميع الصفوف التي تغطيها الخلية. للقراءة فقط double.

**الإرجاع:**
double

### getMarginLeft() {#getMarginLeft--}
```
public abstract double getMarginLeft()
```

إرجاع أو ضبط الهامش الأيسر في TextFrame. قراءة/كتابة double.

**الإرجاع:**
double

### setMarginLeft(double value) {#setMarginLeft-double-}
```
public abstract void setMarginLeft(double value)
```

إرجاع أو ضبط الهامش الأيسر في TextFrame. قراءة/كتابة double.

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | double |  |

### getMarginRight() {#getMarginRight--}
```
public abstract double getMarginRight()
```

إرجاع أو ضبط الهامش الأيمن في TextFrame. قراءة/كتابة double.

**الإرجاع:**
double

### setMarginRight(double value) {#setMarginRight-double-}
```
public abstract void setMarginRight(double value)
```

إرجاع أو ضبط الهامش الأيمن في TextFrame. قراءة/كتابة double.

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | double |  |

### getMarginTop() {#getMarginTop--}
```
public abstract double getMarginTop()
```

إرجاع أو ضبط الهامش العلوي في TextFrame. قراءة/كتابة double.

**الإرجاع:**
double

### setMarginTop(double value) {#setMarginTop-double-}
```
public abstract void setMarginTop(double value)
```

إرجاع أو ضبط الهامش العلوي في TextFrame. قراءة/كتابة double.

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | double |  |

### getMarginBottom() {#getMarginBottom--}
```
public abstract double getMarginBottom()
```

إرجاع أو ضبط الهامش السفلي في TextFrame. قراءة/كتابة double.

**الإرجاع:**
double

### setMarginBottom(double value) {#setMarginBottom-double-}
```
public abstract void setMarginBottom(double value)
```

إرجاع أو ضبط الهامش السفلي في TextFrame. قراءة/كتابة double.

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | double |  |

### getTextVerticalType() {#getTextVerticalType--}
```
public abstract byte getTextVerticalType()
```

إرجاع أو ضبط نوع النص العمودي. قراءة/كتابة [TextVerticalType](../../com.aspose.slides/textverticaltype).

**الإرجاع:**
byte

### setTextVerticalType(byte value) {#setTextVerticalType-byte-}
```
public abstract void setTextVerticalType(byte value)
```

إرجاع أو ضبط نوع النص العمودي. قراءة/كتابة [TextVerticalType](../../com.aspose.slides/textverticaltype).

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | byte |  |

### getTextAnchorType() {#getTextAnchorType--}
```
public abstract byte getTextAnchorType()
```

إرجاع أو ضبط نوع مرساة النص. قراءة/كتابة [TextAnchorType](../../com.aspose.slides/textanchortype).

**الإرجاع:**
byte

### setTextAnchorType(byte value) {#setTextAnchorType-byte-}
```
public abstract void setTextAnchorType(byte value)
```

إرجاع أو ضبط نوع مرساة النص. قراءة/كتابة [TextAnchorType](../../com.aspose.slides/textanchortype).

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | byte |  |

### getAnchorCenter() {#getAnchorCenter--}
```
public abstract boolean getAnchorCenter()
```

تحديد ما إذا كان صندوق النص مركّزًا داخل الخلية أم لا. قراءة/كتابة boolean.

**الإرجاع:**
boolean

### setAnchorCenter(boolean value) {#setAnchorCenter-boolean-}
```
public abstract void setAnchorCenter(boolean value)
```

تحديد ما إذا كان صندوق النص مركّزًا داخل الخلية أم لا. قراءة/كتابة boolean.

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | boolean |  |

### getFirstColumn() {#getFirstColumn--}
```
public abstract IColumn getFirstColumn()
```

الحصول على العمود الأول للخلية. للقراءة فقط [IColumn](../../com.aspose.slides/icolumn).

**الإرجاع:**
[IColumn](../../com.aspose.slides/icolumn)

### getFirstRow() {#getFirstRow--}
```
public abstract IRow getFirstRow()
```

الحصول على الصف الأول للخلية. للقراءة فقط [IRow](../../com.aspose.slides/irow).

**الإرجاع:**
[IRow](../../com.aspose.slides/irow)

### getColSpan() {#getColSpan--}
```
public abstract int getColSpan()
```

إرجاع عدد أعمدة الشبكة في شبكة جدول الجدول الأب التي يجب أن يمتد عبرها الخلية الحالية. تسمح هذه الخاصية للخلية بأن تبدو مدمجة عبر حدود خلايا أخرى في الجدول. للقراءة فقط int.

**الإرجاع:**
int

### getRowSpan() {#getRowSpan--}
```
public abstract int getRowSpan()
```

إرجاع عدد الصفوف التي يغطيها خلية مدمجة. يُستخدم هذا بالتزامن مع سمة vMerge على خلايا أخرى لتحديد خلية البداية للدمج الأفقي. للقراءة فقط int.

**الإرجاع:**
int

### getTextFrame() {#getTextFrame--}
```
public abstract ITextFrame getTextFrame()
```

إرجاع إطار النص للخلية. للقراءة فقط [ITextFrame](../../com.aspose.slides/itextframe).

**الإرجاع:**
[ITextFrame](../../com.aspose.slides/itextframe)

### getTable() {#getTable--}
```
public abstract ITable getTable()
```

إرجاع كائن Table الأب للخلية. للقراءة فقط [ITable](../../com.aspose.slides/itable).

**الإرجاع:**
[ITable](../../com.aspose.slides/itable)

### isMergedCell() {#isMergedCell--}
```
public abstract boolean isMergedCell()
```

إرجاع true إذا كانت الخلية مدمجة مع أي خلية معدلة، وإلا false. للقراءة فقط boolean.

**الإرجاع:**
boolean

### getCellFormat() {#getCellFormat--}
```
public abstract ICellFormat getCellFormat()
```

إرجاع كائن CellFormat الذي يحتوي على خصائص التنسيق لهذه الخلية. للقراءة فقط [ICellFormat](../../com.aspose.slides/icellformat).

**الإرجاع:**
[ICellFormat](../../com.aspose.slides/icellformat)

### splitByColSpan(int index) {#splitByColSpan-int-}
```
public abstract void splitByColSpan(int index)
```

تقسيم الخلية إلى خيليتين حسب فهرس العمود.

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| index | int | فهرس العمود. |

### splitByRowSpan(int index) {#splitByRowSpan-int-}
```
public abstract void splitByRowSpan(int index)
```

تقسيم الخلية إلى خيليتين حسب فهرس الصف.

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| index | int | فهرس الصف. |

### splitByHeight(double height) {#splitByHeight-double-}
```
public abstract void splitByHeight(double height)
```

تقسيم الخلية حسب الارتفاع.

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| height | double | ارتفاع الصف. |

### splitByWidth(double width) {#splitByWidth-double-}
```
public abstract void splitByWidth(double width)
```

تقسيم الخلية حسب العرض.

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| width | double | عرض العمود. |