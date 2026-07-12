---
title: ILegacyDiagram
second_title: Aspose.Slides für Android über Java API Referenz
description: Stellt ein Legacy-Diagrammobjekt dar
type: docs
url: /de/com.aspose.slides/ilegacydiagram/
---
**Alle implementierten Schnittstellen:**
[com.aspose.slides.IGraphicalObject](../../com.aspose.slides/igraphicalobject)
```
public interface ILegacyDiagram extends IGraphicalObject
```

Stellt ein Legacy-Diagrammobjekt dar
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [convertToSmartArt()](#convertToSmartArt--) | Konvertiert legacy digram zu editierbarem SmartArt-Objekt. |
| [convertToGroupShape()](#convertToGroupShape--) | Konvertiert legacy digram zu editierbarer group shape. |
### convertToSmartArt() {#convertToSmartArt--}
```
public abstract ISmartArt convertToSmartArt()
```

Konvertiert legacy digram zu editierbarem SmartArt-Objekt. Das erstellte SmartArt-Objekt wird an derselben Position zur übergeordneten group shape hinzugefügt.

**Rückgabe:**
[ISmartArt](../../com.aspose.slides/ismartart) - Erstelltes SmartArt-Objekt.
### convertToGroupShape() {#convertToGroupShape--}
```
public abstract IGroupShape convertToGroupShape()
```

Konvertiert legacy digram zu editierbarer group shape. Das erstellte GroupShape-Objekt wird an derselben Position zur übergeordneten group shape hinzugefügt.

**Rückgabe:**
[IGroupShape](../../com.aspose.slides/igroupshape) - Erstelltes GroupShape-Objekt.