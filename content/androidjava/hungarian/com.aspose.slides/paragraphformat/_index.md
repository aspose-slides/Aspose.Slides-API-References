---
title: ParagraphFormat
second_title: Aspose.Slides for Android Java API referencia
description: Ez az osztály a bekezdés formázási tulajdonságait tartalmazza.
type: docs
url: /hu/com.aspose.slides/paragraphformat/
---
**Öröklés:**
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject)

**Minden megvalósított interfész:**
[com.aspose.slides.IParagraphFormat](../../com.aspose.slides/iparagraphformat), [com.aspose.slides.IChartParagraphFormat](../../com.aspose.slides/ichartparagraphformat)
```
public final class ParagraphFormat extends PVIObject implements IParagraphFormat, IChartParagraphFormat
```

Ez az osztály a bekezdés formázási tulajdonságait tartalmazza. A [IParagraphFormatEffectiveData](../../com.aspose.slides/iparagraphformateffectivedata)-től eltérően ennek az osztálynak az összes tulajdonsága írható.

--------------------

Ez az osztály a bekezdéshez definiált formázási tulajdonságok visszaadására és manipulálására szolgál. Ez azt jelenti, hogy értékek lekérésekor nem alkalmazódik öröklődés, ezért a legtöbb esetben a visszakapott érték „nem definiált”.

