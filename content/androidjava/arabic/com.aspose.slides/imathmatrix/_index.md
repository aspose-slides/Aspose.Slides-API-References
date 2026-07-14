---
title: IMathMatrix
second_title: Aspose.Slides لنظام Android عبر مرجع API للـ Java
description: يحدد كائن Matrix المكوّن من عناصر فرعية مرتبة في صف واحد أو أكثر وأعمدة.
type: docs
url: /ar/com.aspose.slides/imathmatrix/
---
**جميع الواجهات المُنفذة:**
[com.aspose.slides.IMathElement](../../com.aspose.slides/imathelement)
```
public interface IMathMatrix extends IMathElement
```

يحدد كائن Matrix، المكوّن من عناصر فرعية مرتّبة في صف واحد أو أكثر وأعمدة. من المهم ملاحظة أن المصفوفات لا تحتوي على محددات مدمجة. لوضع المصفوفة بين الأقواس يجب عليك استخدام كائن المحدد (IMathDelimiter). يمكن استخدام القيم الفارغة (null) لإنشاء فراغات في المصفوفات.

--------------------

> ```
> Example:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.set_Item(0, 0, new MathematicalText("item.1.1"));
> ```
## الطرق

| الطريقة | الوصف |
| --- | --- |
| [get_Item(int row, int column)](#get-Item-int-int-) | عناصر المصفوفة |
| [set_Item(int row, int column, IMathElement value)](#set-Item-int-int-com.aspose.slides.IMathElement-) | عناصر المصفوفة |
| [getRowCount()](#getRowCount--) | عدد الصفوف في المصفوفة |
| [getColumnCount()](#getColumnCount--) | عدد الأعمدة في المصفوفة |
| [getHidePlaceholders()](#getHidePlaceholders--) | إخفاء العناصر النائبة لعناصر المصفوفة الفارغة. القيمة الافتراضية: false |
| [setHidePlaceholders(boolean value)](#setHidePlaceholders-boolean-) | إخفاء العناصر النائبة لعناصر المصفوفة الفارغة. القيمة الافتراضية: false |
| [getBaseJustification()](#getBaseJustification--) | يحدد المحاذاة العمودية بالنسبة للنص المحيط. |
| [setBaseJustification(int value)](#setBaseJustification-int-) | يحدد المحاذاة العمودية بالنسبة للنص المحيط. |
| [getMinColumnWidth()](#getMinColumnWidth--) | الحد الأدنى لعرض العمود بوحدة twips (1/20 نقطة). يتم إضافة الفجوة (المعروفة أيضًا باسم “Column Gap” أو “Gap Width”) إلى MinColumnWidth لتحديد إجمالي تباعد أعمدة المصفوفة (المسافة بين حواف الأعمدة المختلفة). |
| [setMinColumnWidth(long value)](#setMinColumnWidth-long-) | الحد الأدنى لعرض العمود بوحدة twips (1/20 نقطة). يتم إضافة الفجوة (المعروفة أيضًا باسم “Column Gap” أو “Gap Width”) إلى MinColumnWidth لتحديد إجمالي تباعد أعمدة المصفوفة (المسافة بين حواف الأعمدة المختلفة). |
| [getColumnGapRule()](#getColumnGapRule--) | نوع التباعد الأفقي بين أعمدة المصفوفة؛ يمكن أن تكون وحدات التباعد الأفقي إما ems أو نقاط (مخزنة كوحدات twips). |
| [setColumnGapRule(int value)](#setColumnGapRule-int-) | نوع التباعد الأفقي بين أعمدة المصفوفة؛ يمكن أن تكون وحدات التباعد الأفقي إما ems أو نقاط (مخزنة كوحدات twips). |
| [getColumnGap()](#getColumnGap--) | قيمة التباعد الأفقي بين أعمدة المصفوفة؛ إذا تم ضبط ColumnGapRule إلى 3 ("Exactly")، فإن الوحدة تُفسّر كوحدة twips (1/20 نقطة). إذا تم ضبط ColumnGapRule إلى 4 ("Multiple")، فإن الوحدة تُفسّر كعدد من الزيادة 0.5 em. |
| [setColumnGap(long value)](#setColumnGap-long-) | قيمة التباعد الأفقي بين أعمدة المصفوفة؛ إذا تم ضبط ColumnGapRule إلى 3 ("Exactly")، فإن الوحدة تُفسّر كوحدة twips (1/20 نقطة). إذا تم ضبط ColumnGapRule إلى 4 ("Multiple")، فإن الوحدة تُفسّر كعدد من الزيادة 0.5 em. |
| [getRowGapRule()](#getRowGapRule--) | نوع التباعد العمودي بين صفوف المصفوفة؛ يمكن أن تكون وحدات التباعد العمودي خطوطًا أو نقاطًا (مخزنة كوحدات twips). |
| [setRowGapRule(int value)](#setRowGapRule-int-) | نوع التباعد العمودي بين صفوف المصفوفة؛ يمكن أن تكون وحدات التباعد العمودي خطوطًا أو نقاطًا (مخزنة كوحدات twips). |
| [getRowGap()](#getRowGap--) | قيمة التباعد العمودي بين صفوف المصفوفة؛ إذا تم ضبط RowGapRule إلى 3 ("Exactly")، فإن الوحدة تُفسّر كوحدة twips (1/20 نقطة). إذا تم ضبط RowGapRule إلى 4 ("Multiple")، فإن الوحدة تُفسّر كنصف خطوط. |
| [setRowGap(long value)](#setRowGap-long-) | قيمة التباعد العمودي بين صفوف المصفوفة؛ إذا تم ضبط RowGapRule إلى 3 ("Exactly")، فإن الوحدة تُفسّر كوحدة twips (1/20 نقطة). إذا تم ضبط RowGapRule إلى 4 ("Multiple")، فإن الوحدة تُفسّر كنصف خطوط. |
| [getColumnAlignment(int columnIndex)](#getColumnAlignment-int-) | الحصول على المحاذاة الأفقية للعمود المحدد |
| [setColumnAlignment(int columnIndex, int val)](#setColumnAlignment-int-int-) | تعيين المحاذاة الأفقية للعمود المحدد |
| [setColumnsAlignment(int columnIndex, long columnsCount, int val)](#setColumnsAlignment-int-long-int-) | تعيين المحاذاة الأفقية للأعمدة المحددة |
| [insertRowBefore(int rowIndex)](#insertRowBefore-int-) | إدراج صف جديد قبل الصف المحدد. في البداية جميع عناصر الصف الجديد تكون null. |
| [insertRowAfter(int rowIndex)](#insertRowAfter-int-) | إدراج صف جديد بعد الصف المحدد. في البداية جميع عناصر الصف الجديد تكون null. |
| [deleteRow(int rowIndex)](#deleteRow-int-) | حذف الصف المحدد |
| [insertColumnBefore(int columnIndex)](#insertColumnBefore-int-) | إدراج عمود جديد قبل العمود المحدد. في البداية جميع عناصر العمود الجديد تكون null. |
| [insertColumnAfter(int columnIndex)](#insertColumnAfter-int-) | إدراج عمود جديد بعد العمود المحدد. في البداية جميع عناصر العمود الجديد تكون null. |
| [deleteColumn(int columnIndex)](#deleteColumn-int-) | حذف العمود المحدد |

### get_Item(int row, int column) {#get-Item-int-int-}
```
public abstract IMathElement get_Item(int row, int column)
```

عناصر المصفوفة

--------------------

> ```
> Example:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.set_Item(0, 0, new MathematicalText("item.1.1"));
> ```

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| row | int | الفهرس الصفري للصف للحصول على العنصر |
| column | int | الفهرس الصفري للعمود للحصول على العنصر |

**الإرجاع:**
[IMathElement](../../com.aspose.slides/imathelement) - IMathElement

### set_Item(int row, int column, IMathElement value) {#set-Item-int-int-com.aspose.slides.IMathElement-}
```
public abstract void set_Item(int row, int column, IMathElement value)
```

عناصر المصفوفة

--------------------

> ```
> Example:
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

### getRowCount() {#getRowCount--}
```
public abstract int getRowCount()
```

عدد الصفوف في المصفوفة

--------------------

> ```
> Example:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  int rowCount = matrix.getRowCount();
> ```

**الإرجاع:**
int

### getColumnCount() {#getColumnCount--}
```
public abstract int getColumnCount()
```

عدد الأعمدة في المصفوفة

--------------------

> ```
> Example:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  int columnCount = matrix.getColumnCount();
> ```

**الإرجاع:**
int

### getHidePlaceholders() {#getHidePlaceholders--}
```
public abstract boolean getHidePlaceholders()
```

إخفاء العناصر النائبة لعناصر المصفوفة الفارغة. القيمة الافتراضية: false

--------------------

> ```
> Example:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.setHidePlaceholders(true);
> ```

**الإرجاع:**
boolean

### setHidePlaceholders(boolean value) {#setHidePlaceholders-boolean-}
```
public abstract void setHidePlaceholders(boolean value)
```

إخفاء العناصر النائبة لعناصر المصفوفة الفارغة. القيمة الافتراضية: false

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
public abstract int getBaseJustification()
```

يحدد المحاذاة العمودية بالنسبة للنص المحيط. القيم الممكنة هي top، bottom، وcenter. القيمة الافتراضية: Center

--------------------

> ```
> Example:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.setBaseJustification(MathVerticalAlignment.Center);
> ```

**الإرجاع:**
int

### setBaseJustification(int value) {#setBaseJustification-int-}
```
public abstract void setBaseJustification(int value)
```

يحدد المحاذاة العمودية بالنسبة للنص المحيط. القيم الممكنة هي top، bottom، وcenter. القيمة الافتراضية: Center

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
public abstract long getMinColumnWidth()
```

الحد الأدنى لعرض العمود بوحدة twips (1/20 نقطة). يتم إضافة الفجوة (المعروفة أيضًا باسم “Column Gap” أو “Gap Width”) إلى MinColumnWidth لتحديد إجمالي تباعد أعمدة المصفوفة (المسافة بين حواف الأعمدة المختلفة). القيمة الافتراضية: 0.

--------------------

> ```
> Example:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.setMinColumnWidth(20);
> ```

**الإرجاع:**
long

### setMinColumnWidth(long value) {#setMinColumnWidth-long-}
```
public abstract void setMinColumnWidth(long value)
```

الحد الأدنى لعرض العمود بوحدة twips (1/20 نقطة). يتم إضافة الفجوة (المعروفة أيضًا باسم “Column Gap” أو “Gap Width”) إلى MinColumnWidth لتحديد إجمالي تباعد أعمدة المصفوفة (المسافة بين حواف الأعمدة المختلفة). القيمة الافتراضية: 0.

--------------------

> ```
> مثال:
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
public abstract int getColumnGapRule()
```

نوع التباعد الأفقي بين أعمدة المصفوفة؛ يمكن أن تكون وحدات التباعد الأفقي إما ems أو نقاط (مخزنة كوحدات twips). القيمة الافتراضية: SingleSpacingGap (0)

--------------------

> ```
> مثال:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.setColumnGapRule(MathSpacingRules.OneAndHalfSpacingGap);
> ```

**الإرجاع:**
int

### setColumnGapRule(int value) {#setColumnGapRule-int-}
```
public abstract void setColumnGapRule(int value)
```

نوع التباعد الأفقي بين أعمدة المصفوفة؛ يمكن أن تكون وحدات التباعد الأفقي إما ems أو نقاط (مخزنة كوحدات twips). القيمة الافتراضية: SingleSpacingGap (0)

--------------------

> ```
> Example:
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
public abstract long getColumnGap()
```

قيمة التباعد الأفقي بين أعمدة المصفوفة؛ إذا تم ضبط ColumnGapRule إلى 3 ("Exactly")، فإن الوحدة تُفسّر كوحدة twips (1/20 نقطة). إذا تم ضبط ColumnGapRule إلى 4 ("Multiple")، فإن الوحدة تُفسّر كعدد من الزيادة 0.5 em. في الحالات الأخرى تُهمل. القيمة الافتراضية: 0

--------------------

> ```
> Example:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.setColumnGapRule(MathSpacingRules.Exactly);
>  matrix.setColumnGap(20);
> ```

**الإرجاع:**
long

### setColumnGap(long value) {#setColumnGap-long-}
```
public abstract void setColumnGap(long value)
```

قيمة التباعد الأفقي بين أعمدة المصفوفة؛ إذا تم ضبط ColumnGapRule إلى 3 ("Exactly")، فإن الوحدة تُفسّر كوحدة twips (1/20 نقطة). إذا تم ضبط ColumnGapRule إلى 4 ("Multiple")، فإن الوحدة تُفسّر كعدد من الزيادة 0.5 em. في الحالات الأخرى تُهمل. القيمة الافتراضية: 0

--------------------

> ```
> Example:
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
public abstract int getRowGapRule()
```

نوع التباعد العمودي بين صفوف المصفوفة؛ يمكن أن تكون وحدات التباعد العمودي خطوطًا أو نقاطًا (مخزنة كوحدات twips). القيمة الافتراضية: SingleSpacingGap (0)

--------------------

> ```
> Example:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.setRowGapRule(MathSpacingRules.OneAndHalfSpacingGap);
> ```

**الإرجاع:**
int

### setRowGapRule(int value) {#setRowGapRule-int-}
```
public abstract void setRowGapRule(int value)
```

نوع التباعد العمودي بين صفوف المصفوفة؛ يمكن أن تكون وحدات التباعد العمودي خطوطًا أو نقاطًا (مخزنة كوحدات twips). القيمة الافتراضية: SingleSpacingGap (0)

--------------------

> ```
> Example:
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
public abstract long getRowGap()
```

قيمة التباعد العمودي بين صفوف المصفوفة؛ إذا تم ضبط RowGapRule إلى 3 ("Exactly")، فإن الوحدة تُفسّر كوحدة twips (1/20 نقطة). إذا تم ضبط RowGapRule إلى 4 ("Multiple")، فإن الوحدة تُفسّر كأنصاف خطوط. القيمة الافتراضية: 0

--------------------

> ```
> مثال:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.setRowGapRule(MathSpacingRules.Exactly);
>  matrix.setRowGap(20);
> ```

**الإرجاع:**
long

### setRowGap(long value) {#setRowGap-long-}
```
public abstract void setRowGap(long value)
```

قيمة التباعد العمودي بين صفوف المصفوفة؛ إذا تم ضبط RowGapRule إلى 3 ("Exactly")، فإن الوحدة تُفسّر كوحدة twips (1/20 نقطة). إذا تم ضبط RowGapRule إلى 4 ("Multiple")، فإن الوحدة تُفسّر كأنصاف خطوط. القيمة الافتراضية: 0

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

### getColumnAlignment(int columnIndex) {#getColumnAlignment-int-}
```
public abstract int getColumnAlignment(int columnIndex)
```

الحصول على المحاذاة الأفقية للعمود المحدد

--------------------

> ```
> مثال:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  MathHorizontalAlignment alignment = matrix.getColumnAlignment(0);
> ```

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| columnIndex | int | فهرس العمود الصفري |

**الإرجاع:**
int - Horizontal Alignment of specified column

### setColumnAlignment(int columnIndex, int val) {#setColumnAlignment-int-int-}
```
public abstract void setColumnAlignment(int columnIndex, int val)
```

تعيين المحاذاة الأفقية للعمود المحدد

--------------------

> ```
> Example:
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
public abstract void setColumnsAlignment(int columnIndex, long columnsCount, int val)
```

تعيين المحاذاة الأفقية للأعمدة المحددة

--------------------

> ```
> Example:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.setColumnAlignment(0, 3, MathHorizontalAlignment.Left);
> ```

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| columnIndex | int | الفهرس الصفري للعمود الأول لتعيين المحاذاة |
| columnsCount | long | عدد الأعمدة التي سيُحدَّد لها المحاذاة |
| val | int | القيمة الجديدة للمحاذاة الأفقية للعمود المحدد |

### insertRowBefore(int rowIndex) {#insertRowBefore-int-}
```
public abstract void insertRowBefore(int rowIndex)
```

إدراج صف جديد قبل الصف المحدد. في البداية جميع عناصر الصف الجديد تكون null.

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
| rowIndex | int | فهرس الصف الذي يسبق مكان إدراج صف جديد |

### insertRowAfter(int rowIndex) {#insertRowAfter-int-}
```
public abstract void insertRowAfter(int rowIndex)
```

إدراج صف جديد بعد الصف المحدد. في البداية جميع عناصر الصف الجديد تكون null.

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
| rowIndex | int | فهرس الصف الذي يلي مكان إدراج صف جديد |

### deleteRow(int rowIndex) {#deleteRow-int-}
```
public abstract void deleteRow(int rowIndex)
```

حذف الصف المحدد

--------------------

> ```
> Example:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.deleteRow(0);
> ```

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| rowIndex | int | الفهرس الصفري للصف الذي سيُحذف. |

### insertColumnBefore(int columnIndex) {#insertColumnBefore-int-}
```
public abstract void insertColumnBefore(int columnIndex)
```

إدراج عمود جديد قبل العمود المحدد. في البداية جميع عناصر العمود الجديد تكون null.

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
| columnIndex | int | فهرس العمود الذي يسبق مكان إدراج عمود جديد |

### insertColumnAfter(int columnIndex) {#insertColumnAfter-int-}
```
public abstract void insertColumnAfter(int columnIndex)
```

إدراج عمود جديد بعد العمود المحدد. في البداية جميع عناصر العمود الجديد تكون null.

--------------------

> ```
> Example:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.insertColumnAfter(0);
> ```

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| columnIndex | int | فهرس العمود الذي يلي مكان إدراج عمود جديد |

### deleteColumn(int columnIndex) {#deleteColumn-int-}
```
public abstract void deleteColumn(int columnIndex)
```

حذف العمود المحدد

--------------------

> ```
> Example:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.deleteColumn(0);
> ```

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| columnIndex | int | الفهرس الصفري للعمود الذي سيُحذف. |