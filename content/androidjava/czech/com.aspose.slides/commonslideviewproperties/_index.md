---
title: CommonSlideViewProperties
second_title: Aspose.Slides pro Android prostřednictvím Java API Reference
description: Reprezentuje běžné vlastnosti zobrazení snímků.
type: docs
url: /cs/com.aspose.slides/commonslideviewproperties/
---
**Dědičnost:**
java.lang.Object

**Všechny implementované rozhraní:**
[com.aspose.slides.ICommonSlideViewProperties](../../com.aspose.slides/icommonslideviewproperties)
```
public class CommonSlideViewProperties implements ICommonSlideViewProperties
```

Reprezentuje obecné vlastnosti zobrazení snímků.

--------------------

> ```
> Následující příklad ukazuje, jak nastavit hodnotu zvětšení pro snímek v PowerPoint prezentaci.
>  
>  // Vytvořte objekt Presentation, který představuje soubor prezentace
>  Presentation pres = new Presentation("demo.pptx");
>  try {
>      // Nastavení vlastností zobrazení prezentace
>      pres.getViewProperties().getSlideViewProperties().setScale(100); // Hodnota zvětšení v procentech pro zobrazení snímku
>      pres.getViewProperties().getNotesViewProperties().setScale(100); // Hodnota zvětšení v procentech pro zobrazení poznámek
>      pres.save("Zoom_out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

## Metody

| Metoda | Popis |
| --- | --- |
| [getScale()](#getScale--) | Určuje měřítko zobrazení v procentech. |
| [setScale(int value)](#setScale-int-) | Určuje měřítko zobrazení v procentech. |
| [getVariableScale()](#getVariableScale--) | Určuje, že obsah zobrazení by měl být automaticky škálován tak, aby co nejlépe vyhovoval aktuální velikosti okna. |
| [setVariableScale(boolean value)](#setVariableScale-boolean-) | Určuje, že obsah zobrazení by měl být automaticky škálován tak, aby co nejlépe vyhovoval aktuální velikosti okna. |
| [getDrawingGuides()](#getDrawingGuides--) | Vrací kolekci vodítek kreslení. |
### getScale() {#getScale--}
```
public final int getScale()
```

Určuje měřítko zobrazení v procentech. Číst/Zapisovat int.

**Vrací:**
int
### setScale(int value) {#setScale-int-}
```
public final void setScale(int value)
```

Určuje měřítko zobrazení v procentech. Číst/Zapisovat int.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | int |  |
### getVariableScale() {#getVariableScale--}
```
public final boolean getVariableScale()
```

Určuje, že obsah zobrazení by měl být automaticky škálován tak, aby co nejlépe vyhovoval aktuální velikosti okna. Číst/Zapisovat boolean.

**Vrací:**
boolean
### setVariableScale(boolean value) {#setVariableScale-boolean-}
```
public final void setVariableScale(boolean value)
```

Určuje, že obsah zobrazení by měl být automaticky škálován tak, aby co nejlépe vyhovoval aktuální velikosti okna. Číst/Zapisovat boolean.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | boolean |  |
### getDrawingGuides() {#getDrawingGuides--}
```
public final IDrawingGuidesCollection getDrawingGuides()
```

Vrací kolekci vodítek kreslení. Pouze pro čtení [IDrawingGuidesCollection](../../com.aspose.slides/idrawingguidescollection)

--------------------

> ```
> The following sample code shows how to add the new drawing guides in a PowerPoint presentation.
>  
>  Presentation pres = new Presentation();
>  try {
>      SizeF slideSize = pres.getSlideSize().getSize();
> 
>      IDrawingGuidesCollection guides = pres.getViewProperties().getSlideViewProperties().getDrawingGuides();
>      // Přidání nového svislého kreslicího vodítka vpravo od středu snímku
>      guides.add(Orientation.Vertical, (float)(slideSize.getWidth()) / 2 + 12.5f);
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