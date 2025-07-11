---  
title: SetSubSuperscriptOnTheRight
second_title: Referencia de API de Aspose.Slides para .NET  
description: Crea subíndices y superíndices a la derecha
type: docs
weight: 150  
url: /es/aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheright/
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

### Valor de Retorno  

Nuevo elemento matemático del tipo [`IMathRightSubSuperscriptElement`](../../imathrightsubsuperscriptelement)  

### Ejemplos  

Ejemplo:  

```csharp  
[C#]  
IMathElement baseElement = new MathematicalText("N");  
IMathElement subscript = new MathematicalText("i");  
IMathElement superscript = new MathematicalText("j");  
IMathRightSubSuperscriptElement subsuperscript = baseElement.SetSubSuperscriptOnTheRight(subscript, superscript);  
```  

### Ver También  

* interfaz [IMathRightSubSuperscriptElement](../../imathrightsubsuperscriptelement)  
* interfaz [IMathElement](../../imathelement)  
* clase [MathElementBase](../../mathelementbase)  
* espacio de nombres [Aspose.Slides.MathText](../../mathelementbase)  
* ensamblaje [Aspose.Slides](../../../)  

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

### Valor de Retorno  

Nuevo elemento matemático del tipo [`IMathRightSubSuperscriptElement`](../../imathrightsubsuperscriptelement)  

### Ejemplos  

Ejemplo:  

```csharp  
[C#]  
IMathElement baseElement = new MathematicalText("N");  
IMathRightSubSuperscriptElement subsuperscript = baseElement.SetSubSuperscriptOnTheRight("i", "j");  
```  

### Ver También  

* interfaz [IMathRightSubSuperscriptElement](../../imathrightsubsuperscriptelement)  
* clase [MathElementBase](../../mathelementbase)  
* espacio de nombres [Aspose.Slides.MathText](../../mathelementbase)  
* ensamblaje [Aspose.Slides](../../../)  

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->  