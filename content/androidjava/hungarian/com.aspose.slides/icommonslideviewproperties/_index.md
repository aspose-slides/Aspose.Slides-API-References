---
title: ICommonSlideViewProperties
second_title: Aspose.Slides for Android via Java API Reference
description: Közös dia nézet tulajdonságait reprezentálja.
type: docs
url: /hu/com.aspose.slides/icommonslideviewproperties/
---```
public interface ICommonSlideViewProperties
```

Közös dia nézet tulajdonságait reprezentálja.
## Metódusok

| Method | Description |
| --- | --- |
| [getScale()](#getScale--) | Meghatározza a nézet méretezési arányát százalékban. |
| [setScale(int value)](#setScale-int-) | Meghatározza a nézet méretezési arányát százalékban. |
| [getVariableScale()](#getVariableScale--) | Meghatározza, hogy a nézet tartalma automatikusan méreteződjön, hogy a legjobban illeszkedjen az aktuális ablakmérethez. |
| [setVariableScale(boolean value)](#setVariableScale-boolean-) | Meghatározza, hogy a nézet tartalma automatikusan méreteződjön, hogy a legjobban illeszkedjen az aktuális ablakmérethez. |
| [getDrawingGuides()](#getDrawingGuides--) | Visszaadja a rajzolási segédvonalak gyűjteményét. |

### getScale() {#getScale--}
```
public abstract int getScale()
```

Meghatározza a nézet méretezési arányát százalékban. Olvasás/írás int.

**Visszatér:**
int

### setScale(int value) {#setScale-int-}
```
public abstract void setScale(int value)
```

Meghatározza a nézet méretezési arányát százalékban. Olvasás/írás int.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | int |  |

### getVariableScale() {#getVariableScale--}
```
public abstract boolean getVariableScale()
```

Meghatározza, hogy a nézet tartalma automatikusan méreteződjön, hogy a legjobban illeszkedjen az aktuális ablakmérethez. Olvasás/írás boolean.

**Visszatér:**
boolean

### setVariableScale(boolean value) {#setVariableScale-boolean-}
```
public abstract void setVariableScale(boolean value)
```

Meghatározza, hogy a nézet tartalma automatikusan méreteződjön, hogy a legjobban illeszkedjen az aktuális ablakmérethez. Olvasás/írás boolean.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | boolean |  |

### getDrawingGuides() {#getDrawingGuides--}
```
public abstract IDrawingGuidesCollection getDrawingGuides()
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
>      // Új függőleges rajzolási segédvonal hozzáadása a dia közepétől jobbra
>      guides.add(Orientation.Vertical, (float)(slideSize.getWidth() / 2) + 12.5f);
>      // Új vízszintes rajzolási segédvonal hozzáadása a dia közepét alá
>      guides.add(Orientation.Horizontal, (float)(slideSize.getHeight() / 2) + 12.5f);
> 
>      pres.save("DrawingGuides_out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Visszatér:**
[IDrawingGuidesCollection](../../com.aspose.slides/idrawingguidescollection)