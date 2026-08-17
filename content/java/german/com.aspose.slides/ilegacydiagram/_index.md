---
title: ILegacyDiagram
second_title: Aspose.Slides für Java API Referenz
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
| [convertToSmartArt()](#convertToSmartArt--) | Konvertiert das Legacy-Diagramm in ein editierbares SmartArt-Objekt. |
| [convertToGroupShape()](#convertToGroupShape--) | Konvertiert das Legacy-Diagramm in ein editierbares GroupShape-Objekt. |
### convertToSmartArt() {#convertToSmartArt--}
```
public abstract ISmartArt convertToSmartArt()
```

Konvertiert das Legacy-Diagramm in ein editierbares SmartArt-Objekt. Das erstellte SmartArt-Objekt wird an derselben Position zur übergeordneten Gruppe hinzugefügt.

**Rückgabe:**
[ISmartArt](../../com.aspose.slides/ismartart) - Erstelltes SmartArt-Objekt.
### convertToGroupShape() {#convertToGroupShape--}
```
public abstract IGroupShape convertToGroupShape()
```

Konvertiert das Legacy-Diagramm in ein editierbares GroupShape-Objekt. Das erstellte GroupShape-Objekt wird an derselben Position zur übergeordneten Gruppe hinzugefügt.

**Rückgabe:**
[IGroupShape](../../com.aspose.slides/igroupshape) - Erstelltes GroupShape-Objekt.