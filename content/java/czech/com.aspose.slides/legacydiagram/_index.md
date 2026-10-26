---
title: LegacyDiagram
second_title: Aspose.Slides pro Java API Reference
description: Představuje objekt staršího diagramu.
type: docs
url: /cs/com.aspose.slides/legacydiagram/
---
**Dědičnost:**
java.lang.Object, [com.aspose.slides.Shape](../../com.aspose.slides/shape), [com.aspose.slides.GraphicalObject](../../com.aspose.slides/graphicalobject)

**Všechny implementované rozhraní:**
[com.aspose.slides.ILegacyDiagram](../../com.aspose.slides/ilegacydiagram)
```
public class LegacyDiagram extends GraphicalObject implements ILegacyDiagram
```

Představuje objekt staršího diagramu.
## Metody

| Metoda | Popis |
| --- | --- |
| [convertToSmartArt()](#convertToSmartArt--) | Převádí starý diagram na editovatelný objekt SmartArt. |
| [convertToGroupShape()](#convertToGroupShape--) | Převádí starý diagram na editovatelný skupinový tvar. |
### convertToSmartArt() {#convertToSmartArt--}
```
public final ISmartArt convertToSmartArt()
```

Převádí starý diagram na editovatelný objekt SmartArt. Vytvořený objekt SmartArt se přidá k nadřazenému skupinovému tvaru na stejnou pozici.

**Návratová hodnota:**
[ISmartArt](../../com.aspose.slides/ismartart) - Vytvořený objekt SmartArt.
### convertToGroupShape() {#convertToGroupShape--}
```
public final IGroupShape convertToGroupShape()
```

Převádí starý diagram na editovatelný skupinový tvar. Vytvořený objekt GroupShape se přidá k nadřazenému skupinovému tvaru na stejnou pozici.

**Návratová hodnota:**
[IGroupShape](../../com.aspose.slides/igroupshape) - Vytvořený objekt GroupShape.