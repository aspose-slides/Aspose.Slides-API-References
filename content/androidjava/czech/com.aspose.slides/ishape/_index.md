---
title: IShape
second_title: Aspose.Slides pro Android pomocí Java API Reference
description: Představuje tvar na snímku.
type: docs
url: /cs/com.aspose.slides/ishape/
---
**All Implemented Interfaces:**
[com.aspose.slides.ISlideComponent](../../com.aspose.slides/islidecomponent), [com.aspose.slides.IHyperlinkContainer](../../com.aspose.slides/ihyperlinkcontainer)
```
public interface IShape extends ISlideComponent, IHyperlinkContainer
```

Represents a shape on a slide.
## Metody

| Metoda | Popis |
| --- | --- |
| [isTextHolder()](#isTextHolder--) | Určuje, zda je tvar TextHolder. |
| [getPlaceholder()](#getPlaceholder--) | Vrací placeholder pro tvar. |
| [addPlaceholder(IPlaceholder placeholderToCopyFrom)](#addPlaceholder-com.aspose.slides.IPlaceholder-) | Přidá nový placeholder, pokud neexistuje, a nastaví vlastnosti placeholderu na zadaný. |
| [removePlaceholder()](#removePlaceholder--) | Definuje, že tento tvar není placeholder. |
| [getCustomData()](#getCustomData--) | Vrací vlastní data tvaru. |
| [getRawFrame()](#getRawFrame--) | Vrací nebo nastavuje vlastnosti surového rámce tvaru. |
| [setRawFrame(IShapeFrame value)](#setRawFrame-com.aspose.slides.IShapeFrame-) | Vrací nebo nastavuje vlastnosti surového rámce tvaru. |
| [getFrame()](#getFrame--) | Vrací nebo nastavuje vlastnosti rámce tvaru. |
| [setFrame(IShapeFrame value)](#setFrame-com.aspose.slides.IShapeFrame-) | Vrací nebo nastavuje vlastnosti rámce tvaru. |
| [getLineFormat()](#getLineFormat--) | Vrací objekt LineFormat, který obsahuje vlastnosti formátování čáry pro tvar. |
| [getThreeDFormat()](#getThreeDFormat--) | Vrací objekt ThreeDFormat, který obsahuje vlastnosti formátování 3D pro tvar. |
| [getEffectFormat()](#getEffectFormat--) | Vrací objekt EffectFormat, který obsahuje pixelové efekty aplikované na tvar. |
| [getFillFormat()](#getFillFormat--) | Vrací objekt FillFormat, který obsahuje vlastnosti formátování výplně pro tvar. |
| [getImage()](#getImage--) | Vrací miniaturu tvaru. |
| [getImage(int bounds, float scaleX, float scaleY)](#getImage-int-float-float-) | Vrací miniaturu tvaru. |
| [getHidden()](#getHidden--) | Určuje, zda je tvar skrytý. |
| [setHidden(boolean value)](#setHidden-boolean-) | Určuje, zda je tvar skrytý. |
| [getZOrderPosition()](#getZOrderPosition--) | Vrací pozici tvaru v pořadí Z. |
| [getConnectionSiteCount()](#getConnectionSiteCount--) | Vrací počet připojovacích míst na tvaru. |
| [getRotation()](#getRotation--) | Vrací nebo nastavuje počet stupňů, o které je určený tvar otočen kolem osy Z. |
| [setRotation(float value)](#setRotation-float-) | Vrací nebo nastavuje počet stupňů, o které je určený tvar otočen kolem osy Z. |
| [getX()](#getX--) | Získá nebo nastaví x-souřadnici levého horního rohu tvaru, měřenou v bodech. |
| [setX(float value)](#setX-float-) | Získá nebo nastaví x-souřadnici levého horního rohu tvaru, měřenou v bodech. |
| [getY()](#getY--) | Získá nebo nastaví y-souřadnici levého horního rohu tvaru, měřenou v bodech. |
| [setY(float value)](#setY-float-) | Získá nebo nastaví y-souřadnici levého horního rohu tvaru, měřenou v bodech. |
| [getWidth()](#getWidth--) | Získá nebo nastaví šířku tvaru, měřenou v bodech. |
| [setWidth(float value)](#setWidth-float-) | Získá nebo nastaví šířku tvaru, měřenou v bodech. |
| [getHeight()](#getHeight--) | Získá nebo nastaví výšku tvaru, měřenou v bodech. |
| [setHeight(float value)](#setHeight-float-) | Získá nebo nastaví výšku tvaru, měřenou v bodech. |
| [getAlternativeText()](#getAlternativeText--) | Vrací nebo nastavuje alternativní text spojený s tvarem. |
| [setAlternativeText(String value)](#setAlternativeText-java.lang.String-) | Vrací nebo nastavuje alternativní text spojený s tvarem. |
| [getAlternativeTextTitle()](#getAlternativeTextTitle--) | Vrací nebo nastavuje název alternativního textu spojeného s tvarem. |
| [setAlternativeTextTitle(String value)](#setAlternativeTextTitle-java.lang.String-) | Vrací nebo nastavuje název alternativního textu spojeného s tvarem. |
| [getName()](#getName--) | Vrací nebo nastavuje název tvaru. |
| [setName(String value)](#setName-java.lang.String-) | Vrací nebo nastavuje název tvaru. |
| [isDecorative()](#isDecorative--) | Získá nebo nastaví volbu 'Mark as decorative' (čtení/zápisu) boolean. |
| [setDecorative(boolean value)](#setDecorative-boolean-) | Získá nebo nastaví volbu 'Mark as decorative' (čtení/zápisu) boolean. |
| [getShapeLock()](#getShapeLock--) | Vrací zámky tvaru. |
| [getUniqueId()](#getUniqueId--) | Vrací interní identifikátor v rámci prezentace, určený pro použití doplňky nebo jiným kódem. |
| [getOfficeInteropShapeId()](#getOfficeInteropShapeId--) | Vrací jedinečný identifikátor v rámci snímku, který zůstává konstantní po celou dobu existence tvaru a umožňuje PowerPointu nebo interop kódu spolehlivě odkazovat na tvar odkudkoli v dokumentu. |
| [isGrouped()](#isGrouped--) | Určuje, zda je tvar seskupený. |
| [getBlackWhiteMode()](#getBlackWhiteMode--) | Vlastnost určuje, jak bude tvar vykreslen v černobílém režimu zobrazení. |
| [setBlackWhiteMode(byte value)](#setBlackWhiteMode-byte-) | Vlastnost určuje, jak bude tvar vykreslen v černobílém režimu zobrazení. |
| [getParentGroup()](#getParentGroup--) | Vrací objekt GroupShape rodiče, pokud je tvar seskupený. |
| [writeAsSvg(OutputStream stream)](#writeAsSvg-java.io.OutputStream-) | Ukládá obsah tvaru jako SVG soubor. |
| [writeAsSvg(OutputStream stream, ISVGOptions svgOptions)](#writeAsSvg-java.io.OutputStream-com.aspose.slides.ISVGOptions-) | Ukládá obsah tvaru jako SVG soubor. |
| [getBasePlaceholder()](#getBasePlaceholder--) | Vrací základní placeholder tvar (tvar z rozvržení a/nebo hlavní snímek, ze kterého je aktuální tvar zděděn). |

### isTextHolder() {#isTextHolder--}
```
public abstract boolean isTextHolder()
```

Určuje, zda je tvar TextHolder. Pouze pro čtení boolean.

**Vrací:**
boolean

### getPlaceholder() {#getPlaceholder--}
```
public abstract IPlaceholder getPlaceholder()
```

Vrací placeholder pro tvar. Pouze pro čtení [IPlaceholder](../../com.aspose.slides/iplaceholder).

**Vrací:**
[IPlaceholder](../../com.aspose.slides/iplaceholder)

### addPlaceholder(IPlaceholder placeholderToCopyFrom) {#addPlaceholder-com.aspose.slides.IPlaceholder-}
```
public abstract IPlaceholder addPlaceholder(IPlaceholder placeholderToCopyFrom)
```

Přidá nový placeholder, pokud neexistuje, a nastaví vlastnosti placeholderu na zadaný.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| placeholderToCopyFrom | [IPlaceholder](../../com.aspose.slides/iplaceholder) | Placeholder, ze kterého se kopíruje obsah. |

**Vrací:**
[IPlaceholder](../../com.aspose.slides/iplaceholder) – nový [IPlaceholder](../../com.aspose.slides/iplaceholder).

### removePlaceholder() {#removePlaceholder--}
```
public abstract void removePlaceholder()
```

Definuje, že tento tvar není placeholder.

### getCustomData() {#getCustomData--}
```
public abstract ICustomData getCustomData()
```

Vrací vlastní data tvaru. Pouze pro čtení [ICustomData](../../com.aspose.slides/icustomdata).

**Vrací:**
[ICustomData](../../com.aspose.slides/icustomdata)

### getRawFrame() {#getRawFrame--}
```
public abstract IShapeFrame getRawFrame()
```

Vrací nebo nastavuje vlastnosti surového rámce tvaru. Čtení/zápis [IShapeFrame](../../com.aspose.slides/ishapeframe).

--------------------

> ```
> Code that attempts to assign undefined frame to IShape.getFrame() doesn't make sense in general case (particularly in case when parent GroupShape is multiple nested into other GroupShape-s). For example:
>  
>  IShape shape = ...;
>  shape.setFrame(new ShapeFrame(Float.NaN, Float.NaN, Float.NaN, Float.NaN, NullableBool.NotDefined, NullableBool.NotDefined, Float.NaN));
>  //nebo
>  slide.getShapes().addAutoShape(ShapeType.RoundCornerRectangle, Float.NaN, Float.NaN, Float.NaN, Float.NaN);
>  //Takový kód může vést k nejasným situacím. Byla tedy přidána omezení pro používání nedefinovaných hodnot u IShape.getFrame(). Hodnoty x, y, width, height, flipH, flipV a rotationAngle musí být definovány (ne Float.NaN ani NullableBool.NotDefined). Výše uvedený příklad nyní hází výjimku ArgumentException.
>  //Toto se vztahuje na tyto případy použití:
>  IShape shape = ...;
>  shape.setFrame(...); // nesmí být nedefinováno
>  IShapeCollection shapes = ...;
>  // parametry x, y, width, height nesmí být Float.NaN:
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
>  IShape shape = ...; // tvar je propojen s placeholderem
>  shape.setRawFrame(new ShapeFrame(Float.NaN, Float.NaN, 100, Float.NaN, NullableBool.NotDefined, NullableBool.NotDefined, 0)); // nyní tvar dědí hodnoty x, y, height, flipH, flipV z placeholderu a přepisuje width=100 a rotationAngle=0.
```

**Vrací:**
[IShapeFrame](../../com.aspose.slides/ishapeframe)

### setRawFrame(IShapeFrame value) {#setRawFrame-com.aspose.slides.IShapeFrame-}
```
public abstract void setRawFrame(IShapeFrame value)
```

Vrací nebo nastavuje vlastnosti surového rámce tvaru. Čtení/zápis [IShapeFrame](../../com.aspose.slides/ishapeframe).

--------------------

> ```
> Code that attempts to assign undefined frame to IShape.getFrame() doesn't make sense in general case (particularly in case when parent GroupShape is multiple nested into other GroupShape-s). For example:
>  
>  IShape shape = ...;
>  shape.setFrame(new ShapeFrame(Float.NaN, Float.NaN, Float.NaN, Float.NaN, NullableBool.NotDefined, NullableBool.NotDefined, Float.NaN));
>  //nebo
>  slide.getShapes().addAutoShape(ShapeType.RoundCornerRectangle, Float.NaN, Float.NaN, Float.NaN, Float.NaN);
>  //Takový kód může vést k nejasným situacím. Byla tedy přidána omezení pro používání nedefinovaných hodnot u IShape.getFrame(). Hodnoty x, y, width, height, flipH, flipV a rotationAngle musí být definovány (ne Float.NaN ani NullableBool.NotDefined). Výše uvedený příklad nyní hází výjimku ArgumentException.
>  //Toto se vztahuje na tyto případy použití:
>  IShape shape = ...;
>  shape.setFrame(...); // nesmí být nedefinováno
>  IShapeCollection shapes = ...;
>  // parametry x, y, width, height nesmí být Float.NaN:
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
>  IShape shape = ...; // tvar je propojen s placeholderem
>  shape.setRawFrame(new ShapeFrame(Float.NaN, Float.NaN, 100, Float.NaN, NullableBool.NotDefined, NullableBool.NotDefined, 0)); // nyní tvar dědí hodnoty x, y, height, flipH, flipV z placeholderu a přepisuje width=100 a rotationAngle=0.
```

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | [IShapeFrame](../../com.aspose.slides/ishapeframe) |  |

### getFrame() {#getFrame--}
```
public abstract IShapeFrame getFrame()
```

Vrací nebo nastavuje vlastnosti rámce tvaru. Čtení/zápis [IShapeFrame](../../com.aspose.slides/ishapeframe).

--------------------

Value of each property of the returned IShapeFrame instance is not undefined (is not NaN or NotDefined). Value of each property of the assigned IShapeFrame instance must be not undefined (must be not NaN or NotDefined). You can set undefined values for RawFrame instance properties.

**Vrací:**
[IShapeFrame](../../com.aspose.slides/ishapeframe)

### setFrame(IShapeFrame value) {#setFrame-com.aspose.slides.IShapeFrame-}
```
public abstract void setFrame(IShapeFrame value)
```

Vrací nebo nastavuje vlastnosti rámce tvaru. Čtení/zápis [IShapeFrame](../../com.aspose.slides/ishapeframe).

--------------------

Value of each property of the returned IShapeFrame instance is not undefined (is not NaN or NotDefined). Value of each property of the assigned IShapeFrame instance must be not undefined (must be not NaN or NotDefined). You can set undefined values for RawFrame instance properties.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | [IShapeFrame](../../com.aspose.slides/ishapeframe) |  |

### getLineFormat() {#getLineFormat--}
```
public abstract ILineFormat getLineFormat()
```

Vrací objekt LineFormat, který obsahuje vlastnosti formátování čáry pro tvar. Pouze pro čtení [ILineFormat](../../com.aspose.slides/ilineformat).

**Vrací:**
[ILineFormat](../../com.aspose.slides/ilineformat)

### getThreeDFormat() {#getThreeDFormat--}
```
public abstract IThreeDFormat getThreeDFormat()
```

Vrací objekt ThreeDFormat, který obsahuje vlastnosti formátování 3D pro tvar. Pouze pro čtení [IThreeDFormat](../../com.aspose.slides/ithreedformat).

**Vrací:**
[IThreeDFormat](../../com.aspose.slides/ithreedformat)

### getEffectFormat() {#getEffectFormat--}
```
public abstract IEffectFormat getEffectFormat()
```

Vrací objekt EffectFormat, který obsahuje pixelové efekty aplikované na tvar. Pouze pro čtení [IEffectFormat](../../com.aspose.slides/ieffectformat).

**Vrací:**
[IEffectFormat](../../com.aspose.slides/ieffectformat)

### getFillFormat() {#getFillFormat--}
```
public abstract IFillFormat getFillFormat()
```

Vrací objekt FillFormat, který obsahuje vlastnosti formátování výplně pro tvar. Pouze pro čtení [IFillFormat](../../com.aspose.slides/ifillformat).

**Vrací:**
[IFillFormat](../../com.aspose.slides/ifillformat)

### getImage() {#getImage--}
```
public abstract IImage getImage()
```

Vrací miniaturu tvaru. ShapeThumbnailBounds.Shape shape thumbnail bounds type is used by default.

**Vrací:**
[IImage](../../com.aspose.slides/iimage) – miniatura tvaru.

### getImage(int bounds, float scaleX, float scaleY) {#getImage-int-float-float-}
```
public abstract IImage getImage(int bounds, float scaleX, float scaleY)
```

Vrací miniaturu tvaru.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| bounds | int | Typ ohraničení miniatury tvaru. |
| scaleX | float | Měřítko X |
| scaleY | float | Měřítko Y |

**Vrací:**
[IImage](../../com.aspose.slides/iimage) – miniatura tvaru nebo null v případě, že je použit ShapeThumbnailBounds.Appearance a tvar nemá viditelné prvky.

### getHidden() {#getHidden--}
```
public abstract boolean getHidden()
```

Určuje, zda je tvar skrytý. Čtení/zápis boolean.

**Vrací:**
boolean

### setHidden(boolean value) {#setHidden-boolean-}
```
public abstract void setHidden(boolean value)
```

Určuje, zda je tvar skrytý. Čtení/zápis boolean.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | boolean |  |

### getZOrderPosition() {#getZOrderPosition--}
```
public abstract int getZOrderPosition()
```

Vrací pozici tvaru v pořadí Z. Shapes[0] vrací tvar v zadní části z-pořadí a Shapes[Shapes.Count - 1] vrací tvar v přední části z-pořadí. Pouze pro čtení int.

**Vrací:**
int

### getConnectionSiteCount() {#getConnectionSiteCount--}
```
public abstract int getConnectionSiteCount()
```

Vrací počet připojovacích míst na tvaru. Pouze pro čtení int.

**Vrací:**
int

### getRotation() {#getRotation--}
```
public abstract float getRotation()
```

Vrací nebo nastavuje počet stupňů, o které je určený tvar otočen kolem osy Z. Kladná hodnota značí otočení po směru hodinových ručiček; záporná hodnota značí otočení proti směru hodinových ručiček. Čtení/zápis float.

--------------------

Returned value is always defined (is not Float.NaN). Assigned value must be defined (not Float.NaN). You can set undefined values for RawFrame instance properties.

**Vrací:**
float

### setRotation(float value) {#setRotation-float-}
```
public abstract void setRotation(float value)
```

Vrací nebo nastavuje počet stupňů, o které je určený tvar otočen kolem osy Z. Kladná hodnota značí otočení po směru hodinových ručiček; záporná hodnota značí otočení proti směru hodinových ručiček. Čtení/zápis float.

--------------------

Returned value is always defined (is not Float.NaN). Assigned value must be defined (not Float.NaN). You can set undefined values for RawFrame instance properties.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | float |  |

### getX() {#getX--}
```
public abstract float getX()
```

Získá nebo nastaví x-souřadnici levého horního rohu tvaru, měřenou v bodech. Čtení/zápis float.

--------------------

The value returned is always defined and never Float.NaN. The value assigned must also be defined; assign Float.NaN only to properties of a RawFrame instance.

**Vrací:**
float

### setX(float value) {#setX-float-}
```
public abstract void setX(float value)
```

Získá nebo nastaví x-souřadnici levého horního rohu tvaru, měřenou v bodech. Čtení/zápis float.

--------------------

The value returned is always defined and never Float.NaN. The value assigned must also be defined; assign Float.NaN only to properties of a RawFrame instance.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | float |  |

### getY() {#getY--}
```
public abstract float getY()
```

Získá nebo nastaví y-souřadnici levého horního rohu tvaru, měřenou v bodech. Čtení/zápis float.

--------------------

The value returned is always defined and never Float.NaN. The value assigned must also be defined; assign Float.NaN only to properties of a RawFrame instance.

**Vrací:**
float

### setY(float value) {#setY-float-}
```
public abstract void setY(float value)
```

Získá nebo nastaví y-souřadnici levého horního rohu tvaru, měřenou v bodech. Čtení/zápis float.

--------------------

The value returned is always defined and never Float.NaN. The value assigned must also be defined; assign Float.NaN only to properties of a RawFrame instance.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | float |  |

### getWidth() {#getWidth--}
```
public abstract float getWidth()
```

Získá nebo nastaví šířku tvaru, měřenou v bodech. Čtení/zápis float.

--------------------

The value returned is always defined and never Float.NaN. The value assigned must also be defined; assign Float.NaN only to properties of a RawFrame instance.

**Vrací:**
float

### setWidth(float value) {#setWidth-float-}
```
public abstract void setWidth(float value)
```

Získá nebo nastaví šířku tvaru, měřenou v bodech. Čtení/zápis float.

--------------------

The value returned is always defined and never Float.NaN. The value assigned must also be defined; assign Float.NaN only to properties of a RawFrame instance.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | float |  |

### getHeight() {#getHeight--}
```
public abstract float getHeight()
```

Získá nebo nastaví výšku tvaru, měřenou v bodech. Čtení/zápis float.

--------------------

The value returned is always defined and never Float.NaN. The value assigned must also be defined; assign Float.NaN only to properties of a RawFrame instance.

**Vrací:**
float

### setHeight(float value) {#setHeight-float-}
```
public abstract void setHeight(float value)
```

Získá nebo nastaví výšku tvaru, měřenou v bodech. Čtení/zápis float.

--------------------

The value returned is always defined and never Float.NaN. The value assigned must also be defined; assign Float.NaN only to properties of a RawFrame instance.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | float |  |

### getAlternativeText() {#getAlternativeText--}
```
public abstract String getAlternativeText()
```

Vrací nebo nastavuje alternativní text spojený s tvarem. Čtení/zápis String.

**Vrací:**
java.lang.String

### setAlternativeText(String value) {#setAlternativeText-java.lang.String-}
```
public abstract void setAlternativeText(String value)
```

Vrací nebo nastavuje alternativní text spojený s tvarem. Čtení/zápis String.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | java.lang.String |  |

### getAlternativeTextTitle() {#getAlternativeTextTitle--}
```
public abstract String getAlternativeTextTitle()
```

Vrací nebo nastavuje název alternativního textu spojeného s tvarem. Čtení/zápis String.

**Vrací:**
java.lang.String

### setAlternativeTextTitle(String value) {#setAlternativeTextTitle-java.lang.String-}
```
public abstract void setAlternativeTextTitle(String value)
```

Vrací nebo nastavuje název alternativního textu spojeného s tvarem. Čtení/zápis String.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | java.lang.String |  |

### getName() {#getName--}
```
public abstract String getName()
```

Vrací nebo nastavuje název tvaru. Čtení/zápis String.

**Vrací:**
java.lang.String

### setName(String value) {#setName-java.lang.String-}
```
public abstract void setName(String value)
```

Vrací nebo nastavuje název tvaru. Čtení/zápis String.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | java.lang.String |  |

### isDecorative() {#isDecorative--}
```
public abstract boolean isDecorative()
```

Získá nebo nastaví volbu 'Mark as decorative' (čtení/zápisu) boolean.

--------------------

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
public abstract void setDecorative(boolean value)
```

Získá nebo nastaví volbu 'Mark as decorative' (čtení/zápisu) boolean.

--------------------

> ```
> Presentation pres = new Presentation("sample.pptx");
>  try {
>     pres.getSlides().get_Item(0).getShapes().get_Item(0).setDecorative(true);
>  finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | boolean |  |

### getShapeLock() {#getShapeLock--}
```
public abstract IBaseShapeLock getShapeLock()
```

Vrací zámky tvaru. Pouze pro čtení [IBaseShapeLock](../../com.aspose.slides/ibaseshapelock).

**Vrací:**
[IBaseShapeLock](../../com.aspose.slides/ibaseshapelock)

### getUniqueId() {#getUniqueId--}
```
public abstract long getUniqueId()
```

Vrací interní identifikátor v rámci prezentace, určený pro použití doplňky nebo jiným kódem. Protože tuto hodnotu může uživatel nebo program přepsat, neměla by být považována za trvalý jedinečný klíč. Pouze pro čtení long. Viz také \#getOfficeInteropShapeId.getOfficeInteropShapeId.

**Vrací:**
long

### getOfficeInteropShapeId() {#getOfficeInteropShapeId--}
```
public abstract long getOfficeInteropShapeId()
```

Vrací jedinečný identifikátor v rámci snímku, který zůstává konstantní po celou dobu existence tvaru a umožňuje PowerPointu nebo interop kódu spolehlivě odkazovat na tvar odkudkoli v dokumentu. Pouze pro čtení long. Viz také \#getUniqueId.getUniqueId.

**Vrací:**
long

### isGrouped() {#isGrouped--}
```
public abstract  boolean   isGrouped  ()
```

Určuje, zda je tvar seskupený. Pouze pro čtení boolean.

--------------------

Property \#getParentGroup.getParentGroup returns parent GroupShape object if shape is grouped.

**Vrací:**
boolean

### getBlackWhiteMode() {#getBlackWhiteMode--}
```
public abstract byte getBlackWhiteMode()
```

Vlastnost určuje, jak bude tvar vykreslen v černobílém režimu zobrazení. Čtení/zápis [BlackWhiteMode](../../com.aspose.slides/blackwhitemode).

**Vrací:**
byte

### setBlackWhiteMode(byte value) {#setBlackWhiteMode-byte-}
```
public abstract void setBlackWhiteMode(byte value)
```

Vlastnost určuje, jak bude tvar vykreslen v černobílém režimu zobrazení. Čtení/zápis [BlackWhiteMode](../../com.aspose.slides/blackwhitemode).

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | byte |  |

### getParentGroup() {#getParentGroup--}
```
public abstract IGroupShape getParentGroup()
```

Vrací objekt GroupShape rodiče, pokud je tvar seskupený. Jinak vrací null. Pouze pro čtení [IGroupShape](../../com.aspose.slides/igroupshape).

--------------------

Property \#isGrouped.isGrouped determines whether the shape is grouped.

**Vrací:**
[IGroupShape](../../com.aspose.slides/igroupshape)

### writeAsSvg(OutputStream stream) {#writeAsSvg-java.io.OutputStream-}
```
public abstract void writeAsSvg(OutputStream stream)
```

Ukládá obsah tvaru jako SVG soubor.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| stream | java.io.OutputStream | Cílový stream |

### writeAsSvg(OutputStream stream, ISVGOptions svgOptions) {#writeAsSvg-java.io.OutputStream-com.aspose.slides.ISVGOptions-}
```
public abstract void writeAsSvg(OutputStream stream, ISVGOptions svgOptions)
```

Ukládá obsah tvaru jako SVG soubor.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| stream | java.io.OutputStream | Cílový stream |
| svgOptions | [ISVGOptions](../../com.aspose.slides/isvgoptions) | Možnosti generování SVG |

### getBasePlaceholder() {#getBasePlaceholder--}
```
public       –    



```

Vrací základní placeholder tvar (tvar z rozvržení a/nebo hlavní snímek, ze kterého je aktuální tvar zděděn).

--------------------

> ```
> // získat všechny (master/layout/slide) animované efekty placeholderu
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

Null je vráceno, pokud aktuální tvar není zděděn.

**Vrací:**
[IShape](../../com.aspose.slides/ishape)