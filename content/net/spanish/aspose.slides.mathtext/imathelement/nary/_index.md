---
title: N-ario
second_title: Aspose.Sildes para .NET API Referencia
description: Crea un operador N-ario
type: docs
weight: 100
url: /es/aspose.slides.mathtext/imathelement/nary/
---

## Nary(MathNaryOperatorTypes, IMathElement, IMathElement) {#nary}

Crea un operador N-ario

```csharp
public IMathNaryOperator Nary(MathNaryOperatorTypes type, IMathElement lowerLimit, 
    IMathElement upperLimit)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| type | MathNaryOperatorTypes | El tipo de operador N-ario |
| lowerLimit | IMathElement | El límite inferior |
| upperLimit | IMathElement | El límite superior |

### Valor de Retorno

Nueva instancia del tipo [`IMathNaryOperator`](../../imathnaryoperator)

### Ejemplos

Ejemplo:

```csharp
[C#]
IMathElement baseElement = new MathematicalText("i-1");
IMathElement lowerLimit = new MathematicalText("i=0");
IMathElement upperLimit = new MathematicalText("𝑛");
IMathNaryOperator naryOperator = baseElement.Nary(MathNaryOperatorTypes.Summation, lowerLimit, upperLimit);
```

### Ver También

* interfaz [IMathNaryOperator](../../imathnaryoperator)
* enum [MathNaryOperatorTypes](../../mathnaryoperatortypes)
* interfaz [IMathElement](../../imathelement)
* espacio de nombres [Aspose.Slides.MathText](../../imathelement)
* ensamblado [Aspose.Slides](../../../)

---

## Nary(MathNaryOperatorTypes, string, string) {#nary_1}

Crea un operador N-ario

```csharp
public IMathNaryOperator Nary(MathNaryOperatorTypes type, string lowerLimit, string upperLimit)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| type | MathNaryOperatorTypes | El tipo de operador N-ario |
| lowerLimit | String | El límite inferior |
| upperLimit | String | El límite superior |

### Valor de Retorno

Nueva instancia del tipo [`IMathNaryOperator`](../../imathnaryoperator)

### Ejemplos

Ejemplo:

```csharp
[C#]
IMathNaryOperator naryOperator = new MathematicalText("i").Nary(MathNaryOperatorTypes.Summation, "i=0", "𝑛");
```

### Ver También

* interfaz [IMathNaryOperator](../../imathnaryoperator)
* enum [MathNaryOperatorTypes](../../mathnaryoperatortypes)
* interfaz [IMathElement](../../imathelement)
* espacio de nombres [Aspose.Slides.MathText](../../imathelement)
* ensamblado [Aspose.Slides](../../../)

<!-- NO EDITAR: generado por xmldocmd para Aspose.Slides.dll -->