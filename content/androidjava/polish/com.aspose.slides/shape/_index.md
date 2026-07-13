---
title: Shape
second_title: Aspose.Slides dla Androida poprzez odniesienie API Java
description: Reprezentuje kształt na slajdzie.
type: docs
url: /pl/com.aspose.slides/shape/
---
**Dziedziczenie:**
java.lang.Object

**Wszystkie zaimplementowane interfejsy:**
[com.aspose.slides.IShape](../../com.aspose.slides/ishape), com.aspose.slides.IDOMObject
```
public class Shape implements IShape, IDOMObject
```

Reprezentuje kształt na slajdzie.
## Metody

| Metoda | Opis |
| --- | --- |
| [isTextHolder()](#isTextHolder--) | Określa, czy kształt jest TextHolder_PPT. |
| [getPlaceholder()](#getPlaceholder--) | Zwraca placeholder dla kształtu. |
| [removePlaceholder()](#removePlaceholder--) | Określa, że ten kształt nie jest placeholderem. |
| [addPlaceholder(IPlaceholder placeholderToCopyFrom)](#addPlaceholder-com.aspose.slides.IPlaceholder-) | Dodaje nowy placeholder, jeśli go nie ma, i ustawia właściwości placeholdera na określone. |
| [getBasePlaceholder()](#getBasePlaceholder--) | Zwraca podstawowy kształt placeholdera (kształt z układu i/lub slajdu macierzystego, z którego dziedziczony jest bieżący kształt). |
| [getCustomData()](#getCustomData--) | Zwraca niestandardowe dane kształtu. |
| [getRawFrame()](#getRawFrame--) | Zwraca lub ustawia surowe właściwości ramki kształtu. |
| [setRawFrame(IShapeFrame value)](#setRawFrame-com.aspose.slides.IShapeFrame-) | Zwraca lub ustawia surowe właściwości ramki kształtu. |
| [getFrame()](#getFrame--) | Zwraca lub ustawia surowe właściwości ramki kształtu. |
| [setFrame(IShapeFrame value)](#setFrame-com.aspose.slides.IShapeFrame-) | Zwraca lub ustawia surowe właściwości ramki kształtu. |
| [getLineFormat()](#getLineFormat--) | Zwraca obiekt LineFormat zawierający właściwości formatowania linii dla kształtu. |
| [getThreeDFormat()](#getThreeDFormat--) | Zwraca obiekt ThreeDFormat zawierający właściwości efektu 3D dla kształtu. |
| [getEffectFormat()](#getEffectFormat--) | Zwraca obiekt EffectFormat, który zawiera efekty pikselowe zastosowane do kształtu. |
| [getFillFormat()](#getFillFormat--) | Zwraca obiekt FillFormat zawierający właściwości formatowania wypełnienia dla kształtu. |
| [getImage()](#getImage--) | Zwraca miniaturkę kształtu. |
| [getImage(int bounds, float scaleX, float scaleY)](#getImage-int-float-float-) | Zwraca miniaturkę kształtu. |
| [writeAsSvg(OutputStream stream)](#writeAsSvg-java.io.OutputStream-) | Zapisuje zawartość Shape jako plik SVG. |
| [writeAsSvg(OutputStream stream, ISVGOptions svgOptions)](#writeAsSvg-java.io.OutputStream-com.aspose.slides.ISVGOptions-) | Zapisuje zawartość Shape jako plik SVG. |
| [getHyperlinkClick()](#getHyperlinkClick--) | Zwraca lub ustawia hiperłącze zdefiniowane dla kliknięcia myszy. |
| [setHyperlinkClick(IHyperlink value)](#setHyperlinkClick-com.aspose.slides.IHyperlink-) | Zwraca lub ustawia hiperłącze zdefiniowane dla kliknięcia myszy. |
| [getHyperlinkMouseOver()](#getHyperlinkMouseOver--) | Zwraca lub ustawia hiperłącze zdefiniowane dla najechania myszą. |
| [setHyperlinkMouseOver(IHyperlink value)](#setHyperlinkMouseOver-com.aspose.slides.IHyperlink-) | Zwraca lub ustawia hiperłącze zdefiniowane dla najechania myszą. |
| [getHyperlinkManager()](#getHyperlinkManager--) | Zwraca menedżer hiperłączy. |
| [getHidden()](#getHidden--) | Określa, czy kształt jest ukryty. |
| [setHidden(boolean value)](#setHidden-boolean-) | Określa, czy kształt jest ukryty. |
| [getZOrderPosition()](#getZOrderPosition--) | Zwraca pozycję kształtu w kolejności Z. |
| [getConnectionSiteCount()](#getConnectionSiteCount--) | Zwraca liczbę miejsc połączeń na kształcie. |
| [getRotation()](#getRotation--) | Zwraca lub ustawia liczbę stopni, o które określony kształt jest obrócony wokół osi Z. |
| [setRotation(float value)](#setRotation-float-) | Zwraca lub ustawia liczbę stopni, o które określony kształt jest obrócony wokół osi Z. |
| [getX()](#getX--) | Pobiera lub ustawia współrzędną x lewego górnego rogu kształtu, mierzoną w punktach. |
| [setX(float value)](#setX-float-) | Pobiera lub ustawia współrzędną x lewego górnego rogu kształtu, mierzoną w punktach. |
| [getY()](#getY--) | Pobiera lub ustawia współrzędną y lewego górnego rogu kształtu, mierzoną w punktach. |
| [setY(float value)](#setY-float-) | Pobiera lub ustawia współrzędną y lewego górnego rogu kształtu, mierzoną w punktach. |
| [getWidth()](#getWidth--) | Pobiera lub ustawia szerokość kształtu, mierzoną w punktach. |
| [setWidth(float value)](#setWidth-float-) | Pobiera lub ustawia szerokość kształtu, mierzoną w punktach. |
| [getHeight()](#getHeight--) | Pobiera lub ustawia wysokość kształtu, mierzoną w punktach. |
| [setHeight(float value)](#setHeight-float-) | Pobiera lub ustawia wysokość kształtu, mierzoną w punktach. |
| [getBlackWhiteMode()](#getBlackWhiteMode--) | Właściwość określa, jak kształt będzie renderowany w trybie czarno-białym. |
| [setBlackWhiteMode(byte value)](#setBlackWhiteMode-byte-) | Właściwość określa, jak kształt będzie renderowany w trybie czarno-białym. |
| [getUniqueId()](#getUniqueId--) | Zwraca wewnętrzny, zakresowy identyfikator prezentacji przeznaczony do użycia przez dodatki lub inny kod. |
| [getOfficeInteropShapeId()](#getOfficeInteropShapeId--) | Zwraca unikalny identyfikator zakresu slajdu, który pozostaje stały przez całe życie kształtu i pozwala PowerPointowi lub kodowi interop na niezawodne odwoływanie się do kształtu z dowolnego miejsca w dokumencie. |
| [getAlternativeText()](#getAlternativeText--) | Zwraca lub ustawia tekst alternatywny powiązany z kształtem. |
| [setAlternativeText(String value)](#setAlternativeText-java.lang.String-) | Zwraca lub ustawia tekst alternatywny powiązany z kształtem. |
| [getAlternativeTextTitle()](#getAlternativeTextTitle--) | Zwraca lub ustawia tytuł tekstu alternatywnego powiązanego z kształtem. |
| [setAlternativeTextTitle(String value)](#setAlternativeTextTitle-java.lang.String-) | Zwraca lub ustawia tytuł tekstu alternatywnego powiązanego z kształtem. |
| [getName()](#getName--) | Zwraca lub ustawia nazwę kształtu. |
| [setName(String value)](#setName-java.lang.String-) | Zwraca lub ustawia nazwę kształtu. |
| [isDecorative()](#isDecorative--) | Pobiera lub ustawia opcję 'Oznacz jako dekoracyjne' (boolean odczyt/zapis). |
| [setDecorative(boolean value)](#setDecorative-boolean-) | Pobiera lub ustawia opcję 'Oznacz jako dekoracyjne' (boolean odczyt/zapis). |
| [getShapeLock()](#getShapeLock--) | Zwraca blokady kształtu. |
| [isGrouped()](#isGrouped--) | Określa, czy kształt jest grupowany. |
| [getParentGroup()](#getParentGroup--) | Zwraca obiekt GroupShape nadrzędny, jeśli kształt jest grupowany. |
| [getParent_Immediate()](#getParent-Immediate--) |  |
| [getVisualBounds()](#getVisualBounds--) | Pobiera wizualne granice kształtu obliczone na podstawie jego renderowanej treści. |
| [getSlide()](#getSlide--) | Zwraca slajd nadrzędny kształtu. |
| [getPresentation()](#getPresentation--) | Zwraca prezentację nadrzędną slajdu. |

### isTextHolder() {#isTextHolder--}
```
public final boolean isTextHolder()
```

Określa, czy kształt jest TextHolder_PPT. Tylko do odczytu boolean.

**Zwraca:**
boolean

### getPlaceholder() {#getPlaceholder--}
```
public final IPlaceholder getPlaceholder()
```

Zwraca placeholder dla kształtu. Zwraca null, jeśli kształt nie ma placeholdera. Tylko do odczytu [IPlaceholder](../../com.aspose.slides/iplaceholder).

--------------------

> ```
> The following example shows how to change Text in Placeholder.
>  
>  // Tworzy instancję klasy Presentation
>  Presentation pres = new Presentation("ReplacingText.pptx");
>  try {
>      // Uzyskuje dostęp do pierwszego slajdu
>      ISlide sld = pres.getSlides().get_Item(0);
>      // Iteruje przez kształty, aby znaleźć placeholder
>      for (IShape shp : sld.getShapes())
>          if (shp.getPlaceholder() != null)
>          {
>              // Zmienia tekst w każdym placeholderze
>              ((IAutoShape)shp).getTextFrame().setText("This is a Placeholder");
>          }
>      // Zapisuje prezentację na dysku
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
>      for (IShape shape : slide.getSlide().getShapes()) // Iteruje przez slajd
>      {
>          if (shape.getPlaceholder() != null && shape instanceof AutoShape)
>          {
>              String text = "";
>              if (shape.getPlaceholder().getType() == PlaceholderType.CenteredTitle) // PowerPoint wyświetla "Click to add title"
>              {
>                  text = "Add Title";
>              }
>              else if (shape.getPlaceholder().getType() == PlaceholderType.Subtitle) // Dodaje podtytuł
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


**Zwraca:**
[IPlaceholder](../../com.aspose.slides/iplaceholder)

### removePlaceholder() {#removePlaceholder--}
```
public final void removePlaceholder()
```

Określa, że ten kształt nie jest placeholderem.

### addPlaceholder(IPlaceholder placeholderToCopyFrom) {#addPlaceholder-com.aspose.slides.IPlaceholder-}
```
public final IPlaceholder addPlaceholder(IPlaceholder placeholderToCopyFrom)
```

Dodaje nowy placeholder, jeśli go nie ma, i ustawia właściwości placeholdera na określone.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| placeholderToCopyFrom | [IPlaceholder](../../com.aspose.slides/iplaceholder) | Placeholder, z którego kopiować zawartość. |

**Zwraca:**
[IPlaceholder](../../com.aspose.slides/iplaceholder) - New #getPlaceholder.getPlaceholder.

### getBasePlaceholder() {#getBasePlaceholder--}
```
public final IShape getBasePlaceholder()
```

Zwraca podstawowy kształt placeholdera (kształt z układu i/lub slajdu macierzystego, z którego dziedziczony jest bieżący kształt).

--------------------

> ```
> // pobierz wszystkie (master/layout/slide) animowane efekty placeholdera
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

Zwraca null, jeśli bieżący kształt nie jest dziedziczony.

**Zwraca:**
[IShape](../../com.aspose.slides/ishape)

### getCustomData() {#getCustomData--}
```
public final ICustomData getCustomData()
```

Zwraca niestandardowe dane kształtu. Tylko do odczytu [ICustomData](../../com.aspose.slides/icustomdata).

**Zwraca:**
[ICustomData](../../com.aspose.slides/icustomdata)

### getRawFrame() {#getRawFrame--}
```
public final IShapeFrame getRawFrame()
```

Zwraca lub ustawia surowe właściwości ramki kształtu. Odczyt/zapis [IShapeFrame](../../com.aspose.slides/ishapeframe).

--------------------

> ```
> // pobierz wszystkie (master/layout/slide) animowane efekty placeholdera
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
> 
> //lub
>  //Taki kod może prowadzić do niejasnych sytuacji. Dlatego wprowadzono ograniczenia dotyczące używania niezdefiniowanych wartości dla IShape.getFrame(). Wartości x, y, width, height, flipH, flipV i rotationAngle muszą być określone (nie Float.NaN ani NullableBool.NotDefined). Powyższy przykład kodu teraz zgłasza wyjątek ArgumentException.
>  //Obowiązuje to w następujących przypadkach:
>  // parametry x, y, width, height nie mogą być Float.NaN:
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
>  //Jednak właściwości ramki IShape.RawFrame mogą być niezdefiniowane. Ma to sens, gdy kształt jest powiązany z placeholderem. Wtedy niezdefiniowane wartości ramki kształtu są zastępowane przez wartości z kształtu placeholdera nadrzędnego. Jeśli nie ma takiego placeholdera, kształt używa wartości domyślnych przy obliczaniu efektywnej ramki na podstawie swojego IShape.RawFrame. Domyślne wartości to 0 i NullableBool.False dla x, y, width, height, flipH, flipV i rotationAngle. Na przykład:
>  IShape shape = ...; // kształt jest powiązany z placeholderem
>  shape.setRawFrame(new ShapeFrame(Float.NaN, Float.NaN, 100, Float.NaN, NullableBool.NotDefined, NullableBool.NotDefined, 0)); // teraz kształt dziedziczy wartości x, y, height, flipH, flipV z placeholdera i nadpisuje width=100 oraz rotationAngle=0.{code}
> ```


**Zwraca:**
[IShapeFrame](../../com.aspose.slides/ishapeframe)

### setRawFrame(IShapeFrame value) {#setRawFrame-com.aspose.slides.IShapeFrame-}
```
public final void setRawFrame(IShapeFrame value)
```

Zwraca lub ustawia surowe właściwości ramki kształtu. Odczyt/zapis [IShapeFrame](../../com.aspose.slides/ishapeframe).

--------------------

> ```
> Code that attempts to assign undefined frame to IShape.getFrame() doesn't make sense in general case (particularly in case when parent GroupShape is multiple nested into other GroupShape-s). For example:
>  
>  IShape shape = ...;
>  shape.setFrame(new ShapeFrame(Float.NaN, Float.NaN, Float.NaN, Float.NaN, NullableBool.NotDefined, NullableBool.NotDefined, Float.NaN));
>  //or
>  slide.getShapes().addAutoShape(ShapeType.RoundCornerRectangle, Float.NaN, Float.NaN, Float.NaN, Float.NaN);
>  //Such code can lead to unclear situations. So restrictions had been added for using undefined values for IShape.getFrame(). Values of x, y, width, height, flipH, flipV and rotationAngle must be defined (not Float.NaN or NullableBool.NotDefined). Example code above now throws ArgumentException exception.
>  //This applies to these use cases:
>  IShape shape = ...;
>  shape.setFrame(...); // cannot be undefined
>  IShapeCollection shapes = ...;
>  // x, y, width, height parameters cannot be Float.NaN:
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
>  //But IShape.RawFrame frame properties can be undefined. This make sence when shape is linked to placeholder. Then undefined shape frame values is overridden from the parent placeholder shape. If there is no parent placeholder shape for that shape then that shape uses default values when it evaluates effective frame based on its IShape.RawFrame. Default values are 0 and NullableBool.False for x, y, width, height, flipH, flipV and rotationAngle. For example:
>  IShape shape = ...; // shape is linked to placeholder
>  shape.setRawFrame(new ShapeFrame(Float.NaN, Float.NaN, 100, Float.NaN, NullableBool.NotDefined, NullableBool.NotDefined, 0)); // now shape inherits x, y, height, flipH, flipV values form placeholder and overrides width=100 and rotationAngle=0.{code}
> ```

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | [IShapeFrame](../../com.aspose.slides/ishapeframe) |  |

### getFrame() {#getFrame--}
```
public final IShapeFrame getFrame()
```

Zwraca lub ustawia właściwości ramki kształtu. Odczyt/zapis [IShapeFrame](../../com.aspose.slides/ishapeframe).

--------------------

Wartość każdej właściwości zwróconego obiektu IShapeFrame nie jest niezdefiniowana (nie jest NaN ani NotDefined). Wartość każdej właściwości przypisanego obiektu IShapeFrame musi nie być niezdefiniowana (nie może być NaN ani NotDefined). Można ustawiać niezdefiniowane wartości dla właściwości instancji RawFrame.

**Zwraca:**
[IShapeFrame](../../com.aspose.slides/ishapeframe)

### setFrame(IShapeFrame value) {#setFrame-com.aspose.slides.IShapeFrame-}
```
public final void setFrame(IShapeFrame value)
```

Zwraca lub ustawia właściwości ramki kształtu. Odczyt/zapis [IShapeFrame](../../com.aspose.slides/ishapeframe).

--------------------

Wartość każdej właściwości zwróconego obiektu IShapeFrame nie jest niezdefiniowana (nie jest NaN ani NotDefined). Wartość każdej właściwości przypisanego obiektu IShapeFrame musi nie być niezdefiniowana (nie może być NaN ani NotDefined). Można ustawiać niezdefiniowane wartości dla właściwości instancji RawFrame.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | [IShapeFrame](../../com.aspose.slides/ishapeframe) |  |

### getLineFormat() {#getLineFormat--}
```
public ILineFormat getLineFormat()
```

Zwraca obiekt LineFormat zawierający właściwości formatowania linii dla kształtu. Uwaga: może zwrócić null dla niektórych typów kształtów, które nie mają właściwości linii. Tylko do odczytu [ILineFormat](../../com.aspose.slides/ilineformat).

**Zwraca:**
[ILineFormat](../../com.aspose.slides/ilineformat)

### getThreeDFormat() {#getThreeDFormat--}
```
public IThreeDFormat getThreeDFormat()
```

Zwraca obiekt ThreeDFormat zawierający właściwości efektu 3D dla kształtu. Uwaga: może zwrócić null dla niektórych typów kształtów, które nie mają właściwości 3D. Tylko do odczytu [IThreeDFormat](../../com.aspose.slides/ithreedformat).

**Zwraca:**
[IThreeDFormat](../../com.aspose.slides/ithreedformat)

### getEffectFormat() {#getEffectFormat--}
```
public IEffectFormat getEffectFormat()
```

Zwraca obiekt EffectFormat, który zawiera efekty pikselowe zastosowane do kształtu. Uwaga: może zwrócić null dla niektórych typów kształtów, które nie mają właściwości efektu. Tylko do odczytu [IEffectFormat](../../com.aspose.slides/ieffectformat).

**Zwraca:**
[IEffectFormat](../../com.aspose.slides/ieffectformat)

### getFillFormat() {#getFillFormat--}
```
public IFillFormat getFillFormat()
```

Zwraca obiekt FillFormat zawierający właściwości formatowania wypełnienia dla kształtu. Uwaga: może zwrócić null dla niektórych typów kształtów, które nie mają właściwości wypełnienia. Tylko do odczytu [IFillFormat](../../com.aspose.slides/ifillformat).

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
>      // Akcent 4
>      IShape shape1 = slide.getShapes().addAutoShape(ShapeType.Rectangle, 10, 10, 50, 50);
>      shape1.getFillFormat().setFillType(FillType.Solid);
>      shape1.getFillFormat().getSolidFillColor().setSchemeColor(SchemeColor.Accent4);
>      // Akcent 4, jaśniejszy 80%
>      IShape shape2 = slide.getShapes().addAutoShape(ShapeType.Rectangle, 10, 70, 50, 50);
>      shape2.getFillFormat().setFillType(FillType.Solid);
>      shape2.getFillFormat().getSolidFillColor().setSchemeColor(SchemeColor.Accent4);
>      shape2.getFillFormat().getSolidFillColor().getColorTransform().add(ColorTransformOperation.MultiplyLuminance, 0.2f);
>      shape2.getFillFormat().getSolidFillColor().getColorTransform().add(ColorTransformOperation.AddLuminance, 0.8f);
>      // Akcent 4, jaśniejszy 60%
>      IShape shape3 = slide.getShapes().addAutoShape(ShapeType.Rectangle, 10, 130, 50, 50);
>      shape3.getFillFormat().setFillType(FillType.Solid);
>      shape3.getFillFormat().getSolidFillColor().setSchemeColor(SchemeColor.Accent4);
>      shape3.getFillFormat().getSolidFillColor().getColorTransform().add(ColorTransformOperation.MultiplyLuminance, 0.4f);
>      shape3.getFillFormat().getSolidFillColor().getColorTransform().add(ColorTransformOperation.AddLuminance, 0.6f);
>      // Akcent 4, jaśniejszy 40%
>      IShape shape4 = slide.getShapes().addAutoShape(ShapeType.Rectangle, 10, 190, 50, 50);
>      shape4.getFillFormat().setFillType(FillType.Solid);
>      shape4.getFillFormat().getSolidFillColor().setSchemeColor(SchemeColor.Accent4);
>      shape4.getFillFormat().getSolidFillColor().getColorTransform().add(ColorTransformOperation.MultiplyLuminance, 0.6f);
>      shape4.getFillFormat().getSolidFillColor().getColorTransform().add(ColorTransformOperation.AddLuminance, 0.4f);
>      // Akcent 4, ciemniejszy 25%
>      IShape shape5 = slide.getShapes().addAutoShape(ShapeType.Rectangle, 10, 250, 50, 50);
>      shape5.getFillFormat().setFillType(FillType.Solid);
>      shape5.getFillFormat().getSolidFillColor().setSchemeColor(SchemeColor.Accent4);
>      shape5.getFillFormat().getSolidFillColor().getColorTransform().add(ColorTransformOperation.MultiplyLuminance, 0.75f);
>      // Akcent 4, ciemniejszy 50%
>      IShape shape6 = slide.getShapes().addAutoShape(ShapeType.Rectangle, 10, 310, 50, 50);
>      shape6.getFillFormat().setFillType(FillType.Solid);
>      shape6.getFillFormat().getSolidFillColor().setSchemeColor(SchemeColor.Accent4);
>      shape6.getFillFormat().getSolidFillColor().getColorTransform().add(ColorTransformOperation.MultiplyLuminance, 0.5f);
>      pres.save("example_accent4.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Zwraca:**
[IFillFormat](../../com.aspose.slides/ifillformat)

### getImage() {#getImage--}
```
public final IImage getImage()
```

Zwraca miniaturkę kształtu. ShapeThumbnailBounds.Shape shape thumbnail bounds type jest używany domyślnie.

**Zwraca:**
[IImage](../../com.aspose.slides/iimage) - Miniaturka kształtu.

### getImage(int bounds, float scaleX, float scaleY) {#getImage-int-float-float-}
```
public final IImage getImage(int bounds, float scaleX, float scaleY)
```

Zwraca miniaturkę kształtu.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| bounds | int | Typ granic miniaturki kształtu. |
| scaleX | float | Skala X |
| scaleY | float | Skala Y |

**Zwraca:**
[IImage](../../com.aspose.slides/iimage) - Miniatura kształtu lub null w przypadku, gdy użyto ShapeThumbnailBounds.Appearance i kształt nie ma widocznych elementów.

### writeAsSvg(OutputStream stream) {#writeAsSvg-java.io.OutputStream-}
```
public final void writeAsSvg(OutputStream stream)
```

Zapisuje zawartość Shape jako plik SVG.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| stream | java.io.OutputStream | Strumień docelowy |

### writeAsSvg(OutputStream stream, ISVGOptions svgOptions) {#writeAsSvg-java.io.OutputStream-com.aspose.slides.ISVGOptions-}
```
public final void writeAsSvg(OutputStream stream, ISVGOptions svgOptions)
```

Zapisuje zawartość Shape jako plik SVG.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| stream | java.io.OutputStream | Strumień docelowy |
| svgOptions | [ISVGOptions](../../com.aspose.slides/isvgoptions) | Opcje generowania SVG |

### getHyperlinkClick() {#getHyperlinkClick--}
```
public final IHyperlink getHyperlinkClick()
```

Zwraca lub ustawia hiperłącze zdefiniowane dla kliknięcia myszy. Odczyt/zapis [IHyperlink](../../com.aspose.slides/ihyperlink).

**Zwraca:**
[IHyperlink](../../com.aspose.slides/ihyperlink)

### setHyperlinkClick(IHyperlink value) {#setHyperlinkClick-com.aspose.slides.IHyperlink-}
```
public final void setHyperlinkClick(IHyperlink value)
```

Zwraca lub ustawia hiperłącze zdefiniowane dla kliknięcia myszy. Odczyt/zapis [IHyperlink](../../com.aspose.slides/ihyperlink).

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | [IHyperlink](../../com.aspose.slides/ihyperlink) |  |

### getHyperlinkMouseOver() {#getHyperlinkMouseOver--}
```
public final IHyperlink getHyperlinkMouseOver()
```

Zwraca lub ustawia hiperłącze zdefiniowane dla najechania myszą. Odczyt/zapis [IHyperlink](../../com.aspose.slides/ihyperlink).

**Zwraca:**
[IHyperlink](../../com.aspose.slides/ihyperlink)

### setHyperlinkMouseOver(IHyperlink value) {#setHyperlinkMouseOver-com.aspose.slides.IHyperlink-}
```
public final void setHyperlinkMouseOver(IHyperlink value)
```

Zwraca lub ustawia hiperłącze zdefiniowane dla najechania myszą. Odczyt/zapis [IHyperlink](../../com.aspose.slides/ihyperlink).

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | [IHyperlink](../../com.aspose.slides/ihyperlink) |  |

### getHyperlinkManager() {#getHyperlinkManager--}
```
public final IHyperlinkManager getHyperlinkManager()
```

Zwraca menedżer hiperłączy. Tylko do odczytu [IHyperlinkManager](../../com.aspose.slides/ihyperlinkmanager).

**Zwraca:**
[IHyperlinkManager](../../com.aspose.slides/ihyperlinkmanager)

### getHidden() {#getHidden--}
```
public final boolean getHidden()
```

Określa, czy kształt jest ukryty. Odczyt/zapis boolean.

**Zwraca:**
boolean

### setHidden(boolean value) {#setHidden-boolean-}
```
public final void setHidden(boolean value)
```

Określa, czy kształt jest ukryty. Odczyt/zapis boolean.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | boolean |  |

### getZOrderPosition() {#getZOrderPosition--}
```
public int getZOrderPosition()
```

Zwraca pozycję kształtu w kolejności Z. Shapes[0] zwraca kształt z tyłu kolejności Z, a Shapes[Shapes.Count - 1] zwraca kształt z przodu kolejności Z. Tylko do odczytu int.

**Zwraca:**
int

### getConnectionSiteCount() {#getConnectionSiteCount--}
```
public final int getConnectionSiteCount()
```

Zwraca liczbę miejsc połączeń na kształcie. Tylko do odczytu int.

**Zwraca:**
int

### getRotation() {#getRotation--}
```
public final float getRotation()
```

Zwraca lub ustawia liczbę stopni, o które określony kształt jest obrócony wokół osi Z. Wartość dodatnia oznacza obrót zgodny z ruchem wskazówek zegara; wartość ujemna – przeciwny. Odczyt/zapis float.

--------------------

Zwracana wartość jest zawsze określona (nie jest Float.NaN). Przypisana wartość musi być określona (nie Float.NaN). Można ustawiać niezdefiniowane wartości dla właściwości instancji RawFrame.

**Zwraca:**
float

### setRotation(float value) {#setRotation-float-}
```
public final void setRotation(float value)
```

Zwraca lub ustawia liczbę stopni, o które określony kształt jest obrócony wokół osi Z. Wartość dodatnia oznacza obrót zgodny z ruchem wskazówek zegara; wartość ujemna – przeciwny. Odczyt/zapis float.

--------------------

Zwracana wartość jest zawsze określona (nie jest Float.NaN). Przypisana wartość musi być określona (nie Float.NaN). Można ustawiać niezdefiniowane wartości dla właściwości instancji RawFrame.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | float |  |

### getX() {#getX--}
```
public final float getX()
```

Pobiera lub ustawia współrzędną x lewego górnego rogu kształtu, mierzoną w punktach. Odczyt/zapis float.

--------------------

Wartość zwracana jest zawsze określona i nigdy nie jest Float.NaN. Wartość przypisana musi być określona; przypisz Float.NaN tylko właściwościom instancji RawFrame.

**Zwraca:**
float

### setX(float value) {#setX-float-}
```
public final void setX(float value)
```

Pobiera lub ustawia współrzędną x lewego górnego rogu kształtu, mierzoną w punktach. Odczyt/zapis float.

--------------------

Wartość zwracana jest zawsze określona i nigdy nie jest Float.NaN. Wartość przypisana musi być określona; przypisz Float.NaN tylko właściwościom instancji RawFrame.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | float |  |

### getY() {#getY--}
```
public final float getY()
```

Pobiera lub ustawia współrzędną y lewego górnego rogu kształtu, mierzoną w punktach. Odczyt/zapis float.

--------------------

Wartość zwracana jest zawsze określona i nigdy nie jest Float.NaN. Wartość przypisana musi być określona; przypisz Float.NaN tylko właściwościom instancji RawFrame.

**Zwraca:**
float

### setY(float value) {#setY-float-}
```
public final void setY(float value)
```

Pobiera lub ustawia współrzędną y lewego górnego rogu kształtu, mierzoną w punktach. Odczyt/zapis float.

--------------------

Wartość zwracana jest zawsze określona i nigdy nie jest Float.NaN. Wartość przypisana musi być określona; przypisz Float.NaN tylko właściwościom instancji RawFrame.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | float |  |

### getWidth() {#getWidth--}
```
public final float getWidth()
```

Pobiera lub ustawia szerokość kształtu, mierzoną w punktach. Odczyt/zapis float.

--------------------

Wartość zwracana jest zawsze określona i nigdy nie jest Float.NaN. Wartość przypisana musi być określona; przypisz Float.NaN tylko właściwościom instancji RawFrame.

**Zwraca:**
float

### setWidth(float value) {#setWidth-float-}
```
public final void setWidth(float value)
```

Pobiera lub ustawia szerokość kształtu, mierzoną w punktach. Odczyt/zapis float.

--------------------

Wartość zwracana jest zawsze określona i nigdy nie jest Float.NaN. Wartość przypisana musi być określona; przypisz Float.NaN tylko właściwościom instancji RawFrame.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | float |  |

### getHeight() {#getHeight--}
```
public final float getHeight()
```

Pobiera lub ustawia wysokość kształtu, mierzoną w punktach. Odczyt/zapis float.

--------------------

Wartość zwracana jest zawsze określona i nigdy nie jest Float.NaN. Wartość przypisana musi być określona; przypisz Float.NaN tylko właściwościom instancji RawFrame.

**Zwraca:**
float

### setHeight(float value) {#setHeight-float-}
```
public final void setHeight(float value)
```

Pobiera lub ustawia wysokość kształtu, mierzoną w punktach. Odczyt/zapis float.

--------------------

Wartość zwracana jest zawsze określona i nigdy nie jest Float.NaN. Wartość przypisana musi być określona; przypisz Float.NaN tylko właściwościom instancji RawFrame.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | float |  |

### getBlackWhiteMode() {#getBlackWhiteMode--}
```
public final byte getBlackWhiteMode()
```

Właściwość określa, jak kształt będzie renderowany w trybie czarno-białym. Odczyt/zapis [BlackWhiteMode](../../com.aspose.slides/blackwhitemode).

**Zwraca:**
byte

### setBlackWhiteMode(byte value) {#setBlackWhiteMode-byte-}
```
public final void setBlackWhiteMode(byte value)
```

Właściwość określa, jak kształt będzie renderowany w trybie czarno-białym. Odczyt/zapis [BlackWhiteMode](../../com.aspose.slides/blackwhitemode).

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | byte |  |

### getUniqueId() {#getUniqueId--}
```
public final long getUniqueId()
```

Zwraca wewnętrzny, zakresowy identyfikator prezentacji przeznaczony do użycia przez dodatki lub inny kod. Ponieważ wartość może być zmieniona przez użytkownika lub programowo, nie należy jej traktować jako trwały unikalny klucz. Tylko do odczytu long. Zobacz także #getOfficeInteropShapeId.getOfficeInteropShapeId.

**Zwraca:**
long

### getOfficeInteropShapeId() {#getOfficeInteropShapeId--}
```
public final long getOfficeInteropShapeId()
```

Zwraca unikalny identyfikator zakresu slajdu, który pozostaje stały przez całe życie kształtu i pozwala PowerPointowi lub kodowi interop na niezawodne odwoływanie się do kształtu z dowolnego miejsca w dokumencie. Tylko do odczytu long. Zobacz także #getUniqueId.getUniqueId.

**Zwraca:**
long

### getAlternativeText() {#getAlternativeText--}
```
public final String getAlternativeText()
```

Zwraca lub ustawia tekst alternatywny powiązany z kształtem. Odczyt/zapis String.

**Zwraca:**
java.lang.String

### setAlternativeText(String value) {#setAlternativeText-java.lang.String-}
```
public final void setAlternativeText(String value)
```

Zwraca lub ustawia tekst alternatywny powiązany z kształtem. Odczyt/zapis String.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | java.lang.String |  |

### getAlternativeTextTitle() {#getAlternativeTextTitle--}
```
public final String getAlternativeTextTitle()
```

Zwraca lub ustawia tytuł tekstu alternatywnego powiązanego z kształtem. Odczyt/zapis String.

**Zwraca:**
java.lang.String

### setAlternativeTextTitle(String value) {#setAlternativeTextTitle-java.lang.String-}
```
public final void setAlternativeTextTitle(String value)
```

Zwraca lub ustawia tytuł tekstu alternatywnego powiązanego z kształtem. Odczyt/zapis String.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | java.lang.String |  |

### getName() {#getName--}
```
public final String getName()
```

Zwraca lub ustawia nazwę kształtu. Musi być niepusty. Użyj pustego ciągu, jeśli to konieczne. Odczyt/zapis String.

**Zwraca:**
java.lang.String

### setName(String value) {#setName-java.lang.String-}
```
public final void setName(String value)
```

Zwraca lub ustawia nazwę kształtu. Musi być niepusty. Użyj pustego ciągu, jeśli to konieczne. Odczyt/zapis String.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | java.lang.String |  |

### isDecorative() {#isDecorative--}
```
public final boolean isDecorative()
```

Pobiera lub ustawia opcję 'Oznacz jako dekoracyjne' (boolean odczyt/zapis).

--------------------

> ```
> Presentation pres = new Presentation("sample.pptx");
>  try {
>     pres.getSlides().get_Item(0).getShapes().get_Item(0).setDecorative(true);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Zwraca:**
boolean

### setDecorative(boolean value) {#setDecorative-boolean-}
```
public final void setDecorative(boolean value)
```

Pobiera lub ustawia opcję 'Oznacz jako dekoracyjne' (boolean odczyt/zapis).

--------------------

> ```
> Presentation pres = new Presentation("sample.pptx");
>  try {
>     pres.getSlides().get_Item(0).getShapes().get_Item(0).setDecorative(true);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | boolean |  |

### getShapeLock() {#getShapeLock--}
```
public IBaseShapeLock getShapeLock()
```

Zwraca blokady kształtu. Tylko do odczytu [IBaseShapeLock](../../com.aspose.slides/ibaseshapelock).

**Zwraca:**
[IBaseShapeLock](../../com.aspose.slides/ibaseshapelock)

### isGrouped() {#isGrouped--}
```
public final boolean isGrouped()
```

Określa, czy kształt jest grupowany. Tylko do odczytu boolean.

Property #getParentGroup.getParentGroup zwraca obiekt GroupShape nadrzędny, jeśli kształt jest grupowany.

**Zwraca:**
boolean

### getParentGroup() {#getParentGroup--}
```
public final IGroupShape getParentGroup()
```

Zwraca obiekt GroupShape nadrzędny, jeśli kształt jest grupowany. W przeciwnym razie zwraca null. Tylko do odczytu [IGroupShape](../../com.aspose.slides/igroupshape).

Property #isGrouped.isGrouped określa, czy kształt jest grupowany.

**Zwraca:**
[IGroupShape](../../com.aspose.slides/igroupshape)

### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```

Zwraca obiekt Parent_Immediate. Tylko do odczytu IDOMObject.

**Zwraca:**
com.aspose.slides.IDOMObject

### getVisualBounds() {#getVisualBounds--}
```
public final RectF getVisualBounds()
```

Pobiera wizualne granice kształtu obliczone na podstawie jego renderowanej treści.

**Zwraca:**
android.graphics.RectF - A android.graphics.RectF that represents the visual bounds of the shape in slide coordinates.

--------------------

Zwrócony prostokąt reprezentuje wyrównane do osi granice całej zawartości generowanej przez kształt podczas renderowania w układzie współrzędnych slajdu. Granice te mogą różnić się od granic modelu kształtu #getX.getX/#setX(float).setX(float), #getY.getY/#setY(float).setY(float), #getWidth.getWidth/#setWidth(float).setWidth(float), #getHeight.getHeight/#setHeight(float).setHeight(float) i mogą zawierać ujemne współrzędne, jeśli renderowana zawartość wykracza poza początek slajdu. Granice wizualne uwzględniają aspekty związane z renderowaniem, takie jak przekształcenia (np. obrót), szerokość i połączenia linii, układ i przepełnienie tekstu, geometria SmartArt oraz inne efekty układu wpływające na ostateczny wygląd renderowanego kształtu. Zwrócone granice nie są przycięte do prostokąta slajdu.

### getSlide() {#getSlide--}
```
public final IBaseSlide getSlide()
```

Zwraca slajd nadrzędny kształtu. Tylko do odczytu [IBaseSlide](../../com.aspose.slides/ibaseslide).

**Zwraca:**
[IBaseSlide](../../com.aspose.slides/ibaseslide)

### getPresentation() {#getPresentation--}
```
public     �
```

Zwraca prezentację nadrzędną slajdu. Tylko do odczytu [IPresentation](../../com.aspose.slides/ipresentation).

**Zwraca:**
[IPresentation](../../com.aspose.slides/ipresentation)