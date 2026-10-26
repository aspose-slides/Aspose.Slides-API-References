---
title: IZoomObject
second_title: Aspose.Slides için Java API Referansı
description: Bir slayttaki Zoom nesnesini temsil eder.
type: docs
url: /tr/com.aspose.slides/izoomobject/
---
**All Implemented Interfaces:**
[com.aspose.slides.IGraphicalObject](../../com.aspose.slides/igraphicalobject)
```
public interface IZoomObject extends IGraphicalObject
```

Bir slaytta Zoom nesnesini temsil eder.
## Yöntemler

| Method | Description |
| --- | --- |
| [getImageType()](#getImageType--) | Bir Zoom nesnesinin resim türünü alır veya ayarlar. |
| [setImageType(int value)](#setImageType-int-) | Bir Zoom nesnesinin resim türünü alır veya ayarlar. |
| [getReturnToParent()](#getReturnToParent--) | Slayt gösterisindeki gezinme davranışını alır veya ayarlar. |
| [setReturnToParent(boolean value)](#setReturnToParent-boolean-) | Slayt gösterisindeki gezinme davranışını alır veya ayarlar. |
| [getShowBackground()](#getShowBackground--) | Zoom’un hedef slaytın arka planını kullanıp kullanmayacağını belirten değeri alır veya ayarlar. |
| [setShowBackground(boolean value)](#setShowBackground-boolean-) | Zoom’un hedef slaytın arka planını kullanıp kullanmayacağını belirten değeri alır veya ayarlar. |
| [getZoomImage()](#getZoomImage--) | Zoom nesnesi için resmi alır veya ayarlar. |
| [setZoomImage(IPPImage value)](#setZoomImage-com.aspose.slides.IPPImage-) | Zoom nesnesi için resmi alır veya ayarlar. |
| [getTransitionDuration()](#getTransitionDuration--) | Zoom ile slayt arasındaki geçiş süresini alır veya ayarlar. |
| [setTransitionDuration(float value)](#setTransitionDuration-float-) | Zoom ile slayt arasındaki geçiş süresini alır veya ayarlar. |
### getImageType() {#getImageType--}
```
public abstract int getImageType()
```

Bir Zoom nesnesinin resim türünü alır veya ayarlar. Okunur/Yazılır [ZoomImageType](../../com.aspose.slides/zoomimagetype). Varsayılan değer: Preview

--------------------

> ```
> This example demonstrates changing Image Type to Preview value. 
>  In this case the current image of a Zoom object changes to slide image:
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

Zoom nesnesinin slayt ön izlemeyi mi yoksa bir kapak resmini mi kullandığını belirler.

**Döndürür:**
int
### setImageType(int value) {#setImageType-int-}
```
public abstract void setImageType(int value)
```

Bir Zoom nesnesinin resim türünü alır veya ayarlar. Okunur/Yazılır [ZoomImageType](../../com.aspose.slides/zoomimagetype). Varsayılan değer: Preview

--------------------

> ```
> This example demonstrates changing Image Type to Preview value. 
>  In this case the current image of a Zoom object changes to slide image:
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

Zoom nesnesinin slayt ön izlemeyi mi yoksa bir kapak resmini mi kullandığını belirler.

**Parametreler:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getReturnToParent() {#getReturnToParent--}
```
public abstract boolean getReturnToParent()
```

Slayt gösterisindeki gezinme davranışını alır veya ayarlar. Okunur/Yazılır boolean. Varsayılan değer: false

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

Özelliğin true değeri, slayt gösterisinde üst öğeye dönüş gezinme davranışını belirtir.

**Döndürür:**
boolean
### setReturnToParent(boolean value) {#setReturnToParent-boolean-}
```
public abstract void setReturnToParent(boolean value)
```

Slayt gösterisindeki gezinme davranışını alır veya ayarlar. Okunur/Yazılır boolean. Varsayılan değer: false

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

Özelliğin true değeri, slayt gösterisinde üst öğeye dönüş gezinme davranışını belirtir.

**Parametreler:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getShowBackground() {#getShowBackground--}
```
public abstract boolean getShowBackground()
```

Zoom’un hedef slaytın arka planını kullanıp kullanmayacağını belirten değeri alır veya ayarlar. Okunur/Yazılır boolean. Varsayılan değer: true

--------------------

> ```
> Bu örnek, bir Zoom nesnesinin görüntüsünün arka planını kaldırmayı gösterir:
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
public abstract void setShowBackground(boolean value)
```

Zoom’un hedef slaytın arka planını kullanıp kullanmayacağını belirten değeri alır veya ayarlar. Okunur/Yazılır boolean. Varsayılan değer: true

--------------------

> ```
> Bu örnek, bir Zoom nesnesinin görüntüsünün arka planını kaldırmayı gösterir:
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
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getZoomImage() {#getZoomImage--}
```
public abstract IPPImage getZoomImage()
```

Zoom nesnesi için resmi alır veya ayarlar. Okunur/Yazılır [IPPImage](../../com.aspose.slides/ippimage).

--------------------

> ```
> Bu örnek, bir Zoom nesnesinin görüntüsünü değiştirmeyi gösterir:
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
public abstract void setZoomImage(IPPImage value)
```

Zoom nesnesi için resmi alır veya ayarlar. Okunur/Yazılır [IPPImage](../../com.aspose.slides/ippimage).

--------------------

> ```
> Bu örnek, bir Zoom nesnesinin görüntüsünü değiştirmeyi gösterir:
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
| Parameter | Type | Description |
| --- | --- | --- |
| value | [IPPImage](../../com.aspose.slides/ippimage) |  |

### getTransitionDuration() {#getTransitionDuration--}
```
public abstract float getTransitionDuration()
```

Zoom ile slayt arasındaki geçiş süresini alır veya ayarlar. Okunur/Yazılır float. Varsayılan değer: 1.0f

--------------------

> ```
> örnek, Zoom ve slayt arasındaki geçiş süresini değiştirmeyi gösterir:
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

Belirtilmezse (TransitionDur = 0), hedef slaytın geçişi ve o geçişe bağlı zamanlamalar kullanılır.

**Döndürür:**
float
### setTransitionDuration(float value) {#setTransitionDuration-float-}
```
public abstract void setTransitionDuration(float value)
```

Zoom ile slayt arasındaki geçiş süresini alır veya ayarlar. Okunur/Yazılır float. Varsayılan değer: 1.0f

--------------------

> ```
> örnek, Zoom ve slayt arasındaki geçiş süresini değiştirmeyi gösterir:
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

Belirtilmezse (TransitionDur = 0), hedef slaytın geçişi ve o geçişe bağlı zamanlamalar kullanılır.

**Parametreler:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | float |  |