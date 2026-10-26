---
title: ILegacyDiagram
second_title: Aspose.Slides dla Java – Dokumentacja API
description: Reprezentuje starszy obiekt diagramu
type: docs
url: /pl/com.aspose.slides/ilegacydiagram/
---
**Wszystkie zaimplementowane interfejsy:**
[com.aspose.slides.IGraphicalObject](../../com.aspose.slides/igraphicalobject)
```
public interface ILegacyDiagram extends IGraphicalObject
```

Reprezentuje starszy obiekt diagramu
## Metody

| Metoda | Opis |
| --- | --- |
| [convertToSmartArt()](#convertToSmartArt--) | Konwertuje starszy diagram na edytowalny obiekt SmartArt. |
| [convertToGroupShape()](#convertToGroupShape--) | Konwertuje starszy diagram na edytowalny kształt grupy. |
### convertToSmartArt() {#convertToSmartArt--}
```
public abstract ISmartArt convertToSmartArt()
```

Konwertuje starszy diagram na edytowalny obiekt SmartArt. Utworzony obiekt SmartArt jest dodawany do nadrzędnego kształtu grupy w tej samej pozycji.

**Zwraca:**
[ISmartArt](../../com.aspose.slides/ismartart) - Utworzony obiekt SmartArt.
### convertToGroupShape() {#convertToGroupShape--}
```
public abstract IGroupShape convertToGroupShape()
```

Konwertuje starszy diagram na edytowalny kształt grupy. Utworzony obiekt GroupShape jest dodawany do nadrzędnego kształtu grupy w tej samej pozycji.

**Zwraca:**
[IGroupShape](../../com.aspose.slides/igroupshape) - Utworzony obiekt GroupShape.