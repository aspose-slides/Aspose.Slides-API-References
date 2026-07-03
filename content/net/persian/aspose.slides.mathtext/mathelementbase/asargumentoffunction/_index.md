---
title: AsArgumentOfFunction
second_title: Aspose.Sildes برای مرجع API .NET
description: عملکرد مشخص‌شده را با استفاده از این نمونه به‌عنوان آرگومان می‌گیرد
type: docs
weight: 20
url: /fa/aspose.slides.mathtext/mathelementbase/asargumentoffunction/
---
## AsArgumentOfFunction(IMathElement) {#asargumentoffunction}

عملکرد مشخص‌شده را با استفاده از این نمونه به‌عنوان آرگومان می‌گیرد

```csharp
public IMathFunction AsArgumentOfFunction(IMathElement functionName)
```

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| functionName | IMathElement | نام تابع |

### مقدار برگشتی

عنصر ریاضی جدید از نوع [`IMathFunction`](../../imathfunction)

### مثال‌ها

مثال:

```csharp
[C#]
IMathElement functionName = new MathematicalText("sin");
IMathElement functionArg = new MathematicalText("x");
IMathFunction func = functionArg.AsArgumentOfFunction(functionName);
```

### موارد مرتبط

* رابط [IMathFunction](../../imathfunction)
* رابط [IMathElement](../../imathelement)
* کلاس [MathElementBase](../../mathelementbase)
* فضای‌نام [Aspose.Slides.MathText](../../mathelementbase)
* مجمع [Aspose.Slides](../../../)

---

## AsArgumentOfFunction(string) {#asargumentoffunction_4}

عملکرد مشخص‌شده را با استفاده از این نمونه به‌عنوان آرگومان می‌گیرد

```csharp
public IMathFunction AsArgumentOfFunction(string functionName)
```

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| functionName | String | نام تابع |

### مقدار برگشتی

عنصر ریاضی جدید از نوع [`IMathFunction`](../../imathfunction)

### مثال‌ها

مثال:

```csharp
[C#]
IMathElement functionArg = new MathematicalText("x");
IMathFunction func = functionArg.AsArgumentOfFunction("cos");
```

### موارد مرتبط

* رابط [IMathFunction](../../imathfunction)
* کلاس [MathElementBase](../../mathelementbase)
* فضای‌نام [Aspose.Slides.MathText](../../mathelementbase)
* مجمع [Aspose.Slides](../../../)

---

## AsArgumentOfFunction(MathFunctionsOfOneArgument) {#asargumentoffunction_1}

عملکرد مشخص‌شده را با استفاده از این نمونه به‌عنوان آرگومان می‌گیرد

```csharp
public IMathFunction AsArgumentOfFunction(MathFunctionsOfOneArgument functionType)
```

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| functionType | MathFunctionsOfOneArgument | یکی از انواع رایج توابع یک آرگومان |

### مقدار برگشتی

عنصر ریاضی جدید از نوع [`IMathFunction`](../../imathfunction)

### مثال‌ها

مثال:

```csharp
[C#]
IMathElement functionName = new MathematicalText("sin");
IMathElement functionArg = new MathematicalText("x");
IMathFunction func = functionArg.AsArgumentOfFunction(functionName);
```

### موارد مرتبط

* رابط [IMathFunction](../../imathfunction)
* شمارش‌گر [MathFunctionsOfOneArgument](../../mathfunctionsofoneargument)
* کلاس [MathElementBase](../../mathelementbase)
* فضای‌نام [Aspose.Slides.MathText](../../mathelementbase)
* مجمع [Aspose.Slides](../../../)

---

## AsArgumentOfFunction(MathFunctionsOfTwoArguments, IMathElement) {#asargumentoffunction_2}

عملکرد مشخص‌شده را با استفاده از این نمونه به‌عنوان آرگومان می‌گیرد و آرگومان اضافی مشخص‌شده را اضافه می‌کند

```csharp
public IMathFunction AsArgumentOfFunction(MathFunctionsOfTwoArguments functionType, 
    IMathElement additionalArgument)
```

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| functionType | MathFunctionsOfTwoArguments | یکی از انواع رایج توابع دو آرگومان: Log, Lim, Min, Max |
| additionalArgument | IMathElement | آرگومان اضافی بسته به نوع تابع |

### مقدار برگشتی

عنصر ریاضی جدید از نوع [`IMathFunction`](../../imathfunction)

### مثال‌ها

مثال:

```csharp
[C#]
IMathElement functionArg = new MathematicalText("x");
IMathElement logarithmBase = new MathematicalText("5");
IMathFunction func = functionArg.AsArgumentOfFunction(MathFunctionsOfTwoArguments.Log, logarithmBase); // لگاریتم 'x' به پایه '5' را برمی‌گرداند
```

### موارد مرتبط

* رابط [IMathFunction](../../imathfunction)
* شمارش‌گر [MathFunctionsOfTwoArguments](../../mathfunctionsoftwoarguments)
* رابط [IMathElement](../../imathelement)
* کلاس [MathElementBase](../../mathelementbase)
* فضای‌نام [Aspose.Slides.MathText](../../mathelementbase)
* مجمع [Aspose.Slides](../../../)

---

## AsArgumentOfFunction(MathFunctionsOfTwoArguments, string) {#asargumentoffunction_3}

عملکرد مشخص‌شده را با استفاده از این نمونه به‌عنوان آرگومان می‌گیرد و آرگومان اضافی مشخص‌شده را اضافه می‌کند

```csharp
public IMathFunction AsArgumentOfFunction(MathFunctionsOfTwoArguments functionType, 
    string additionalArgument)
```

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| functionType | MathFunctionsOfTwoArguments | یکی از انواع رایج توابع دو آرگومان: Log, Lim, Min, Max |
| additionalArgument | String | آرگومان اضافی بسته به نوع تابع |

### مقدار برگشتی

عنصر ریاضی جدید از نوع [`IMathFunction`](../../imathfunction)

### مثال‌ها

مثال:

```csharp
[C#]
IMathElement functionArg = new MathematicalText("x");
IMathFunction func = functionArg.AsArgumentOfFunction(MathFunctionsOfTwoArguments.Log, "5"); // لگاریتم 'x' به پایه '5' را برمی‌گرداند
```

### موارد مرتبط

* رابط [IMathFunction](../../imathfunction)
* شمارش‌گر [MathFunctionsOfTwoArguments](../../mathfunctionsoftwoarguments)
* کلاس [MathElementBase](../../mathelementbase)
* فضای‌نام [Aspose.Slides.MathText](../../mathelementbase)
* مجمع [Aspose.Slides](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->