---
title: ILegacyDiagram
second_title: Aspose.Slides voor Android via Java API-referentie
description: Stelt een legacy diagramobject voor
type: docs
url: /nl/com.aspose.slides/ilegacydiagram/
---
**Alle geïmplementeerde interfaces:**
[com.aspose.slides.IGraphicalObject](../../com.aspose.slides/igraphicalobject)
```
public interface ILegacyDiagram extends IGraphicalObject
```

Stelt een legacy diagramobject voor
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [convertToSmartArt()](#convertToSmartArt--) | Converteert legacy digram naar bewerkbaar SmartArt-object. |
| [convertToGroupShape()](#convertToGroupShape--) | Converteert legacy digram naar bewerkbare groepsvorm. |
### convertToSmartArt() {#convertToSmartArt--}
```
public abstract ISmartArt convertToSmartArt()
```

Converteert legacy digram naar bewerkbaar SmartArt-object. Het gemaakte SmartArt-object wordt toegevoegd aan de bovenliggende groepsvorm op dezelfde positie.

**Retour:**
[ISmartArt](../../com.aspose.slides/ismartart) - Aangemaakt SmartArt-object.
### convertToGroupShape() {#convertToGroupShape--}
```
public abstract IGroupShape convertToGroupShape()
```

Converteert legacy digram naar bewerkbare groepsvorm. Het gemaakte GroupShape-object wordt toegevoegd aan de bovenliggende groepsvorm op dezelfde positie.

**Retour:**
[IGroupShape](../../com.aspose.slides/igroupshape) - Aangemaakt GroupShape-object.