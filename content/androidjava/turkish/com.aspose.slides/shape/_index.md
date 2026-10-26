---
title: Shape
second_title: Aspose.Slides Android için Java API Referansı
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
| [addPlaceholder(IPlaceholder placeholderToCopyFrom)](#addPlaceholder-com.aspose.slides.IPlaceholder-) | Yer tutucu yoksa yeni bir yer tutucu ekler ve yer tutucu özelliklerini belirtilen birine ayarlar. |
| [getBasePlaceholder()](#getBasePlaceholder--) | Temel bir yer tutucu şekli döndürür (geçerli şeklin miras aldığı düzen ve/veya ana slayttan şekil). |
| [getCustomData()](#getCustomData--) | Şeklin özel verisini döndürür. |
| [getRawFrame()](#getRawFrame--) | Ham şekil çerçevesinin özelliklerini döndürür veya ayarlar. |
| [setRawFrame(IShapeFrame value)](#setRawFrame-com.aspose.slides.IShapeFrame-) | Ham şekil çerçevesinin özelliklerini döndürür veya ayarlar. |
| [getFrame()](#getFrame--) | Şekil çerçevesinin özelliklerini döndürür veya ayarlar. |
| [setFrame(IShapeFrame value)](#setFrame-com.aspose.slides.IShapeFrame-) | Şekil çerçevesinin özelliklerini döndürür veya ayarlar. |
| [getLineFormat()](#getLineFormat--) | Bir şekil için çizgi biçimlendirme özelliklerini içeren LineFormat nesnesini döndürür. |
| [getThreeDFormat()](#getThreeDFormat--) | Bir şekil için 3D efekt özelliklerini içeren ThreeDFormat nesnesini döndürür. |
| [getEffectFormat()](#getEffectFormat--) | Bir şekle uygulanan piksel efektlerini içeren EffectFormat nesnesini döndürür. |
| [getFillFormat()](#getFillFormat--) | Bir şekil için doldurma biçimlendirme özelliklerini içeren FillFormat nesnesini döndürür. |
| [getImage()](#getImage--) | Şeklin küçük resmini döndürür. |
| [getImage(int bounds, float scaleX, float scaleY)](#getImage-int-float-float-) | Şeklin küçük resmini döndürür. |
| [writeAsSvg(OutputStream stream)](#writeAsSvg-java.io.OutputStream-) | Şeklin içeriğini SVG dosyası olarak kaydeder. |
| [writeAsSvg(OutputStream stream, ISVGOptions svgOptions)](#writeAsSvg-java.io.OutputStream-com.aspose.slides.ISVGOptions-) | Şeklin içeriğini SVG dosyası olarak kaydeder. |
| [getHyperlinkClick()](#getHyperlinkClick--) | Fare tıklaması için tanımlanmış köprüyü döndürür veya ayarlar. |
| [setHyperlinkClick(IHyperlink value)](#setHyperlinkClick-com.aspose.slides.IHyperlink-) | Fare tıklaması için tanımlanmış köprüyü döndürür veya ayarlar. |
| [getHyperlinkMouseOver()](#getHyperlinkMouseOver--) | Fare üzerine gelindiğinde tanımlanmış köprüyü döndürür veya ayarlar. |
| [setHyperlinkMouseOver(IHyperlink value)](#setHyperlinkMouseOver-com.aspose.slides.IHyperlink-) | Fare üzerine gelindiğinde tanımlanmış köprüyü döndürür veya ayarlar. |
| [getHyperlinkManager()](#getHyperlinkManager--) | Köprü yöneticisini döndürür. |
| [getHidden()](#getHidden--) | Şeklin gizli olup olmadığını belirler. |
| [setHidden(boolean value)](#setHidden-boolean-) | Şeklin gizli olup olmadığını belirler. |
| [getZOrderPosition()](#getZOrderPosition--) | Bir şeklin z-sırasındaki konumunu döndürür. |
| [getConnectionSiteCount()](#getConnectionSiteCount--) | Şeklin bağlantı noktalarının sayısını döndürür. |
| [getRotation()](#getRotation--) | Belirtilen şeklin z ekseni etrafında döndürüldüğü derece sayısını döndürür veya ayarlar. |
| [setRotation(float value)](#setRotation-float-) | Belirtilen şeklin z ekseni etrafında döndürüldüğü derece sayısını döndürür veya ayarlar. |
| [getX()](#getX--) | Şeklin sol üst köşesinin x koordinatını (point cinsinden) alır veya ayarlar. |
| [setX(float value)](#setX-float-) | Şeklin sol üst köşesinin x koordinatını (point cinsinden) alır veya ayarlar. |
| [getY()](#getY--) | Şeklin sol üst köşesinin y koordinatını (point cinsinden) alır veya ayarlar. |
| [setY(float value)](#setY-float-) | Şeklin sol üst köşesinin y koordinatını (point cinsinden) alır veya ayarlar. |
| [getWidth()](#getWidth--) | Şeklin genişliğini (point cinsinden) alır veya ayarlar. |
| [setWidth(float value)](#setWidth-float-) | Şeklin genişliğini (point cinsinden) alır veya ayarlar. |
| [getHeight()](#getHeight--) | Şeklin yüksekliğini (point cinsinden) alır veya ayarlar. |
| [setHeight(float value)](#setHeight-float-) | Şeklin yüksekliğini (point cinsinden) alır veya ayarlar. |
| [getBlackWhiteMode()](#getBlackWhiteMode--) | Özellik, bir şeklin siyah-beyaz görüntü modunda nasıl render edileceğini belirtir. |
| [setBlackWhiteMode(byte value)](#setBlackWhiteMode-byte-) | Özellik, bir şeklin siyah-beyaz görüntü modunda nasıl render edileceğini belirtir. |
| [getUniqueId()](#getUniqueId--) | Eklentiler veya diğer kodlar tarafından kullanılmak üzere tasarlanmış dahili, sunum kapsamlı bir tanımlayıcı döndürür. |
| [getOfficeInteropShapeId()](#getOfficeInteropShapeId--) | Bir slayt kapsamlı benzersiz tanımlayıcı döndürür; bu, şeklin ömrü boyunca sabit kalır ve PowerPoint ya da interop kodunun şekle belge içinde her yerden güvenilir şekilde başvurmasını sağlar. |
| [getAlternativeText()](#getAlternativeText--) | Bir şekille ilişkili alternatif metni döndürür veya ayarlar. |
| [setAlternativeText(String value)](#setAlternativeText-java.lang.String-) | Bir şekille ilişkili alternatif metni döndürür veya ayarlar. |
| [getAlternativeTextTitle()](#getAlternativeTextTitle--) | Bir şekille ilişkili alternatif metnin başlığını döndürür veya ayarlar. |
| [setAlternativeTextTitle(String value)](#setAlternativeTextTitle-java.lang.String-) | Bir şekille ilişkili alternatif metnin başlığını döndürür veya ayarlar. |
| [getName()](#getName--) | Bir şeklin adını döndürür veya ayarlar. |
| [setName(String value)](#setName-java.lang.String-) | Bir şeklin adını döndürür veya ayarlar. |
| [isDecorative()](#isDecorative--) | ‘Dekoratif olarak işaretle’ seçeneğini alır veya ayarlar. Okunur/yazılabilir boolean. |
| [setDecorative(boolean value)](#setDecorative-boolean-) | ‘Dekoratif olarak işaretle’ seçeneğini alır veya ayarlar. Okunur/yazılabilir boolean. |
| [getShapeLock()](#getShapeLock--) | Şeklin kilitlerini döndürür. |
| [isGrouped()](#isGrouped--) | Şeklin gruplanmış olup olmadığını belirler. |
| [getParentGroup()](#getParentGroup--) | Şekil gruplanmışsa üst GroupShape nesnesini döndürür. |
| [getParent_Immediate()](#getParent-Immediate--) |  |
| [getVisualBounds()](#getVisualBounds--) | Şeklin render edilmiş içeriğinden hesaplanan görsel sınırlarını alır. |
| [getSlide()](#getSlide--) | Bir şeklin üst slaydını döndürür. |
| [getPresentation()](#getPresentation--) | Bir slaydın üst sunumunu döndürür. |

### isTextHolder() {#isTextHolder--}
```
public final boolean isTextHolder()
```

Şeklin TextHolder_PPT olup olmadığını belirler. Salt-okunur boolean .

**Döndürür:**
boolean

### getPlaceholder() {#getPlaceholder--}
```
public final IPlaceholder getPlaceholder()
```

Bir şekil için yer tutucuyu döndürür. Şeklin yer tutucusu yoksa null döndürür. Salt-okunur [IPlaceholder](../../com.aspose.slides/iplaceholder).

--------------------

> ```
> The following example shows how to change Text in Placeholder.
>  
>  // Bir Presentation sınıfı örnekleştirir
>  Presentation pres = new Presentation("ReplacingText.pptx");
>  try {
>      // İlk slayta erişir
>      ISlide sld = pres.getSlides().get_Item(0);
>      // Yer tutucuyu bulmak için şekillerde dolaşır
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
>      for (IShape shape : slide.getSlide().getShapes()) // Slaytı dolaşır
>      {
>          if (shape.getPlaceholder() != null && shape instanceof AutoShape)
>          {
>              String text = "";
>              if (shape.getPlaceholder().getType() == PlaceholderType.CenteredTitle) // PowerPoint "Click to add title" gösterir
>              {
>                  text = "Add Title";
>              }
>              else if (shape.getPlaceholder().getType() == PlaceholderType.Subtitle) // Altyazı ekler
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

Yer tutucu yoksa yeni bir yer tutucu ekler ve yer tutucu özelliklerini belirtilen birine ayarlar.

**Parametreler:**
| Parametre | Tip | Açıklama |
| --- | --- | --- |
| placeholderToCopyFrom | [IPlaceholder](../../com.aspose.slides/iplaceholder) | İçeriği kopyalanacak yer tutucu. |

**Döndürür:**
[IPlaceholder](../../com.aspose.slides/iplaceholder) - New \#getPlaceholder.getPlaceholder.

### getBasePlaceholder() {#getBasePlaceholder--}
```
public final IShape getBasePlaceholder()
```

Temel bir yer tutucu şekli döndürür (geçerli şeklin miras aldığı düzen ve/veya ana slayttan şekil).

--------------------

> ```
> // yer tutucu şeklin tüm (master/layout/slide) animasyonlu efektlerini al
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

Geçerli şekil miras alınmamışsa null döndürülür.

**Döndürür:**
[IShape](../../com.aspose.slides/ishape)

### getCustomData() {#getCustomData--}
```
public final ICustomData getCustomData()
```

Şeklin özel verisini döndürür. Salt-okunur [ICustomData](../../com.aspose.slides/icustomdata).

**Döndürür:**
[ICustomData](../../com.aspose.slides/icustomdata)

### getRawFrame() {#getRawFrame--}
```
public final IShapeFrame getRawFrame()
```

Ham şekil çerçevesinin özelliklerini döndürür veya ayarlar. Okunur/yazılabilir [IShapeFrame](../../com.aspose.slides/ishapeframe).

--------------------

> ```
> Code that attempts to assign undefined frame to IShape.getFrame() doesn't make sense in general case (particularly in case when parent GroupShape is multiple nested into other GroupShape-s). For example:
>  
>  IShape shape = ...;
>  shape.setFrame(new ShapeFrame(Float.NaN, Float.NaN, Float.NaN, Float.NaN, NullableBool.NotDefined, NullableBool.NotDefined, Float.NaN));
>  //veya
>  slide.getShapes().addAutoShape(ShapeType.RoundCornerRectangle, Float.NaN, Float.NaN, Float.NaN, Float.NaN);
>  //Bu kod belirsiz durumlara yol açabilir. Bu nedenle IShape.getFrame() için tanımsız değerlerin kullanımına kısıtlamalar eklenmiştir. x, y, width, height, flipH, flipV ve rotationAngle değerlerinin tanımlı olması gerekir (Float.NaN veya NullableBool.NotDefined olmamalıdır). Yukarıdaki örnek kod şimdi ArgumentException hatası fırlatıyor.
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
>  //Ancak IShape.RawFrame çerçeve özellikleri tanımsız olabilir. Bu, şekil bir placeholder'a bağlanmışken anlamlıdır. Daha sonra tanımsız şekil çerçeve değerleri üst placeholder şekli tarafından geçersiz kılınır. Eğer o şekil için üst placeholder şekli yoksa, şekil IShape.RawFrame temelinde etkili çerçeveyi değerlendirirken varsayılan değerleri kullanır. Varsayılan değerler x, y, width, height, flipH, flipV ve rotationAngle için 0 ve NullableBool.False'dur. Örneğin:
>  IShape shape = ...; // şekil placeholder'a bağlanmış
>  shape.setRawFrame(new ShapeFrame(Float.NaN, Float.NaN, 100, Float.NaN, NullableBool.NotDefined, NullableBool.NotDefined, 0)); // şimdi şekil x, y, height, flipH, flipV değerlerini placeholder'dan devralır ve width=100 ve rotationAngle=0 değerlerini geçersiz kılar.{code}
> ```


**Döndürür:**
[IShapeFrame](../../com.aspose.slides/ishapeframe)

### setRawFrame(IShapeFrame value) {#setRawFrame-com.aspose.slides.IShapeFrame-}
```
public final void setRawFrame(IShapeFrame value)
```

Ham şekil çerçevesinin özelliklerini döndürür veya ayarlar. Okunur/yazılabilir [IShapeFrame](../../com.aspose.slides/ishapeframe).

--------------------

> ```
> Code that attempts to assign undefined frame to IShape.getFrame() doesn't make sense in general case (particularly in case when parent GroupShape is multiple nested into other GroupShape-s). For example:
>  
>  IShape shape = ...;
>  shape.setFrame(new ShapeFrame(Float.NaN, Float.NaN, Float.NaN, Float.NaN, NullableBool.NotDefined, NullableBool.NotDefined, Float.NaN));
>  //veya
>  slide.getShapes().addAutoShape(ShapeType.RoundCornerRectangle, Float.NaN, Float.NaN, Float.NaN, Float.NaN);
>  //Bu kod belirsiz durumlara yol açabilir. Bu nedenle IShape.getFrame() için tanımsız değerlerin kullanılmasına kısıtlamalar eklenmiştir. x, y, width, height, flipH, flipV ve rotationAngle değerlerinin tanımlı olması gerekir (Float.NaN veya NullableBool.NotDefined olmamalıdır). Yukarıdaki örnek kod şimdi ArgumentException hatası fırlatıyor.
>  //Bu durumlar aşağıdaki kullanım senaryoları için geçerlidir:
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
>  //Ancak IShape.RawFrame çerçeve özellikleri tanımsız olabilir. Bu, şekil bir placeholder'a bağlıysa anlamlıdır. Daha sonra tanımsız şekil çerçeve değerleri üst placeholder şekli tarafından geçersiz kılınır. Eğer o şekil için üst placeholder şekli yoksa, şekil IShape.RawFrame temelinde etkili çerçeveyi değerlendirirken varsayılan değerleri kullanır. Varsayılan değerler x, y, width, height, flipH, flipV ve rotationAngle için 0 ve NullableBool.False'dur. Örneğin:
>  IShape shape = ...; // şekil placeholder'a bağlı
>  shape.setRawFrame(new ShapeFrame(Float.NaN, Float.NaN, 100, Float.NaN, NullableBool.NotDefined, NullableBool.NotDefined, 0)); // şimdi şekil x, y, height, flipH, flipV değerlerini placeholder'dan devralır ve width=100 ve rotationAngle=0 değerlerini geçersiz kılar.{code}
```

**Parametreler:**
| Parametre | Tip | Açıklama |
| --- | --- | --- |
| value | [IShapeFrame](../../com.aspose.slides/ishapeframe) |  |

### getFrame() {#getFrame--}
```
public final IShapeFrame getFrame()
```

Şekil çerçevesinin özelliklerini döndürür veya ayarlar. Okunur/yazılabilir [IShapeFrame](../../com.aspose.slides/ishapeframe).

--------------------

Dönen IShapeFrame örneğinin her özelliğinin değeri tanımsız değildir (NaN veya NotDefined değildir). Atanan IShapeFrame örneğinin her özelliğinin değeri tanımsız olmamalıdır (NaN veya NotDefined olmamalıdır). RawFrame örnek özellikleri için tanımsız değerler ayarlayabilirsiniz.

**Döndürür:**
[IShapeFrame](../../com.aspose.slides/ishapeframe)

### setFrame(IShapeFrame value) {#setFrame-com.aspose.slides.IShapeFrame-}
```
public final void setFrame(IShapeFrame value)
```

Şekil çerçevesinin özelliklerini döndürür veya ayarlar. Okunur/yazılabilir [IShapeFrame](../../com.aspose.slides/ishapeframe).

--------------------

Dönen IShapeFrame örneğinin her özelliğinin değeri tanımsız değildir (NaN veya NotDefined değildir). Atanan IShapeFrame örneğinin her özelliğinin değeri tanımsız olmamalıdır (NaN veya NotDefined olmamalıdır). RawFrame örnek özellikleri için tanımsız değerler ayarlayabilirsiniz.

**Parametreler:**
| Parametre | Tip | Açıklama |
| --- | --- | --- |
| value | [IShapeFrame](../../com.aspose.slides/ishapeframe) |  |

### getLineFormat() {#getLineFormat--}
```
public ILineFormat getLineFormat()
```

Bir şekil için çizgi biçimlendirme özelliklerini içeren LineFormat nesnesini döndürür. Not: Çizgi özellikleri olmayan bazı şekil türleri için null döndürebilir. Salt-okunur [ILineFormat](../../com.aspose.slides/ilineformat).

**Döndürür:**
[ILineFormat](../../com.aspose.slides/ilineformat)

### getThreeDFormat() {#getThreeDFormat--}
```
public IThreeDFormat getThreeDFormat()
```

Bir şekil için 3D efekt özelliklerini içeren ThreeDFormat nesnesini döndürür. Not: 3D özellikleri olmayan bazı şekil türleri için null döndürebilir. Salt-okunur [IThreeDFormat](../../com.aspose.slides/ithreedformat).

**Döndürür:**
[IThreeDFormat](../../com.aspose.slides/ithreedformat)

### getEffectFormat() {#getEffectFormat--}
```
public IEffectFormat getEffectFormat()
```

Bir şekle uygulanan piksel efektlerini içeren EffectFormat nesnesini döndürür. Not: Efekt özellikleri olmayan bazı şekil türleri için null döndürebilir. Salt-okunur [IEffectFormat](../../com.aspose.slides/ieffectformat).

**Döndürür:**
[IEffectFormat](../../com.aspose.slides/ieffectformat)

### getFillFormat() {#getFillFormat--}
```
public IFillFormat getFillFormat()
```

Bir şekil için doldurma biçimlendirme özelliklerini içeren FillFormat nesnesini döndürür. Not: Doldurma özellikleri olmayan bazı şekil türleri için null döndürebilir. Salt-okunur [IFillFormat](../../com.aspose.slides/ifillformat).

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

Şeklin küçük resmini döndürür. Varsayılan olarak ShapeThumbnailBounds.Shape şekil küçük resmi sınır tipi kullanılır.

**Döndürür:**
[IImage](../../com.aspose.slides/iimage) - Shape thumbnail.

### getImage(int bounds, float scaleX, float scaleY) {#getImage-int-float-float-}
```
public final IImage getImage(int bounds, float scaleX, float scaleY)
```

Şeklin küçük resmini döndürür.

**Parametreler:**
| Parametre | Tip | Açıklama |
| --- | --- | --- |
| bounds | int | Şekil küçük resmi sınır tipi. |
| scaleX | float | X ölçeği |
| scaleY | float | Y ölçeği |

**Döndürür:**
[IImage](../../com.aspose.slides/iimage) - Shape thumbnail or null in case when ShapeThumbnailBounds.Appearance is used and a shape doesn't have visible elements.

### writeAsSvg(OutputStream stream) {#writeAsSvg-java.io.OutputStream-}
```
public final void writeAsSvg(OutputStream stream)
```

Şeklin içeriğini SVG dosyası olarak kaydeder.

**Parametreler:**
| Parametre | Tip | Açıklama |
| --- | --- | --- |
| stream | java.io.OutputStream | Hedef akış |

### writeAsSvg(OutputStream stream, ISVGOptions svgOptions) {#writeAsSvg-java.io.OutputStream-com.aspose.slides.ISVGOptions-}
```
public final void writeAsSvg(OutputStream stream, ISVGOptions svgOptions)
```

Şeklin içeriğini SVG dosyası olarak kaydeder.

**Parametreler:**
| Parametre | Tip | Açıklama |
| --- | --- | --- |
| stream | java.io.OutputStream | Hedef akış |
| svgOptions | [ISVGOptions](../../com.aspose.slides/isvgoptions) | SVG oluşturma seçenekleri |

### getHyperlinkClick() {#getHyperlinkClick--}
```
public final IHyperlink getHyperlinkClick()
```

Fare tıklaması için tanımlanmış köprüyü döndürür veya ayarlar. Okunur/yazılabilir [IHyperlink](../../com.aspose.slides/ihyperlink).

**Döndürür:**
[IHyperlink](../../com.aspose.slides/ihyperlink)

### setHyperlinkClick(IHyperlink value) {#setHyperlinkClick-com.aspose.slides.IHyperlink-}
```
public final void setHyperlinkClick(IHyperlink value)
```

Fare tıklaması için tanımlanmış köprüyü döndürür veya ayarlar. Okunur/yazılabilir [IHyperlink](../../com.aspose.slides/ihyperlink).

**Parametreler:**
| Parametre | Tip | Açıklama |
| --- | --- | --- |
| value | [IHyperlink](../../com.aspose.slides/ihyperlink) |  |

### getHyperlinkMouseOver() {#getHyperlinkMouseOver--}
```
public final IHyperlink getHyperlinkMouseOver()
```

Fare üzerine gelindiğinde tanımlanmış köprüyü döndürür veya ayarlar. Okunur/yazılabilir [IHyperlink](../../com.aspose.slides/ihyperlink).

**Döndürür:**
[IHyperlink](../../com.aspose.slides/ihyperlink)

### setHyperlinkMouseOver(IHyperlink value) {#setHyperlinkMouseOver-com.aspose.slides.IHyperlink-}
```
public final void setHyperlinkMouseOver(IHyperlink value)
```

Fare üzerine gelindiğinde tanımlanmış köprüyü döndürür veya ayarlar. Okunur/yazılabilir [IHyperlink](../../com.aspose.slides/ihyperlink).

**Parametreler:**
| Parametre | Tip | Açıklama |
| --- | --- | --- |
| value | [IHyperlink](../../com.aspose.slides/ihyperlink) |  |

### getHyperlinkManager() {#getHyperlinkManager--}
```
public final IHyperlinkManager getHyperlinkManager()
```

Köprü yöneticisini döndürür. Salt-okunur [IHyperlinkManager](../../com.aspose.slides/ihyperlinkmanager).

**Döndürür:**
[IHyperlinkManager](../../com.aspose.slides/ihyperlinkmanager)

### getHidden() {#getHidden--}
```
public final boolean getHidden()
```

Şeklin gizli olup olmadığını belirler. Okunur/yazılabilir boolean .

**Döndürür:**
boolean

### setHidden(boolean value) {#setHidden-boolean-}
```
public final void setHidden(boolean value)
```

Şeklin gizli olup olmadığını belirler. Okunur/yazılabilir boolean .

**Parametreler:**
| Parametre | Tip | Açıklama |
| --- | --- | --- |
| value | boolean |  |

### getZOrderPosition() {#getZOrderPosition--}
```
public int getZOrderPosition()
```

Bir şeklin z-sırasındaki konumunu döndürür. Shapes[0] z-sırasının arkasındaki şekli, Shapes[Shapes.Count - 1] ise önündeki şekli döndürür. Salt-okunur int .

**Döndürür:**
int

### getConnectionSiteCount() {#getConnectionSiteCount--}
```
public final int getConnectionSiteCount()
```

Şeklin bağlantı noktalarının sayısını döndürür. Salt-okunur int .

**Döndürür:**
int

### getRotation() {#getRotation--}
```
public final float getRotation()
```

Belirtilen şeklin z ekseni etrafında döndürüldüğü derece sayısını döndürür veya ayarlar. Pozitif değer saat yönünde dönüş, negatif değer saat yönünün tersine dönüş anlamına gelir. Okunur/yazılabilir float.

--------------------

Dönen değer her zaman tanımlıdır (Float.NaN değildir). Atanan değer tanımlı olmalıdır (Float.NaN olmamalıdır). RawFrame örnek özellikleri için tanımsız değerler ayarlayabilirsiniz.

**Döndürür:**
float

### setRotation(float value) {#setRotation-float-}
```
public final void setRotation(float value)
```

Belirtilen şeklin z ekseni etrafında döndürüldüğü derece sayısını döndürür veya ayarlar. Pozitif değer saat yönünde dönüş, negatif değer saat yönünün tersine dönüş anlamına gelir. Okunur/yazılabilir float.

--------------------

Dönen değer her zaman tanımlıdır (Float.NaN değildir). Atanan değer tanımlı olmalıdır (Float.NaN olmamalıdır). RawFrame örnek özellikleri için tanımsız değerler ayarlayabilirsiniz.

**Parametreler:**
| Parametre | Tip | Açıklama |
| --- | --- | --- |
| value | float |  |

### getX() {#getX--}
```
public final float getX()
```

Şeklin sol üst köşesinin x koordinatını (point cinsinden) alır veya ayarlar. Okunur/yazılabilir float.

--------------------

Dönen değer her zaman tanımlıdır ve hiçbir zaman Float.NaN değildir. Atanan değer de tanımlı olmalıdır; Float.NaN yalnızca RawFrame örnek özelliklerine atanabilir.

**Döndürür:**
float

### setX(float value) {#setX-float-}
```
public final void setX(float value)
```

Şeklin sol üst köşesinin x koordinatını (point cinsinden) alır veya ayarlar. Okunur/yazılabilir float.

--------------------

Dönen değer her zaman tanımlıdır ve hiçbir zaman Float.NaN değildir. Atanan değer de tanımlı olmalıdır; Float.NaN yalnızca RawFrame örnek özelliklerine atanabilir.

**Parametreler:**
| Parametre | Tip | Açıklama |
| --- | --- | --- |
| value | float |  |

### getY() {#getY--}
```
public final float getY()
```

Şeklin sol üst köşesinin y koordinatını (point cinsinden) alır veya ayarlar. Okunur/yazılabilir float.

--------------------

Dönen değer her zaman tanımlıdır ve hiçbir zaman Float.NaN değildir. Atanan değer de tanımlı olmalıdır; Float.NaN yalnızca RawFrame örnek özelliklerine atanabilir.

**Döndürür:**
float

### setY(float value) {#setY-float-}
```
public final void setY(float value)
```

Şeklin sol üst köşesinin y koordinatını (point cinsinden) alır veya ayarlar. Okunur/yazılabilir float.

--------------------

Dönen değer her zaman tanımlıdır ve hiçbir zaman Float.NaN değildir. Atanan değer de tanımlı olmalıdır; Float.NaN yalnızca RawFrame örnek özelliklerine atanabilir.

**Parametreler:**
| Parametre | Tip | Açıklama |
| --- | --- | --- |
| value | float |  |

### getWidth() {#getWidth--}
```
public final float getWidth()
```

Şeklin genişliğini (point cinsinden) alır veya ayarlar. Okunur/yazılabilir float.

--------------------

Dönen değer her zaman tanımlıdır ve hiçbir zaman Float.NaN değildir. Atanan değer de tanımlı olmalıdır; Float.NaN yalnızca RawFrame örnek özelliklerine atanabilir.

**Döndürür:**
float

### setWidth(float value) {#setWidth-float-}
```
public final void setWidth(float value)
```

Şeklin genişliğini (point cinsinden) alır veya ayarlar. Okunur/yazılabilir float.

--------------------

Dönen değer her zaman tanımlıdır ve hiçbir zaman Float.NaN değildir. Atanan değer de tanımlı olmalıdır; Float.NaN yalnızca RawFrame örnek özelliklerine atanabilir.

**Parametreler:**
| Parametre | Tip | Açıklama |
| --- | --- | --- |
| value | float |  |

### getHeight() {#getHeight--}
```
public final float getHeight()
```

Şeklin yüksekliğini (point cinsinden) alır veya ayarlar. Okunur/yazılabilir float.

--------------------

Dönen değer her zaman tanımlıdır ve hiçbir zaman Float.NaN değildir. Atanan değer de tanımlı olmalıdır; Float.NaN yalnızca RawFrame örnek özelliklerine atanabilir.

**Döndürür:**
float

### setHeight(float value) {#setHeight-float-}
```
public final void setHeight(float value)
```

Şeklin yüksekliğini (point cinsinden) alır veya ayarlar. Okunur/yazılabilir float.

--------------------

Dönen değer her zaman tanımlıdır ve hiçbir zaman Float.NaN değildir. Atanan değer de tanımlı olmalıdır; Float.NaN yalnızca RawFrame örnek özelliklerine atanabilir.

**Parametreler:**
| Parametre | Tip | Açıklama |
| --- | --- | --- |
| value | float |  |

### getBlackWhiteMode() {#getBlackWhiteMode--}
```
public final byte getBlackWhiteMode()
```

Özellik, bir şeklin siyah-beyaz görüntü modunda nasıl render edileceğini belirtir. Okunur/yazılabilir [BlackWhiteMode](../../com.aspose.slides/blackwhitemode).

**Döndürür:**
byte

### setBlackWhiteMode(byte value) {#setBlackWhiteMode-byte-}
```
public final void setBlackWhiteMode(byte value)
```

Özellik, bir şeklin siyah-beyaz görüntü modunda nasıl render edileceğini belirtir. Okunur/yazılabilir [BlackWhiteMode](../../com.aspose.slides/blackwhitemode).

**Parametreler:**
| Parametre | Tip | Açıklama |
| --- | --- | --- |
| value | byte |  |

### getUniqueId() {#getUniqueId--}
```
public final long getUniqueId()
```

Eklentiler veya diğer kodlar tarafından kullanılmak üzere tasarlanmış dahili, sunum kapsamlı bir tanımlayıcı döndürür. Bu değer kullanıcı veya program tarafından yeniden atanabileceği için kalıcı benzersiz bir anahtar olarak ele alınmamalıdır. Salt-okunur long. Ayrıca bakınız \#getOfficeInteropShapeId.getOfficeInteropShapeId.

**Döndürür:**
long

### getOfficeInteropShapeId() {#getOfficeInteropShapeId--}
```
public final long getOfficeInteropShapeId()
```

Bir slayt kapsamlı benzersiz tanımlayıcı döndürür; bu, şeklin ömrü boyunca sabit kalır ve PowerPoint ya da interop kodunun şekle belge içinde her yerden güvenilir şekilde başvurmasını sağlar. Salt-okunur long. Ayrıca bakınız \#getUniqueId.getUniqueId.

**Döndürür:**
long

### getAlternativeText() {#getAlternativeText--}
```
public final String getAlternativeText()
```

Bir şekille ilişkili alternatif metni döndürür veya ayarlar. Okunur/yazılabilir String.

**Döndürür:**
java.lang.String

### setAlternativeText(String value) {#setAlternativeText-java.lang.String-}
```
public final void setAlternativeText(String value)
```

Bir şekille ilişkili alternatif metni döndürür veya ayarlar. Okunur/yazılabilir String.

**Parametreler:**
| Parametre | Tip | Açıklama |
| --- | --- | --- |
| value | java.lang.String |  |

### getAlternativeTextTitle() {#getAlternativeTextTitle--}
```
public final String getAlternativeTextTitle()
```

Bir şekille ilişkili alternatif metnin başlığını döndürür veya ayarlar. Okunur/yazılabilir String.

**Döndürür:**
java.lang.String

### setAlternativeTextTitle(String value) {#setAlternativeTextTitle-java.lang.String-}
```
public final void setAlternativeTextTitle(String value)
```

Bir şekille ilişkili alternatif metnin başlığını döndürür veya ayarlar. Okunur/yazılabilir String.

**Parametreler:**
| Parametre | Tip | Açıklama |
| --- | --- | --- |
| value | java.lang.String |  |

### getName() {#getName--}
```
public final String getName()
```

Bir şeklin adını döndürür veya ayarlar. Null olmamalıdır. Gerekirse boş dize değeri kullanın. Okunur/yazılabilir String.

**Döndürür:**
java.lang.String

### setName(String value) {#setName-java.lang.String-}
```
public final void setName(String value)
```

Bir şeklin adını döndürür veya ayarlar. Null olmamalıdır. Gerekirse boş dize değeri kullanın. Okunur/yazılabilir String.

**Parametreler:**
| Parametre | Tip | Açıklama |
| --- | --- | --- |
| value | java.lang.String |  |

### isDecorative() {#isDecorative--}
```
public final boolean isDecorative()
```

‘Dekoratif olarak işaretle’ seçeneğini alır veya ayarlar. Okunur/yazılabilir boolean.

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
public final void setDecorative(boolean value)
```

‘Dekoratif olarak işaretle’ seçeneğini alır veya ayarlar. Okunur/yazılabilir boolean.

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

Şeklin kilitlerini döndürür. Salt-okunur [IBaseShapeLock](../../com.aspose.slides/ibaseshapelock).

**Döndürür:**
[IBaseShapeLock](../../com.aspose.slides/ibaseshapelock)

### isGrouped() {#isGrouped--}
```
public final boolean isGrouped()
```

Şeklin gruplanmış olup olmadığını belirler. Salt-okunur boolean.

--------------------

Özellik \#getParentGroup.getParentGroup, şekil gruplanmışsa üst GroupShape nesnesini döndürür.

**Döndürür:**
boolean

### getParentGroup() {#getParentGroup--}
```
public final IGroupShape getParentGroup()
```

Şekil gruplanmışsa üst GroupShape nesnesini döndürür. Aksi takdirde null döndürür. Salt-okunur [IGroupShape](../../com.aspose.slides/igroupshape).

--------------------

Özellik \#isGrouped.isGrouped, şeklin gruplanmış olup olmadığını belirler.

**Döndürür:**
[IGroupShape](../../com.aspose.slides/igroupshape)

### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```

Parent_Immediate nesnesini döndürür. Salt-okunur IDOMObject.

**Döndürür:**
com.aspose.slides.IDOMObject

### getVisualBounds() {#getVisualBounds--}
```
public final RectF getVisualBounds()
```

Şeklin render edilmiş içeriğinden hesaplanan görsel sınırlarını alır.

**Döndürür:**
android.graphics.RectF - Slayt koordinatlarında şeklin görsel sınırlarını temsil eden bir android.graphics.RectF.

--------------------

Dönen dikdörtgen, slayt koordinat alanında şekil tarafından render sırasında üretilen tüm içeriğin eksen-hizalı sınırlarını temsil eder. Bu sınırlar, şeklin model sınırları \#getX.getX/\#setX(float).setX(float), \#getY.getY/\#setY(float).setY(float), \#getWidth.getWidth/\#setWidth(float).setWidth(float), \#getHeight.getHeight/\#setHeight(float).setHeight(float) ile farklılık gösterebilir ve render edilen içerik slayt orijini dışına uzarsa negatif koordinatlar içerebilir. Görsel sınırlar, dönüşüm (örneğin, dönme), çizgi kalınlığı ve eklemeler, metin yerleşimi ve taşma, SmartArt geometrisi ve şeklin nihai render görünümünü etkileyen diğer yerleşim etkileri gibi render-ile ilgili yönleri dikkate alır. Dönen sınırlar slayt dikdörtgenine kırpılmaz.

### getSlide() {#getSlide--}
```
public final IBaseSlide getSlide()
```

Şeklin üst slaydını döndürür. Salt-okunur [IBaseSlide](../../com.aspose.slides/ibaseslide).

**Döndürür:**
[IBaseSlide](../../com.aspose.slides/ibaseslide)

### getPresentation() {#getPresentation--}
```
public final IPresentation getPresentation()
```

Bir slaydın üst sunumunu döndürür. Salt-okunur [IPresentation](../../com.aspose.slides/ipresentation).

**Döndürür:**
[IPresentation](../../com.aspose.slides/ipresentation)