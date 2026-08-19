---
title: Ink
second_title: Aspose.Slides pro Java – referenční příručka API
description: Reprezentuje objekt ink na snímku.
type: docs
url: /cs/com.aspose.slides/ink/
---
**Dědičnost:**
java.lang.Object, [com.aspose.slides.Shape](../../com.aspose.slides/shape), [com.aspose.slides.GraphicalObject](../../com.aspose.slides/graphicalobject)

**Všechna implementovaná rozhraní:**
[com.aspose.slides.IInk](../../com.aspose.slides/iink)
```
public class Ink extends GraphicalObject implements IInk
```

Reprezentuje ink objekt na snímku.
## Metody

| Metoda | Popis |
| --- | --- |
| [getTraces()](#getTraces--) | Získá všechny stopy obsažené v elementu IInk [IInkTrace](../../com.aspose.slides/iinktrace). |
| [getInkEffectImages()](#getInkEffectImages--) | Získá kolekci vlastních obrázků používaných k simulaci vizuálních efektů pro inkové štětce. |
### getTraces() {#getTraces--}
```
public final IInkTrace[] getTraces()
```

Získá všechny stopy obsažené v elementu IInk [IInkTrace](../../com.aspose.slides/iinktrace). Pouze pro čtení.

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      IInk ink = (IInk)pres.getSlides().get_Item(0).getShapes().get_Item(0);
>      IInkTrace[] traces = ink.getTraces();
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Vrací:**
com.aspose.slides.IInkTrace[]
### getInkEffectImages() {#getInkEffectImages--}
```
public static System.Collections.Generic.Dictionary<Integer,IImage> getInkEffectImages()
```

Získá kolekci vlastních obrázků používaných k simulaci vizuálních efektů pro inkové štětce. Tyto obrázky jsou používány při vykreslování ink s konkrétními hodnotami [InkEffectType](../../com.aspose.slides/inkeffecttype), jako jsou Galaxy, Rainbow atd. Poskytnutím vlastních obrázků můžete ovládat, jak se každý ink efekt zobrazuje.

--------------------

> ```
> IImage image = Images.fromFile("image.png");
>  ink.getInkEffectImages().addItem(InkEffectType.Galaxy, image);
> ```


--------------------

Tato vlastnost umožňuje nahradit výchozí textury inkových efektů uživatelem definovanými, což je zvláště užitečné, když jsou výchozí prostředky omezeny licencí nebo nejsou v době běhu dostupné. Každý záznam ve slovníku musí přiřadit hodnotu [InkEffectType](../../com.aspose.slides/inkeffecttype) k odpovídajícímu objektu [IImage](../../com.aspose.slides/iimage) (např. Bitmap nebo rozhraní Aspose image).

**Vrací:**
com.aspose.ms.System.Collections.Generic.Dictionary<java.lang.Integer,com.aspose.slides.IImage>