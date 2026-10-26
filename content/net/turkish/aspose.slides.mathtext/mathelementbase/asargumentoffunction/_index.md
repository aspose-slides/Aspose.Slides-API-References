---
title: AsArgumentOfFunction
second_title: Aspose.Sildes için .NET API Referansı
description: Bu örnek kullanılarak belirtilen işlevi argüman olarak alır
type: docs
weight: 20
url: /tr/aspose.slides.mathtext/mathelementbase/asargumentoffunction/
---
## AsArgumentOfFunction(IMathElement) {#asargumentoffunction}

Bu örnek kullanılarak belirtilen işlev argüman olarak alınır

```csharp
public IMathFunction AsArgumentOfFunction(IMathElement functionName)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| functionName | IMathElement | Function name |

### Dönüş Değeri

Tipi [`IMathFunction`](../../imathfunction) olan yeni matematik öğesi

### Örnekler

Örnek:

```csharp
[C#]
IMathElement functionName = new MathematicalText("sin");
IMathElement functionArg = new MathematicalText("x");
IMathFunction func = functionArg.AsArgumentOfFunction(functionName);
```

### Ayrıca Bakınız

* arayüz [IMathFunction](../../imathfunction)
* arayüz [IMathElement](../../imathelement)
* sınıf [MathElementBase](../../mathelementbase)
* ad alanı [Aspose.Slides.MathText](../../mathelementbase)
* derleme [Aspose.Slides](../../../)

---

## AsArgumentOfFunction(string) {#asargumentoffunction_4}

Bu örnek kullanılarak belirtilen işlev argüman olarak alınır

```csharp
public IMathFunction AsArgumentOfFunction(string functionName)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| functionName | String | Function name |

### Dönüş Değeri

Tipi [`IMathFunction`](../../imathfunction) olan yeni matematik öğesi

### Örnekler

Örnek:

```csharp
[C#]
IMathElement functionArg = new MathematicalText("x");
IMathFunction func = functionArg.AsArgumentOfFunction("cos");
```

### Ayrıca Bakınız

* arayüz [IMathFunction](../../imathfunction)
* sınıf [MathElementBase](../../mathelementbase)
* ad alanı [Aspose.Slides.MathText](../../mathelementbase)
* derleme [Aspose.Slides](../../../)

---

## AsArgumentOfFunction(MathFunctionsOfOneArgument) {#asargumentoffunction_1}

Bu örnek kullanılarak belirtilen işlev argüman olarak alınır

```csharp
public IMathFunction AsArgumentOfFunction(MathFunctionsOfOneArgument functionType)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| functionType | MathFunctionsOfOneArgument | One of the common function type of one argument |

### Dönüş Değeri

Tipi [`IMathFunction`](../../imathfunction) olan yeni matematik öğesi

### Örnekler

Örnek:

```csharp
[C#]
IMathElement functionName = new MathematicalText("sin");
IMathElement functionArg = new MathematicalText("x");
IMathFunction func = functionArg.AsArgumentOfFunction(functionName);
```

### Ayrıca Bakınız

* arayüz [IMathFunction](../../imathfunction)
* enum [MathFunctionsOfOneArgument](../../mathfunctionsofoneargument)
* sınıf [MathElementBase](../../mathelementbase)
* ad alanı [Aspose.Slides.MathText](../../mathelementbase)
* derleme [Aspose.Slides](../../../)

---

## AsArgumentOfFunction(MathFunctionsOfTwoArguments, IMathElement) {#asargumentoffunction_2}

Bu örnek kullanılarak belirtilen işlev argüman olarak alınır ve ek argüman belirtilir

```csharp
public IMathFunction AsArgumentOfFunction(MathFunctionsOfTwoArguments functionType, 
    IMathElement additionalArgument)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| functionType | MathFunctionsOfTwoArguments | One of the common function type of two arguments: Log, Lim, Min, Max |
| additionalArgument | IMathElement | Additional argument depending on the type of function |

### Dönüş Değeri

Tipi [`IMathFunction`](../../imathfunction) olan yeni matematik öğesi

### Örnekler

Örnek:

```csharp
[C#]
IMathElement functionArg = new MathematicalText("x");
IMathElement logarithmBase = new MathematicalText("5");
IMathFunction func = functionArg.AsArgumentOfFunction(MathFunctionsOfTwoArguments.Log, logarithmBase); // 'x' değişkeninin 5 tabanındaki logaritmasını döndürür
```

### Ayrıca Bakınız

* arayüz [IMathFunction](../../imathfunction)
* enum [MathFunctionsOfTwoArguments](../../mathfunctionsoftwoarguments)
* arayüz [IMathElement](../../imathelement)
* sınıf [MathElementBase](../../mathelementbase)
* ad alanı [Aspose.Slides.MathText](../../mathelementbase)
* derleme [Aspose.Slides](../../../)

---

## AsArgumentOfFunction(MathFunctionsOfTwoArguments, string) {#asargumentoffunction_3}

Bu örnek kullanılarak belirtilen işlev argüman olarak alınır ve ek argüman belirtilir

```csharp
public IMathFunction AsArgumentOfFunction(MathFunctionsOfTwoArguments functionType, 
    string additionalArgument)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| functionType | MathFunctionsOfTwoArguments | One of the common function type of two arguments: Log, Lim, Min, Max |
| additionalArgument | String | Additional argument depending on the type of function |

### Dönüş Değeri

Tipi [`IMathFunction`](../../imathfunction) olan yeni matematik öğesi

### Örnekler

Örnek:

```csharp
[C#]
IMathElement functionArg = new MathematicalText("x");
IMathFunction func = functionArg.AsArgumentOfFunction(MathFunctionsOfTwoArguments.Log, "5"); // 'x' değişkeninin 5 tabanındaki logaritmasını döndürür
```

### Ayrıca Bakınız

* arayüz [IMathFunction](../../imathfunction)
* enum [MathFunctionsOfTwoArguments](../../mathfunctionsoftwoarguments)
* sınıf [MathElementBase](../../mathelementbase)
* ad alanı [Aspose.Slides.MathText](../../mathelementbase)
* derleme [Aspose.Slides](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->