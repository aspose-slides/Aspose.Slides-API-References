---
title: Ink
second_title: Aspose.Slides para Android vía referencia de API Java
description: Representa un objeto de tinta en una diapositiva.
type: docs
url: /es/com.aspose.slides/ink/
---
**Herencia:**
java.lang.Object, [com.aspose.slides.Shape](../../com.aspose.slides/shape), [com.aspose.slides.GraphicalObject](../../com.aspose.slides/graphicalobject)

**Todas las interfaces implementadas:**
[com.aspose.slides.IInk](../../com.aspose.slides/iink)
```
public class Ink extends GraphicalObject implements IInk
```

Representa un objeto de tinta en una diapositiva.
## Métodos

| Método | Descripción |
| --- | --- |
| [getTraces()](#getTraces--) | Obtiene todas las trazas contenidas en el elemento IInk [IInkTrace](../../com.aspose.slides/iinktrace). |
| [getInkEffectImages()](#getInkEffectImages--) | Obtiene la colección de imágenes personalizadas usadas para simular efectos visuales para pinceles de tinta. |
### getTraces() {#getTraces--}
```
public final IInkTrace[] getTraces()
```

Obtiene todas las trazas contenidas en el elemento IInk [IInkTrace](../../com.aspose.slides/iinktrace). Solo lectura.

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

**Devuelve:**
com.aspose.slides.IInkTrace[]
### getInkEffectImages() {#getInkEffectImages--}
```
public static System.Collections.Generic.Dictionary<Integer,IImage> getInkEffectImages()
```

Obtiene la colección de imágenes personalizadas usadas para simular efectos visuales para pinceles de tinta. Estas imágenes se utilizan al renderizar tinta con valores específicos de [InkEffectType](../../com.aspose.slides/inkeffecttype), como Galaxy, Rainbow, etc. Al proporcionar sus propias imágenes, puede controlar cómo aparece cada efecto de tinta.

--------------------

> ```
> IImage image = Images.fromFile("image.png");
>  ink.getInkEffectImages().addItem(InkEffectType.Galaxy, image);
> ```


--------------------

Esta propiedad permite reemplazar las texturas de efecto de tinta predeterminadas por otras definidas por el usuario, lo que es particularmente útil cuando los recursos predeterminados están restringidos por licencias o no están disponibles en tiempo de ejecución. Cada entrada en el diccionario debe asociar un valor [InkEffectType](../../com.aspose.slides/inkeffecttype) con un objeto [IImage](../../com.aspose.slides/iimage) correspondiente (p. ej., Bitmap, o una interfaz de imagen de Aspose).

**Devuelve:**
com.aspose.ms.System.Collections.Generic.Dictionary<java.lang.Integer,com.aspose.slides.IImage>