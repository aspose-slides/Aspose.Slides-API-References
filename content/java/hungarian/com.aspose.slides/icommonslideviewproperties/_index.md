---
title: ICommonSlideViewProperties
second_title: Aspose.Slides for Java API Reference
description: Közös dianézet tulajdonságokat képvisel.
type: docs
url: /hu/com.aspose.slides/icommonslideviewproperties/
---```
public interface ICommonSlideViewProperties
```

Közös dianézet tulajdonságokat képvisel.
## Módszerek

| Módszer | Leírás |
| --- | --- |
| [getScale()](#getScale--) | A nézet nagyítási arányát százalékban adja meg. |
| [setScale(int value)](#setScale-int-) | A nézet nagyítási arányát százalékban adja meg. |
| [getVariableScale()](#getVariableScale--) | Azt határozza meg, hogy a nézet tartalma automatikusan skálázódjon a jelenlegi ablakmérethez legjobban illeszkedve. |
| [setVariableScale(boolean value)](#setVariableScale-boolean-) | Azt határozza meg, hogy a nézet tartalma automatikusan skálázódjon a jelenlegi ablakmérethez legjobban illeszkedve. |
| [getDrawingGuides()](#getDrawingGuides--) | Visszaadja a rajzolósegédek gyűjteményét. |
### getScale() {#getScale--}
```
public abstract int getScale()
```

A nézet nagyítási arányát százalékban adja meg. Olvasás/írás int.

**Visszatér:**
int
### setScale(int value) {#setScale-int-}
```
public abstract void setScale(int value)
```

A nézet nagyítási arányát százalékban adja meg. Olvasás/írás int.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | int |  |
### getVariableScale() {#getVariableScale--}
```
public abstract boolean getVariableScale()
```

Azt határozza meg, hogy a nézet tartalma automatikusan skálázódjon a jelenlegi ablakmérethez legjobban illeszkedve. Olvasás/írás boolean.

**Visszatér:**
boolean
### setVariableScale(boolean value) {#setVariableScale-boolean-}
```
public abstract void setVariableScale(boolean value)
```

Azt határozza meg, hogy a nézet tartalma automatikusan skálázódjon a jelenlegi ablakmérethez legjobban illeszkedve. Olvasás/írás boolean.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | boolean |  |
### getDrawingGuides() {#getDrawingGuides--}
```
public abstract IDrawingGuidesCollection getDrawingGuides()
```

Visszaadja a rajzolósegédek gyűjteményét. Csak olvasható [IDrawingGuidesCollection](../../com.aspose.slides/idrawingguidescollection)

--------------------

> ```
> The following sample code shows how to add the new drawing guides in a PowerPoint presentation.
>  
>  Presentation pres = new Presentation();
>  try {
>      Dimension2D slideSize = pres.getSlideSize().getSize();
> 
>      IDrawingGuidesCollection guides = pres.getViewProperties().getSlideViewProperties().getDrawingGuides();
>      // Az új függőleges rajzolósegéd hozzáadása a dia középpontjának jobb oldalához
>      // Az új vízszintes rajzolósegéd hozzáadása a dia középpontja alá
> 
>      pres.save("DrawingGuides_out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Visszatér:**
[IDrawingGuidesCollection](../../com.aspose.slides/idrawingguidescollection)