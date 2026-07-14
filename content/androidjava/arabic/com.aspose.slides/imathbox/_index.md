---
title: IMathBox
second_title: Aspose.Slides لـ Android عبر مرجع API لجافا
description: يحدد التعبئة المنطقية للعنصر الرياضي.
type: docs
url: /ar/com.aspose.slides/imathbox/
---
**جميع الواجهات المنفذة:**
[com.aspose.slides.IMathElement](../../com.aspose.slides/imathelement)
```
public interface IMathBox extends IMathElement
```

يحدد التعبئة المنطقية (التغليف) للعنصر الرياضي. على سبيل المثال، يمكن لكائن مُغلق أن يعمل كمحاكي للمعامل مع أو بدون نقطة محاذاة، أو يعمل كنقطة فاصل سطر، أو يتم تجميعه بحيث لا يُسمح بفواصل الأسطر داخله. على سبيل المثال، يجب تغليف معامل "==" لمنع فواصل الأسطر.

--------------------

> ```
> Example:
>  
>  IMathBox box = new MathematicalText("==").toBox();
> ```
## الطرق

| الطريقة | الوصف |
| --- | --- |
| [getBase()](#getBase--) | الوسيط الأساسي |
| [getOperatorEmulator()](#getOperatorEmulator--) | محاكي المشغل. |
| [setOperatorEmulator(boolean value)](#setOperatorEmulator-boolean-) | محاكي المشغل. |
| [getNoBreak()](#getNoBreak--) | بدون فاصل. |
| [setNoBreak(boolean value)](#setNoBreak-boolean-) | بدون فاصل. |
| [getDifferential()](#getDifferential--) | تفاضل. |
| [setDifferential(boolean value)](#setDifferential-boolean-) | تفاضل. |
| [getAlignmentPoint()](#getAlignmentPoint--) | عند يكون صحيحًا، يعمل هذا محاكي المشغل كنقطة محاذاة؛ أي أن نقاط المحاذاة المحددة في معادلات أخرى يمكن محاذاتها معه. |
| [setAlignmentPoint(boolean value)](#setAlignmentPoint-boolean-) | عند يكون صحيحًا، يعمل هذا محاكي المشغل كنقطة محاذاة؛ أي أن نقاط المحاذاة المحددة في معادلات أخرى يمكن محاذاتها معه. |
| [getExplicitBreak()](#getExplicitBreak--) | الفاصل الصريح يحدد ما إذا كان هناك فاصل سطر في بداية كائن الصندوق، بحيث يلتفون السطر عند بداية كائن الصندوق. |
| [setExplicitBreak(byte value)](#setExplicitBreak-byte-) | الفاصل الصريح يحدد ما إذا كان هناك فاصل سطر في بداية كائن الصندوق، بحيث يلتفون السطر عند بداية كائن الصندوق. |

### getBase() {#getBase--}
```
public abstract IMathElement getBase()
```

الوسيط الأساسي

--------------------

> ```
> Example:
>  
>  IMathBox box = new MathematicalText("==").toBox();
>  IMathElement base = box.getBase();
> ```

**الإرجاع:**  
[IMathElement](../../com.aspose.slides/imathelement)
### getOperatorEmulator() {#getOperatorEmulator--}
```
public abstract boolean getOperatorEmulator()
```

محاكي المشغل. عندما يكون صحيحًا، يتصرف الصندوق ومحتوياته كمعامل واحد ويرثان خصائص المعامل. هذا يعني، على سبيل المثال، أن الحرف يمكن أن يعمل كنقطة لفاصل سطر ويمكن محاذاته مع معاملات أخرى. غالبًا ما تُستخدم محاكيات المشغل عندما يتحد glyph واحد أو أكثر لتكوين معامل، مثل '=='. القيمة الافتراضية: false

--------------------

> ```
> Example:
>  
>  IMathBox box = new MathematicalText("==").toBox();
>  box.setOperatorEmulator(true);
> ```

**الإرجاع:**  
boolean
### setOperatorEmulator(boolean value) {#setOperatorEmulator-boolean-}
```
public abstract void setOperatorEmulator(boolean value)
```

محاكي المشغل. عندما يكون صحيحًا، يتصرف الصندوق ومحتوياته كمعامل واحد ويرثان خصائص المعامل. هذا يعني، على سبيل المثال، أن الحرف يمكن أن يعمل كنقطة لفاصل سطر ويمكن محاذاته مع معاملات أخرى. غالبًا ما تُستخدم محاكيات المشغل عندما يتحد glyph واحد أو أكثر لتكوين معامل، مثل '=='. القيمة الافتراضية: false

--------------------

> ```
> Example:
>  
>  IMathBox box = new MathematicalText("==").toBox();
>  box.setOperatorEmulator(true);
> ```

**المُعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | boolean |  |

### getNoBreak() {#getNoBreak--}
```
public abstract boolean getNoBreak()
```

بدون فاصل. تحدد هذه الخاصية خاصية "غير قابل للكسر" على صندوق الكائن. عندما تكون صحيحة، لا يمكن حدوث فواصل أسطر داخل الصندوق. قد يكون هذا مهمًا لمحاكيات المشغل التي تتكون من أكثر من معامل ثنائي. عندما لا يتم تحديد هذا العنصر، يمكن حدوث فواصل داخل الصندوق. القيمة الافتراضية: true

--------------------

> ```
> Example:
>  
>  IMathBox box = new MathematicalText("**********").toBox();
>  box.setNoBreak(false);
> ```

**الإرجاع:**  
boolean
### setNoBreak(boolean value) {#setNoBreak-boolean-}
```
public abstract void setNoBreak(boolean value)
```

بدون فاصل. تحدد هذه الخاصية خاصية "غير قابل للكسر" على صندوق الكائن. عندما تكون صحيحة، لا يمكن حدوث فواصل أسطر داخل الصندوق. قد يكون هذا مهمًا لمحاكيات المشغل التي تتكون من أكثر من معامل ثنائي. عندما لا يتم تحديد هذا العنصر، يمكن حدوث فواصل داخل الصندوق. القيمة الافتراضية: true

--------------------

> ```
> Example:
>  
>  IMathBox box = new MathematicalText("**********").toBox();
>  box.setNoBreak(false);
> ```

**المُعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | boolean |  |

### getDifferential() {#getDifferential--}
```
public abstract boolean getDifferential()
```

تفاضل. عندما تكون صحيحة، يعمل الصندوق كـ تفاضل (مثال: \\ud835\\udc51\\ud835\\udc65 في داخل التكامل)، ويتلقى التباعد الأفقي المناسب للتفاضل الرياضي. القيمة الافتراضية: false

--------------------

> ```
> مثال:
>  
>  IMathBox differential = new MathematicalText("dx").toBox();
>  differential.setDifferential(true);
>  IMathBlock baseArg = new MathematicalText("x").join(differential);
>  IMathNaryOperator integral = baseArg.integral(MathIntegralTypes.Simple, "0", "1");
> ```

**الإرجاع:**  
boolean
### setDifferential(boolean value) {#setDifferential-boolean-}
```
public abstract void setDifferential(boolean value)
```

تفاضل. عندما تكون صحيحة، يعمل الصندوق كـ تفاضل (مثال: \\ud835\\udc51\\ud835\\udc65 في داخل التكامل)، ويتلقى التباعد الأفقي المناسب للتفاضل الرياضي. القيمة الافتراضية: false

--------------------

> ```
> مثال:
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
public abstract boolean getAlignmentPoint()
```

عند تكون صحيحة، يعمل هذا محاكي المشغل كنقطة محاذاة؛ أي أن نقاط المحاذاة المحددة في معادلات أخرى يمكن محاذاتها معه. القيمة الافتراضية: false

--------------------

> ```
> مثال:
>  
>  IMathBox box = new MathematicalText("==").toBox();
>  box.setAlignmentPoint(true);
> ```

**الإرجاع:**  
boolean
### setAlignmentPoint(boolean value) {#setAlignmentPoint-boolean-}
```
public abstract void setAlignmentPoint(boolean value)
```

عند تكون صحيحة، يعمل هذا محاكي المشغل كنقطة محاذاة؛ أي أن نقاط المحاذاة المحددة في معادلات أخرى يمكن محاذاتها معه. القيمة الافتراضية: false

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
public abstract byte getExplicitBreak()
```

الفاصل الصريح يحدد ما إذا كان هناك فاصل سطر في بداية كائن الصندوق، بحيث يلتفون السطر عند بداية كائن الصندوق. يحدد رقم المشغل في السطر السابق من النص الرياضي الذي يُستخدم كنقطة محاذاة للسطر الحالي من النص الرياضي. القيم الممكنة: 1..255 القيمة الافتراضية: 0 (بدون فاصل صريح)

--------------------

> ```
> Example:
>  
>  IMathBox box = new MathematicalText("==").toBox();
>  box.setExplicitBreak(1);
> ```

**الإرجاع:**  
byte
### setExplicitBreak(byte value) {#setExplicitBreak-byte-}
```
public abstract void setExplicitBreak(byte value)
```

الفاصل الصريح يحدد ما إذا كان هناك فاصل سطر في بداية كائن الصندوق، بحيث يلتفون السطر عند بداية كائن الصندوق. يحدد رقم المشغل في السطر السابق من النص الرياضي الذي يُستخدم كنقطة محاذاة للسطر الحالي من النص الرياضي. القيم الممكنة: 1..255 القيمة الافتراضية: 0 (بدون فاصل صريح)

--------------------

> ```
> Example:
>  
>  IMathBox box = new MathematicalText("==").toBox();
>  box.setExplicitBreak(1);
> ```

**المُعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | byte |  |