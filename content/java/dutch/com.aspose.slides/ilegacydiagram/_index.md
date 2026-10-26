---
title: ILegacyDiagram
second_title: Aspose.Slides voor Java API-referentie
description: Stelt een legacy-diagramobject voor
type: docs
url: /nl/com.aspose.slides/ilegacydiagram/
---
**Alle geïmplementeerde interfaces:**
[com.aspose.slides.IGraphicalObject](../../com.aspose.slides/igraphicalobject)
```
public interface ILegacyDiagram extends IGraphicalObject
```

Stelt een legacy-diagramobject voor
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [convertToSmartArt()](#convertToSmartArt--) | Converteert legacy-diagram naar bewerkbaar SmartArt-object. |
| [convertToGroupShape()](#convertToGroupShape--) | Converteert legacy-diagram naar bewerkbare groepvorm. |
### convertToSmartArt() {#convertToSmartArt--}
```
public abstract ISmartArt convertToSmartArt()
```

Converteert legacy-diagram naar bewerkbaar SmartArt-object. Het gemaakte SmartArt-object wordt toegevoegd aan de bovenliggende groepvorm op dezelfde positie.

**Retour:**
[ISmartArt](../../com.aspose.slides/ismartart) - Gemaakt SmartArt-object.
### convertToGroupShape() {#convertToGroupShape--}
```
public abstract IGroupShape convertToGroupShape()
```

Converteert legacy-diagram naar bewerkbare groepvorm. Het gemaakte GroupShape-object wordt toegevoegd aan de bovenliggende groepvorm op dezelfde positie.

**Retour:**
[IGroupShape](../../com.aspose.slides/igroupshape) - Gemaakt GroupShape-object.