---
title: AsArgumentOfFunction
second_title: Aspose.Sildes .NET için API Referansı
description: Bu örnek kullanılarak belirtilen fonksiyonu argüman olarak alır
type: docs
weight: 20
url: /tr/aspose.slides.mathtext/imathelement/asargumentoffunction/
---
## AsArgumentOfFunction(IMathElement) {#asargumentoffunction}

Belirtilen fonksiyonu bu örnek argüman olarak alır

```csharp
public IMathFunction AsArgumentOfFunction(IMathElement functionName)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| functionName | IMathElement | Fonksiyon adı |

### Dönüş Değeri

Yeni matematik öğesi türü [`IMathFunction`](../../imathfunction)

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
* ad alanı [Aspose.Slides.MathText](../../imathelement)
* derleme [Aspose.Slides](../../../)

---

## AsArgumentOfFunction(string) {#asargumentoffunction_4}

Belirtilen fonksiyonu bu örnek argüman olarak alır

```csharp
public IMathFunction AsArgumentOfFunction(string functionName)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| functionName | String | Fonksiyon adı |

### Dönüş Değeri

Yeni matematik öğesi türü [`IMathFunction`](../../imathfunction)

### Örnekler

Örnek:

```csharp
[C#]
IMathElement functionArg = new MathematicalText("x");
IMathFunction func = functionArg.AsArgumentOfFunction("cos");
```

### Ayrıca Bakınız

* arayüz [IMathFunction](../../imathfunction)
* arayüz [IMathElement](../../imathelement)
* ad alanı [Aspose.Slides.MathText](../../imathelement)
* derleme [Aspose.Slides](../../../)

---

## AsArgumentOfFunction(MathFunctionsOfOneArgument) {#asargumentoffunction_1}

Belirtilen fonksiyonu bu örnek argüman olarak alır

```csharp
public IMathFunction AsArgumentOfFunction(MathFunctionsOfOneArgument functionType)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| functionType | MathFunctionsOfOneArgument | Tek argümanlı yaygın fonksiyon tiplerinden biri |

### Dönüş Değeri

Yeni matematik öğesi türü [`IMathFunction`](../../imathfunction)

### Örnekler

Örnek:

```csharp
[C#]
IMathElement functionArg = new MathematicalText("x");
IMathFunction func = functionArg.AsArgumentOfFunction(MathFunctionsOfOneArgument.ArcSin);
```

### Ayrıca Bakınız

* arayüz [IMathFunction](../../imathfunction)
* enum [MathFunctionsOfOneArgument](../../mathfunctionsofoneargument)
* arayüz [IMathElement](../../imathelement)
* ad alanı [Aspose.Slides.MathText](../../imathelement)
* derleme [Aspose.Slides](../../../)

---

## AsArgumentOfFunction(MathFunctionsOfTwoArguments, IMathElement) {#asargumentoffunction_2}

Belirtilen fonksiyonu bu örnek argüman olarak alır ve ek argüman alır

```csharp
public IMathFunction AsArgumentOfFunction(MathFunctionsOfTwoArguments functionType, 
    IMathElement additionalArgument)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| functionType | MathFunctionsOfTwoArguments | İki argümanlı yaygın fonksiyon tiplerinden biri: Log, Lim, Min, Max |
| additionalArgument | IMathElement | Fonksiyon tipine bağlı ek argüman |

### Dönüş Değeri

Yeni matematik öğesi türü [`IMathFunction`](../../imathfunction)

### Örnekler

Örnek:

```csharp
[C#]
IMathElement functionArg = new MathematicalText("x");
IMathElement logarithmBase = new MathematicalText("5");
IMathFunction func = functionArg.AsArgumentOfFunction(MathFunctionsOfTwoArguments.Log, logarithmBase); // 'x' değerinin '5' tabanına göre logaritmasını döndürür
```

### Ayrıca Bakınız

* arayüz [IMathFunction](../../imathfunction)
* enum [MathFunctionsOfTwoArguments](../../mathfunctionsoftwoarguments)
* arayüz [IMathElement](../../imathelement)
* ad alanı [Aspose.Slides.MathText](../../imathelement)
* derleme [Aspose.Slides](../../../)

---

## AsArgumentOfFunction(MathFunctionsOfTwoArguments, string) {#asargumentoffunction_3}

Belirtilen fonksiyonu bu örnek argüman olarak alır ve ek argüman alır

```csharp
public IMathFunction AsArgumentOfFunction(MathFunctionsOfTwoArguments functionType, 
    string additionalArgument)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| functionType | MathFunctionsOfTwoArguments | İki argümanlı yaygın fonksiyon tiplerinden biri: Log, Lim, Min, Max |
| additionalArgument | String | Fonksiyon tipine bağlı ek argüman |

### Dönüş Değeri

Yeni matematik öğesi türü [`IMathFunction`](../../imathfunction)

### Örnekler

Örnek:

```csharp
[C#]
IMathElement functionArg = new MathematicalText("x");
IMathFunction func = functionArg.AsArgumentOfFunction(MathFunctionsOfTwoArguments.Log, "5"); // 'x' değerinin '5' tabanına göre logaritmasını döndürür
```

### Ayrıca Bakınız

* arayüz [IMathFunction](../../imathfunction)
* enum [MathFunctionsOfTwoArguments](../../mathfunctionsoftwoarguments)
* arayüz [IMathElement](../../imathelement)
* ad alanı [Aspose.Slides.MathText](../../imathelement)
* derleme [Aspose.Slides](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->