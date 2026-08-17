---
title: ZoomObject
second_title: Aspose.Slides for Java API Referansı
description: Bir slaytta Zoom nesnesini temsil eder.
type: docs
url: /tr/com.aspose.slides/zoomobject/
---
**Kalıtım:**
java.lang.Object, [com.aspose.slides.Shape](../../com.aspose.slides/shape), [com.aspose.slides.GraphicalObject](../../com.aspose.slides/graphicalobject)

**Tüm Uygulanan Arabirimler:**
[com.aspose.slides.IZoomObject](../../com.aspose.slides/izoomobject)
```
public class ZoomObject extends GraphicalObject implements IZoomObject
```

Bir slaytta Zoom nesnesini temsil eder.
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getImageType()](#getImageType--) | Bir yakınlaştırma nesnesinin görüntü türünü alır veya ayarlar. |
| [setImageType(int value)](#setImageType-int-) | Bir yakınlaştırma nesnesinin görüntü türünü alır veya ayarlar. |
| [getReturnToParent()](#getReturnToParent--) | Slayt gösterisinde gezinme davranışını alır veya ayarlar. |
| [setReturnToParent(boolean value)](#setReturnToParent-boolean-) | Slayt gösterisinde gezinme davranışını alır veya ayarlar. |
| [getShowBackground()](#getShowBackground--) | Zoom’un hedef slaydın arka planını kullanıp kullanmayacağını belirten değeri alır veya ayarlar. |
| [setShowBackground(boolean value)](#setShowBackground-boolean-) | Zoom’un hedef slaydın arka planını kullanıp kullanmayacağını belirten değeri alır veya ayarlar. |
| [getZoomImage()](#getZoomImage--) | Zoom nesnesi için görüntüyü alır veya ayarlar. |
| [setZoomImage(IPPImage value)](#setZoomImage-com.aspose.slides.IPPImage-) | Zoom nesnesi için görüntüyü alır veya ayarlar. |
| [getTransitionDuration()](#getTransitionDuration--) | Zoom ile slayt arasındaki geçiş süresini alır veya ayarlar. |
| [setTransitionDuration(float value)](#setTransitionDuration-float-) | Zoom ile slayt arasındaki geçiş süresini alır veya ayarlar. |
### getImageType() {#getImageType--}
```
public final int getImageType()
```

Bir yakınlaştırma nesnesinin görüntü türünü alır veya ayarlar. Okuma/yazma [ZoomImageType](../../com.aspose.slides/zoomimagetype). Varsayılan değer: Preview

--------------------

> ```
> Son örnek, Görüntü Türünü Preview değerine değiştirmeyi gösterir. 
>  Bu durumda bir Zoom nesnesinin mevcut görüntüsü slayt görüntüsüne değişir:
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      IPPImage image = pres.getImages().addImage(Files.readAllBytes(Paths.get("image.png")));
>      IZoomFrame zoomFrame = pres.getSlides().get_Item(0).getShapes().addZoomFrame(150, 20, 50, 50, pres.getSlides().get_Item(1), image);
>      zoomFrame.setImageType(ZoomImageType.Preview);
>  } catch(IOException e) {
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


--------------------

Zoom nesnesinin slayt ön izlemesini mi yoksa bir kapak görüntüsü mü kullandığını belirtir.

**Döndürür:**
int
### setImageType(int value) {#setImageType-int-}
```
public final void setImageType(int value)
```

Bir yakınlaştırma nesnesinin görüntü türünü alır veya ayarlar. Okuma/yazma [ZoomImageType](../../com.aspose.slides/zoomimagetype). Varsayılan değer: Preview

--------------------

> ```
> Next example demonstrates changing Image Type to Preview value. 
>  In this case current image of a Zoom object changes to slide image:
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      IPPImage image = pres.getImages().addImage(Files.readAllBytes(Paths.get("image.png")));
>      IZoomFrame zoomFrame = pres.getSlides().get_Item(0).getShapes().addZoomFrame(150, 20, 50, 50, pres.getSlides().get_Item(1), image);
>      zoomFrame.setImageType(ZoomImageType.Preview);
>  } catch(IOException e) {
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


--------------------

Zoom nesnesinin slayt ön izlemesini mi yoksa bir kapak görüntüsü mü kullandığını belirtir.

**Parametreler:**
| Parametre | Tip | Açıklama |
| --- | --- | --- |
| value | int |  |
### getReturnToParent() {#getReturnToParent--}
```
public final boolean getReturnToParent()
```

Slayt gösterisinde gezinme davranışını alır veya ayarlar. Okuma/yazma boolean. Varsayılan değer: false

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

Özelliğin true değeri, slayt gösterisinde üst öğeye dönüş davranışını belirtir.

**Döndürür:**
boolean
### setReturnToParent(boolean value) {#setReturnToParent-boolean-}
```
public final void setReturnToParent(boolean value)
```

Slayt gösterisinde gezinme davranışını alır veya ayarlar. Okuma/yazma boolean. Varsayılan değer: false

--------------------

> ```
> Example:
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

Özelliğin true değeri, slayt gösterisinde üst öğeye dönüş davranışını belirtir.

**Parametreler:**
| Parametre | Tip | Açıklama |
| --- | --- | --- |
| value | boolean |  |
### getShowBackground() {#getShowBackground--}
```
public final boolean getShowBackground()
```

Zoom’un hedef slaydın arka planını kullanıp kullanmayacağını belirten değeri alır veya ayarlar. Okuma/yazma boolean. Varsayılan değer: true

--------------------

> ```
> örnek, bir Zoom nesnesinin görüntüsünün arka planının kaldırılmasını gösterir:
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

Zoom’un hedef slaydın arka planını kullanıp kullanmayacağını belirten değeri alır veya ayarlar. Okuma/yazma boolean. Varsayılan değer: true

--------------------

> ```
> örnek, bir Zoom nesnesinin görüntüsünün arka planının kaldırılmasını gösterir:
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
| Parametre | Tip | Açıklama |
| --- | --- | --- |
| value | boolean |  |
### getZoomImage() {#getZoomImage--}
```
public final IPPImage getZoomImage()
```

Zoom nesnesi için görüntüyü alır veya ayarlar. Okuma/yazma [IPPImage](../../com.aspose.slides/ippimage).

--------------------

> ```
> örnek, bir Zoom nesnesinin görüntüsünün değiştirilmesini gösterir:
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      IZoomFrame zoomFrame = pres.getSlides().get_Item(0).getShapes().addZoomFrame(150, 20, 50, 50, pres.getSlides().get_Item(1));
>      IPPImage image = pres.getImages().addImage(Files.readAllBytes(Paths.get("image.png")));
>      zoomFrame.setImage(image);
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
> örnek, bir Zoom nesnesinin görüntüsünün değiştirilmesini gösterir:
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      IZoomFrame zoomFrame = pres.getSlides().get_Item(0).getShapes().addZoomFrame(150, 20, 50, 50, pres.getSlides().get_Item(1));
>      IPPImage image = pres.getImages().addImage(Files.readAllBytes(Paths.get("image.png")));
>      zoomFrame.setImage(image);
>  } catch(IOException e) {
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Parametreler:**
| Parametre | Tip | Açıklama |
| --- | --- | --- |
| value | [IPPImage](../../com.aspose.slides/ippimage) |  |
### getTransitionDuration() {#getTransitionDuration--}
```
public final float getTransitionDuration()
```

Zoom ile slayt arasındaki geçiş süresini alır veya ayarlar. Okuma/yazma float. Varsayılan değer: 1.0f

--------------------

> ```
> örnek, Zoom ile slayt arasındaki geçiş süresinin değiştirilmesini gösterir:
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

Belirtilmezse (TransitionDur = 0), hedef slaydın geçişi ve bu geçişle ilişkili zamanlamalar kullanılır.

**Döndürür:**
float
### setTransitionDuration(float value) {#setTransitionDuration-float-}
```
public final void setTransitionDuration(float value)
```

Zoom ile slayt arasındaki geçiş süresini alır veya ayarlar. Okuma/yazma float. Varsayılan değer: 1.0f

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

Belirtilmezse (TransitionDur = 0), hedef slaydın geçişi ve bu geçişle ilişkili zamanlamalar kullanılır.

**Parametreler:**
| Parametre | Tip | Açıklama |
| --- | --- | --- |
| value | float |  |