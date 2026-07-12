---
title: CommonSlideViewProperties
second_title: Aspose.Slides for Android via Java API Referansı
description: Ortak slayt görünüm özelliklerini temsil eder.
type: docs
url: /tr/com.aspose.slides/commonslideviewproperties/
---
**Kalıtım:**
java.lang.Object

**Uygulanan Tüm Arabirimler:**
[com.aspose.slides.ICommonSlideViewProperties](../../com.aspose.slides/icommonslideviewproperties)
```
public class CommonSlideViewProperties implements ICommonSlideViewProperties
```

Ortak slayt görünüm özelliklerini temsil eder.

--------------------

> ```
> The following example shows how to set the zoom value for slide of PowerPoint Presentation.
>  
>  // Bir sunum dosyasını temsil eden Presentation nesnesi oluşturur
>  Presentation pres = new Presentation("demo.pptx");
>  try {
>      // Sunumun Görünüm Özelliklerini Ayarlama
>      pres.getViewProperties().getSlideViewProperties().setScale(100); // Slayt görünümü için yüzde olarak yakınlaştırma değeri
>      pres.getViewProperties().getNotesViewProperties().setScale(100); // Notlar görünümü için yüzde olarak yakınlaştırma değeri
>      pres.save("Zoom_out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getScale()](#getScale--) | Görünüm ölçekleme oranını yüzde olarak belirtir. |
| [setScale(int value)](#setScale-int-) | Görünüm ölçekleme oranını yüzde olarak belirtir. |
| [getVariableScale()](#getVariableScale--) | Görünüm içeriğinin mevcut pencere boyutuna en iyi şekilde sığacak şekilde otomatik olarak ölçeklenmesi gerektiğini belirtir. |
| [setVariableScale(boolean value)](#setVariableScale-boolean-) | Görünüm içeriğinin mevcut pencere boyutuna en iyi şekilde sığacak şekilde otomatik olarak ölçeklenmesi gerektiğini belirtir. |
| [getDrawingGuides()](#getDrawingGuides--) | Çizim kılavuzlarının koleksiyonunu döndürür. |
### getScale() {#getScale--}
```
public final int getScale()
```


Görünüm ölçekleme oranını yüzde olarak belirtir. Okuma/yazma int.

**Döndürür:**
int
### setScale(int value) {#setScale-int-}
```
public final void setScale(int value)
```


Görünüm ölçekleme oranını yüzde olarak belirtir. Okuma/yazma int.

**Parametreler:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getVariableScale() {#getVariableScale--}
```
public final boolean getVariableScale()
```


Görünüm içeriğinin mevcut pencere boyutuna en iyi şekilde sığacak şekilde otomatik olarak ölçeklenmesi gerektiğini belirtir. Okuma/yazma boolean.

**Döndürür:**
boolean
### setVariableScale(boolean value) {#setVariableScale-boolean-}
```
public final void setVariableScale(boolean value)
```


Görünüm içeriğinin mevcut pencere boyutuna en iyi şekilde sığacak şekilde otomatik olarak ölçeklenmesi gerektiğini belirtir. Okuma/yazma boolean.

**Parametreler:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getDrawingGuides() {#getDrawingGuides--}
```
public final IDrawingGuidesCollection getDrawingGuides()
```


Çizim kılavuzlarının koleksiyonunu döndürür. Yalnızca okunur [IDrawingGuidesCollection](../../com.aspose.slides/idrawingguidescollection)

--------------------

> ```
> The following sample code shows how to add the new drawing guides in a PowerPoint presentation.
>  
>  Presentation pres = new Presentation();
>  try {
>      SizeF slideSize = pres.getSlideSize().getSize();
> 
>      IDrawingGuidesCollection guides = pres.getViewProperties().getSlideViewProperties().getDrawingGuides();
>      // Yeni dikey çizim kılavuzunu slayt merkezinin sağına ekleme
>      guides.add(Orientation.Vertical, (float)(slideSize.getWidth()) / 2 + 12.5f);
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