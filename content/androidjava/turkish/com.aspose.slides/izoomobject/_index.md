---
title: IZoomObject
second_title: Aspose.Slides for Android için Java API Referansı
description: Bir slaytta Zoom nesnesini temsil eder.
type: docs
url: /tr/com.aspose.slides/izoomobject/
---
**Uygulanan Tüm Arabirimler:**
[com.aspose.slides.IGraphicalObject](../../com.aspose.slides/igraphicalobject)
```
public interface IZoomObject extends IGraphicalObject
```

Bir slaytta Zoom nesnesini temsil eder.
## Yöntemler

| Metot | Açıklama |
| --- | --- |
| [getImageType()](#getImageType--) | Bir yakınlaştırma nesnesinin görüntü tipini alır veya ayarlar. |
| [setImageType(int value)](#setImageType-int-) | Bir yakınlaştırma nesnesinin görüntü tipini alır veya ayarlar. |
| [getReturnToParent()](#getReturnToParent--) | Slayt gösterisinde gezinme davranışını alır veya ayarlar. |
| [setReturnToParent(boolean value)](#setReturnToParent-boolean-) | Slayt gösterisinde gezinme davranışını alır veya ayarlar. |
| [getShowBackground()](#getShowBackground--) | Zoom’un hedef slaydın arka planını kullanıp kullanmayacağını belirten değeri alır veya ayarlar. |
| [setShowBackground(boolean value)](#setShowBackground-boolean-) | Zoom’un hedef slaydın arka planını kullanıp kullanmayacağını belirten değeri alır veya ayarlar. |
| [getZoomImage()](#getZoomImage--) | Yakınlaştırma nesnesi için resmi alır veya ayarlar. |
| [setZoomImage(IPPImage value)](#setZoomImage-com.aspose.slides.IPPImage-) | Yakınlaştırma nesnesi için resmi alır veya ayarlar. |
| [getTransitionDuration()](#getTransitionDuration--) | Zoom ile slayt arasındaki geçiş süresini alır veya ayarlar. |
| [setTransitionDuration(float value)](#setTransitionDuration-float-) | Zoom ile slayt arasındaki geçiş süresini alır veya ayarlar. |
### getImageType() {#getImageType--}
```
public abstract int getImageType()
```

Bir yakınlaştırma nesnesinin görüntü tipini alır veya ayarlar. Okunur/yazılır [ZoomImageType](../../com.aspose.slides/zoomimagetype). Varsayılan değer: Preview

--------------------

> ```
> This example demonstrates changing Image Type to Preview value. 
>  In this case the current image of a Zoom object changes to slide image:
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

Zoom nesnesinin slayt önizlemesini mi yoksa kapak resmini mi kullandığını belirtir.

**Dönüş Değeri:**
int
### setImageType(int value) {#setImageType-int-}
```
public abstract void setImageType(int value)
```

Bir yakınlaştırma nesnesinin görüntü tipini alır veya ayarlar. Okunur/yazılır [ZoomImageType](../../com.aspose.slides/zoomimagetype). Varsayılan değer: Preview

--------------------

> ```
> This example demonstrates changing Image Type to Preview value. 
>  In this case the current image of a Zoom object changes to slide image:
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

Zoom nesnesinin slayt önizlemesini mi yoksa kapak resmini mi kullandığını belirtir.

**Parametreler:**
| Parametre | Tip | Açıklama |
| --- | --- | --- |
| value | int |  |
### getReturnToParent() {#getReturnToParent--}
```
public abstract boolean getReturnToParent()
```

Slayt gösterisinde gezinme davranışını alır veya ayarlar. Okunur/yazılır boolean. Varsayılan değer: false

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

**Dönüş Değeri:**
boolean
### setReturnToParent(boolean value) {#setReturnToParent-boolean-}
```
public abstract void setReturnToParent(boolean value)
```

Slayt gösterisinde gezinme davranışını alır veya ayarlar. Okunur/yazılır boolean. Varsayılan değer: false

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
public abstract boolean getShowBackground()
```

Zoom’un hedef slaydın arka planını kullanıp kullanmayacağını belirten değeri alır veya ayarlar. Okunur/yazılır boolean. Varsayılan değer: true

--------------------

> ```
> The example demonstrates removing the background of an image of a Zoom object:
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>       IZoomFrame zoomFrame = pres.getSlides().get_Item(0).getShapes().addZoomFrame(150, 20, 50, 50, pres.getSlides().get_Item(1));
>       zoomFrame.setShowBackground(false);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Dönüş Değeri:**
boolean
### setShowBackground(boolean value) {#setShowBackground-boolean-}
```
public abstract void setShowBackground(boolean value)
```

Zoom’un hedef slaydın arka planını kullanıp kullanmayacağını belirten değeri alır veya ayarlar. Okunur/yazılır boolean. Varsayılan değer: true

--------------------

> ```
> The example demonstrates removing the background of an image of a Zoom object:
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
public abstract IPPImage getZoomImage()
```

Yakınlaştırma nesnesi için resmi alır veya ayarlar. Okunur/yazılır [IPPImage](../../com.aspose.slides/ippimage).

--------------------

> ```
> The example demonstrates changing an image of a Zoom object:
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

**Dönüş Değeri:**
[IPPImage](../../com.aspose.slides/ippimage)
### setZoomImage(IPPImage value) {#setZoomImage-com.aspose.slides.IPPImage-}
```
public abstract void setZoomImage(IPPImage value)
```

Yakınlaştırma nesnesi için resmi alır veya ayarlar. Okunur/yazılır [IPPImage](../../com.aspose.slides/ippimage).

--------------------

> ```
> The example demonstrates changing an image of a Zoom object:
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
| Parametre | Tip | Açıklama |
| --- | --- | --- |
| value | [IPPImage](../../com.aspose.slides/ippimage) |  |
### getTransitionDuration() {#getTransitionDuration--}
```
public abstract float getTransitionDuration()
```

Zoom ile slayt arasındaki geçiş süresini alır veya ayarlar. Okunur/yazılır float. Varsayılan değer: 1.0f

--------------------

> ```
> the example demonstrates changing the duration of the transition between Zoom and slide:
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

**Dönüş Değeri:**
float
### setTransitionDuration(float value) {#setTransitionDuration-float-}
```
public abstract void setTransitionDuration(float value)
```

Zoom ile slayt arasındaki geçiş süresini alır veya ayarlar. Okunur/yazılır float. Varsayılan değer: 1.0f

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

Belirtilmemişse (TransitionDur = 0), hedef slaydın geçişi ve bu geçişle ilişkili zamanlamalar kullanılır.

**Parametreler:**
| Parametre | Tip | Açıklama |
| --- | --- | --- |
| value | float |  |