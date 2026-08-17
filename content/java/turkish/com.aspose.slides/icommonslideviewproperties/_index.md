---
title: ICommonSlideViewProperties
second_title: Aspose.Slides for Java API Reference
description: Ortak slayt görünüm özelliklerini temsil eder.
type: docs
url: /tr/com.aspose.slides/icommonslideviewproperties/
---```
public interface ICommonSlideViewProperties
```

Ortak slayt görünüm özelliklerini temsil eder.
## Methods

| Yöntem | Açıklama |
| --- | --- |
| [getScale()](#getScale--) | Görünüm ölçek oranını yüzde olarak belirtir. |
| [setScale(int value)](#setScale-int-) | Görünüm ölçek oranını yüzde olarak belirtir. |
| [getVariableScale()](#getVariableScale--) | Görünüm içeriğinin mevcut pencere boyutuna en iyi şekilde sığacak şekilde otomatik olarak ölçeklenmesini belirtir. |
| [setVariableScale(boolean value)](#setVariableScale-boolean-) | Görünüm içeriğinin mevcut pencere boyutuna en iyi şekilde sığacak şekilde otomatik olarak ölçeklenmesini belirtir. |
| [getDrawingGuides()](#getDrawingGuides--) | Çizim kılavuzlarının koleksiyonunu döndürür. |
### getScale() {#getScale--}
```
public abstract int getScale()
```

Görünüm ölçek oranını yüzde olarak belirtir. Okunur/yazılır int.

**Döndürür:**
int
### setScale(int value) {#setScale-int-}
```
public abstract void setScale(int value)
```

Görünüm ölçek oranını yüzde olarak belirtir. Okunur/yazılır int.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | int |  |

### getVariableScale() {#getVariableScale--}
```
public abstract boolean getVariableScale()
```

Görünüm içeriğinin mevcut pencere boyutuna en iyi şekilde sığacak şekilde otomatik olarak ölçeklenmesini belirtir. Okunur/yazılır boolean.

**Döndürür:**
boolean
### setVariableScale(boolean value) {#setVariableScale-boolean-}
```
public abstract void setVariableScale(boolean value)
```

Görünüm içeriğinin mevcut pencere boyutuna en iyi şekilde sığacak şekilde otomatik olarak ölçeklenmesini belirtir. Okunur/yazılır boolean.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | boolean |  |

### getDrawingGuides() {#getDrawingGuides--}
```
public abstract IDrawingGuidesCollection getDrawingGuides()
```

Çizim kılavuzlarının koleksiyonunu döndürür. Yalnızca okunur [IDrawingGuidesCollection](../../com.aspose.slides/idrawingguidescollection)

--------------------

> ```
> The following sample code shows how to add the new drawing guides in a PowerPoint presentation.
>  
>  Presentation pres = new Presentation();
>  try {
>      Dimension2D slideSize = pres.getSlideSize().getSize();
> 
>      IDrawingGuidesCollection guides = pres.getViewProperties().getSlideViewProperties().getDrawingGuides();
>      // Adding the new vertical drawing guide to the right of the slide center
>      // Yeni dikey çizim kılavuzunu slayt merkezinin sağına ekleme
>      guides.add(Orientation.Vertical, (float)(slideSize.getWidth() / 2) + 12.5f);
>      // Adding the new horizontal drawing guide below the slide center
>      // Yeni yatay çizim kılavuzunu slayt merkezinin altına ekleme
>      guides.add(Orientation.Horizontal, (float)(slideSize.getHeight() / 2) + 12.5f);
> 
>      pres.save("DrawingGuides_out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Döndürür:**
[IDrawingGuidesCollection](../../com.aspose.slides/idrawingguidescollection)