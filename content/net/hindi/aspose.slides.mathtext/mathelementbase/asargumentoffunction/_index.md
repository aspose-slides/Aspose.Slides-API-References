---
title: AsArgumentOfFunction
second_title: Aspose.Sildes के लिए .NET API संदर्भ
description: इस इंस्टेंस को तर्क के रूप में उपयोग करके निर्दिष्ट फ़ंक्शन लेता है
type: docs
weight: 20
url: /hi/aspose.slides.mathtext/mathelementbase/asargumentoffunction/
---
## AsArgumentOfFunction(IMathElement) {#asargumentoffunction}

यह इंस्टेंस को तर्क के रूप में उपयोग करके निर्दिष्ट फ़ंक्शन लेता है

```csharp
public IMathFunction AsArgumentOfFunction(IMathElement functionName)
```

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| functionName | IMathElement | फ़ंक्शन नाम |

### रिटर्न वैल्यू

नए गणित तत्व प्रकार [`IMathFunction`](../../imathfunction)

### उदाहरण

उदाहरण:

```csharp
[C#]
IMathElement functionName = new MathematicalText("sin");
IMathElement functionArg = new MathematicalText("x");
IMathFunction func = functionArg.AsArgumentOfFunction(functionName);
```

### देखें

* इंटरफ़ेस [IMathFunction](../../imathfunction)
* इंटरफ़ेस [IMathElement](../../imathelement)
* क्लास [MathElementBase](../../mathelementbase)
* नामस्थान [Aspose.Slides.MathText](../../mathelementbase)
* असेंबली [Aspose.Slides](../../../)

---

## AsArgumentOfFunction(string) {#asargumentoffunction_4}

यह इंस्टेंस को तर्क के रूप में उपयोग करके निर्दिष्ट फ़ंक्शन लेता है

```csharp
public IMathFunction AsArgumentOfFunction(string functionName)
```

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| functionName | String | फ़ंक्शन नाम |

### रिटर्न वैल्यू

नए गणित तत्व प्रकार [`IMathFunction`](../../imathfunction)

### उदाहरण

उदाहरण:

```csharp
[C#]
IMathElement functionArg = new MathematicalText("x");
IMathFunction func = functionArg.AsArgumentOfFunction("cos");
```

### देखें

* इंटरफ़ेस [IMathFunction](../../imathfunction)
* क्लास [MathElementBase](../../mathelementbase)
* नामस्थान [Aspose.Slides.MathText](../../mathelementbase)
* असेंबली [Aspose.Slides](../../../)

---

## AsArgumentOfFunction(MathFunctionsOfOneArgument) {#asargumentoffunction_1}

यह इंस्टेंस को तर्क के रूप में उपयोग करके निर्दिष्ट फ़ंक्शन लेता है

```csharp
public IMathFunction AsArgumentOfFunction(MathFunctionsOfOneArgument functionType)
```

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| functionType | MathFunctionsOfOneArgument | एक-आर्ग्यूमेंट वाले सामान्य फ़ंक्शन प्रकारों में से एक |

### रिटर्न वैल्यू

नए गणित तत्व प्रकार [`IMathFunction`](../../imathfunction)

### उदाहरण

उदाहरण:

```csharp
[C#]
IMathElement functionName = new MathematicalText("sin");
IMathElement functionArg = new MathematicalText("x");
IMathFunction func = functionArg.AsArgumentOfFunction(functionName);
```

### देखें

* इंटरफ़ेस [IMathFunction](../../imathfunction)
* एन्यूम [MathFunctionsOfOneArgument](../../mathfunctionsofoneargument)
* क्लास [MathElementBase](../../mathelementbase)
* नामस्थान [Aspose.Slides.MathText](../../mathelementbase)
* असेंबली [Aspose.Slides](../../../)

---

## AsArgumentOfFunction(MathFunctionsOfTwoArguments, IMathElement) {#asargumentoffunction_2}

यह इंस्टेंस को तर्क के रूप में उपयोग करके निर्दिष्ट फ़ंक्शन लेता है और निर्दिष्ट अतिरिक्त तर्क

```csharp
public IMathFunction AsArgumentOfFunction(MathFunctionsOfTwoArguments functionType, 
    IMathElement additionalArgument)
```

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| functionType | MathFunctionsOfTwoArguments | दो-आर्ग्यूमेंट वाले सामान्य फ़ंक्शन प्रकारों में से एक: Log, Lim, Min, Max |
| additionalArgument | IMathElement | फ़ंक्शन प्रकार के आधार पर अतिरिक्त तर्क |

### रिटर्न वैल्यू

नए गणित तत्व प्रकार [`IMathFunction`](../../imathfunction)

### उदाहरण

उदाहरण:

```csharp
[C#]
IMathElement functionArg = new MathematicalText("x");
IMathElement logarithmBase = new MathematicalText("5");
IMathFunction func = functionArg.AsArgumentOfFunction(MathFunctionsOfTwoArguments.Log, logarithmBase); // 'x' का लघुगणक बेस '5' पर लौटाता है
```

### देखें

* इंटरफ़ेस [IMathFunction](../../imathfunction)
* एन्यूम [MathFunctionsOfTwoArguments](../../mathfunctionsoftwoarguments)
* इंटरफ़ेस [IMathElement](../../imathelement)
* क्लास [MathElementBase](../../mathelementbase)
* नामस्थान [Aspose.Slides.MathText](../../mathelementbase)
* असेंबली [Aspose.Slides](../../../)

---

## AsArgumentOfFunction(MathFunctionsOfTwoArguments, string) {#asargumentoffunction_3}

यह इंस्टेंस को तर्क के रूप में उपयोग करके निर्दिष्ट फ़ंक्शन लेता है और निर्दिष्ट अतिरिक्त तर्क

```csharp
public IMathFunction AsArgumentOfFunction(MathFunctionsOfTwoArguments functionType, 
    string additionalArgument)
```

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| functionType | MathFunctionsOfTwoArguments | दो-आर्ग्यूमेंट वाले सामान्य फ़ंक्शन प्रकारों में से एक: Log, Lim, Min, Max |
| additionalArgument | String | फ़ंक्शन प्रकार के आधार पर अतिरिक्त तर्क |

### रिटर्न वैल्यू

नए गणित तत्व प्रकार [`IMathFunction`](../../imathfunction)

### उदाहरण

उदाहरण:

```csharp
[C#]
IMathElement functionArg = new MathematicalText("x");
IMathFunction func = functionArg.AsArgumentOfFunction(MathFunctionsOfTwoArguments.Log, "5"); // 'x' का लघुगणक बेस '5' पर लौटाता है
```

### देखें

* इंटरफ़ेस [IMathFunction](../../imathfunction)
* एन्यूम [MathFunctionsOfTwoArguments](../../mathfunctionsoftwoarguments)
* क्लास [MathElementBase](../../mathelementbase)
* नामस्थान [Aspose.Slides.MathText](../../mathelementbase)
* असेंबली [Aspose.Slides](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->