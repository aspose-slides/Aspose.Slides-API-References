---
title: ILegacyDiagram
second_title: Aspose.Slides dla Androida poprzez odwołanie do Java API
description: Reprezentuje starszy obiekt diagramu
type: docs
url: /pl/com.aspose.slides/ilegacydiagram/
---
**All Implemented Interfaces:**
[com.aspose.slides.IGraphicalObject](../../com.aspose.slides/igraphicalobject)
```
public interface ILegacyDiagram extends IGraphicalObject
```

Reprezentuje starszy obiekt diagramu
## Metody

| Metoda | Opis |
| --- | --- |
| [convertToSmartArt()](#convertToSmartArt--) | Konwertuje starszy digram na edytowalny obiekt SmartArt. |
| [convertToGroupShape()](#convertToGroupShape--) | Konwertuje starszy digram na edytowalny group shape. |
### convertToSmartArt() {#convertToSmartArt--}
```
public abstract ISmartArt convertToSmartArt()
```


Konwertuje starszy digram na edytowalny obiekt SmartArt. Utworzony obiekt SmartArt zostaje dodany do nadrzędnego group shape w tej samej pozycji.

**Zwraca:**
[ISmartArt](../../com.aspose.slides/ismartart) - Utworzony obiekt SmartArt.
### convertToGroupShape() {#convertToGroupShape--}
```
public abstract IGroupShape convertToGroupShape()
```


Konwertuje starszy digram na edytowalny group shape. Utworzony obiekt GroupShape zostaje dodany do nadrzędnego group shape w tej samej pozycji.

**Zwraca:**
[IGroupShape](../../com.aspose.slides/igroupshape) - Utworzony obiekt GroupShape.