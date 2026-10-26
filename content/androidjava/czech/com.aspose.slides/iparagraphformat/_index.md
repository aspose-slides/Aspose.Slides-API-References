---
title: IParagraphFormat
second_title: Aspose.Slides for Android via Java API Reference
description: Třída obsahuje vlastnosti formátování odstavce.
type: docs
url: /cs/com.aspose.slides/iparagraphformat/
---```
public interface IParagraphFormat
```

Tato třída obsahuje vlastnosti formátování odstavce. Na rozdíl od [IParagraphFormatEffectiveData](../../com.aspose.slides/iparagraphformateffectivedata) jsou všechny vlastnosti této třídy zapisovatelné.

--------------------

Tato třída se používá k vracení a manipulaci s vlastnostmi formátování odstavce definovanými pro konkrétní odstavec. To znamená, že při získávání hodnot se nepoužije dědičnost, takže ve většině případů získáte hodnoty označující „nedefinováno“.

Chcete-li získat efektivní hodnoty formátovacích parametrů včetně zděděných, musíte použít metodu [getEffective](../../com.aspose.slides/iparagraphformat\#getEffective), která vrací instanci [IParagraphFormatEffectiveData](../../com.aspose.slides/iparagraphformateffectivedata).

## Metody

| Metoda | Popis |
| --- | --- |
| [getBullet()](#getBullet--) | Vrací formát odrážky odstavce. |
| [getDepth()](#getDepth--) | Vrací nebo nastavuje hloubku odstavce. |
| [setDepth(short value)](#setDepth-short-) | Vrací nebo nastavuje hloubku odstavce. |
| [getAlignment()](#getAlignment--) | Vrací nebo nastavuje zarovnání textu v odstavci bez dědičnosti. |
| [setAlignment(int value)](#setAlignment-int-) | Vrací nebo nastavuje zarovnání textu v odstavci bez dědičnosti. |
| [getSpaceWithin()](#getSpaceWithin--) | Vrací nebo nastavuje množství mezery mezi základními řádky v odstavci. |
| [setSpaceWithin(float value)](#setSpaceWithin-float-) | Vrací nebo nastavuje množství mezery mezi základními řádky v odstavci. |
| [getSpaceBefore()](#getSpaceBefore--) | Vrací nebo nastavuje množství mezery před první řádkou v odstavci bez dědičnosti. |
| [setSpaceBefore(float value)](#setSpaceBefore-float-) | Vrací nebo nastavuje množství mezery před první řádkou v odstavci bez dědičnosti. |
| [getSpaceAfter()](#getSpaceAfter--) | Vrací nebo nastavuje množství mezery za poslední řádkou v odstavci bez dědičnosti. |
| [setSpaceAfter(float value)](#setSpaceAfter-float-) | Vrací nebo nastavuje množství mezery za poslední řádkou v odstavci bez dědičnosti. |
| [getEastAsianLineBreak()](#getEastAsianLineBreak--) | Určuje, zda se v odstavci používá východní asijské zalomení řádku. |
| [setEastAsianLineBreak(byte value)](#setEastAsianLineBreak-byte-) | Určuje, zda se v odstavci používá východní asijské zalomení řádku. |
| [getRightToLeft()](#getRightToLeft--) | Určuje, zda se v odstavci používá zápis zprava doleva. |
| [setRightToLeft(byte value)](#setRightToLeft-byte-) | Určuje, zda se v odstavci používá zápis zprava doleva. |
| [getLatinLineBreak()](#getLatinLineBreak--) | Určuje, zda se v odstavci používá latinské zalomení řádku. |
| [setLatinLineBreak(byte value)](#setLatinLineBreak-byte-) | Určuje, zda se v odstavci používá latinské zalomení řádku. |
| [getHangingPunctuation()](#getHangingPunctuation--) | Určuje, zda se v odstavci používá závěsná interpunkce. |
| [setHangingPunctuation(byte value)](#setHangingPunctuation-byte-) | Určuje, zda se v odstavci používá závěsná interpunkce. |
| [getMarginLeft()](#getMarginLeft--) | Vrací nebo nastavuje levý okraj v odstavci bez dědičnosti. |
| [setMarginLeft(float value)](#setMarginLeft-float-) | Vrací nebo nastavuje levý okraj v odstavci bez dědičnosti. |
| [getMarginRight()](#getMarginRight--) | Vrací nebo nastavuje pravý okraj v odstavci bez dědičnosti. |
| [setMarginRight(float value)](#setMarginRight-float-) | Vrací nebo nastavuje pravý okraj v odstavci bez dědičnosti. |
| [getIndent()](#getIndent--) | Vrací nebo nastavuje první řádkové odsazení/závěsné odsazení odstavce bez dědičnosti. |
| [setIndent(float value)](#setIndent-float-) | Vrací nebo nastavuje první řádkové odsazení/závěsné odsazení odstavce bez dědičnosti. |
| [getDefaultTabSize()](#getDefaultTabSize--) | Vrací nebo nastavuje výchozí velikost tabulátoru bez dědičnosti. |
| [setDefaultTabSize(float value)](#setDefaultTabSize-float-) | Vrací nebo nastavuje výchozí velikost tabulátoru bez dědičnosti. |
| [getTabs()](#getTabs--) | Vrací tabulátory odstavce. |
| [getFontAlignment()](#getFontAlignment--) | Vrací nebo nastavuje zarovnání písma v odstavci bez dědičnosti. |
| [setFontAlignment(int value)](#setFontAlignment-int-) | Vrací nebo nastavuje zarovnání písma v odstavci bez dědičnosti. |
| [getDefaultPortionFormat()](#getDefaultPortionFormat--) | Vrací výchozí formát úseku odstavce. |
| [getEffective()](#getEffective--) | Získává efektivní data formátování odstavce s aplikovanou dědičností. |

### getBullet() {#getBullet--}
```
public abstract IBulletFormat getBullet()
```

Vrací formát odrážky odstavce. Pouze pro čtení [IBulletFormat](../../com.aspose.slides/ibulletformat).

**Vrací:**
[IBulletFormat](../../com.aspose.slides/ibulletformat)

### getDepth() {#getDepth--}
```
public abstract short getDepth()
```

Vrací nebo nastavuje hloubku odstavce. Hodnota 0 znamená nedefinovanou hodnotu. Čtení/zápis short.

**Vrací:**
short

### setDepth(short value) {#setDepth-short-}
```
public abstract void setDepth(short value)
```

Vrací nebo nastavuje hloubku odstavce. Hodnota 0 znamená nedefinovanou hodnotu. Čtení/zápis short.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | short |  |

### getAlignment() {#getAlignment--}
```
public abstract int getAlignment()
```

Vrací nebo nastavuje zarovnání textu v odstavci bez dědičnosti. Čtení/zápis [TextAlignment](../../com.aspose.slides/textalignment).

**Vrací:**
int

### setAlignment(int value) {#setAlignment-int-}
```
public abstract void setAlignment(int value)
```

Vrací nebo nastavuje zarovnání textu v odstavci bez dědičnosti. Čtení/zápis [TextAlignment](../../com.aspose.slides/textalignment).

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | int |  |

### getSpaceWithin() {#getSpaceWithin--}
```
public abstract float getSpaceWithin()
```

Vrací nebo nastavuje množství mezery mezi základními řádky v odstavci. Kladná hodnota znamená procenta, záporná – velikost v bodech. Není použita dědičnost. Čtení/zápis float.

**Vrací:**
float

### setSpaceWithin(float value) {#setSpaceWithin-float-}
```
public abstract void setSpaceWithin(float value)
```

Vrací nebo nastavuje množství mezery mezi základními řádky v odstavci. Kladná hodnota znamená procenta, záporná – velikost v bodech. Není použita dědičnost. Čtení/zápis float.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | float |  |

### getSpaceBefore() {#getSpaceBefore--}
```
public abstract float getSpaceBefore()
```

Vrací nebo nastavuje množství mezery před první řádkou v odstavci bez dědičnosti. Kladná hodnota udává procento velikosti písma, kterou by měla bílá mezera zabírat. Záporná hodnota udává velikost bílé mezery v bodech. Čtení/zápis float.

**Vrací:**
float

### setSpaceBefore(float value) {#setSpaceBefore-float-}
```
public abstract void setSpaceBefore(float value)
```

Vrací nebo nastavuje množství mezery před první řádkou v odstavci bez dědičnosti. Kladná hodnota udává procento velikosti písma, kterou by měla bílá mezera zabírat. Záporná hodnota udává velikost bílé mezery v bodech. Čtení/zápis float.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | float |  |

### getSpaceAfter() {#getSpaceAfter--}
```
public abstract float getSpaceAfter()
```

Vrací nebo nastavuje množství mezery za poslední řádkou v odstavci bez dědičnosti. Kladná hodnota udává procento velikosti písma, kterou by měla bílá mezera zabírat. Záporná hodnota udává velikost bílé mezery v bodech. Čtení/zápis float.

**Vrací:**
float

### setSpaceAfter(float value) {#setSpaceAfter-float-}
```
public abstract void setSpaceAfter(float value)
```

Vrací nebo nastavuje množství mezery za poslední řádkou v odstavci bez dědičnosti. Kladná hodnota udává procento velikosti písma, kterou by měla bílá mezera zabírat. Záporná hodnota udává velikost bílé mezery v bodech. Čtení/zápis float.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | float |  |

### getEastAsianLineBreak() {#getEastAsianLineBreak--}
```
public abstract byte getEastAsianLineBreak()
```

Určuje, zda se v odstavci používá východní asijské zalomení řádku. Není použita dědičnost. Čtení/zápis [NullableBool](../../com.aspose.slides/nullablebool).

**Vrací:**
byte

### setEastAsianLineBreak(byte value) {#setEastAsianLineBreak-byte-}
```
public abstract void setEastAsianLineBreak(byte value)
```

Určuje, zda se v odstavci používá východní asijské zalomení řádku. Není použita dědičnost. Čtení/zápis [NullableBool](../../com.aspose.slides/nullablebool).

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | byte |  |

### getRightToLeft() {#getRightToLeft--}
```
public abstract byte getRightToLeft()
```

Určuje, zda se v odstavci používá zápis zprava doleva. Není použita dědičnost. Čtení/zápis [NullableBool](../../com.aspose.slides/nullablebool).

**Vrací:**
byte

### setRightToLeft(byte value) {#setRightToLeft-byte-}
```
public abstract void setRightToLeft(byte value)
```

Určuje, zda se v odstavci používá zápis zprava doleva. Není použita dědičnost. Čtení/zápis [NullableBool](../../com.aspose.slides/nullablebool).

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | byte |  |

### getLatinLineBreak() {#getLatinLineBreak--}
```
public abstract byte getLatinLineBreak()
```

Určuje, zda se v odstavci používá latinské zalomení řádku. Není použita dědičnost. Čtení/zápis [NullableBool](../../com.aspose.slides/nullablebool).

**Vrací:**
byte

### setLatinLineBreak(byte value) {#setLatinLineBreak-byte-}
```
public abstract void setLatinLineBreak(byte value)
```

Určuje, zda se v odstavci používá latinské zalomení řádku. Není použita dědičnost. Čtení/zápis [NullableBool](../../com.aspose.slides/nullablebool).

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | byte |  |

### getHangingPunctuation() {#getHangingPunctuation--}
```
public abstract byte getHangingPunctuation()
```

Určuje, zda se v odstavci používá závěsná interpunkce. Není použita dědičnost. Čtení/zápis [NullableBool](../../com.aspose.slides/nullablebool).

**Vrací:**
byte

### setHangingPunctuation(byte value) {#setHangingPunctuation-byte-}
```
public abstract void setHangingPunctuation(byte value)
```

Určuje, zda se v odstavci používá závěsná interpunkce. Není použita dědičnost. Čtení/zápis [NullableBool](../../com.aspose.slides/nullablebool).

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | byte |  |

### getMarginLeft() {#getMarginLeft--}
```
public abstract float getMarginLeft()
```

Vrací nebo nastavuje levý okraj v odstavci bez dědičnosti. Čtení/zápis float.

**Vrací:**
float

### setMarginLeft(float value) {#setMarginLeft-float-}
```
public abstract void setMarginLeft(float value)
```

Vrací nebo nastavuje levý okraj v odstavci bez dědičnosti. Čtení/zápis float.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | float |  |

### getMarginRight() {#getMarginRight--}
```
public abstract float getMarginRight()
```

Vrací nebo nastavuje pravý okraj v odstavci bez dědičnosti. Čtení/zápis float.

**Vrací:**
float

### setMarginRight(float value) {#setMarginRight-float-}
```
public abstract void setMarginRight(float value)
```

Vrací nebo nastavuje pravý okraj v odstavci bez dědičnosti. Čtení/zápis float.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | float |  |

### getIndent() {#getIndent--}
```
public abstract float getIndent()
```

Vrací nebo nastavuje první řádkové odsazení/závěsné odsazení odstavce bez dědičnosti. Závěsné odsazení lze definovat zápornými hodnotami. Čtení/zápis float.

**Vrací:**
float

### setIndent(float value) {#setIndent-float-}
```
public abstract void setIndent(float value)
```

Vrací nebo nastavuje první řádkové odsazení/závěsné odsazení odstavce bez dědičnosti. Závěsné odsazení lze definovat zápornými hodnotami. Čtení/zápis float.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | float |  |

### getDefaultTabSize() {#getDefaultTabSize--}
```
public abstract float getDefaultTabSize()
```

Vrací nebo nastavuje výchozí velikost tabulátoru bez dědičnosti. Čtení/zápis float.

**Vrací:**
float

### setDefaultTabSize(float value) {#setDefaultTabSize-float-}
```
public abstract void setDefaultTabSize(float value)
```

Vrací nebo nastavuje výchozí velikost tabulátoru bez dědičnosti. Čtení/zápis float.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | float |  |

### getTabs() {#getTabs--}
```
public abstract ITabCollection getTabs()
```

Vrací tabulátory odstavce. Není použita dědičnost. Pouze pro čtení [ITabCollection](../../com.aspose.slides/itabcollection).

**Vrací:**
[ITabCollection](../../com.aspose.slides/itabcollection)

### getFontAlignment() {#getFontAlignment--}
```
public abstract int getFontAlignment()
```

Vrací nebo nastavuje zarovnání písma v odstavci bez dědičnosti. Čtení/zápis [FontAlignment](../../com.aspose.slides/fontalignment).

**Vrací:**
int

### setFontAlignment(int value) {#setFontAlignment-int-}
```
public abstract void setFontAlignment(int value)
```

Vrací nebo nastavuje zarovnání písma v odstavci bez dědičnosti. Čtení/zápis [FontAlignment](../../com.aspose.slides/fontalignment).

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | int |  |

### getDefaultPortionFormat() {#getDefaultPortionFormat--}
```
public abstract IPortionFormat getDefaultPortionFormat()
```

Vrací výchozí formát úseku odstavce. Není použita dědičnost. Pouze pro čtení [IPortionFormat](../../com.aspose.slides/iportionformat).

**Vrací:**
[IPortionFormat](../../com.aspose.slides/iportionformat)

### getEffective() {#getEffective--}
```
public abstract IParagraphFormatEffectiveData getEffective()
```

Získává efektivní data formátování odstavce s aplikovanou dědičností.

**Vrací:**
[IParagraphFormatEffectiveData](../../com.aspose.slides/iparagraphformateffectivedata) - A [IParagraphFormatEffectiveData](../../com.aspose.slides/iparagraphformateffectivedata).