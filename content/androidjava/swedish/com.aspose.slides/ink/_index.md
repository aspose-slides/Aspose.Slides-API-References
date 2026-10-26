---
title: Ink
second_title: Aspose.Slides för Android via Java API-referens
description: Representerar ett bläckobjekt på en bild.
type: docs
url: /sv/com.aspose.slides/ink/
---
**Arv:**
java.lang.Object, [com.aspose.slides.Shape](../../com.aspose.slides/shape), [com.aspose.slides.GraphicalObject](../../com.aspose.slides/graphicalobject)

**Alla implementerade gränssnitt:**
[com.aspose.slides.IInk](../../com.aspose.slides/iink)
```
public class Ink extends GraphicalObject implements IInk
```

Representerar ett bläckobjekt på en bild.
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getTraces()](#getTraces--) | Hämtar alla spår som finns i IInk-elementet [IInkTrace](../../com.aspose.slides/iinktrace). |
| [getInkEffectImages()](#getInkEffectImages--) | Hämtar samlingen av anpassade bilder som används för att simulera visuella effekter för bläckpenslar. |

### getTraces() {#getTraces--}
```
public final IInkTrace[] getTraces()
```

Hämtar alla spår som finns i IInk-elementet [IInkTrace](../../com.aspose.slides/iinktrace). Skrivskyddad.

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

**Returnerar:**
com.aspose.slides.IInkTrace[]

### getInkEffectImages() {#getInkEffectImages--}
```
public static System.Collections.Generic.Dictionary<Integer,IImage> getInkEffectImages()
```

Hämtar samlingen av anpassade bilder som används för att simulera visuella effekter för bläckpenslar. Dessa bilder används när bläck renderas med specifika [InkEffectType](../../com.aspose.slides/inkeffecttype)-värden, såsom Galaxy, Rainbow osv. Genom att tillhandahålla egna bilder kan du styra hur varje bläckeffekt visas.

--------------------

> ```
> IImage image = Images.fromFile("image.png");
>  ink.getInkEffectImages().addItem(InkEffectType.Galaxy, image);
> ```

--------------------

Den här egenskapen tillåter att ersätta standard-bläck-effekt-texturer med användardefinierade, vilket är särskilt användbart när standardresurser är begränsade av licens eller inte tillgängliga vid körning. Varje post i ordboken måste associera ett [InkEffectType](../../com.aspose.slides/inkeffecttype)-värde med ett motsvarande [IImage](../../com.aspose.slides/iimage)-objekt (t.ex. Bitmap eller ett Aspose-bildgränssnitt).

**Returnerar:**
com.aspose.ms.System.Collections.Generic.Dictionary<java.lang.Integer,com.aspose.slides.IImage>