---
title: CommonSlideViewProperties
second_title: Aspose.Slides Androidra a Java API referencián keresztül
description: Közös dianézet tulajdonságait képviseli.
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

Közös diavetítés nézet tulajdonságait képviseli.

--------------------

> ```
> The following example shows how to set the zoom value for slide of PowerPoint Presentation.
>  
>  // Hozzon létre egy Presentation objektumot, amely egy bemutató fájlt képvisel
>  Presentation pres = new Presentation("demo.pptx");
>  try {
>      // A bemutató nézetbeállításainak beállítása
>      pres.getViewProperties().getSlideViewProperties().setScale(100); // Nagyítás értéke százalékban a dia nézethez
>      pres.getViewProperties().getNotesViewProperties().setScale(100); // Nagyítás értéke százalékban a jegyzet nézethez
>      pres.save("Zoom_out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

## Metódusok

| Metódus | Leírás |
| --- | --- |
| [getScale()](#getScale--) | Megadja a nézet skálázási arányát százalékban. |
| [setScale(int value)](#setScale-int-) | Megadja a nézet skálázási arányát százalékban. |
| [getVariableScale()](#getVariableScale--) | Megadja, hogy a nézet tartalma automatikusan méreteződjön a legjobb illeszkedés érdekében az aktuális ablakmérethez. |
| [setVariableScale(boolean value)](#setVariableScale-boolean-) | Megadja, hogy a nézet tartalma automatikusan méreteződjön a legjobb illeszkedés érdekében az aktuális ablakmérethez. |
| [getDrawingGuides()](#getDrawingGuides--) | Visszaadja a rajzolási segédvonalak gyűjteményét. |
### getScale() {#getScale--}
```
public final int getScale()
```

Megadja a nézet skálázási arányát százalékban. Olvasás/írás int.

**Visszatér:**
int
### setScale(int value) {#setScale-int-}
```
public final void setScale(int value)
```

Megadja a nézet skálázási arányát százalékban. Olvasás/írás int.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | int |  |
### getVariableScale() {#getVariableScale--}
```
public final boolean getVariableScale()
```

Megadja, hogy a nézet tartalma automatikusan méreteződjön a legjobb illeszkedés érdekében az aktuális ablakmérethez. Olvasás/írás boolean.

**Visszatér:**
boolean
### setVariableScale(boolean value) {#setVariableScale-boolean-}
```
public final void setVariableScale(boolean value)
```

Megadja, hogy a nézet tartalma automatikusan méreteződjön a legjobb illeszkedés érdekében az aktuális ablakmérethez. Olvasás/írás boolean.

**Paraméterek:**
| Paraméter | Típus | Leírás |
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
>      SizeF slideSize = pres.getSlideSize().getSize();
> 
>      IDrawingGuidesCollection guides = pres.getViewProperties().getSlideViewProperties().getDrawingGuides();
>      // Új függőleges rajzolási segéd hozzáadása a dia közepének jobb oldalához
>      guides.add(Orientation.Vertical, (float)(slideSize.getWidth()) / 2 + 12.5f);
>      // Új vízszintes rajzolási segéd hozzáadása a dia közepének alá
>      guides.add(Orientation.Horizontal, (float)(slideSize.getHeight() / 2) + 12.5f);
> 
>      pres.save("DrawingGuides_out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Visszatér:**
[IDrawingGuidesCollection](../../com.aspose.slides/idrawingguidescollection)