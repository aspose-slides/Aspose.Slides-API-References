---
title: ParagraphFormat
second_title: Aspose.Slides pro Java – reference API
description: Tato třída obsahuje vlastnosti formátování odstavce.
type: docs
url: /cs/com.aspose.slides/paragraphformat/
---
**Dědičnost:**
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject)

**Všechna implementovaná rozhraní:**
[com.aspose.slides.IParagraphFormat](../../com.aspose.slides/iparagraphformat), [com.aspose.slides.IChartParagraphFormat](../../com.aspose.slides/ichartparagraphformat)
```
public final class ParagraphFormat extends PVIObject implements IParagraphFormat, IChartParagraphFormat
```

Tato třída obsahuje vlastnosti formátování odstavce. Na rozdíl od [IParagraphFormatEffectiveData](../../com.aspose.slides/iparagraphformateffectivedata) jsou všechny vlastnosti této třídy zapisovatelné.

--------------------

Tato třída se používá k vrácení a manipulaci s vlastnostmi formátování odstavce definovanými pro konkrétní odstavec. To znamená, že při získávání hodnot se nepoužívá dědičnost, takže ve většině případů získáte hodnoty označující „ndefinováno“.

Aby bylo možné získat efektivní hodnoty parametrů formátování včetně děděných, je třeba použít metodu [getEffective](../../com.aspose.slides/paragraphformat\#getEffective), která vrací instanci [IParagraphFormatEffectiveData](../../com.aspose.slides/iparagraphformateffectivedata).
## Konstruktory

| Konstruktor | Popis |
| --- | --- |
| [ParagraphFormat()](#ParagraphFormat--) | Inicializuje novou instanci třídy [ParagraphFormat](../../com.aspose.slides/paragraphformat). |
## Metody

| Metoda | Popis |
| --- | --- |
| [getBullet()](#getBullet--) | Vrátí formát odrážky odstavce. |
| [getDepth()](#getDepth--) | Vrátí nebo nastaví hloubku odstavce. |
| [setDepth(short value)](#setDepth-short-) | Vrátí nebo nastaví hloubku odstavce. |
| [getAlignment()](#getAlignment--) | Vrátí nebo nastaví zarovnání textu v odstavci bez dědičnosti. |
| [setAlignment(int value)](#setAlignment-int-) | Vrátí nebo nastaví zarovnání textu v odstavci bez dědičnosti. |
| [getSpaceWithin()](#getSpaceWithin--) | Vrátí nebo nastaví množství prostoru mezi základními řádky v odstavci. |
| [setSpaceWithin(float value)](#setSpaceWithin-float-) | Vrátí nebo nastaví množství prostoru mezi základními řádky v odstavci. |
| [getSpaceBefore()](#getSpaceBefore--) | Vrátí nebo nastaví množství prostoru před první řádkou v odstavci bez dědičnosti. |
| [setSpaceBefore(float value)](#setSpaceBefore-float-) | Vrátí nebo nastaví množství prostoru před první řádkou v odstavci bez dědičnosti. |
| [getSpaceAfter()](#getSpaceAfter--) | Vrátí nebo nastaví množství prostoru za poslední řádkou v odstavci bez dědičnosti. |
| [setSpaceAfter(float value)](#setSpaceAfter-float-) | Vrátí nebo nastaví množství prostoru za poslední řádkou v odstavci bez dědičnosti. |
| [getEastAsianLineBreak()](#getEastAsianLineBreak--) | Určuje, zda se v odstavci používá východoasijské zalomení řádku. |
| [setEastAsianLineBreak(byte value)](#setEastAsianLineBreak-byte-) | Určuje, zda se v odstavci používá východoasijské zalomení řádku. |
| [getRightToLeft()](#getRightToLeft--) | Určuje, zda se v odstavci používá zápis zprava doleva. |
| [setRightToLeft(byte value)](#setRightToLeft-byte-) | Určuje, zda se v odstavci používá zápis zprava doleva. |
| [getLatinLineBreak()](#getLatinLineBreak--) | Určuje, zda se v odstavci používá latinské zalomení řádku. |
| [setLatinLineBreak(byte value)](#setLatinLineBreak-byte-) | Určuje, zda se v odstavci používá latinské zalomení řádku. |
| [getHangingPunctuation()](#getHangingPunctuation--) | Určuje, zda se v odstavci používá visící interpunkce. |
| [setHangingPunctuation(byte value)](#setHangingPunctuation-byte-) | Určuje, zda se v odstavci používá visící interpunkce. |
| [getMarginLeft()](#getMarginLeft--) | Vrátí nebo nastaví levý okraj v odstavci bez dědičnosti. |
| [setMarginLeft(float value)](#setMarginLeft-float-) | Vrátí nebo nastaví levý okraj v odstavci bez dědičnosti. |
| [getMarginRight()](#getMarginRight--) | Vrátí nebo nastaví pravý okraj v odstavci bez dědičnosti. |
| [setMarginRight(float value)](#setMarginRight-float-) | Vrátí nebo nastaví pravý okraj v odstavci bez dědičnosti. |
| [getIndent()](#getIndent--) | Vrátí nebo nastaví odsazení první řádky/visící odsazení odstavce bez dědičnosti. |
| [setIndent(float value)](#setIndent-float-) | Vrátí nebo nastaví odsazení první řádky/visící odsazení odstavce bez dědičnosti. |
| [getDefaultTabSize()](#getDefaultTabSize--) | Vrátí nebo nastaví výchozí velikost tabulátoru bez dědičnosti. |
| [setDefaultTabSize(float value)](#setDefaultTabSize-float-) | Vrátí nebo nastaví výchozí velikost tabulátoru bez dědičnosti. |
| [getTabs()](#getTabs--) | Vrátí tabulátory odstavce. |
| [getFontAlignment()](#getFontAlignment--) | Vrátí nebo nastaví zarovnání písma v odstavci bez dědičnosti. |
| [setFontAlignment(int value)](#setFontAlignment-int-) | Vrátí nebo nastaví zarovnání písma v odstavci bez dědičnosti. |
| [getDefaultPortionFormat()](#getDefaultPortionFormat--) | Vrátí výchozí formát úseku odstavce. |
| [getEffective()](#getEffective--) | Získá efektivní data formátování odstavce s aplikovanou dědičností. |
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

Vrátí formát odrážky odstavce. Pouze pro čtení [IBulletFormat](../../com.aspose.slides/ibulletformat).

**Vrací:**
[IBulletFormat](../../com.aspose.slides/ibulletformat)
### getDepth() {#getDepth--}
```
public final short getDepth()
```

Vrátí nebo nastaví hloubku odstavce. Hodnota 0 znamená nedefinovanou hodnotu. Čtení/zápis  short .

**Vrací:**
short
### setDepth(short value) {#setDepth-short-}
```
public final void setDepth(short value)
```

Vrátí nebo nastaví hloubku odstavce. Hodnota 0 znamená nedefinovanou hodnotu. Čtení/zápis  short .

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | short |  |
### getAlignment() {#getAlignment--}
```
public final int getAlignment()
```

Vrátí nebo nastaví zarovnání textu v odstavci bez dědičnosti. Čtení/zápis [TextAlignment](../../com.aspose.slides/textalignment).

--------------------

> ```
> The following sample code shows how to Align Text Paragraphs in PowerPoint Presentation.
>  
>  // Vytvořte objekt Presentation, který reprezentuje soubor PPTX
>  try {
>      // Přístup k prvnímu snímku
>      ISlide slide = pres.getSlides().get_Item(0);
>      // Přístup k prvnímu a druhému placeholderu na snímku a převod na AutoShape
>      ITextFrame tf1 = ((IAutoShape)slide.getShapes().get_Item(0)).getTextFrame();
>      ITextFrame tf2 = ((IAutoShape)slide.getShapes().get_Item(1)).getTextFrame();
>      // Změňte text v obou placeholderech
>      tf1.setText("Center Align by Aspose");
>      tf2.setText("Center Align by Aspose");
>      // Získání prvního odstavce z placeholderů
>      IParagraph para1 = tf1.getParagraphs().get_Item(0);
>      IParagraph para2 = tf2.getParagraphs().get_Item(0);
>      // Zarovnání textového odstavce na střed
>      para1.getParagraphFormat().setAlignment(TextAlignment.Center);
>      para2.getParagraphFormat().setAlignment(TextAlignment.Center);
>      // Uložení prezentace jako soubor PPTX
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

Vrátí nebo nastaví zarovnání textu v odstavci bez dědičnosti. Čtení/zápis [TextAlignment](../../com.aspose.slides/textalignment).

--------------------

> ```
> The following sample code shows how to Align Text Paragraphs in PowerPoint Presentation.
>  
>  // Vytvořte objekt Presentation, který reprezentuje soubor PPTX
>  Presentation pres = new Presentation("ParagraphsAlignment.pptx");
>  try {
>      // Přístup k prvnímu snímku
>      ISlide slide = pres.getSlides().get_Item(0);
>      // Přístup k prvnímu a druhému placeholderu v snímku a přetypování na AutoShape
>      ITextFrame tf1 = ((IAutoShape)slide.getShapes().get_Item(0)).getTextFrame();
>      ITextFrame tf2 = ((IAutoShape)slide.getShapes().get_Item(1)).getTextFrame();
>      // Změna textu v obou placeholderách
>      tf1.setText("Center Align by Aspose");
>      tf2.setText("Center Align by Aspose");
>      // Získání prvního odstavce z placeholderů
>      IParagraph para1 = tf1.getParagraphs().get_Item(0);
>      IParagraph para2 = tf2.getParagraphs().get_Item(0);
>      // Zarovnání textového odstavce na střed
>      para1.getParagraphFormat().setAlignment(TextAlignment.Center);
>      para2.getParagraphFormat().setAlignment(TextAlignment.Center);
>      //Ukládání prezentace jako soubor PPTX
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

Vrátí nebo nastaví množství prostoru mezi základními řádky v odstavci. Kladná hodnota značí procenta, záporná – velikost v bodech. Není použita dědičnost. Čtení/zápis  float .

**Vrací:**
float
### setSpaceWithin(float value) {#setSpaceWithin-float-}
```
public final void setSpaceWithin(float value)
```

Vrátí nebo nastaví množství prostoru mezi základními řádky v odstavci. Kladná hodnota značí procenta, záporná – velikost v bodech. Není použita dědičnost. Čtení/zápis  float .

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | float |  |
### getSpaceBefore() {#getSpaceBefore--}
```
public final float getSpaceBefore()
```

Vrátí nebo nastaví množství prostoru před první řádkou v odstavci bez dědičnosti. Kladná hodnota určuje procento velikosti písma, kterou má bílý prostor zabírat. Záporná hodnota určuje velikost bílého prostoru v bodech. Čtení/zápis  float .

**Vrací:**
float
### setSpaceBefore(float value) {#setSpaceBefore-float-}
```
public final void setSpaceBefore(float value)
```

Vrátí nebo nastaví množství prostoru před první řádkou v odstavci bez dědičnosti. Kladná hodnota určuje procento velikosti písma, kterou má bílý prostor zabírat. Záporná hodnota určuje velikost bílého prostoru v bodech. Čtení/zápis  float .

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | float |  |
### getSpaceAfter() {#getSpaceAfter--}
```
public final float getSpaceAfter()
```

Vrátí nebo nastaví množství prostoru za poslední řádkou v odstavci bez dědičnosti. Kladná hodnota určuje procento velikosti písma, kterou má bílý prostor zabírat. Záporná hodnota určuje velikost bílého prostoru v bodech. Čtení/zápis  float .

**Vrací:**
float
### setSpaceAfter(float value) {#setSpaceAfter-float-}
```
public final void setSpaceAfter(float value)
```

Vrátí nebo nastaví množství prostoru za poslední řádkou v odstavci bez dědičnosti. Kladná hodnota určuje procento velikosti písma, kterou má bílý prostor zabírat. Záporná hodnota určuje velikost bílého prostoru v bodech. Čtení/zápis  float .

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | float |  |
### getEastAsianLineBreak() {#getEastAsianLineBreak--}
```
public final byte getEastAsianLineBreak()
```

Určuje, zda se v odstavci používá východoasijské zalomení řádku. Není použita dědičnost. Čtení/zápis [NullableBool](../../com.aspose.slides/nullablebool).

**Vrací:**
byte
### setEastAsianLineBreak(byte value) {#setEastAsianLineBreak-byte-}
```
public final void setEastAsianLineBreak(byte value)
```

Určuje, zda se v odstavci používá východoasijské zalomení řádku. Není použita dědičnost. Čtení/zápis [NullableBool](../../com.aspose.slides/nullablebool).

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | byte |  |
### getRightToLeft() {#getRightToLeft--}
```
public final byte getRightToLeft()
```

Určuje, zda se v odstavci používá zápis zprava doleva. Není použita dědičnost. Čtení/zápis [NullableBool](../../com.aspose.slides/nullablebool).

**Vrací:**
byte
### setRightToLeft(byte value) {#setRightToLeft-byte-}
```
public final void setRightToLeft(byte value)
```

Určuje, zda se v odstavci používá zápis zprava doleva. Není použita dědičnost. Čtení/zápis [NullableBool](../../com.aspose.slides/nullablebool).

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | byte |  |
### getLatinLineBreak() {#getLatinLineBreak--}
```
public final byte getLatinLineBreak()
```

Určuje, zda se v odstavci používá latinské zalomení řádku. Není použita dědičnost. Čtení/zápis [NullableBool](../../com.aspose.slides/nullablebool).

**Vrací:**
byte
### setLatinLineBreak(byte value) {#setLatinLineBreak-byte-}
```
public final void setLatinLineBreak(byte value)
```

Určuje, zda se v odstavci používá latinské zalomení řádku. Není použita dědičnost. Čtení/zápis [NullableBool](../../com.aspose.slides/nullablebool).

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | byte |  |
### getHangingPunctuation() {#getHangingPunctuation--}
```
public final byte getHangingPunctuation()
```

Určuje, zda se v odstavci používá visící interpunkce. Není použita dědičnost. Čtení/zápis [NullableBool](../../com.aspose.slides/nullablebool).

**Vrací:**
byte
### setHangingPunctuation(byte value) {#setHangingPunctuation-byte-}
```
public final void setHangingPunctuation(byte value)
```

Určuje, zda se v odstavci používá visící interpunkce. Není použita dědičnost. Čtení/zápis [NullableBool](../../com.aspose.slides/nullablebool).

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | byte |  |
### getMarginLeft() {#getMarginLeft--}
```
public final float getMarginLeft()
```

Vrátí nebo nastaví levý okraj v odstavci bez dědičnosti. Čtení/zápis  float .

**Vrací:**
float
### setMarginLeft(float value) {#setMarginLeft-float-}
```
public final void setMarginLeft(float value)
```

Vrátí nebo nastaví levý okraj v odstavci bez dědičnosti. Čtení/zápis  float .

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | float |  |
### getMarginRight() {#getMarginRight--}
```
public final float getMarginRight()
```

Vrátí nebo nastaví pravý okraj v odstavci bez dědičnosti. Čtení/zápis  float .

**Vrací:**
float
### setMarginRight(float value) {#setMarginRight-float-}
```
public final void setMarginRight(float value)
```

Vrátí nebo nastaví pravý okraj v odstavci bez dědičnosti. Čtení/zápis  float .

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | float |  |
### getIndent() {#getIndent--}
```
public final float getIndent()
```

Vrátí nebo nastaví odsazení první řádky/visící odsazení odstavce bez dědičnosti. Visící odsazení může být definováno zápornými hodnotami. Čtení/zápis  float .

**Vrací:**
float
### setIndent(float value) {#setIndent-float-}
```
public final void setIndent(float value)
```

Vrátí nebo nastaví odsazení první řádky/visící odsazení odstavce bez dědičnosti. Visící odsazení může být definováno zápornými hodnotami. Čtení/zápis  float .

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | float |  |
### getDefaultTabSize() {#getDefaultTabSize--}
```
public final float getDefaultTabSize()
```

Vrátí nebo nastaví výchozí velikost tabulátoru bez dědičnosti. Čtení/zápis  float .

**Vrací:**
float
### setDefaultTabSize(float value) {#setDefaultTabSize-float-}
```
public final void setDefaultTabSize(float value)
```

Vrátí nebo nastaví výchozí velikost tabulátoru bez dědičnosti. Čtení/zápis  float .

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | float |  |
### getTabs() {#getTabs--}
```
public final ITabCollection getTabs()
```

Vrátí tabulátory odstavce. Není použita dědičnost. Pouze pro čtení [ITabCollection](../../com.aspose.slides/itabcollection).

**Vrací:**
[ITabCollection](../../com.aspose.slides/itabcollection)
### getFontAlignment() {#getFontAlignment--}
```
public final int getFontAlignment()
```

Vrátí nebo nastaví zarovnání písma v odstavci bez dědičnosti. Čtení/zápis [FontAlignment](../../com.aspose.slides/fontalignment).

**Vrací:**
int
### setFontAlignment(int value) {#setFontAlignment-int-}
```
public final void setFontAlignment(int value)
```

Vrátí nebo nastaví zarovnání písma v odstavci bez dědičnosti. Čtení/zápis [FontAlignment](../../com.aspose.slides/fontalignment).

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | int |  |
### getDefaultPortionFormat() {#getDefaultPortionFormat--}
```
public final IPortionFormat getDefaultPortionFormat()
```

Vrátí výchozí formát úseku odstavce. Není použita dědičnost. Pouze pro čtení [IPortionFormat](../../com.aspose.slides/iportionformat).

**Vrací:**
[IPortionFormat](../../com.aspose.slides/iportionformat)
### getEffective() {#getEffective--}
```
public final IParagraphFormatEffectiveData getEffective()
```

Získá efektivní data formátování odstavce s aplikovanou dědičností.

--------------------

> ```
> Tento příklad ukazuje, jak získat některé efektivní vlastnosti formátování odstavce.
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


**Vrací:** [IParagraphFormatEffectiveData](../../com.aspose.slides/iparagraphformateffectivedata) - A [IParagraphFormatEffectiveData](../../com.aspose.slides/iparagraphformateffectivedata).
### getVersion() {#getVersion--}
```
public long getVersion()
```

Verze. Pouze pro čtení long.

**Vrací:** long