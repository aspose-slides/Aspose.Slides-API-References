---
title: MathBox
second_title: Aspose.Slides for Android عبر مرجع API لجافا
description: يحدد عملية التغليف المنطقي للعنصر الرياضي.
type: docs
url: /ar/com.aspose.slides/mathbox/
---
**Inheritance:**
java.lang.Object, [com.aspose.slides.MathElementBase](../../com.aspose.slides/mathelementbase)

**All Implemented Interfaces:**
[com.aspose.slides.IMathBox](../../com.aspose.slides/imathbox), com.aspose.slides.IHasControlCharacterProperties
```
public final class MathBox extends MathElementBase implements IMathBox, IHasControlCharacterProperties
```

Specifies the logical boxing (packaging) of mathematical element. For example, a boxed object can serve as an operator emulator with or without an alignment point, serve as a line break point, or be grouped such as not to allow line breaks within. For example, the "==" operator should be boxed to prevent line breaks.

--------------------

> ```
> Example:
>  
>  MathBox box = new MathBox(new MathematicalText("=="));
> ```
## المُنشئات

| المُنشئ | الوصف |
| --- | --- |
| [MathBox(IMathElement element)](#MathBox-com.aspose.slides.IMathElement-) | يُهيئ MathBox بالعنصر المحدد كمعامل |
## الطرق

| الطريقة | الوصف |
| --- | --- |
| [getBase()](#getBase--) | الوسيط الأساسي |
| [getOperatorEmulator()](#getOperatorEmulator--) | محاكي المشغل. |
| [setOperatorEmulator(boolean value)](#setOperatorEmulator-boolean-) | محاكي المشغل. |
| [getNoBreak()](#getNoBreak--) | عدم الانقسام. تُحدد هذه الخاصية الخاصية "unbreakable" على صندوق الكائن. |
| [setNoBreak(boolean value)](#setNoBreak-boolean-) | عدم الانقسام. تُحدد هذه الخاصية الخاصية "unbreakable" على صندوق الكائن. |
| [getDifferential()](#getDifferential--) | تفاضل عندما يكون true، الصندوق يعمل كعملية تفاضل (مثال، \\ud835\\udc51\\ud835\\udc65 في تكامل)، ويتلقى التباعد الأفقي المناسب للّتفاضل الرياضي. |
| [setDifferential(boolean value)](#setDifferential-boolean-) | تفاضل عندما يكون true، الصندوق يعمل كعملية تفاضل (مثال، \\ud835\\udc51\\ud835\\udc65 في تكامل)، ويتلقى التباعد الأفقي المناسب للّتفاضل الرياضي. |
| [getAlignmentPoint()](#getAlignmentPoint--) | عندما يكون true، يعمل هذا محاكي المشغل كنقطة محاذاة؛ أي أن نقاط المحاذاة المحددة في معادلات أخرى يمكن محاذاتها معه. |
| [setAlignmentPoint(boolean value)](#setAlignmentPoint-boolean-) | عندما يكون true، يعمل هذا محاكي المشغل كنقطة محاذاة؛ أي أن نقاط المحاذاة المحددة في معادلات أخرى يمكن محاذاتها معه. |
| [getExplicitBreak()](#getExplicitBreak--) | الكسر الصريح يُحدد ما إذا كان هناك فاصل سطر في بداية كائن Box، بحيث يُلف السطر عند بداية كائن الصندوق. |
| [setExplicitBreak(byte value)](#setExplicitBreak-byte-) | الكسر الصريح يُحدد ما إذا كان هناك فاصل سطر في بداية كائن Box، بحيث يُلف السطر عند بداية كائن الصندوق. |
| [getChildren()](#getChildren--) | إرجاع عناصر الأطفال |
| [getControlCharacterProperties()](#getControlCharacterProperties--) | خصائص أحرف التحكم |

### MathBox(IMathElement element) {#MathBox-com.aspose.slides.IMathElement-}
```
public MathBox(IMathElement element)
```

يُهيئ MathBox بالعنصر المحدد كمعامل

--------------------

> ```
> Example:
>  
>  MathBox box = new MathBox(new MathematicalText("=="));
> ```

**المُعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| element | [IMathElement](../../com.aspose.slides/imathelement) | العنصر الأساسي الذي يُطبق الصندوق عليه. يمكن أن يكون null. |

### getBase() {#getBase--}
```
public final IMathElement getBase()
```

الوسيط الأساسي

--------------------

> ```
> Example:
>  
>  MathBox box = new MathBox(new MathematicalText("=="));
>  IMathElement base = box.getBase();
> ```

**القيمة المرجعة:**
[IMathElement](../../com.aspose.slides/imathelement)
### getOperatorEmulator() {#getOperatorEmulator--}
```
public final boolean getOperatorEmulator()
```

محاكي المشغل. عندما يكون true، الصندوق ومحتوياته يتصرفان كعامل واحد ويرثان خصائص العامل. هذا يعني، على سبيل المثال، أن الحرف يمكن أن يكون نقطة لفاصل سطر ويمكن محاذاته إلى عوامل أخرى. يُستخدم محاكي المشغل غالبًا عندما يتحد رمز أو أكثر لتشكيل عامل، مثل '=='. القيمة الافتراضية: false

--------------------

> ```
> Example:
>  
>  MathBox box = new MathBox(new MathematicalText("=="));
>  box.setOperatorEmulator(true);
> ```

**القيمة المرجعة:**
boolean
### setOperatorEmulator(boolean value) {#setOperatorEmulator-boolean-}
```
public final void setOperatorEmulator(boolean value)
```

محاكي المشغل. عندما يكون true، الصندوق ومحتوياته يتصرفان كعامل واحد ويرثان خصائص العامل. هذا يعني، على سبيل المثال، أن الحرف يمكن أن يكون نقطة لفاصل سطر ويمكن محاذاته إلى عوامل أخرى. يُستخدم محاكي المشغل غالبًا عندما يتحد رمز أو أكثر لتشكيل عامل، مثل '=='. القيمة الافتراضية: false

--------------------

> ```
> Example:
>  
>  MathBox box = new MathBox(new MathematicalText("=="));
>  box.setOperatorEmulator(true);
> ```

**المُعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | boolean |  |

### getNoBreak() {#getNoBreak--}
```
public final boolean getNoBreak()
```

عدم الانقسام. تُحدد هذه الخاصية الخاصية "unbreakable" على صندوق الكائن. عندما يكون true، لا يمكن حدوث فواصل سطر داخل الصندوق. قد يكون هذا مهمًا لمحاكيات المشغل التي تتكون من أكثر من عامل ثنائي. عندما لا يُحدد هذا العنصر، يمكن حدوث فواصل داخل الصندوق. القيمة الافتراضية: true

--------------------

> ```
> Example:
>  
>  MathBox box = new MathBox(new MathematicalText("*****"));
>  box.setNoBreak(false);
> ```

**القيمة المرجعة:**
boolean
### setNoBreak(boolean value) {#setNoBreak-boolean-}
```
public final void setNoBreak(boolean value)
```

عدم الانقسام. تُحدد هذه الخاصية الخاصية "unbreakable" على صندوق الكائن. عندما يكون true، لا يمكن حدوث فواصل سطر داخل الصندوق. قد يكون هذا مهمًا لمحاكيات المشغل التي تتكون من أكثر من عامل ثنائي. عندما لا يُحدد هذا العنصر، يمكن حدوث فواصل داخل الصندوق. القيمة الافتراضية: true

--------------------

> ```
> Example:
>  
>  MathBox box = new MathBox(new MathematicalText("*****"));
>  box.setNoBreak(false);
> ```

**المُعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | boolean |  |

### getDifferential() {#getDifferential--}
```
public final boolean getDifferential()
```

تفاضل عندما يكون true، الصندوق يعمل كعملية تفاضل (مثال، \\ud835\\udc51\\ud835\\udc65 في تكامل)، ويتلقى التباعد الأفقي المناسب للّتفاضل الرياضي. القيمة الافتراضية: false

--------------------

> ```
> Example:
>  
>  IMathBox differential = new MathematicalText("dx").toBox();
>  differential.setDifferential(true);
>  IMathBlock baseArg = new MathematicalText("x").join(differential);
>  IMathNaryOperator integral = baseArg.integral(MathIntegralTypes.Simple, "0", "1");
> ```

**القيمة المرجعة:**
boolean
### setDifferential(boolean value) {#setDifferential-boolean-}
```
public final void setDifferential(boolean value)
```

تفاضل عندما يكون true، الصندوق يعمل كعملية تفاضل (مثال، \\ud835\\udc51\\ud835\\udc65 في تكامل)، ويتلقى التباعد الأفقي المناسب للّتفاضل الرياضي. القيمة الافتراضية: false

--------------------

> ```
> Example:
>  
>  IMathBox differential = new MathematicalText("dx").toBox();
>  differential.setDifferential(true);
>  IMathBlock baseArg = new MathematicalText("x").join(differential);
>  IMathNaryOperator integral = baseArg.integral(MathIntegralTypes.Simple, "0", "1");
> ```

**المُعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | boolean |  |

### getAlignmentPoint() {#getAlignmentPoint--}
```
public final boolean getAlignmentPoint()
```

عندما يكون true، يعمل هذا محاكي المشغل كنقطة محاذاة؛ أي أن نقاط المحاذاة المحددة في معادلات أخرى يمكن محاذاتها معه. القيمة الافتراضية: false

--------------------

> ```
> Example:
>  
>  IMathBox box = new MathematicalText("==").toBox();
>  box.setAlignmentPoint(true);
> ```

**القيمة المرجعة:**
boolean
### setAlignmentPoint(boolean value) {#setAlignmentPoint-boolean-}
```
public final void setAlignmentPoint(boolean value)
```

عندما يكون true، يعمل هذا محاكي المشغل كنقطة محاذاة؛ أي أن نقاط المحاذاة المحددة في معادلات أخرى يمكن محاذاتها معه. القيمة الافتراضية: false

--------------------

> ```
> Example:
>  
>  IMathBox box = new MathematicalText("==").toBox();
>  box.setAlignmentPoint(true);
> ```

**المُعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | boolean |  |

### getExplicitBreak() {#getExplicitBreak--}
```
public final byte getExplicitBreak()
```

الكسر الصريح يُحدد ما إذا كان هناك فاصل سطر في بداية كائن Box، بحيث يُلف السطر عند بداية كائن الصندوق. يحدد عدد العامل في السطر السابق للنص الرياضي الذي يُستخدم كنقطة محاذاة للسطر الحالي للنص الرياضي. القيم الممكنة: 1..255 القيمة الافتراضية: 0 (بدون كسر صريح)

--------------------

> ```
> Example:
>  
>  IMathBox box = new MathematicalText("==").toBox();
>  box.setExplicitBreak(1);
> ```

**القيمة المرجعة:**
byte
### setExplicitBreak(byte value) {#setExplicitBreak-byte-}
```
public final void setExplicitBreak(byte value)
```

الكسر الصريح يُحدد ما إذا كان هناك فاصل سطر في بداية كائن Box، بحيث يُلف السطر عند بداية كائن الصندوق. يحدد عدد العامل في السطر السابق للنص الرياضي الذي يُستخدم كنقطة محاذاة للسطر الحالي للنص الرياضي. القيم الممكنة: 1..255 القيمة الافتراضية: 0 (بدون كسر صريح)

--------------------

> ```
> مثال:
>  
>  IMathBox box = new MathematicalText("==").toBox();
>  box.setExplicitBreak(1);
> ```

**المُعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | byte |  |

### getChildren() {#getChildren--}
```
public final IMathElement[] getChildren()
```

إرجاع عناصر الأطفال

**القيمة المرجعة:**
com.aspose.slides.IMathElement[]
### getControlCharacterProperties() {#getControlCharacterProperties--}
```
public final OmmlControlCharacterPPTXUnsupportedProps getControlCharacterProperties()
```

خصائص أحرف التحكم

**القيمة المرجعة:**
com.aspose.slides.OmmlControlCharacterPPTXUnsupportedProps