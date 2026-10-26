---
title: ITextFrameFormat
second_title: Aspose.Slides for Java API Reference
description: TextFrame'lerin biçimlendirme özelliklerini içerir.
type: docs
url: /tr/com.aspose.slides/itextframeformat/
---```
public interface ITextFrameFormat
```

TextFrame'in biçimlendirme özelliklerini içerir.
## Metotlar

| Metot | Açıklama |
| --- | --- |
| [getTextStyle()](#getTextStyle--) | Metnin stilini döndürür. |
| [getMarginLeft()](#getMarginLeft--) | Bir TextFrame içinde sol kenar boşluğunu (puan) döndürür veya ayarlar. |
| [setMarginLeft(double value)](#setMarginLeft-double-) | Bir TextFrame içinde sol kenar boşluğunu (puan) döndürür veya ayarlar. |
| [getMarginRight()](#getMarginRight--) | Bir TextFrame içinde sağ kenar boşluğunu (puan) döndürür veya ayarlar. |
| [setMarginRight(double value)](#setMarginRight-double-) | Bir TextFrame içinde sağ kenar boşluğunu (puan) döndürür veya ayarlar. |
| [getMarginTop()](#getMarginTop--) | Bir TextFrame içinde üst kenar boşluğunu (puan) döndürür veya ayarlar. |
| [setMarginTop(double value)](#setMarginTop-double-) | Bir TextFrame içinde üst kenar boşluğunu (puan) döndürür veya ayarlar. |
| [getMarginBottom()](#getMarginBottom--) | Bir TextFrame içinde alt kenar boşluğunu (puan) döndürür veya ayarlar. |
| [setMarginBottom(double value)](#setMarginBottom-double-) | Bir TextFrame içinde alt kenar boşluğunu (puan) döndürür veya ayarlar. |
| [getWrapText()](#getWrapText--) | Metin TextFrame kenar boşluklarında sarılıyorsa doğru döndürür. |
| [setWrapText(byte value)](#setWrapText-byte-) | Metin TextFrame kenar boşluklarında sarılıyorsa doğru döndürür. |
| [getAnchoringType()](#getAnchoringType--) | Bir TextFrame içinde dikey sabitleme metnini döndürür veya ayarlar. |
| [setAnchoringType(byte value)](#setAnchoringType-byte-) | Bir TextFrame içinde dikey sabitleme metnini döndürür veya ayarlar. |
| [getCenterText()](#getCenterText--) | NullableBool.True ise metin yatay olarak kutuya ortalanmalıdır. |
| [setCenterText(byte value)](#setCenterText-byte-) | NullableBool.True ise metin yatay olarak kutuya ortalanmalıdır. |
| [getTextVerticalType()](#getTextVerticalType--) | Metin yönünü belirler. |
| [setTextVerticalType(byte value)](#setTextVerticalType-byte-) | Metin yönünü belirler. |
| [getAutofitType()](#getAutofitType--) | Metnin otomatik sığdırma modunu döndürür veya ayarlar. |
| [setAutofitType(byte value)](#setAutofitType-byte-) | Metnin otomatik sığdırma modunu döndürür veya ayarlar. |
| [getColumnCount()](#getColumnCount--) | Metin alanındaki sütun sayısını döndürür veya ayarlar. |
| [setColumnCount(int value)](#setColumnCount-int-) | Metin alanındaki sütun sayısını döndürür veya ayarlar. |
| [getColumnSpacing()](#getColumnSpacing--) | Metin alanındaki metin sütunları arasındaki boşluğu (puan olarak) döndürür veya ayarlar. |
| [setColumnSpacing(double value)](#setColumnSpacing-double-) | Metin alanındaki metin sütunları arasındaki boşluğu (puan olarak) döndürür veya ayarlar. |
| [getThreeDFormat()](#getThreeDFormat--) | Bir metin için 3D efekt özelliklerini temsil eden ThreeDFormat nesnesini döndürür. |
| [getKeepTextFlat()](#getKeepTextFlat--) | Metni tamamen 3D sahneden dışarıda tutmayı döndürür veya ayarlar. |
| [setKeepTextFlat(boolean value)](#setKeepTextFlat-boolean-) | Metni tamamen 3D sahneden dışarıda tutmayı döndürür veya ayarlar. |
| [getRotationAngle()](#getRotationAngle--) | Sınırlayıcı kutu içinde metne uygulanan özel dönüşü belirler. |
| [setRotationAngle(float value)](#setRotationAngle-float-) | Sınırlayıcı kutu içinde metne uygulanan özel dönüşü belirler. |
| [getTransform()](#getTransform--) | Metin sarma şeklini alır veya ayarlar. |
| [setTransform(byte value)](#setTransform-byte-) | Metin sarma şeklini alır veya ayarlar. |
| [getEffective()](#getEffective--) | Kalıtım uygulanan etkili metin çerçevesi biçimlendirme verilerini alır. |
### getTextStyle() {#getTextStyle--}
```
public abstract ITextStyle getTextStyle()
```

Metnin stilini döndürür. Salt-okunur [ITextStyle](../../com.aspose.slides/itextstyle).

**Döndürür:**
[ITextStyle](../../com.aspose.slides/itextstyle)
### getMarginLeft() {#getMarginLeft--}
```
public abstract double getMarginLeft()
```

Bir TextFrame içinde sol kenar boşluğunu (puan) döndürür veya ayarlar. Okunur/yazılabilir double.

**Döndürür:**
double
### setMarginLeft(double value) {#setMarginLeft-double-}
```
public abstract void setMarginLeft(double value)
```

Bir TextFrame içinde sol kenar boşluğunu (puan) döndürür veya ayarlar. Okunur/yazılabilir double.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | double |  |
### getMarginRight() {#getMarginRight--}
```
public abstract double getMarginRight()
```

Bir TextFrame içinde sağ kenar boşluğunu (puan) döndürür veya ayarlar. Okunur/yazılabilir double.

**Döndürür:**
double
### setMarginRight(double value) {#setMarginRight-double-}
```
public abstract void setMarginRight(double value)
```

Bir TextFrame içinde sağ kenar boşluğunu (puan) döndürür veya ayarlar. Okunur/yazılabilir double.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | double |  |
### getMarginTop() {#getMarginTop--}
```
public abstract double getMarginTop()
```

Bir TextFrame içinde üst kenar boşluğunu (puan) döndürür veya ayarlar. Okunur/yazılabilir double.

**Döndürür:**
double
### setMarginTop(double value) {#setMarginTop-double-}
```
public abstract void setMarginTop(double value)
```

Bir TextFrame içinde üst kenar boşluğunu (puan) döndürür veya ayarlar. Okunur/yazılabilir double.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | double |  |
### getMarginBottom() {#getMarginBottom--}
```
public abstract double getMarginBottom()
```

Bir TextFrame içinde alt kenar boşluğunu (puan) döndürür veya ayarlar. Okunur/yazılabilir double.

**Döndürür:**
double
### setMarginBottom(double value) {#setMarginBottom-double-}
```
public abstract void setMarginBottom(double value)
```

Bir TextFrame içinde alt kenar boşluğunu (puan) döndürür veya ayarlar. Okunur/yazılabilir double.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | double |  |
### getWrapText() {#getWrapText--}
```
public abstract byte getWrapText()
```

Metin TextFrame kenar boşluklarında sarılıyorsa doğru döndürür. Okunur/yazılabilir [NullableBool](../../com.aspose.slides/nullablebool).

**Döndürür:**
byte
### setWrapText(byte value) {#setWrapText-byte-}
```
public abstract void setWrapText(byte value)
```

Metin TextFrame kenar boşluklarında sarılıyorsa doğru döndürür. Okunur/yazılabilir [NullableBool](../../com.aspose.slides/nullablebool).

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | byte |  |
### getAnchoringType() {#getAnchoringType--}
```
public abstract byte getAnchoringType()
```

Bir TextFrame içinde dikey sabitleme metnini döndürür veya ayarlar. Okunur/yazılabilir [TextAnchorType](../../com.aspose.slides/textanchortype).

**Döndürür:**
byte
### setAnchoringType(byte value) {#setAnchoringType-byte-}
```
public abstract void setAnchoringType(byte value)
```

Bir TextFrame içinde dikey sabitleme metnini döndürür veya ayarlar. Okunur/yazılabilir [TextAnchorType](../../com.aspose.slides/textanchortype).

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | byte |  |
### getCenterText() {#getCenterText--}
```
public abstract byte getCenterText()
```

NullableBool.True ise metin yatay olarak kutuya ortalanmalıdır. Okunur/yazılabilir [NullableBool](../../com.aspose.slides/nullablebool).

**Döndürür:**
byte
### setCenterText(byte value) {#setCenterText-byte-}
```
public abstract void setCenterText(byte value)
```

NullableBool.True ise metin yatay olarak kutuya ortalanmalıdır. Okunur/yazılabilir [NullableBool](../../com.aspose.slides/nullablebool).

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | byte |  |
### getTextVerticalType() {#getTextVerticalType--}
```
public abstract byte getTextVerticalType()
```

Metin yönünü belirler. Bu özelliğin ve RotationAngle özelliğindeki özel açının özetlenmiş görsel metin dönüş değeridir. Okunur/yazılabilir [TextVerticalType](../../com.aspose.slides/textverticaltype).

**Döndürür:**
byte
### setTextVerticalType(byte value) {#setTextVerticalType-byte-}
```
public abstract void setTextVerticalType(byte value)
```

Metin yönünü belirler. Bu özelliğin ve RotationAngle özelliğindeki özel açının özetlenmiş görsel metin dönüş değeridir. Okunur/yazılabilir [TextVerticalType](../../com.aspose.slides/textverticaltype).

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | byte |  |
### getAutofitType() {#getAutofitType--}
```
public abstract byte getAutofitType()
```

Metnin otomatik sığdırma modunu döndürür veya ayarlar. Okunur/yazılabilir [TextAutofitType](../../com.aspose.slides/textautofittype).

**Döndürür:**
byte
### setAutofitType(byte value) {#setAutofitType-byte-}
```
public abstract void setAutofitType(byte value)
```

Metnin otomatik sığdırma modunu döndürür veya ayarlar. Okunur/yazılabilir [TextAutofitType](../../com.aspose.slides/textautofittype).

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | byte |  |
### getColumnCount() {#getColumnCount--}
```
public abstract int getColumnCount()
```

Metin alanındaki sütun sayısını döndürür veya ayarlar. Bu değer pozitif bir sayı olmalıdır. Aksi takdirde değer sıfıra ayarlanır. Değer 0 tanımsız değeri gösterir. Okunur/yazılabilir int.

**Döndürür:**
int
### setColumnCount(int value) {#setColumnCount-int-}
```
public abstract void setColumnCount(int value)
```

Metin alanındaki sütun sayısını döndürür veya ayarlar. Bu değer pozitif bir sayı olmalıdır. Aksi takdirde değer sıfıra ayarlanır. Değer 0 tanımsız değeri gösterir. Okunur/yazılabilir int.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | int |  |
### getColumnSpacing() {#getColumnSpacing--}
```
public abstract double getColumnSpacing()
```

Metin alanındaki metin sütunları arasındaki boşluğu (puan olarak) döndürür veya ayarlar. Bu sadece birden fazla sütun olduğunda uygulanmalıdır. Bu değer pozitif bir sayı olmalıdır. Aksi takdirde değer sıfıra ayarlanır. Okunur/yazılabilir double.

**Döndürür:**
double
### setColumnSpacing(double value) {#setColumnSpacing-double-}
```
public abstract void setColumnSpacing(double value)
```

Metin alanındaki metin sütunları arasındaki boşluğu (puan olarak) döndürür veya ayarlar. Bu sadece birden fazla sütun olduğunda uygulanmalıdır. Bu değer pozitif bir sayı olmalıdır. Aksi takdirde değer sıfıra ayarlanır. Okunur/yazılabilir double.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | double |  |
### getThreeDFormat() {#getThreeDFormat--}
```
public abstract IThreeDFormat getThreeDFormat()
```

Bir metin için 3D efekt özelliklerini temsil eden ThreeDFormat nesnesini döndürür. Salt-okunur [IThreeDFormat](../../com.aspose.slides/ithreedformat).

--------------------

> ```
> Presentation pres = new Presentation();
>  try {
>      IAutoShape autoShape = pres.getSlides().get_Item(0).getShapes().addAutoShape(ShapeType.Rectangle, 10, 20, 400, 300);
>      ITextFrame textFrame = autoShape.getTextFrame();
>      textFrame.setText("Aspose.Slide Test Text");
>      // Set text transformation
>      textFrame.getTextFrameFormat().setTransform(TextShapeType.ArchUpPour);
>      // Set Extrusion
>      textFrame.getTextFrameFormat().getThreeDFormat().getExtrusionColor().setColor(Color.ORANGE);
>      textFrame.getTextFrameFormat().getThreeDFormat().setExtrusionHeight(6);
>      // Set Contour
>      textFrame.getTextFrameFormat().getThreeDFormat().getContourColor().setColor(Color.DARK_GRAY);
>      textFrame.getTextFrameFormat().getThreeDFormat().setContourWidth(1.5);
>      // Set Depth
>      textFrame.getTextFrameFormat().getThreeDFormat().setDepth(3);
>      // Set Material
>      textFrame.getTextFrameFormat().getThreeDFormat().setMaterial(MaterialPresetType.Plastic);
>      // Set Lighting
>      textFrame.getTextFrameFormat().getThreeDFormat().getLightRig().setDirection(LightingDirection.Top);
>      textFrame.getTextFrameFormat().getThreeDFormat().getLightRig().setLightType(LightRigPresetType.Balanced);
>      textFrame.getTextFrameFormat().getThreeDFormat().getLightRig().setRotation(0, 0, 40);
>      // Set camera type
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

Metni tamamen 3D sahneden dışarıda tutmayı döndürür veya ayarlar. Okunur/yazılabilir boolean.

**Döndürür:**
boolean
### setKeepTextFlat(boolean value) {#setKeepTextFlat-boolean-}
```
public abstract void setKeepTextFlat(boolean value)
```

Metni tamamen 3D sahneden dışarıda tutmayı döndürür veya ayarlar. Okunur/yazılabilir boolean.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | boolean |  |
### getRotationAngle() {#getRotationAngle--}
```
public abstract float getRotationAngle()
```

Sınırlayıcı kutu içinde metne uygulanan özel dönüşü belirler. Belirtilmezse eşlik eden şeklin dönüşü kullanılır. Belirtilirse şekilden bağımsız olarak uygulanır. Yani şekil, metnin kendisine ayrı bir dönüş uygulandığında aynı anda bir dönüşe sahip olabilir. Bu özelliğin ve TextVerticalType özelliğindeki önceden tanımlı dikey tipin özetlenmiş görsel metin dönüş değeridir. Okunur/yazılabilir float.

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

Sınırlayıcı kutu içinde metne uygulanan özel dönüşü belirler. Belirtilmezse eşlik eden şeklin dönüşü kullanılır. Belirtilirse şekilden bağımsız olarak uygulanır. Yani şekil, metnin kendisine ayrı bir dönüş uygulandığında aynı anda bir dönüşe sahip olabilir. Bu özelliğin ve TextVerticalType özelliğindeki önceden tanımlı dikey tipin özetlenmiş görsel metin dönüş değeridir. Okunur/yazılabilir float.

--------------------

> ```
> Consider the case where a shape has a rotation of 90 degrees clockwise applied to it. 
>  In addition to this, the text body itself has a rotation of -90 degrees 
>  counter-clockwise applied to it. Then the resulting shape would appear to
>  be rotated but the text within it would appear as though it had not been rotated at all.
> ```


**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | float |  |
### getTransform() {#getTransform--}
```
public abstract byte getTransform()
```

Metin sarma şeklini alır veya ayarlar. Okunur/yazılabilir [TextShapeType](../../com.aspose.slides/textshapetype).

**Döndürür:**
byte
### setTransform(byte value) {#setTransform-byte-}
```
public abstract void setTransform(byte value)
```

Metin sarma şeklini alır veya ayarlar. Okunur/yazılabilir [TextShapeType](../../com.aspose.slides/textshapetype).

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