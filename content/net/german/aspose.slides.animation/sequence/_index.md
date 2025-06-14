---  
title: Sequence
second_title: Aspose.Sildes für .NET API-Referenz  
description: Stellt eine Sequenzsammlung von Effekten dar.
type: docs
weight: 710  
url: /de/aspose.slides.animation/sequence/
---  

## Sequence-Klasse  

Stellt eine Sequenz (Sammlung von Effekten) dar.  

```csharp  
public sealed class Sequence : ISequence  
```  

## Eigenschaften  

| Name | Beschreibung |  
| --- | --- |  
| [Count](../../aspose.slides.animation/sequence/count) { get; } | Gibt die Anzahl der Effekte in einer Sequenz zurück. Nur-lesbares Int32. |  
| [Item](../../aspose.slides.animation/sequence/item) { get; } | Gibt einen Effekt am angegebenen Index zurück. |  
| [TriggerShape](../../aspose.slides.animation/sequence/triggershape) { get; set; } | Gibt die Form zurück oder legt sie für die INTERAKTIVE Sequenz fest. Wenn die Sequenz nicht interaktiv ist, wird null zurückgegeben. Lese-/Schreibzugriff [`IShape`](../../aspose.slides/ishape). |  

## Methoden  

| Name | Beschreibung |  
| --- | --- |  
| [AddEffect](../../aspose.slides.animation/sequence/addeffect#addeffect_2)(IParagraph, EffectType, EffectSubtype, EffectTriggerType) | Fügt einen neuen Animationseffekt für den Absatz am Ende der Sequenz hinzu. |  
| [AddEffect](../../aspose.slides.animation/sequence/addeffect#addeffect_3)(IShape, EffectType, EffectSubtype, EffectTriggerType) | Fügt einen neuen Effekt am Ende der Sequenz hinzu. |  
| [AddEffect](../../aspose.slides.animation/sequence/addeffect#addeffect)(IChart, EffectChartMajorGroupingType, int, EffectType, EffectSubtype, EffectTriggerType) | Fügt den neuen Diagrammanimationseffekt für die Kategorie oder Reihe am Ende der Sequenz hinzu. |  
| [AddEffect](../../aspose.slides.animation/sequence/addeffect#addeffect_1)(IChart, EffectChartMinorGroupingType, int, int, EffectType, EffectSubtype, EffectTriggerType) | Fügt den neuen Diagrammanimationseffekt für Elemente in der Kategorie oder Reihe am Ende der Sequenz hinzu. |  
| [Clear](../../aspose.slides.animation/sequence/clear)() | Entfernt alle Effekte aus einer Sammlung. |  
| [GetCount](../../aspose.slides.animation/sequence/getcount)(IShape) | Gibt die Anzahl der Effekte für die angegebene Form zurück. |  
| [GetEffectsByParagraph](../../aspose.slides.animation/sequence/geteffectsbyparagraph)(IParagraph) | Gibt ein Array von Effekten für den angegebenen Absatz zurück. |  
| [GetEffectsByShape](../../aspose.slides.animation/sequence/geteffectsbyshape)(IShape) | Gibt ein Array von Effekten für die angegebene Form zurück. |  
| [GetEnumerator](../../aspose.slides.animation/sequence/getenumerator)() | Gibt einen Enumerator zurück, der durch die Sammlung iteriert. |  
| [Remove](../../aspose.slides.animation/sequence/remove)(IEffect) | Entfernt den angegebenen Effekt aus einer Sammlung. |  
| [RemoveAt](../../aspose.slides.animation/sequence/removeat)(int) | Entfernt einen Effekt aus einer Sammlung. |  
| [RemoveByShape](../../aspose.slides.animation/sequence/removebyshape)(IShape) | Entfernt den Effekt für die angegebene Form. |  

### Siehe auch  

* Schnittstelle [ISequence](../isequence)  
* Namespace [Aspose.Slides.Animation](../../aspose.slides.animation)  
* Assembly [Aspose.Slides](../../)  

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->