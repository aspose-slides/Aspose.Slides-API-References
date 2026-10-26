---
title: Shape
second_title: Aspose.Slides pro Android přes Java API Reference
description: Reprezentuje tvar na snímku.
type: docs
url: /cs/com.aspose.slides/shape/
---
**Dědičnost:**
java.lang.Object

**Všechna implementovaná rozhraní:**
[com.aspose.slides.IShape](../../com.aspose.slides/ishape), com.aspose.slides.IDOMObject
```
public class Shape implements IShape, IDOMObject
```

Reprezentuje tvar na snímku.
## Metody

| Metoda | Popis |
| --- | --- |
| [isTextHolder()](#isTextHolder--) | Určuje, zda je tvar TextHolder_PPT. |
| [getPlaceholder()](#getPlaceholder--) | Vrací zástupný prvek tvaru. |
| [removePlaceholder()](#removePlaceholder--) | Definuje, že tento tvar není zástupný prvek. |
| [addPlaceholder(IPlaceholder placeholderToCopyFrom)](#addPlaceholder-com.aspose.slides.IPlaceholder-) | Přidá nový zástupný prvek, pokud neexistuje, a nastaví vlastnosti zástupného prvku na zadaný. |
| [getBasePlaceholder()](#getBasePlaceholder--) | Vrací základní zástupný tvar (tvar z rozvržení a/nebo hlavního snímku, ze kterého je aktuální tvar zděděn). |
| [getCustomData()](#getCustomData--) | Vrací vlastní data tvaru. |
| [getRawFrame()](#getRawFrame--) | Vrací nebo nastavuje surové vlastnosti rámce tvaru. |
| [setRawFrame(IShapeFrame value)](#setRawFrame-com.aspose.slides.IShapeFrame-) | Vrací nebo nastavuje surové vlastnosti rámce tvaru. |
| [getFrame()](#getFrame--) | Vrací nebo nastavuje vlastnosti rámce tvaru. |
| [setFrame(IShapeFrame value)](#setFrame-com.aspose.slides.IShapeFrame-) | Vrací nebo nastavuje vlastnosti rámce tvaru. |
| [getLineFormat()](#getLineFormat--) | Vrací objekt LineFormat, který obsahuje vlastnosti formátování čáry pro tvar. |
| [getThreeDFormat()](#getThreeDFormat--) | Vrací objekt ThreeDFormat, který obsahuje 3D efektní vlastnosti pro tvar. |
| [getEffectFormat()](#getEffectFormat--) | Vrací objekt EffectFormat, který obsahuje pixelové efekty aplikované na tvar. |
| [getFillFormat()](#getFillFormat--) | Vrací objekt FillFormat, který obsahuje vlastnosti výplně formátování pro tvar. |
| [getImage()](#getImage--) | Vrací miniaturu tvaru. |
| [getImage(int bounds, float scaleX, float scaleY)](#getImage-int-float-float-) | Vrací miniaturu tvaru. |
| [writeAsSvg(OutputStream stream)](#writeAsSvg-java.io.OutputStream-) | Ukládá obsah tvaru jako SVG soubor. |
| [writeAsSvg(OutputStream stream, ISVGOptions svgOptions)](#writeAsSvg-java.io.OutputStream-com.aspose.slides.ISVGOptions-) | Ukládá obsah tvaru jako SVG soubor. |
| [getHyperlinkClick()](#getHyperlinkClick--) | Vrací nebo nastavuje hyperodkaz definovaný pro kliknutí myší. |
| [setHyperlinkClick(IHyperlink value)](#setHyperlinkClick-com.aspose.slides.IHyperlink-) | Vrací nebo nastavuje hyperodkaz definovaný pro kliknutí myší. |
| [getHyperlinkMouseOver()](#getHyperlinkMouseOver--) | Vrací nebo nastavuje hyperodkaz definovaný pro najetí myší. |
| [setHyperlinkMouseOver(IHyperlink value)](#setHyperlinkMouseOver-com.aspose.slides.IHyperlink-) | Vrací nebo nastavuje hyperodkaz definovaný pro najetí myší. |
| [getHyperlinkManager()](#getHyperlinkManager--) | Vrací správce hyperodkazů. |
| [getHidden()](#getHidden--) | Určuje, zda je tvar skrytý. |
| [setHidden(boolean value)](#setHidden-boolean-) | Určuje, zda je tvar skrytý. |
| [getZOrderPosition()](#getZOrderPosition--) | Vrací pozici tvaru ve z-řazení. |
| [getConnectionSiteCount()](#getConnectionSiteCount--) | Vrací počet připojovacích míst na tvaru. |
| [getRotation()](#getRotation--) | Vrací nebo nastavuje počet stupňů, o které je specifikovaný tvar otočen kolem osy z. |
| [setRotation(float value)](#setRotation-float-) | Vrací nebo nastavuje počet stupňů, o které je specifikovaný tvar otočen kolem osy z. |
| [getX()](#getX--) | Získá nebo nastaví x-souřadnici levého horního rohu tvaru, měřeno v bodech. |
| [setX(float value)](#setX-float-) | Získá nebo nastaví x-souřadnici levého horního rohu tvaru, měřeno v bodech. |
| [getY()](#getY--) | Získá nebo nastaví y-souřadnici levého horního rohu tvaru, měřeno v bodech. |
| [setY(float value)](#setY-float-) | Získá nebo nastaví y-souřadnici levého horního rohu tvaru, měřeno v bodech. |
| [getWidth()](#getWidth--) | Získá nebo nastaví šířku tvaru, měřeno v bodech. |
| [setWidth(float value)](#setWidth-float-) | Získá nebo nastaví šířku tvaru, měřeno v bodech. |
| [getHeight()](#getHeight--) | Získá nebo nastaví výšku tvaru, měřeno v bodech. |
| [setHeight(float value)](#setHeight-float-) | Získá nebo nastaví výšku tvaru, měřeno v bodech. |
| [getBlackWhiteMode()](#getBlackWhiteMode--) | Vlastnost určuje, jak bude tvar vykreslen v černobílém režimu zobrazení. |
| [setBlackWhiteMode(byte value)](#setBlackWhiteMode-byte-) | Vlastnost určuje, jak bude tvar vykreslen v černobílém režimu zobrazení. |
| [getUniqueId()](#getUniqueId--) | Vrací interní identifikátor v rámci prezentace určený k použití doplňky nebo jiným kódem. |
| [getOfficeInteropShapeId()](#getOfficeInteropShapeId--) | Vrací jedinečný identifikátor v rámci snímku, který zůstává konstantní po celou životnost tvaru a umožňuje PowerPointu nebo interop kódu spolehlivě odkazovat na tvar odkudkoli v dokumentu. |
| [getAlternativeText()](#getAlternativeText--) | Vrací nebo nastavuje alternativní text spojený s tvarem. |
| [setAlternativeText(String value)](#setAlternativeText-java.lang.String-) | Vrací nebo nastavuje alternativní text spojený s tvarem. |
| [getAlternativeTextTitle()](#getAlternativeTextTitle--) | Vrací nebo nastavuje nadpis alternativního textu spojeného s tvarem. |
| [setAlternativeTextTitle(String value)](#setAlternativeTextTitle-java.lang.String-) | Vrací nebo nastavuje nadpis alternativního textu spojeného s tvarem. |
| [getName()](#getName--) | Vrací nebo nastavuje název tvaru. |
| [setName(String value)](#setName-java.lang.String-) | Vrací nebo nastavuje název tvaru. |
| [isDecorative()](#isDecorative--) | Získá nebo nastaví 'Mark as decorative' možnost Pouze čtení/zápis boolean. |
| [setDecorative(boolean value)](#setDecorative-boolean-) | Získá nebo nastaví 'Mark as decorative' možnost Pouze čtení/zápis boolean. |
| [getShapeLock()](#getShapeLock--) | Vrací zámky tvaru. |
| [isGrouped()](#isGrouped--) | Určuje, zda je tvar seskupený. |
| [getParentGroup()](#getParentGroup--) | Vrací objekt GroupShape rodiče, pokud je tvar seskupený. |
| [getParent_Immediate()](#getParent-Immediate--) |  |
| [getVisualBounds()](#getVisualBounds--) | Získá vizuální hranice tvaru vypočítané z jeho vykresleného obsahu. |
| [getSlide()](#getSlide--) | Vrací nadřazený snímek tvaru. |
| [getPresentation()](#getPresentation--) | Vrací nadřazenou prezentaci snímku. |

### isTextHolder() {#isTextHolder--}
```
public final boolean isTextHolder()
```

Určuje, zda je tvar TextHolder_PPT. Pouze ke čtení boolean .

**Vrací:**
boolean

### getPlaceholder() {#getPlaceholder--}
```
public final IPlaceholder getPlaceholder()
```

Vrací zástupný prvek tvaru. Vrátí null, pokud tvar nemá zástupný prvek. Pouze ke čtení [IPlaceholder](../../com.aspose.slides/iplaceholder).

> ```
> The following example shows how to change Text in Placeholder.
>  
>  // Instantiates a Presentation class
>  Presentation pres = new Presentation("ReplacingText.pptx");
>  try {
>      // Accesses the first slide
>      ISlide sld = pres.getSlides().get_Item(0);
>      // Iterates through shapes to find the placeholder
>      for (IShape shp : sld.getShapes())
>          if (shp.getPlaceholder() != null)
>          {
>              // Changes the text in each placeholder
>              ((IAutoShape)shp).getTextFrame().setText("This is a Placeholder");
>          }
>      // Saves the presentation to disk
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
>      for (IShape shape : slide.getSlide().getShapes()) // Iterates through the slide
>      {
>          if (shape.getPlaceholder() != null && shape instanceof AutoShape)
>          {
>              String text = "";
>              if (shape.getPlaceholder().getType() == PlaceholderType.CenteredTitle) // PowerPoint displays "Click to add title"
>              {
>                  text = "Add Title";
>              }
>              else if (shape.getPlaceholder().getType() == PlaceholderType.Subtitle) // Adds subtitle
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

**Vrací:**
[IPlaceholder](../../com.aspose.slides/iplaceholder)

### removePlaceholder() {#removePlaceholder--}
```
public final void removePlaceholder()
```

Definuje, že tento tvar není zástupný prvek.

### addPlaceholder(IPlaceholder placeholderToCopyFrom) {#addPlaceholder-com.aspose.slides.IPlaceholder-}
```
public final IPlaceholder addPlaceholder(IPlaceholder placeholderToCopyFrom)
```

Přidá nový zástupný prvek, pokud neexistuje, a nastaví vlastnosti zástupného prvku na zadaný.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| placeholderToCopyFrom | [IPlaceholder](../../com.aspose.slides/iplaceholder) | Zástupný prvek, ze kterého se kopíruje obsah. |

**Vrací:**
[IPlaceholder](../../com.aspose.slides/iplaceholder) - Nový #getPlaceholder.getPlaceholder.

### getBasePlaceholder() {#getBasePlaceholder--}
```
public final IShape getBasePlaceholder()
```

Vrací základní zástupný tvar (tvar z rozvržení a/nebo hlavního snímku, ze kterého je aktuální tvar zděděn).

> ```
> // získá všechny (master/layout/slide) animované efekty zástupného tvaru
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


Vrátí se null, pokud aktuální tvar není zděděn.

**Vrací:**
[IShape](../../com.aspose.slides/ishape)

### getCustomData() {#getCustomData--}
```
public final ICustomData getCustomData()
```

Vrací vlastní data tvaru. Pouze ke čtení [ICustomData](../../com.aspose.slides/icustomdata).

**Vrací:**
[ICustomData](../../com.aspose.slides/icustomdata)

### getRawFrame() {#getRawFrame--}
```
public final IShapeFrame getRawFrame()
```

Vrací nebo nastavuje surové vlastnosti rámce tvaru. Pouze čtení/zápis [IShapeFrame](../../com.aspose.slides/ishapeframe).

> ```
> Code that attempts to assign undefined frame to IShape.getFrame() doesn't make sense in general case (particularly in case when parent GroupShape is multiple nested into other GroupShape-s). For example:
>  
>  IShape shape = ...;
>  shape.setFrame(new ShapeFrame(Float.NaN, Float.NaN, Float.NaN, Float.NaN, NullableBool.NotDefined, NullableBool.NotDefined, Float.NaN));
>  //nebo
>  slide.getShapes().addAutoShape(ShapeType.RoundCornerRectangle, Float.NaN, Float.NaN, Float.NaN, Float.NaN);
>  //Takový kód může vést k nejasným situacím. Proto byla přidána omezení pro používání nedefinovaných hodnot pro IShape.getFrame(). Hodnoty x, y, šířka, výška, flipH, flipV a rotationAngle musejí být definovány (ne Float.NaN ani NullableBool.NotDefined). Výše uvedený kód nyní vyhazuje výjimku ArgumentException.
>  //Toto se vztahuje na následující případy použití:
>  IShape shape = ...;
>  shape.setFrame(...); // nesmí být nedefinováno
>  IShapeCollection shapes = ...;
>  // parametry x, y, šířka, výška nesmí být Float.NaN:
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
>  //Ale vlastnosti rámce IShape.RawFrame mohou být nedefinované. To dává smysl, když je tvar propojen se zástupným prvkem. Pak jsou nedefinované hodnoty rámce tvaru přepsány z nadřazeného zástupného tvaru. Pokud pro tento tvar neexistuje nadřazený zástupný tvar, pak tvar používá výchozí hodnoty při vyhodnocování efektivního rámce na základě jeho IShape.RawFrame. Výchozí hodnoty jsou 0 a NullableBool.False pro x, y, šířka, výška, flipH, flipV a rotationAngle. Například:
>  IShape shape = ...; // tvar je propojen se zástupným prvkem
>  shape.setRawFrame(new ShapeFrame(Float.NaN, Float.NaN, 100, Float.NaN, NullableBool.NotDefined, NullableBool.NotDefined, 0)); // nyní tvar dědí hodnoty x, y, výška, flipH, flipV ze zástupného prvku a přepisuje šířku=100 a rotationAngle=0.{code}
```

**Vrací:**
[IShapeFrame](../../com.aspose.slides/ishapeframe)

### setRawFrame(IShapeFrame value) {#setRawFrame-com.aspose.slides.IShapeFrame-}
```
public final void setRawFrame(IShapeFrame value)
```

Vrací nebo nastavuje surové vlastnosti rámce tvaru. Pouze čtení/zápis [IShapeFrame](../../com.aspose.slides/ishapeframe).

> ```
> Code that attempts to assign undefined frame to IShape.getFrame() doesn't make sense in general case (particularly in case when parent GroupShape is multiple nested into other GroupShape-s). For example:
>  
>  IShape shape = ...;
>  shape.setFrame(new ShapeFrame(Float.NaN, Float.NaN, Float.NaN, Float.NaN, NullableBool.NotDefined, NullableBool.NotDefined, Float.NaN));
>  //nebo
>  slide.getShapes().addAutoShape(ShapeType.RoundCornerRectangle, Float.NaN, Float.NaN, Float.NaN, Float.NaN);
>  //Takový kód může vést k nejasným situacím. Proto byla přidána omezení pro používání nedefinovaných hodnot pro IShape.getFrame(). Hodnoty x, y, šířka, výška, flipH, flipV a rotationAngle musejí být definovány (ne Float.NaN ani NullableBool.NotDefined). Výše uvedený kód nyní vyhazuje výjimku ArgumentException.
>  //Toto se vztahuje na následující případy použití:
>  IShape shape = ...;
>  shape.setFrame(...); // cannot be undefined
>  IShapeCollection shapes = ...;
>  // x, y, šířka, výška parameters cannot be Float.NaN:
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
>  //Ale vlastnosti rámce IShape.RawFrame mohou být nedefinované. To dává smysl, když je tvar propojen se zástupným prvkem. Pak jsou nedefinované hodnoty rámce tvaru přepsány z nadřazeného zástupného tvaru. Pokud pro tento tvar neexistuje nadřazený zástupný prvek, pak tvar používá výchozí hodnoty při vyhodnocování efektivního rámce na základě svého IShape.RawFrame. Výchozí hodnoty jsou 0 a NullableBool.False pro x, y, šířka, výška, flipH, flipV a rotationAngle. Například:
>  IShape shape = ...; // shape is linked to placeholder
>  shape.setRawFrame(new ShapeFrame(Float.NaN, Float.NaN, 100, Float.NaN, NullableBool.NotDefined, NullableBool.NotDefined, 0)); // tvar nyní dědí hodnoty x, y, výška, flipH, flipV ze zástupného prvku a přepisuje šířku=100 a rotationAngle=0.{code}
> ```


**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | [IShapeFrame](../../com.aspose.slides/ishapeframe) |  |

### getFrame() {#getFrame--}
```
public final IShapeFrame getFrame()
```

Vrací nebo nastavuje vlastnosti rámce tvaru. Pouze čtení/zápis [IShapeFrame](../../com.aspose.slides/ishapeframe).

> Value of each property of the returned IShapeFrame instance is not undefined (is not NaN or NotDefined). Value of each property of the assigned IShapeFrame instance must be not undefined (must be not NaN or NotDefined). You can set undefined values for RawFrame instance properties.

**Vrací:**
[IShapeFrame](../../com.aspose.slides/ishapeframe)

### setFrame(IShapeFrame value) {#setFrame-com.aspose.slides.IShapeFrame-}
```
public final void setTheme



```

Vrací nebo nastavuje vlastnosti rámce tvaru. Pouze čtení/zápis [IShapeFrame](../../com.aspose.slides/ishapeframe).

> Value of each property of the returned IShapeFrame instance is not undefined (is not NaN or NotDefined). Value of each property of the assigned IShapeFrame instance must be not undefined (must be not NaN or NotDefined). You can set undefined values for RawFrame instance properties.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | [IShapeFrame](../../com.aspose.slides/ishapeframe) |  |

### getLineFormat() {#getLineFormat--}
```
public ILineFormat getLineFormat()
```

Vrací objekt LineFormat, který obsahuje vlastnosti formátování čáry pro tvar. Poznámka: může vrátit null pro určité typy tvarů, které nemají vlastnosti čáry. Pouze ke čtení [ILineFormat](../../com.aspose.slides/ilineformat).

**Vrací:**
[ILineFormat](../../com.aspose.slides/ilineformat)

### getThreeDFormat() {#getThreeDFormat--}
```
public IThreeDFormat getThreeDFormat()
```

Vrací objekt ThreeDFormat, který obsahuje 3D efektní vlastnosti pro tvar. Poznámka: může vrátit null pro určité typy tvarů, které nemají 3D vlastnosti. Pouze ke čtení [IThreeDFormat](../../com.aspose.slides/ithreedformat).

**Vrací:**
[IThreeDFormat](../../com.aspose.slides/ithreedformat)

### getEffectFormat() {#getEffectFormat--}
```
public IEffectFormat getEffectFormat()
```

Vrací objekt EffectFormat, který obsahuje pixelové efekty aplikované na tvar. Poznámka: může vrátit null pro určité typy tvarů, které nemají efektové vlastnosti. Pouze ke čtení [IEffectFormat](../../com.aspose.slides/ieffectformat).

**Vrací:**
[IEffectFormat](../../com.aspose.slides/ieffectformat)

### getFillFormat() {#getFillFormat--}
```
public IFillFormat getFillFormat()
```

Vrací objekt FillFormat, který obsahuje vlastnosti výplně formátování pro tvar. Poznámka: může vrátit null pro určité typy tvarů, které nemají výplňové vlastnosti. Pouze ke čtení [IFillFormat](../../com.aspose.slides/ifillformat).

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
>      // Akcent 4, světlejší 80%
>      IShape shape2 = slide.getShapes().addAutoShape(ShapeType.Rectangle, 10, 70, 50, 50);
>      shape2.getFillFormat().setFillType(FillType.Solid);
>      shape2.getFillFormat().getSolidFillColor().setSchemeColor(SchemeColor.Accent4);
>      shape2.getFillFormat().getSolidFillColor().getColorTransform().add(ColorTransformOperation.MultiplyLuminance, 0.2f);
>      shape2.getFillFormat().getSolidFillColor().getColorTransform().add(ColorTransformOperation.AddLuminance, 0.8f);
>      // Akcent 4, světlejší 60%
>      IShape shape3 = slide.getShapes().addAutoShape(ShapeType.Rectangle, 10, 130, 50, 50);
>      shape3.getFillFormat().setFillType(FillType.Solid);
>      shape3.getFillFormat().getSolidFillColor().setSchemeColor(SchemeColor.Accent4);
>      shape3.getFillFormat().getSolidFillColor().getColorTransform().add(ColorTransformOperation.MultiplyLuminance, 0.4f);
>      shape3.getFillFormat().getSolidFillColor().getColorTransform().add(ColorTransformOperation.AddLuminance, 0.6f);
>      // Akcent 4, světlejší 40%
>      IShape shape4 = slide.getShapes().addAutoShape(ShapeType.Rectangle, 10, 190, 50, 50);
>      shape4.getFillFormat().setFillType(FillType.Solid);
>      shape4.getFillFormat().getSolidFillColor().setSchemeColor(SchemeColor.Accent4);
>      shape4.getFillFormat().getSolidFillColor().getColorTransform().add(ColorTransformOperation.MultiplyLuminance, 0.6f);
>      shape4.getFillFormat().getSolidFillColor().getColorTransform().add(ColorTransformOperation.AddLuminance, 0.4f);
>      // Akcent 4, tmavší 25%
>      IShape shape5 = slide.getShapes().addAutoShape(ShapeType.Rectangle, 10, 250, 50, 50);
>      shape5.getFillFormat().setFillType(FillType.Solid);
>      shape5.getFillFormat().getSolidFillColor().setSchemeColor(SchemeColor.Accent4);
>      shape5.getFillFormat().getSolidFillColor().getColorTransform().add(ColorTransformOperation.MultiplyLuminance, 0.75f);
>      // Akcent 4, tmavší 50%
>      IShape shape6 = slide.getShapes().addAutoShape(ShapeType.Rectangle, 10, 310, 50, 50);
>      shape6.getFillFormat().setFillType(FillType.Solid);
>      shape6.getFillFormat().getSolidFillColor().setSchemeColor(SchemeColor.Accent4);
>      shape6.getFillFormat().getSolidFillColor().getColorTransform().add(ColorTransformOperation.MultiplyLuminance, 0.5f);
>      pres.save("example_accent4.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Vrací:**
[IFillFormat](../../com.aspose.slides/ifillformat)

### getImage() {#getImage--}
```
public final IImage getImage()
```

Vrací miniaturu tvaru. ShapeThumbnailBounds.Shape shape thumbnail bounds type is used by default.

**Vrací:**
[IImage](../../com.aspose.slides/iimage) - Shape thumbnail.

### getImage(int bounds, float scaleX, float scaleY) {#getImage-int-float-float-}
```
public final IImage getImage(int bounds, float scaleX, float scaleY)
```

Vrací miniaturu tvaru.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| bounds | int | Shape thumbnail bounds type. |
| scaleX | float | X scale |
| scaleY | float | Y scale |

**Vrací:**
[IImage](../../com.aspose.slides/iimage) - Shape thumbnail or null in case when ShapeThumbnailBounds.Appearance is used and a shape doesn't have visible elements.

### writeAsSvg(OutputStream stream) {#writeAsSvg-java.io.OutputStream-}
```
public final void writeAsSvg(OutputStream stream)
```

Ukládá obsah tvaru jako SVG soubor.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| stream | java.io.OutputStream | Target stream |

### writeAsSvg(OutputStream stream, ISVGOptions svgOptions) {#writeAsSvg-java.io.OutputStream-com.aspose.slides.ISVGOptions-}
```
public final void writeAsSvg(OutputStream stream, ISVGOptions svgOptions)
```

Ukládá obsah tvaru jako SVG soubor.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| stream | java.io.OutputStream | Target stream |
| svgOptions | [ISVGOptions](../../com.aspose.slides/isvgoptions) | SVG generation options |

### getHyperlinkClick() {#getHyperlinkClick--}
```
public final IHyperlink getHyperlinkClick()
```

Vrací nebo nastavuje hyperodkaz definovaný pro kliknutí myší. Čtení/zápis [IHyperlink](../../com.aspose.slides/ihyperlink).

**Vrací:**
[IHyperlink](../../com.aspose.slides/ihyperlink)

### setHyperlinkClick(IHyperlink value) {#setHyperlinkClick-com.aspose.slides.IHyperlink-}
```
public final void setHyperlinkClick(IHyperlink value)
```

Vrací nebo nastavuje hyperodkaz definovaný pro kliknutí myší. Čtení/zápis [IHyperlink](../../com.aspose.slides/ihyperlink).

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | [IHyperlink](../../com.aspose.slides/ihyperlink) |  |

### getHyperlinkMouseOver() {#getHyperlinkMouseOver--}
```
public final IHyperlink getHyperlinkMouseOver()
```

Vrací nebo nastavuje hyperodkaz definovaný pro najetí myší. Čtení/zápis [IHyperlink](../../com.aspose.slides/ihyperlink).

**Vrací:**
[IHyperlink](../../com.aspose.slides/ihyperlink)

### setHyperlinkMouseOver(IHyperlink value) {#setHyperlinkMouseOver-com.aspose.slides.IHyperlink-}
```
public final void setHyperlinkMouseOver(IHyperlink value)
```

Vrací nebo nastavuje hyperodkaz definovaný pro najetí myší. Čtení/zápis [IHyperlink](../../com.aspose.slides/ihyperlink).

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | [IHyperlink](../../com.aspose.slides/ihyperlink) |  |

### getHyperlinkManager() {#getHyperlinkManager--}
```
public final IHyperlinkManager getHyperlinkManager()
```

Vrací správce hyperodkazů. Pouze ke čtení [IHyperlinkManager](../../com.aspose.slides/ihyperlinkmanager).

**Vrací:**
[IHyperlinkManager](../../com.aspose.slides/ihyperlinkmanager)

### getHidden() {#getHidden--}
```
public final boolean getHidden()
```

Určuje, zda je tvar skrytý. Čtení/zápis boolean .

**Vrací:**
boolean

### setHidden(boolean value) {#setHidden-boolean-}
```
public final void setHidden(boolean value)
```

Určuje, zda je tvar skrytý. Čtení/zápis boolean .

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | boolean |  |

### getZOrderPosition() {#getZOrderPosition--}
```
public int getZOrderPosition()
```

Vrací pozici tvaru ve z-řazení. Shapes[0] returns the shape at the back of the z-order, and Shapes[Shapes.Count - 1] returns the shape at the front of the z-order. Pouze ke čtení int .

**Vrací:**
int

### getConnectionSiteCount() {#getConnectionSiteCount--}
```
public final int getConnectionSiteCount()
```

Vrací počet připojovacích míst na tvaru. Pouze ke čtení int .

**Vrací:**
int

### getRotation() {#getRotation--}
```
public final float getRotation()
```

Vrací nebo nastavuje počet stupňů, o které je specifikovaný tvar otočen kolem osy z. Pozitivní hodnota značí otočení po směru hodinových ručiček; záporná hodnota značí otočení proti směru hodinových ručiček. Čtení/zápis float.

> Returned value is always defined (is not Float.NaN). Assigned value must be defined (not Float.NaN). You can set undefined values for RawFrame instance properties.

**Vrací:**
float

### setRotation(float value) {#setRotation-float-}
```
public final void setRotation(float value)
```

Vrací nebo nastavuje počet stupňů, o které je specifikovaný tvar otočen kolem osy z. Pozitivní hodnota značí otočení po směru hodinových ručiček; záporná hodnota značí otočení proti směru hodinových ručiček. Čtení/zápis float.

> Returned value is always defined (is not Float.NaN). Assigned value must be defined (not Float.NaN). You can set undefined values for RawFrame instance properties.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | float |  |

### getX() {#getX--}
```
public final float getX()
```

Získá nebo nastaví x-souřadnici levého horního rohu tvaru, měřeno v bodech. Čtení/zápis float.

> The value returned is always defined and never Float.NaN. The value assigned must also be defined; assign Float.NaN only to properties of a RawFrame instance.

**Vrací:**
float

### setX(float value) {#setX-float-}
```
public final void setX(float value)
```

Získá nebo nastaví x-souřadnici levého horního rohu tvaru, měřeno v bodech. Čtení/zápis float.

> The value returned is always defined and never Float.NaN. The value assigned must also be defined; assign Float.NaN only to properties of a RawFrame instance.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | float |  |

### getY() {#getY--}
```
public final float getY()
```

Získá nebo nastaví y-souřadnici levého horního rohu tvaru, měřeno v bodech. Čtení/zápis float.

> The value returned is always defined and never Float.NaN. The value assigned must also be defined; assign Float.NaN only to properties of a RawFrame instance.

**Vrací:**
float

### setY(float value) {#setY-float-}
```
public final void setY(float value)
```

Získá nebo nastaví y-souřadnici levého horního rohu tvaru, měřeno v bodech. Čtení/zápis float.

> The value returned is always defined and never Float.NaN. The value assigned must also be defined; assign Float.NaN only to properties of a RawFrame instance.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | float |  |

### getWidth() {#getWidth--}
```
public final float getWidth()
```

Získá nebo nastaví šířku tvaru, měřeno v bodech. Čtení/zápis float.

> The value returned is always defined and never Float.NaN. The value assigned must also be defined; assign Float.NaN only to properties of a RawFrame instance.

**Vrací:**
float

### setWidth(float value) {#setWidth-float-}
```
public final void setWidth(float value)
```

Získá nebo nastaví šířku tvaru, měřeno v bodech. Čtení/zápis float.

> The value returned is always defined and never Float.NaN. The value assigned must also be defined; assign Float.NaN only to properties of a RawFrame instance.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | float |  |

### getHeight() {#getHeight--}
```
public final float getHeight()
```

Získá nebo nastaví výšku tvaru, měřeno v bodech. Čtení/zápis float.

> The value returned is always defined and never Float.NaN. The value assigned must also be defined; assign Float.NaN only to properties of a RawFrame instance.

**Vrací:**
float

### setHeight(float value) {#setHeight-float-}
```
public final void setHeight(float value)
```

Získá nebo nastaví výšku tvaru, měřeno v bodech. Čtení/zápis float.

> The value returned is always defined and never Float.NaN. The value assigned must also be defined; assign Float.NaN only to properties of a RawFrame instance.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | float |  |

### getBlackWhiteMode() {#getBlackWhiteMode--}
```
public final byte getBlackWhiteMode()
```

Vlastnost určuje, jak bude tvar vykreslen v černobílém režimu zobrazení. Čtení/zápis [BlackWhiteMode](../../com.aspose.slides/blackwhitemode).

**Vrací:**
byte

### setBlackWhiteMode(byte value) {#setBlackWhiteMode-byte-}
```
public final void setBlackWhiteMode(byte value)
```

Vlastnost určuje, jak bude tvar vykreslen v černobílém režimu zobrazení. Čtení/zápis [BlackWhiteMode](../../com.aspose.slides/blackwhitemode).

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | byte |  |

### getUniqueId() {#getUniqueId--}
```
public final long getUniqueId()
```

Vrací interní identifikátor v rámci prezentace určený k použití doplňky nebo jiným kódem. Protože tuto hodnotu může uživatel nebo program přepsat, neměla by být považována za trvalý jedinečný klíč. Pouze ke čtení long. See also #getOfficeInteropShapeId.getOfficeInteropShapeId.

**Vrací:**
long

### getOfficeInteropShapeId() {#getOfficeInteropShapeId--}
```
public final long getOfficeInteropShapeId()
```

Vrací jedinečný identifikátor v rámci snímku, který zůstává konstantní po celou životnost tvaru a umožňuje PowerPointu nebo interop kódu spolehlivě odkazovat na tvar odkudkoli v dokumentu. Pouze ke čtení long. See also #getUniqueId.getUniqueId.

**Vrací:**
long

### getAlternativeText() {#getAlternativeText--}
```
public final String getAlternativeText()
```

Vrací nebo nastavuje alternativní text spojený s tvarem. Čtení/zápis String.

**Vrací:**
java.lang.String

### setAlternativeText(String value) {#setAlternativeText-java.lang.String-}
```
public final void setAlternativeText(String value)
```

Vrací nebo nastavuje alternativní text spojený s tvarem. Čtení/zápis String.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | java.lang.String |  |

### getAlternativeTextTitle() {#getAlternativeTextTitle--}
```
public final String getAlternativeTextTitle()
```

Vrací nebo nastavuje nadpis alternativního textu spojeného s tvarem. Čtení/zápis String.

**Vrací:**
java.lang.String

### setAlternativeTextTitle(String value) {#setAlternativeTextTitle-java.lang.String-}
```
public final void setAlternativeTextTitle(String value)
```

Vrací nebo nastavuje nadpis alternativního textu spojeného s tvarem. Čtení/zápis String.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | java.lang.String |  |

### getName() {#getName--}
```
public final String getName()
```

Vrací nebo nastavuje název tvaru. Must be not null. Use empty string value if needed. Čtení/zápis String.

**Vrací:**
java.lang.String

### setName(String value) {#setName-java.lang.String-}
```
public final void setName(String value)
```

Vrací nebo nastavuje název tvaru. Must be not null. Use empty string value if needed. Čtení/zápis String.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | java.lang.String |  |

### isDecorative() {#isDecorative--}
```
public final boolean isDecorative()
```

Získá nebo nastaví 'Mark as decorative' možnost Pouze čtení/zápis boolean.

> ```
> Presentation pres = new Presentation("sample.pptx");
>  try {
>     pres.getSlides().get_Item(0).getShapes().get_Item(0).setDecorative(true);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Vrací:**
boolean

### setDecorative(boolean value) {#setDecorative-boolean-}
```
public final void setDecorative(boolean value)
```

Získá nebo nastaví 'Mark as decorative' možnost Pouze čtení/zápis boolean.

> ```
> Presentation pres = new Presentation("sample.pptx");
>  try {
>     pres.getSlides().get_Item(0).getShapes().get_Item(0).setDecorative(true);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | boolean |  |

### getShapeLock() {#getShapeLock--}
```
public IBaseShapeLock getShapeLock()
```

Vrací zámky tvaru. Pouze ke čtení [IBaseShapeLock](../../com.aspose.slides/ibaseshapelock).

**Vrací:**
[IBaseShapeLock](../../com.aspose.slides/ibaseshapelock)

### isGrouped() {#isGrouped--}
```
public final boolean isGrouped()
```

Určuje, zda je tvar seskupený. Pouze ke čtení boolean.

> Property #getParentGroup.getParentGroup returns parent GroupShape object if shape is grouped.

**Vrací:**
boolean

### getParentGroup() {#getParentGroup--}
```
public final IGroupShape getParentGroup()
```

Vrací objekt GroupShape rodiče, pokud je tvar seskupený. Otherwise returns null. Pouze ke čtení [IGroupShape](../../com.aspose.slides/igroupshape).

> Property #isGrouped.isGrouped determines whether the shape is grouped.

**Vrací:**
[IGroupShape](../../com.aspose.slides/igroupshape)

### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```

Vrací Parent_Immediate object. Pouze ke čtení IDOMObject.

**Vrací:**
com.aspose.slides.IDOMObject

### getVisualBounds() {#getVisualBounds--}
```
public final RectF getVisualBounds()
```

Získá vizuální hranice tvaru vypočítané z jeho vykresleného obsahu.

**Vrací:**
android.graphics.RectF - A android.graphics.RectF that represents the visual bounds of the shape in slide coordinates.

> The returned rectangle represents the axis-aligned bounds of all content produced by the shape during rendering in slide coordinate space. These bounds may differ from the shape's model bounds #getX.getX/#setX(float).setX(float), #getY.getY/#setY(float).setY(float), #getWidth.getWidth/#setWidth(float).setWidth(float), #getHeight.getHeight/#setHeight(float).setHeight(float) and may contain negative coordinates if the rendered content extends beyond the slide origin. The visual bounds take into account rendering-related aspects such as transformations (for example, rotation), stroke width and joins, text layout and overflow, SmartArt geometry, and other layout effects that influence the final rendered appearance of the shape. The returned bounds are not clipped to the slide rectangle.

### getSlide() {#getSlide--}
```
public final IBaseSlide getSlide()
```

Vrací nadřazený snímek tvaru. Pouze ke čtení [IBaseSlide](../../com.aspose.slides/ibaseslide).

**Vrací:**
[IBaseSlide](../../com.aspose.slides/ibaseslide)

### getPresentation() {#getPresentation--}
```
public final IPresentation getPresentation()
```

Vrací nadřazenou prezentaci snímku. Pouze ke čtení [IPresentation](../../com.aspose.slides/ipresentation).

**Vrací:**
[IPresentation](../../com.aspose.slides/ipresentation)