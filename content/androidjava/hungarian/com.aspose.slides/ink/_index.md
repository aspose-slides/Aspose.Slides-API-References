---
title: Ink
second_title: Aspose.Slides Androidhoz Java API referencia
description: Egy tintát ábrázoló objektumot jelöl a dián.
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

Egy tintát ábrázoló objektumot jelöl a dián.
## Módszerek

| Módszer | Leírás |
| --- | --- |
| [getTraces()](#getTraces--) | Lekéri az összes nyomot, amely a [IInkTrace](../../com.aspose.slides/iinktrace) IInk elemben található. |
| [getInkEffectImages()](#getInkEffectImages--) | Lekéri az egyedi képek gyűjteményét, amelyet a tintakezelő ecsetek vizuális hatásainak szimulálásához használnak. |
### getTraces() {#getTraces--}
```
public final IInkTrace[] getTraces()
```


Lekéri az összes nyomot, amely a [IInkTrace](../../com.aspose.slides/iinktrace) IInk elemben található. Csak olvasható.

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


Lekéri az egyedi képek gyűjteményét, amelyet a tintakezelő ecsetek vizuális hatásainak szimulálásához használnak. Ezek a képek a tinták renderelésekor használatosak specifikus [InkEffectType](../../com.aspose.slides/inkeffecttype) értékekkel, például Galaxy, Rainbow stb. Saját képek megadásával szabályozhatja, hogyan jelenik meg minden egyes tintahatás.

--------------------

> ```
> IImage image = Images.fromFile("image.png");
>  ink.getInkEffectImages().addItem(InkEffectType.Galaxy, image);
> ```


--------------------

Ezzel a tulajdonsággal helyettesítheti az alapértelmezett tintahatás textúrákat felhasználó által definiáltakkal, ami különösen hasznos, ha az alapértelmezett eszközök licenckorlátozások miatt nem elérhetők vagy futásidőben nem állnak rendelkezésre. A szótár minden bejegyzésének egy [InkEffectType](../../com.aspose.slides/inkeffecttype) értéket kell társítania a megfelelő [IImage](../../com.aspose.slides/iimage) objektummal (például Bitmap, vagy egy Aspose kép interfész).

**Visszatér:**
com.aspose.ms.System.Collections.Generic.Dictionary<java.lang.Integer,com.aspose.slides.IImage>