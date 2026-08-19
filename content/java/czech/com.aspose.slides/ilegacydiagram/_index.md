---
title: ILegacyDiagram
second_title: Aspose.Slides pro Java API Reference
description: Reprezentuje starý diagramový objekt
type: docs
url: /cs/com.aspose.slides/ilegacydiagram/
---
**Všechny implementované rozhraní:**
[com.aspose.slides.IGraphicalObject](../../com.aspose.slides/igraphicalobject)
```
public interface ILegacyDiagram extends IGraphicalObject
```

Reprezentuje starý diagramový objekt
## Metody

| Metoda | Popis |
| --- | --- |
| [convertToSmartArt()](#convertToSmartArt--) | Převádí starý diagram na editovatelný objekt SmartArt. |
| [convertToGroupShape()](#convertToGroupShape--) | Převádí starý diagram na editovatelný skupinový tvar. |
### convertToSmartArt() {#convertToSmartArt--}
```
public abstract ISmartArt convertToSmartArt()
```


Převádí starý diagram na editovatelný objekt SmartArt. Vytvořený objekt SmartArt se přidá do nadřazeného skupinového tvaru na stejné pozici.

**Vrací:**
[ISmartArt](../../com.aspose.slides/ismartart) - Vytvořený objekt SmartArt.
### convertToGroupShape() {#convertToGroupShape--}
```
public abstract IGroupShape convertToGroupShape()
```


Převádí starý diagram na editovatelný skupinový tvar. Vytvořený objekt GroupShape se přidá do nadřazeného skupinového tvaru na stejné pozici.

**Vrací:**
[IGroupShape](../../com.aspose.slides/igroupshape) - Vytvořený objekt GroupShape.