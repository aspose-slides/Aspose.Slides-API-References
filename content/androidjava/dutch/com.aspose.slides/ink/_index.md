---
title: Ink
second_title: Aspose.Slides voor Android via Java API-referentie
description: Vertegenwoordigt een inktobject op een dia.
type: docs
url: /nl/com.aspose.slides/ink/
---
**Erfenis:**
java.lang.Object, [com.aspose.slides.Shape](../../com.aspose.slides/shape), [com.aspose.slides.GraphicalObject](../../com.aspose.slides/graphicalobject)

**Alle geïmplementeerde interfaces:**
[com.aspose.slides.IInk](../../com.aspose.slides/iink)
```
public class Ink extends GraphicalObject implements IInk
```

Vertegenwoordigt een inktobject op een dia.
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [getTraces()](#getTraces--) | Haalt alle sporen op die zich bevinden in het IInk-element [IInkTrace](../../com.aspose.slides/iinktrace). |
| [getInkEffectImages()](#getInkEffectImages--) | Haalt de verzameling aangepaste afbeeldingen op die worden gebruikt om visuele effecten voor inktkwasten te simuleren. |
### getTraces() {#getTraces--}
```
public final IInkTrace[] getTraces()
```


Haalt alle sporen op die zich bevinden in het IInk-element [IInkTrace](../../com.aspose.slides/iinktrace). Alleen-lezen.

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


**Retourneert:**
com.aspose.slides.IInkTrace[]
### getInkEffectImages() {#getInkEffectImages--}
```
public static System.Collections.Generic.Dictionary<Integer,IImage> getInkEffectImages()
```


Haalt de verzameling aangepaste afbeeldingen op die worden gebruikt om visuele effecten voor inktkwasten te simuleren. Deze afbeeldingen worden gebruikt bij het renderen van inkt met specifieke [InkEffectType](../../com.aspose.slides/inkeffecttype)-waarden, zoals Galaxy, Rainbow, enz. Door uw eigen afbeeldingen te leveren, kunt u bepalen hoe elk inkt-effect verschijnt.

--------------------

> ```
> IImage image = Images.fromFile("image.png");
>  ink.getInkEffectImages().addItem(InkEffectType.Galaxy, image);
> ```


--------------------

Deze eigenschap maakt het mogelijk de standaard inkt-effecttexturen te vervangen door door de gebruiker gedefinieerde, wat bijzonder handig is wanneer standaard assets door licenties worden beperkt of niet beschikbaar zijn tijdens runtime. Elk item in het woordenboek moet een [InkEffectType](../../com.aspose.slides/inkeffecttype)-waarde koppelen aan een overeenkomstig [IImage](../../com.aspose.slides/iimage)-object (bijv. Bitmap, of een Aspose-afbeeldingsinterface).

**Retourneert:**
com.aspose.ms.System.Collections.Generic.Dictionary<java.lang.Integer,com.aspose.slides.IImage>