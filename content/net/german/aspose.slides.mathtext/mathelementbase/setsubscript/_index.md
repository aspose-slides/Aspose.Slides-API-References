---  
title: SetSubscript
second_title: Aspose.Sildes für .NET API Referenz  
description: Erstellt Tiefstellung
type: docs
weight: 130  
url: /de/aspose.slides.mathtext/mathelementbase/setsubscript/
---  
  
## SetSubscript(IMathElement) {#setsubscript}  
  
Erstellt Tiefstellung  
  
```csharp  
public IMathSubscriptElement SetSubscript(IMathElement subscript)  
```  
  
| Parameter | Typ | Beschreibung |  
| --- | --- | --- |  
| subscript | IMathElement | Tiefstellung (unterer Index rechts) |  
  
### Rückgabewert  
  
Neues mathematisches Element vom Typ [`IMathSubscriptElement`](../../imathsubscriptelement)  
  
### Beispiele  
  
Beispiel:  
  
```csharp  
[C#]  
IMathElement element = new MathematicalText("N");  
IMathElement index = new MathematicalText("i");  
IMathSubscriptElement subscript = element.SetSubscript(index);  
```  
  
### Siehe auch  
  
* Schnittstelle [IMathSubscriptElement](../../imathsubscriptelement)  
* Schnittstelle [IMathElement](../../imathelement)  
* Klasse [MathElementBase](../../mathelementbase)  
* Namespace [Aspose.Slides.MathText](../../mathelementbase)  
* Assembly [Aspose.Slides](../../../)  
  
---  
  
## SetSubscript(string) {#setsubscript_1}  
  
Erstellt Tiefstellung  
  
```csharp  
public IMathSubscriptElement SetSubscript(string subscript)  
```  
  
| Parameter | Typ | Beschreibung |  
| --- | --- | --- |  
| subscript | String | Tiefstellung (unterer Index rechts) |  
  
### Rückgabewert  
  
Neues mathematisches Element vom Typ [`IMathSubscriptElement`](../../imathsubscriptelement)  
  
### Beispiele  
  
Beispiel:  
  
```csharp  
[C#]  
IMathElement element = new MathematicalText("N");  
IMathSubscriptElement subscript = element.SetSubscript("i");  
```  
  
### Siehe auch  
  
* Schnittstelle [IMathSubscriptElement](../../imathsubscriptelement)  
* Klasse [MathElementBase](../../mathelementbase)  
* Namespace [Aspose.Slides.MathText](../../mathelementbase)  
* Assembly [Aspose.Slides](../../../)  
  
<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->