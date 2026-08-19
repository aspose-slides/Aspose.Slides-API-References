---
title: ILegacyDiagram
second_title: Riferimento API di Aspose.Slides per Java
description: Rappresenta un oggetto diagramma legacy
type: docs
url: /it/com.aspose.slides/ilegacydiagram/
---
**Tutte le interfacce implementate:**
[com.aspose.slides.IGraphicalObject](../../com.aspose.slides/igraphicalobject)
```
public interface ILegacyDiagram extends IGraphicalObject
```

Rappresenta un oggetto diagramma legacy
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [convertToSmartArt()](#convertToSmartArt--) | Converte il diagramma legacy in un oggetto SmartArt modificabile. |
| [convertToGroupShape()](#convertToGroupShape--) | Converte il diagramma legacy in una forma di gruppo modificabile. |
### convertToSmartArt() {#convertToSmartArt--}
```
public abstract ISmartArt convertToSmartArt()
```


Converte il diagramma legacy in un oggetto SmartArt modificabile. L'oggetto SmartArt creato viene aggiunto alla forma di gruppo padre nella stessa posizione.

**Restituisce:**
[ISmartArt](../../com.aspose.slides/ismartart) - Oggetto SmartArt creato.
### convertToGroupShape() {#convertToGroupShape--}
```
public abstract IGroupShape convertToGroupShape()
```


Converte il diagramma legacy in una forma di gruppo modificabile. L'oggetto GroupShape creato viene aggiunto alla forma di gruppo padre nella stessa posizione.

**Restituisce:**
[IGroupShape](../../com.aspose.slides/igroupshape) - Oggetto GroupShape creato.