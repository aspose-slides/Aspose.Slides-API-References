---
title: ICommonSlideViewProperties
second_title: Aspose.Slides for Android via Java API Reference
description: Reprezentuje běžné vlastnosti zobrazení snímku.
type: docs
url: /cs/com.aspose.slides/icommonslideviewproperties/
---```
public interface ICommonSlideViewProperties
```

Reprezentuje běžné vlastnosti zobrazení snímku.
## Metody

| Metoda | Popis |
| --- | --- |
| [getScale()](#getScale--) | Určuje poměr měřítka zobrazení v procentech. |
| [setScale(int value)](#setScale-int-) | Určuje poměr měřítka zobrazení v procentech. |
| [getVariableScale()](#getVariableScale--) | Určuje, že obsah zobrazení by se měl automaticky přizpůsobit tak, aby co nejlépe vyplnil aktuální velikost okna. |
| [setVariableScale(boolean value)](#setVariableScale-boolean-) | Určuje, že obsah zobrazení by se měl automaticky přizpůsobit tak, aby co nejlépe vyplnil aktuální velikost okna. |
| [getDrawingGuides()](#getDrawingGuides--) | Vrací kolekci kreslicích vodítek. |
### getScale() {#getScale--}
```
public abstract int getScale()
```


Určuje poměr měřítka zobrazení v procentech. Čtení/zápis int.

**Vrací:**
int
### setScale(int value) {#setScale-int-}
```
public abstract void setScale(int value)
```


Určuje poměr měřítka zobrazení v procentech. Čtení/zápis int.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | int |  |

### getVariableScale() {#getVariableScale--}
```
public abstract boolean getVariableScale()
```


Určuje, že obsah zobrazení by se měl automaticky přizpůsobit tak, aby co nejlépe vyplnil aktuální velikost okna. Čtení/zápis boolean.

**Vrací:**
boolean
### setVariableScale(boolean value) {#setVariableScale-boolean-}
```
public abstract void setVariableScale(boolean value)
```


Určuje, že obsah zobrazení by se měl automaticky přizpůsobit tak, aby co nejlépe vyplnil aktuální velikost okna. Čtení/zápis boolean.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | boolean |  |

### getDrawingGuides() {#getDrawingGuides--}
```
public abstract IDrawingGuidesCollection getDrawingGuides()
```


Vrací kolekci kreslicích vodítek. Pouze pro čtení [IDrawingGuidesCollection](../../com.aspose.slides/idrawingguidescollection)

--------------------

> ```
> The following sample code shows how to add the new drawing guides in a PowerPoint presentation.
>  
>  Presentation pres = new Presentation();
>  try {
>      SizeF slideSize = pres.getSlideSize().getSize();
> 
>      IDrawingGuidesCollection guides = pres.getViewProperties().getSlideViewProperties().getDrawingGuides();
>      // Přidání nového svislého kreslicího vodítka napravo od středu snímku
>      guides.add(Orientation.Vertical, (float)(slideSize.getWidth() / 2) + 12.5f);
>      // Přidání nového vodorovného kreslicího vodítka pod střed snímku
>      guides.add(Orientation.Horizontal, (float)(slideSize.getHeight() / 2) + 12.5f);
> 
>      pres.save("DrawingGuides_out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Vrací:**
[IDrawingGuidesCollection](../../com.aspose.slides/idrawingguidescollection)