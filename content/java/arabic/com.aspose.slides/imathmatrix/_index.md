---
title: IMathMatrix
second_title: مرجع API لـ Aspose.Slides للغة Java
description: يحدد كائن Matrix المكوّن من عناصر فرعية مُرتبة في صف واحد أو أكثر وأعمدة.
type: docs
url: /ar/com.aspose.slides/imathmatrix/
---
**جميع الواجهات المنفذة:**
[com.aspose.slides.IMathElement](../../com.aspose.slides/imathelement)
```
public interface IMathMatrix extends IMathElement
```

يحدد كائن Matrix، المؤلف من عناصر فرعية مرتبة في صفوف وأعمدة واحدة أو أكثر. من المهم ملاحظة أن المصفوفات لا تحتوي على فواصل مدمجة. لوضع المصفوفة داخل القوسين يجب استخدام كائن الفاصل (IMathDelimiter). يمكن استخدام قيم null لإنشاء فراغات في المصفوفات.

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
| [getHidePlaceholders()](#getHidePlaceholders--) | إخفاء عناصر الحجز لعناصر المصفوفة الفارغة الإعداد الافتراضي: false |
| [setHidePlaceholders(boolean value)](#setHidePlaceholders-boolean-) | إخفاء عناصر الحجز لعناصر المصفوفة الفارغة الإعداد الافتراضي: false |
| [getBaseJustification()](#getBaseJustification--) | يحدد المحاذاة الرأسية بالنسبة للنص المحيط. |
| [setBaseJustification(int value)](#setBaseJustification-int-) | يحدد المحاذاة الرأسية بالنسبة للنص المحيط. |
| [getMinColumnWidth()](#getMinColumnWidth--) | الحد الأدنى لعرض العمود بوحدة twips (1/20 من النقطة) يتم إضافة مساحة الفجوة (المعروفة أيضًا بـ \\u201cColumn Gap\\u201d أو \\u201cGap Width\\u201d) إلى MinColumnWidth لتحديد إجمالي تباعد أعمدة المصفوفة (المسافة بين الحواف المتطابقة للأعمدة المختلفة). |
| [setMinColumnWidth(long value)](#setMinColumnWidth-long-) | الحد الأدنى لعرض العمود بوحدة twips (1/20 من النقطة) يتم إضافة مساحة الفجوة (المعروفة أيضًا بـ \\u201cColumn Gap\\u201d أو \\u201cGap Width\\u201d) إلى MinColumnWidth لتحديد إجمالي تباعد أعمدة المصفوفة (المسافة بين الحواف المتطابقة للأعمدة المختلفة). |
| [getColumnGapRule()](#getColumnGapRule--) | نوع التباعد الأفقي بين أعمدة المصفوفة؛ يمكن أن تكون وحدات التباعد الأفقية ems أو نقاط (مخزنة كوحدات twips). |
| [setColumnGapRule(int value)](#setColumnGapRule-int-) | نوع التباعد الأفقي بين أعمدة المصفوفة؛ يمكن أن تكون وحدات التباعد الأفقية ems أو نقاط (مخزنة كوحدات twips). |
| [getColumnGap()](#getColumnGap--) | قيمة التباعد الأفقي بين أعمدة المصفوفة؛ إذا تم تعيين ColumnGapRule إلى 3 ("Exactly")، فسيتم تفسير الوحدة كوحدة twips (1/20 من النقطة)؛ إذا تم تعيين ColumnGapRule إلى 4 ("Multiple")، فسيتم تفسير الوحدة كعدد من الزيادات 0.5 em. في حالات أخرى يتم تجاهلها. الإعداد الافتراضي: 0 |
| [setColumnGap(long value)](#setColumnGap-long-) | قيمة التباعد الأفقي بين أعمدة المصفوفة؛ إذا تم تعيين ColumnGapRule إلى 3 ("Exactly")، فسيتم تفسير الوحدة كوحدة twips (1/20 من النقطة)؛ إذا تم تعيين ColumnGapRule إلى 4 ("Multiple")، فسيتم تفسير الوحدة كعدد من الزيادات 0.5 em. في حالات أخرى يتم تجاهلها. الإعداد الافتراضي: 0 |
| [getRowGapRule()](#getRowGapRule--) | نوع التباعد الرأسي بين صفوف المصفوفة؛ يمكن أن تكون وحدات التباعد الرأسي خطوطًا أو نقاطًا (مخزنة بوحدة twips). |
| [setRowGapRule(int value)](#setRowGapRule-int-) | نوع التباعد الرأسي بين صفوف المصفوفة؛ يمكن أن تكون وحدات التباعد الرأسي خطوطًا أو نقاطًا (مخزنة بوحدة twips). |
| [getRowGap()](#getRowGap--) | قيمة التباعد الرأسي بين صفوف المصفوفة؛ إذا تم تعيين RowGapRule إلى 3 ("Exactly")، فسيتم تفسير الوحدة كوحدة twips (1/20 من النقطة)؛ إذا تم تعيين RowGapRule إلى 4 ("Multiple")، فسيتم تفسير الوحدة كنصف خطوط. الإعداد الافتراضي: 0 |
| [setRowGap(long value)](#setRowGap-long-) | قيمة التباعد الرأسي بين صفوف المصفوفة؛ إذا تم تعيين RowGapRule إلى 3 ("Exactly")، فسيتم تفسير الوحدة كوحدة twips (1/20 من النقطة)؛ إذا تم تعيين RowGapRule إلى 4 ("Multiple")، فسيتم تفسير الوحدة كنصف خطوط. الإعداد الافتراضي: 0 |
| [getColumnAlignment(int columnIndex)](#getColumnAlignment-int-) | الحصول على المحاذاة الأفقية للعمود المحدد |
| [setColumnAlignment(int columnIndex, int val)](#setColumnAlignment-int-int-) | تعيين المحاذاة الأفقية للعمود المحدد |
| [setColumnsAlignment(int columnIndex, long columnsCount, int val)](#setColumnsAlignment-int-long-int-) | تعيين المحاذاة الأفقية للأعمدة المحددة |
| [insertRowBefore(int rowIndex)](#insertRowBefore-int-) | إدراج صف جديد قبل الصف المحدد. في البداية تكون جميع عناصر الصف الجديد قيمتها null. |
| [insertRowAfter(int rowIndex)](#insertRowAfter-int-) | إدراج صف جديد بعد الصف المحدد. في البداية تكون جميع عناصر الصف الجديد قيمتها null. |
| [deleteRow(int rowIndex)](#deleteRow-int-) | حذف الصف المحدد |
| [insertColumnBefore(int columnIndex)](#insertColumnBefore-int-) | إدراج عمود جديد قبل العمود المحدد. في البداية تكون جميع عناصر العمود الجديد قيمتها null. |
| [insertColumnAfter(int columnIndex)](#insertColumnAfter-int-) | إدراج عمود جديد بعد العمود المحدد. في البداية تكون جميع عناصر العمود الجديد قيمتها null. |
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
| row | int | فهرس الصف (يبدأ من الصفر) للحصول على العنصر |
| column | int | فهرس العمود (يبدأ من الصفر) للحصول على العنصر |

**القيمة المرجعة:**
[IMathElement](../../com.aspose.slides/imathelement) - IMathElement

### set_Item(int row, int column, IMathElement value) {#set-Item-int-int-com.aspose.slides.IMathElement-}
```
public abstract void set_Item(int row, int column, IMathElement value)
```

عناصر المصفوفة

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
| row | int | فهرس الصف (يبدأ من الصفر) للحصول على العنصر |
| column | int | فهرس العمود (يبدأ من الصفر) للحصول على العنصر |
| value | [IMathElement](../../com.aspose.slides/imathelement) |  |

### getRowCount() {#getRowCount--}
```
public abstract int getRowCount()
```

عدد الصفوف في المصفوفة

--------------------

> ```
> مثال:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  int rowCount = matrix.getRowCount();
> ```

**القيمة المرجعة:**
int

### getColumnCount() {#getColumnCount--}
```
public abstract int getColumnCount()
```

عدد الأعمدة في المصفوفة

--------------------

> ```
> مثال:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  int columnCount = matrix.getColumnCount();
> ```

**القيمة المرجعة:**
int

### getHidePlaceholders() {#getHidePlaceholders--}
```
public abstract boolean getHidePlaceholders()
```

إخفاء عناصر الحجز لعناصر المصفوة الفارغة الإعداد الافتراضي: false

--------------------

> ```
> مثال:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.setHidePlaceholders(true);
> ```

**القيمة المرجعة:**
boolean

### setHidePlaceholders(boolean value) {#setHidePlaceholders-boolean-}
```
public abstract void setHidePlaceholders(boolean value)
```

إخفاء عناصر الحجز لعناصر المصفوة الفارغة الإعداد الافتراضي: false

--------------------

> ```
> مثال:
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

يحدد المحاذاة الرأسية بالنسبة للنص المحيط. القيم الممكنة هي top, bottom, و center. الإعداد الافتراضي: Center

--------------------

> ```
> مثال:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.setBaseJustification(MathVerticalAlignment.Center);
> ```

**القيمة المرجعة:**
int

### setBaseJustification(int value) {#setBaseJustification-int-}
```
public abstract void setBaseJustification(int value)
```

يحدد المحاذاة الرأسية بالنسبة للنص المحيط. القيم الممكنة هي top, bottom, و center. الإعداد الافتراضي: Center

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

الحد الأدنى لعرض العمود بوحدة twips (1/20 من النقطة) يتم إضافة مساحة الفجوة (المعروفة أيضًا بـ \\u201cColumn Gap\\u201d أو \\u201cGap Width\\u201d) إلى MinColumnWidth لتحديد إجمالي تباعد أعمدة المصفوفة (المسافة بين الحواف المتطابقة للأعمدة المختلفة). الإعداد الافتراضي: 0.

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
public abstract void setMinColumnWidth(long value)
```

الحد الأدنى لعرض العمود بوحدة twips (1/20 من النقطة) يتم إضافة مساحة الفجوة (المعروفة أيضًا بـ \\u201cColumn Gap\\u201d أو \\u201cGap Width\\u201d) إلى MinColumnWidth لتحديد إجمالي تباعد أعمدة المصفوفة (المسافة بين الحواف المتطابقة للأعمدة المختلفة). الإعداد الافتراضي: 0.

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

نوع التباعد الأفقي بين أعمدة المصفوفة؛ يمكن أن تكون وحدات التباعد الأفقية ems أو نقاط (مخزنة كوحدات twips). الإعداد الافتراضي: SingleSpacingGap (0)

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
public abstract void setColumnGapRule(int value)
```

نوع التباعد الأفقي بين أعمدة المصفوفة؛ يمكن أن تكون وحدات التباعد الأفقية ems أو نقاط (مخزنة كوحدات twips). الإعداد الافتراضي: SingleSpacingGap (0)

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
public abstract long getColumnGap()
```

قيمة التباعد الأفقي بين أعمدة المصفوفة؛ إذا تم تعيين ColumnGapRule إلى 3 ("Exactly")، فسيتم تفسير الوحدة كوحدة twips (1/20 من النقطة)؛ إذا تم تعيين ColumnGapRule إلى 4 ("Multiple")، فسيتم تفسير الوحدة كعدد من الزيادات 0.5 em. في حالات أخرى يتم تجاهلها. الإعداد الافتراضي: 0

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
public abstract void setColumnGap(long value)
```

قيمة التباعد الأفقي بين أعمدة المصفوفة؛ إذا تم تعيين ColumnGapRule إلى 3 ("Exactly")، فسيتم تفسير الوحدة كوحدة twips (1/20 من النقطة)؛ إذا تم تعيين ColumnGapRule إلى 4 ("Multiple")، فسيتم تفسير الوحدة كعدد من الزيادات 0.5 em. في حالات أخرى يتم تجاهلها. الإعداد الافتراضي: 0

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
public abstract int getRowGapRule()
```

نوع التباعد الرأسي بين صفوف المصفوفة؛ يمكن أن تكون وحدات التباعد الرأسي خطوطًا أو نقاطًا (مخزنة بوحدة twips). الإعداد الافتراضي: SingleSpacingGap (0)

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
public abstract void setRowGapRule(int value)
```

نوع التباعد الرأسي بين صفوف المصفوفة؛ يمكن أن تكون وحدات التباعد الرأسي خطوطًا أو نقاطًا (مخزنة بوحدة twips). الإعداد الافتراضي: SingleSpacingGap (0)

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
public abstract long getRowGap()
```

قيمة التباعد الرأسي بين صفوف المصفوفة؛ إذا تم تعيين RowGapRule إلى 3 ("Exactly")، فسيتم تفسير الوحدة كوحدة twips (1/20 من النقطة)؛ إذا تم تعيين RowGapRule إلى 4 ("Multiple")، فسيتم تفسير الوحدة كنصف خطوط. الإعداد الافتراضي: 0

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
public abstract void setRowGap(long value)
```

قيمة التباعد الرأسي بين صفوف المصفوفة؛ إذا تم تعيين RowGapRule إلى 3 ("Exactly")، فسيتم تفسير الوحدة كوحدة twips (1/20 من النقطة)؛ إذا تم تعيين RowGapRule إلى 4 ("Multiple")، فسيتم تفسير الوحدة كنصف خطوط. الإعداد الافتراضي: 0

--------------------

> ```
> مثال:
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
| columnIndex | int | فهرس العمود (يبدأ من الصفر) |

**القيمة المرجعة:**
int - المحاذاة الأفقية للعمود المحدد

### setColumnAlignment(int columnIndex, int val) {#setColumnAlignment-int-int-}
```
public abstract void setColumnAlignment(int columnIndex, int val)
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
| columnIndex | int | فهرس العمود (يبدأ من الصفر) |
| val | int | القيمة الجديدة للمحاذاة الأفقية للعمود المحدد |

### setColumnsAlignment(int columnIndex, long columnsCount, int val) {#setColumnsAlignment-int-long-int-}
```
public abstract void setColumnsAlignment(int columnIndex, long columnsCount, int val)
```

تعيين المحاذاة الأفقية للأعمدة المحددة

--------------------

> ```
> مثال:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.setColumnAlignment(0, 3, MathHorizontalAlignment.Left);
> ```

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| columnIndex | int | فهرس العمود (يبدأ من الصفر) للعمود الأول لتعيين المحاذاة |
| columnsCount | long | عدد الأعمدة التي سيتم تحديد المحاذاة لها |
| val | int | القيمة الجديدة للمحاذاة الأفقية للعمود المحدد |

### insertRowBefore(int rowIndex) {#insertRowBefore-int-}
```
public abstract void insertRowBefore(int rowIndex)
```

إدراج صف جديد قبل الصف المحدد. في البداية تكون جميع عناصر الصف الجديد قيمتها null.

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
| rowIndex | int | فهرس الصف قبل الذي سيتم إدراج صف جديد قبله |

### insertRowAfter(int rowIndex) {#insertRowAfter-int-}
```
public abstract void insertRowAfter(int rowIndex)
```

إدراج صف جديد بعد الصف المحدد. في البداية تكون جميع عناصر الصف الجديد قيمتها null.

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
| rowIndex | int | فهرس الصف بعد الذي سيتم إدراج صف جديد بعده |

### deleteRow(int rowIndex) {#deleteRow-int-}
```
public abstract void deleteRow(int rowIndex)
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
| rowIndex | int | فهرس الصف (يبدأ من الصفر) الذي سيتم حذفه. |

### insertColumnBefore(int columnIndex) {#insertColumnBefore-int-}
```
public abstract void insertColumnBefore(int columnIndex)
```

إدراج عمود جديد قبل العمود المحدد. في البداية تكون جميع عناصر العمود الجديد قيمتها null.

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
| columnIndex | int | فهرس العمود قبل الذي سيتم إدراج عمود جديد قبله |

### insertColumnAfter(int columnIndex) {#insertColumnAfter-int-}
```
public abstract void insertColumnAfter(int columnIndex)
```

إدراج عمود جديد بعد العمود المحدد. في البداية تكون جميع عناصر العمود الجديد قيمتها null.

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
| columnIndex | int | فهرس العمود بعد الذي سيتم إدراج عمود جديد بعده |

### deleteColumn(int columnIndex) {#deleteColumn-int-}
```
public abstract void deleteColumn(int columnIndex)
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
| columnIndex | int | فهرس العمود (يبدأ من الصفر) الذي سيتم حذفه. |