---
title: MathMatrix
second_title: Aspose.Slides لنظام Android عبر مرجع Java API
description: يحدد كائن Matrix المكوّن من عناصر فرعية مرتبة في صف واحد أو أكثر وأعمدة.
type: docs
url: /ar/com.aspose.slides/mathmatrix/
---
**الوراثة:**  
java.lang.Object, [com.aspose.slides.MathElementBase](../../com.aspose.slides/mathelementbase)

**جميع الواجهات المنفذة:**  
[com.aspose.slides.IMathMatrix](../../com.aspose.slides/imathmatrix), com.aspose.slides.IHasControlCharacterProperties  
```
public final class MathMatrix extends MathElementBase implements IMathMatrix, IHasControlCharacterProperties
```

يحدد كائن Matrix، المكوّن من عناصر فرعية مرتبة في صفّ واحد أو أكثر وأعمدة. من المهم ملاحظة أن المصفوفات لا تحتوي على فواصل مدمجة. لوضع المصفوفة داخل الأقواس يجب استخدام كائن الفاصل (IMathDelimiter). يمكن استخدام القيم null لإنشاء فراغات في المصفوفات.

--------------------

> ```
> Example:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.set_Item(0, 0, new MathematicalText("item.1.1"));
> ```
## المنشئات

| المُنشئ | الوصف |
| --- | --- |
| [MathMatrix(int rowCount, int columnCount)](#MathMatrix-int-int-) | يهيئ نسخة جديدة من الفئة MathMatrix. |
## الطرق

| الطريقة | الوصف |
| --- | --- |
| [getRowCount()](#getRowCount--) | عدد الصفوف في المصفوفة |
| [getColumnCount()](#getColumnCount--) | عدد الأعمدة في المصفوفة |
| [getHidePlaceholders()](#getHidePlaceholders--) | إخفاء العناصر النائبة لعناصر المصفوة الفارغة الافتراضي: false |
| [setHidePlaceholders(boolean value)](#setHidePlaceholders-boolean-) | إخفاء العناصر النائبة لعناصر المصفوة الفارغة الافتراضي: false |
| [getBaseJustification()](#getBaseJustification--) | يحدد المحاذاة العمودية بالنسبة للنص المحيط. |
| [setBaseJustification(int value)](#setBaseJustification-int-) | يحدد المحاذاة العمودية بالنسبة للنص المحيط. |
| [getMinColumnWidth()](#getMinColumnWidth--) | الحد الأدنى لعرض العمود بوحدة twips (1/20 من النقطة). تُضاف المسافة الفاصلة (المعروفة أيضًا باسم “Column Gap” أو “Gap Width”) إلى MinColumnWidth لتحديد إجمالي تباعد أعمدة المصفوفة (المسافة بين الحواف المتقابلة للأعمدة المختلفة). |
| [setMinColumnWidth(long value)](#setMinColumnWidth-long-) | الحد الأدنى لعرض العمود بوحدة twips (1/20 من النقطة). تُضاف المسافة الفاصلة (المعروفة أيضًا باسم “Column Gap” أو “Gap Width”) إلى MinColumnWidth لتحديد إجمالي تباعد أعمدة المصفوفة (المسافة بين الحواف المتقابلة للأعمدة المختلفة). |
| [getColumnGapRule()](#getColumnGapRule--) | نوع التباعد الأفقي بين أعمدة المصفوفة؛ يمكن أن تكون وحدات التباعد إما ems أو نقاط (مخزنة كـ twips). |
| [setColumnGapRule(int value)](#setColumnGapRule-int-) | نوع التباعد الأفقي بين أعمدة المصفوفة؛ يمكن أن تكون وحدات التباعد إما ems أو نقاط (مخزنة كـ twips). |
| [getColumnGap()](#getColumnGap--) | قيمة التباعد الأفقي بين أعمدة المصفوفة؛ إذا كان ColumnGapRule مضبوطًا على 3 (“Exactly”)، فإن الوحدة تُفسَّر كـ twips (1/20 من النقطة). إذا كان ColumnGapRule مضبوطًا على 4 (“Multiple”)، فإن الوحدة تُفسَّر كعدد من الزيادات 0.5 em. في الحالات الأخرى تُهمل. الافتراضي: 0 |
| [setColumnGap(long value)](#setColumnGap-long-) | قيمة التباعد الأفقي بين أعمدة المصفوفة؛ إذا كان ColumnGapRule مضبوطًا على 3 (“Exactly”)، فإن الوحدة تُفسَّر كـ twips (1/20 من النقطة). إذا كان ColumnGapRule مضبوطًا على 4 (“Multiple”)، فإن الوحدة تُفسَّر كعدد من الزيادات 0.5 em. في الحالات الأخرى تُهمل. الافتراضي: 0 |
| [getRowGapRule()](#getRowGapRule--) | نوع التباعد العمودي بين صفوف المصفوفة؛ يمكن أن تكون وحدات التباعد إما خطوط أو نقاط (مخزنة كـ twips). |
| [setRowGapRule(int value)](#setRowGapRule-int-) | نوع التباعد العمودي بين صفوف المصفوفة؛ يمكن أن تكون وحدات التباعد إما خطوط أو نقاط (مخزنة كـ twips). |
| [getRowGap()](#getRowGap--) | قيمة التباعد العمودي بين صفوف المصفوفة؛ إذا كان RowGapRule مضبوطًا على 3 (“Exactly”)، فإن الوحدة تُفسَّر كـ twips (1/20 من النقطة). إذا كان RowGapRule مضبوطًا على 4 (“Multiple”)، فإن الوحدة تُفسَّر كنصف خطوط. الافتراضي: 0 |
| [setRowGap(long value)](#setRowGap-long-) | قيمة التباعد العمودي بين صفوف المصفوفة؛ إذا كان RowGapRule مضبوطًا على 3 (“Exactly”)، فإن الوحدة تُفسَّر كـ twips (1/20 من النقطة). إذا كان RowGapRule مضبوطًا على 4 (“Multiple”)، فإن الوحدة تُفسَّر كنصف خطوط. الافتراضي: 0 |
| [get_Item(int row, int column)](#get-Item-int-int-) | عنصر من المصفوفة |
| [set_Item(int row, int column, IMathElement value)](#set-Item-int-int-com.aspose.slides.IMathElement-) | عنصر من المصفوفة |
| [getControlCharacterProperties()](#getControlCharacterProperties--) | خصائص حرف التحكم |
| [getColumnAlignment(int columnIndex)](#getColumnAlignment-int-) | الحصول على محاذاة أفقية للعمود المحدد |
| [setColumnAlignment(int columnIndex, int val)](#setColumnAlignment-int-int-) | تعيين المحاذاة الأفقية للعمود المحدد |
| [setColumnsAlignment(int columnIndex, long columnsCount, int val)](#setColumnsAlignment-int-long-int-) | تعيين المحاذاة الأفقية للأعمدة المحددة |
| [insertRowBefore(int rowIndex)](#insertRowBefore-int-) | إدراج صف جديد قبل الصف المحدد. في البداية تكون جميع العناصر في الصف الجديد null. |
| [insertRowAfter(int rowIndex)](#insertRowAfter-int-) | إدراج صف جديد بعد الصف المحدد. في البداية تكون جميع العناصر في الصف الجديد null. |
| [deleteRow(int rowIndex)](#deleteRow-int-) | حذف الصف المحدد |
| [insertColumnBefore(int columnIndex)](#insertColumnBefore-int-) | إدراج عمود جديد قبل العمود المحدد. في البداية تكون جميع العناصر في العمود الجديد null. |
| [insertColumnAfter(int columnIndex)](#insertColumnAfter-int-) | إدراج عمود جديد بعد العمود المحدد. في البداية تكون جميع العناصر في العمود الجديد null. |
| [deleteColumn(int columnIndex)](#deleteColumn-int-) | حذف العمود المحدد |
| [getChildren()](#getChildren--) | الحصول على عناصر الأطفال |

### MathMatrix(int rowCount, int columnCount) {#MathMatrix-int-int-}
```
public MathMatrix(int rowCount, int columnCount)
```

يهيئ نسخة جديدة من الفئة MathMatrix.

--------------------

> ```
> Example:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
> ```

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| rowCount | int | عدد الصفوف |
| columnCount | int | عدد الأعمدة |

### getRowCount() {#getRowCount--}
```
public final int getRowCount()
```

عدد الصفوف في المصفوفة

--------------------

> ```
> Example:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  int rowCount = matrix.getRowCount();
> ```

**القيمة المرجعة:**
int
### getColumnCount() {#getColumnCount--}
```
public final int getColumnCount()
```

عدد الأعمدة في المصفوفة

--------------------

> ```
> Example:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  int columnCount = matrix.getColumnCount();
> ```

**القيمة المرجعة:**
int
### getHidePlaceholders() {#getHidePlaceholders--}
```
public final boolean getHidePlaceholders()
```

إخفاء العناصر النائبة لعناصر المصفوة الفارغة الافتراضي: false

--------------------

> ```
> Example:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.setHidePlaceholders(true);
> ```

**القيمة المرجعة:**
boolean
### setHidePlaceholders(boolean value) {#setHidePlaceholders-boolean-}
```
public final void setHidePlaceholders(boolean value)
```

إخفاء العناصر النائبة لعناصر المصفوة الفارغة الافتراضي: false

--------------------

> ```
> Example:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.setHidePlaceholders(true);
> ```

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | boolean |  |

### getBaseJustification() {#getBaseJustification--}
```
public final int getBaseJustification()
```

يحدد المحاذاة العمودية بالنسبة للنص المحيط. القيم الممكنة هي top, bottom, و center. الافتراضي: Center

--------------------

> ```
> مثال:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.setBaseJustification(MathVerticalAlignment.Center);
```

**القيمة المرجعة:**
int
### setBaseJustification(int value) {#setBaseJustification-int-}
```
public final void setBaseJustification(int value)
```

يحدد المحاذاة العمودية بالنسبة للنص المحيط. القيم الممكنة هي top, bottom, و center. الافتراضي: Center

--------------------

> ```
> Example:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.setBaseJustification(MathVerticalAlignment.Center);
> ```

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | int |  |

### getMinColumnWidth() {#getMinColumnWidth--}
```
public final long getMinColumnWidth()
```

الحد الأدنى لعرض العمود بوحدة twips (1/20 من النقطة). تُضاف المسافة الفاصلة (المعروفة أيضًا باسم “Column Gap” أو “Gap Width”) إلى MinColumnWidth لتحديد إجمالي تباعد أعمدة المصفوفة (المسافة بين الحواف المتقابلة للأعمدة المختلفة). الافتراضي: 0.

--------------------

> ```
> مثال:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.setMinColumnWidth(20);
> ```


**القيمة المرجعة:**
long
### setMinColumnWidth(long value) {#setMinColumnWidth-long-}
```
public final void setMinColumnWidth(long value)
```

الحد الأدنى لعرض العمود بوحدة twips (1/20 من النقطة). تُضاف المسافة الفاصلة (المعروفة أيضًا باسم “Column Gap” أو “Gap Width”) إلى MinColumnWidth لتحديد إجمالي تباعد أعمدة المصفوفة (المسافة بين الحواف المتقابلة للأعمدة المختلفة). الافتراضي: 0.

--------------------

> ```
> Example:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.setMinColumnWidth(20);
> ```

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | long |  |

### getColumnGapRule() {#getColumnGapRule--}
```
public final int getColumnGapRule()
```

نوع التباعد الأفقي بين أعمدة المصفوفة؛ يمكن أن تكون وحدات التباعد إما ems أو نقاط (مخزنة كـ twips). الافتراضي: SingleSpacingGap (0)

--------------------

> ```
> مثال:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.setColumnGapRule(MathSpacingRules.OneAndHalfSpacingGap);
> ```

**القيمة المرجعة:**
int
### setColumnGapRule(int value) {#setColumnGapRule-int-}
```
public final void setColumnGapRule(int value)
```

نوع التباعد الأفقي بين أعمدة المصفوفة؛ يمكن أن تكون وحدات التباعد إما ems أو نقاط (مخزنة كـ twips). الافتراضي: SingleSpacingGap (0)

--------------------

> ```
> مثال:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.setColumnGapRule(MathSpacingRules.OneAndHalfSpacingGap);
> ```


**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | int |  |

### getColumnGap() {#getColumnGap--}
```
public final long getColumnGap()
```

قيمة التباعد الأفقي بين أعمدة المصفوفة؛ إذا كان ColumnGapRule مضبوطًا على 3 (“Exactly”)، فإن الوحدة تُفسَّر كـ twips (1/20 من النقطة). إذا كان ColumnGapRule مضبوطًا على 4 (“Multiple”)، فإن الوحدة تُفسَّر كعدد من الزيادات 0.5 em. في الحالات الأخرى تُهمل. الافتراضي: 0

--------------------

> ```
> Example:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.setColumnGapRule(MathSpacingRules.Exactly);
>  matrix.setColumnGap(20);
> ```

**القيمة المرجعة:**
long
### setColumnGap(long value) {#setColumnGap-long-}
```
public final void setColumnGap(long value)
```

قيمة التباعد الأفقي بين أعمدة المصفوفة؛ إذا كان ColumnGapRule مضبوطًا على 3 (“Exactly”)، فإن الوحدة تُفسَّر كـ twips (1/20 من النقطة). إذا كان ColumnGapRule مضبوطًا على 4 (“Multiple”)، فإن الوحدة تُفسَّر كعدد من الزيادات 0.5 em. في الحالات الأخرى تُهمل. الافتراضي: 0

--------------------

> ```
> مثال:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.setColumnGapRule(MathSpacingRules.Exactly);
>  matrix.setColumnGap(20);
> ```


**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | long |  |

### getRowGapRule() {#getRowGapRule--}
```
public final int getRowGapRule()
```

نوع التباعد العمودي بين صفوف المصفوفة؛ يمكن أن تكون وحدات التباعد إما خطوط أو نقاط (مخزنة كـ twips). الافتراضي: SingleSpacingGap (0)

--------------------

> ```
> Example:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.setRowGapRule(MathSpacingRules.OneAndHalfSpacingGap);
> ```

**القيمة المرجعة:**
int
### setRowGapRule(int value) {#setRowGapRule-int-}
```
public final void setRowGapRule(int value)
```

نوع التباعد العمودي بين صفوف المصفوفة؛ يمكن أن تكون وحدات التباعد إما خطوط أو نقاط (مخزنة كـ twips). الافتراضي: SingleSpacingGap (0)

--------------------

> ```
> مثال:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.setRowGapRule(MathSpacingRules.OneAndHalfSpacingGap);
> ```

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | int |  |

### getRowGap() {#getRowGap--}
```
public final long getRowGap()
```

قيمة التباعد العمودي بين صفوف المصفوفة؛ إذا كان RowGapRule مضبوطًا على 3 (“Exactly”)، فإن الوحدة تُفسَّر كـ twips (1/20 من النقطة). إذا كان RowGapRule مضبوطًا على 4 (“Multiple”)، فإن الوحدة تُفسَّر كنصف خطوط. الافتراضي: 0

--------------------

> ```
> Example:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.setRowGapRule(MathSpacingRules.Exactly);
>  matrix.setRowGap(20);
> ```

**القيمة المرجعة:**
long
### setRowGap(long value) {#setRowGap-long-}
```
public final void setRowGap(long value)
```

قيمة التباعد العمودي بين صفوف المصفوفة؛ إذا كان RowGapRule مضبوطًا على 3 (“Exactly”)، فإن الوحدة تُفسَّر كـ twips (1/20 من النقطة). إذا كان RowGapRule مضبوطًا على 4 (“Multiple”)، فإن الوحدة تُفسَّر كنصف خطوط. الافتراضي: 0

--------------------

> ```
> Example:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.setRowGapRule(MathSpacingRules.Exactly);
>  matrix.setRowGap(20);
> ```

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | long |  |

### get_Item(int row, int column) {#get-Item-int-int-}
```
public final IMathElement get_Item(int row, int column)
```

عنصر من المصفوفة

--------------------

> ```
> مثال:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.set_Item(0, 0, new MathematicalText("item.1.1"));
> ```

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| row | int | الفهرس الصفري للصف للحصول على العنصر |
| column | int | الفهرس الصفري للعمود للحصول على العنصر |

**القيمة المرجعة:**
[IMathElement](../../com.aspose.slides/imathelement) - IMathElement
### set_Item(int row, int column, IMathElement value) {#set-Item-int-int-com.aspose.slides.IMathElement-}
```
public final void set_Item(int row, int column, IMathElement value)
```

عنصر من المصفوفة

--------------------

> ```
> مثال:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.set_Item(0, 0, new MathematicalText("item.1.1"));
> ```

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| row | int | الفهرس الصفري للصف للحصول على العنصر |
| column | int | الفهرس الصفري للعمود للحصول على العنصر |
| value | [IMathElement](../../com.aspose.slides/imathelement) |  |

### getControlCharacterProperties() {#getControlCharacterProperties--}
```
public final OmmlControlCharacterPPTXUnsupportedProps getControlCharacterProperties()
```

خصائص حرف التحكم

**القيمة المرجعة:**
com.aspose.slides.OmmlControlCharacterPPTXUnsupportedProps
### getColumnAlignment(int columnIndex) {#getColumnAlignment-int-}
```
public final int getColumnAlignment(int columnIndex)
```

الحصول على المحاذاة الأفقية للعمود المحدد

--------------------

> ```
> Example:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  MathHorizontalAlignment alignment = matrix.getColumnAlignment(0);
> ```

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| columnIndex | int | فهرس العمود الصفري |

**القيمة المرجعة:**
int - المحاذاة الأفقية للعمود المحدد
### setColumnAlignment(int columnIndex, int val) {#setColumnAlignment-int-int-}
```
public final void setColumnAlignment(int columnIndex, int val)
```

تعيين المحاذاة الأفقية للعمود المحدد

--------------------

> ```
> مثال:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.setColumnAlignment(0, MathHorizontalAlignment.Left);
> ```

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| columnIndex | int | فهرس العمود الصفري |
| val | int | القيمة الجديدة للمحاذاة الأفقية للعمود المحدد |

### setColumnsAlignment(int columnIndex, long columnsCount, int val) {#setColumnsAlignment-int-long-int-}
```
public final void setColumnsAlignment(int columnIndex, long columnsCount, int val)
```

تعيين المحاذاة الأفقية للأعمدة المحددة

--------------------

> ```
> مثال
```

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| columnIndex | int | الفهرس الصفري للعمود الأول لتعيين المحاذاة |
| columnsCount | long | عدد الأعمدة التي سيُحدَّد لها المحاذاة |
| val | int | القيمة الجديدة للمحاذاة الأفقية للعمود المحدد |

### insertRowBefore(int rowIndex) {#insertRowBefore-int-}
```
public final void insertRowBefore(int rowIndex)
```

إدراج صف جديد قبل الصف المحدد. في البداية تكون جميع العناصر في الصف الجديد null.

--------------------

> ```
> مثال:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.insertRowBefore(1);
> ```

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| rowIndex | int | فهرس الصف قبل الذي يُدرج صف جديد |

### insertRowAfter(int rowIndex) {#insertRowAfter-int-}
```
public final void insertRowAfter(int rowIndex)
```

إدراج صف جديد بعد الصف المحدد. في البداية تكون جميع العناصر في الصف الجديد null.

--------------------

> ```
> مثال:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.insertRowAfter(1);
> ```


**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| rowIndex | int | فهرس الصف بعده يُدرج صف جديد |

### deleteRow(int rowIndex) {#deleteRow-int-}
```
public final void deleteRow(int rowIndex)
```

حذف الصف المحدد

--------------------

> ```
> مثال:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.deleteRow(0);
> ```

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| rowIndex | int | الفهرس الصفري للصف لحذفه. |

### insertColumnBefore(int columnIndex) {#insertColumnBefore-int-}
```
public final void insertColumnBefore(int columnIndex)
```

إدراج عمود جديد قبل العمود المحدد. في البداية تكون جميع العناصر في العمود الجديد null.

--------------------

> ```
> مثال:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.insertColumnBefore(0);
> ```

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| columnIndex | int | فهرس العمود قبل الذي يُدرج عمود جديد |

### insertColumnAfter(int columnIndex) {#insertColumnAfter-int-}
```
public final void insertColumnAfter(int columnIndex)
```

إدراج عمود جديد بعد العمود المحدد. في البداية تكون جميع العناصر في العمود الجديد null.

--------------------

> ```
> مثال:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.insertColumnAfter(0);
> ```

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| columnIndex | int | فهرس العمود بعده يُدرج عمود جديد |

### deleteColumn(int columnIndex) {#deleteColumn-int-}
```
public final void deleteColumn(int columnIndex)
```

حذف العمود المحدد

--------------------

> ```
> مثال:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.deleteColumn(0);
> ```

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| columnIndex | int | الفهرس الصفري للعمود لحذفه. |

### getChildren() {#getChildren--}
```
public final IMathElement[] getChildren()
```

الحصول على عناصر الأطفال

**القيمة المرجعة:**
com.aspose.slides.IMathElement[]