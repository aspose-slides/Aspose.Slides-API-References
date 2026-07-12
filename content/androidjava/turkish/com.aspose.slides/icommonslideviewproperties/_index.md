---
title: ICommonSlideViewProperties
second_title: Aspose.Slides for Android via Java API Reference
description: Genel slayt görünüm özelliklerini temsil eder.
type: docs
url: /tr/com.aspose.slides/icommonslideviewproperties/
---```
public interface ICommonSlideViewProperties
```

Genel slayt görünüm özelliklerini temsil eder.
## Metodlar

| Method | Description |
| --- | --- |
| [getScale()](#getScale--) | Görünüm ölçekleme oranını yüzde olarak belirtir. |
| [setScale(int value)](#setScale-int-) | Görünüm ölçekleme oranını yüzde olarak belirtir. |
| [getVariableScale()](#getVariableScale--) | Görünüm içeriğinin mevcut pencere boyutuna en iyi şekilde sığacak şekilde otomatik olarak ölçeklenmesi gerektiğini belirtir. |
| [setVariableScale(boolean value)](#setVariableScale-boolean-) | Görünüm içeriğinin mevcut pencere boyutuna en iyi şekilde sığacak şekilde otomatik olarak ölçeklenmesi gerektiğini belirtir. |
| [getDrawingGuides()](#getDrawingGuides--) | Çizim kılavuzlarının koleksiyonunu döndürür. |
### getScale() {#getScale--}
```
public abstract int getScale()
```

Görünüm ölçekleme oranını yüzde olarak belirtir. Okunur/yazılır int.

**Döndürür:**
int
### setScale(int value) {#setScale-int-}
```
public abstract void setScale(int value)
```

Görünüm ölçekleme oranını yüzde olarak belirtir. Okunur/yazılır int.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | int |  |

### getVariableScale() {#getVariableScale--}
```
public abstract boolean getVariableScale()
```

Görünüm içeriğinin mevcut pencere boyutuna en iyi şekilde sığacak şekilde otomatik olarak ölçeklenmesi gerektiğini belirtir. Okunur/yazılır boolean.

**Döndürür:**
boolean
### setVariableScale(boolean value) {#setVariableScale-boolean-}
```
public abstract void setVariableScale(boolean value)
```

Görünüm içeriğinin mevcut pencere boyutuna en iyi şekilde sığacak şekilde otomatik olarak ölçeklenmesi gerektiğini belirtir. Okunur/yazılır boolean.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | boolean |  |

### getDrawingGuides() {#getDrawingGuides--}
```
public abstract IDrawingGuidesCollection getDrawingGuides()
```

Çizim kılavuzlarının koleksiyonunu döndürür. Salt-okunur [IDrawingGuidesCollection](../../com.aspose.slides/idrawingguidescollection)

--------------------

> ```
> The following sample code shows how to add the new drawing guides in a PowerPoint presentation.
>  
>  Presentation pres = new Presentation();
>  try {
>      SizeF slideSize = pres.getSlideSize().getSize();
> 
>      IDrawingGuidesCollection guides = pres.getViewProperties().getSlideViewProperties().getDrawingGuides();
>      // Adding the new vertical drawing guide to the right of the slide center
>      guides.add(Orientation.Vertical, (float)(slideSize.getWidth() / 2) + 12.5f);
>      // Adding the new horizontal drawing guide below the slide center
>      guides.add(Orientation.Horizontal, (float)(slideSize.getHeight() / 2) + 12.5f);
> 
>      pres.save("DrawingGuides_out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Döndürür:**
[IDrawingGuidesCollection](../../com.aspose.slides/idrawingguidescollection)