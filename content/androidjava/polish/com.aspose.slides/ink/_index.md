---
title: Ink
second_title: Aspose.Slides dla Androida za pośrednictwem referencji API Java
description: Reprezentuje obiekt atramentu na slajdzie.
type: docs
url: /pl/com.aspose.slides/ink/
---
**Dziedziczenie:**
java.lang.Object, [com.aspose.slides.Shape](../../com.aspose.slides/shape), [com.aspose.slides.GraphicalObject](../../com.aspose.slides/graphicalobject)

**Wszystkie zaimplementowane interfejsy:**
[com.aspose.slides.IInk](../../com.aspose.slides/iink)
```
public class Ink extends GraphicalObject implements IInk
```

Reprezentuje obiekt atramentu na slajdzie.
## Metody

| Metoda | Opis |
| --- | --- |
| [getTraces()](#getTraces--) | Pobiera wszystkie ślady zawarte w elemencie IInk [IInkTrace](../../com.aspose.slides/iinktrace). |
| [getInkEffectImages()](#getInkEffectImages--) | Pobiera kolekcję niestandardowych obrazów używanych do symulacji efektów wizualnych pędzli atramentu. |
### getTraces() {#getTraces--}
```
public final IInkTrace[] getTraces()
```


Pobiera wszystkie ślady zawarte w elemencie IInk [IInkTrace](../../com.aspose.slides/iinktrace). Tylko do odczytu.

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


**Zwraca:**
com.aspose.slides.IInkTrace[]
### getInkEffectImages() {#getInkEffectImages--}
```
public static System.Collections.Generic.Dictionary<Integer,IImage> getInkEffectImages()
```


Pobiera kolekcję niestandardowych obrazów używanych do symulacji efektów wizualnych pędzli atramentu. Obrazy te są używane podczas renderowania atramentu z określonymi wartościami [InkEffectType](../../com.aspose.slides/inkeffecttype), takimi jak Galaxy, Rainbow itp. Dostarczając własne obrazy, możesz kontrolować, jak każdy efekt atramentu się wyświetla.

--------------------

> ```
> IImage image = Images.fromFile("image.png");
>  ink.getInkEffectImages().addItem(InkEffectType.Galaxy, image);
> ```


--------------------

Ta właściwość umożliwia zastąpienie domyślnych tekstur efektów atramentu własnymi, co jest szczególnie przydatne, gdy domyślne zasoby są ograniczone licencją lub niedostępne w czasie wykonywania. Każdy wpis w słowniku musi powiązać wartość [InkEffectType](../../com.aspose.slides/inkeffecttype) z odpowiadającym obiektem [IImage](../../com.aspose.slides/iimage) (np. Bitmap, lub interfejs obrazu Aspose).

**Zwraca:**
com.aspose.ms.System.Collections.Generic.Dictionary<java.lang.Integer,com.aspose.slides.IImage>