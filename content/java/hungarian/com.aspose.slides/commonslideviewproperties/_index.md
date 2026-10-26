---
title: CommonSlideViewProperties
second_title: Aspose.Slides for Java API Hivatkozás
description: Közös dia nézet tulajdonságait képviseli.
type: docs
url: /hu/com.aspose.slides/commonslideviewproperties/
---
**Öröklés:**
java.lang.Object

**Minden megvalósított interfész:**
[com.aspose.slides.ICommonSlideViewProperties](../../com.aspose.slides/icommonslideviewproperties)
```
public class CommonSlideViewProperties implements ICommonSlideViewProperties
```

Közös dia nézet tulajdonságait képviseli.

--------------------

> ```
> The following example shows how to set the zoom value for slide of PowerPoint Presentation.
>  
>  // Létrehoz egy Presentation objektumot, amely egy prezentációs fájlt reprezentál
>  Presentation pres = new Presentation("demo.pptx");
>  try {
>      // A prezentáció nézeti tulajdonságainak beállítása
>      pres.getViewProperties().getSlideViewProperties().setScale(100); // Nagyítási érték százalékban a dia nézethez
>      pres.getViewProperties().getNotesViewProperties().setScale(100); // Nagyítási érték százalékban a jegyzet nézethez
>      pres.save("Zoom_out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

## Metódusok

| Method | Description |
| --- | --- |
| [getScale()](#getScale--) | Megadja a nézet nagyítási arányát százalékban. |
| [setScale(int value)](#setScale-int-) | Megadja a nézet nagyítási arányát százalékban. |
| [getVariableScale()](#getVariableScale--) | Megadja, hogy a nézet tartalma automatikusan méreteződjön a jelenlegi ablakmérethez legjobban illeszkedő módon. |
| [setVariableScale(boolean value)](#setVariableScale-boolean-) | Megadja, hogy a nézet tartalma automatikusan méreteződjön a jelenlegi ablakmérethez legjobban illeszkedő módon. |
| [getDrawingGuides()](#getDrawingGuides--) | Visszaadja a rajzolási segédvonalak gyűjteményét. |

### getScale() {#getScale--}
```
public final int getScale()
```

Megadja a nézet nagyítási arányát százalékban. Olvasás/írás int.

**Visszatérési érték:**
int

### setScale(int value) {#setScale-int-}
```
public final void setScale(int value)
```

Megadja a nézet nagyítási arányát százalékban. Olvasás/írás int.

**Paraméterek:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getVariableScale() {#getVariableScale--}
```
public final boolean getVariableScale()
```

Megadja, hogy a nézet tartalma automatikusan méreteződjön a jelenlegi ablakmérethez legjobban illeszkedő módon. Olvasás/írás boolean.

**Visszatérési érték:**
boolean

### setVariableScale(boolean value) {#setVariableScale-boolean-}
```
public final void setVariableScale(boolean value)
```

Megadja, hogy a nézet tartalma automatikusan méreteződjön a jelenlegi ablakmérethez legjobban illeszkedő módon. Olvasás/írás boolean.

**Paraméterek:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getDrawingGuides() {#getDrawingGuides--}
```
public final IDrawingGuidesCollection getDrawingGuides()
```

Visszaadja a rajzolási segédvonalak gyűjteményét. Csak olvasható [IDrawingGuidesCollection](../../com.aspose.slides/idrawingguidescollection)

--------------------

> ```
> The following sample code shows how to add the new drawing guides in a PowerPoint presentation.
>  
>  Presentation pres = new Presentation();
>  try {
>      Dimension2D slideSize = pres.getSlideSize().getSize();
> 
>      IDrawingGuidesCollection guides = pres.getViewProperties().getSlideViewProperties().getDrawingGuides();
>      // Az új függőleges rajzsegédvonal hozzáadása a dia közepétől jobbra
>      guides.add(Orientation.Vertical, (float)(slideSize.getWidth()) / 2 + 12.5f);
>      // Az új vízszintes rajzsegédvonal hozzáadása a dia közép alatt
>      guides.add(Orientation.Horizontal, (float)(slideSize.getHeight() / 2) + 12.5f);
> 
>      pres.save("DrawingGuides_out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Visszatérési érték:**
[IDrawingGuidesCollection](../../com.aspose.slides/idrawingguidescollection)