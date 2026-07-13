---
title: ILegacyDiagram
second_title: Aspose.Slides pro Android prostřednictvím Java API Reference
description: Representuje objekt legacy diagramu
type: docs
url: /cs/com.aspose.slides/ilegacydiagram/
---
**Všechny implementované rozhraní:**
[com.aspose.slides.IGraphicalObject](../../com.aspose.slides/igraphicalobject)
```
public interface ILegacyDiagram extends IGraphicalObject
```

Representuje objekt legacy diagramu
## Metody

| Metoda | Popis |
| --- | --- |
| [convertToSmartArt()](#convertToSmartArt--) | Převádí legacy diagram na editovatelný objekt SmartArt. |
| [convertToGroupShape()](#convertToGroupShape--) | Převádí legacy diagram na editovatelný skupinový tvar. |
### convertToSmartArt() {#convertToSmartArt--}
```
public abstract ISmartArt convertToSmartArt()
```


Převádí legacy diagram na editovatelný objekt SmartArt. Vytvořený objekt SmartArt se přidá do nadřazeného grupového tvaru na stejné pozici.

**Vrací:**
[ISmartArt](../../com.aspose.slides/ismartart) - Vytvořený objekt SmartArt.
### convertToGroupShape() {#convertToGroupShape--}
```
public abstract IGroupShape convertToGroupShape()
```


Převádí legacy diagram na editovatelný skupinový tvar. Vytvořený objekt GroupShape se přidá do nadřazeného grupového tvaru na stejné pozici.

**Vrací:**
[IGroupShape](../../com.aspose.slides/igroupshape) - Vytvořený objekt GroupShape.