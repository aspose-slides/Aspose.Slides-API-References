---
title: ZoomObject
second_title: Java API Referansı aracılığıyla Android için Aspose.Slides
description: Bir slayttaki Zoom nesnesini temsil eder.
type: docs
url: /tr/com.aspose.slides/zoomobject/
---
**Kalıtım:**
java.lang.Object, [com.aspose.slides.Shape](../../com.aspose.slides/shape), [com.aspose.slides.GraphicalObject](../../com.aspose.slides/graphicalobject)

**Uygulanan Tüm Arayüzler:**
[com.aspose.slides.IZoomObject](../../com.aspose.slides/izoomobject)
```
public class ZoomObject extends GraphicalObject implements IZoomObject
```

Bir slayttaki Zoom nesnesini temsil eder.
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getImageType()](#getImageType--) | Zoom nesnesinin görüntü tipini alır veya ayarlar. |
| [setImageType(int value)](#setImageType-int-) | Zoom nesnesinin görüntü tipini alır veya ayarlar. |
| [getReturnToParent()](#getReturnToParent--) | Slayt gösterisindeki gezinme davranışını alır veya ayarlar. |
| [setReturnToParent(boolean value)](#setReturnToParent-boolean-) | Slayt gösterisindeki gezinme davranışını alır veya ayarlar. |
| [getShowBackground()](#getShowBackground--) | Zoom nesnesinin hedef slaydın arka planını kullanıp kullanmayacağını belirten değeri alır veya ayarlar. |
| [setShowBackground(boolean value)](#setShowBackground-boolean-) | Zoom nesnesinin hedef slaydın arka planını kullanıp kullanmayacağını belirten değeri alır veya ayarlar. |
| [getZoomImage()](#getZoomImage--) | Zoom nesnesi için görüntüyü alır veya ayarlar. |
| [setZoomImage(IPPImage value)](#setZoomImage-com.aspose.slides.IPPImage-) | Zoom nesnesi için görüntüyü alır veya ayarlar. |
| [getTransitionDuration()](#getTransitionDuration--) | Zoom ve slayt arasındaki geçiş süresini alır veya ayarlar. |
| [setTransitionDuration(float value)](#setTransitionDuration-float-) | Zoom ve slayt arasındaki geçiş süresini alır veya ayarlar. |
### getImageType() {#getImageType--}
```
public final int getImageType()
```

Zoom nesnesinin görüntü tipini alır veya ayarlar. Okuma/yazma [ZoomImageType](../../com.aspose.slides/zoomimagetype). Varsayılan değer: Preview

--------------------

> ```
> Next example demonstrates changing Image Type to Preview value. 
>  In this case current image of a Zoom object changes to slide image:
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      FileInputStream fos = null;
>      try {
>          fos = new FileInputStream("image.png");
>          IPPImage image = pres.getImages().addImage(fos);
>          IZoomFrame zoomFrame = pres.getSlides().get_Item(0).getShapes().addZoomFrame(150, 20, 50, 50, pres.getSlides().get_Item(1), image);
>          zoomFrame.setImageType(ZoomImageType.Preview);
>      } finally {
>          if (fos != null) fos.close();
>      }
>  } catch(IOException e) {
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


--------------------

Zoom nesnesinin slayt önizlemesini mi yoksa bir kapak görüntüsünü mü kullandığını belirtir.

**Döndürür:**
int
### setImageType(int value) {#setImageType-int-}
```
public final void setImageType(int value)
```

Zoom nesnesinin görüntü tipini alır veya ayarlar. Okuma/yazma [ZoomImageType](../../com.aspose.slides/zoomimagetype). Varsayılan değer: Preview

--------------------

> ```
> Next example demonstrates changing Image Type to Preview value. 
>  In this case current image of a Zoom object changes to slide image:
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      FileInputStream fos = null;
>      try {
>          fos = new FileInputStream("image.png");
>          IPPImage image = pres.getImages().addImage(fos);
>          IZoomFrame zoomFrame = pres.getSlides().get_Item(0).getShapes().addZoomFrame(150, 20, 50, 50, pres.getSlides().get_Item(1), image);
>          zoomFrame.setImageType(ZoomImageType.Preview);
>      } finally {
>          if (fos != null) fos.close();
>      }
>  } catch(IOException e) {
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


--------------------

Zoom nesnesinin slayt önizlemesini mi yoksa bir kapak görüntüsünü mü kullandığını belirtir.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | int |  |

### getReturnToParent() {#getReturnToParent--}
```
public final boolean getReturnToParent()
```

Slayt gösterisindeki gezinme davranışını alır veya ayarlar. Okuma/yazma boolean. Varsayılan değer: false

--------------------

> ```
> Örnek:
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>       IZoomFrame zoomFrame = pres.getSlides().get_Item(0).getShapes().addZoomFrame(150, 20, 50, 50, pres.getSlides().get_Item(1));
>       zoomFrame.setReturnToParent(true);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


--------------------

Özelliğin true değeri, slayt gösterisinde üst öğeye geri dönme gezinme davranışını belirtir.

**Döndürür:**
boolean
### setReturnToParent(boolean value) {#setReturnToParent-boolean-}
```
public final void setReturnToParent(boolean value)
```

Slayt gösterisindeki gezinme davranışını alır veya ayarlar. Okuma/yazma boolean. Varsayılan değer: false

--------------------

> ```
> Örnek:
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>       IZoomFrame zoomFrame = pres.getSlides().get_Item(0).getShapes().addZoomFrame(150, 20, 50, 50, pres.getSlides().get_Item(1));
>       zoomFrame.setReturnToParent(true);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

--------------------

Özelliğin true değeri, slayt gösterisinde üst öğeye geri dönme gezinme davranışını belirtir.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | boolean |  |

### getShowBackground() {#getShowBackground--}
```
public final boolean getShowBackground()
```

Zoom nesnesinin hedef slaydın arka planını kullanıp kullanmayacağını belirten değeri alır veya ayarlar. Okuma/yazma boolean. Varsayılan değer: true

--------------------

> ```
> örnek bir Zoom nesnesinin görüntüsünün arka planını kaldırma örneğini gösterir:
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>       IZoomFrame zoomFrame = pres.getSlides().get_Item(0).getShapes().addZoomFrame(150, 20, 50, 50, pres.getSlides().get_Item(1));
>       zoomFrame.setShowBackground(false);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Döndürür:**
boolean
### setShowBackground(boolean value) {#setShowBackground-boolean-}
```
public final void setShowBackground(boolean value)
```

Zoom nesnesinin hedef slaydın arka planını kullanıp kullanmayacağını belirten değeri alır veya ayarlar. Okuma/yazma boolean. Varsayılan değer: true

--------------------

> ```
> örnek, bir Zoom nesnesinin görüntüsünün arka planını kaldırmayı gösterir:
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>       IZoomFrame zoomFrame = pres.getSlides().get_Item(0).getShapes().addZoomFrame(150, 20, 50, 50, pres.getSlides().get_Item(1));
>       zoomFrame.setShowBackground(false);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | boolean |  |

### getZoomImage() {#getZoomImage--}
```
public final IPPImage getZoomImage()
```

Zoom nesnesi için görüntüyü alır veya ayarlar. Okuma/yazma [IPPImage](../../com.aspose.slides/ippimage).

--------------------

> ```
> örnek, bir Zoom nesnesinin görüntüsünü değiştirmeyi gösterir:
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      IZoomFrame zoomFrame = pres.getSlides().get_Item(0).getShapes().addZoomFrame(150, 20, 50, 50, pres.getSlides().get_Item(1));
>      FileInputStream fos = null;
>      try {
>          fos = new FileInputStream("image.png");
>          IPPImage image = pres.getImages().addImage(fos);
>          zoomFrame.setImage(image);
>      } finally {
>          if (fos != null) fos.close();
>      }
>  } catch(IOException e) {
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Döndürür:**
[IPPImage](../../com.aspose.slides/ippimage)
### setZoomImage(IPPImage value) {#setZoomImage-com.aspose.slides.IPPImage-}
```
public final void setZoomImage(IPPImage value)
```

Zoom nesnesi için görüntüyü alır veya ayarlar. Okuma/yazma [IPPImage](../../com.aspose.slides/ippimage).

--------------------

> ```
> örnek, bir Zoom nesnesinin görüntüsünü değiştirmeyi gösterir:
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      IZoomFrame zoomFrame = pres.getSlides().get_Item(0).getShapes().addZoomFrame(150, 20, 50, 50, pres.getSlides().get_Item(1));
>      FileInputStream fos = null;
>      try {
>          fos = new FileInputStream("image.png");
>          IPPImage image = pres.getImages().addImage(fos);
>          zoomFrame.setImage(image);
>      } finally {
>          if (fos != null) fos.close();
>      }
>  } catch(IOException e) {
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [IPPImage](../../com.aspose.slides/ippimage) |  |

### getTransitionDuration() {#getTransitionDuration--}
```
public final float getTransitionDuration()
```

Zoom ve slayt arasındaki geçiş süresini alır veya ayarlar. Okuma/yazma float. Varsayılan değer: 1.0f

--------------------

> ```
> örnek, Zoom ve slayt arasındaki geçiş süresinin değiştirilmesini gösterir:
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>       IZoomFrame zoomFrame = pres.getSlides().get_Item(0).getShapes().addZoomFrame(150, 20, 50, 50, pres.getSlides().get_Item(1));
>       zoomFrame.setTransitionDuration(2.5f);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


--------------------

Belirtilmemişse (TransitionDur = 0), hedef slaydın geçişi ve bu geçişle ilişkili zamanlamalar kullanılır.

**Döndürür:**
float
### setTransitionDuration(float value) {#setTransitionDuration-float-}
```
public final void setTransitionDuration(float value)
```

Zoom ve slayt arasındaki geçiş süresini alır veya ayarlar. Okuma/yazma float. Varsayılan değer: 1.0f

--------------------

> ```
> örnek, Zoom ve slayt arasındaki geçiş süresinin değiştirilmesini gösterir:
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>       IZoomFrame zoomFrame = pres.getSlides().get_Item(0).getShapes().addZoomFrame(150, 20, 50, 50, pres.getSlides().get_Item(1));
>       zoomFrame.setTransitionDuration(2.5f);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

--------------------

Belirtilmemişse (TransitionDur = 0), hedef slaydın geçişi ve bu geçişle ilişkili zamanlamalar kullanılır.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | float |  |