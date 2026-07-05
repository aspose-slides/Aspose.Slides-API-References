---
title: AsArgumentOfFunction
second_title: Aspose.Sildes for .NET API संदर्भ
description: निर्दिष्ट फ़ंक्शन को इस इंस्टेंस को तर्क के रूप में लेकर लेता है
type: docs
weight: 20
url: /hi/aspose.slides.mathtext/imathelement/asargumentoffunction/
---
## AsArgumentOfFunction(IMathElement) {#asargumentoffunction}

निर्दिष्ट फ़ंक्शन को इस इंस्टेंस को तर्क के रूप में लेकर लेता है

```csharp
public IMathFunction AsArgumentOfFunction(IMathElement functionName)
```

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| functionName | IMathElement | फ़ंक्शन नाम |

### Return Value

प्रकार [`IMathFunction`](../../imathfunction) का नया गणितीय तत्व

### Examples

Example:

```csharp
[C#]
IMathElement functionName = new MathematicalText("sin");
IMathElement functionArg = new MathematicalText("x");
IMathFunction func = functionArg.AsArgumentOfFunction(functionName);
```

### See Also

* इंटरफ़ेस [IMathFunction](../../imathfunction)
* इंटरफ़ेस [IMathElement](../../imathelement)
* नामस्थान [Aspose.Slides.MathText](../../imathelement)
* असेंबली [Aspose.Slides](../../../)

---

## AsArgumentOfFunction(string) {#asargumentoffunction_4}

निर्दिष्ट फ़ंक्शन को इस इंस्टेंस को तर्क के रूप में लेकर लेता है

```csharp
public IMathFunction AsArgumentOfFunction(string functionName)
```

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| functionName | String | फ़ंक्शन नाम |

### Return Value

प्रकार [`IMathFunction`](../../imathfunction) का नया गणितीय तत्व

### Examples

Example:

```csharp
[C#]
IMathElement functionArg = new MathematicalText("x");
IMathFunction func = functionArg.AsArgumentOfFunction("cos");
```

### See Also

* इंटरफ़ेस [IMathFunction](../../imathfunction)
* इंटरफ़ेस [IMathElement](../../imathelement)
* नामस्थान [Aspose.Slides.MathText](../../imathelement)
* असेंबली [Aspose.Slides](../../../)

---

## AsArgumentOfFunction(MathFunctionsOfOneArgument) {#asargumentoffunction_1}

निर्दिष्ट फ़ंक्शन को इस इंस्टेंस को तर्क के रूप में लेकर लेता है

```csharp
public IMathFunction AsArgumentOfFunction(MathFunctionsOfOneArgument functionType)
```

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| functionType | MathFunctionsOfOneArgument | एक तर्क वाले सामान्य फ़ंक्शन प्रकारों में से एक |

### Return Value

प्रकार [`IMathFunction`](../../imathfunction) का नया गणितीय तत्व

### Examples

Example:

```csharp
[C#]
IMathElement functionArg = new MathematicalText("x");
IMathFunction func = functionArg.AsArgumentOfFunction(MathFunctionsOfOneArgument.ArcSin);
```

### See Also

* इंटरफ़ेस [IMathFunction](../../imathfunction)
* एन्यूम [MathFunctionsOfOneArgument](../../mathfunctionsofoneargument)
* इंटरफ़ेस [IMathElement](../../imathelement)
* नामस्थान [Aspose.Slides.MathText](../../imathelement)
* असेंबली [Aspose.Slides](../../../)

---

## AsArgumentOfFunction(MathFunctionsOfTwoArguments, IMathElement) {#asargumentoffunction_2}

निर्दिष्ट फ़ंक्शन को इस इंस्टेंस को तर्क के रूप में लेकर, तथा अतिरिक्त तर्क को निर्दिष्ट करके लेता है

```csharp
public IMathFunction AsArgumentOfFunction(MathFunctionsOfTwoArguments functionType, 
    IMathElement additionalArgument)
```

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| functionType | MathFunctionsOfTwoArguments | दो तर्क वाले सामान्य फ़ंक्शन प्रकारों में से एक: Log, Lim, Min, Max |
| additionalArgument | IMathElement | फ़ंक्शन प्रकार के आधार पर अतिरिक्त तर्क |

### Return Value

प्रकार [`IMathFunction`](../../imathfunction) का नया गणितीय तत्व

### Examples

Example:

```csharp
[C#]
IMathElement functionArg = new MathematicalText("x");
IMathElement logarithmBase = new MathematicalText("5");
IMathFunction func = functionArg.AsArgumentOfFunction(MathFunctionsOfTwoArguments.Log, logarithmBase); // 'x' का लघुगणक आधार '5' पर लौटाता है
```

### See Also

* इंटरफ़ेस [IMathFunction](../../imathfunction)
* एन्यूम [MathFunctionsOfTwoArguments](../../mathfunctionsoftwoarguments)
* इंटरफ़ेस [IMathElement](../../imathelement)
* नामस्थान [Aspose.Slides.MathText](../../imathelement)
* असेंबली [Aspose.Slides](../../../)

---

## AsArgumentOfFunction(MathFunctionsOfTwoArguments, string) {#asargumentoffunction_3}

निर्दिष्ट फ़ंक्शन को इस इंस्टेंस को तर्क के रूप में लेकर, तथा अतिरिक्त तर्क को निर्दिष्ट करके लेता है

```csharp
public IMathFunction AsArgumentOfFunction(MathFunctionsOfTwoArguments functionType, 
    string additionalArgument)
```

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| functionType | MathFunctionsOfTwoArguments | दो तर्क वाले सामान्य फ़ंक्शन प्रकारों में से एक: Log, Lim, Min, Max |
| additionalArgument | String | फ़ंक्शन प्रकार के आधार पर अतिरिक्त तर्क |

### Return Value

प्रकार [`IMathFunction`](../../imathfunction) का नया गणितीय तत्व

### Examples

Example:

```csharp
[C#]
IMathElement functionArg = new MathematicalText("x");
IMathFunction func = functionArg.AsArgumentOfFunction(MathFunctionsOfTwoArguments.Log, "5"); // 'x' का लघुगणक आधार '5' पर लौटाता है
```

### See Also

* इंटरफ़ेस [IMathFunction](../../imathfunction)
* एन्यूम [MathFunctionsOfTwoArguments](../../mathfunctionsoftwoarguments)
* इंटरफ़ेस [IMathElement](../../imathelement)
* नामस्थान [Aspose.Slides.MathText](../../imathelement)
* असेंबली [Aspose.Slides](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->