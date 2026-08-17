---
title: Ink
second_title: Aspose.Slides für Java API Referenz
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
| [getTraces()](#getTraces--) | Liefert alle Spuren, die im IInk-Element [IInkTrace](../../com.aspose.slides/iinktrace) enthalten sind. |
| [getInkEffectImages()](#getInkEffectImages--) | Liefert die Sammlung benutzerdefinierter Bilder, die zur Simulation von visuellen Effekten für Ink-Pinsel verwendet werden. |
### getTraces() {#getTraces--}
```
public final IInkTrace[] getTraces()
```

Liefert alle Spuren, die im IInk-Element [IInkTrace](../../com.aspose.slides/iinktrace) enthalten sind. Nur lesend.

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

Liefert die Sammlung benutzerdefinierter Bilder, die zur Simulation von visuellen Effekten für Ink-Pinsel verwendet werden. Diese Bilder werden beim Rendern von Ink mit bestimmten [InkEffectType](../../com.aspose.slides/inkeffecttype)-Werten verwendet, z. B. Galaxy, Rainbow usw. Durch die Bereitstellung eigener Bilder können Sie steuern, wie jeder Ink-Effekt angezeigt wird.

--------------------

> ```
> IImage image = Images.fromFile("image.png");
>  ink.getInkEffectImages().addItem(InkEffectType.Galaxy, image);
> ```

Diese Eigenschaft ermöglicht das Ersetzen der standardmäßigen Ink-Effekt-Texturen durch benutzerdefinierte, was besonders nützlich ist, wenn standardmäßige Assets durch Lizenzierung eingeschränkt oder zur Laufzeit nicht verfügbar sind. Jeder Eintrag im Wörterbuch muss einen [InkEffectType](../../com.aspose.slides/inkeffecttype)-Wert mit einem entsprechenden [IImage](../../com.aspose.slides/iimage)-Objekt verknüpfen (z. B. Bitmap oder eine Aspose-Image-Schnittstelle).

**Rückgabe:**
com.aspose.ms.System.Collections.Generic.Dictionary<java.lang.Integer,com.aspose.slides.IImage>