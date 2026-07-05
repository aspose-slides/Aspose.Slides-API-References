---
title: AsArgumentOfFunction
second_title: Aspose.Sildes لـ .NET مرجع API
description: يأخذ الدالة المحددة باستخدام هذا المثيل كمعامل
type: docs
weight: 20
url: /ar/aspose.slides.mathtext/mathelementbase/asargumentoffunction/
---
## AsArgumentOfFunction(IMathElement) {#asargumentoffunction}

يأخذ الدالة المحددة باستخدام هذه المثيل كمعامل

```csharp
public IMathFunction AsArgumentOfFunction(IMathElement functionName)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| functionName | IMathElement | اسم الدالة |

### قيمة الإرجاع

عنصر رياضي جديد من النوع [`IMathFunction`](../../imathfunction)

### أمثلة

مثال:

```csharp
[C#]
IMathElement functionName = new MathematicalText("sin");
IMathElement functionArg = new MathematicalText("x");
IMathFunction func = functionArg.AsArgumentOfFunction(functionName);
```

### أنظر أيضاً

* واجهة [IMathFunction](../../imathfunction)
* واجهة [IMathElement](../../imathelement)
* فئة [MathElementBase](../../mathelementbase)
* مساحة الاسم [Aspose.Slides.MathText](../../mathelementbase)
* تجميع [Aspose.Slides](../../../)

---

## AsArgumentOfFunction(string) {#asargumentoffunction_4}

يأخذ الدالة المحددة باستخدام هذه المثيل كمعامل

```csharp
public IMathFunction AsArgumentOfFunction(string functionName)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| functionName | String | اسم الدالة |

### قيمة الإرجاع

عنصر رياضي جديد من النوع [`IMathFunction`](../../imathfunction)

### أمثلة

مثال:

```csharp
[C#]
IMathElement functionArg = new MathematicalText("x");
IMathFunction func = functionArg.AsArgumentOfFunction("cos");
```

### أنظر أيضاً

* واجهة [IMathFunction](../../imathfunction)
* فئة [MathElementBase](../../mathelementbase)
* مساحة الاسم [Aspose.Slides.MathText](../../mathelementbase)
* تجميع [Aspose.Slides](../../../)

---

## AsArgumentOfFunction(MathFunctionsOfOneArgument) {#asargumentoffunction_1}

يأخذ الدالة المحددة باستخدام هذه المثيل كمعامل

```csharp
public IMathFunction AsArgumentOfFunction(MathFunctionsOfOneArgument functionType)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| functionType | MathFunctionsOfOneArgument | أحد أنواع الدوال الشائعة للمعامل الواحد |

### قيمة الإرجاع

عنصر رياضي جديد من النوع [`IMathFunction`](../../imathfunction)

### أمثلة

مثال:

```csharp
[C#]
IMathElement functionName = new MathematicalText("sin");
IMathElement functionArg = new MathematicalText("x");
IMathFunction func = functionArg.AsArgumentOfFunction(functionName);
```

### أنظر أيضاً

* واجهة [IMathFunction](../../imathfunction)
* تعداد [MathFunctionsOfOneArgument](../../mathfunctionsofoneargument)
* فئة [MathElementBase](../../mathelementbase)
* مساحة الاسم [Aspose.Slides.MathText](../../mathelementbase)
* تجميع [Aspose.Slides](../../../)

---

## AsArgumentOfFunction(MathFunctionsOfTwoArguments, IMathElement) {#asargumentoffunction_2}

يأخذ الدالة المحددة باستخدام هذه المثيل كمعامل ويضيف المعامل الإضافي المحدد

```csharp
public IMathFunction AsArgumentOfFunction(MathFunctionsOfTwoArguments functionType, 
    IMathElement additionalArgument)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| functionType | MathFunctionsOfTwoArguments | أحد أنواع الدوال الشائعة لاثنين من المعاملات: Log, Lim, Min, Max |
| additionalArgument | IMathElement | معامل إضافي يعتمد على نوع الدالة |

### قيمة الإرجاع

عنصر رياضي جديد من النوع [`IMathFunction`](../../imathfunction)

### أمثلة

مثال:

```csharp
[C#]
IMathElement functionArg = new MathematicalText("x");
IMathElement logarithmBase = new MathematicalText("5");
IMathFunction func = functionArg.AsArgumentOfFunction(MathFunctionsOfTwoArguments.Log, logarithmBase); // يعيد لوغاريتم 'x' للقاعدة '5'
```

### أنظر أيضاً

* واجهة [IMathFunction](../../imathfunction)
* تعداد [MathFunctionsOfTwoArguments](../../mathfunctionsoftwoarguments)
* واجهة [IMathElement](../../imathelement)
* فئة [MathElementBase](../../mathelementbase)
* مساحة الاسم [Aspose.Slides.MathText](../../mathelementbase)
* تجميع [Aspose.Slides](../../../)

---

## AsArgumentOfFunction(MathFunctionsOfTwoArguments, string) {#asargumentoffunction_3}

يأخذ الدالة المحددة باستخدام هذه المثيل كمعامل ويضيف المعامل الإضافي المحدد

```csharp
public IMathFunction AsArgumentOfFunction(MathFunctionsOfTwoArguments functionType, 
    string additionalArgument)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| functionType | MathFunctionsOfTwoArguments | أحد أنواع الدوال الشائعة لاثنين من المعاملات: Log, Lim, Min, Max |
| additionalArgument | String | معامل إضافي يعتمد على نوع الدالة |

### قيمة الإرجاع

عنصر رياضي جديد من النوع [`IMathFunction`](../../imathfunction)

### أمثلة

مثال:

```csharp
[C#]
IMathElement functionArg = new MathematicalText("x");
IMathFunction func = functionArg.AsArgumentOfFunction(MathFunctionsOfTwoArguments.Log, "5"); // يعيد لوغاريتم 'x' إلى القاعدة '5'
```

### أنظر أيضاً

* واجهة [IMathFunction](../../imathfunction)
* تعداد [MathFunctionsOfTwoArguments](../../mathfunctionsoftwoarguments)
* فئة [MathElementBase](../../mathelementbase)
* مساحة الاسم [Aspose.Slides.MathText](../../mathelementbase)
* تجميع [Aspose.Slides](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->