---
title: MathMatrix
second_title: مرجع API Aspose.Slides للغة Java
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

يحدد كائن Matrix، المكوّن من عناصر طفلة مرتَّبة في صفوف وأعمدة واحد أو أكثر. من المهم ملاحظة أن المصفوفات لا تحتوي على محددات مدمجة. لوضع المصفوفة داخل الأقواس يجب عليك استخدام كائن المحدد (IMathDelimiter). يمكن استخدام القيم null لإنشاء فراغات في المصفوفات.

--------------------

> ```
> Example:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.set_Item(0, 0, new MathematicalText("item.1.1"));
> ```
## المُنشئات

| المُنشئ | الوصف |
| --- | --- |
| [MathMatrix(int rowCount, int columnCount)](#MathMatrix-int-int-) | ينشئ مثلاً جديدًا من فئة MathMatrix. |
## الطرق

| الطريقة | الوصف |
| --- | --- |
| [getRowCount()](#getRowCount--) | عدد الصفوف في المصفوفة |
| [getColumnCount()](#getColumnCount--) | عدد الأعمدة في المصفوفة |
| [getHidePlaceholders()](#getHidePlaceholders--) | إخفاء العناصر النائبة لعناصر المصفوفة الفارغة. القيمة الافتراضية: false |
| [setHidePlaceholders(boolean value)](#setHidePlaceholders-boolean-) | إخفاء العناصر النائبة لعناصر المصفوفة الفارغة. القيمة الافتراضية: false |
| [getBaseJustification()](#getBaseJustification--) | يحدد المحاذاة الرأسية بالنسبة للنص المحيط. |
| [setBaseJustification(int value)](#setBaseJustification-int-) | يحدد المحاذاة الرأسية بالنسبة للنص المحيط. |
| [getMinColumnWidth()](#getMinColumnWidth--) | العرض الأدنى للعمود بوحدات twips (1/20 نقطة). يتم إضافة تباعد الفجوة (المعروف أيضًا باسم \u201cColumn Gap\u201d أو \u201cGap Width\u201d) إلى MinColumnWidth لتحديد إجمالي تباعد أعمدة المصفوفة (المسافة بين الحواف المتطابقة للأعمدة المختلفة). |
| [setMinColumnWidth(long value)](#setMinColumnWidth-long-) | العرض الأدنى للعمود بوحدات twips (1/20 نقطة). يتم إضافة تباعد الفجوة (المعروف أيضًا باسم \u201cColumn Gap\u201d أو \u201cGap Width\u201d) إلى MinColumnWidth لتحديد إجمالي تباعد أعمدة المصفوفة (المسافة بين الحواف المتطابقة للأعمدة المختلفة). |
| [getColumnGapRule()](#getColumnGapRule--) | نوع التباعد الأفقي بين أعمدة المصفوفة؛ يمكن أن تكون وحدات التباعد الأفقي إيمز أو نقاط (مخزنة كوحدات twips). |
| [setColumnGapRule(int value)](#setColumnGapRule-int-) | نوع التباعد الأفقي بين أعمدة المصفوفة؛ يمكن أن تكون وحدات التباعد الأفقي إيمز أو نقاط (مخزنة كوحدات twips). |
| [getColumnGap()](#getColumnGap--) | قيمة التباعد الأفقي بين أعمدة المصفوفة؛ إذا تم تعيين ColumnGapRule إلى 3 (\"Exactly\"), فإن الوحدة تُفسَّر بوحدات twips (1/20 نقطة). إذا تم تعيين ColumnGapRule إلى 4 (\"Multiple\"), فإن الوحدة تُفسَّر كعدد من الزيادات 0.5 em. |
| [setColumnGap(long value)](#setColumnGap-long-) | قيمة التباعد الأفقي بين أعمدة المصفوفة؛ إذا تم تعيين ColumnGapRule إلى 3 (\"Exactly\"), فإن الوحدة تُفسَّر بوحدات twips (1/20 نقطة). إذا تم تعيين ColumnGapRule إلى 4 (\"Multiple\"), فإن الوحدة تُفسَّر كعدد من الزيادات 0.5 em. |
| [getRowGapRule()](#getRowGapRule--) | نوع التباعد العمودي بين صفوف المصفوفة؛ يمكن أن تكون وحدات التباعد العمودي سطورًا أو نقاطًا (مخزنة كوحدات twips). |
| [setRowGapRule(int value)](#setRowGapRule-int-) | نوع التباعد العمودي بين صفوف المصفوفة؛ يمكن أن تكون وحدات التباعد العمودي سطورًا أو نقاطًا (مخزنة كوحدات twips). |
| [getRowGap()](#getRowGap--) | قيمة التباعد العمودي بين صفوف المصفوفة؛ إذا تم تعيين RowGapRule إلى 3 (\"Exactly\"), فإن الوحدة تُفسَّر بوحدات twips (1/20 نقطة). إذا تم تعيين RowGapRule إلى 4 (\"Multiple\"), فإن الوحدة تُفسَّر كنصف سطر. |
| [setRowGap(long value)](#setRowGap-long-) | قيمة التباعد العمودي بين صفوف المصفوفة؛ إذا تم تعيين RowGapRule إلى 3 (\"Exactly\"), فإن الوحدة تُفسَّر بوحدات twips (1/20 نقطة). إذا تم تعيين RowGapRule إلى 4 (\"Multiple\"), فإن الوحدة تُفسَّر كنصف سطر. |
| [get_Item(int row, int column)](#get-Item-int-int-) | عنصر من المصفوفة |
| [set_Item(int row, int column, IMathElement value)](#set-Item-int-int-com.aspose.slides.IMathElement-) | عنصر من المصفوفة |
| [getControlCharacterProperties()](#getControlCharacterProperties--) | خصائص حرف التحكم |
| [getColumnAlignment(int columnIndex)](#getColumnAlignment-int-) | الحصول على المحاذاة الأفقية للعمود المحدد |
| [setColumnAlignment(int columnIndex, int val)](#setColumnAlignment-int-int-) | تعيين المحاذاة الأفقية للعمود المحدد |
| [setColumnsAlignment(int columnIndex, long columnsCount, int val)](#setColumnsAlignment-int-long-int-) | تعيين المحاذاة الأفقية للأعمدة المحددة |
| [insertRowBefore(int rowIndex)](#insertRowBefore-int-) | إدراج صف جديد قبل المحدد. في البداية جميع العناصر في الصف الجديد هي null. |
| [insertRowAfter(int rowIndex)](#insertRowAfter-int-) | إدراج صف جديد بعد المحدد. في البداية جميع العناصر في الصف الجديد هي null. |
| [deleteRow(int rowIndex)](#deleteRow-int-) | حذف الصف المحدد |
| [insertColumnBefore(int columnIndex)](#insertColumnBefore-int-) | إدراج عمود جديد قبل المحدد. في البداية جميع العناصر في العمود الجديد هي null. |
| [insertColumnAfter(int columnIndex)](#insertColumnAfter-int-) | إدراج عمود جديد بعد المحدد. في البداية جميع العناصر في العمود الجديد هي null. |
| [deleteColumn(int columnIndex)](#deleteColumn-int-) | حذف العمود المحدد |
| [getChildren()](#getChildren--) | الحصول على العناصر الفرعية |
### MathMatrix(int rowCount, int columnCount) {#MathMatrix-int-int-}
```
public MathMatrix(int rowCount, int columnCount)
```

ينشئ مثلاً جديدًا من فئة MathMatrix.

--------------------

> ```
> Example:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
> ```

**المعاملات:**
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

إخفاء العناصر النائبة لعناصر المصفوفة الفارغة. القيمة الافتراضية: false

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

إخفاء العناصر النائبة لعناصر المصفوفة الفارغة. القيمة الافتراضية: false

--------------------

> ```
> Example:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.setHidePlaceholders(true);
> ```

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | int |  |

### getBaseJustification() {#getBaseJustification--}
```
public final int getBaseJustification()
```

يحدد المحاذاة الرأسية بالنسبة للنص المحيط. القيم الممكنة هي top, bottom, و center. القيمة الافتراضية: Center

--------------------

> ```
> Example:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.setBaseJustification(MathVerticalAlignment.Center);
> ```

**القيمة المرجعة:**
int
### setBaseJustification(int value) {#setBaseJustification-int-}
```
public final void setBaseJustification(int value)
```

يحدد المحاذاة الرأسية بالنسبة للنص المحيط. القيم الممكنة هي top, bottom, و center. القيمة الافتراضية: Center

--------------------

> ```
> Example:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.setBaseJustification(MathVerticalAlignment.Center);
> ```

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | int |  |

### getMinColumnWidth() {#getMinColumnWidth--}
```
public final long getMinColumnWidth()
```

العرض الأدنى للعمود بوحدات twips (1/20 نقطة). يتم إضافة تباعد الفجوة (المعروف أيضًا باسم \u201cColumn Gap\u201d أو \u201cGap Width\u201d) إلى MinColumnWidth لتحديد إجمالي تباعد أعمدة المصفوفة (المسافة بين الحواف المتطابقة للأعمدة المختلفة). القيمة الافتراضية: 0.

--------------------

> ```
> Example:
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

العرض الأدنى للعمود بوحدات twips (1/20 نقطة). يتم إضافة تباعد الفجوة (المعروف أيضًا باسم \u201cColumn Gap\u201d أو \u201cGap Width\u201d) إلى MinColumnWidth لتحديد إجمالي تباعد أعمدة المصفوفة (المسافة بين الحواف المتطابقة للأعمدة المختلفة). القيمة الافتراضية: 0.

--------------------

> ```
> Example:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.setMinColumnWidth(20);
> ```

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | long |  |

### getColumnGapRule() {#getColumnGapRule--}
```
public final int getColumnGapRule()
```

نوع التباعد الأفقي بين أعمدة المصفوفة؛ يمكن أن تكون وحدات التباعد الأفقي إيمز أو نقاط (مخزنة كوحدات twips). القيمة الافتراضية: SingleSpacingGap (0)

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

نوع التباعد الأفقي بين أعمدة المصفوفة؛ يمكن أن تكون وحدات التباعد الأفقي إيمز أو نقاط (مخزنة كوحدات twips). القيمة الافتراضية: SingleSpacingGap (0)

--------------------

> ```
> Example:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.setColumnGapRule(MathSpacingRules.OneAndHalfSpacingGap);
> ```

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | int |  |

### getColumnGap() {#getColumnGap--}
```
public final long getColumnGap()
```

قيمة التباعد الأفقي بين أعمدة المصفوفة؛ إذا تم تعيين ColumnGapRule إلى 3 (\"Exactly\"), فإن الوحدة تُفسَّر بوحدات twips (1/20 نقطة). إذا تم تعيين ColumnGapRule إلى 4 (\"Multiple\"), فإن الوحدة تُفسَّر كعدد من الزيادات 0.5 em. في الحالات الأخرى يتم التجاهل. القيمة الافتراضية: 0

--------------------

> ```
> مثال:
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

قيمة التباعد الأفقي بين أعمدة المصفوفة؛ إذا تم تعيين ColumnGapRule إلى 3 (\"Exactly\"), فإن الوحدة تُفسَّر بوحدات twips (1/20 نقطة). إذا تم تعيين ColumnGapRule إلى 4 (\"Multiple\"), فإن الوحدة تُفسَّر كعدد من الزيادات 0.5 em. في الحالات الأخرى يتم التجاهل. القيمة الافتراضية: 0

--------------------

> ```
> Example:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.setColumnGapRule(MathSpacingRules.Exactly);
>  matrix.setColumnGap(20);
> ```

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | long |  |

### getRowGapRule() {#getRowGapRule--}
```
public final int getRowGapRule()
```

نوع التباعد العمودي بين صفوف المصفوفة؛ يمكن أن تكون وحدات التباعد العمودي سطورًا أو نقاطًا (مخزنة كوحدات twips). القيمة الافتراضية: SingleSpacingGap (0)

--------------------

> ```
> مثال:
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

نوع التباعد العمودي بين صفوف المصفوفة؛ يمكن أن تكون وحدات التباعد العمودي سطورًا أو نقاطًا (مخزنة كوحدات twips). القيمة الافتراضية: SingleSpacingGap (0)

--------------------

> ```
> مثال:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.setRowGapRule(MathSpacingRules.OneAndHalfSpacingGap);
> ```

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | int |  |

### getRowGap() {#getRowGap--}
```
public final long getRowGap()
```

قيمة التباعد العمودي بين صفوف المصفوفة؛ إذا تم تعيين RowGapRule إلى 3 (\"Exactly\"), فإن الوحدة تُفسَّر بوحدات twips (1/20 نقطة). إذا تم تعيين RowGapRule إلى 4 (\"Multiple\"), فإن الوحدة تُفسَّر كأنصاف سطور. القيمة الافتراضية: 0

--------------------

> ```
> مثال:
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

قيمة التباعد العمودي بين صفوف المصفوفة؛ إذا تم تعيين RowGapRule إلى 3 (\"Exactly\"), فإن الوحدة تُفسَّر بوحدات twips (1/20 نقطة). إذا تم تعيين RowGapRule إلى 4 (\"Multiple\"), فإن الوحدة تُفسَّر كأنصاف سطور. القيمة الافتراضية: 0

--------------------

> ```
> Example:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.setRowGapRule(MathSpacingRules.Exactly);
>  matrix.setRowGap(20);
> ```

**المعاملات:**
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
> Example:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.set_Item(0, 0, new MathematicalText("item.1.1"));
> ```

**المعاملات:**
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
> Example:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.set_Item(0, 0, new MathematicalText("item.1.1"));
> ```


**المعاملات:**
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

**المعاملات:**
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
> Example:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.setColumnAlignment(0, MathHorizontalAlignment.Left);
> ```

**المعاملات:**
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
> مثال:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.setColumnAlignment(0, 3, MathHorizontalAlignment.Left);
> ```

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| columnIndex | int | الفهرس الصفري للعمود الأول لتعيين المحاذاة |
| columnsCount | long | عدد الأعمدة لتحديد المحاذاة |
| val | int | القيمة الجديدة للمحاذاة الأفقية للعمود المحدد |

### insertRowBefore(int rowIndex) {#insertRowBefore-int-}
```
public final void insertRowBefore(int rowIndex)
```

إدراج صف جديد قبل المحدد. في البداية جميع العناصر في الصف الجديد هي null.

--------------------

> ```
> Example:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.insertRowBefore(1);
> ```

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| rowIndex | int | الفهرس للصف قبل إدراج صف جديد أمامه |

### insertRowAfter(int rowIndex) {#insertRowAfter-int-}
```
public final void insertRowAfter(int rowIndex)
```

إدراج صف جديد بعد المحدد. في البداية جميع العناصر في الصف الجديد هي null.

--------------------

> ```
> Example:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.insertRowAfter(1);
> ```

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| rowIndex | int | الفهرس للصف بعده يتم إدراج صف جديد |

### deleteRow(int rowIndex) {#deleteRow-int-}
```
public final void deleteRow(int rowIndex)
```

حذف الصف المحدد

--------------------

> ```
> Example:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.deleteRow(0);
> ```

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| rowIndex | int | الفهرس الصفري للصف لحذف العنصر. |

### insertColumnBefore(int columnIndex) {#insertColumnBefore-int-}
```
public final void insertColumnBefore(int columnIndex)
```

إدراج عمود جديد قبل المحدد. في البداية جميع العناصر في العمود الجديد هي null.

--------------------

> ```
> مثال:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.insertColumnBefore(0);
> ```

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| columnIndex | int | الفهرس للعمود قبل إدراج عمود جديد أمامه |

### insertColumnAfter(int columnIndex) {#insertColumnAfter-int-}
```
public final void insertColumnAfter(int columnIndex)
```

إدراج عمود جديد بعد المحدد. في البداية جميع العناصر في العمود الجديد هي null.

--------------------

> ```
> Example:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.insertColumnAfter(0);
> ```

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| columnIndex | int | الفهرس للعمود بعده يتم إدراج عمود جديد |

### deleteColumn(int columnIndex) {#deleteColumn-int-}
```
public final void deleteColumn(int columnIndex)
```

حذف العمود المحدد

--------------------

> ```
> Example:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.deleteColumn(0);
> ```

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| columnIndex | int | الفهرس الصفري للعمود لحذف العنصر. |

### getChildren() {#getChildren--}
```
public final IMathElement[] getChildren()
```

الحصول على العناصر الفرعية

**القيمة المرجعة:**
com.aspose.slides.IMathElement[]