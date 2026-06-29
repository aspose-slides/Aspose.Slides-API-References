---
title: Integral
second_title: Aspose.Sildes for .NET API リファレンス
description: 積分を取得します
type: docs
weight: 70
url: /ja/aspose.slides.mathtext/mathelementbase/integral/
---
## Integral(MathIntegralTypes, IMathElement, IMathElement, MathLimitLocations) {#integral_2}

積分を取得します

```csharp
public IMathNaryOperator Integral(MathIntegralTypes integralType, IMathElement lowerLimit, 
    IMathElement upperLimit, MathLimitLocations limitLocations)
```

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| integralType | MathIntegralTypes | 積分タイプ |
| lowerLimit | IMathElement | 積分の下限 |
| upperLimit | IMathElement | 積分の上限 |
| limitLocations | MathLimitLocations | 限界の位置 |

### 戻り値

[`IMathNaryOperator`](../../imathnaryoperator) 型の新しいインスタンス

### 例

例:

```csharp
[C#]
IMathElement baseElement = new MathematicalText("𝑥");
IMathElement lowerLimit = new MathematicalText("1");
IMathElement upperLimit = new MathematicalText("2");
IMathNaryOperator integral = baseElement.Integral(MathIntegralTypes.Simple, lowerLimit, upperLimit, MathLimitLocations.UnderOver);
```

### 参照

* インターフェイス [IMathNaryOperator](../../imathnaryoperator)
* 列挙型 [MathIntegralTypes](../../mathintegraltypes)
* インターフェイス [IMathElement](../../imathelement)
* 列挙型 [MathLimitLocations](../../mathlimitlocations)
* クラス [MathElementBase](../../mathelementbase)
* 名前空間 [Aspose.Slides.MathText](../../mathelementbase)
* アセンブリ [Aspose.Slides](../../../)

---

## Integral(MathIntegralTypes, IMathElement, IMathElement) {#integral_1}

積分を取得します

```csharp
public IMathNaryOperator Integral(MathIntegralTypes integralType, IMathElement lowerLimit, 
    IMathElement upperLimit)
```

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| integralType | MathIntegralTypes | 積分タイプ |
| lowerLimit | IMathElement | 積分の下限 |
| upperLimit | IMathElement | 積分の上限 |

### 戻り値

[`IMathNaryOperator`](../../imathnaryoperator) 型の新しいインスタンス

### 例

例:

```csharp
[C#]
IMathElement baseElement = new MathematicalText("𝑥");
IMathElement lowerLimit = new MathematicalText("1");
IMathElement upperLimit = new MathematicalText("2");
IMathNaryOperator integral = baseElement.Integral(MathIntegralTypes.Simple, lowerLimit, upperLimit, MathLimitLocations.UnderOver);
```

### 参照

* インターフェイス [IMathNaryOperator](../../imathnaryoperator)
* 列挙型 [MathIntegralTypes](../../mathintegraltypes)
* インターフェイス [IMathElement](../../imathelement)
* クラス [MathElementBase](../../mathelementbase)
* 名前空間 [Aspose.Slides.MathText](../../mathelementbase)
* アセンブリ [Aspose.Slides](../../../)

---

## Integral(MathIntegralTypes) {#integral}

限界なしで積分を取得します

```csharp
public IMathNaryOperator Integral(MathIntegralTypes integralType)
```

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| integralType | MathIntegralTypes | 積分タイプ |

### 戻り値

[`IMathNaryOperator`](../../imathnaryoperator) 型の新しいインスタンス

### 例

例:

```csharp
[C#]
IMathElement baseElement = new MathematicalText("𝑥");
IMathNaryOperator integral = baseElement.Integral(MathIntegralTypes.Contour);
```

### 参照

* インターフェイス [IMathNaryOperator](../../imathnaryoperator)
* 列挙型 [MathIntegralTypes](../../mathintegraltypes)
* クラス [MathElementBase](../../mathelementbase)
* 名前空間 [Aspose.Slides.MathText](../../mathelementbase)
* アセンブリ [Aspose.Slides](../../../)

---

## Integral(MathIntegralTypes, string, string, MathLimitLocations) {#integral_4}

積分を取得します

```csharp
public IMathNaryOperator Integral(MathIntegralTypes integralType, string lowerLimit, 
    string upperLimit, MathLimitLocations limitLocations)
```

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| integralType | MathIntegralTypes | 積分タイプ |
| lowerLimit | String | 積分の下限 |
| upperLimit | String | 積分の上限 |
| limitLocations | MathLimitLocations | 限界の位置 |

### 戻り値

[`IMathNaryOperator`](../../imathnaryoperator) 型の新しいインスタンス

### 例

例:

```csharp
[C#]
IMathElement baseElement = new MathematicalText("𝑥");
IMathNaryOperator integral = baseElement.Integral(MathIntegralTypes.Simple, "1", "5", MathLimitLocations.UnderOver);
```

### 参照

* インターフェイス [IMathNaryOperator](../../imathnaryoperator)
* 列挙型 [MathIntegralTypes](../../mathintegraltypes)
* 列挙型 [MathLimitLocations](../../mathlimitlocations)
* クラス [MathElementBase](../../mathelementbase)
* 名前空間 [Aspose.Slides.MathText](../../mathelementbase)
* アセンブリ [Aspose.Slides](../../../)

---

## Integral(MathIntegralTypes, string, string) {#integral_3}

積分を取得します

```csharp
public IMathNaryOperator Integral(MathIntegralTypes integralType, string lowerLimit, 
    string upperLimit)
```

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| integralType | MathIntegralTypes | 積分タイプ |
| lowerLimit | String | 積分の下限 |
| upperLimit | String | 積分の上限 |

### 戻り値

[`IMathNaryOperator`](../../imathnaryoperator) 型の新しいインスタンス

### 例

例:

```csharp
[C#]
IMathElement baseElement = new MathematicalText("𝑥");
IMathNaryOperator integral = baseElement.Integral(MathIntegralTypes.Simple, "1", "5");
```

### 参照

* インターフェイス [IMathNaryOperator](../../imathnaryoperator)
* 列挙型 [MathIntegralTypes](../../mathintegraltypes)
* クラス [MathElementBase](../../mathelementbase)
* 名前空間 [Aspose.Slides.MathText](../../mathelementbase)
* アセンブリ [Aspose.Slides](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->