Az öröklődéssel együtt a tényleges formázási paraméterértékek lekéréséhez a [getEffective](../../com.aspose.slides/paragraphformat\#getEffective) metódust kell használni, amely egy [IParagraphFormatEffectiveData](../../com.aspose.slides/iparagraphformateffectivedata) példányt ad vissza.
## Konstruktorok

| Konstruktor | Leírás |
| --- | --- |
| [ParagraphFormat()](#ParagraphFormat--) | Új példányt inicializál a(z) [ParagraphFormat](../../com.aspose.slides/paragraphformat) osztályból. |
## Metódusok

| Metódus | Leírás |
| --- | --- |
| [getBullet()](#getBullet--) | Visszaadja a bekezdés golyóformátumát. |
| [getDepth()](#getDepth--) | Visszaadja vagy beállítja a bekezdés mélységét. |
| [setDepth(short value)](#setDepth-short-) | Visszaadja vagy beállítja a bekezdés mélységét. |
| [getAlignment()](#getAlignment--) | Visszaadja vagy beállítja a szöveg igazítását egy bekezdésben öröklődés nélkül. |
| [setAlignment(int value)](#setAlignment-int-) | Visszaadja vagy beállítja a szöveg igazítását egy bekezdésben öröklődés nélkül. |
| [getSpaceWithin()](#getSpaceWithin--) | Visszaadja vagy beállítja a sorok közti távolságot egy bekezdésben. |
| [setSpaceWithin(float value)](#setSpaceWithin-float-) | Visszaadja vagy beállítja a sorok közti távolságot egy bekezdésben. |
| [getSpaceBefore()](#getSpaceBefore--) | Visszaadja vagy beállítja a térközt az első sor előtt egy bekezdésben öröklődés nélkül. |
| [setSpaceBefore(float value)](#setSpaceBefore-float-) | Visszaadja vagy beállítja a térközt az első sor előtt egy bekezdésben öröklődés nélkül. |
| [getSpaceAfter()](#getSpaceAfter--) | Visszaadja vagy beállítja a térközt az utolsó sor után egy bekezdésben öröklődés nélkül. |
| [setSpaceAfter(float value)](#setSpaceAfter-float-) | Visszaadja vagy beállítja a térközt az utolsó sor után egy bekezdésben öröklődés nélkül. |
| [getEastAsianLineBreak()](#getEastAsianLineBreak--) | Megállapítja, hogy a kelet-ázsiai sortörést használják-e a bekezdésben. |
| [setEastAsianLineBreak(byte value)](#setEastAsianLineBreak-byte-) | Megállapítja, hogy a kelet-ázsiai sortörést használják-e a bekezdésben. |
| [getRightToLeft()](#getRightToLeft--) | Megállapítja, hogy a jobbról balra írást használják-e a bekezdésben. |
| [setRightToLeft(byte value)](#setRightToLeft-byte-) | Megállapítja, hogy a jobbról balra írást használják-e a bekezdésben. |
| [getLatinLineBreak()](#getLatinLineBreak--) | Megállapítja, hogy a latin sortörést használják-e a bekezdésben. |
| [setLatinLineBreak(byte value)](#setLatinLineBreak-byte-) | Megállapítja, hogy a latin sortörést használják-e a bekezdésben. |
| [getHangingPunctuation()](#getHangingPunctuation--) | Megállapítja, hogy a függő központozást használják-e a bekezdésben. |
| [setHangingPunctuation(byte value)](#setHangingPunctuation-byte-) | Megállapítja, hogy a függő központozást használják-e a bekezdésben. |
| [getMarginLeft()](#getMarginLeft--) | Visszaadja vagy beállítja a bal margót egy bekezdésben öröklődés nélkül. |
| [setMarginLeft(float value)](#setMarginLeft-float-) | Visszaadja vagy beállítja a bal margót egy bekezdésben öröklődés nélkül. |
| [getMarginRight()](#getMarginRight--) | Visszaadja vagy beállítja a jobb margót egy bekezdésben öröklődés nélkül. |
| [setMarginRight(float value)](#setMarginRight-float-) | Visszaadja vagy beállítja a jobb margót egy bekezdésben öröklődés nélkül. |
| [getIndent()](#getIndent--) | Visszaadja vagy beállítja a bekezdés első sor behúzását/függő behúzást öröklődés nélkül. |
| [setIndent(float value)](#setIndent-float-) | Visszaadja vagy beállítja a bekezdés első sor behúzását/függő behúzást öröklődés nélkül. |
| [getDefaultTabSize()](#getDefaultTabSize--) | Visszaadja vagy beállítja az alapértelmezett tabulálási méretet öröklődés nélkül. |
| [setDefaultTabSize(float value)](#setDefaultTabSize-float-) | Visszaadja vagy beállítja az alapértelmezett tabulálási méretet öröklődés nélkül. |
| [getTabs()](#getTabs--) | Visszaadja a bekezdés tabulációit. |
| [getFontAlignment()](#getFontAlignment--) | Visszaadja vagy beállítja a betűtípus igazítást egy bekezdésben öröklődés nélkül. |
| [setFontAlignment(int value)](#setFontAlignment-int-) | Visszaadja vagy beállítja a betűtípus igazítást egy bekezdésben öröklődés nélkül. |
| [getDefaultPortionFormat()](#getDefaultPortionFormat--) | Visszaadja a bekezdés alapértelmezett részformátumát. |
| [getEffective()](#getEffective--) | Megkapja a hatékony bekezdés formázási adatokat az öröklődés alkalmazásával. |
| [getVersion()](#getVersion--) |  |
### ParagraphFormat() {#ParagraphFormat--}
```
public ParagraphFormat()
```

Új példányt inicializál a(z) [ParagraphFormat](../../com.aspose.slides/paragraphformat) osztályból.

### getBullet() {#getBullet--}
```
public final IBulletFormat getBullet()
```

Visszaadja a bekezdés golyóformátumát. Csak olvasható [IBulletFormat](../../com.aspose.slides/ibulletformat).

**Visszatérési érték:**
[IBulletFormat](../../com.aspose.slides/ibulletformat)
### getDepth() {#getDepth--}
```
public final short getDepth()
```

Visszaadja vagy beállítja a bekezdés mélységét. A 0 érték nem definiált érték. Olvasás/írás  short .

**Visszatérési érték:**
short
### setDepth(short value) {#setDepth-short-}
```
public final void setDepth(short value)
```

Visszaadja vagy beállítja a bekezdés mélységét. A 0 érték nem definiált érték. Olvasás/írás  short .

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | short |  |

### getAlignment() {#getAlignment--}
```
public final int getAlignment()
```

Visszaadja vagy beállítja a szöveg igazítását egy bekezdésben öröklődés nélkül. Olvasás/írás [TextAlignment](../../com.aspose.slides/textalignment).

--------------------

> ```
> The following sample code shows how to Align Text Paragraphs in PowerPoint Presentation.
>  
>  // Példányosítsuk a Presentation objektumot, amely egy PPTX fájlt képvisel
>  Presentation pres = new Presentation("ParagraphsAlignment.pptx");
>  try {
>      // Első dia elérése
>      ISlide slide = pres.getSlides().get_Item(0);
>      // Az első és második helyőrző elérése a dián, és AutoShape típusra való átkonvertálása
>      ITextFrame tf1 = ((IAutoShape)slide.getShapes().get_Item(0)).getTextFrame();
>      ITextFrame tf2 = ((IAutoShape)slide.getShapes().get_Item(1)).getTextFrame();
>      // A szöveg módosítása mindkét helyőrzőben
>      tf1.setText("Center Align by Aspose");
>      tf2.setText("Center Align by Aspose");
>      // A helyőrzők első bekezdésének lekérése
>      IParagraph para1 = tf1.getParagraphs().get_Item(0);
>      IParagraph para2 = tf2.getParagraphs().get_Item(0);
>      // A szöveg bekezdésének középre igazítása
>      para1.getParagraphFormat().setAlignment(TextAlignment.Center);
>      para2.getParagraphFormat().setAlignment(TextAlignment.Center);
>      //A prezentáció mentése PPTX fájlként
>      pres.save("Centeralign_out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Visszatérési érték:**
int
### setAlignment(int value) {#setAlignment-int-}
```
public final void setAlignment(int value)
```

Visszaadja vagy beállítja a szöveg igazítását egy bekezdésben öröklődés nélkül. Olvasás/írás [TextAlignment](../../com.aspose.slides/textalignment).

--------------------

> ```
> The following sample code shows how to Align Text Paragraphs in PowerPoint Presentation.
>  
>  // Példányosítsuk a Presentation objektumot, amely egy PPTX fájlt képvisel
>  Presentation pres = new Presentation("ParagraphsAlignment.pptx");
>  try {
>      // Az első dia elérése
>      ISlide slide = pres.getSlides().get_Item(0);
>      // Az első és második helyőrző elérése a dián, és AutoShape típusra való átkonvertálása
>      ITextFrame tf1 = ((IAutoShape)slide.getShapes().get_Item(0)).getTextFrame();
>      ITextFrame tf2 = ((IAutoShape)slide.getShapes().get_Item(1)).getTextFrame();
>      // A szöveg módosítása mindkét helyőrzőben
>      tf1.setText("Center Align by Aspose");
>      tf2.setText("Center Align by Aspose");
>      // A helyőrzők első bekezdésének lekérése
>      IParagraph para1 = tf1.getParagraphs().get_Item(0);
>      IParagraph para2 = tf2.getParagraphs().get_Item(0);
>      // A szöveg bekezdésének középre igazítása
>      para1.getParagraphFormat().setAlignment(TextAlignment.Center);
>      para2.getParagraphFormat().setAlignment(TextAlignment.Center);
>      // A prezentáció mentése PPTX fájlként
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

Visszaadja vagy beállítja a sorok közti távolságot egy bekezdésben. A pozitív érték százalékot jelent, a negatív – pontokban megadott méretet. Nincs öröklődés. Olvasás/írás  float .

**Visszatérési érték:**
float
### setSpaceWithin(float value) {#setSpaceWithin-float-}
```
public final void setSpaceWithin(float value)
```

Visszaadja vagy beállítja a sorok közti távolságot egy bekezdésben. A pozitív érték százalékot jelent, a negatív – pontokban megadott méretet. Nincs öröklődés. Olvasás/írás  float .

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | float |  |

### getSpaceBefore() {#getSpaceBefore--}
```
public final float getSpaceBefore()
```

Visszaadja vagy beállítja a térközt az első sor előtt egy bekezdésben öröklődés nélkül. A pozitív érték a betűméret százalékát adja meg, a negatív érték pontméretben adja meg a térközt. Olvasás/írás  float .

**Visszatérési érték:**
float
### setSpaceBefore(float value) {#setSpaceBefore-float-}
```
public final void setSpaceBefore(float value)
```

Visszaadja vagy beállítja a térközt az első sor előtt egy bekezdésben öröklődés nélkül. A pozitív érték a betűméret százalékát adja meg, a negatív érték pontméretben adja meg a térközt. Olvasás/írás  float .

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | float |  |

### getSpaceAfter() {#getSpaceAfter--}
```
public final float getSpaceAfter()
```

Visszaadja vagy beállítja a térközt az utolsó sor után egy bekezdésben öröklődés nélkül. A pozitív érték a betűméret százalékát adja meg, a negatív érték pontméretben adja meg a térközt. Olvasás/írás  float .

**Visszatérési érték:**
float
### setSpaceAfter(float value) {#setSpaceAfter-float-}
```
public final void setSpaceAfter(float value)
```

Visszaadja vagy beállítja a térközt az utolsó sor után egy bekezdésben öröklődés nélkül. A pozitív érték a betűméret százalékát adja meg, a negatív érték pontméretben adja meg a térközt. Olvasás/írás  float .

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | float |  |

### getEastAsianLineBreak() {#getEastAsianLineBreak--}
```
public final byte getEastAsianLineBreak()
```

Megállapítja, hogy a kelet-ázsiai sortörést használják-e a bekezdésben. Nincs öröklődés. Olvasás/írás [NullableBool](../../com.aspose.slides/nullablebool).

**Visszatérési érték:**
byte
### setEastAsianLineBreak(byte value) {#setEastAsianLineBreak-byte-}
```
public final void setEastAsianLineBreak(byte value)
```

Megállapítja, hogy a kelet-ázsiai sortörést használják-e a bekezdésben. Nincs öröklődés. Olvasás/írás [NullableBool](../../com.aspose.slides/nullablebool).

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | byte |  |

### getRightToLeft() {#getRightToLeft--}
```
public final byte getRightToLeft()
```

Megállapítja, hogy jobbról balra írásra van-e szükség a bekezdésben. Nincs öröklődés. Olvasás/írás [NullableBool](../../com.aspose.slides/nullablebool).

**Visszatérési érték:**
byte
### setRightToLeft(byte value) {#setRightToLeft-byte-}
```
public final void setRightToLeft(byte value)
```

Megállapítja, hogy jobbról balra írásra van-e szükség a bekezdésben. Nincs öröklődés. Olvasás/írás [NullableBool](../../com.aspose.slides/nullablebool).

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | byte |  |

### getLatinLineBreak() {#getLatinLineBreak--}
```
public final byte getLatinLineBreak()
```

Megállapítja, hogy a latin sortörést használják-e a bekezdésben. Nincs öröklődés. Olvasás/írás [NullableBool](../../com.aspose.slides/nullablebool).

**Visszatérési érték:**
byte
### setLatinLineBreak(byte value) {#setLatinLineBreak-byte-}
```
public final void setLatinLineBreak(byte value)
```

Megállapítja, hogy a latin sortörést használják-e a bekezdésben. Nincs öröklődés. Olvasás/írás [NullableBool](../../com.aspose.slides/nullablebool).

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | byte |  |

### getHangingPunctuation() {#getHangingPunctuation--}
```
public final byte getHangingPunctuation()
```

Megállapítja, hogy a függő központozást használják-e a bekezdésben. Nincs öröklődés. Olvasás/írás [NullableBool](../../com.aspose.slides/nullablebool).

**Visszatérési érték:**
byte
### setHangingPunctuation(byte value) {#setHangingPunctuation-byte-}
```
public final void setHangingPunctuation(byte value)
```

Megállapítja, hogy a függő központozást használják-e a bekezdésben. Nincs öröklődés. Olvasás/írás [NullableBool](../../com.aspose.slides/nullablebool).

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | byte |  |

### getMarginLeft() {#getMarginLeft--}
```
public final float getMarginLeft()
```

Visszaadja vagy beállítja a bal margót egy bekezdésben öröklődés nélkül. Olvasás/írás  float .

**Visszatérési érték:**
float
### setMarginLeft(float value) {#setMarginLeft-float-}
```
public final void setMarginLeft(float value)
```

Visszaadja vagy beállítja a bal margót egy bekezdésben öröklődés nélkül. Olvasás/írás  float .

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | float |  |

### getMarginRight() {#getMarginRight--}
```
public final float getMarginRight()
```

Visszaadja vagy beállítja a jobb margót egy bekezdésben öröklődés nélkül. Olvasás/írás  float .

**Visszatérési érték:**
float
### setMarginRight(float value) {#setMarginRight-float-}
```
public final void setMarginRight(float value)
```

Visszaadja vagy beállítja a jobb margót egy bekezdésben öröklődés nélkül. Olvasás/írás  float .

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | float |  |

### getIndent() {#getIndent--}
```
public final float getIndent()
```

Visszaadja vagy beállítja a bekezdés első sor behúzását/függő behúzást öröklődés nélkül. A függő behúzás negatív értékkel definiálható. Olvasás/írás  float .

**Visszatérési érték:**
float
### setIndent(float value) {#setIndent-float-}
```
public final void setIndent(float value)
```

Visszaadja vagy beállítja a bekezdés első sor behúzását/függő behúzást öröklődés nélkül. A függő behúzás negatív értékkel definiálható. Olvasás/írás  float .

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | float |  |

### getDefaultTabSize() {#getDefaultTabSize--}
```
public final float getDefaultTabSize()
```

Visszaadja vagy beállítja az alapértelmezett tabulálási méretet öröklődés nélkül. Olvasás/írás  float .

**Visszatérési érték:**
float
### setDefaultTabSize(float value) {#setDefaultTabSize-float-}
```
public final void setDefaultTabSize(float value)
```

Visszaadja vagy beállítja az alapértelmezett tabulálási méretet öröklődés nélkül. Olvasás/írás  float .

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | float |  |

### getTabs() {#getTabs--}
```
public final ITabCollection getTabs()
```

Visszaadja a bekezdés tabulációit. Nincs öröklődés. Csak olvasható [ITabCollection](../../com.aspose.slides/itabcollection).

**Visszatérési érték:**
[ITabCollection](../../com.aspose.slides/itabcollection)
### getFontAlignment() {#getFontAlignment--}
```
public final int getFontAlignment()
```

Visszaadja vagy beállítja a betűtípus igazítást egy bekezdésben öröklődés nélkül. Olvasás/írás [FontAlignment](../../com.aspose.slides/fontalignment).

**Visszatérési érték:**
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

Visszaadja a bekezdés alapértelmezett részformátumát. Nincs öröklődés. Csak olvasható [IPortionFormat](../../com.aspose.slides/iportionformat).

**Visszatérési érték:**
[IPortionFormat](../../com.aspose.slides/iportionformat)
### getEffective() {#getEffective--}
```
public final IParagraphFormatEffectiveData getEffective()
```

Megkapja a hatékony bekezdés formázási adatokat az öröklődés alkalmazásával.

--------------------

> ```
> This example demonstrates getting some effective paragraph format properties.
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

**Visszatérési érték:**
[IParagraphFormatEffectiveData](../../com.aspose.slides/iparagraphformateffectivedata) - A [IParagraphFormatEffectiveData](../../com.aspose.slides/iparagraphformateffectivedata).
### getVersion() {#getVersion--}
```
public long getVersion()
```

Verzió. Csak olvasható long.

**Visszatérési érték:**
long