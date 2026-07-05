---
title: Integral
second_title: Aspose.Sildes के लिए .NET API संदर्भ
description: इंटीग्रल लेता है
type: docs
weight: 80
url: /hi/aspose.slides.mathtext/imathelement/integral/
---
## Integral(MathIntegralTypes, IMathElement, IMathElement, MathLimitLocations) {#integral_2}

इंटीग्रल लेता है

```csharp
public IMathNaryOperator Integral(MathIntegralTypes integralType, IMathElement lowerLimit, 
    IMathElement upperLimit, MathLimitLocations limitLocations)
```

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| integralType | MathIntegralTypes | इंटीग्रल प्रकार |
| lowerLimit | IMathElement | इंटीग्रल की निचली सीमा |
| upperLimit | IMathElement | इंटीग्रल की ऊपरी सीमा |
| limitLocations | MathLimitLocations | सीमाओं का स्थान |

### रिटर्न मान

प्रकार [`IMathNaryOperator`](../../imathnaryoperator) की नई instance

### उदाहरण

उदाहरण:

```csharp
[C#]
IMathElement baseElement = new MathematicalText("𝑥");
IMathElement lowerLimit = new MathematicalText("1");
IMathElement upperLimit = new MathematicalText("2");
IMathNaryOperator integral = baseElement.Integral(MathIntegralTypes.Simple, lowerLimit, upperLimit, MathLimitLocations.UnderOver);
```

### संबंधित देखें

* इंटरफ़ेस [IMathNaryOperator](../../imathnaryoperator)
* एनम [MathIntegralTypes](../../mathintegraltypes)
* एनम [MathLimitLocations](../../mathlimitlocations)
* इंटरफ़ेस [IMathElement](../../imathelement)
* नेमस्पेस [Aspose.Slides.MathText](../../imathelement)
* असेंबली [Aspose.Slides](../../../)

---

## Integral(MathIntegralTypes, IMathElement, IMathElement) {#integral_1}

इंटीग्रल लेता है

```csharp
public IMathNaryOperator Integral(MathIntegralTypes integralType, IMathElement lowerLimit, 
    IMathElement upperLimit)
```

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| integralType | MathIntegralTypes | इंटीग्रल प्रकार |
| lowerLimit | IMathElement | इंटीग्रल की निचली सीमा |
| upperLimit | IMathElement | इंटीग्रल की ऊपरी सीमा |

### रिटर्न मान

प्रकार [`IMathNaryOperator`](../../imathnaryoperator) की नई instance

### उदाहरण

उदाहरण:

```csharp
[C#]
IMMathElement baseElement = new MathematicalText("𝑥");
IMMathElement lowerLimit = new MathematicalText("1");
IMMathElement upperLimit = new MathematicalText("2");
IMMathNaryOperator integral = baseElement.Integral(MathIntegralTypes.Simple, lowerLimit, upperLimit, MathLimitLocations.UnderOver);
```

### संबंधित देखें

* इंटरफ़ेस [IMathNaryOperator](../../imathnaryoperator)
* एनम [MathIntegralTypes](../../mathintegraltypes)
* इंटरफ़ेस [IMathElement](../../imathelement)
* नेमस्पेस [Aspose.Slides.MathText](../../imathelement)
* असेंबली [Aspose.Slides](../../../)

---

## Integral(MathIntegralTypes) {#integral}

इंटीग्रल बिना सीमा के लेता है

```csharp
public IMathNaryOperator Integral(MathIntegralTypes integralType)
```

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| integralType | MathIntegralTypes | इंटीग्रल प्रकार |

### रिटर्न मान

प्रकार [`IMathNaryOperator`](../../imathnaryoperator) की नई instance

### उदाहरण

उदाहरण:

```csharp
[C#]
IMathElement baseElement = new MathematicalText("𝑥");
IMathNaryOperator integral = baseElement.Integral(MathIntegralTypes.Contour);
```

### संबंधित देखें

* इंटरफ़ेस [IMathNaryOperator](../../imathnaryoperator)
* एनम [MathIntegralTypes](../../mathintegraltypes)
* इंटरफ़ेस [IMathElement](../../imathelement)
* नेमस्पेस [Aspose.Slides.MathText](../../imathelement)
* असेंबली [Aspose.Slides](../../../)

---

## Integral(MathIntegralTypes, string, string, MathLimitLocations) {#integral_4}

इंटीग्रल लेता है

```csharp
public IMathNaryOperator Integral(MathIntegralTypes integralType, string lowerLimit, 
    string upperLimit, MathLimitLocations limitLocations)
```

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| integralType | MathIntegralTypes | इंटीग्रल प्रकार |
| lowerLimit | String | इंटीग्रल की निचली सीमा |
| upperLimit | String | इंटीग्रल की ऊपरी सीमा |
| limitLocations | MathLimitLocations | सीमाओं का स्थान |

### रिटर्न मान

प्रकार [`IMathNaryOperator`](../../imathnaryoperator) की नई instance

### उदाहरण

उदाहरण:

```csharp
[C#]
IMathElement baseElement = new MathematicalText("𝑥");
IMathNaryOperator integral = baseElement.Integral(MathIntegralTypes.Simple, "1", "5", MathLimitLocations.UnderOver);
```

### संबंधित देखें

* इंटरफ़ेस [IMathNaryOperator](../../imathnaryoperator)
* एनम [MathIntegralTypes](../../mathintegraltypes)
* एनम [MathLimitLocations](../../mathlimitlocations)
* इंटरफ़ेस [IMathElement](../../imathelement)
* नेमस्पेस [Aspose.Slides.MathText](../../imathelement)
* असेंबली [Aspose.Slides](../../../)

---

## Integral(MathIntegralTypes, string, string) {#integral_3}

इंटीग्रल लेता है

```csharp
public IMathNaryOperator Integral(MathIntegralTypes integralType, string lowerLimit, 
    string upperLimit)
```

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| integralType | MathIntegralTypes | इंटीग्रल प्रकार |
| lowerLimit | String | इंटीग्रल की निचली सीमा |
| upperLimit | String | इंटीग्रल की ऊपरी सीमा |

### रिटर्न मान

प्रकार [`IMathNaryOperator`](../../imathnaryoperator) की नई instance

### उदाहरण

उदाहरण:

```csharp
[C#]
IMathElement baseElement = new MathematicalText("𝑥");
IMathNaryOperator integral = baseElement.Integral(MathIntegralTypes.Simple, "1", "5");
```

### संबंधित देखें

* इंटरफ़ेस [IMathNaryOperator](../../imathnaryoperator)
* एनम [MathIntegralTypes](../../mathintegraltypes)
* इंटरफ़ेस [IMathElement](../../imathelement)
* नेमस्पेस [Aspose.Slides.MathText](../../imathelement)
* असेंबली [Aspose.Slides](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->