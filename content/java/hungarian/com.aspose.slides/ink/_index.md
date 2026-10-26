---
title: Ink
second_title: Aspose.Slides for Java API hivatkozás
description: Egy tintát ábrázoló objektumot képvisel a dián.
type: docs
url: /hu/com.aspose.slides/ink/
---
**Öröklés:**
java.lang.Object, [com.aspose.slides.Shape](../../com.aspose.slides/shape), [com.aspose.slides.GraphicalObject](../../com.aspose.slides/graphicalobject)

**Minden megvalósított interfész:**
[com.aspose.slides.IInk](../../com.aspose.slides/iink)
```
public class Ink extends GraphicalObject implements IInk
```

Egy tintát ábrázoló objektumot képvisel a dián.
## Metódusok

| Metódus | Leírás |
| --- | --- |
| [getTraces()](#getTraces--) | Az [IInkTrace](../../com.aspose.slides/iinktrace) IInk elemben lévő összes nyomvonalat lekéri. |
| [getInkEffectImages()](#getInkEffectImages--) | Lekéri az egyedi képek gyűjteményét, amelyet a tintakefék vizuális hatásainak szimulálására használnak. |
### getTraces() {#getTraces--}
```
public final IInkTrace[] getTraces()
```


Az [IInkTrace](../../com.aspose.slides/iinktrace) IInk elemben lévő összes nyomvonalat lekéri. Csak olvasható.

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


**Visszatér:**
com.aspose.slides.IInkTrace[]
### getInkEffectImages() {#getInkEffectImages--}
```
public static System.Collections.Generic.Dictionary<Integer,IImage> getInkEffectImages()
```


Lekéri az egyedi képek gyűjteményét, amelyet a tintakefék vizuális hatásainak szimulálására használnak. Ezeket a képeket akkor használják, amikor az adott [InkEffectType](../../com.aspose.slides/inkeffecttype) értékekkel, például Galaxy, Rainbow stb., tintát renderelnek. Saját képekkel meghatározhatja, hogy minden tintaeffektus hogyan jelenjen meg.

--------------------

> ```
> IImage image = Images.fromFile("image.png");
>  ink.getInkEffectImages().addItem(InkEffectType.Galaxy, image);
> ```


--------------------

Ez a tulajdonság lehetővé teszi az alapértelmezett tintahatás-textúrák felhasználó által definiáltakra történő cseréjét, ami különösen hasznos, ha az alapértelmezett erőforrások licencelés miatt korlátozottak vagy futásidőben nem érhetők el. A szótár minden bejegyzésének egy [InkEffectType](../../com.aspose.slides/inkeffecttype) értéket kell összekapcsolnia a megfelelő [IImage](../../com.aspose.slides/iimage) objektummal (például Bitmap, vagy egy Aspose képadattal).

**Visszatér:**
com.aspose.ms.System.Collections.Generic.Dictionary<java.lang.Integer,com.aspose.slides.IImage>