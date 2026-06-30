---
title: Integral
second_title: Aspose.Sildes para .NET Referência da API
description: Calcula a integral
type: docs
weight: 80
url: /pt/aspose.slides.mathtext/imathelement/integral/
---
## Integral(MathIntegralTypes, IMathElement, IMathElement, MathLimitLocations) {#integral_2}

Calcula a integral

```csharp
public IMathNaryOperator Integral(MathIntegralTypes integralType, IMathElement lowerLimit, 
    IMathElement upperLimit, MathLimitLocations limitLocations)
```

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| integralType | MathIntegralTypes | Tipo integral |
| lowerLimit | IMathElement | Limite inferior da integral |
| upperLimit | IMathElement | Limite superior da integral |
| limitLocations | MathLimitLocations | localização dos limites |

### Valor de Retorno

Nova instância do tipo [`IMathNaryOperator`](../../imathnaryoperator)

### Exemplos

Exemplo:

```csharp
[C#]
IMathElement baseElement = new MathematicalText("𝑥");
IMathElement lowerLimit = new MathematicalText("1");
IMathElement upperLimit = new MathematicalText("2");
IMathNaryOperator integral = baseElement.Integral(MathIntegralTypes.Simple, lowerLimit, upperLimit, MathLimitLocations.UnderOver);
```

### Ver Também

* interface [IMathNaryOperator](../../imathnaryoperator)
* enum [MathIntegralTypes](../../mathintegraltypes)
* enum [MathLimitLocations](../../mathlimitlocations)
* interface [IMathElement](../../imathelement)
* namespace [Aspose.Slides.MathText](../../imathelement)
* assembly [Aspose.Slides](../../../)

---

## Integral(MathIntegralTypes, IMathElement, IMathElement) {#integral_1}

Calcula a integral

```csharp
public IMathNaryOperator Integral(MathIntegralTypes integralType, IMathElement lowerLimit, 
    IMathElement upperLimit)
```

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| integralType | MathIntegralTypes | Tipo integral |
| lowerLimit | IMathElement | Limite inferior da integral |
| upperLimit | IMathElement | Limite superior da integral |

### Valor de Retorno

Nova instância do tipo [`IMathNaryOperator`](../../imathnaryoperator)

### Exemplos

Exemplo:

```csharp
[C#]
IMathElement baseElement = new MathematicalText("𝑥");
IMathElement lowerLimit = new MathematicalText("1");
IMathElement upperLimit = new MathematicalText("2");
IMathNaryOperator integral = baseElement.Integral(MathIntegralTypes.Simple, lowerLimit, upperLimit, MathLimitLocations.UnderOver);
```

### Ver Também

* interface [IMathNaryOperator](../../imathnaryoperator)
* enum [MathIntegralTypes](../../mathintegraltypes)
* interface [IMathElement](../../imathelement)
* namespace [Aspose.Slides.MathText](../../imathelement)
* assembly [Aspose.Slides](../../../)

---

## Integral(MathIntegralTypes) {#integral}

Calcula a integral sem limites

```csharp
public IMathNaryOperator Integral(MathIntegralTypes integralType)
```

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| integralType | MathIntegralTypes | Tipo integral |

### Valor de Retorno

Nova instância do tipo [`IMathNaryOperator`](../../imathnaryoperator)

### Exemplos

Exemplo:

```csharp
[C#]
IMathElement baseElement = new MathematicalText("𝑥");
IMathNaryOperator integral = baseElement.Integral(MathIntegralTypes.Contour);
```

### Ver Também

* interface [IMathNaryOperator](../../imathnaryoperator)
* enum [MathIntegralTypes](../../mathintegraltypes)
* interface [IMathElement](../../imathelement)
* namespace [Aspose.Slides.MathText](../../imathelement)
* assembly [Aspose.Slides](../../../)

---

## Integral(MathIntegralTypes, string, string, MathLimitLocations) {#integral_4}

Calcula a integral

```csharp
public IMathNaryOperator Integral(MathIntegralTypes integralType, string lowerLimit, 
    string upperLimit, MathLimitLocations limitLocations)
```

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| integralType | MathIntegralTypes | Tipo integral |
| lowerLimit | String | Limite inferior da integral |
| upperLimit | String | Limite superior da integral |
| limitLocations | MathLimitLocations | localização dos limites |

### Valor de Retorno

Nova instância do tipo [`IMathNaryOperator`](../../imathnaryoperator)

### Exemplos

Exemplo:

```csharp
[C#]
IMathElement baseElement = new MathematicalText("𝑥");
IMathNaryOperator integral = baseElement.Integral(MathIntegralTypes.Simple, "1", "5", MathLimitLocations.UnderOver);
```

### Ver Também

* interface [IMathNaryOperator](../../imathnaryoperator)
* enum [MathIntegralTypes](../../mathintegraltypes)
* enum [MathLimitLocations](../../mathlimitlocations)
* interface [IMathElement](../../imathelement)
* namespace [Aspose.Slides.MathText](../../imathelement)
* assembly [Aspose.Slides](../../../)

---

## Integral(MathIntegralTypes, string, string) {#integral_3}

Calcula a integral

```csharp
public IMathNaryOperator Integral(MathIntegralTypes integralType, string lowerLimit, 
    string upperLimit)
```

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| integralType | MathIntegralTypes | Tipo integral |
| lowerLimit | String | Limite inferior da integral |
| upperLimit | String | Limite superior da integral |

### Valor de Retorno

Nova instância do tipo [`IMathNaryOperator`](../../imathnaryoperator)

### Exemplos

Exemplo:

```csharp
[C#]
IMathElement baseElement = new MathematicalText("𝑥");
IMathNaryOperator integral = baseElement.Integral(MathIntegralTypes.Simple, "1", "5");
```

### Ver Também

* interface [IMathNaryOperator](../../imathnaryoperator)
* enum [MathIntegralTypes](../../mathintegraltypes)
* interface [IMathElement](../../imathelement)
* namespace [Aspose.Slides.MathText](../../imathelement)
* assembly [Aspose.Slides](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->