---
title: Integral
second_title: Aspose.Sildes for .NET API 참조
description: 적분을 수행합니다
type: docs
weight: 70
url: /ko/aspose.slides.mathtext/mathelementbase/integral/
---
## Integral(MathIntegralTypes, IMathElement, IMathElement, MathLimitLocations) {#integral_2}

적분을 수행합니다

```csharp
public IMathNaryOperator Integral(MathIntegralTypes integralType, IMathElement lowerLimit, 
    IMathElement upperLimit, MathLimitLocations limitLocations)
```

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| integralType | MathIntegralTypes | 적분 유형 |
| lowerLimit | IMathElement | 적분의 하한 |
| upperLimit | IMathElement | 적분의 상한 |
| limitLocations | MathLimitLocations | 한계 위치 |

### 반환값

New instance of type [`IMathNaryOperator`](../../imathnaryoperator)

### 예제

예제:

```csharp
[C#]
IMathElement baseElement = new MathematicalText("𝑥");
IMathElement lowerLimit = new MathematicalText("1");
IMathElement upperLimit = new MathematicalText("2");
IMathNaryOperator integral = baseElement.Integral(MathIntegralTypes.Simple, lowerLimit, upperLimit, MathLimitLocations.UnderOver);
```

### 참조

* 인터페이스 [IMathNaryOperator](../../imathnaryoperator)
* 열거형 [MathIntegralTypes](../../mathintegraltypes)
* 인터페이스 [IMathElement](../../imathelement)
* 열거형 [MathLimitLocations](../../mathlimitlocations)
* 클래스 [MathElementBase](../../mathelementbase)
* 네임스페이스 [Aspose.Slides.MathText](../../mathelementbase)
* 어셈블리 [Aspose.Slides](../../../)

---

## Integral(MathIntegralTypes, IMathElement, IMathElement) {#integral_1}

적분을 수행합니다

```csharp
public IMathNaryOperator Integral(MathIntegralTypes integralType, IMathElement lowerLimit, 
    IMathElement upperLimit)
```

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| integralType | MathIntegralTypes | 적분 유형 |
| lowerLimit | IMathElement | 적분의 하한 |
| upperLimit | IMathElement | 적분의 상한 |

### 반환값

New instance of type [`IMathNaryOperator`](../../imathnaryoperator)

### 예제

예제:

```csharp
[C#]
IMathElement baseElement = new MathematicalText("𝑥");
IMathElement lowerLimit = new MathematicalText("1");
IMathElement upperLimit = new MathematicalText("2");
IMathNaryOperator integral = baseElement.Integral(MathIntegralTypes.Simple, lowerLimit, upperLimit, MathLimitLocations.UnderOver);
```

### 참조

* 인터페이스 [IMathNaryOperator](../../imathnaryoperator)
* 열거형 [MathIntegralTypes](../../mathintegraltypes)
* 인터페이스 [IMathElement](../../imathelement)
* 클래스 [MathElementBase](../../mathelementbase)
* 네임스페이스 [Aspose.Slides.MathText](../../mathelementbase)
* 어셈블리 [Aspose.Slides](../../../)

---

## Integral(MathIntegralTypes) {#integral}

한계 없이 적분을 수행합니다

```csharp
public IMathNaryOperator Integral(MathIntegralTypes integralType)
```

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| integralType | MathIntegralTypes | 적분 유형 |

### 반환값

New instance of type [`IMathNaryOperator`](../../imathnaryoperator)

### 예제

예제:

```csharp
[C#]
IMathElement baseElement = new MathematicalText("𝑥");
IMathNaryOperator integral = baseElement.Integral(MathIntegralTypes.Contour);
```

### 참조

* 인터페이스 [IMathNaryOperator](../../imathnaryoperator)
* 열거형 [MathIntegralTypes](../../mathintegraltypes)
* 클래스 [MathElementBase](../../mathelementbase)
* 네임스페이스 [Aspose.Slides.MathText](../../mathelementbase)
* 어셈블리 [Aspose.Slides](../../../)

---

## Integral(MathIntegralTypes, string, string, MathLimitLocations) {#integral_4}

적분을 수행합니다

```csharp
public IMathNaryOperator Integral(MathIntegralTypes integralType, string lowerLimit, 
    string upperLimit, MathLimitLocations limitLocations)
```

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| integralType | MathIntegralTypes | 적분 유형 |
| lowerLimit | String | 적분의 하한 |
| upperLimit | String | 적분의 상한 |
| limitLocations | MathLimitLocations | 한계 위치 |

### 반환값

New instance of type [`IMathNaryOperator`](../../imathnaryoperator)

### 예제

예제:

```csharp
[C#]
IMathElement baseElement = new MathematicalText("𝑥");
IMathNaryOperator integral = baseElement.Integral(MathIntegralTypes.Simple, "1", "5", MathLimitLocations.UnderOver);
```

### 참조

* 인터페이스 [IMathNaryOperator](../../imathnaryoperator)
* 열거형 [MathIntegralTypes](../../mathintegraltypes)
* 열거형 [MathLimitLocations](../../mathlimitlocations)
* 클래스 [MathElementBase](../../mathelementbase)
* 네임스페이스 [Aspose.Slides.MathText](../../mathelementbase)
* 어셈블리 [Aspose.Slides](../../../)

---

## Integral(MathIntegralTypes, string, string) {#integral_3}

적분을 수행합니다

```csharp
public IMathNaryOperator Integral(MathIntegralTypes integralType, string lowerLimit, 
    string upperLimit)
```

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| integralType | MathIntegralTypes | 적분 유형 |
| lowerLimit | String | 적분의 하한 |
| upperLimit | String | 적분의 상한 |

### 반환값

New instance of type [`IMathNaryOperator`](../../imathnaryoperator)

### 예제

예제:

```csharp
[C#]
IMathElement baseElement = new MathematicalText("𝑥");
IMathNaryOperator integral = baseElement.Integral(MathIntegralTypes.Simple, "1", "5");
```

### 참조

* 인터페이스 [IMathNaryOperator](../../imathnaryoperator)
* 열거형 [MathIntegralTypes](../../mathintegraltypes)
* 클래스 [MathElementBase](../../mathelementbase)
* 네임스페이스 [Aspose.Slides.MathText](../../mathelementbase)
* 어셈블리 [Aspose.Slides](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->