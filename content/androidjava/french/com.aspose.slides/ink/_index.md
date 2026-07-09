---
title: Ink
second_title: Aspose.Slides pour Android via la référence de l'API Java
description: Représente un objet encre sur une diapositive.
type: docs
url: /fr/com.aspose.slides/ink/
---
**Héritage:**
java.lang.Object, [com.aspose.slides.Shape](../../com.aspose.slides/shape), [com.aspose.slides.GraphicalObject](../../com.aspose.slides/graphicalobject)

**Toutes les interfaces implémentées:**
[com.aspose.slides.IInk](../../com.aspose.slides/iink)
```
public class Ink extends GraphicalObject implements IInk
```

Représente un objet encre sur une diapositive.
## Méthodes

| Méthode | Description |
| --- | --- |
| [getTraces()](#getTraces--) | Obtient toutes les traces contenues dans l'élément IInk [IInkTrace](../../com.aspose.slides/iinktrace). |
| [getInkEffectImages()](#getInkEffectImages--) | Obtient la collection d'images personnalisées utilisées pour simuler les effets visuels des pinceaux d'encre. |
### getTraces() {#getTraces--}
```
public final IInkTrace[] getTraces()
```

Obtient toutes les traces contenues dans l'élément IInk [IInkTrace](../../com.aspose.slides/iinktrace). Lecture seule.

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

**Returns:**
com.aspose.slides.IInkTrace[]
### getInkEffectImages() {#getInkEffectImages--}
```
public static System.Collections.Generic.Dictionary<Integer,IImage> getInkEffectImages()
Obtient la collection d'images personnalisées utilisées pour simuler les effets visuels des pinceaux d'encre. Ces images sont utilisées lors du rendu de l'encre avec des valeurs spécifiques [InkEffectType](../../com.aspose.slides/inkeffecttype), telles que Galaxy, Rainbow, etc. En fournissant vos propres images, vous pouvez contrôler l'apparence de chaque effet d'encre.

--------------------

> ```
> IImage image = Images.fromFile("image.png");
>  ink.getInkEffectImages().addItem(InkEffectType.Galaxy, image);
> ```

--------------------

Cette propriété permet de remplacer les textures d'effet d'encre par défaut par des textures définies par l'utilisateur, ce qui est particulièrement utile lorsque les ressources par défaut sont restreintes par des licences ou indisponibles à l'exécution. Chaque entrée du dictionnaire doit associer une valeur [InkEffectType](../../com.aspose.slides/inkeffecttype) à un objet [IImage](../../com.aspose.slides/iimage) correspondant (par exemple, Bitmap, ou une interface d'image Aspose).

**Renvoie:**
com.aspose.ms.System.Collections.Generic.Dictionary<java.lang.Integer,com.aspose.slides.IImage>