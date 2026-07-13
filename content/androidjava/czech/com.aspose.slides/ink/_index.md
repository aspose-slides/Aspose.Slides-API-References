---
title: Ink
second_title: Aspose.Slides pro Android prostřednictvím reference Java API
description: Představuje objekt ink na snímku.
type: docs
url: /cs/com.aspose.slides/ink/
---
**Dědičnost:**
java.lang.Object, [com.aspose.slides.Shape](../../com.aspose.slides/shape), [com.aspose.slides.GraphicalObject](../../com.aspose.slides/graphicalobject)

**Všechny implementované rozhraní:**
[com.aspose.slides.IInk](../../com.aspose.slides/iink)
```
public class Ink extends GraphicalObject implements IInk
```

Představuje objekt ink na snímku.
## Metody

| Metoda | Popis |
| --- | --- |
| [getTraces()](#getTraces--) | Získá všechny stopy obsažené v prvku IInk [IInkTrace](../../com.aspose.slides/iinktrace). |
| [getInkEffectImages()](#getInkEffectImages--) | Získá kolekci vlastních obrázků použitých k simulaci vizuálních efektů pro ink štětce. |
### getTraces() {#getTraces--}
```
public final IInkTrace[] getTraces()
```


Získá všechny stopy obsažené v prvku IInk [IInkTrace](../../com.aspose.slides/iinktrace). Pouze ke čtení.

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

**Vrátí:**
com.aspose.slides.IInkTrace[]
### getInkEffectImages() {#getInkEffectImages--}
```
public static System.Collections.Generic.Dictionary<Integer,IImage> getInkEffectImages()
```


Získá kolekci vlastních obrázků použitých k simulaci vizuálních efektů pro ink štětce. Tyto obrázky jsou použity při vykreslování ink s konkrétními hodnotami [InkEffectType](../../com.aspose.slides/inkeffecttype), jako jsou Galaxy, Rainbow atd. Poskytnutím vlastních obrázků můžete ovládat, jak se každý ink efekt zobrazuje.

--------------------

> ```
> IImage image = Images.fromFile("image.png");
>  ink.getInkEffectImages().addItem(InkEffectType.Galaxy, image);
> ```


--------------------

Tato vlastnost umožňuje nahradit výchozí textury ink efektů uživatelem definovanými, což je obzvláště užitečné, když jsou výchozí zdroje omezeny licencí nebo nejsou v době běhu k dispozici. Každý záznam ve slovníku musí přiřadit hodnotu [InkEffectType](../../com.aspose.slides/inkeffecttype) k odpovídajícímu objektu [IImage](../../com.aspose.slides/iimage) (např. Bitmap nebo rozhraní Aspose obrázku).

**Vrátí:**
com.aspose.ms.System.Collections.Generic.Dictionary<java.lang.Integer,com.aspose.slides.IImage>