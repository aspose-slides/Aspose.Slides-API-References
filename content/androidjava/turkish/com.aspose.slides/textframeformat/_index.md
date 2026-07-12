---
title: TextFrameFormat
second_title: Aspose.Slides için Android üzerinden Java API Referansı
description: TextFrames'in formatTextFrameFormatting özelliklerini içerir.
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
| [TextFrameFormat()](#TextFrameFormat--) | Yeni bir [TextFrameFormat](../../com.aspose.slides/textframeformat) sınıfının örneğini başlatır. |
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getVersion()](#getVersion--) |  |
| [getTextStyle()](#getTextStyle--) | Metnin stilini döndürür. |
| [getThreeDFormat()](#getThreeDFormat--) | Metin için 3D efekt özelliklerini temsil eden ThreeDFormat nesnesini döndürür. |
| [getMarginLeft()](#getMarginLeft--) | TextFrame içinde sol kenar boşluğunu (nokta) döndürür veya ayarlar. |
| [setMarginLeft(double value)](#setMarginLeft-double-) | TextFrame içinde sol kenar boşluğunu (nokta) döndürür veya ayarlar. |
| [getMarginRight()](#getMarginRight--) | TextFrame içinde sağ kenar boşluğunu (nokta) döndürür veya ayarlar. |
| [setMarginRight(double value)](#setMarginRight-double-) | TextFrame içinde sağ kenar boşluğunu (nokta) döndürür veya ayarlar. |
| [getMarginTop()](#getMarginTop--) | TextFrame içinde üst kenar boşluğunu (nokta) döndürür veya ayarlar. |
| [setMarginTop(double value)](#setMarginTop-double-) | TextFrame içinde üst kenar boşluğunu (nokta) döndürür veya ayarlar. |
| [getMarginBottom()](#getMarginBottom--) | TextFrame içinde alt kenar boşluğunu (nokta) döndürür veya ayarlar. |
| [setMarginBottom(double value)](#setMarginBottom-double-) | TextFrame içinde alt kenar boşluğunu (nokta) döndürür veya ayarlar. |
| [getWrapText()](#getWrapText--) | Metin, TextFrame kenar boşluklarında sarılıysa doğrudur. |
| [setWrapText(byte value)](#setWrapText-byte-) | Metin, TextFrame kenar boşluklarında sarılıysa doğrudur. |
| [getAnchoringType()](#getAnchoringType--) | TextFrame içinde dikey çapa metni döndürür veya ayarlar. |
| [setAnchoringType(byte value)](#setAnchoringType-byte-) | TextFrame içinde dikey çapa metni döndürür veya ayarlar. |
| [getCenterText()](#getCenterText--) | NullableBool.True ise metin yatay olarak kutuya ortalanmalıdır. |
| [setCenterText(byte value)](#setCenterText-byte-) | NullableBool.True ise metin yatay olarak kutuya ortalanmalıdır. |
| [getTextVerticalType()](#getTextVerticalType--) | Metin yönünü belirler. |
| [setTextVerticalType(byte value)](#setTextVerticalType-byte-) | Metin yönünü belirler. |
| [getAutofitType()](#getAutofitType--) | Metnin otomatik sığdırma kipini döndürür veya ayarlar. |
| [setAutofitType(byte value)](#setAutofitType-byte-) | Metnin otomatik sığdırma kipini döndürür veya ayarlar. |
| [getColumnCount()](#getColumnCount--) | Metin alanındaki sütun sayısını döndürür veya ayarlar. |
| [setColumnCount(int value)](#setColumnCount-int-) | Metin alanındaki sütun sayısını döndürür veya ayarlar. |
| [getColumnSpacing()](#getColumnSpacing--) | Metin alanındaki sütunlar arasındaki boşluğu (nokta) döndürür veya ayarlar. |
| [setColumnSpacing(double value)](#setColumnSpacing-double-) | Metin alanındaki sütunlar arasındaki boşluğu (nokta) döndürür veya ayarlar. |
| [getRotationAngle()](#getRotationAngle--) | Sınırlayıcı kutu içinde metne uygulanacak özel dönüşü belirler. |
| [setRotationAngle(float value)](#setRotationAngle-float-) | Sınırlayıcı kutu içinde metne uygulanacak özel dönüşü belirler. |
| [getTransform()](#getTransform--) | Metin sarma şekli alır veya ayarlar. |
| [setTransform(byte value)](#setTransform-byte-) | Metin sarma şekli alır veya ayarlar. |
| [getKeepTextFlat()](#getKeepTextFlat--) | 3-D Döndürme etkisi uygulanmış olsa bile metni düz tutmayı alır veya ayarlar. |
| [setKeepTextFlat(boolean value)](#setKeepTextFlat-boolean-) | 3-D Döndürme etkisi uygulanmış olsa bile metni düz tutmayı alır veya ayarlar. |
| [getEffective()](#getEffective--) | Kalıtım uygulanmış etkili metin çerçevesi biçimlendirme verilerini alır. |
### TextFrameFormat() {#TextFrameFormat--}
```
public TextFrameFormat()
```


Yeni bir [TextFrameFormat](../../com.aspose.slides/textframeformat) sınıfının örneğini başlatır.

### getVersion() {#getVersion--}
```
public long getVersion()
```


Versiyon. Yalnızca okunur long.

**Döndürür:**
long
### getTextStyle() {#getTextStyle--}
```
public final ITextStyle getTextStyle()
```


Metnin stilini döndürür. Yalnızca okunur [ITextStyle](../../com.aspose.slides/itextstyle).

**Döndürür:**
[ITextStyle](../../com.aspose.slides/itextstyle)
### getThreeDFormat() {#getThreeDFormat--}
```
public final IThreeDFormat getThreeDFormat()
```


Metin için 3D efekt özelliklerini temsil eden ThreeDFormat nesnesini döndürür. Yalnızca okunur [IThreeDFormat](../../com.aspose.slides/ithreedformat).

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
### getMarginLeft() {#getMarginLeft--}
```
public final double getMarginLeft()
```


TextFrame içinde sol kenar boşluğunu (nokta) döndürür veya ayarlar. Okunur/yazılır double.

**Döndürür:**
double
### setMarginLeft(double value) {#setMarginLeft-double-}
```
public final void setMarginLeft(double value)
```


TextFrame içinde sol kenar boşluğunu (nokta) döndürür veya ayarlar. Okunur/yazılır double.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | double |  |

### getMarginRight() {#getMarginRight--}
```
public final double getMarginRight()
```


TextFrame içinde sağ kenar boşluğunu (nokta) döndürür veya ayarlar. Okunur/yazılır double.

**Döndürür:**
double
### setMarginRight(double value) {#setMarginRight-double-}
```
public final void setMarginRight(double value)
```


TextFrame içinde sağ kenar boşluğunu (nokta) döndürür veya ayarlar. Okunur/yazılır double.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | double |  |

### getMarginTop() {#getMarginTop--}
```
public final double getMarginTop()
```


TextFrame içinde üst kenar boşluğunu (nokta) döndürür veya ayarlar. Okunur/yazılır double.

**Döndürür:**
double
### setMarginTop(double value) {#setMarginTop-double-}
```
public final void setMarginTop(double value)
```


TextFrame içinde üst kenar boşluğunu (nokta) döndürür veya ayarlar. Okunur/yazılır double.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | double |  |

### getMarginBottom() {#getMarginBottom--}
```
public final double getMarginBottom()
```


TextFrame içinde alt kenar boşluğunu (nokta) döndürür veya ayarlar. Okunur/yazılır double.

**Döndürür:**
double
### setMarginBottom(double value) {#setMarginBottom-double-}
```
public final void setMarginBottom(double value)
```


TextFrame içinde alt kenar boşluğunu (nokta) döndürür veya ayarlar. Okunur/yazılır double.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | double |  |

### getWrapText() {#getWrapText--}
```
public final byte getWrapText()
```


Metin, TextFrame kenar boşluklarında sarılıysa doğrudur. Okunur/yazılır [NullableBool](../../com.aspose.slides/nullablebool).

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


Metin, TextFrame kenar boşluklarında sarılıysa doğrudur. Okunur/yazılır [NullableBool](../../com.aspose.slides/nullablebool).

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


TextFrame içinde dikey çapa metni döndürür veya ayarlar. Okunur/yazılır [TextAnchorType](../../com.aspose.slides/textanchortype).

**Döndürür:**
byte
### setAnchoringType(byte value) {#setAnchoringType-byte-}
```
public final void setAnchoringType(byte value)
```


TextFrame içinde dikey çapa metni döndürür veya ayarlar. Okunur/yazılır [TextAnchorType](../../com.aspose.slides/textanchortype).

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | byte |  |

### getCenterText() {#getCenterText--}
```
public final byte getCenterText()
```


NullableBool.True ise metin yatay olarak kutuya ortalanmalıdır. Okunur/yazılır [NullableBool](../../com.aspose.slides/nullablebool).

**Döndürür:**
byte
### setCenterText(byte value) {#setCenterText-byte-}
```
public final void setCenterText(byte value)
```


NullableBool.True ise metin yatay olarak kutuya ortalanmalıdır. Okunur/yazılır [NullableBool](../../com.aspose.slides/nullablebool).

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | byte |  |

### getTextVerticalType() {#getTextVerticalType--}
```
public final byte getTextVerticalType()
```


Metin yönünü belirler. Görsel metin döndürmesinin bu özelliktan ve RotationAngle özelliğindeki özel açıdan özetlenen sonucu. Okunur/yazılır [TextVerticalType](../../com.aspose.slides/textverticaltype).

**Döndürür:**
byte
### setTextVerticalType(byte value) {#setTextVerticalType-byte-}
```
public final void setTextVerticalType(byte value)
```


Metin yönünü belirler. Görsel metin döndürmesinin bu özelliktan ve RotationAngle özelliğindeki özel açıdan özetlenen sonucu. Okunur/yazılır [TextVerticalType](../../com.aspose.slides/textverticaltype).

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | byte |  |

### getAutofitType() {#getAutofitType--}
```
public final byte getAutofitType()
```


Metnin otomatik sığdırma kipini döndürür veya ayarlar. Okunur/yazılır [TextAutofitType](../../com.aspose.slides/textautofittype).

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


Metnin otomatik sığdırma kipini döndürür veya ayarlar. Okunur/yazılır [TextAutofitType](../../com.aspose.slides/textautofittype).

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


Metin alanındaki sütun sayısını döndürür veya ayarlar. Bu değer pozitif bir sayı olmalıdır. Aksi takdirde değer sıfıra ayarlanır. Değer 0 tanımsız anlamına gelir. Okunur/yazılır int.

--------------------

> ```
> Aşağıdaki örnek kod, bir PowerPoint Sunumu içinde Metin çerçevesine sütun eklemenin nasıl yapılacağını gösterir.
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


Metin alanındaki sütun sayısını döndürür veya ayarlar. Bu değer pozitif bir sayı olmalıdır. Aksi takdirde değer sıfıra ayarlanır. Değer 0 tanımsız anlamına gelir. Okunur/yazılır int.

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


Metin alanındaki sütunlar arasındaki boşluğu (nokta) döndürür veya ayarlar. Bu yalnızca birden fazla sütun mevcut olduğunda uygulanmalıdır. Bu değer pozitif bir sayı olmalıdır. Aksi takdirde değer sıfıra ayarlanır. Okunur/yazılır double.

**Döndürür:**
double
### setColumnSpacing(double value) {#setColumnSpacing-double-}
```
public final void setColumnSpacing(double value)
```


Metin alanındaki sütunlar arasındaki boşluğu (nokta) döndürür veya ayarlar. Bu yalnızca birden fazla sütun mevcut olduğunda uygulanmalıdır. Bu değer pozitif bir sayı olmalıdır. Aksi takdirde değer sıfıra ayarlanır. Okunur/yazılır double.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | double |  |

### getRotationAngle() {#getRotationAngle--}
```
public final float getRotationAngle()
```


Sınırlayıcı kutu içinde metne uygulanacak özel dönüşü belirler. Belirtilmezse, ilişkilendirilen şeklin dönüşü kullanılır. Belirtilirse, bu dönüş şekilden bağımsız olarak uygulanır. Yani şeklin bir dönüşü olabilir ve aynı zamanda metnin de ayrı bir dönüşü uygulanabilir. Görsel metin döndürmesinin bu özelliktan ve TextVerticalType özelliğindeki ön tanımlı dikey türden özetlenen sonucu. Okunur/yazılır float.

--------------------

> ```
> Bir şekle saat yönünde 90 derece döndürme uygulanmış durumunu düşünün. 
>  Buna ek olarak, metin gövdesi de saat yönünün tersine -90 derece döndürülmüştür. 
>  Sonuçta ortaya çıkan şekil şöyle görünecek 
>  dönmüş gibi, ancak içindeki metin hiç dönmüş gibi görünmeyecek.
```

**Döndürür:**
float
### setRotationAngle(float value) {#setRotationAngle-float-}
```
public final void setRotationAngle(float value)
```


Sınırlayıcı kutu içinde metne uygulanacak özel dönüşü belirler. Belirtilmezse, ilişkilendirilen şeklin dönüşü kullanılır. Belirtilirse, bu dönüş şekilden bağımsız olarak uygulanır. Yani şeklin bir dönüşü olabilir ve aynı zamanda metnin de ayrı bir dönüşü uygulanabilir. Görsel metin döndürmesinin bu özelliktan ve TextVerticalType özelliğindeki ön tanımlı dikey türden özetlenen sonucu. Okunur/yazılır float.

--------------------

> ```
> Bir şekle saat yönünde 90 derece döndürme uygulanmış durumu düşünün. 
>  Bunun yanı sıra, metin gövdesi de -90 derece 
>  saat yönünün tersine uygulanmıştır. Sonra ortaya çıkan şekil şöyle görünecektir
>  döndürülmüş ama içindeki metin hiç döndürülmemiş gibi görünecektir.
```

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | float |  |

### getTransform() {#getTransform--}
```
public final byte getTransform()
```


Metin sarma şekli alır veya ayarlar. Okunur/yazılır [TextShapeType](../../com.aspose.slides/textshapetype).

**Döndürür:**
byte
### setTransform(byte value) {#setTransform-byte-}
```
public final void setTransform(byte value)
```


Metin sarma şekli alır veya ayarlar. Okunur/yazılır [TextShapeType](../../com.aspose.slides/textshapetype).

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | byte |  |

### getKeepTextFlat() {#getKeepTextFlat--}
```
public final boolean getKeepTextFlat()
```


3-D Döndürme etkisi uygulanmış olsa bile metni düz tutmayı alır veya ayarlar. Okunur/yazılır boolean.

**Döndürür:**
boolean
### setKeepTextFlat(boolean value) {#setKeepTextFlat-boolean-}
```
public final void setKeepTextFlat(boolean value)
```


3-D Döndürme etkisi uygulanmış olsa bile metni düz tutmayı alır veya ayarlar. Okunur/yazılır boolean.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | boolean |  |

### getEffective() {#getEffective--}
```
public final ITextFrameFormatEffectiveData getEffective()
```


Kalıtım uygulanmış etkili metin çerçevesi biçimlendirme verilerini alır.

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