---
title: MathBox
second_title: مرجع API لـ Aspose.Slides للـ Java
description: يحدد التعبئة المنطقية (التغليف) للعنصر الرياضي.
type: docs
url: /ar/com.aspose.slides/mathbox/
---
**الوراثة:**  
java.lang.Object, [com.aspose.slides.MathElementBase](../../com.aspose.slides/mathelementbase)

**جميع الواجهات المنفذة:**  
[com.aspose.slides.IMathBox](../../com.aspose.slides/imathbox), com.aspose.slides.IHasControlCharacterProperties  
```
public final class MathBox extends MathElementBase implements IMathBox, IHasControlCharacterProperties
```

يحدد التعبئة المنطقية (التغليف) للعنصر الرياضي. على سبيل المثال، يمكن لكائن مُغلف أن يعمل كمحاكٍ للمعامل مع أو بدون نقطة محاذاة، أو أن يعمل كنقطة لفاصل سطر، أو يُجمّع بحيث لا يُسمح بفواصل الأسطر داخله. على سبيل المثال، يجب تغليف المُعامل “==” لمنع فواصل الأسطر.

--------------------

> ```
> مثال:
>  
>  MathBox box = new MathBox(new MathematicalText("=="));
> ```
## المنشئ

| المنشئ | الوصف |
| --- | --- |
| [MathBox(IMathElement element)](#MathBox-com.aspose.slides.IMathElement-) | يُهيئ MathBox بالعنصر المحدد كمعامل |
## الطرق

| الطريقة | الوصف |
| --- | --- |
| [getBase()](#getBase--) | الوسيط الأساسي |
| [getOperatorEmulator()](#getOperatorEmulator--) | محاكٍ للمعامل. |
| [setOperatorEmulator(boolean value)](#setOperatorEmulator-boolean-) | محاكٍ للمعامل. |
| [getNoBreak()](#getNoBreak--) | بدون فاصل هذه الخاصية تحدد الخاصية "unbreakable" على صندوق الكائن. |
| [setNoBreak(boolean value)](#setNoBreak-boolean-) | بدون فاصل هذه الخاصية تحدد الخاصية "unbreakable" على صندوق الكائن. |
| [getDifferential()](#getDifferential--) | تفاضل عندما تكون true، يكون الصندوق كالمتفاضل (مثلاً \\ud835\\udc51\\ud835\\udc65 في المتكامل)، ويتلقى التباعد الأفقي المناسب للمتفاضل الرياضي. |
| [setDifferential(boolean value)](#setDifferential-boolean-) | تفاضل عندما تكون true، يكون الصندوق كالمتفاضل (مثلاً \\ud835\\udc51\\ud835\\udc65 في المتكامل)، ويتلقى التباعد الأفقي المناسب للمتفاضل الرياضي. |
| [getAlignmentPoint()](#getAlignmentPoint--) | عند true، يعمل هذا محاكٍ للمعامل كنقطة محاذاة؛ أي أن نقاط المحاذاة المحددة في معادلات أخرى يمكن محاذاتها معه. |
| [setAlignmentPoint(boolean value)](#setAlignmentPoint-boolean-) | عند true، يعمل هذا محاكٍ للمعامل كنقطة محاذاة؛ أي أن نقاط المحاذاة المحددة في معادلات أخرى يمكن محاذتها معه. |
| [getExplicitBreak()](#getExplicitBreak--) | فاصل صريح يحدد ما إذا كان هناك فاصل سطر في بداية كائن الصندوق، بحيث يلتف السطر في بداية كائن الصندوق. |
| [setExplicitBreak(byte value)](#setExplicitBreak-byte-) | فاصل صريح يحدد ما إذا كان هناك فاصل سطر في بداية كائن الصندوق، بحيث يلتف السطر في بداية كائن الصندوق. |
| [getChildren()](#getChildren--) | جلب عناصر الأطفال |
| [getControlCharacterProperties()](#getControlCharacterProperties--) | خصائص حرف التحكم |
### MathBox(IMathElement element) {#MathBox-com.aspose.slides.IMathElement-}
```
public MathBox(IMathElement element)
```

يُهيئ MathBox بالعنصر المحدد كمعامل

--------------------

> ```
> مثال:
>  
>  MathBox box = new MathBox(new MathematicalText("=="));
> ```


**معلمات:**  
| المعامل | النوع | الوصف |
| --- | --- | --- |
| element | [IMathElement](../../com.aspose.slides/imathelement) | العنصر الأساسي الذي يُطبق عليه الصندوق. يمكن أن يكون null. |

### getBase() {#getBase--}
```
public final IMathElement getBase()
```

الوسيط الأساسي

--------------------

> ```
> مثال:
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

محاكٍ للمعامل. عندما تكون true، يتصرف الصندوق ومحتوياته كمؤثر واحد ويرثان خصائص المؤثر. هذا يعني، على سبيل المثال، أن الحرف يمكن أن يعمل كنقطة لفاصل سطر ويمكن محاذاته إلى مؤثرات أخرى. غالبًا ما تُستخدم محاكيات المعامل عندما يتحد واحد أو أكثر من الرموز لتكوين مؤثر، مثل '=='. القيمة الافتراضية: false

--------------------

> ```
> مثال:
>  
>  MathBox box = new MathBox(new MathematicalText("=="));
>  box.setOperatorEmulator(true);
> ```

**القيمة المرجعة:** boolean  
### setOperatorEmulator(boolean value) {#setOperatorEmulator-boolean-}
```
public final void setOperatorEmulator(boolean value)
```

محاكٍ للمعامل. عندما تكون true، يتصرف الصندوق ومحتوياته كمؤثر واحد ويرثان خصائص المؤثر. هذا يعني، على سبيل المثال، أن الحرف يمكن أن يعمل كنقطة لفاصل سطر ويمكن محاذاته إلى مؤثرات أخرى. غالبًا ما تُستخدم محاكيات المعامل عندما يتحد واحد أو أكثر من الرموز لتكوين مؤثر، مثل '=='. القيمة الافتراضية: false

--------------------

> ```
> Example:
>  
>  MathBox box = new MathBox(new MathematicalText("=="));
>  box.setOperatorEmulator(true);
> ```

**معلمات:**  
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | boolean |  |

### getNoBreak() {#getNoBreak--}
```
public final boolean getNoBreak()
```

بدون فاصل هذه الخاصية تحدد الخاصية "unbreakable" على صندوق الكائن. عندما تكون true، لا يمكن حدوث فواصل أسطر داخل الصندوق. قد يكون هذا مهمًا لمحاكيات المعامل التي تتكون من أكثر من معامل ثنائي. عندما لا يُحدد هذا العنصر، يمكن حدوث فواصل داخل الصندوق. القيمة الافتراضية: true

--------------------

> ```
> مثال:
>  
>  MathBox box = new MathBox(new MathematicalText("*****"));
>  box.setNoBreak(false);
> ```

**القيمة المرجعة:** boolean  
### setNoBreak(boolean value) {#setNoBreak-boolean-}
```
public final void setNoBreak(boolean value)
```

بدون فاصل هذه الخاصية تحدد الخاصية "unbreakable" على صندوق الكائن. عندما تكون true، لا يمكن حدوث فواصل أسطر داخل الصندوق. قد يكون هذا مهمًا لمحاكيات المعامل التي تتكون من أكثر من معامل ثنائي. عندما لا يُحدد هذا العنصر، يمكن حدوث فواصل داخل الصندوق. القيمة الافتراضية: true

--------------------

> ```
> مثال:
>  
>  MathBox box = new MathBox(new MathematicalText("*****"));
>  box.setNoBreak(false);
> ```

**معلمات:**  
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | boolean |  |

### getDifferential() {#getDifferential--}
```
public final boolean getDifferential()
```

تفاضل عندما تكون true، يكون الصندوق كالمتفاضل (مثلاً \\ud835\\udc51\\ud835\\udc65 في المتكامل)، ويتلقى التباعد الأفقي المناسب للمتفاضل الرياضي. القيمة الافتراضية: false

--------------------

> ```
> مثال:
>  
>  IMathBox differential = new MathematicalText("dx").toBox();
>  differential.setDifferential(true);
>  IMathBlock baseArg = new MathematicalText("x").join(differential);
>  IMathNaryOperator integral = baseArg.integral(MathIntegralTypes.Simple, "0", "1");
> ```

**القيمة المرجعة:** boolean  
### setDifferential(boolean value) {#setDifferential-boolean-}
```
public final void setDifferential(boolean value)
```

تفاضل عندما تكون true، يكون الصندوق كالمتفاضل (مثلاً \\ud835\\udc51\\ud835\\udc65 في المتكامل)، ويتلقى التباعد الأفقي المناسب للمتفاضل الرياضي. القيمة الافتراضية: false

--------------------

> ```
> مثال:
>  
>  MathBox box = new MathBox(new MathematicalText("=="));
>  box.setOperatorEmulator(true);
> ```

**معلمات:**  
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | boolean |  |

### getAlignmentPoint() {#getAlignmentPoint--}
```
public final boolean getAlignmentPoint()
```

عند true، يعمل هذا محاكٍ للمعامل كنقطة محاذاة؛ أي أن نقاط المحاذاة المحددة في معادلات أخرى يمكن محاذتها معه. القيمة الافتراضية: false

--------------------

> ```
> مثال:
>  
>  IMathBox box = new MathematicalText("==").toBox();
>  box.setAlignmentPoint(true);
> ```

**القيمة المرجعة:** boolean  
### setAlignmentPoint(boolean value) {#setAlignmentPoint-boolean-}
```
public final void setAlignmentPoint(boolean value)
```

عند true، يعمل هذا محاكٍ للمعامل كنقطة محاذاة؛ أي أن نقاط المحاذاة المحددة في معادلات أخرى يمكن محاذتها معه. القيمة الافتراضية: false

--------------------

> ```
> Example:
>  
>  IMathBox box = new MathematicalText("==").toBox();
>  box.setAlignmentPoint(true);
> ```

**معلمات:**  
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | boolean |  |

### getExplicitBreak() {#getExplicitBreak--}
```
public final byte getExplicitBreak()
```

فاصل صريح يحدد ما إذا كان هناك فاصل سطر في بداية كائن الصندوق، بحيث يلتف السطر في بداية كائن الصندوق. يحدد عدد المعامل على السطر السابق من النص الرياضي الذي سيُستخدم كنقطة محاذاة للسطر الحالي من النص الرياضي. القيم الممكنة: 1..255 القيمة الافتراضية: 0 (بدون فاصل صريح)

--------------------

> ```
> مثال:
>  
>  IMathBox box = new MathematicalText("==").toBox();
>  box.setExplicitBreak(1);
> ```

**القيمة المرجعة:** byte  
### setExplicitBreak(byte value) {#setExplicitBreak-byte-}
```
public final void setExplicitBreak(byte value)
```

فاصل صريح يحدد ما إذا كان هناك فاصل سطر في بداية كائن الصندوق، بحيث يلتف السطر في بداية كائن الصندوق. يحدد عدد المعامل على السطر السابق من النص الرياضي الذي سيُستخدم كنقطة محاذاة للسطر الحالي من النص الرياضي. القيم الممكنة: 1..255 القيمة الافتراضية: 0 (بدون فاصل صريح)

--------------------

> ```
> مثال:
>  
>  IMathBox box = new MathematicalText("==").toBox();
>  box.setExplicitBreak(1);
> ```

**معلمات:**  
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | byte |  |

### getChildren() {#getChildren--}
```
public final IMathElement[] getChildren()
```

جلب عناصر الأطفال

**القيمة المرجعة:**  
com.aspose.slides.IMathElement[]
### getControlCharacterProperties() {#getControlCharacterProperties--}
```
public final OmmlControlCharacterPPTXUnsupportedProps getControlCharacterProperties()
```

خصائص حرف التحكم

**القيمة المرجعة:**  
com.aspose.slides.OmmlControlCharacterPPTXUnsupportedProps