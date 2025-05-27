---
title: SetSubSuperscriptOnTheRight
second_title: Referencia de la API de Aspose.Slides para .NET
description: Crea subíndices y superíndices a la derecha
type: docs
weight: 160
url: /es/aspose.slides.mathtext/imathelement/setsubsuperscriptontheright/
---

## SetSubSuperscriptOnTheRight(IMathElement, IMathElement) {#setsubsuperscriptontheright}

Crea subíndices y superíndices a la derecha

```csharp
public IMathRightSubSuperscriptElement SetSubSuperscriptOnTheRight(IMathElement subscript, 
    IMathElement superscript)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| subscript | IMathElement | Subíndice (índice inferior a la derecha) |
| superscript | IMathElement | Superíndice (índice superior a la derecha) |

### Valor de retorno

Nuevo elemento matemático de tipo [`IMathRightSubSuperscriptElement`](../../imathrightsubsuperscriptelement)

### Ejemplos

Ejemplo:

```csharp
[C#]
IMathElement baseElement = new MathematicalText("N");
IMathElement subscript = new MathematicalText("i");
IMathElement superscript = new MathematicalText("j");
IMathRightSubSuperscriptElement subsuperscript = baseElement.SetSubSuperscriptOnTheRight(subscript, superscript);
```

### Véase también

* interfaz [IMathRightSubSuperscriptElement](../../imathrightsubsuperscriptelement)
* interfaz [IMathElement](../../imathelement)
* espacio de nombres [Aspose.Slides.MathText](../../imathelement)
* ensamblado [Aspose.Slides](../../../)

---

## SetSubSuperscriptOnTheRight(string, string) {#setsubsuperscriptontheright_1}

Crea subíndices y superíndices a la derecha

```csharp
public IMathRightSubSuperscriptElement SetSubSuperscriptOnTheRight(string subscript, 
    string superscript)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| subscript | String | Subíndice (índice inferior a la derecha) |
| superscript | String | Superíndice (índice superior a la derecha) |

### Valor de retorno

Nuevo elemento matemático de tipo [`IMathRightSubSuperscriptElement`](../../imathrightsubsuperscriptelement)

### Ejemplos

Ejemplo:

```csharp
[C#]
IMathElement baseElement = new MathematicalText("N");
IMathRightSubSuperscriptElement subsuperscript = baseElement.SetSubSuperscriptOnTheRight("i", "j");
```

### Véase también

* interfaz [IMathRightSubSuperscriptElement](../../imathrightsubsuperscriptelement)
* interfaz [IMathElement](../../imathelement)
* espacio de nombres [Aspose.Slides.MathText](../../imathelement)
* ensamblado [Aspose.Slides](../../../)

<!-- NO EDITAR: generado por xmldocmd para Aspose.Slides.dll -->