---
title: Ink
second_title: Aspose.Slides für Android über Java API-Referenz
description: Stellt ein Tintenobjekt auf einer Folie dar.
type: docs
url: /de/com.aspose.slides/ink/
---
**Vererbung:**
java.lang.Object, [com.aspose.slides.Shape](../../com.aspose.slides/shape), [com.aspose.slides.GraphicalObject](../../com.aspose.slides/graphicalobject)

**Alle implementierten Schnittstellen:**
[com.aspose.slides.IInk](../../com.aspose.slides/iink)
```
public class Ink extends GraphicalObject implements IInk
```

Stellt ein Tintenobjekt auf einer Folie dar.
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getTraces()](#getTraces--) | Ruft alle Spuren ab, die im IInk-Element [IInkTrace](../../com.aspose.slides/iinktrace) enthalten sind. |
| [getInkEffectImages()](#getInkEffectImages--) | Ruft die Sammlung benutzerdefinierter Bilder ab, die verwendet werden, um visuelle Effekte für Tintenpinsel zu simulieren. |
### getTraces() {#getTraces--}
```
public final IInkTrace[] getTraces()
```

Ruft alle Spuren ab, die im IInk-Element [IInkTrace](../../com.aspose.slides/iinktrace) enthalten sind. Nur Lesen.

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

**Rückgabe:**
com.aspose.slides.IInkTrace[]
### getInkEffectImages() {#getInkEffectImages--}
```
public static System.Collections.Generic.Dictionary<Integer,IImage> getInkEffectImages()
```

Ruft die Sammlung benutzerdefinierter Bilder ab, die verwendet werden, um visuelle Effekte für Tintenpinsel zu simulieren. Diese Bilder werden verwendet, wenn Tinte mit spezifischen [InkEffectType](../../com.aspose.slides/inkeffecttype)-Werten gerendert wird, wie z. B. Galaxy, Rainbow usw. Durch das Bereitstellen eigener Bilder können Sie steuern, wie jeder Tinteneffekt erscheint.

--------------------

> ```
> IImage image = Images.fromFile("image.png");
>  ink.getInkEffectImages().addItem(InkEffectType.Galaxy, image);
> ```

--------------------

Diese Eigenschaft ermöglicht das Ersetzen der standardmäßigen Tinteneffekt-Texturen durch benutzerdefinierte, was besonders nützlich ist, wenn Standardressourcen durch Lizenzbeschränkungen eingeschränkt oder zur Laufzeit nicht verfügbar sind. Jeder Eintrag im Wörterbuch muss einen [InkEffectType](../../com.aspose.slides/inkeffecttype)-Wert mit einem entsprechenden [IImage](../../com.aspose.slides/iimage)-Objekt (z. B. Bitmap oder einer Aspose-Bildschnittstelle) verknüpfen.

**Rückgabe:**
com.aspose.ms.System.Collections.Generic.Dictionary<java.lang.Integer,com.aspose.slides.IImage>