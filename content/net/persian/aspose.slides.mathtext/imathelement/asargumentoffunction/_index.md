---
title: AsArgumentOfFunction
second_title: مرجع API Aspose.Sildes برای .NET
description: تابع مشخص‌شده را با استفاده از این نمونه به‌عنوان آرگومان می‌گیرد
type: docs
weight: 20
url: /fa/aspose.slides.mathtext/imathelement/asargumentoffunction/
---
## AsArgumentOfFunction(IMathElement) {#asargumentoffunction}

تابع مشخص‌شده را با استفاده از این نمونه به‌عنوان آرگومان می‌گیرد

```csharp
public IMathFunction AsArgumentOfFunction(IMathElement functionName)
```

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| functionName | IMathElement | نام تابع |

### مقدار بازگشت

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
* فضای‌نام [Aspose.Slides.MathText](../../imathelement)
* مونتاژ [Aspose.Slides](../../../)

---

## AsArgumentOfFunction(string) {#asargumentoffunction_4}

تابع مشخص‌شده را با استفاده از این نمونه به‌عنوان آرگومان می‌گیرد

```csharp
public IMathFunction AsArgumentOfFunction(string functionName)
```

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| functionName | String | نام تابع |

### مقدار بازگشت

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
* رابط [IMathElement](../../imathelement)
* فضای‌نام [Aspose.Slides.MathText](../../imathelement)
* مونتاژ [Aspose.Slides](../../../)

---

## AsArgumentOfFunction(MathFunctionsOfOneArgument) {#asargumentoffunction_1}

تابع مشخص‌شده را با استفاده از این نمونه به‌عنوان آرگومان می‌گیرد

```csharp
public IMathFunction AsArgumentOfFunction(MathFunctionsOfOneArgument functionType)
```

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| functionType | MathFunctionsOfOneArgument | یکی از انواع توابع عمومی با یک آرگومان |

### مقدار بازگشت

عنصر ریاضی جدید از نوع [`IMathFunction`](../../imathfunction)

### مثال‌ها

مثال:

```csharp
[C#]
IMathElement functionArg = new MathematicalText("x");
IMathFunction func = functionArg.AsArgumentOfFunction(MathFunctionsOfOneArgument.ArcSin);
```

### موارد مرتبط

* رابط [IMathFunction](../../imathfunction)
* شمارش [MathFunctionsOfOneArgument](../../mathfunctionsofoneargument)
* رابط [IMathElement](../../imathelement)
* فضای‌نام [Aspose.Slides.MathText](../../imathelement)
* مونتاژ [Aspose.Slides](../../../)

---

## AsArgumentOfFunction(MathFunctionsOfTwoArguments, IMathElement) {#asargumentoffunction_2}

تابع مشخص‌شده را با استفاده از این نمونه به‌عنوان آرگومان و آرگومان اضافی مشخص می‌گیرد

```csharp
public IMathFunction AsArgumentOfFunction(MathFunctionsOfTwoArguments functionType, 
    IMathElement additionalArgument)
```

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| functionType | MathFunctionsOfTwoArguments | یکی از انواع توابع عمومی با دو آرگومان: Log, Lim, Min, Max |
| additionalArgument | IMathElement | آرگومان اضافی بسته به نوع تابع |

### مقدار بازگشت

عنصر ریاضی جدید از نوع [`IMathFunction`](../../imathfunction)

### مثال‌ها

مثال:

```csharp
[C#]
IMathElement functionArg = new MathematicalText("x");
IMathElement logarithmBase = new MathematicalText("5");
IMathFunction func = functionArg.AsArgumentOfFunction(MathFunctionsOfTwoArguments.Log, logarithmBase); // لگاریتم 'x' به پایه '5' را بر می‌گرداند
```

### موارد مرتبط

* رابط [IMathFunction](../../imathfunction)
* شمارش [MathFunctionsOfTwoArguments](../../mathfunctionsoftwoarguments)
* رابط [IMathElement](../../imathelement)
* فضای‌نام [Aspose.Slides.MathText](../../imathelement)
* مونتاژ [Aspose.Slides](../../../)

---

## AsArgumentOfFunction(MathFunctionsOfTwoArguments, string) {#asargumentoffunction_3}

تابع مشخص‌شده را با استفاده از این نمونه به‌عنوان آرگومان و آرگومان اضافی مشخص می‌گیرد

```csharp
public IMathFunction AsArgumentOfFunction(MathFunctionsOfTwoArguments functionType, 
    string additionalArgument)
```

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| functionType | MathFunctionsOfTwoArguments | یکی از انواع توابع عمومی با دو آرگومان: Log, Lim, Min, Max |
| additionalArgument | String | آرگومان اضافی بسته به نوع تابع |

### مقدار بازگشت

عنصر ریاضی جدید از نوع [`IMathFunction`](../../imathfunction)

### مثال‌ها

مثال:

```csharp
[C#]
IMathElement functionArg = new MathematicalText("x");
IMathFunction func = functionArg.AsArgumentOfFunction(MathFunctionsOfTwoArguments.Log, "5"); // لگاریتم 'x' به پایه '5' را بر می‌گرداند
```

### موارد مرتبط

* رابط [IMathFunction](../../imathfunction)
* شمارش [MathFunctionsOfTwoArguments](../../mathfunctionsoftwoarguments)
* رابط [IMathElement](../../imathelement)
* فضای‌نام [Aspose.Slides.MathText](../../imathelement)
* مونتاژ [Aspose.Slides](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->