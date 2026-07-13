---
title: ParagraphFormat
second_title: Aspose.Slides pro Android přes Java API Reference
description: Tato třída obsahuje vlastnosti formátování odstavců.
type: docs
url: /cs/com.aspose.slides/paragraphformat/
---
**Dědičnost:**
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject)

**Všechny implementované rozhraní:**
[com.aspose.slides.IParagraphFormat](../../com.aspose.slides/iparagraphformat), [com.aspose.slides.IChartParagraphFormat](../../com.aspose.slides/ichartparagraphformat)
```
public final class ParagraphFormat extends PVIObject implements IParagraphFormat, IChartParagraphFormat
```

Tato třída obsahuje vlastnosti formátování odstavců. Na rozdíl od [IParagraphFormatEffectiveData](../../com.aspose.slides/iparagraphformateffectivedata) jsou všechny vlastnosti této třídy zapisovatelné.

--------------------

Tato třída se používá k vracení a manipulaci s vlastnostmi formátování odstavců definovanými pro konkrétní odstavec. To znamená, že při získávání hodnot se nepoužije dědičnost, takže ve většině případů získáte hodnoty označující „nedefinováno“.

Aby bylo možné získat efektivní hodnoty parametrů formátování včetně zděděných, je třeba použít metodu [getEffective](../../com.aspose.slides/paragraphformat\#getEffective), která vrací instanci [IParagraphFormatEffectiveData](../../com.aspose.slides/iparagraphformateffectivedata).

## Konstruktory

| Konstruktor | Popis |
| --- | --- |
| [ParagraphFormat()](#ParagraphFormat--) | Inicializuje novou instanci třídy [ParagraphFormat](../../com.aspose.slides/paragraphformat). |

## Metody

| Metoda | Popis |
| --- | --- |
| [getBullet()](#getBullet--) | Vrací formát odrážky odstavce. |
| [getDepth()](#getDepth--) | Vrací nebo nastavuje hloubku odstavce. |
| [setDepth(short value)](#setDepth-short-) | Vrací nebo nastavuje hloubku odstavce. |
| [getAlignment()](#getAlignment--) | Vrací nebo nastavuje zarovnání textu v odstavci bez dědičnosti. |
| [setAlignment(int value)](#setAlignment-int-) | Vrací nebo nastavuje zarovnání textu v odstavci bez dědičnosti. |
| [getSpaceWithin()](#getSpaceWithin--) | Vrací nebo nastavuje množství prostoru mezi základními řádky v odstavci. |
| [setSpaceWithin(float value)](#setSpaceWithin-float-) | Vrací nebo nastavuje množství prostoru mezi základními řádky v odstavci. |
| [getSpaceBefore()](#getSpaceBefore--) | Vrací nebo nastavuje množství prostoru před první řádkou v odstavci bez dědičnosti. |
| [setSpaceBefore(float value)](#setSpaceBefore-float-) | Vrací nebo nastavuje množství prostoru před první řádkou v odstavci bez dědičnosti. |
| [getSpaceAfter()](#getSpaceAfter--) | Vrací nebo nastavuje množství prostoru za posledním řádkem v odstavci bez dědičnosti. |
| [setSpaceAfter(float value)](#setSpaceAfter-float-) | Vrací nebo nastavuje množství prostoru za posledním řádkem v odstavci bez dědičnosti. |
| [getEastAsianLineBreak()](#getEastAsianLineBreak--) | Určuje, zda se v odstavci používá asijské zalomení řádku. |
| [setEastAsianLineBreak(byte value)](#setEastAsianLineBreak-byte-) | Určuje, zda se v odstavci používá asijské zalomení řádku. |
| [getRightToLeft()](#getRightToLeft--) | Určuje, zda se v odstavci používá zápis zprava doleva. |
| [setRightToLeft(byte value)](#setRightToLeft-byte-) | Určuje, zda se v odstavci používá zápis zprava doleva. |
| [getLatinLineBreak()](#getLatinLineBreak--) | Určuje, zda se v odstavci používá latinské zalomení řádku. |
| [setLatinLineBreak(byte value)](#setLatinLineBreak-byte-) | Určuje, zda se v odstavci používá latinské zalomení řádku. |
| [getHangingPunctuation()](#getHangingPunctuation--) | Určuje, zda se v odstavci používá zavěšená interpunkce. |
| [setHangingPunctuation(byte value)](#setHangingPunctuation-byte-) | Určuje, zda se v odstavci používá zavěšená interpunkce. |
| [getMarginLeft()](#getMarginLeft--) | Vrací nebo nastavuje levý okraj v odstavci bez dědičnosti. |
| [setMarginLeft(float value)](#setMarginLeft-float-) | Vrací nebo nastavuje levý okraj v odstavci bez dědičnosti. |
| [getMarginRight()](#getMarginRight--) | Vrací nebo nastavuje pravý okraj v odstavci bez dědičnosti. |
| [setMarginRight(float value)](#setMarginRight-float-) | Vrací nebo nastavuje pravý okraj v odstavci bez dědičnosti. |
| [getIndent()](#getIndent--) | Vrací nebo nastavuje odsazení první řádky/visící odsazení odstavce bez dědičnosti. |
| [setIndent(float value)](#setIndent-float-) | Vrací nebo nastavuje odsazení první řádky/visící odsazení odstavce bez dědičnosti. |
| [getDefaultTabSize()](#getDefaultTabSize--) | Vrací nebo nastavuje výchozí velikost tabulátoru bez dědičnosti. |
| [setDefaultTabSize(float value)](#setDefaultTabSize-float-) | Vrací nebo nastavuje výchozí velikost tabulátoru bez dědičnosti. |
| [getTabs()](#getTabs--) | Vrací tabulátory odstavce. |
| [getFontAlignment()](#getFontAlignment--) | Vrací nebo nastavuje zarovnání písma v odstavci bez dědičnosti. |
| [setFontAlignment(int value)](#setFontAlignment-int-) | Vrací nebo nastavuje zarovnání písma v odstavci bez dědičnosti. |
| [getDefaultPortionFormat()](#getDefaultPortionFormat--) | Vrací výchozí formát části odstavce. |
| [getEffective()](#getEffective--) | Získává efektivní data formátování odstavce s aplikovanou dědičností. |
| [getVersion()](#getVersion--) |  |

### ParagraphFormat() {#ParagraphFormat--}
```
public ParagraphFormat()
```

Inicializuje novou instanci třídy [ParagraphFormat](../../com.aspose.slides/paragraphformat).

### getBullet() {#getBullet--}
```
public final IBulletFormat getBullet()
```

Vrací formát odrážky odstavce. Pouze pro čtení [IBulletFormat](../../com.aspose.slides/ibulletformat).

**Vrací:**
[IBulletFormat](../../com.aspose.slides/ibulletformat)
### getDepth() {#getDepth--}
```
public final short getDepth()
```

Vrací nebo nastavuje hloubku odstavce. Hodnota 0 znamená nedefinovanou hodnotu. Čtení/Zápis short .

**Vrací:**
short
### setDepth(short value) {#setDepth-short-}
```
public final void setDepth(short value)
```

Vrací nebo nastavuje hloubku odstavce. Hodnota 0 znamená nedefinovanou hodnotu. Čtení/Zápis short .

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | short |  |

### getAlignment() {#getAlignment--}
```
public final int getAlignment()
```

Vrací nebo nastavuje zarovnání textu v odstavci bez dědičnosti. Čtení/Zápis [TextAlignment](../../com.aspose.slides/textalignment).

--------------------

> ```
> The following sample code shows how to Align Text Paragraphs in PowerPoint Presentation.
>  
>  // Vytvořit objekt Presentation, který představuje soubor PPTX
>  Presentation pres = new Presentation("ParagraphsAlignment.pptx");
>  try {
>      // Přístup k prvnímu snímku
>      ISlide slide = pres.getSlides().get_Item(0);
>      // Přístup k prvnímu a druhému placeholderu na snímku a přetypování na AutoShape
>      ITextFrame tf1 = ((IAutoShape)slide.getShapes().get_Item(0)).getTextFrame();
>      ITextFrame tf2 = ((IAutoShape)slide.getShapes().get_Item(1)).getTextFrame();
>      // Změna textu v obou placeholderech
>      tf1.setText("Center Align by Aspose");
>      tf2.setText("Center Align by Aspose");
>      // Získání prvního odstavce ze zástupců
>      IParagraph para1 = tf1.getParagraphs().get_Item(0);
>      IParagraph para2 = tf2.getParagraphs().get_Item(0);
>      // Zarovnání textového odstavce na střed
>      para1.getParagraphFormat().setAlignment(TextAlignment.Center);
>      para2.getParagraphFormat().setAlignment(TextAlignment.Center);
>      //Zapsání prezentace jako soubor PPTX
>      pres.save("Centeralign_out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Vrací:**
int
### setAlignment(int value) {#setAlignment-int-}
```
public final void setAlignment(int value)
```

Vrací nebo nastavuje zarovnání textu v odstavci bez dědičnosti. Čtení/Zápis [TextAlignment](../../com.aspose.slides/textalignment).

--------------------

> ```
> The following sample code shows how to Align Text Paragraphs in PowerPoint Presentation.
>  
>  // Vytvořit objekt Presentation, který představuje soubor PPTX
>  Presentation pres = new Presentation("ParagraphsAlignment.pptx");
>  try {
>      // Přístup k prvnímu snímku
>      ISlide slide = pres.getSlides().get_Item(0);
>      // Přístup k prvnímu a druhému placeholderu na snímku a přetypování na AutoShape
>      ITextFrame tf1 = ((IAutoShape)slide.getShapes().get_Item(0)).getTextFrame();
>      ITextFrame tf2 = ((IAutoShape)slide.getShapes().get_Item(1)).getTextFrame();
>      // Změna textu v obou placeholderech
>      tf1.setText("Center Align by Aspose");
>      tf2.setText("Center Align by Aspose");
>      // Získání prvního odstavce ze zástupců
>      IParagraph para1 = tf1.getParagraphs().get_Item(0);
>      IParagraph para2 = tf2.getParagraphs().get_Item(0);
>      // Zarovnání textového odstavce na střed
>      para1.getParagraphFormat().setAlignment(TextAlignment.Center);
>      para2.getParagraphFormat().setAlignment(TextAlignment.Center);
>      //Zapsání prezentace jako soubor PPTX
>      pres.save("Centeralign_out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | int |  |

### getSpaceWithin() {#getSpaceWithin--}
```
public final float getSpaceWithin()
```

Vrací nebo nastavuje množství prostoru mezi základními řádky v odstavci. Kladná hodnota znamená procenta, záporná – velikost v bodech. Dědičnost není použita. Čtení/Zápis float .

**Vrací:**
float
### setSpaceWithin(float value) {#setSpaceWithin-float-}
```
public final void setSpaceWithin(float value)
```

Vrací nebo nastavuje množství prostoru mezi základními řádky v odstavci. Kladná hodnota znamená procenta, záporná – velikost v bodech. Dědičnost není použita. Čtení/Zápis float .

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | float |  |

### getSpaceBefore() {#getSpaceBefore--}
```
public final float getSpaceBefore()
```

Vrací nebo nastavuje množství prostoru před první řádkou v odstavci bez dědičnosti. Kladná hodnota udává procento velikosti písma, které má bílý prostor zabírat. Záporná hodnota udává velikost bílého prostoru v bodech. Čtení/Zápis float .

**Vrací:**
float
### setSpaceBefore(float value) {#setSpaceBefore-float-}
```
public final void setSpaceBefore(float value)
```

Vrací nebo nastavuje množství prostoru před první řádkou v odstavci bez dědičnosti. Kladná hodnota udává procento velikosti písma, které má bílý prostor zabírat. Záporná hodnota udává velikost bílého prostoru v bodech. Čtení/Zápis float .

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | float |  |

### getSpaceAfter() {#getSpaceAfter--}
```
public final float getSpaceAfter()
```

Vrací nebo nastavuje množství prostoru za posledním řádkem v odstavci bez dědičnosti. Kladná hodnota udává procento velikosti písma, které má bílý prostor zabírat. Záporná hodnota udává velikost bílého prostoru v bodech. Čtení/Zápis float .

**Vrací:**
float
### setSpaceAfter(float value) {#setSpaceAfter-float-}
```
public final void setSpaceAfter(float value)
```

Vrací nebo nastavuje množství prostoru za posledním řádkem v odstavci bez dědičnosti. Kladná hodnota udává procento velikosti písma, které má bílý prostor zabírat. Záporná hodnota udává velikost bílého prostoru v bodech. Čtení/Zápis float .

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | float |  |

### getEastAsianLineBreak() {#getEastAsianLineBreak--}
```
public final byte getEastAsianLineBreak()
```

Určuje, zda se v odstavci používá asijské zalomení řádku. Dědičnost není použita. Čtení/Zápis [NullableBool](../../com.aspose.slides/nullablebool).

**Vrací:**
byte
### setEastAsianLineBreak(byte value) {#setEastAsianLineBreak-byte-}
```
public final void setEastAsianLineBreak(byte value)
```

Určuje, zda se v odstavci používá asijské zalomení řádku. Dědičnost není použita. Čtení/Zápis [NullableBool](../../com.aspose.slides/nullablebool).

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | byte |  |

### getRightToLeft() {#getRightToLeft--}
```
public final byte getRightToLeft()
```

Určuje, zda se v odstavci používá zápis zprava doleva. Dědičnost není použita. Čtení/Zápis [NullableBool](../../com.aspose.slides/nullablebool).

**Vrací:**
byte
### setRightToLeft(byte value) {#setRightToLeft-byte-}
```
public final void setRightToLeft(byte value)
```

Určuje, zda se v odstavci používá zápis zprava doleva. Dědičnost není použita. Čtení/Zápis [NullableBool](../../com.aspose.slides/nullablebool).

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | byte |  |

### getLatinLineBreak() {#getLatinLineBreak--}
```
public final byte getLatinLineBreak()
```

Určuje, zda se v odstavci používá latinské zalomení řádku. Dědičnost není použita. Čtení/Zápis [NullableBool](../../com.aspose.slides/nullablebool).

**Vrací:**
byte
### setLatinLineBreak(byte value) {#setLatinLineBreak-byte-}
```
public final void setLatinLineBreak(byte value)
```

Určuje, zda se v odstavci používá latinské zalomení řádku. Dědičnost není použita. Čtení/Zápis [NullableBool](../../com.aspose.slides/nullablebool).

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | byte |  |

### getHangingPunctuation() {#getHangingPunctuation--}
```
public final byte getHangingPunctuation()
```

Určuje, zda se v odstavci používá zavěšená interpunkce. Dědičnost není použita. Čtení/Zápis [NullableBool](../../com.aspose.slides/nullablebool).

**Vrací:**
byte
### setHangingPunctuation(byte value) {#setHangingPunctuation-byte-}
```
public final void setHangingPunctuation(byte value)
```

Určuje, zda se v odstavci používá zavěšená interpunkce. Dědičnost není použita. Čtení/Zápis [NullableBool](../../com.aspose.slides/nullablebool).

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | byte |  |

### getMarginLeft() {#getMarginLeft--}
```
public final float getMarginLeft()
```

Vrací nebo nastavuje levý okraj v odstavci bez dědičnosti. Čtení/Zápis float .

**Vrací:**
float
### setMarginLeft(float value) {#setMarginLeft-float-}
```
public final void setMarginLeft(float value)
```

Vrací nebo nastavuje levý okraj v odstavci bez dědičnosti. Čtení/Zápis float .

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | float |  |

### getMarginRight() {#getMarginRight--}
```
public final float getMarginRight()
```

Vrací nebo nastavuje pravý okraj v odstavci bez dědičnosti. Čtení/Zápis float .

**Vrací:**
float
### setMarginRight(float value) {#setMarginRight-float-}
```
public final void setMarginRight(float value)
```

Vrací nebo nastavuje pravý okraj v odstavci bez dědičnosti. Čtení/Zápis float .

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | float |  |

### getIndent() {#getIndent--}
```
public final float getIndent()
```

Vrací nebo nastavuje odsazení první řádky/visící odsazení odstavce bez dědičnosti. Visící odsazení lze definovat zápornými hodnotami. Čtení/Zápis float .

**Vrací:**
float
### setIndent(float value) {#setIndent-float-}
```
public final void setIndent(float value)
```

Vrací nebo nastavuje odsazení první řádky/visící odsazení odstavce bez dědičnosti. Visící odsazení lze definovat zápornými hodnotami. Čtení/Zápis float .

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | float |  |

### getDefaultTabSize() {#getDefaultTabSize--}
```
public final float getDefaultTabSize()
```

Vrací nebo nastavuje výchozí velikost tabulátoru bez dědičnosti. Čtení/Zápis float .

**Vrací:**
float
### setDefaultTabSize(float value) {#setDefaultTabSize-float-}
```
public final void setDefaultTabSize(float value)
```

Vrací nebo nastavuje výchozí velikost tabulátoru bez dědičnosti. Čtení/Zápis float .

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | float |  |

### getTabs() {#getTabs--}
```
public final ITabCollection getTabs()
```

Vrací tabulátory odstavce. Dědičnost není použita. Pouze pro čtení [ITabCollection](../../com.aspose.slides/itabcollection).

**Vrací:**
[ITabCollection](../../com.aspose.slides/itabcollection)
### getFontAlignment() {#getFontAlignment--}
```
public final int getFontAlignment()
```

Vrací nebo nastavuje zarovnání písma v odstavci bez dědičnosti. Čtení/Zápis [FontAlignment](../../com.aspose.slides/fontalignment).

**Vrací:**
int
### setFontAlignment(int value) {#setFontAlignment-int-}
```
public final void setFontAlignment(int value)
```

Vrací nebo nastavuje zarovnání písma v odstavci bez dědičnosti. Čtení/Zápis [FontAlignment](../../com.aspose.slides/fontalignment).

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | int |  |

### getDefaultPortionFormat() {#getDefaultPortionFormat--}
```
public final IPortionFormat getDefaultPortionFormat()
```

Vrací výchozí formát části odstavce. Dědičnost není použita. Pouze pro čtení [IPortionFormat](../../com.aspose.slides/iportionformat).

**Vrací:**
[IPortionFormat](../../com.aspose.slides/iportionformat)
### getEffective() {#getEffective--}
```
public final IParagraphFormatEffectiveData getEffective()
```

Získává efektivní data formátování odstavce s aplikovanou dědičností.

--------------------

> ```
> Tento příklad demonstruje získání některých efektivních vlastností formátování odstavce.
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


**Vrací:**
[IParagraphFormatEffectiveData](../../com.aspose.slides/iparagraphformateffectivedata) - A [IParagraphFormatEffectiveData](../../com.aspose.slides/iparagraphformateffectivedata).
### getVersion() {#getVersion--}
```
public long getVersion()
```

Verze. Pouze pro čtení long.

**Vrací:**
long