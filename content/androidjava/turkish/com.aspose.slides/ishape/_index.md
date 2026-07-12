---
title: IShape
second_title: Aspose.Slides for Android Java API Referansı
description: Bir slayttaki şekli temsil eder.
type: docs
url: /tr/com.aspose.slides/ishape/
---
**Uygulanan Tüm Arayüzler:**
[com.aspose.slides.ISlideComponent](../../com.aspose.slides/islidecomponent), [com.aspose.slides.IHyperlinkContainer](../../com.aspose.slides/ihyperlinkcontainer)
```
public interface IShape extends ISlideComponent, IHyperlinkContainer
```

Bir slayttaki şekli temsil eder.
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [isTextHolder()](#isTextHolder--) | Şeklin TextHolder olup olmadığını belirler. |
| [getPlaceholder()](#getPlaceholder--) | Bir şekil için yer tutucuyu döndürür. |
| [addPlaceholder(IPlaceholder placeholderToCopyFrom)](#addPlaceholder-com.aspose.slides.IPlaceholder-) | Yer tutucu yoksa yeni bir yer tutucu ekler ve yer tutucu özelliklerini belirtilen birine ayarlar. |
| [removePlaceholder()](#removePlaceholder--) | Bu şeklin yer tutucu olmadığını tanımlar. |
| [getCustomData()](#getCustomData--) | Şeklin özel verilerini döndürür. |
| [getRawFrame()](#getRawFrame--) | Ham şekil çerçevesinin özelliklerini döndürür veya ayarlar. |
| [setRawFrame(IShapeFrame value)](#setRawFrame-com.aspose.slides.IShapeFrame-) | Ham şekil çerçevesinin özelliklerini döndürür veya ayarlar. |
| [getFrame()](#getFrame--) | Ham şekil çerçevesinin özelliklerini döndürür veya ayarlar. |
| [setFrame(IShapeFrame value)](#setFrame-com.aspose.slides.IShapeFrame-) | Ham şekil çerçevesinin özelliklerini döndürür veya ayarlar. |
| [getLineFormat()](#getLineFormat--) | Bir şeklin çizgi biçimlendirme özelliklerini içeren LineFormat nesnesini döndürür. |
| [getThreeDFormat()](#getThreeDFormat--) | Bir şeklin çizgi biçimlendirme özelliklerini içeren ThreeDFormat nesnesini döndürür. |
| [getEffectFormat()](#getEffectFormat--) | Bir şekle uygulanan piksel efektlerini içeren EffectFormat nesnesini döndürür. |
| [getFillFormat()](#getFillFormat--) | Bir şeklin dolgu biçimlendirme özelliklerini içeren FillFormat nesnesini döndürür. |
| [getImage()](#getImage--) | Şeklin küçük resmini döndürür. |
| [getImage(int bounds, float scaleX, float scaleY)](#getImage-int-float-float-) | Şeklin küçük resmini döndürür. |
| [getHidden()](#getHidden--) | Şeklin gizli olup olmadığını belirler. |
| [setHidden(boolean value)](#setHidden-boolean-) | Şeklin gizli olup olmadığını belirler. |
| [getZOrderPosition()](#getZOrderPosition--) | Bir şeklin z-sırasındaki konumunu döndürür. |
| [getConnectionSiteCount()](#getConnectionSiteCount--) | Şekildeki bağlantı noktalarının sayısını döndürür. |
| [getRotation()](#getRotation--) | Belirtilen şeklin z ekseni etrafında döndürüldüğü derece sayısını döndürür veya ayarlar. |
| [setRotation(float value)](#setRotation-float-) | Belirtilen şeklin z ekseni etrafında döndürüldüğü derece sayısını döndürür veya ayarlar. |
| [getX()](#getX--) | Şeklin sol üst köşesinin x koordinatını, puan cinsinden alır veya ayarlar. |
| [setX(float value)](#setX-float-) | Şeklin sol üst köşesinin x koordinatını, puan cinsinden alır veya ayarlar. |
| [getY()](#getY--) | Şeklin sol üst köşesinin y koordinatını, puan cinsinden alır veya ayarlar. |
| [setY(float value)](#setY-float-) | Şeklin sol üst köşesinin y koordinatını, puan cinsinden alır veya ayarlar. |
| [getWidth()](#getWidth--) | Şeklin genişliğini, puan cinsinden alır veya ayarlar. |
| [setWidth(float value)](#setWidth-float-) | Şeklin genişliğini, puan cinsinden alır veya ayarlar. |
| [getHeight()](#getHeight--) | Şeklin yüksekliğini, puan cinsinden alır veya ayarlar. |
| [setHeight(float value)](#setHeight-float-) | Şeklin yüksekliğini, puan cinsinden alır veya ayarlar. |
| [getAlternativeText()](#getAlternativeText--) | Bir şekille ilişkili alternatif metni döndürür veya ayarlar. |
| [setAlternativeText(String value)](#setAlternativeText-java.lang.String-) | Bir şekille ilişkili alternatif metni döndürür veya ayarlar. |
| [getAlternativeTextTitle()](#getAlternativeTextTitle--) | Bir şekille ilişkili alternatif metnin başlığını döndürür veya ayarlar. |
| [setAlternativeTextTitle(String value)](#setAlternativeTextTitle-java.lang.String-) | Bir şekille ilişkili alternatif metnin başlığını döndürür veya ayarlar. |
| [getName()](#getName--) | Bir şeklin adını döndürür veya ayarlar. |
| [setName(String value)](#setName-java.lang.String-) | Bir şeklin adını döndürür veya ayarlar. |
| [isDecorative()](#isDecorative--) | 'Mark as decorative' seçeneğini alır veya ayarlar. Okunur/yazılır boolean. |
| [setDecorative(boolean value)](#setDecorative-boolean-) | 'Mark as decorative' seçeneğini alır veya ayarlar. Okunur/yazılır boolean. |
| [getShapeLock()](#getShapeLock--) | Şeklin kilitlerini döndürür. |
| [getUniqueId()](#getUniqueId--) | Eklentiler veya diğer kodlar tarafından kullanılmak üzere tasarlanmış dahili, sunum kapsamlı bir tanımlayıcıyı döndürür. |
| [getOfficeInteropShapeId()](#getOfficeInteropShapeId--) | Bir slayta özgü benzersiz tanımlayıcıyı döndürür; şeklin yaşam süresi boyunca sabit kalır ve PowerPoint ya da interop kodunun şekle her yerden güvenilir şekilde başvurmasını sağlar. |
| [isGrouped()](#isGrouped--) | Şeklin gruplanıp gruplanmadığını belirler. |
| [getBlackWhiteMode()](#getBlackWhiteMode--) | Özellik, bir şeklin siyah-beyaz görüntüleme modunda nasıl render edileceğini belirtir. |
| [setBlackWhiteMode(byte value)](#setBlackWhiteMode-byte-) | Özellik, bir şeklin siyah-beyaz görüntüleme modunda nasıl render edileceğini belirtir. |
| [getParentGroup()](#getParentGroup--) | Şekil gruplanmışsa üst GroupShape nesnesini döndürür. |
| [writeAsSvg(OutputStream stream)](#writeAsSvg-java.io.OutputStream-) | Şeklin içeriğini SVG dosyası olarak kaydeder. |
| [writeAsSvg(OutputStream stream, ISVGOptions svgOptions)](#writeAsSvg-java.io.OutputStream-com.aspose.slides.ISVGOptions-) | Şeklin içeriğini SVG dosyası olarak kaydeder. |
| [getBasePlaceholder()](#getBasePlaceholder--) | Temel bir yer tutucu şekli döndürür (şu anki şeklin devralındığı düzen ve/veya ana slayttan gelen şekil). |

### isTextHolder() {#isTextHolder--}
```
public abstract boolean isTextHolder()
```

Şeklin TextHolder olup olmadığını belirler. Yalnızca okunur boolean.

**Döndürür:**
boolean

### getPlaceholder() {#getPlaceholder--}
```
public abstract IPlaceholder getPlaceholder()
```

Bir şekil için yer tutucuyu döndürür. Yalnızca okunur [IPlaceholder](../../com.aspose.slides/iplaceholder).

**Döndürür:**
[IPlaceholder](../../com.aspose.slides/iplaceholder)

### addPlaceholder(IPlaceholder placeholderToCopyFrom) {#addPlaceholder-com.aspose.slides.IPlaceholder-}
```
public abstract IPlaceholder addPlaceholder(IPlaceholder placeholderToCopyFrom)
```

Yer tutucu yoksa yeni bir yer tutucu ekler ve yer tutucu özelliklerini belirtilen birine ayarlar.

**Parametreler:**
| Parametre | Tip | Açıklama |
| --- | --- | --- |
| placeholderToCopyFrom | [IPlaceholder](../../com.aspose.slides/iplaceholder) | İçeriği kopyalanacak yer tutucu. |

**Döndürür:**
[IPlaceholder](../../com.aspose.slides/iplaceholder) - Yeni [IPlaceholder](../../com.aspose.slides/iplaceholder).

### removePlaceholder() {#removePlaceholder--}
```
public abstract void removePlaceholder()
```

Bu şeklin yer tutucu olmadığını tanımlar.

### getCustomData() {#getCustomData--}
```
public abstract ICustomData getCustomData()
```

Şeklin özel verilerini döndürür. Yalnızca okunur [ICustomData](../../com.aspose.slides/icustomdata).

**Döndürür:**
[ICustomData](../../com.aspose.slides/icustomdata)

### getRawFrame() {#getRawFrame--}
```
public abstract IShapeFrame getRawFrame()
```

Ham şekil çerçevesinin özelliklerini döndürür veya ayarlar. Okunur/yazılır [IShapeFrame](../../com.aspose.slides/ishapeframe).

--------------------

> ```
> Code that attempts to assign undefined frame to IShape.getFrame() doesn't make sense in general case (particularly in case when parent GroupShape is multiple nested into other GroupShape-s). For example:
>  
>  IShape shape = ...;
>  shape.setFrame(new ShapeFrame(Float.NaN, Float.NaN, Float.NaN, Float.NaN, NullableBool.NotDefined, NullableBool.NotDefined, Float.NaN));
>  //veya
>  slide.getShapes().addAutoShape(ShapeType.RoundCornerRectangle, Float.NaN, Float.NaN, Float.NaN, Float.NaN);
>  //Bu kod belirsiz durumlara yol açabilir. Bu nedenle IShape.getFrame() için tanımsız değerlerin kullanımına kısıtlamalar eklenmiştir. x, y, width, height, flipH, flipV ve rotationAngle değerleri tanımlı olmalıdır (Float.NaN veya NullableBool.NotDefined olmamalıdır). Yukarıdaki örnek kod şimdi ArgumentException hatası fırlatır.
>  //Bu şu kullanım durumlarına uygulanır:
>  IShape shape = ...;
>  shape.setFrame(...); // tanımsız olamaz
>  IShapeCollection shapes = ...;
>  // x, y, width, height parametreleri Float.NaN olamaz:
>  {
>      shapes.addAudioFrameCD(...);
>      shapes.addAudioFrameEmbedded(...);
>      shapes.addAudioFrameLinked(...);
>      shapes.addAutoShape(...);
>      shapes.addChart(...);
>      shapes.addConnector(...);
>      shapes.addOleObjectFrame(...);
>      shapes.addPictureFrame(...);
>      shapes.addSmartArt(...);
>      shapes.addTable(...);
>      shapes.addVideoFrame(...);
>      shapes.insertAudioFrameEmbedded(...);
>      shapes.insertAudioFrameLinked(...);
>      shapes.insertAutoShape(...);
>      shapes.insertChart(...);
>      shapes.insertConnector(...);
>      shapes.insertOleObjectFrame(...);
>      shapes.insertPictureFrame(...);
>      shapes.insertTable(...);
>      shapes.insertVideoFrame(...);
>  }
>  But IShape.RawFrame frame properties can be undefined. This make sense when shape is linked to placeholder. Then undefined shape frame values is overridden from the parent placeholder shape. If there is no parent placeholder shape for that shape then that shape uses default values when it evaluates effective frame based on its IShape.RawFrame. Default values are 0 and NullableBool.False for x, y, width, height, flipH, flipV and rotationAngle. For example:
>  IShape shape = ...; // şekil placeholder'a bağlıdır
>  shape.setRawFrame(new ShapeFrame(Float.NaN, Float.NaN, 100, Float.NaN, NullableBool.NotDefined, NullableBool.NotDefined, 0)); // şimdi şekil x, y, height, flipH, flipV değerlerini placeholder'dan devralır ve width=100 ve rotationAngle=0 değerlerini geçersiz kılar.
```

**Döndürür:**
[IShapeFrame](../../com.aspose.slides/ishapeframe)

### setRawFrame(IShapeFrame value) {#setRawFrame-com.aspose.slides.IShapeFrame-}
```
public abstract void setRawFrame(IShapeFrame value)
```

Ham şekil çerçevesinin özelliklerini döndürür veya ayarlar. Okunur/yazılır [IShapeFrame](../../com.aspose.slides/ishapeframe).

--------------------

> ```
> Code that attempts to assign undefined frame to IShape.getFrame() doesn't make sense in general case (particularly in case when parent GroupShape is multiple nested into other GroupShape-s). For example:
>  
>  IShape shape = ...;
>  shape.setFrame(new ShapeFrame(Float.NaN, Float.NaN, Float.NaN, Float.NaN, NullableBool.NotDefined, NullableBool.NotDefined, Float.NaN));
>  //veya
>  slide.getShapes().addAutoShape(ShapeType.RoundCornerRectangle, Float.NaN, Float.NaN, Float.NaN, Float.NaN);
>  //Bu kod belirsiz durumlara yol açabilir. Bu nedenle IShape.getFrame() için tanımsız değerlerin kullanımına kısıtlamalar eklenmiştir. x, y, width, height, flipH, flipV ve rotationAngle değerleri tanımlı olmalıdır (not Float.NaN or NullableBool.NotDefined). Yukarıdaki örnek kod artık ArgumentException hatası fırlatır.
>  //Bu kullanım durumları için geçerlidir:
>  IShape shape = ...;
>  shape.setFrame(...); // tanımsız olamaz
>  IShapeCollection shapes = ...;
>  // x, y, width, height parametreleri Float.NaN olamaz:
>  {
>      shapes.addAudioFrameCD(...);
>      shapes.addAudioFrameEmbedded(...);
>      shapes.addAudioFrameLinked(...);
>      shapes.addAutoShape(...);
>      shapes.addChart(...);
>      shapes.addConnector(...);
>      shapes.addOleObjectFrame(...);
>      shapes.addPictureFrame(...);
>      shapes.addSmartArt(...);
>      shapes.addTable(...);
>      shapes.addVideoFrame(...);
>      shapes.insertAudioFrameEmbedded(...);
>      shapes.insertAudioFrameLinked(...);
>      shapes.insertAutoShape(...);
>      shapes.insertChart(...);
>      shapes.insertConnector(...);
>      shapes.insertOleObjectFrame(...);
>      shapes.insertPictureFrame(...);
>      shapes.insertTable(...);
>      shapes.insertVideoFrame(...);
>  }
>  But IShape.RawFrame frame properties can be undefined. This make sense when shape is linked to placeholder. Then undefined shape frame values is overridden from the parent placeholder shape. If there is no parent placeholder shape for that shape then that shape uses default values when it evaluates effective frame based on its IShape.RawFrame. Default values are 0 and NullableBool.False for x, y, width, height, flipH, flipV and rotationAngle. For example:
>  IShape shape = ...; // shape is linked to placeholder
>  shape.setRawFrame(new ShapeFrame(Float.NaN, Float.NaN, 100, Float.NaN, NullableBool.NotDefined, NullableBool.NotDefined, 0)); // şimdi şekil x, y, height, flipH, flipV değerlerini placeholder'dan devralır ve width=100 ve rotationAngle=0 değerlerini geçersiz kılar.
```

**Parametreler:**
| Parametre | Tip | Açıklama |
| --- | --- | --- |
| value | [IShapeFrame](../../com.aspose.slides/ishapeframe) |  |

### getFrame() {#getFrame--}
```
public abstract IShapeFrame getFrame()
```

Şekil çerçevesinin özelliklerini döndürür veya ayarlar. Okunur/yazılır [IShapeFrame](../../com.aspose.slides/ishapeframe).

--------------------

Returned value of each property of the returned IShapeFrame instance is not undefined (is not NaN or NotDefined). Value of each property of the assigned IShapeFrame instance must be not undefined (must be not NaN or NotDefined). You can set undefined values for RawFrame instance properties.

**Döndürür:**
[IShapeFrame](../../com.aspose.slides/ishapeframe)

### setFrame(IShapeFrame value) {#setFrame-com.aspose.slides.IShapeFrame-}
```
public abstract void setFrame(IShapeFrame value)
```

Şekil çerçevesinin özelliklerini döndürür veya ayarlar. Okunur/yazılır [IShapeFrame](../../com.aspose.slides/ishapeframe).

--------------------

Returned value of each property of the returned IShapeFrame instance is not undefined (is not NaN or NotDefined). Value of each property of the assigned IShapeFrame instance must be not undefined (must be not NaN or NotDefined). You can set undefined values for RawFrame instance properties.

**Parametreler:**
| Parametre | Tip | Açıklama |
| --- | --- | --- |
| value | [IShapeFrame](../../com.aspose.slides/ishapeframe) |  |

### getLineFormat() {#getLineFormat--}
```
public abstract ILineFormat getLineFormat()
```

Bir şeklin çizgi biçimlendirme özelliklerini içeren LineFormat nesnesini döndürür. Yalnızca okunur [ILineFormat](../../com.aspose.slides/ilineformat).

**Döndürür:**
[ILineFormat](../../com.aspose.slides/ilineformat)

### getThreeDFormat() {#getThreeDFormat--}
```
public abstract IThreeDFormat getThreeDFormat()
```

Bir şeklin çizgi biçimlendirme özelliklerini içeren ThreeDFormat nesnesini döndürür. Yalnızca okunur [IThreeDFormat](../../com.aspose.slides/ithreedformat).

**Döndürür:**
[IThreeDFormat](../../com.aspose.slides/ithreedformat)

### getEffectFormat() {#getEffectFormat--}
```
public abstract IEffectFormat getEffectFormat()
```

Bir şekle uygulanan piksel efektlerini içeren EffectFormat nesnesini döndürür. Yalnızca okunur [IEffectFormat](../../com.aspose.slides/ieffectformat).

**Döndürür:**
[IEffectFormat](../../com.aspose.slides/ieffectformat)

### getFillFormat() {#getFillFormat--}
```
public abstract IFillFormat getFillFormat()
```

Bir şeklin dolgu biçimlendirme özelliklerini içeren FillFormat nesnesini döndürür. Yalnızca okunur [IFillFormat](../../com.aspose.slides/ifillformat).

**Döndürür:**
[IFillFormat](../../com.aspose.slides/ifillformat)

### getImage() {#getImage--}
```
public abstract IImage getImage()
```

Şeklin küçük resmini döndürür. ShapeThumbnailBounds.Shape şekil küçük resmi sınırları türü varsayılan olarak kullanılır.

**Döndürür:**
[IImage](../../com.aspose.slides/iimage) - Şekil küçük resmi.

### getImage(int bounds, float scaleX, float scaleY) {#getImage-int-float-float-}
```
public abstract IImage getImage(int bounds, float scaleX, float scaleY)
```

Şeklin küçük resmini döndürür.

**Parametreler:**
| Parametre | Tip | Açıklama |
| --- | --- | --- |
| bounds | int | Şekil küçük resmi sınırları türü. |
| scaleX | float | X ölçeği |
| scaleY | float | Y ölçeği |

**Döndürür:**
[IImage](../../com.aspose.slides/iimage) - Şekil küçük resmi veya ShapeThumbnailBounds.Appearance kullanıldığında ve şeklin görünür öğeleri olmadığında null.

### getHidden() {#getHidden--}
```
public abstract boolean getHidden()
```

Şeklin gizli olup olmadığını belirler. Okunur/yazılır boolean.

**Döndürür:**
boolean

### setHidden(boolean value) {#setHidden-boolean-}
```
public abstract void setHidden(boolean value)
```

Şeklin gizli olup olmadığını belirler. Okunur/yazılır boolean.

**Parametreler:**
| Parametre | Tip | Açıklama |
| --- | --- | --- |
| value | boolean |  |

### getZOrderPosition() {#getZOrderPosition--}
```
public abstract int getZOrderPosition()
```

Bir şeklin z-sırasındaki konumunu döndürür. Shapes[0] z-sırasının arkasındaki şekli döndürür, Shapes[Shapes.Count - 1] ise önündeki şekli döndürür. Yalnızca okunur int.

**Döndürür:**
int

### getConnectionSiteCount() {#getConnectionSiteCount--}
```
public abstract int getConnectionSiteCount()
```

Şekildeki bağlantı noktalarının sayısını döndürür. Yalnızca okunur int.

**Döndürür:**
int

### getRotation() {#getRotation--}
```
public abstract float getRotation()
```

Belirtilen şeklin z ekseni etrafında döndürüldüğü derece sayısını döndürür veya ayarlar. Pozitif değer saat yönünde, negatif değer saat yönünün tersinde döndürülür. Okunur/yazılır float.

--------------------

Döndürülen değer daima tanımlıdır (Float.NaN değildir). Atanan değer tanımlı olmalıdır (Float.NaN olmamalıdır). RawFrame örneği özelliklerine undefined değerler atanabilir.

**Döndürür:**
float

### setRotation(float value) {#setRotation-float-}
```
public abstract void setRotation(float value)
```

Belirtilen şeklin z ekseni etrafında döndürüldüğü derece sayısını döndürür veya ayarlar. Pozitif değer saat yönünde, negatif değer saat yönünün tersinde döndürülür. Okunur/yazılır float.

--------------------

Döndürülen değer daima tanımlıdır (Float.NaN değildir). Atanan değer tanımlı olmalıdır (Float.NaN olmamalıdır). RawFrame örneği özelliklerine undefined değerler atanabilir.

**Parametreler:**
| Parametre | Tip | Açıklama |
| --- | --- | --- |
| value | float |  |

### getX() {#getX--}
```
public abstract float getX()
```

Şeklin sol üst köşesinin x koordinatını, puan cinsinden alır veya ayarlar. Okunur/yazılır float.

--------------------

Alınan değer daima tanımlıdır ve Float.NaN değildir. Atanan değer de tanımlı olmalıdır; sadece RawFrame örneği özelliklerine Float.NaN atanabilir.

**Döndürür:**
float

### setX(float value) {#setX-float-}
```
public abstract void setX(float value)
```

Şeklin sol üst köşesinin x koordinatını, puan cinsinden alır veya ayarlar. Okunur/yazılır float.

--------------------

Alınan değer daima tanımlıdır ve Float.NaN değildir. Atanan değer de tanımlı olmalıdır; sadece RawFrame örneği özelliklerine Float.NaN atanabilir.

**Parametreler:**
| Parametre | Tip | Açıklama |
| --- | --- | --- |
| value | float |  |

### getY() {#getY--}
```
public abstract float getY()
```

Şeklin sol üst köşesinin y koordinatını, puan cinsinden alır veya ayarlar. Okunur/yazılır float.

--------------------

Alınan değer daima tanımlıdır ve Float.NaN değildir. Atanan değer de tanımlı olmalıdır; sadece RawFrame örneği özelliklerine Float.NaN atanabilir.

**Döndürür:**
float

### setY(float value) {#setY-float-}
```
public abstract void setY(float value)
```

Şeklin sol üst köşesinin y koordinatını, puan cinsinden alır veya ayarlar. Okunur/yazılır float.

--------------------

Alınan değer daima tanımlıdır ve Float.NaN değildir. Atanan değer de tanımlı olmalıdır; sadece RawFrame örneği özelliklerine Float.NaN atanabilir.

**Parametreler:**
| Parametre | Tip | Açıklama |
| --- | --- | --- |
| value | float |  |

### getWidth() {#getWidth--}
```
public abstract float getWidth()
```

Şeklin genişliğini, puan cinsinden alır veya ayarlar. Okunur/yazılır float.

--------------------

Alınan değer daima tanımlıdır ve Float.NaN değildir. Atanan değer de tanımlı olmalıdır; sadece RawFrame örneği özelliklerine Float.NaN atanabilir.

**Döndürür:**
float

### setWidth(float value) {#setWidth-float-}
```
public abstract void setWidth(float value)
```

Şeklin genişliğini, puan cinsinden alır veya ayarlar. Okunur/yazılır float.

--------------------

Alınan değer daima tanımlıdır ve Float.NaN değildir. Atanan değer de tanımlı olmalıdır; sadece RawFrame örneği özelliklerine Float.NaN atanabilir.

**Parametreler:**
| Parametre | Tip | Açıklama |
| --- | --- | --- |
| value | float |  |

### getHeight() {#getHeight--}
```
public abstract float getHeight()
```

Şeklin yüksekliğini, puan cinsinden alır veya ayarlar. Okunur/yazılır float.

--------------------

Alınan değer daima tanımlıdır ve Float.NaN değildir. Atanan değer de tanımlı olmalıdır; sadece RawFrame örneği özelliklerine Float.NaN atanabilir.

**Döndürür:**
float

### setHeight(float value) {#setHeight-float-}
```
public abstract void setHeight(float value)
```

Şeklin yüksekliğini, puan cinsinden alır veya ayarlar. Okunur/yazılır float.

--------------------

Alınan değer daima tanımlıdır ve Float.NaN değildir. Atanan değer de tanımlı olmalıdır; sadece RawFrame örneği özelliklerine Float.NaN atanabilir.

**Parametreler:**
| Parametre | Tip | Açıklama |
| --- | --- | --- |
| value | float |  |

### getAlternativeText() {#getAlternativeText--}
```
public abstract String getAlternativeText()
```

Bir şekille ilişkili alternatif metni döndürür veya ayarlar. Okunur/yazılır String.

**Döndürür:**
java.lang.String

### setAlternativeText(String value) {#setAlternativeText-java.lang.String-}
```
public abstract void setAlternativeText(String value)
```

Bir şekille ilişkili alternatif metni döndürür veya ayarlar. Okunur/yazılır String.

**Parametreler:**
| Parametre | Tip | Açıklama |
| --- | --- | --- |
| value | java.lang.String |  |

### getAlternativeTextTitle() {#getAlternativeTextTitle--}
```
public abstract String getAlternativeTextTitle()
```

Bir şekille ilişkili alternatif metnin başlığını döndürür veya ayarlar. Okunur/yazılır String.

**Döndürür:**
java.lang.String

### setAlternativeTextTitle(String value) {#setAlternativeTextTitle-java.lang.String-}
```
public abstract void setAlternativeTextTitle(String value)
```

Bir şekille ilişkili alternatif metnin başlığını döndürür veya ayarlar. Okunur/yazılır String.

**Parametreler:**
| Parametre | Tip | Açıklama |
| --- | --- | --- |
| value | java.lang.String |  |

### getName() {#getName--}
```
public abstract String getName()
```

Bir şeklin adını döndürür veya ayarlar. Okunur/yazılır String.

**Döndürür:**
java.lang.String

### setName(String value) {#setName-java.lang.String-}
```
public abstract void setName(String value)
```

Bir şeklin adını döndürür veya ayarlar. Okunur/yazılır String.

**Parametreler:**
| Parametre | Tip | Açıklama |
| --- | --- | --- |
| value | java.lang.String |  |

### isDecorative() {#isDecorative--}
```
public abstract boolean isDecorative()
```

'Dekoratif olarak işaretle' seçeneğini alır veya ayarlar. Okunur/yazılır boolean.

--------------------

> ```
> Presentation pres = new Presentation("sample.pptx");
>  try {
>     pres.getSlides().get_Item(0).getShapes().get_Item(0).setDecorative(true);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Döndürür:**
boolean

### setDecorative(boolean value) {#setDecorative-boolean-}
```
public abstract void setDecorative(boolean value)
```

'Dekoratif olarak işaretle' seçeneğini alır veya ayarlar. Okunur/yazılır boolean.

--------------------

> ```
> Presentation pres = new Presentation("sample.pptx");
>  try {
>     pres.getSlides().get_Item(0).getShapes().get_Item(0).setDecorative(true);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Parametreler:**
| Parametre | Tip | Açıklama |
| --- | --- | --- |
| value | boolean |  |

### getShapeLock() {#getShapeLock--}
```
public abstract IBaseShapeLock getShapeLock()
```

Şeklin kilitlerini döndürür. Yalnızca okunur [IBaseShapeLock](../../com.aspose.slides/ibaseshapelock).

**Döndürür:**
[IBaseShapeLock](../../com.aspose.slides/ibaseshapelock)

### getUniqueId() {#getUniqueId--}
```
public abstract long getUniqueId()
```

Eklentiler veya diğer kodlar tarafından kullanılmak üzere tasarlanmış dahili, sunum kapsamlı bir tanımlayıcıyı döndürür. Bu değer kullanıcı tarafından yeniden atanabileceği veya programatik olarak değiştirilebileceği için kalıcı bir benzersiz anahtar olarak kullanılmamalıdır. Yalnızca okunur long. Ayrıntılar için \#getOfficeInteropShapeId.getOfficeInteropShapeId.

**Döndürür:**
long

### getOfficeInteropShapeId() {#getOfficeInteropShapeId--}
```
public abstract long getOfficeInteropShapeId()
```

Şeklin yaşam süresi boyunca sabit kalan ve PowerPoint ya da interop kodunun şekle her yerden güvenilir şekilde başvurmasını sağlayan slayt-kapsamlı benzersiz tanımlayıcıyı döndürür. Yalnızca okunur long. Ayrıntılar için \#getUniqueId.getUniqueId.

**Döndürür:**
long

### isGrouped() {#isGrouped--}
```
public abstract boolean isGrouped()
```

Şeklin gruplanıp gruplanmadığını belirler. Yalnızca okunur boolean.

--------------------

Özellik \#getParentGroup.getParentGroup, şekil gruplanmışsa üst GroupShape nesnesini döndürür.

**Döndürür:**
boolean

### getBlackWhiteMode() {#getBlackWhiteMode--}
```
public abstract byte getBlackWhiteMode()
```

Özellik, bir şeklin siyah-beyaz görüntüleme modunda nasıl render edileceğini belirtir. Okunur/yazılır [BlackWhiteMode](../../com.aspose.slides/blackwhitemode).

**Döndürür:**
byte

### setBlackWhiteMode(byte value) {#setBlackWhiteMode-byte-}
```
public abstract void setBlackWhiteMode(byte value)
```

Özellik, bir şeklin siyah-beyaz görüntüleme modunda nasıl render edileceğini belirtir. Okunur/yazılır [BlackWhiteMode](../../com.aspose.slides/blackwhitemode).

**Parametreler:**
| Parametre | Tip | Açıklama |
| --- | --- | --- |
| value | byte |  |

### getParentGroup() {#getParentGroup--}
```
public abstract IGroupShape getParentGroup()
```

Şekil gruplanmışsa üst GroupShape nesnesini döndürür. Aksi takdirde null döndürür. Yalnızca okunur [IGroupShape](../../com.aspose.slides/igroupshape).

--------------------

Özellik \#isGrouped.isGrouped, şeklin gruplanıp gruplanmadığını belirler.

**Döndürür:**
[IGroupShape](../../com.aspose.slides/igroupshape)

### writeAsSvg(OutputStream stream) {#writeAsSvg-java.io.OutputStream-}
```
public abstract void writeAsSvg(OutputStream stream)
```

Şeklin içeriğini SVG dosyası olarak kaydeder.

**Parametreler:**
| Parametre | Tip | Açıklama |
| --- | --- | --- |
| stream | java.io.OutputStream | Hedef akış |

### writeAsSvg(OutputStream stream, ISVGOptions svgOptions) {#writeAsSvg-java.io.OutputStream-com.aspose.slides.ISVGOptions-}
```
public abstract void writeAsSvg(OutputStream stream, ISVGOptions svgOptions)
```

Şeklin içeriğini SVG dosyası olarak kaydeder.

**Parametreler:**
| Parametre | Tip | Açıklama |
| --- | --- | --- |
| stream | java.io.OutputStream | Hedef akış |
| svgOptions | [ISVGOptions](../../com.aspose.slides/isvgoptions) | SVG oluşturma seçenekleri |

### getBasePlaceholder() {#getBasePlaceholder--}
```
public abstract IShape getBasePlaceholder()
```

Temel bir yer tutucu şekli döndürür (şu anki şeklin devralındığı düzen ve/veya ana slayttan gelen şekil).

--------------------

> ```
> // placeholder şeklinin (master/layout/slide) tüm animasyon etkilerini al
>  Presentation pres = new Presentation("sample.pptx");
>  try {
>      ISlide slide = pres.getSlides().get_Item(0);
>      IShape shape = slide.getShapes().get_Item(0);
>      IEffect[] shapeEffects = slide.getTimeline().getMainSequence().getEffectsByShape(shape);
>      IShape layoutShape = shape.getBasePlaceholder();
>      IEffect[] layoutShapeEffects = slide.getLayoutSlide().getTimeline().getMainSequence().getEffectsByShape(layoutShape);
>      IShape masterShape = layoutShape.getBasePlaceholder();
>      IEffect[] masterShapeEffects = slide.getLayoutSlide().getMasterSlide().getTimeline().getMainSequence().getEffectsByShape(masterShape);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


--------------------

Mevcut şekil devralınmamışsa null döndürülür.

**Döndürür:**
[IShape](../../com.aspose.slides/ishape)