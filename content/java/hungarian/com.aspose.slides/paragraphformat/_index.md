---
title: ParagraphFormat
second_title: Aspose.Slides Java API Referenciája
description: Ez az osztály tartalmazza a bekezdés formázási tulajdonságait.
type: docs
url: /hu/com.aspose.slides/paragraphformat/
---
**Öröklődés:**
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject)

**Minden megvalósított interfész:**
[com.aspose.slides.IParagraphFormat](../../com.aspose.slides/iparagraphformat), [com.aspose.slides.IChartParagraphFormat](../../com.aspose.slides/ichartparagraphformat)
```
public final class ParagraphFormat extends PVIObject implements IParagraphFormat, IChartParagraphFormat
```

Ez az osztály tartalmazza a bekezdés formázási tulajdonságait. A [IParagraphFormatEffectiveData](../../com.aspose.slides/iparagraphformateffectivedata)-tól eltérően az osztály minden tulajdonsága írható.

--------------------

Ez az osztály a konkrét bekezdéshez definiált bekezdésformázási tulajdonságok lekérésére és módosítására szolgál. Ez azt jelenti, hogy az értékek lekérdezésekor nincs öröklődés alkalmazva, így a legtöbb esetben olyan értékeket kapunk, amelyek "undefined"-et jelentnek.

