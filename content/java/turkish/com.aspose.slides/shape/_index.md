---
title: Shape
second_title: Aspose.Slides için Java API Referansı
description: Bir slayttaki şekli temsil eder.
type: docs
url: /tr/com.aspose.slides/shape/
---
**Kalıtım:**  
java.lang.Object

**Tüm Uygulanan Arayüzler:**  
[com.aspose.slides.IShape](../../com.aspose.slides/ishape), com.aspose.slides.IDOMObject  
```
public class Shape implements IShape, IDOMObject
```

Bir slayttaki şekli temsil eder.
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [isTextHolder()](#isTextHolder--) | Şeklin TextHolder_PPT olup olmadığını belirler. |
| [getPlaceholder()](#getPlaceholder--) | Bir şekil için yer tutucuyu döndürür. |
| [removePlaceholder()](#removePlaceholder--) | Bu şeklin bir yer tutucu olmadığını tanımlar. |
| [addPlaceholder(IPlaceholder placeholderToCopyFrom)](#addPlaceholder-com.aspose.slides.IPlaceholder-) | Eğer yoksa yeni bir yer tutucu ekler ve yer tutucu özelliklerini belirtilen birine ayarlar. |
| [getBasePlaceholder()](#getBasePlaceholder--) | Temel bir yer tutucu şekli döndürür (geçerli şeklin devralındığı düzen ve/veya ana slayttan gelen şekil). |
| [getCustomData()](#getCustomData--) | Şeklin özel verilerini döndürür. |
| [getRawFrame()](#getRawFrame--) | Ham şekil çerçevesinin özelliklerini döndürür veya ayarlar. |
| [setRawFrame(IShapeFrame value)](#setRawFrame-com.aspose.slides.IShapeFrame-) | Ham şekil çerçevesinin özelliklerini döndürür veya ayarlar. |
| [getFrame()](#getFrame--) | Ham şekil çerçevesinin özelliklerini döndürür veya ayarlar. |
| [setFrame(IShapeFrame value)](#setFrame-com.aspose.slides.IShapeFrame-) | Ham şekil çerçevesinin özelliklerini döndürür veya ayarlar. |
| [getLineFormat()](#getLineFormat--) | Bir şekil için çizgi biçimlendirme özelliklerini içeren LineFormat nesnesini döndürür. |
| [getThreeDFormat()](#getThreeDFormat--) | Bir şekil için 3B efekt özelliklerini içeren ThreeDFormat nesnesini döndürür. |
| [getEffectFormat()](#getEffectFormat--) | Bir şekle uygulanan piksel efektlerini içeren EffectFormat nesnesini döndürür. |
| [getFillFormat()](#getFillFormat--) | Bir şekil için doldurma biçimlendirme özelliklerini içeren FillFormat nesnesini döndürür. |
| [getImage()](#getImage--) | Şeklin küçük resmini döndürür. |
| [getImage(int bounds, float scaleX, float scaleY)](#getImage-int-float-float-) | Şeklin küçük resmini döndürür. |
| [writeAsSvg(OutputStream stream)](#writeAsSvg-java.io.OutputStream-) | Şeklin içeriğini SVG dosyası olarak kaydeder. |
| [writeAsSvg(OutputStream stream, ISVGOptions svgOptions)](#writeAsSvg-java.io.OutputStream-com.aspose.slides.ISVGOptions-) | Şeklin içeriğini SVG dosyası olarak kaydeder. |
| [getHyperlinkClick()](#getHyperlinkClick--) | Fare tıklaması için tanımlanan köprüyi döndürür veya ayarlar. |
| [setHyperlinkClick(IHyperlink value)](#setHyperlinkClick-com.aspose.slides.IHyperlink-) | Fare tıklaması için tanımlanan köprüyi döndürür veya ayarlar. |
| [getHyperlinkMouseOver()](#getHyperlinkMouseOver--) | Fare üzerindeyken tanımlanan köprüyi döndürür veya ayarlar. |
| [setHyperlinkMouseOver(IHyperlink value)](#setHyperlinkMouseOver-com.aspose.slides.IHyperlink-) | Fare üzerindeyken tanımlanan köprüyi döndürür veya ayarlar. |
| [getHyperlinkManager()](#getHyperlinkManager--) | Köprü yöneticisini döndürür. |
| [getHidden()](#getHidden--) | Şeklin gizli olup olmadığını belirler. |
| [setHidden(boolean value)](#setHidden-boolean-) | Şeklin gizli olup olmadığını belirler. |
| [getZOrderPosition()](#getZOrderPosition--) | Bir şeklin z-sırasındaki konumunu döndürür. |
| [getConnectionSiteCount()](#getConnectionSiteCount--) | Şekildeki bağlantı noktalarının sayısını döndürür. |
| [getRotation()](#getRotation--) | Belirtilen şeklin z-ekseni etrafında döndürüldüğü derece sayısını döndürür veya ayarlar. |
| [setRotation(float value)](#setRotation-float-) | Belirtilen şeklin z-ekseni etrafında döndürüldüğü derece sayısını döndürür veya ayarlar. |
| [getX()](#getX--) | Şeklin sol üst köşesinin x koordinatını, nokta cinsinden alır veya ayarlar. |
| [setX(float value)](#setX-float-) | Şeklin sol üst köşesinin x koordinatını, nokta cinsinden alır veya ayarlar. |
| [getY()](#getY--) | Şeklin sol üst köşesinin y koordinatını, nokta cinsinden alır veya ayarlar. |
| [setY(float value)](#setY-float-) | Şeklin sol üst köşesinin y koordinatını, nokta cinsinden alır veya ayarlar. |
| [getWidth()](#getWidth--) | Şeklin genişliğini, nokta cinsinden alır veya ayarlar. |
| [setWidth(float value)](#setWidth-float-) | Şeklin genişliğini, nokta cinsinden alır veya ayarlar. |
| [getHeight()](#getHeight--) | Şeklin yüksekliğini, nokta cinsinden alır veya ayarlar. |
| [setHeight(float value)](#setHeight-float-) | Şeklin yüksekliğini, nokta cinsinden alır veya ayarlar. |
| [getBlackWhiteMode()](#getBlackWhiteMode--) | Özellik, bir şeklin siyah-beyaz görüntü modunda nasıl render edileceğini belirtir. |
| [setBlackWhiteMode(byte value)](#setBlackWhiteMode-byte-) | Özellik, bir şeklin siyah-beyaz görüntü modunda nasıl render edileceğini belirtir. |
| [getUniqueId()](#getUniqueId--) | Eklentiler veya diğer kodlar tarafından kullanılmak üzere tasarlanmış, dahili, sunum-kapsamlı bir tanımlayıcı döndürür. |
| [getOfficeInteropShapeId()](#getOfficeInteropShapeId--) | Şeklin ömrü boyunca sabit kalan ve PowerPoint ya da interop kodunun belge içindeki herhangi bir yerden şekli güvenilir bir şekilde referans almasını sağlayan, slayt-kapsamlı benzersiz bir tanımlayıcı döndürür. |
| [getAlternativeText()](#getAlternativeText--) | Bir şekille ilişkili alternatif metni döndürür veya ayarlar. |
| [setAlternativeText(String value)](#setAlternativeText-java.lang.String-) | Bir şekille ilişkili alternatif metni döndürür veya ayarlar. |
| [getAlternativeTextTitle()](#getAlternativeTextTitle--) | Bir şekille ilişkili alternatif metnin başlığını döndürür veya ayarlar. |
| [setAlternativeTextTitle(String value)](#setAlternativeTextTitle-java.lang.String-) | Bir şekille ilişkili alternatif metnin başlığını döndürür veya ayarlar. |
| [getName()](#getName--) | Bir şeklin adını döndürür veya ayarlar. |
| [setName(String value)](#setName-java.lang.String-) | Bir şeklin adını döndürür veya ayarlar. |
| [isDecorative()](#isDecorative--) | ‘Mark as decorative’ seçeneğini okuma/yazma boolean olarak alır veya ayarlar. |
| [setDecorative(boolean value)](#setDecorative-boolean-) | ‘Mark as decorative’ seçeneğini okuma/yazma boolean olarak alır veya ayarlar. |
| [getShapeLock()](#getShapeLock--) | Şeklin kilitlerini döndürür. |
| [isGrouped()](#isGrouped--) | Şeklin gruplanıp gruplanmadığını belirler. |
| [getParentGroup()](#getParentGroup--) | Şekil gruplanmışsa, üst grup şekil nesnesini döndürür. |
| [getParent_Immediate()](#getParent-Immediate--) |  |
| [getVisualBounds()](#getVisualBounds--) | Render edilmiş içeriğinden hesaplanan şeklin görsel sınırlarını alır. |
| [getSlide()](#getSlide--) | Bir şeklin üst slaydını döndürür. |
| [getPresentation()](#getPresentation--) | Bir slaydın üst sunumunu döndürür. |

### isTextHolder() {#isTextHolder--}
```
public final boolean isTextHolder()
```

Şeklin TextHolder_PPT olup olmadığını belirler. Salt okunur boolean.

**Döndürür:**  
boolean

### getPlaceholder() {#getPlaceholder--}
```
public final IPlaceholder getPlaceholder()
```

Bir şekil için yer tutucuyu döndürür. Şeklin yer tutucusu yoksa null döndürür. Salt okunur [IPlaceholder](../../com.aspose.slides/iplaceholder).

--------------------

> ```
> The following example shows how to change Text in Placeholder.
>  
>  // Bir Presentation sınıfı örneklenir
>  Presentation pres = new Presentation("ReplacingText.pptx");
>  try {
>      // İlk slayta erişir
>      ISlide sld = pres.getSlides().get_Item(0);
>      // Yer tutucuyu bulmak için şekiller arasında iterasyon yapar
>      for (IShape shp : sld.getShapes())
>          if (shp.getPlaceholder() != null)
>          {
>              // Her yer tutucudaki metni değiştirir
>              ((IAutoShape)shp).getTextFrame().setText("This is a Placeholder");
>          }
>      // Sunumu diske kaydeder
>      pres.save("output_out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
>  
>  The following example shows how to set Prompt Text in Placeholder.
>  
>  Presentation pres = new Presentation("Presentation2.pptx");
>  try {
>      ISlide slide = pres.getSlides().get_Item(0);
>      for (IShape shape : slide.getSlide().getShapes()) // Slayt içinde iterasyon yapar
>      {
>          if (shape.getPlaceholder() != null && shape instanceof AutoShape)
>          {
>              String text = "";
>              if (shape.getPlaceholder().getType() == PlaceholderType.CenteredTitle) // PowerPoint "Click to add title" metnini gösterir
>              {
>                  text = "Add Title";
>              }
>              else if (shape.getPlaceholder().getType() == PlaceholderType.Subtitle) // Alt başlık ekler
>              {
>                  text = "Add Subtitle";
>              }
>              ((IAutoShape)shape).getTextFrame().setText(text);
>              System.out.println("Placeholder with text: " + text);
>          }
>      }
>      pres.save("Placeholders_PromptText.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Döndürür:**  
[IPlaceholder](../../com.aspose.slides/iplaceholder)

### removePlaceholder() {#removePlaceholder--}
```
public final void removePlaceholder()
```

Bu şeklin bir yer tutucu olmadığını tanımlar.

### addPlaceholder(IPlaceholder placeholderToCopyFrom) {#addPlaceholder-com.aspose.slides.IPlaceholder-}
```
public final IPlaceholder addPlaceholder(IPlaceholder placeholderToCopyFrom)
```

Yeni bir yer tutucu ekler (eğer yoksa) ve yer tutucu özelliklerini belirtilen birine ayarlar.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| placeholderToCopyFrom | [IPlaceholder](../../com.aspose.slides/iplaceholder) | İçeriği kopyalanacak yer tutucu. |

**Döndürür:**  
[IPlaceholder](../../com.aspose.slides/iplaceholder) - Yeni `#getPlaceholder.getPlaceholder`.

### getBasePlaceholder() {#getBasePlaceholder--}
```
public final IShape getBasePlaceholder()
```

Temel bir yer tutucu şekli döndürür (geçerli şeklin devralındığı düzen ve/veya ana slayttan gelen şekil).

--------------------

> ```
> // yer tutucu şeklin tüm (master/layout/slide) animasyon efektlerini al
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

Geçerli şekil devralınmamışsa null döndürülür.

**Döndürür:**  
[IShape](../../com.aspose.slides/ishape)

### getCustomData() {#getCustomData--}
```
public final ICustomData getCustomData()
```

Şeklin özel verilerini döndürür. Salt okunur [ICustomData](../../com.aspose.slides/icustomdata).

**Döndürür:**  
[ICustomData](../../com.aspose.slides/icustomdata)

### getRawFrame() {#getRawFrame--}
```
public final IShapeFrame getRawFrame()
```

Ham şekil çerçevesinin özelliklerini döndürür veya ayarlar. Okunabilir/yazılabilir [IShapeFrame](../../com.aspose.slides/ishapeframe).

--------------------

> ```
> Code that attempts to assign undefined frame to IShape.getFrame() doesn't make sense in general case (particularly in case when parent GroupShape is multiple nested into other GroupShape-s). For example:
>  
>  IShape shape = ...;
>  shape.setFrame(new ShapeFrame(Float.NaN, Float.NaN, Float.NaN, Float.NaN, NullableBool.NotDefined, NullableBool.NotDefined, Float.NaN));
>  //veya
>  slide.getShapes().addAutoShape(ShapeType.RoundCornerRectangle, Float.NaN, Float.NaN, Float.NaN, Float.NaN);
>  //Bu tür kod belirsiz durumlara yol açabilir. Bu nedenle IShape.getFrame() için tanımsız değerlerin kullanılmasına sınırlamalar getirilmiştir. x, y, width, height, flipH, flipV ve rotationAngle değerlerinin tanımlı olması gerekir (Float.NaN veya NullableBool.NotDefined olmamalıdır). Yukarıdaki örnek kod şimdi ArgumentException hatası fırlatır.
>  //Bu, aşağıdaki kullanım durumları için geçerlidir:
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
>  //Ancak IShape.RawFrame çerçeve özellikleri tanımsız olabilir. Bu, şekil bir yer tutucuya bağlı olduğunda mantıklıdır. Bu durumda tanımsız şekil çerçeve değerleri üst yer tutucu şekilden devralınır. Eğer o şekil için üst bir yer tutucu şekil yoksa, şekil etkili çerçevesini IShape.RawFrame'ine göre değerlendirirken varsayılan değerleri kullanır. Varsayılan değerler x, y, width, height, flipH, flipV ve rotationAngle için 0 ve NullableBool.False'dur. Örneğin:
>  IShape shape = ...; // şekil yer tutucuya bağlıdır
>  shape.setRawFrame(new ShapeFrame(Float.NaN, Float.NaN, 100, Float.NaN, NullableBool.NotDefined, NullableBool.NotDefined, 0)); // şimdi şekil x, y, height, flipH, flipV değerlerini yer tutucudan devralır ve width=100 ve rotationAngle=0.{code}
> ```


**Döndürür:**  
[IShapeFrame](../../com.aspose.slides/ishapeframe)

### setRawFrame(IShapeFrame value) {#setRawFrame-com.aspose.slides.IShapeFrame-}
```
public final void setRawFrame(IShapeFrame value)
```

Ham şekil çerçevesinin özelliklerini döndürür veya ayarlar. Okunabilir/yazılabilir [IShapeFrame](../../com.aspose.slides/ishapeframe).

--------------------

> ```
> Code that attempts to assign undefined frame to IShape.getFrame() doesn't make sense in general case (particularly in case when parent GroupShape is multiple nested into other GroupShape-s). For example:
>  
>  IShape shape = ...;
>  shape.setFrame(new ShapeFrame(Float.NaN, Float.NaN, Float.NaN, Float.NaN, NullableBool.NotDefined, NullableBool.NotDefined, Float.NaN));
>  //veya
>  slide.getShapes().addAutoShape(ShapeType.RoundCornerRectangle, Float.NaN, Float.NaN, Float.NaN, Float.NaN);
>  //Bu tür kod belirsiz durumlara yol açabilir. Bu nedenle IShape.getFrame() için tanımsız değerlerin kullanılmasına sınırlamalar getirilmiştir. x, y, width, height, flipH, flipV ve rotationAngle değerlerinin tanımlı olması gerekir (Float.NaN veya NullableBool.NotDefined olmamalıdır). Yukarıdaki örnek kod şimdi ArgumentException hatası fırlatır.
>  //Bu, aşağıdaki kullanım durumları için geçerlidir:
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
>  //Ancak IShape.RawFrame çerçeve özellikleri tanımsız olabilir. Bu, şekil bir yer tutucuya bağlı olduğunda mantıklıdır. Bu durumda tanımsız şekil çerçeve değerleri üst yer tutucu şekilden devralınır. Eğer o şekil için üst bir yer tutucu şekil yoksa, şekil etkili çerçevesini IShape.RawFrame'ine göre değerlendirirken varsayılan değerleri kullanır. Varsayılan değerler x, y, width, height, flipH, flipV ve rotationAngle için 0 ve NullableBool.False'dur. Örneğin:
>  IShape shape = ...; // şekil yer tutucuya bağlıdır
>  shape.setRawFrame(new ShapeFrame(Float.NaN, Float.NaN, 100, Float.NaN, NullableBool.NotDefined, NullableBool.NotDefined, 0)); // şimdi şekil x, y, height, flipH, flipV değerlerini yer tutucudan devralır ve width=100 ve rotationAngle=0.{code}
> ```


**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [IShapeFrame](../../com.aspose.slides/ishapeframe) |  |

### getFrame() {#getFrame--}
```
public final IShapeFrame getFrame()
```

Şekil çerçevesinin özelliklerini döndürür veya ayarlar. Okunabilir/yazılabilir [IShapeFrame](../../com.aspose.slides/ishapeframe).

--------------------

Returned value is always defined (is not Float.NaN). Assigned value must be defined (not Float.NaN). You can set undefined values for RawFrame instance properties.

**Döndürür:**  
[IShapeFrame](../../com.aspose.slides/ishapeframe)

### setFrame(IShapeFrame value) {#setFrame-com.aspose.slides.IShapeFrame-}
```
public final void setFrame(IShapeFrame value)
```

Şekil çerçevesinin özelliklerini döndürür veya ayarlar. Okunabilir/yazılabilir [IShapeFrame](../../com.aspose.slides/ishapeframe).

--------------------

Returned value is always defined (is not Float.NaN). Assigned value must be not undefined (must be not NaN or NotDefined). You can set undefined values for RawFrame instance properties.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [IShapeFrame](../../com.aspose.slides/ishapeframe) |  |

### getLineFormat() {#getLineFormat--}
```
public ILineFormat getLineFormat()
```

Bir şekil için çizgi biçimlendirme özelliklerini içeren LineFormat nesnesini döndürür. Not: çizgi özellikleri olmayan bazı şekil türleri için null dönebilir. Salt okunur [ILineFormat](../../com.aspose.slides/ilineformat).

**Döndürür:**  
[ILineFormat](../../com.aspose.slides/ilineformat)

### getThreeDFormat() {#getThreeDFormat--}
```
public IThreeDFormat getThreeDFormat()
```

Bir şekil için 3B efekt özelliklerini içeren ThreeDFormat nesnesini döndürür. Not: 3B özellikleri olmayan bazı şekil türleri için null dönebilir. Salt okunur [IThreeDFormat](../../com.aspose.slides/ithreedformat).

**Döndürür:**  
[IThreeDFormat](../../com.aspose.slides/ithreedformat)

### getEffectFormat() {#getEffectFormat--}
```
public IEffectFormat getEffectFormat()
```

Bir şekle uygulanan piksel efektlerini içeren EffectFormat nesnesini döndürür. Not: efekt özellikleri olmayan bazı şekil türleri için null dönebilir. Salt okunur [IEffectFormat](../../com.aspose.slides/ieffectformat).

**Döndürür:**  
[IEffectFormat](../../com.aspose.slides/ieffectformat)

### getFillFormat() {#getFillFormat--}
```
public IFillFormat getFillFormat()
```

Bir şekil için doldurma biçimlendirme özelliklerini içeren FillFormat nesnesini döndürür. Not: doldurma özellikleri olmayan bazı şekil türleri için null dönebilir. Salt okunur [IFillFormat](../../com.aspose.slides/ifillformat).

--------------------

> ```
> The following example shows how to change the accent color for a theme of PowerPoint Presentation.
>  
>  Presentation pres = new Presentation();
>  try {
>      IAutoShape shape = pres.getSlides().get_Item(0).getShapes().addAutoShape(ShapeType.Rectangle, 10, 10, 100, 100);
>      shape.getFillFormat().setFillType(FillType.Solid);
>      shape.getFillFormat().getSolidFillColor().setSchemeColor(SchemeColor.Accent4);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
>  
>  The following example demonstrates how to obtain palette colors from the main theme color and then used in shapes.
>  
>  Presentation pres = new Presentation();
>  try {
>      ISlide slide = pres.getSlides().get_Item(0);
>      // Vurgu 4
>      IShape shape1 = slide.getShapes().addAutoShape(ShapeType.Rectangle, 10, 10, 50, 50);
>      shape1.getFillFormat().setFillType(FillType.Solid);
>      shape1.getFillFormat().getSolidFillColor().setSchemeColor(SchemeColor.Accent4);
>      // Vurgu 4, %80 Daha Açık
>      IShape shape2 = slide.getShapes().addAutoShape(ShapeType.Rectangle, 10, 70, 50, 50);
>      shape2.getFillFormat().setFillType(FillType.Solid);
>      shape2.getFillFormat().getSolidFillColor().setSchemeColor(SchemeColor.Accent4);
>      shape2.getFillFormat().getSolidFillColor().getColorTransform().add(ColorTransformOperation.MultiplyLuminance, 0.2f);
>      shape2.getFillFormat().getSolidFillColor().getColorTransform().add(ColorTransformOperation.AddLuminance, 0.8f);
>      // Vurgu 4, %60 Daha Açık
>      IShape shape3 = slide.getShapes().addAutoShape(ShapeType.Rectangle, 10, 130, 50, 50);
>      shape3.getFillFormat().setFillType(FillType.Solid);
>      shape3.getFillFormat().getSolidFillColor().setSchemeColor(SchemeColor.Accent4);
>      shape3.getFillFormat().getSolidFillColor().getColorTransform().add(ColorTransformOperation.MultiplyLuminance, 0.4f);
>      shape3.getFillFormat().getSolidFillColor().getColorTransform().add(ColorTransformOperation.AddLuminance, 0.6f);
>      // Vurgu 4, %40 Daha Açık
>      IShape shape4 = slide.getShapes().addAutoShape(ShapeType.Rectangle, 10, 190, 50, 50);
>      shape4.getFillFormat().setFillType(FillType.Solid);
>      shape4.getFillFormat().getSolidFillColor().setSchemeColor(SchemeColor.Accent4);
>      shape4.getFillFormat().getSolidFillColor().getColorTransform().add(ColorTransformOperation.MultiplyLuminance, 0.6f);
>      shape4.getFillFormat().getSolidFillColor().getColorTransform().add(ColorTransformOperation.AddLuminance, 0.4f);
>      // Vurgu 4, %25 Daha Koyu
>      IShape shape5 = slide.getShapes().addAutoShape(ShapeType.Rectangle, 10, 250, 50, 50);
>      shape5.getFillFormat().setFillType(FillType.Solid);
>      shape5.getFillFormat().getSolidFillColor().setSchemeColor(SchemeColor.Accent4);
>      shape5.getFillFormat().getSolidFillColor().getColorTransform().add(ColorTransformOperation.MultiplyLuminance, 0.75f);
>      // Vurgu 4, %50 Daha Koyu
>      IShape shape6 = slide.getShapes().addAutoShape(ShapeType.Rectangle, 10, 310, 50, 50);
>      shape6.getFillFormat().setFillType(FillType.Solid);
>      shape6.getFillFormat().getSolidFillColor().setSchemeColor(SchemeColor.Accent4);
>      shape6.getFillFormat().getSolidFillColor().getColorTransform().add(ColorTransformOperation.MultiplyLuminance, 0.5f);
>      pres.save("example_accent4.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Döndürür:**  
[IFillFormat](../../com.aspose.slides/ifillformat)

### getImage() {#getImage--}
```
public final IImage getImage()
```

Şeklin küçük resmini döndürür. ShapeThumbnailBounds.Shape şekil küçük resmi sınırları türü varsayılan olarak kullanılır.

**Döndürür:**  
[IImage](../../com.aspose.slides/iimage) - Şekil küçük resmi.

### getImage(int bounds, float scaleX, float scaleY) {#getImage-int-float-float-}
```
public final IImage getImage(int bounds, float scaleX, float scaleY)
```

Şeklin küçük resmini döndürür.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| bounds | int | Şekil küçük resmi sınırları türü. |
| scaleX | float | X ölçeği |
| scaleY | float | Y ölçeği |

**Döndürür:**  
[IImage](../../com.aspose.slides/iimage) - Şekil küçük resmi veya ShapeThumbnailBounds.Appearance kullanıldığında ve şeklin görünür öğeleri yoksa null.

### writeAsSvg(OutputStream stream) {#writeAsSvg-java.io.OutputStream-}
```
public final void writeAsSvg(OutputStream stream)
```

Şeklin içeriğini SVG dosyası olarak kaydeder.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| stream | java.io.OutputStream | Hedef akış |

### writeAsSvg(OutputStream stream, ISVGOptions svgOptions) {#writeAsSvg-java.io.OutputStream-com.aspose.slides.ISVGOptions-}
```
public final void writeAsSvg(OutputStream stream, ISVGOptions svgOptions)
```

Şeklin içeriğini SVG dosyası olarak kaydeder.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| stream | java.io.OutputStream | Hedef akış |
| svgOptions | [ISVGOptions](../../com.aspose.slides/isvgoptions) | SVG oluşturma seçenekleri |

### getHyperlinkClick() {#getHyperlinkClick--}
```
public final IHyperlink getHyperlinkClick()
```

Fare tıklaması için tanımlanan köprüyi döndürür veya ayarlar. Okunabilir/yazılabilir [IHyperlink](../../com.aspose.slides/ihyperlink).

**Döndürür:**  
[IHyperlink](../../com.aspose.slides/ihyperlink)

### setHyperlinkClick(IHyperlink value) {#setHyperlinkClick-com.aspose.slides.IHyperlink-}
```
public final void setHyperlinkClick(IHyperlink value)
```

Fare tıklaması için tanımlanan köprüyi döndürür veya ayarlar. Okunabilir/yazılabilir [IHyperlink](../../com.aspose.slides/ihyperlink).

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [IHyperlink](../../com.aspose.slides/ihyperlink) |  |

### getHyperlinkMouseOver() {#getHyperlinkMouseOver--}
```
public final IHyperlink getHyperlinkMouseOver()
```

Fare üzerindeyken tanımlanan köprüyi döndürür veya ayarlar. Okunabilir/yazılabilir [IHyperlink](../../com.aspose.slides/ihyperlink).

**Döndürür:**  
[IHyperlink](../../com.aspose.slides/ihyperlink)

### setHyperlinkMouseOver(IHyperlink value) {#setHyperlinkMouseOver-com.aspose.slides.IHyperlink-}
```
public final void setHyperlinkMouseOver(IHyperlink value)
```

Fare üzerindeyken tanımlanan köprüyi döndürür veya ayarlar. Okunabilir/yazılabilir [IHyperlink](../../com.aspose.slides/ihyperlink).

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [IHyperlink](../../com.aspose.slides/ihyperlink) |  |

### getHyperlinkManager() {#getHyperlinkManager--}
```
public final IHyperlinkManager getHyperlinkManager()
```

Köprü yöneticisini döndürür. Salt okunur [IHyperlinkManager](../../com.aspose.slides/ihyperlinkmanager).

**Döndürür:**  
[IHyperlinkManager](../../com.aspose.slides/ihyperlinkmanager)

### getHidden() {#getHidden--}
```
public final boolean getHidden()
```

Şeklin gizli olup olmadığını belirler. Okunabilir/yazılabilir boolean.

**Döndürür:**  
boolean

### setHidden(boolean value) {#setHidden-boolean-}
```
public final void setHidden(boolean value)
```

Şeklin gizli olup olmadığını belirler. Okunabilir/yazılabilir boolean.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | boolean |  |

### getZOrderPosition() {#getZOrderPosition--}
```
public int getZOrderPosition()
```

Bir şeklin z-sırasındaki konumunu döndürür. Shapes[0] z-sırasının arkasındaki şekli, Shapes[Shapes.Count - 1] ise önündeki şekli verir. Salt okunur int.

**Döndürür:**  
int

### getConnectionSiteCount() {#getConnectionSiteCount--}
```
public final int getConnectionSiteCount()
```

Şekildeki bağlantı noktalarının sayısını döndürür. Salt okunur int.

**Döndürür:**  
int

### getRotation() {#getRotation--}
```
public final float getRotation()
```

Belirtilen şeklin z-ekseni etrafında döndürüldüğü derece sayısını döndürür veya ayarlar. Pozitif değer saat yönünde, negatif değer saat yönünün tersine döndürülür. Okunabilir/yazılabilir float.

--------------------

Returned value is always defined (is not Float.NaN). Assigned value must be defined (not Float.NaN). You can set undefined values for RawFrame instance properties.

**Döndürür:**  
float

### setRotation(float value) {#setRotation-float-}
```
public final void setRotation(float value)
```
Returns or sets the number of degrees the specified shape is rotated around the z-axis. A positive value indicates clockwise rotation; a negative value indicates counterclockwise rotation. Okunabilir/Yazılabilir float.

--------------------

Returned value is always defined (is not Float.NaN). Assigned value must be defined (not Float.NaN). You can set undefined values for RawFrame instance properties.

**Parametreler:**
| Parametre | Tip | Açıklama |
| --- | --- | --- |
| value | float |  |

### getX() {#getX--}
```
public final float getX()
```

Gets or sets the x-coordinate of the shape's upper-left corner, measured in points. Okunabilir/Yazılabilir float.

--------------------

The value returned is always defined and never Float.NaN. The value assigned must also be defined; assign Float.NaN only to properties of a RawFrame instance.

**Dönen Değer:**
float
### setX(float value) {#setX-float-}
```
public final void setX(float value)
```

Gets or sets the x-coordinate of the shape's upper-left corner, measured in points. Okunabilir/Yazılabilir float.

--------------------

The value returned is always defined and never Float.NaN. The value assigned must also be defined; assign Float.NaN only to properties of a RawFrame instance.

**Parametreler:**
| Parametre | Tip | Açıklama |
| --- | --- | --- |
| value | float |  |

### getY() {#getY--}
```
public final float getY()
```

Gets or sets the y-coordinate of the shape's upper-left corner, measured in points. Okunabilir/Yazılabilir float.

--------------------

The value returned is always defined and never Float.NaN. The value assigned must also be defined; assign Float.NaN only to properties of a RawFrame instance.

**Dönen Değer:**
float
### setY(float value) {#setY-float-}
```
public final void setY(float value)
```

Gets or sets the y-coordinate of the shape's upper-left corner, measured in points. Okunabilir/Yazılabilir float.

--------------------

The value returned is always defined and never Float.NaN. The value assigned must also be defined; assign Float.NaN only to properties of a RawFrame instance.

**Parametreler:**
| Parametre | Tip | Açıklama |
| --- | --- | --- |
| value | float |  |

### getWidth() {#getWidth--}
```
public final float getWidth()
```

Gets or sets the width of the shape, measured in points. Okunabilir/Yazılabilir float.

--------------------

The value returned is always defined and never Float.NaN. The value assigned must also be defined; assign Float.NaN only to properties of a RawFrame instance.

**Dönen Değer:**
float
### setWidth(float value) {#setWidth-float-}
```
public final void setWidth(float value)
```

Gets or sets the width of the shape, measured in points. Okunabilir/Yazılabilir float.

--------------------

The value returned is always defined and never Float.NaN. The value assigned must also be defined; assign Float.NaN only to properties of a RawFrame instance.

**Parametreler:**
| Parametre | Tip | Açıklama |
| --- | --- | --- |
| value | float |  |

### getHeight() {#getHeight--}
```
public final float getHeight()
```

Gets or sets the height of the shape, measured in points. Okunabilir/Yazılabilir float.

--------------------

The value returned is always defined and never Float.NaN. The value assigned must also be defined; assign Float.NaN only to properties of a RawFrame instance.

**Dönen Değer:**
float
### setHeight(float value) {#setHeight-float-}
```
public final void setHeight(float value)
```

Gets or sets the height of the shape, measured in points. Okunabilir/Yazılabilir float.

--------------------

The value returned is always defined and never Float.NaN. The value assigned must also be defined; assign Float.NaN only to properties of a RawFrame instance.

**Parametreler:**
| Parametre | Tip | Açıklama |
| --- | --- | --- |
| value | float |  |

### getBlackWhiteMode() {#getBlackWhiteMode--}
```
public final byte getBlackWhiteMode()
```

Property specifies how a shape will render in black-and-white display mode.. Okunabilir/Yazılabilir [BlackWhiteMode](../../com.aspose.slides/blackwhitemode).

**Dönen Değer:**
byte
### setBlackWhiteMode(byte value) {#setBlackWhiteMode-byte-}
```
public final void setBlackWhiteMode(byte value)
```

Property specifies how a shape will render in black-and-white display mode.. Okunabilir/Yazılabilir [BlackWhiteMode](../../com.aspose.slides/blackwhitemode).

**Parametreler:**
| Parametre | Tip | Açıklama |
| --- | --- | --- |
| value | byte |  |

### getUniqueId() {#getUniqueId--}
```
public final long getUniqueId()
```

Returns an internal, presentation-scoped identifier intended for use by add-ins or other code. Because this value can be reassigned by the user or programmatically, it must not be treated as a persistent unique key. Salt Okunur long. See also \#getOfficeInteropShapeId.getOfficeInteropShapeId.

**Dönen Değer:**
long
### getOfficeInteropShapeId() {#getOfficeInteropShapeId--}
```
public final long getOfficeInteropShapeId()
```

Returns a slide-scoped unique identifier that remains constant for the lifetime of the shape and lets PowerPoint or interop code reliably reference the shape from anywhere in the document. Salt Okunur long. See also \#getUniqueId.getUniqueId.

**Dönen Değer:**
long
### getAlternativeText() {#getAlternativeText--}
```
public final String getAlternativeText()
```

Returns or sets the alternative text associated with a shape. Okunabilir/Yazılabilir String.

**Dönen Değer:**
java.lang.String
### setAlternativeText(String value) {#setAlternativeText-java.lang.String-}
```
public final void setAlternativeText(String value)
```

Returns or sets the alternative text associated with a shape. Okunabilir/Yazılabilir String.

**Parametreler:**
| Parametre | Tip | Açıklama |
| --- | --- | --- |
| value | java.lang.String |  |

### getAlternativeTextTitle() {#getAlternativeTextTitle--}
```
public final String getAlternativeTextTitle()
```

Returns or sets the title of alternative text associated with a shape. Okunabilir/Yazılabilir String.

**Dönen Değer:**
java.lang.String
### setAlternativeTextTitle(String value) {#setAlternativeTextTitle-java.lang.String-}
```
public final void setAlternativeTextTitle(String value)
```

Returns or sets the title of alternative text associated with a shape. Okunabilir/Yazılabilir String.

**Parametreler:**
| Parametre | Tip | Açıklama |
| --- | --- | --- |
| value | java.lang.String |  |

### getName() {#getName--}
```
public final String getName()
```

Returns or sets the name of a shape. Must be not null. Use empty string value if needed. Okunabilir/Yazılabilir String.

**Dönen Değer:**
java.lang.String
### setName(String value) {#setName-java.lang.String-}
```
public final void setName(String value)
```

Returns or sets the name of a shape. Must be not null. Use empty string value if needed. Okunabilir/Yazılabilir String.

**Parametreler:**
| Parametre | Tip | Açıklama |
| --- | --- | --- |
| value | java.lang.String |  |

### isDecorative() {#isDecorative--}
```
public final boolean isDecorative()
```

Gets or sets 'Mark as decorative' option Okunabilir/Yazılabilir boolean.

--------------------

> ```
> Presentation pres = new Presentation("sample.pptx");
>  try {
>     pres.getSlides().get_Item(0).getShapes().get_Item(0).setDecorative(true);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Dönen Değer:**
boolean
### setDecorative(boolean value) {#setDecorative-boolean-}
```
public final void setDecorative(boolean value)
```

Gets or sets 'Mark as decorative' option Okunabilir/Yazılabilir boolean.

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
public IBaseShapeLock getShapeLock()
```

Returns shape's locks. Salt Okunur [IBaseShapeLock](../../com.aspose.slides/ibaseshapelock).

**Dönen Değer:**
[IBaseShapeLock](../../com.aspose.slides/ibaseshapelock)
### isGrouped() {#isGrouped--}
```
public final boolean isGrouped()
```

Determines whether the shape is grouped. Salt Okunur boolean.

--------------------

Property \#getParentGroup.getParentGroup returns parent GroupShape object if shape is grouped.

**Dönen Değer:**
boolean
### getParentGroup() {#getParentGroup--}
```
public final IGroupShape getParentGroup()
```

Returns parent GroupShape object if shape is grouped. Otherwise returns null. Salt Okunur [IGroupShape](../../com.aspose.slides/igroupshape).

--------------------

Property \#isGrouped.isGrouped determines whether the shape is grouped.

**Dönen Değer:**
[IGroupShape](../../com.aspose.slides/igroupshape)
### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```

Returns Parent_Immediate object. Salt Okunur IDOMObject.

**Dönen Değer:**
com.aspose.slides.IDOMObject
### getVisualBounds() {#getVisualBounds--}
```
public final Rectangle2D.Float getVisualBounds()
```

Gets the visual bounds of the shape calculated from its rendered content.

**Dönen Değer:**
java.awt.geom.Rectangle2D.Float - A java.awt.geom.Rectangle2D.Float that represents the visual bounds of the shape in slide coordinates.

--------------------

The returned rectangle represents the axis-aligned bounds of all content produced by the shape during rendering in slide coordinate space. These bounds may differ from the shape's model bounds \#getX.getX/\#setX(float).setX(float), \#getY.getY/\#setY(float).setY(float), \#getWidth.getWidth/\#setWidth(float).setWidth(float), \#getHeight.getHeight/\#setHeight(float).setHeight(float) and may contain negative coordinates if the rendered content extends beyond the slide origin. The visual bounds take into account rendering-related aspects such as transformations (for example, rotation), stroke width and joins, text layout and overflow, SmartArt geometry, and other layout effects that influence the final rendered appearance of the shape. The returned bounds are not clipped to the slide rectangle.
### getSlide() {#getSlide--}
```
public final IBaseSlide getSlide()
```

Returns the parent slide of a shape. Salt Okunur [IBaseSlide](../../com.aspose.slides/ibaseslide).

**Dönen Değer:**
[IBaseSlide](../../com.aspose.slides/ibaseslide)
### getPresentation() {#getPresentation--}
```
public final IPresentation getPresentation()
```

Returns the parent presentation of a slide. Salt Okunur [IPresentation](../../com.aspose.slides/ipresentation).

**Dönen Değer:**
[IPresentation](../../com.aspose.slides/ipresentation)