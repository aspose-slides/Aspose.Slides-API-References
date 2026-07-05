---
title: Integral
second_title: Aspose.Sildes for .NET API संदर्भ
description: समाकल लेता है
type: docs
weight: 70
url: /hi/aspose.slides.mathtext/mathelementbase/integral/
---
## Integral(MathIntegralTypes, IMathElement, IMathElement, MathLimitLocations) {#integral_2}

समाकल लेता है

```csharp
public IMathNaryOperator Integral(MathIntegralTypes integralType, IMathElement lowerLimit, 
    IMathElement upperLimit, MathLimitLocations limitLocations)
```

| पैरामीटर | टाइप | वर्णन |
| --- | --- | --- |
| integralType | MathIntegralTypes | समाकल प्रकार |
| lowerLimit | IMathElement | समाकल की निचली सीमा |
| upperLimit | IMathElement | समाकल की ऊपरी सीमा |
| limitLocations | MathLimitLocations | सीमाओं का स्थान |

### रिटर्न मान

प्रकार का नया उदाहरण [`IMathNaryOperator`](../../imathnaryoperator)

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

* इंटरफेस [IMathNaryOperator](../../imathnaryoperator)
* एनीम [MathIntegralTypes](../../mathintegraltypes)
* इंटरफेस [IMathElement](../../imathelement)
* एनीम [MathLimitLocations](../../mathlimitlocations)
* क्लास [MathElementBase](../../mathelementbase)
* नेमस्पेस [Aspose.Slides.MathText](../../mathelementbase)
* असेंबली [Aspose.Slides](../../../)

---

## Integral(MathIntegralTypes, IMathElement, IMathElement) {#integral_1}

समाकल लेता है

```csharp
public IMathNaryOperator Integral(MathIntegralTypes integralType, IMathElement lowerLimit, 
    IMathElement upperLimit)
```

| पैरामीटर | टाइप | वर्णन |
| --- | --- | --- |
| integralType | MathIntegralTypes | समाकल प्रकार |
| lowerLimit | IMathElement | समाकल की निचली सीमा |
| upperLimit | IMathElement | समाकल की ऊपरी सीमा |

### रिटर्न मान

प्रकार का नया उदाहरण [`IMathNaryOperator`](../../imathnaryoperator)

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

* इंटरफेस [IMathNaryOperator](../../imathnaryoperator)
* एनीम [MathIntegralTypes](../../mathintegraltypes)
* इंटरफेस [IMathElement](../../imathelement)
* क्लास [MathElementBase](../../mathelementbase)
* नेमस्पेस [Aspose.Slides.MathText](../../mathelementbase)
* असेंबली [Aspose.Slides](../../../)

---

## Integral(MathIntegralTypes) {#integral}

सीमाओं के बिना समाकल लेता है

```csharp
public IMathNaryOperator Integral(MathIntegralTypes integralType)
```

| पैरामीटर | टाइप | वर्णन |
| --- | --- | --- |
| integralType | MathIntegralTypes | समाकल प्रकार |

### रिटर्न मान

प्रकार का नया उदाहरण [`IMathNaryOperator`](../../imathnaryoperator)

### उदाहरण

उदाहरण:

```csharp
[C#]
IMathElement baseElement = new MathematicalText("𝑥");
IMathNaryOperator integral = baseElement.Integral(MathIntegralTypes.Contour);
```

### संबंधित देखें

* इंटरफेस [IMathNaryOperator](../../imathnaryoperator)
* एनीम [MathIntegralTypes](../../mathintegraltypes)
* क्लास [MathElementBase](../../mathelementbase)
* नेमस्पेस [Aspose.Slides.MathText](../../mathelementbase)
* असेंबली [Aspose.Slides](../../../)

---

## Integral(MathIntegralTypes, string, string, MathLimitLocations) {#integral_4}

समाकल लेता है

```csharp
public IMathNaryOperator Integral(MathIntegralTypes integralType, string lowerLimit, 
    string upperLimit, MathLimitLocations limitLocations)
```

| पैरामीटर | टाइप | वर्णन |
| --- | --- | --- |
| integralType | MathIntegralTypes | समाकल प्रकार |
| lowerLimit | String | समाकल की निचली सीमा |
| upperLimit | String | समाकल की ऊपरी सीमा |
| limitLocations | MathLimitLocations | सीमाओं का स्थान |

### रिटर्न मान

प्रकार का नया उदाहरण [`IMathNaryOperator`](../../imathnaryoperator)

### उदाहरण

उदाहरण:

```csharp
[C#]
IMathElement baseElement = new MathematicalText("𝑥");
IMathNaryOperator integral = baseElement.Integral(MathIntegralTypes.Simple, "1", "5", MathLimitLocations.UnderOver);
```

### संबंधित देखें

* इंटरफेस [IMathNaryOperator](../../imathnaryoperator)
* एनीम [MathIntegralTypes](../../mathintegraltypes)
* एनीम [MathLimitLocations](../../mathlimitlocations)
* क्लास [MathElementBase](../../mathelementbase)
* नेमस्पेस [Aspose.Slides.MathText](../../mathelementbase)
* असेंबली [Aspose.Slides](../../../)

---

## Integral(MathIntegralTypes, string, string) {#integral_3}

समाकल लेता है

```csharp
public IMathNaryOperator Integral(MathIntegralTypes integralType, string lowerLimit, 
    string upperLimit)
```

| पैरामीटर | टाइप | वर्णन |
| --- | --- | --- |
| integralType | MathIntegralTypes | समाकल प्रकार |
| lowerLimit | String | समाकल की निचली सीमा |
| upperLimit | String | समाकल की ऊपरी सीमा |

### रिटर्न मान

प्रकार का नया उदाहरण [`IMathNaryOperator`](../../imathnaryoperator)

### उदाहरण

उदाहरण:

```csharp
[C#]
IMathElement baseElement = new MathematicalText("𝑥");
IMathNaryOperator integral = baseElement.Integral(MathIntegralTypes.Simple, "1", "5");
```

### संबंधित देखें

* इंटरफेस [IMathNaryOperator](../../imathnaryoperator)
* एनीम [MathIntegralTypes](../../mathintegraltypes)
* क्लास [MathElementBase](../../mathelementbase)
* नेमस्पेस [Aspose.Slides.MathText](../../mathelementbase)
* असेंबली [Aspose.Slides](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->