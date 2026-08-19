---
title: LegacyDiagram
second_title: Aspose.Slides voor Java API-referentie
description: Stelt een legacy-diagramobject voor.
type: docs
url: /nl/com.aspose.slides/legacydiagram/
---
**Erfgoed:**
java.lang.Object, [com.aspose.slides.Shape](../../com.aspose.slides/shape), [com.aspose.slides.GraphicalObject](../../com.aspose.slides/graphicalobject)

**Alle geïmplementeerde interfaces:**
[com.aspose.slides.ILegacyDiagram](../../com.aspose.slides/ilegacydiagram)
```
public class LegacyDiagram extends GraphicalObject implements ILegacyDiagram
```

Stelt een legacy-diagramobject voor.
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [convertToSmartArt()](#convertToSmartArt--) | Converteert legacy digram naar bewerkbaar SmartArt-object. |
| [convertToGroupShape()](#convertToGroupShape--) | Converteert legacy digram naar bewerkbare groepsvorm. |
### convertToSmartArt() {#convertToSmartArt--}
```
public final ISmartArt convertToSmartArt()
```


Converteert legacy digram naar bewerkbaar SmartArt-object. Het gemaakte SmartArt-object wordt toegevoegd aan de parent group shape op dezelfde positie.

**Retour:**
[ISmartArt](../../com.aspose.slides/ismartart) - Gemaakt SmartArt-object.
### convertToGroupShape() {#convertToGroupShape--}
```
public final IGroupShape convertToGroupShape()
```


Converteert legacy digram naar bewerkbare groepsvorm. Het gemaakte GroupShape-object wordt toegevoegd aan de parent group shape op dezelfde positie.

**Retour:**
[IGroupShape](../../com.aspose.slides/igroupshape) - Gemaakt GroupShape-object.