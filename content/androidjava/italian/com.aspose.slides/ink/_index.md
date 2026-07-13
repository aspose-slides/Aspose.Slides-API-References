---
title: Ink
second_title: Aspose.Slides per Android tramite Riferimento API Java
description: Rappresenta un oggetto di inchiostro su una diapositiva.
type: docs
url: /it/com.aspose.slides/ink/
---
**Eredità:**
java.lang.Object, [com.aspose.slides.Shape](../../com.aspose.slides/shape), [com.aspose.slides.GraphicalObject](../../com.aspose.slides/graphicalobject)

**Tutte le interfacce implementate:**
[com.aspose.slides.IInk](../../com.aspose.slides/iink)
```
public class Ink extends GraphicalObject implements IInk
```

Rappresenta un oggetto di inchiostro su una diapositiva.
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getTraces()](#getTraces--) | Recupera tutte le tracce contenute nell'elemento IInk [IInkTrace](../../com.aspose.slides/iinktrace). |
| [getInkEffectImages()](#getInkEffectImages--) | Recupera la raccolta di immagini personalizzate utilizzate per simulare gli effetti visivi dei pennelli d'inchiostro. |
### getTraces() {#getTraces--}
```
public final IInkTrace[] getTraces()
```


Recupera tutte le tracce contenute nell'elemento IInk [IInkTrace](../../com.aspose.slides/iinktrace). Solo lettura.

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

**Restituisce:**
com.aspose.slides.IInkTrace[]
### getInkEffectImages() {#getInkEffectImages--}
```
public static System.Collections.Generic.Dictionary<Integer,IImage> getInkEffectImages()
```


Recupera la raccolta di immagini personalizzate utilizzate per simulare gli effetti visivi dei pennelli d'inchiostro. Queste immagini vengono utilizzate durante il rendering dell'inchiostro con valori [InkEffectType](../../com.aspose.slides/inkeffecttype) specifici, come Galaxy, Rainbow, ecc. Fornendo le proprie immagini, è possibile controllare l'aspetto di ciascun effetto di inchiostro.

--------------------

> ```
> IImage image = Images.fromFile("image.png");
>  ink.getInkEffectImages().addItem(InkEffectType.Galaxy, image);
> ```

--------------------

Questa proprietà consente di sostituire le texture predefinite degli effetti di inchiostro con quelle definite dall'utente, risultando particolarmente utile quando le risorse predefinite sono limitate da licenze o non disponibili a runtime. Ogni voce nel dizionario deve associare un valore [InkEffectType](../../com.aspose.slides/inkeffecttype) a un oggetto [IImage](../../com.aspose.slides/iimage) corrispondente (ad es., Bitmap o un'interfaccia immagine Aspose).

**Restituisce:**
com.aspose.ms.System.Collections.Generic.Dictionary<java.lang.Integer,com.aspose.slides.IImage>