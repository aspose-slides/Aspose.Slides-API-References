---
title: IMathBox
second_title: مرجع API لـ Aspose.Slides للغة Java
description: يحدد التغليف المنطقي (التعبئة) للعنصر الرياضي.
type: docs
url: /ar/com.aspose.slides/imathbox/
---
**جميع الواجهات المنفذة:**
[com.aspose.slides.IMathElement](../../com.aspose.slides/imathelement)
```
public interface IMathBox extends IMathElement
```

يحدد التغليف المنطقي (التعبئة) للعنصر الرياضي. على سبيل المثال، يمكن لكائن مُغلف أن يعمل كمحاكي عامل مع نقطة محاذاة أو بدونها، أو أن يعمل كنقطة كسر سطر، أو أن يُجمع بحيث لا يسمح بوجود فواصل سطرية داخله. على سبيل المثال، يجب تغليف العامل "==" لمنع فواصل الأسطر.

--------------------

> ```
> مثال:
>  
>  IMathBox box = new MathematicalText("==").toBox();
> ```

## الطرق

| الطريقة | الوصف |
| --- | --- |
| [getBase()](#getBase--) | معامل أساسي |
| [getOperatorEmulator()](#getOperatorEmulator--) | محاكي عامل. |
| [setOperatorEmulator(boolean value)](#setOperatorEmulator-boolean-) | محاكي عامل. |
| [getNoBreak()](#getNoBreak--) | بدون كسر. |
| [setNoBreak(boolean value)](#setNoBreak-boolean-) | بدون كسر. |
| [getDifferential()](#getDifferential--) | تفاضل. |
| [setDifferential(boolean value)](#setDifferential-boolean-) | تفاضل. |
| [getAlignmentPoint()](#getAlignmentPoint--) | عندما يكون صحيحًا، يعمل هذا محاكي العامل كنقطة محاذاة؛ أي أن نقاط المحاذاة المحددة في معادلات أخرى يمكن محاذاتها معه. |
| [setAlignmentPoint(boolean value)](#setAlignmentPoint-boolean-) | عندما يكون صحيحًا، يعمل هذا محاكي العامل كنقطة محاذاة؛ أي أن نقاط المحاذاة المحددة في معادلات أخرى يمكن محاذاتها معه. |
| [getExplicitBreak()](#getExplicitBreak--) | يحدد الكسر الصريح ما إذا كان هناك كسر سطر في بداية كائن الصندوق، بحيث يلتف السطر عند بداية كائن الصندوق. |
| [setExplicitBreak(byte value)](#setExplicitBreak-byte-) | يحدد الكسر الصريح ما إذا كان هناك كسر سطر في بداية كائن الصندوق، بحيث يلتف السطر عند بداية كائن الصندوق. |
### getBase() {#getBase--}
```
public abstract IMathElement getBase()
```


معامل أساسي

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


محاكي عامل. عندما يكون صحيحًا، يتصرف الصندوق ومحتوياته كعامل واحد وي inherit خصائص العامل. هذا يعني، على سبيل المثال، أن الحرف يمكن أن يكون نقطة كسر سطر ويمكن محاذاته إلى عوامل أخرى. غالبًا ما تُستخدم محاكات العوامل عندما يتحد واحد أو أكثر من الرموز لتكوين عامل، مثل '=='. القيمة الافتراضية: false

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


محاكي عامل. عندما يكون صحيحًا، يتصرف الصندوق ومحتوياته كعامل واحد وي inherit خصائص العامل. هذا يعني، على سبيل المثال، أن الحرف يمكن أن يكون نقطة كسر سطر ويمكن محاذاته إلى عوامل أخرى. غالبًا ما تُستخدم محاكات العوامل عندما يتحد واحد أو أكثر من الرموز لتكوين عامل، مثل '=='. القيمة الافتراضية: false

--------------------

> ```
> مثال:
>  
>  IMathBox box = new MathematicalText("==").toBox();
>  box.setOperatorEmulator(true);
> ```

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | boolean |  |

### getNoBreak() {#getNoBreak--}
```
public abstract boolean getNoBreak()
```


بدون كسر. تحدد هذه الخاصية خاصية "عدم القابلية للكسر" على صندوق الكائن. عندما تكون صحيحة، لا يمكن حدوث أي كسر سطر داخل الصندوق. وهذا قد يكون مهمًا لمحاكيات العوامل التي تتألف من أكثر من عامل ثنائي. عندما لا يتم تحديد هذا العنصر، يمكن حدوث كسر داخل الصندوق. القيمة الافتراضية: true

--------------------

> ```
> مثال:
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


بدون كسر. تحدد هذه الخاصية خاصية "عدم القابلية للكسر" على صندوق الكائن. عندما تكون صحيحة، لا يمكن حدوث أي كسر سطر داخل الصندوق. وهذا قد يكون مهمًا لمحاكيات العوامل التي تتألف من أكثر من عامل ثنائي. عندما لا يتم تحديد هذا العنصر، يمكن حدوث كسر داخل الصندوق. القيمة الافتراضية: true

--------------------

> ```
> مثال:
>  
>  IMathBox box = new MathematicalText("**********").toBox();
>  box.setNoBreak(false);
> ```

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | boolean |  |

### getDifferential() {#getDifferential--}
```
public abstract boolean getDifferential()
```


تفاضل. عندما تكون صحيحة، يعمل الصندوق كتفاضل (مثلاً \\ud835\\udc51\\ud835\\udc65 في الدالة المتكاملة)، ويتلقى التباعد الأفقي المناسب للمتفاضل الرياضي. القيمة الافتراضية: false

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


تفاضل. عندما تكون صحيحة، يعمل الصندوق كتفاضل (مثلاً \\ud835\\udc51\\ud835\\udc65 في الدالة المتكاملة)، ويتلقى التباعد الأفقي المناسب للمتفاضل الرياضي. القيمة الافتراضية: false

--------------------

> ```
> مثال:
>  
>  IMathBox differential = new MathematicalText("dx").toBox();
>  differential.setDifferential(true);
>  IMathBlock baseArg = new MathematicalText("x").join(differential);
>  IMathNaryOperator integral = baseArg.integral(MathIntegralTypes.Simple, "0", "1");
> ```

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | boolean |  |

### getAlignmentPoint() {#getAlignmentPoint--}
```
public abstract boolean getAlignmentPoint()
```


عند كونها صحيحة، يعمل هذا محاكي العامل كنقطة محاذاة؛ أي أن نقاط المحاذاة المحددة في معادلات أخرى يمكن محاذاتها معه. القيمة الافتراضية: false

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


عند كونها صحيحة، يعمل هذا محاكي العامل كنقطة محاذاة؛ أي أن نقاط المحاذاة المحددة في معادلات أخرى يمكن محاذتها معه. القيمة الافتراضية: false

--------------------

> ```
> مثال:
>  
>  IMathBox box = new MathematicalText("==").toBox();
>  box.setAlignmentPoint(true);
> ```

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | boolean |  |

### getExplicitBreak() {#getExplicitBreak--}
```
public abstract byte getExplicitBreak()
```


الكسر الصريح يحدد ما إذا كان هناك كسر سطر في بداية كائن الصندوق، بحيث يلتف السطر عند بداية كائن الصندوق. يحدد عدد العامل في السطر السابق للنص الرياضي الذي يُستخدم كنقطة محاذاة للسطر الحالي من النص الرياضي. القيم المحتملة: 1..255 القيمة الافتراضية: 0 (بدون كسر صريح)

--------------------

> ```
> مثال:
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


الكسر الصريح يحدد ما إذا كان هناك كسر سطر في بداية كائن الصندوق، بحيث يلتف السطر عند بداية كائن الصندوق. يحدد عدد العامل في السطر السابق للنص الرياضي الذي يُستخدم كنقطة محاذاة للسطر الحالي من النص الرياضي. القيم المحتملة: 1..255 القيمة الافتراضية: 0 (بدون كسر صريح)

--------------------

> ```
> مثال:
>  
>  IMathBox box = new MathematicalText("==").toBox();
>  box.setExplicitBreak(1);
> ```

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | byte |  |