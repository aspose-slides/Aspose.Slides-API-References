---
title: LegacyDiagram
second_title: Riferimento API Java di Aspose.Slides per Android
description: Rappresenta un oggetto diagramma legacy.
type: docs
url: /it/com.aspose.slides/legacydiagram/
---
**Eredità:**
java.lang.Object, [com.aspose.slides.Shape](../../com.aspose.slides/shape), [com.aspose.slides.GraphicalObject](../../com.aspose.slides/graphicalobject)

**Tutte le interfacce implementate:**
[com.aspose.slides.ILegacyDiagram](../../com.aspose.slides/ilegacydiagram)
```
public class LegacyDiagram extends GraphicalObject implements ILegacyDiagram
```

Rappresenta un oggetto diagramma legacy.

## Metodi

| Metodo | Descrizione |
| --- | --- |
| [convertToSmartArt()](#convertToSmartArt--) | Converte il diagramma legacy in un oggetto SmartArt modificabile. |
| [convertToGroupShape()](#convertToGroupShape--) | Converte il diagramma legacy in una shape di gruppo modificabile. |
### convertToSmartArt() {#convertToSmartArt--}
```
public final ISmartArt convertToSmartArt()
```

Converte il diagramma legacy in un oggetto SmartArt modificabile. L'oggetto SmartArt creato viene aggiunto al gruppo genitore nella stessa posizione.

**Restituisce:**
[ISmartArt](../../com.aspose.slides/ismartart) - Oggetto SmartArt creato.
### convertToGroupShape() {#convertToGroupShape--}
```
public final IGroupShape convertToGroupShape()
```

Converte il diagramma legacy in una shape di gruppo modificabile. L'oggetto GroupShape creato viene aggiunto al gruppo genitore nella stessa posizione.

**Restituisce:**
[IGroupShape](../../com.aspose.slides/igroupshape) - Oggetto GroupShape creato.