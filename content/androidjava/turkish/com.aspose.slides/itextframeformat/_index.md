---
title: ITextFrameFormat
second_title: Aspose.Slides for Android via Java API Reference
description: TextFrame'lerin biçimlendirme özelliklerini içerir.
type: docs
url: /tr/com.aspose.slides/itextframeformat/
---```
public interface ITextFrameFormat
```

TextFrame'in biçimlendirme özelliklerini içerir.
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getTextStyle()](#getTextStyle--) | Metnin stilini döndürür. |
| [getMarginLeft()](#getMarginLeft--) | Bir TextFrame içinde sol kenar boşluğunu (nokta) döndürür veya ayarlar. |
| [setMarginLeft(double value)](#setMarginLeft-double-) | Bir TextFrame içinde sol kenar boşluğunu (nokta) döndürür veya ayarlar. |
| [getMarginRight()](#getMarginRight--) | Bir TextFrame içinde sağ kenar boşluğunu (nokta) döndürür veya ayarlar. |
| [setMarginRight(double value)](#setMarginRight-double-) | Bir TextFrame içinde sağ kenar boşluğunu (nokta) döndürür veya ayarlar. |
| [getMarginTop()](#getMarginTop--) | Bir TextFrame içinde üst kenar boşluğunu (nokta) döndürür veya ayarlar. |
| [setMarginTop(double value)](#setMarginTop-double-) | Bir TextFrame içinde üst kenar boşluğunu (nokta) döndürür veya ayarlar. |
| [getMarginBottom()](#getMarginBottom--) | Bir TextFrame içinde alt kenar boşluğunu (nokta) döndürür veya ayarlar. |
| [setMarginBottom(double value)](#setMarginBottom-double-) | Bir TextFrame içinde alt kenar boşluğunu (nokta) döndürür veya ayarlar. |
| [getWrapText()](#getWrapText--) | Metin TextFrame'in kenar boşluklarında sarılıyorsa True. |
| [setWrapText(byte value)](#setWrapText-byte-) | Metin TextFrame'in kenar boşluklarında sarılıyorsa True. |
| [getAnchoringType()](#getAnchoringType--) | Bir TextFrame içinde dikey bağlama metnini döndürür veya ayarlar. |
| [setAnchoringType(byte value)](#setAnchoringType-byte-) | Bir TextFrame içinde dikey bağlama metnini döndürür veya ayarlar. |
| [getCenterText()](#getCenterText--) | NullableBool.True ise metin yatay olarak kutuya ortalanmalıdır. |
| [setCenterText(byte value)](#setCenterText-byte-) | NullableBool.True ise metin yatay olarak kutuya ortalanmalıdır. |
| [getTextVerticalType()](#getTextVerticalType--) | Metin yönünü belirler. |
| [setTextVerticalType(byte value)](#setTextVerticalType-byte-) | Metin yönünü belirler. |
| [getAutofitType()](#getAutofitType--) | Metnin otomatik sığdırma modunu döndürür veya ayarlar. |
| [setAutofitType(byte value)](#setAutofitType-byte-) | Metnin otomatik sığdırma modunu döndürür veya ayarlar. |
| [getColumnCount()](#getColumnCount--) | Metin alanındaki sütun sayısını döndürür veya ayarlar. |
| [setColumnCount(int value)](#setColumnCount-int-) | Metin alanındaki sütun sayısını döndürür veya ayarlar. |
| [getColumnSpacing()](#getColumnSpacing--) | Metin alanındaki metin sütunları arasındaki boşluğu (nokta) döndürür veya ayarlar. |
| [setColumnSpacing(double value)](#setColumnSpacing-double-) | Metin alanındaki metin sütunları arasındaki boşluğu (nokta) döndürür veya ayarlar. |
| [getThreeDFormat()](#getThreeDFormat--) | Metin için 3D efekt özelliklerini temsil eden ThreeDFormat nesnesini döndürür. |
| [getKeepTextFlat()](#getKeepTextFlat--) | Metni tamamen 3D sahneden dışarıda tutmayı döndürür veya ayarlar. |
| [setKeepTextFlat(boolean value)](#setKeepTextFlat-boolean-) | Metni tamamen 3D sahneden dışarıda tutmayı döndürür veya ayarlar. |
| [getRotationAngle()](#getRotationAngle--) | Sınır kutusu içinde metne uygulanacak özel dönüşü belirtir. |
| [setRotationAngle(float value)](#setRotationAngle-float-) | Sınır kutusu içinde metne uygulanacak özel dönüşü belirtir. |
| [getTransform()](#getTransform--) | Metin sarma şeklini alır veya ayarlar. |
| [setTransform(byte value)](#setTransform-byte-) | Metin sarma şeklini alır veya ayarlar. |
| [getEffective()](#getEffective--) | Kalıtım uygulanmış etkili metin çerçevesi biçimlendirme verilerini alır. |

### getTextStyle() {#getTextStyle--}
```
public abstract ITextStyle getTextStyle()
```

Metnin stilini döndürür. Yalnızca okunabilir [ITextStyle](../../com.aspose.slides/itextstyle).

**Döndürür:**
[ITextStyle](../../com.aspose.slides/itextstyle)

### getMarginLeft() {#getMarginLeft--}
```
public abstract double getMarginLeft()
```

Bir TextFrame içinde sol kenar boşluğunu (nokta) döndürür veya ayarlar. Okunabilir/yazılabilir double.

**Döndürür:**
double

### setMarginLeft(double value) {#setMarginLeft-double-}
```
public abstract void setMarginLeft(double value)
```

Bir TextFrame içinde sol kenar boşluğunu (nokta) döndürür veya ayarlar. Okunabilir/yazılabilir double.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | double |  |

### getMarginRight() {#getMarginRight--}
```
public abstract double getMarginRight()
```

Bir TextFrame içinde sağ kenar boşluğunu (nokta) döndürür veya ayarlar. Okunabilir/yazılabilir double.

**Döndürür:**
double

### setMarginRight(double value) {#setMarginRight-double-}
```
public abstract void setMarginRight(double value)
```

Bir TextFrame içinde sağ kenar boşluğunu (nokta) döndürür veya ayarlar. Okunabilir/yazılabilir double.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | double |  |

### getMarginTop() {#getMarginTop--}
```
public abstract double getMarginTop()
```

Bir TextFrame içinde üst kenar boşluğunu (nokta) döndürür veya ayarlar. Okunabilir/yazılabilir double.

**Döndürür:**
double

### setMarginTop(double value) {#setMarginTop-double-}
```
public abstract void setMarginTop(double value)
```

Bir TextFrame içinde üst kenar boşluğunu (nokta) döndürür veya ayarlar. Okunabilir/yazılabilir double.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | double |  |

### getMarginBottom() {#getMarginBottom--}
```
public abstract double getMarginBottom()
```

Bir TextFrame içinde alt kenar boşluğunu (nokta) döndürür veya ayarlar. Okunabilir/yazılabilir double.

**Döndürür:**
double

### setMarginBottom(double value) {#setMarginBottom-double-}
```
public abstract void setMarginBottom(double value)
```

Bir TextFrame içinde alt kenar boşluğunu (nokta) döndürür veya ayarlar. Okunabilir/yazılabilir double.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | double |  |

### getWrapText() {#getWrapText--}
```
public abstract byte getWrapText()
```

Metin TextFrame'in kenar boşluklarında sarılıyorsa True. Okunabilir/yazılabilir [NullableBool](../../com.aspose.slides/nullablebool).

**Döndürür:**
byte

### setWrapText(byte value) {#setWrapText-byte-}
```
public abstract void setWrapText(byte value)
```

Metin TextFrame'in kenar boşluklarında sarılıyorsa True. Okunabilir/yazılabilir [NullableBool](../../com.aspose.slides/nullablebool).

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | byte |  |

### getAnchoringType() {#getAnchoringType--}
```
public abstract byte getAnchoringType()
```

Bir TextFrame içinde dikey bağlama metnini döndürür veya ayarlar. Okunabilir/yazılabilir [TextAnchorType](../../com.aspose.slides/textanchortype).

**Döndürür:**
byte

### setAnchoringType(byte value) {#setAnchoringType-byte-}
```
public abstract void setAnchoringType(byte value)
```

Bir TextFrame içinde dikey bağlama metnini döndürür veya ayarlar. Okunabilir/yazılabilir [TextAnchorType](../../com.aspose.slides/textanchortype).

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | byte |  |

### getCenterText() {#getCenterText--}
```
public abstract byte getCenterText()
```

NullableBool.True ise metin yatay olarak kutuya ortalanmalıdır. Okunabilir/yazılabilir [NullableBool](../../com.aspose.slides/nullablebool).

**Döndürür:**
byte

### setCenterText(byte value) {#setCenterText-byte-}
```
public abstract void setCenterText(byte value)
```

NullableBool.True ise metin yatay olarak kutuya ortalanmalıdır. Okunabilir/yazılabilir [NullableBool](../../com.aspose.slides/nullablebool).

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | byte |  |

### getTextVerticalType() {#getTextVerticalType--}
```
public abstract byte getTextVerticalType()
```

Metin yönünü belirler. Bu özelliğin ve RotationAngle özelliğindeki özel açının özetlenmiş görsel metin dönüşü değeri döndürülür. Okunabilir/yazılabilir [TextVerticalType](../../com.aspose.slides/textverticaltype).

**Döndürür:**
byte

### setTextVerticalType(byte value) {#setTextVerticalType-byte-}
```
public abstract void setTextVerticalType(byte value)
```

Metin yönünü belirler. Bu özelliğin ve RotationAngle özelliğindeki özel açının özetlenmiş görsel metin dönüşü değeri döndürülür. Okunabilir/yazılabilir [TextVerticalType](../../com.aspose.slides/textverticaltype).

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | byte |  |

### getAutofitType() {#getAutofitType--}
```
public abstract byte getAutofitType()
```

Metnin otomatik sığdırma modunu döndürür veya ayarlar. Okunabilir/yazılabilir [TextAutofitType](../../com.aspose.slides/textautofittype).

**Döndürür:**
byte

### setAutofitType(byte value) {#setAutofitType-byte-}
```
public abstract void setAutofitType(byte value)
```

Metnin otomatik sığdırma modunu döndürür veya ayarlar. Okunabilir/yazılabilir [TextAutofitType](../../com.aspose.slides/textautofittype).

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | byte |  |

### getColumnCount() {#getColumnCount--}
```
public abstract int getColumnCount()
```

Metin alanındaki sütun sayısını döndürür veya ayarlar. Bu değer pozitif bir sayı olmalıdır. Aksi takdirde değer sıfıra ayarlanır. 0 değeri tanımsız anlamına gelir. Okunabilir/yazılabilir int.

**Döndürür:**
int

### setColumnCount(int value) {#setColumnCount-int-}
```
public abstract void setColumnCount(int value)
```

Metin alanındaki sütun sayısını döndürür veya ayarlar. Bu değer pozitif bir sayı olmalıdır. Aksi takdirde değer sıfıra ayarlanır. 0 değeri tanımsız anlamına gelir. Okunabilir/yazılabilir int.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | int |  |

### getColumnSpacing() {#getColumnSpacing--}
```
public abstract double getColumnSpacing()
```

Metin alanındaki metin sütunları arasındaki boşluğu (nokta) döndürür veya ayarlar. Bu yalnızca 1'den fazla sütun olduğunda uygulanmalıdır. Bu değer pozitif bir sayı olmalıdır. Aksi takdirde değer sıfıra ayarlanır. Okunabilir/yazılabilir double.

**Döndürür:**
double

### setColumnSpacing(double value) {#setColumnSpacing-double-}
```
public abstract void setColumnSpacing(double value)
```

Metin alanındaki metin sütunları arasındaki boşluğu (nokta) döndürür veya ayarlar. Bu yalnızca 1'den fazla sütun olduğunda uygulanmalıdır. Bu değer pozitif bir sayı olmalıdır. Aksi takdirde değer sıfıra ayarlanır. Okunabilir/yazılabilir double.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | double |  |

### getThreeDFormat() {#getThreeDFormat--}
```
public abstract IThreeDFormat getThreeDFormat()
```

Metin için 3D efekt özelliklerini temsil eden ThreeDFormat nesnesini döndürür. Yalnızca okunabilir [IThreeDFormat](../../com.aspose.slides/ithreedformat).

--------------------

> ```
> Presentation pres = new Presentation();
>  try {
>      IAutoShape autoShape = pres.getSlides().get_Item(0).getShapes().addAutoShape(ShapeType.Rectangle, 10, 20, 400, 300);
>      ITextFrame textFrame = autoShape.getTextFrame();
>      textFrame.setText("Aspose.Slide Test Text");
>      // Metin dönüşümünü ayarla
>      textFrame.getTextFrameFormat().setTransform(TextShapeType.ArchUpPour);
>      // Ekstrüzyonu ayarla
>      textFrame.getTextFrameFormat().getThreeDFormat().getExtrusionColor().setColor(Color.ORANGE);
>      textFrame.getTextFrameFormat().getThreeDFormat().setExtrusionHeight(6);
>      // Konturu ayarla
>      textFrame.getTextFrameFormat().getThreeDFormat().getContourColor().setColor(Color.DARK_GRAY);
>      textFrame.getTextFrameFormat().getThreeDFormat().setContourWidth(1.5);
>      // Derinliği ayarla
>      textFrame.getTextFrameFormat().getThreeDFormat().setDepth(3);
>      // Malzemeyi ayarla
>      textFrame.getTextFrameFormat().getThreeDFormat().setMaterial(MaterialPresetType.Plastic);
>      // Aydınlatmayı ayarla
>      textFrame.getTextFrameFormat().getThreeDFormat().getLightRig().setDirection(LightingDirection.Top);
>      textFrame.getTextFrameFormat().getThreeDFormat().getLightRig().setLightType(LightRigPresetType.Balanced);
>      textFrame.getTextFrameFormat().getThreeDFormat().getLightRig().setRotation(0, 0, 40);
>      // Kamera tipini ayarla
>      textFrame.getTextFrameFormat().getThreeDFormat().getCamera().setCameraType(CameraPresetType.PerspectiveContrastingRightFacing);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Döndürür:**
[IThreeDFormat](../../com.aspose.slides/ithreedformat)

### getKeepTextFlat() {#getKeepTextFlat--}
```
public abstract boolean getKeepTextFlat()
```

Metni tamamen 3D sahneden dışarıda tutmayı döndürür veya ayarlar. Okunabilir/yazılabilir boolean.

**Döndürür:**
boolean

### setKeepTextFlat(boolean value) {#setKeepTextFlat-boolean-}
```
public abstract void setKeepTextFlat(boolean value)
```

Metni tamamen 3D sahneden dışarıda tutmayı döndürür veya ayarlar. Okunabilir/yazılabilir boolean.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | boolean |  |

### getRotationAngle() {#getRotationAngle--}
```
public abstract float getRotationAngle()
```

Sınır kutusu içinde metne uygulanacak özel dönüşü belirtir. Belirtilmezse, eşlik eden şeklin dönüşü kullanılır. Belirtilirse, şekilden bağımsız olarak uygulanır. Yani şekil, metnin kendisine ek bir dönüş uygulanarak dönebilir. Bu özelliğin ve TextVerticalType özelliğindeki önceden tanımlı dikey tipin özetlenmiş görsel metin dönüşü değeri döndürülür. Okunabilir/yazılabilir float.

--------------------

> ```
> Consider the case where a shape has a rotation of 90 degrees clockwise applied to it. 
>  In addition to this, the text body itself has a rotation of -90 degrees 
>  counter-clockwise applied to it. Then the resulting shape would appear to
>  be rotated but the text within it would appear as though it had not been rotated at all.
> ```

**Döndürür:**
float

### setRotationAngle(float value) {#setRotationAngle-float-}
```
public abstract void setRotationAngle(float value)
```

Sınır kutusu içinde metne uygulanacak özel dönüşü belirtir. Belirtilmezse, eşlik eden şeklin dönüşü kullanılır. Belirtilirse, şekilden bağımsız olarak uygulanır. Yani şekil, metnin kendisine ek bir dönüş uygulanarak dönebilir. Bu özelliğin ve TextVerticalType özelliğindeki önceden tanımlı dikey tipin özetlenmiş görsel metin dönüşü değeri döndürülür. Okunabilir/yazılabilir float.

--------------------

> ```
> Bir şekle saat yönünde 90 derece dönüş uygulanmış durumu düşünün. 
>  Buna ek olarak, metin gövdesi kendisi saat yönünün tersine -90 derece dönüş uygulanmıştır. 
>  Böylece ortaya çıkan şekil döndürülmüş gibi görünecek, ancak içindeki metin hiç döndürülmüş gibi görünmeyecek.
> ```

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | float |  |

### getTransform() {#getTransform--}
```
public abstract byte getTransform()
```

Metin sarma şeklini alır veya ayarlar. Okunabilir/yazılabilir [TextShapeType](../../com.aspose.slides/textshapetype).

**Döndürür:**
byte

### setTransform(byte value) {#setTransform-byte-}
```
public abstract void setTransform(byte value)
```

Metin sarma şeklini alır veya ayarlar. Okunabilir/yazılabilir [TextShapeType](../../com.aspose.slides/textshapetype).

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | byte |  |

### getEffective() {#getEffective--}
```
public abstract ITextFrameFormatEffectiveData getEffective()
```

Kalıtım uygulanmış etkili metin çerçevesi biçimlendirme verilerini alır.

**Döndürür:**
[ITextFrameFormatEffectiveData](../../com.aspose.slides/itextframeformateffectivedata) - A [ITextFrameFormatEffectiveData](../../com.aspose.slides/itextframeformateffectivedata).