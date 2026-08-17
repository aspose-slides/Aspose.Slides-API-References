---
title: TextFrameFormat
second_title: Aspose.Slides for Java API Referansı
description: TextFrames formatTextFrameFormatting özelliklerini içerir.
type: docs
url: /tr/com.aspose.slides/textframeformat/
---
**Kalıtım:**
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject)

**Tüm Uygulanan Arabirimler:**
[com.aspose.slides.ITextFrameFormat](../../com.aspose.slides/itextframeformat), [com.aspose.slides.IChartTextBlockFormat](../../com.aspose.slides/icharttextblockformat)
```
public final class TextFrameFormat extends PVIObject implements ITextFrameFormat, IChartTextBlockFormat
```

TextFrame'in formatTextFrameFormatting özelliklerini içerir.
## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [TextFrameFormat()](#TextFrameFormat--) | Yeni bir [TextFrameFormat](../../com.aspose.slides/textframeformat) sınıfı örneği başlatır. |
## Metodlar

| Metod | Açıklama |
| --- | --- |
| [getVersion()](#getVersion--) |  |
| [getTextStyle()](#getTextStyle--) | Metnin stilini döndürür. |
| [getThreeDFormat()](#getThreeDFormat--) | Metin için 3d efekt özelliklerini temsil eden ThreeDFormat nesnesini döndürür. |
| [getMarginLeft()](#getMarginLeft--) | TextFrame içindeki sol kenar boşluğunu (puan) döndürür veya ayarlar. |
| [setMarginLeft(double value)](#setMarginLeft-double-) | TextFrame içindeki sol kenar boşluğunu (puan) döndürür veya ayarlar. |
| [getMarginRight()](#getMarginRight--) | TextFrame içindeki sağ kenar boşluğunu (puan) döndürür veya ayarlar. |
| [setMarginRight(double value)](#setMarginRight-double-) | TextFrame içindeki sağ kenar boşluğunu (puan) döndürür veya ayarlar. |
| [getMarginTop()](#getMarginTop--) | TextFrame içindeki üst kenar boşluğunu (puan) döndürür veya ayarlar. |
| [setMarginTop(double value)](#setMarginTop-double-) | TextFrame içindeki üst kenar boşluğunu (puan) döndürür veya ayarlar. |
| [getMarginBottom()](#getMarginBottom--) | TextFrame içindeki alt kenar boşluğunu (puan) döndürür veya ayarlar. |
| [setMarginBottom(double value)](#setMarginBottom-double-) | TextFrame içindeki alt kenar boşluğunu (puan) döndürür veya ayarlar. |
| [getWrapText()](#getWrapText--) | Metin, TextFrame kenar boşluklarında sarılıyorsa True döner. |
| [setWrapText(byte value)](#setWrapText-byte-) | Metin, TextFrame kenar boşluklarında sarılıyorsa True döner. |
| [getAnchoringType()](#getAnchoringType--) | TextFrame içinde dikey çapa metnini döndürür veya ayarlar. |
| [setAnchoringType(byte value)](#setAnchoringType-byte-) | TextFrame içinde dikey çapa metnini döndürür veya ayarlar. |
| [getCenterText()](#getCenterText--) | NullableBool.True ise metin yatay olarak kutuda ortalanmalıdır. |
| [setCenterText(byte value)](#setCenterText-byte-) | NullableBool.True ise metin yatay olarak kutuda ortalanmalıdır. |
| [getTextVerticalType()](#getTextVerticalType--) | Metin yönelimini belirler. |
| [setTextVerticalType(byte value)](#setTextVerticalType-byte-) | Metin yönelimini belirler. |
| [getAutofitType()](#getAutofitType--) | Metnin otomatik sığdırma modunu döndürür veya ayarlar. |
| [setAutofitType(byte value)](#setAutofitType-byte-) | Metnin otomatik sığdırma modunu döndürür veya ayarlar. |
| [getColumnCount()](#getColumnCount--) | Metin alanındaki sütun sayısını döndürür veya ayarlar. |
| [setColumnCount(int value)](#setColumnCount-int-) | Metin alanındaki sütun sayısını döndürür veya ayarlar. |
| [getColumnSpacing()](#getColumnSpacing--) | Metin alanındaki sütunlar arasındaki boşluğu (puan) döndürür veya ayarlar. |
| [setColumnSpacing(double value)](#setColumnSpacing-double-) | Metin alanındaki sütunlar arasındaki boşluğu (puan) döndürür veya ayarlar. |
| [getRotationAngle()](#getRotationAngle--) | Metnin sınırlayıcı kutu içinde uygulanacak özelleştirilmiş dönüşünü belirtir. |
| [setRotationAngle(float value)](#setRotationAngle-float-) | Metnin sınırlayıcı kutu içinde uygulanacak özelleştirilmiş dönüşünü belirtir. |
| [getTransform()](#getTransform--) | Metin sarma şekilini alır veya ayarlar. |
| [setTransform(byte value)](#setTransform-byte-) | Metin sarma şekilini alır veya ayarlar. |
| [getKeepTextFlat()](#getKeepTextFlat--) | 3-D Dönüş etkisi uygulanmış olsa bile metni düz tutmayı alır veya ayarlar. |
| [setKeepTextFlat(boolean value)](#setKeepTextFlat-boolean-) | 3-D Dönüş etkisi uygulanmış olsa bile metni düz tutmayı alır veya ayarlar. |
| [getEffective()](#getEffective--) | Kalıtım uygulanmış etkili metin çerçeve biçimlendirme verilerini alır. |
### TextFrameFormat() {#TextFrameFormat--}
```
public TextFrameFormat()
```

Yeni bir [TextFrameFormat](../../com.aspose.slides/textframeformat) sınıfı örneği başlatır.

### getVersion() {#getVersion--}
```
public long getVersion()
```

Versiyon. Salt okunur long.

**Döndürür:**
long
### getTextStyle() {#getTextStyle--}
```
public final ITextStyle getTextStyle()
```

Metnin stilini döndürür. Salt okunur [ITextStyle](../../com.aspose.slides/itextstyle).

**Döndürür:**
[ITextStyle](../../com.aspose.slides/itextstyle)
### getThreeDFormat() {#getThreeDFormat--}
```
public final IThreeDFormat getThreeDFormat()
```

Metin için 3d efekt özelliklerini temsil eden ThreeDFormat nesnesini döndürür. Salt okunur [IThreeDFormat](../../com.aspose.slides/ithreedformat).

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
>      // Kamera türünü ayarla
>      textFrame.getTextFrameFormat().getThreeDFormat().getCamera().setCameraType(CameraPresetType.PerspectiveContrastingRightFacing);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Döndürür:**
[IThreeDFormat](../../com.aspose.slides/ithreedformat)
### getMarginLeft() {#getMarginLeft--}
```
public final double getMarginLeft()
```

TextFrame içindeki sol kenar boşluğunu (puan) döndürür veya ayarlar. Okunur/yazılabilir double.

**Döndürür:**
double
### setMarginLeft(double value) {#setMarginLeft-double-}
```
public final void setMarginLeft(double value)
```

TextFrame içindeki sol kenar boşluğunu (puan) döndürür veya ayarlar. Okunur/yazılabilir double.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | double |  |

### getMarginRight() {#getMarginRight--}
```
public final double getMarginRight()
```

TextFrame içindeki sağ kenar boşluğunu (puan) döndürür veya ayarlar. Okunur/yazılabilir double.

**Döndürür:**
double
### setMarginRight(double value) {#setMarginRight-double-}
```
public final void setMarginRight(double value)
```

TextFrame içindeki sağ kenar boşluğunu (puan) döndürür veya ayarlar. Okunur/yazılabilir double.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | double |  |

### getMarginTop() {#getMarginTop--}
```
public final double getMarginTop()
```

TextFrame içindeki üst kenar boşluğunu (puan) döndürür veya ayarlar. Okunur/yazılabilir double.

**Döndürür:**
double
### setMarginTop(double value) {#setMarginTop-double-}
```
public final void setMarginTop(double value)
```

TextFrame içindeki üst kenar boşluğunu (puan) döndürür veya ayarlar. Okunur/yazılabilir double.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | double |  |

### getMarginBottom() {#getMarginBottom--}
```
public final double getMarginBottom()
```

TextFrame içindeki alt kenar boşluğunu (puan) döndürür veya ayarlar. Okunur/yazılabilir double.

**Döndürür:**
double
### setMarginBottom(double value) {#setMarginBottom-double-}
```
public final void setMarginBottom(double value)
```

TextFrame içindeki alt kenar boşluğunu (puan) döndürür veya ayarlar. Okunur/yazılabilir double.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | double |  |

### getWrapText() {#getWrapText--}
```
public final byte getWrapText()
```

Metin, TextFrame kenar boşluklarında sarılıyorsa True döner. Okunur/yazılabilir [NullableBool](../../com.aspose.slides/nullablebool).

--------------------

> ```
> The following sample code shows how to wrap text in Presentation.
>  
>  Presentation pres = new Presentation();
>  try {
>      ISlide slide = pres.getSlides().get_Item(0);
>      IAutoShape autoShape = slide.getShapes().addAutoShape(ShapeType.Rectangle, 30, 30, 350, 100);
>      Portion portion = new Portion("lorem ipsum...");
>      portion.getPortionFormat().getFillFormat().getSolidFillColor().setColor(Color.BLACK);
>      portion.getPortionFormat().getFillFormat().setFillType(FillType.Solid);
>      autoShape.getTextFrame().getParagraphs().get_Item(0).getPortions().add(portion);
>      ITextFrameFormat textFrameFormat = autoShape.getTextFrame().getTextFrameFormat();
>      textFrameFormat.setWrapText(NullableBool.True);
>      pres.save("Output-presentation.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Döndürür:**
byte
### setWrapText(byte value) {#setWrapText-byte-}
```
public final void setWrapText(byte value)
```

Metin, TextFrame kenar boşluklarında sarılıyorsa True döner. Okunur/yazılabilir [NullableBool](../../com.aspose.slides/nullablebool).

--------------------

> ```
> The following sample code shows how to wrap text in Presentation.
>  
>  Presentation pres = new Presentation();
>  try {
>      ISlide slide = pres.getSlides().get_Item(0);
>      IAutoShape autoShape = slide.getShapes().addAutoShape(ShapeType.Rectangle, 30, 30, 350, 100);
>      Portion portion = new Portion("lorem ipsum...");
>      portion.getPortionFormat().getFillFormat().getSolidFillColor().setColor(Color.BLACK);
>      portion.getPortionFormat().getFillFormat().setFillType(FillType.Solid);
>      autoShape.getTextFrame().getParagraphs().get_Item(0).getPortions().add(portion);
>      ITextFrameFormat textFrameFormat = autoShape.getTextFrame().getTextFrameFormat();
>      textFrameFormat.setWrapText(NullableBool.True);
>      pres.save("Output-presentation.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | byte |  |

### getAnchoringType() {#getAnchoringType--}
```
public final byte getAnchoringType()
```

TextFrame içinde dikey çapa metnini döndürür veya ayarlar. Okunur/yazılabilir [TextAnchorType](../../com.aspose.slides/textanchortype).

**Döndürür:**
byte
### setAnchoringType(byte value) {#setAnchoringType-byte-}
```
public final void setAnchoringType(byte value)
```

TextFrame içinde dikey çapa metnini döndürür veya ayarlar. Okunur/yazılabilir [TextAnchorType](../../com.aspose.slides/textanchortype).

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | byte |  |

### getCenterText() {#getCenterText--}
```
public final byte getCenterText()
```

NullableBool.True ise metin yatay olarak kutuda ortalanmalıdır. Okunur/yazılabilir [NullableBool](../../com.aspose.slides/nullablebool).

**Döndürür:**
byte
### setCenterText(byte value) {#setCenterText-byte-}
```
public final void setCenterText(byte value)
```

NullableBool.True ise metin yatay olarak kutuda ortalanmalıdır. Okunur/yazılabilir [NullableBool](../../com.aspose.slides/nullablebool).

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | byte |  |

### getTextVerticalType() {#getTextVerticalType--}
```
public final byte getTextVerticalType()
```

Metin yönelimini belirler. Bu özelliğin ve RotationAngle özelliğindeki özel açının özetlenmiş görsel metin döndürme değerini oluşturur. Okunur/yazılabilir [TextVerticalType](../../com.aspose.slides/textverticaltype).

**Döndürür:**
byte
### setTextVerticalType(byte value) {#setTextVerticalType-byte-}
```
public final void setTextVerticalType(byte value)
```

Metin yönelimini belirler. Bu özelliğin ve RotationAngle özelliğindeki özel açının özetlenmiş görsel metin döndürme değerini oluşturur. Okunur/yazılabilir [TextVerticalType](../../com.aspose.slides/textverticaltype).

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | byte |  |

### getAutofitType() {#getAutofitType--}
```
public final byte getAutofitType()
```

Metnin otomatik sığdırma modunu döndürür veya ayarlar. Okunur/yazılabilir [TextAutofitType](../../com.aspose.slides/textautofittype).

--------------------

> ```
> The following sample code shows how to resize shape to Fit Text in a PowerPoint Presentation.
>  
>  Presentation pres = new Presentation();
>  try {
>      ISlide slide = pres.getSlides().get_Item(0);
>      IAutoShape autoShape = slide.getShapes().addAutoShape(ShapeType.Rectangle, 30, 30, 350, 100);
>      Portion portion = new Portion("lorem ipsum...");
>      portion.getPortionFormat().getFillFormat().getSolidFillColor().setColor(Color.BLACK);
>      portion.getPortionFormat().getFillFormat().setFillType(FillType.Solid);
>      autoShape.getTextFrame().getParagraphs().get_Item(0).getPortions().add(portion);
>      ITextFrameFormat textFrameFormat = autoShape.getTextFrame().getTextFrameFormat();
>      textFrameFormat.setAutofitType(TextAutofitType.Shape);
>      pres.save("Output-presentation.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
>  
>  The following sample code shows how to shrink text on overflow.
>  
>  Presentation pres = new Presentation();
>  try {
>      ISlide slide = pres.getSlides().get_Item(0);
>      IAutoShape autoShape = slide.getShapes().addAutoShape(ShapeType.Rectangle, 30, 30, 350, 100);
>      Portion portion = new Portion("lorem ipsum...");
>      portion.getPortionFormat().getFillFormat().getSolidFillColor().setColor(Color.BLACK);
>      portion.getPortionFormat().getFillFormat().setFillType(FillType.Solid);
>      autoShape.getTextFrame().getParagraphs().get_Item(0).getPortions().add(portion);
>      ITextFrameFormat textFrameFormat = autoShape.getTextFrame().getTextFrameFormat();
>      textFrameFormat.setAutofitType(TextAutofitType.Normal);
>      pres.save("Output-presentation.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Döndürür:**
byte
### setAutofitType(byte value) {#setAutofitType-byte-}
```
public final void setAutofitType(byte value)
```

Metnin otomatik sığdırma modunu döndürür veya ayarlar. Okunur/yazılabilir [TextAutofitType](../../com.aspose.slides/textautofittype).

--------------------

> ```
> The following sample code shows how to resize shape to Fit Text in a PowerPoint Presentation.
>  
>  Presentation pres = new Presentation();
>  try {
>      ISlide slide = pres.getSlides().get_Item(0);
>      IAutoShape autoShape = slide.getShapes().addAutoShape(ShapeType.Rectangle, 30, 30, 350, 100);
>      Portion portion = new Portion("lorem ipsum...");
>      portion.getPortionFormat().getFillFormat().getSolidFillColor().setColor(Color.BLACK);
>      portion.getPortionFormat().getFillFormat().setFillType(FillType.Solid);
>      autoShape.getTextFrame().getParagraphs().get_Item(0).getPortions().add(portion);
>      ITextFrameFormat textFrameFormat = autoShape.getTextFrame().getTextFrameFormat();
>      textFrameFormat.setAutofitType(TextAutofitType.Shape);
>      pres.save("Output-presentation.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
>  
>  The following sample code shows how to shrink text on overflow.
>  
>  Presentation pres = new Presentation();
>  try {
>      ISlide slide = pres.getSlides().get_Item(0);
>      IAutoShape autoShape = slide.getShapes().addAutoShape(ShapeType.Rectangle, 30, 30, 350, 100);
>      Portion portion = new Portion("lorem ipsum...");
>      portion.getPortionFormat().getFillFormat().getSolidFillColor().setColor(Color.BLACK);
>      portion.getPortionFormat().getFillFormat().setFillType(FillType.Solid);
>      autoShape.getTextFrame().getParagraphs().get_Item(0).getPortions().add(portion);
>      ITextFrameFormat textFrameFormat = autoShape.getTextFrame().getTextFrameFormat();
>      textFrameFormat.setAutofitType(TextAutofitType.Normal);
>      pres.save("Output-presentation.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | byte |  |

### getColumnCount() {#getColumnCount--}
```
public final int getColumnCount()
```

Metin alanındaki sütun sayısını döndürür veya ayarlar. Bu değer pozitif bir sayı olmalıdır. Aksi takdirde değer sıfıra ayarlanır. Değer 0 tanımsız anlamına gelir. Okunur/yazılabilir int.

--------------------

> ```
> The following sample code shows how to add column in Text frame inside a PowerPoint Presentation.
>  
>  Presentation pres = new Presentation();
>  try {
>      IAutoShape shape1 = pres.getSlides().get_Item(0).getShapes().addAutoShape(ShapeType.Rectangle, 100, 100, 300, 300);
>      TextFrameFormat format = (TextFrameFormat)shape1.getTextFrame().getTextFrameFormat();
>      format.setColumnCount(2);
>      format.setColumnSpacing(20);
>      shape1.getTextFrame().setText("All these columns are forced to stay within a single text container -- " +
>      "you can add or delete text - and the new or remaining text automatically adjusts " +
>      "itself to stay within the container. You cannot have text spill over from one container " +
>      "to other, though -- because PowerPoint's column options for text are limited!");
>      pres.save("Columns_output.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Döndürür:**
int
### setColumnCount(int value) {#setColumnCount-int-}
```
public final void setColumnCount(int value)
```

Metin alanındaki sütun sayısını döndürür veya ayarlar. Bu değer pozitif bir sayı olmalıdır. Aksi takdirde değer sıfıra ayarlanır. Değer 0 tanımsız anlamına gelir. Okunur/yazılabilir int.

--------------------

> ```
> The following sample code shows how to add column in Text frame inside a PowerPoint Presentation.
>  
>  Presentation pres = new Presentation();
>  try {
>      IAutoShape shape1 = pres.getSlides().get_Item(0).getShapes().addAutoShape(ShapeType.Rectangle, 100, 100, 300, 300);
>      TextFrameFormat format = (TextFrameFormat)shape1.getTextFrame().getTextFrameFormat();
>      format.setColumnCount(2);
>      format.setColumnSpacing(20);
>      shape1.getTextFrame().setText("All these columns are forced to stay within a single text container -- " +
>      "you can add or delete text - and the new or remaining text automatically adjusts " +
>      "itself to stay within the container. You cannot have text spill over from one container " +
>      "to other, though -- because PowerPoint's column options for text are limited!");
>      pres.save("Columns_output.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | int |  |

### getColumnSpacing() {#getColumnSpacing--}
```
public final double getColumnSpacing()
```

Metin alanındaki sütunlar arasındaki boşluğu (puan) döndürür veya ayarlar. Bu yalnızca birden fazla sütun mevcut olduğunda uygulanmalıdır. Bu değer pozitif bir sayı olmalıdır. Aksi takdirde değer sıfıra ayarlanır. Okunur/yazılabilir double.

**Döndürür:**
double
### setColumnSpacing(double value) {#setColumnSpacing-double-}
```
public final void setColumnSpacing(double value)
```

Metin alanındaki sütunlar arasındaki boşluğu (puan) döndürür veya ayarlar. Bu yalnızca birden fazla sütun mevcut olduğunda uygulanmalıdır. Bu değer pozitif bir sayı olmalıdır. Aksi takdirde değer sıfıra ayarlanır. Okunur/yazılabilir double.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | double |  |

### getRotationAngle() {#getRotationAngle--}
```
public final float getRotationAngle()
```

Metnin sınırlayıcı kutu içinde uygulanacak özelleştirilmiş dönüşünü belirtir. Belirtilmemişse, ilişkili şeklin dönüşü kullanılır. Belirtilmişse, bu dönüş şekilden bağımsız olarak uygulanır. Yani şekil, metnin kendisinin de bir dönüşe sahip olmasının yanı sıra ek bir dönüşe sahip olabilir. Bu özelliğin ve TextVerticalType özelliğindeki önceden tanımlı dikey türün özetlenmiş görsel metin döndürme değerini oluşturur. Okunur/yazılabilir float.

--------------------

> ```
> Bir şeklin saat yönünde 90 derece döndürülmüş olduğu durumu düşünün. 
>  Buna ek olarak, metin gövdesi kendisi -90 derece saat yönünün tersine döndürülmüş 
>  saat yönünün tersine uygulanmıştır. Sonuçta elde edilen şekil şöyle görünür 
>  döndürülmüş ancak içindeki metin hiç döndürülmemiş gibi görünür.
```

**Döndürür:**
float
### setRotationAngle(float value) {#setRotationAngle-float-}
```
public final void setRotationAngle(float value)
```

Metnin sınırlayıcı kutu içinde uygulanacak özelleştirilmiş dönüşünü belirtir. Belirtilmemişse, ilişkili şeklin dönüşü kullanılır. Belirtilmişse, bu dönüş şekilden bağımsız olarak uygulanır. Yani şekil, metnin kendisinin de bir dönüşe sahip olmasının yanı sıra ek bir dönüşe sahip olabilir. Bu özelliğin ve TextVerticalType özelliğindeki önceden tanımlı dikey türün özetlenmiş görsel metin döndürme değerini oluşturur. Okunur/yazılabilir float.

--------------------

> ```
> Bir şeklin saat yönünde 90 derece döndürülmüş olduğu durumu düşünün. 
>  Buna ek olarak, metin gövdesi kendisi -90 derece saat yönünün tersine 
>  uygulanmıştır. Sonuçta elde edilen şekil şöyle görünecektir 
>  döndürülmüş ancak içindeki metin hiç döndürülmemiş gibi görünecektir.
```

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | float |  |

### getTransform() {#getTransform--}
```
public final byte getTransform()
```

Metin sarma şekilini alır veya ayarlar. Okunur/yazılabilir [TextShapeType](../../com.aspose.slides/textshapetype).

**Döndürür:**
byte
### setTransform(byte value) {#setTransform-byte-}
```
public final void setTransform(byte value)
```

Metin sarma şekilini alır veya ayarlar. Okunur/yazılabilir [TextShapeType](../../com.aspose.slides/textshapetype).

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | byte |  |

### getKeepTextFlat() {#getKeepTextFlat--}
```
public final boolean getKeepTextFlat()
```

3-D Dönüş etkisi uygulanmış olsa bile metni düz tutmayı alır veya ayarlar. Okunur/yazılabilir boolean.

**Döndürür:**
boolean
### setKeepTextFlat(boolean value) {#setKeepTextFlat-boolean-}
```
public final void setKeepTextFlat(boolean value)
```

3-D Dönüş etkisi uygulanmış olsa bile metni düz tutmayı alır veya ayarlar. Okunur/yazılabilir boolean.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | boolean |  |

### getEffective() {#getEffective--}
```
public final ITextFrameFormatEffectiveData getEffective()
```

Kalıtım uygulanmış etkili metin çerçeve biçimlendirme verilerini alır.

--------------------

> ```
> This example demonstrates getting some of effective text frame formatting properties.
>  
>  Presentation pres = new Presentation("MyPresentation.pptx");
>  try
>  {
>      IAutoShape shape = (IAutoShape)pres.getSlides().get_Item(0).getShapes().get_Item(0);
>      ITextFrameFormatEffectiveData effectiveTextFrameFormat = shape.getTextFrame().getTextFrameFormat().getEffective();
>     
>      System.out.println("Anchoring type: " + effectiveTextFrameFormat.getAnchoringType());
>      System.out.println("Autofit type: " + effectiveTextFrameFormat.getAutofitType());
>      System.out.println("Text vertical type: " + effectiveTextFrameFormat.getTextVerticalType());
>      System.out.println("Margins");
>      System.out.println("   Left: " + effectiveTextFrameFormat.getMarginLeft());
>      System.out.println("   Top: " + effectiveTextFrameFormat.getMarginTop());
>      System.out.println("   Right: " + effectiveTextFrameFormat.getMarginRight());
>      System.out.println("   Bottom: " + effectiveTextFrameFormat.getMarginBottom());
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Döndürür:**
[ITextFrameFormatEffectiveData](../../com.aspose.slides/itextframeformateffectivedata) - A [ITextFrameFormatEffectiveData](../../com.aspose.slides/itextframeformateffectivedata).