Az öröklött értékeket is tartalmazó hatékony formázási paraméterek értékeinek lekéréséhez a [getEffective](../../com.aspose.slides/paragraphformat\#getEffective) metódust kell használni, amely egy [IParagraphFormatEffectiveData](../../com.aspose.slides/iparagraphformateffectivedata) példányt ad vissza.
## Konstruktorok

| Konstruktor | Leírás |
| --- | --- |
| [ParagraphFormat()](#ParagraphFormat--) | Új példányt hoz létre a [ParagraphFormat](../../com.aspose.slides/paragraphformat) osztályból. |
## Metódusok

| Metódus | Leírás |
| --- | --- |
| [getBullet()](#getBullet--) | Visszaadja a bekezdés bullet formátumát. |
| [getDepth()](#getDepth--) | Visszaadja vagy beállítja a bekezdés mélységét. |
| [setDepth(short value)](#setDepth-short-) | Visszaadja vagy beállítja a bekezdés mélységét. |
| [getAlignment()](#getAlignment--) | Visszaadja vagy beállítja a bekezdés szövegigazítását öröklődés nélkül. |
| [setAlignment(int value)](#setAlignment-int-) | Visszaadja vagy beállítja a bekezdés szövegigazítását öröklődés nélkül. |
| [getSpaceWithin()](#getSpaceWithin--) | Visszaadja vagy beállítja a sorok közti távolságot egy bekezdésben. |
| [setSpaceWithin(float value)](#setSpaceWithin-float-) | Visszaadja vagy beállítja a sorok közti távolságot egy bekezdésben. |
| [getSpaceBefore()](#getSpaceBefore--) | Visszaadja vagy beállítja az első sor előtti térközt egy bekezdésben öröklődés nélkül. |
| [setSpaceBefore(float value)](#setSpaceBefore-float-) | Visszaadja vagy beállítja az első sor előtti térközt egy bekezdésben öröklődés nélkül. |
| [getSpaceAfter()](#getSpaceAfter--) | Visszaadja vagy beállítja az utolsó sor utáni térközt egy bekezdésben öröklődés nélkül. |
| [setSpaceAfter(float value)](#setSpaceAfter-float-) | Visszaadja vagy beállítja az utolsó sor utáni térközt egy bekezdésben öröklődés nélkül. |
| [getEastAsianLineBreak()](#getEastAsianLineBreak--) | Meghatározza, hogy a kelet-ázsiai sortörést használják-e egy bekezdésben. |
| [setEastAsianLineBreak(byte value)](#setEastAsianLineBreak-byte-) | Meghatározza, hogy a kelet-ázsiai sortörést használják-e egy bekezdésben. |
| [getRightToLeft()](#getRightToLeft--) | Meghatározza, hogy a jobbról balra írásmódot használják-e egy bekezdésben. |
| [setRightToLeft(byte value)](#setRightToLeft-byte-) | Meghatározza, hogy a jobbról balra írásmódot használják-e egy bekezdésben. |
| [getLatinLineBreak()](#getLatinLineBreak--) | Meghatározza, hogy a latin sortörést használják-e egy bekezdésben. |
| [setLatinLineBreak(byte value)](#setLatinLineBreak-byte-) | Meghatározza, hogy a latin sortörést használják-e egy bekezdésben. |
| [getHangingPunctuation()](#getHangingPunctuation--) | Meghatározza, hogy függőleges központozást használnak-e egy bekezdésben. |
| [setHangingPunctuation(byte value)](#setHangingPunctuation-byte-) | Meghatározza, hogy függőleges központozást használnak-e egy bekezdésben. |
| [getMarginLeft()](#getMarginLeft--) | Visszaadja vagy beállítja a bal margót egy bekezdésben öröklődés nélkül. |
| [setMarginLeft(float value)](#setMarginLeft-float-) | Visszaadja vagy beállítja a bal margót egy bekezdésben öröklődés nélkül. |
| [getMarginRight()](#getMarginRight--) | Visszaadja vagy beállítja a jobb margót egy bekezdésben öröklődés nélkül. |
| [setMarginRight(float value)](#setMarginRight-float-) | Visszaadja vagy beállítja a jobb margót egy bekezdésben öröklődés nélkül. |
| [getIndent()](#getIndent--) | Visszaadja vagy beállítja a bekezdés első sorának behúzását/függőleges behúzását öröklődés nélkül. |
| [setIndent(float value)](#setIndent-float-) | Visszaadja vagy beállítja a bekezdés első sorának behúzását/függőleges behúzását öröklődés nélkül. |
| [getDefaultTabSize()](#getDefaultTabSize--) | Visszaadja vagy beállítja az alapértelmezett tabuláció méretét öröklődés nélkül. |
| [setDefaultTabSize(float value)](#setDefaultTabSize-float-) | Visszaadja vagy beállítja az alapértelmezett tabuláció méretét öröklődés nélkül. |
| [getTabs()](#getTabs--) | Visszaadja a bekezdés tabulációit. |
| [getFontAlignment()](#getFontAlignment--) | Visszaadja vagy beállítja a betűtípus igazítást egy bekezdésben öröklődés nélkül. |
| [setFontAlignment(int value)](#setFontAlignment-int-) | Visszaadja vagy beállítja a betűtípus igazítást egy bekezdésben öröklődés nélkül. |
| [getDefaultPortionFormat()](#getDefaultPortionFormat--) | Visszaadja a bekezdés alapértelmezett szakaszformátumát. |
| [getEffective()](#getEffective--) | Megkapja a hatékony bekezdésformázási adatokat öröklődés alkalmazásával. |
| [getVersion()](#getVersion--) |  |
### ParagraphFormat() {#ParagraphFormat--}
```
public ParagraphFormat()
```

Új példányt hoz létre a [ParagraphFormat](../../com.aspose.slides/paragraphformat) osztályból.

### getBullet() {#getBullet--}
```
public final IBulletFormat getBullet()
```

Visszaadja a bekezdés bullet formátumát. Csak olvasható [IBulletFormat](../../com.aspose.slides/ibulletformat).

**Visszatér:**
[IBulletFormat](../../com.aspose.slides/ibulletformat)
### getDepth() {#getDepth--}
```
public final short getDepth()
```

Visszaadja vagy beállítja a bekezdés mélységét. A 0 érték undefined értéket jelent. Olvasás/írás short.

**Visszatér:**
short
### setDepth(short value) {#setDepth-short-}
```
public final void setDepth(short value)
```

Visszaadja vagy beállítja a bekezdés mélységét. A 0 érték undefined értéket jelent. Olvasás/írás short.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | short |  |

### getAlignment() {#getAlignment--}
```
public final int getAlignment()
```

Visszaadja vagy beállítja a bekezdés szövegigazítását öröklődés nélkül. Olvasás/írás [TextAlignment](../../com.aspose.slides/textalignment).

--------------------

> ```
> The following sample code shows how to Align Text Paragraphs in PowerPoint Presentation.
>  
>  // Példányosít egy Presentation objektumot, amely egy PPTX fájlt képvisel
>  Presentation pres = new Presentation("ParagraphsAlignment.pptx");
>  try {
>      // Az első dia elérése
>      ISlide slide = pres.getSlides().get_Item(0);
>      // Az első és második helyőrző elérése a dián, és azok AutoShape típusúra való átkonvertálása
>      ITextFrame tf1 = ((IAutoShape)slide.getShapes().get_Item(0)).getTextFrame();
>      ITextFrame tf2 = ((IAutoShape)slide.getShapes().get_Item(1)).getTextFrame();
>      // A szöveg módosítása mindkét helyőrzőben
>      tf1.setText("Center Align by Aspose");
>      tf2.setText("Center Align by Aspose");
>      // Az első bekezdés lekérése a helyőrzőkből
>      IParagraph para1 = tf1.getParagraphs().get_Item(0);
>      IParagraph para2 = tf2.getParagraphs().get_Item(0);
>      // A szöveg bekezdés középre igazítása
>      para1.getParagraphFormat().setAlignment(TextAlignment.Center);
>      para2.getParagraphFormat().setAlignment(TextAlignment.Center);
>      // A prezentáció mentése PPTX fájlként
>      pres.save("Centeralign_out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Visszatér:**
int
### setAlignment(int value) {#setAlignment-int-}
```
public final void setAlignment(int value)
```

Visszaadja vagy beállítja a bekezdés szövegigazítását öröklődés nélkül. Olvasás/írás [TextAlignment](../../com.aspose.slides/textalignment).

--------------------

> ```
> The following sample code shows how to Align Text Paragraphs in PowerPoint Presentation.
>  
>  // Példányosít egy Presentation objektumot, amely egy PPTX fájlt képvisel
>  Presentation pres = new Presentation("ParagraphsAlignment.pptx");
>  try {
>      // Az első dia elérése
>      ISlide slide = pres.getSlides().get_Item(0);
>      // Az első és második helyőrző elérése a dián, és azok AutoShape típusúra való átkonvertálása
>      ITextFrame tf1 = ((IAutoShape)slide.getShapes().get_Item(0)).getTextFrame();
>      ITextFrame tf2 = ((IAutoShape)slide.getShapes().get_Item(1)).getTextFrame();
>      // A szöveg módosítása mindkét helyőrzőben
>      tf1.setText("Center Align by Aspose");
>      tf2.setText("Center Align by Aspose");
>      // Az első bekezdés lekérése a helyőrzőkből
>      IParagraph para1 = tf1.getParagraphs().get_Item(0);
>      IParagraph para2 = tf2.getParagraphs().get_Item(0);
>      // A szöveg bekezdés középre igazítása
>      para1.getParagraphFormat().setAlignment(TextAlignment.Center);
>      para2.getParagraphFormat().setAlignment(TextAlignment.Center);
>      //A prezentáció mentése PPTX fájlként
>      pres.save("Centeralign_out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | int |  |

### getSpaceWithin() {#getSpaceWithin--}
```
public final float getSpaceWithin()
```

Visszaadja vagy beállítja a sorok közti távolságot egy bekezdésben. A pozitív érték százalékot jelent, a negatív – pontméretet. Nincs alkalmazva öröklődés. Olvasás/írás float.

**Visszatér:**
float
### setSpaceWithin(float value) {#setSpaceWithin-float-}
```
public final void setSpaceWithin(float value)
```

Visszaadja vagy beállítja a sorok közti távolságot egy bekezdésben. A pozitív érték százalékot jelent, a negatív – pontméretet. Nincs alkalmazva öröklődés. Olvasás/írás float.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | float |  |

### getSpaceBefore() {#getSpaceBefore--}
```
public final float getSpaceBefore()
```

Visszaadja vagy beállítja az első sor előtti térközt egy bekezdésben öröklődés nélkül. A pozitív érték a betűméret százalékát adja meg, a negatív érték pontméretben adja meg a térközt. Olvasás/írás float.

**Visszatér:**
float
### setSpaceBefore(float value) {#setSpaceBefore-float-}
```
public final void setSpaceBefore(float value)
```

Visszaadja vagy beállítja az első sor előtti térközt egy bekezdésben öröklődés nélkül. A pozitív érték a betűméret százalékát adja meg, a negatív érték pontméretben adja meg a térközt. Olvasás/írás float.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | float |  |

### getSpaceAfter() {#getSpaceAfter--}
```
public final float getSpaceAfter()
```

Visszaadja vagy beállítja az utolsó sor utáni térközt egy bekezdésben öröklődés nélkül. A pozitív érték a betűméret százalékát adja meg, a negatív érték pontméretben adja meg a térközt. Olvasás/írás float.

**Visszatér:**
float
### setSpaceAfter(float value) {#setSpaceAfter-float-}
```
public final void setSpaceAfter(float value)
```

Visszaadja vagy beállítja az utolsó sor utáni térközt egy bekezdésben öröklődés nélkül. A pozitív érték a betűméret százalékát adja meg, a negatív érték pontméretben adja meg a térközt. Olvasás/írás float.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | float |  |

### getEastAsianLineBreak() {#getEastAsianLineBreak--}
```
public final byte getEastAsianLineBreak()
```

Meghatározza, hogy a kelet-ázsiai sortörést használják-e egy bekezdésben. Nincs alkalmazva öröklődés. Olvasás/írás [NullableBool](../../com.aspose.slides/nullablebool).

**Visszatér:**
byte
### setEastAsianLineBreak(byte value) {#setEastAsianLineBreak-byte-}
```
public final void setEastAsianLineBreak(byte value)
```

Meghatározza, hogy a kelet-ázsiai sortörést használják-e egy bekezdésben. Nincs alkalmazva öröklődés. Olvasás/írás [NullableBool](../../com.aspose.slides/nullablebool).

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | byte |  |

### getRightToLeft() {#getRightToLeft--}
```
public final byte getRightToLeft()
```

Meghatározza, hogy a jobbról balra írásmódot használják-e egy bekezdésben. Nincs alkalmazva öröklődés. Olvasás/írás [NullableBool](../../com.aspose.slides/nullablebool).

**Visszatér:**
byte
### setRightToLeft(byte value) {#setRightToLeft-byte-}
```
public final void setRightToLeft(byte value)
```

Meghatározza, hogy a jobbról balra írásmódot használják-e egy bekezdésben. Nincs alkalmazva öröklődés. Olvasás/írás [NullableBool](../../com.aspose.slides/nullablebool).

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | byte |  |

### getLatinLineBreak() {#getLatinLineBreak--}
```
public final byte getLatinLineBreak()
```

Meghatározza, hogy a latin sortörést használják-e egy bekezdésben. Nincs alkalmazva öröklődés. Olvasás/írás [NullableBool](../../com.aspose.slides/nullablebool).

**Visszatér:**
byte
### setLatinLineBreak(byte value) {#setLatinLineBreak-byte-}
```
public final void setLatinLineBreak(byte value)
```

Meghatározza, hogy a latin sortörést használják-e egy bekezdésben. Nincs alkalmazva öröklődés. Olvasás/írás [NullableBool](../../com.aspose.slides/nullablebool).

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | byte |  |

### getHangingPunctuation() {#getHangingPunctuation--}
```
public final byte getHangingPunctuation()
```

Meghatározza, hogy a függőleges központozást használják-e egy bekezdésben. Nincs alkalmazva öröklődés. Olvasás/írás [NullableBool](../../com.aspose.slides/nullablebool).

**Visszatér:**
byte
### setHangingPunctuation(byte value) {#setHangingPunctuation-byte-}
```
public final void setHangingPunctuation(byte value)
```

Meghatározza, hogy a függőleges központozást használják-e egy bekezdésben. Nincs alkalmazva öröklődés. Olvasás/írás [NullableBool](../../com.aspose.slides/nullablebool).

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | byte |  |

### getMarginLeft() {#getMarginLeft--}
```
public final float getMarginLeft()
```

Visszaadja vagy beállítja a bal margót egy bekezdésben öröklődés nélkül. Olvasás/írás float.

**Visszatér:**
float
### setMarginLeft(float value) {#setMarginLeft-float-}
```
public final void setMarginLeft(float value)
```

Visszaadja vagy beállítja a bal margót egy bekezdésben öröklődés nélkül. Olvasás/írás float.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | float |  |

### getMarginRight() {#getMarginRight--}
```
public final float getMarginRight()
```

Visszaadja vagy beállítja a jobb margót egy bekezdésben öröklődés nélkül. Olvasás/írás float.

**Visszatér:**
float
### setMarginRight(float value) {#setMarginRight-float-}
```
public final void setMarginRight(float value)
```

Visszaadja vagy beállítja a jobb margót egy bekezdésben öröklődés nélkül. Olvasás/írás float.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | float |  |

### getIndent() {#getIndent--}
```
public final float getIndent()
```

Visszaadja vagy beállítja a bekezdés első sorának behúzását/függőleges behúzását öröklődés nélkül. A függőleges behúzás negatív értékkel definiálható. Olvasás/írás float.

**Visszatér:**
float
### setIndent(float value) {#setIndent-float-}
```
public final void setIndent(float value)
```

Visszaadja vagy beállítja a bekezdés első sorának behúzását/függőleges behúzását öröklődés nélkül. A függőleges behúzás negatív értékkel definiálható. Olvasás/írás float.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | float |  |

### getDefaultTabSize() {#getDefaultTabSize--}
```
public final float getDefaultTabSize()
```

Visszaadja vagy beállítja az alapértelmezett tabulációméretet öröklődés nélkül. Olvasás/írás float.

**Visszatér:**
float
### setDefaultTabSize(float value) {#setDefaultTabSize-float-}
```
public final void setDefaultTabSize(float value)
```

Visszaadja vagy beállítja az alapértelmezett tabulációméretet öröklődés nélkül. Olvasás/írás float.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | float |  |

### getTabs() {#getTabs--}
```
public final ITabCollection getTabs()
```

Visszaadja a bekezdés tabulációit. Nincs alkalmazva öröklődés. Csak olvasható [ITabCollection](../../com.aspose.slides/itabcollection).

**Visszatér:**
[ITabCollection](../../com.aspose.slides/itabcollection)
### getFontAlignment() {#getFontAlignment--}
```
public final int getFontAlignment()
```

Visszaadja vagy beállítja a betűtípus igazítást egy bekezdésben öröklődés nélkül. Olvasás/írás [FontAlignment](../../com.aspose.slides/fontalignment).

**Visszatér:**
int
### setFontAlignment(int value) {#setFontAlignment-int-}
```
public final void setFontAlignment(int value)
```

Visszaadja vagy beállítja a betűtípus igazítást egy bekezdésben öröklődés nélkül. Olvasás/írás [FontAlignment](../../com.aspose.slides/fontalignment).

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | int |  |

### getDefaultPortionFormat() {#getDefaultPortionFormat--}
```
public final IPortionFormat getDefaultPortionFormat()
```

Visszaadja a bekezdés alapértelmezett szakaszformátumát. Nincs alkalmazva öröklődés. Csak olvasható [IPortionFormat](../../com.aspose.slides/iportionformat).

**Visszatér:**
[IPortionFormat](../../com.aspose.slides/iportionformat)
### getEffective() {#getEffective--}
```
public final IParagraphFormatEffectiveData getEffective()
```

Megkapja a hatékony bekezdésformázási adatokat öröklődés alkalmazásával.

--------------------

> ```
> Ez a példa bemutatja néhány hatékony bekezdésformátum tulajdonság lekérését.
>  
>  Presentation pres = new Presentation("MyPresentation.pptx");
>  try
>  {
>  	IAutoShape shape = (IAutoShape)pres.getSlides().get_Item(0).getShapes().get_Item(0);
>  	IParagraphFormatEffectiveData effectiveParagraphFormat = shape.getTextFrame().getParagraphs().get_Item(0).getParagraphFormat().getEffective();
>  	System.out.println("Text alignment: " + effectiveParagraphFormat.getAlignment());
>  	System.out.println("Indent: " + effectiveParagraphFormat.getIndent());
>  	System.out.println("Bullet type: " + effectiveParagraphFormat.getBullet().getType());
>  } finally {
>   if (pres != null) pres.dispose();
>  }
> ```


**Visszatér:**
[IParagraphFormatEffectiveData](../../com.aspose.slides/iparagraphformateffectivedata) - A [IParagraphFormatEffectiveData](../../com.aspose.slides/iparagraphformateffectivedata).
### getVersion() {#getVersion--}
```
public long getVersion()
```

Verzió. Csak olvasható long.

**Visszatér:**
long