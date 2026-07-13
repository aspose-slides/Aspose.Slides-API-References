---
title: LegacyDiagram
second_title: Aspose.Slides pro Android prostřednictvím Java API Reference
description: Reprezentuje starý objekt diagramu.
type: docs
url: /cs/com.aspose.slides/legacydiagram/
---
**Dědičnost:**
java.lang.Object, [com.aspose.slides.Shape](../../com.aspose.slides/shape), [com.aspose.slides.GraphicalObject](../../com.aspose.slides/graphicalobject)

**Všechna implementovaná rozhraní:**
[com.aspose.slides.ILegacyDiagram](../../com.aspose.slides/ilegacydiagram)
```
public class LegacyDiagram extends GraphicalObject implements ILegacyDiagram
```

Reprezentuje starší objekt diagramu.
## Metody

| Metoda | Popis |
| --- | --- |
| [convertToSmartArt()](#convertToSmartArt--) | Převádí starý diagram na editovatelný objekt SmartArt. |
| [convertToGroupShape()](#convertToGroupShape--) | Převádí starý diagram na editovatelný skupinový tvar. |
### convertToSmartArt() {#convertToSmartArt--}
```
public final ISmartArt convertToSmartArt()
```

Převádí starý diagram na editovatelný objekt SmartArt. Vytvořený objekt SmartArt se přidá do nadřazeného skupinového tvaru na stejnou pozici.

**Vrací:**
[ISmartArt](../../com.aspose.slides/ismartart) - Vytvořený objekt SmartArt.
### convertToGroupShape() {#convertToGroupShape--}
```
public final IGroupShape convertToGroupShape()
```

Převádí starý diagram na editovatelný skupinový tvar. Vytvořený objekt GroupShape se přidá do nadřazeného skupinového tvaru na stejnou pozici.

**Vrací:**
[IGroupShape](../../com.aspose.slides/igroupshape) - Vytvořený objekt GroupShape.