---
title: LegacyDiagram
second_title: Aspose.Slides für Java API-Referenz
description: Stellt ein Legacy-Diagrammobjekt dar.
type: docs
url: /de/com.aspose.slides/legacydiagram/
---
**Vererbung:**
java.lang.Object, [com.aspose.slides.Shape](../../com.aspose.slides/shape), [com.aspose.slides.GraphicalObject](../../com.aspose.slides/graphicalobject)

**Alle implementierten Schnittstellen:**
[com.aspose.slides.ILegacyDiagram](../../com.aspose.slides/ilegacydiagram)
```
public class LegacyDiagram extends GraphicalObject implements ILegacyDiagram
```

Stellt ein Legacy-Diagrammobjekt dar.
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [convertToSmartArt()](#convertToSmartArt--) | Konvertiert ein Legacy-Diagramm in ein bearbeitbares SmartArt-Objekt. |
| [convertToGroupShape()](#convertToGroupShape--) | Konvertiert ein Legacy-Diagramm in eine bearbeitbare Gruppenform. |
### convertToSmartArt() {#convertToSmartArt--}
```
public final ISmartArt convertToSmartArt()
```

Konvertiert ein Legacy-Diagramm in ein bearbeitbares SmartArt-Objekt. Das erstellte SmartArt-Objekt wird an derselben Position zur übergeordneten Gruppierungsform hinzugefügt.

**Rückgabe:**
[ISmartArt](../../com.aspose.slides/ismartart) - Erstelltes SmartArt-Objekt.
### convertToGroupShape() {#convertToGroupShape--}
```
public final IGroupShape convertToGroupShape()
```

Konvertiert ein Legacy-Diagramm in eine bearbeitbare Gruppenform. Das erstellte GroupShape-Objekt wird an derselben Position zur übergeordneten Gruppierungsform hinzugefügt.

**Rückgabe:**
[IGroupShape](../../com.aspose.slides/igroupshape) - Erstelltes GroupShape-Objekt.