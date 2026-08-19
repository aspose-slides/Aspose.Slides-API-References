---
title: IBulletFormat
second_title: Aspose.Slides for Java API Reference
description: Represents paragraph bullet formatting properties.
type: docs
url: /cs/com.aspose.slides/ibulletformat/
---```
public interface IBulletFormat
```

Reprezentuje vlastnosti formátování odrážek odstavce.
## Metody

| Metoda | Popis |
| --- | --- |
| [getType()](#getType--) | Vrací nebo nastavuje typ odrážky odstavce bez dědičnosti. |
| [setType(byte value)](#setType-byte-) | Vrací nebo nastavuje typ odrážky odstavce bez dědičnosti. |
| [getChar()](#getChar--) | Vrací nebo nastavuje znak odrážky odstavce bez dědičnosti. |
| [setChar(char value)](#setChar-char-) | Vrací nebo nastavuje znak odrážky odstavce bez dědičnosti. |
| [getFont()](#getFont--) | Vrací nebo nastavuje písmo odrážky odstavce bez dědičnosti. |
| [setFont(IFontData value)](#setFont-com.aspose.slides.IFontData-) | Vrací nebo nastavuje písmo odrážky odstavce bez dědičnosti. |
| [getHeight()](#getHeight--) | Vrací nebo nastavuje výšku odrážky odstavce bez dědičnosti. |
| [setHeight(float value)](#setHeight-float-) | Vrací nebo nastavuje výšku odrážky odstavce bez dědičnosti. |
| [getColor()](#getColor--) | Vrací formát barvy odrážky odstavce bez dědičnosti. |
| [getPicture()](#getPicture--) | Vrací obrázek použitý jako odrážka v odstavci bez dědičnosti. |
| [getNumberedBulletStartWith()](#getNumberedBulletStartWith--) | Vrací nebo nastavuje první číslo, které se používá pro skupinu číslovaných odrážek bez dědičnosti. |
| [setNumberedBulletStartWith(short value)](#setNumberedBulletStartWith-short-) | Vrací nebo nastavuje první číslo, které se používá pro skupinu číslovaných odrážek bez dědičnosti. |
| [getNumberedBulletStyle()](#getNumberedBulletStyle--) | Vrací nebo nastavuje styl číslované odrážky bez dědičnosti. |
| [setNumberedBulletStyle(byte value)](#setNumberedBulletStyle-byte-) | Vrací nebo nastavuje styl číslované odrážky bez dědičnosti. |
| [isBulletHardColor()](#isBulletHardColor--) | Určuje, zda má odrážka vlastní barvu nebo ji dědí z první části odstavce. |
| [setBulletHardColor(byte value)](#setBulletHardColor-byte-) | Určuje, zda má odrážka vlastní barvu nebo ji dědí z první části odstavce. |
| [isBulletHardFont()](#isBulletHardFont--) | Určuje, zda má odrážka vlastní písmo nebo jej dědí z první části odstavce. |
| [setBulletHardFont(byte value)](#setBulletHardFont-byte-) | Určuje, zda má odrážka vlastní písmo nebo jej dědí z první části odstavce. |
| [applyDefaultParagraphIndentsShifts()](#applyDefaultParagraphIndentsShifts--) | Nastavuje výchozí nenulové posuny pro efektivní odsazení odstavce a levý okraj, když jsou odrážky povoleny (jako to dělá PowerPoint při povolení odrážek/číslování odstavců). |
| [getEffective()](#getEffective--) | Získává efektivní data formátování odrážek s použitou dědičností. |
### getType() {#getType--}
```
public abstract byte getType()
```

Vrací nebo nastavuje typ odrážky odstavce bez dědičnosti. Čtení/zápis [BulletType](../../com.aspose.slides/bullettype).

**Vrací:**
byte
### setType(byte value) {#setType-byte-}
```
public abstract void setType(byte value)
```

Vrací nebo nastavuje typ odrážky odstavce bez dědičnosti. Čtení/zápis [BulletType](../../com.aspose.slides/bullettype).

**Parametry:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | byte |  |
### getChar() {#getChar--}
```
public abstract char getChar()
```

Vrací nebo nastavuje znak odrážky odstavce bez dědičnosti. Čtení/zápis char.

**Vrací:**
char
### setChar(char value) {#setChar-char-}
```
public abstract void setChar(char value)
```

Vrací nebo nastavuje znak odrážky odstavce bez dědičnosti. Čtení/zápis char.

**Parametry:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | char |  |
### getFont() {#getFont--}
```
public abstract IFontData getFont()
```

Vrací nebo nastavuje písmo odrážky odstavce bez dědičnosti. Čtení/zápis [IFontData](../../com.aspose.slides/ifontdata).

**Vrací:**
[IFontData](../../com.aspose.slides/ifontdata)
### setFont(IFontData value) {#setFont-com.aspose.slides.IFontData-}
```
public abstract void setFont(IFontData value)
```

Vrací nebo nastavuje písmo odrážky odstavce bez dědičnosti. Čtení/zápis [IFontData](../../com.aspose.slides/ifontdata).

**Parametry:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [IFontData](../../com.aspose.slides/ifontdata) |  |
### getHeight() {#getHeight--}
```
public abstract float getHeight()
```

Vrací nebo nastavuje výšku odrážky odstavce bez dědičnosti. Hodnota Float.NaN určuje, že odrážka dědí výšku z první části odstavce. Čtení/zápis float.

**Vrací:**
float
### setHeight(float value) {#setHeight-float-}
```
public abstract void setHeight(float value)
```

Vrací nebo nastavuje výšku odrážky odstavce bez dědičnosti. Hodnota Float.NaN určuje, že odrážka dědí výšku z první části odstavce. Čtení/zápis float.

**Parametry:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | float |  |
### getColor() {#getColor--}
```
public abstract IColorFormat getColor()
```

Vrací formát barvy odrážky odstavce bez dědičnosti. Pouze ke čtení [IColorFormat](../../com.aspose.slides/icolorformat).

**Vrací:**
[IColorFormat](../../com.aspose.slides/icolorformat)
### getPicture() {#getPicture--}
```
public abstract ISlidesPicture getPicture()
```

Vrací obrázek použitý jako odrážka v odstavci bez dědičnosti. Pouze ke čtení [ISlidesPicture](../../com.aspose.slides/islidespicture).

**Vrací:**
[ISlidesPicture](../../com.aspose.slides/islidespicture)
### getNumberedBulletStartWith() {#getNumberedBulletStartWith--}
```
public abstract short getNumberedBulletStartWith()
```

Vrací nebo nastavuje první číslo, které se používá pro skupinu číslovaných odrážek bez dědičnosti. Čtení/zápis short.

**Vrací:**
short
### setNumberedBulletStartWith(short value) {#setNumberedBulletStartWith-short-}
```
public abstract void setNumberedBulletStartWith(short value)
```

Vrací nebo nastavuje první číslo, které se používá pro skupinu číslovaných odrážek bez dědičnosti. Čtení/zápis short.

**Parametry:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | short |  |
### getNumberedBulletStyle() {#getNumberedBulletStyle--}
```
public abstract byte getNumberedBulletStyle()
```

Vrací nebo nastavuje styl číslované odrážky bez dědičnosti. Čtení/zápis [NumberedBulletStyle](../../com.aspose.slides/numberedbulletstyle)(\#getNumberedBulletStyle.getNumberedBulletStyle/\#setNumberedBulletStyle(byte).setNumberedBulletStyle(byte)).

**Vrací:**
byte
### setNumberedBulletStyle(byte value) {#setNumberedBulletStyle-byte-}
```
public abstract void setNumberedBulletStyle(byte value)
```

Vrací nebo nastavuje styl číslované odrážky bez dědičnosti. Čtení/zápis [NumberedBulletStyle](../../com.aspose.slides/numberedbulletstyle)(\#getNumberedBulletStyle.getNumberedBulletStyle/\#setNumberedBulletStyle(byte).setNumberedBulletStyle(byte)).

**Parametry:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | byte |  |
### isBulletHardColor() {#isBulletHardColor--}
```
public abstract byte isBulletHardColor()
```

Určuje, zda má odrážka vlastní barvu nebo ji dědí z první části odstavce. **NullableBool\#True** pokud má odrážka vlastní barvu a **NullableBool\#False** pokud odrážka dědí barvu z první části odstavce. Čtení/zápis [NullableBool](../../com.aspose.slides/nullablebool).

**Vrací:**
byte
### setBulletHardColor(byte value) {#setBulletHardColor-byte-}
```
public abstract void setBulletHardColor(byte value)
```

Určuje, zda má odrážka vlastní barvu nebo ji dědí z první části odstavce. **NullableBool\#True** pokud má odrážka vlastní barvu a **NullableBool\#False** pokud odrážka dědí barvu z první části odstavce. Čtení/zápis [NullableBool](../../com.aspose.slides/nullablebool).

**Parametry:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | byte |  |
### isBulletHardFont() {#isBulletHardFont--}
```
public abstract byte isBulletHardFont()
```

Určuje, zda má odrážka vlastní písmo nebo jej dědí z první části odstavce. **NullableBool\#True** pokud má odrážka vlastní písmo a **NullableBool\#False** pokud odrážka dědí písmo z první části odstavce. Čtení/zápis [NullableBool](../../com.aspose.slides/nullablebool).

**Vrací:**
byte
### setBulletHardFont(byte value) {#setBulletHardFont-byte-}
```
public abstract void setBulletHardFont(byte value)
```

Určuje, zda má odrážka vlastní písmo nebo jej dědí z první části odstavce. **NullableBool\#True** pokud má odrážka vlastní písmo a **NullableBool\#False** pokud odrážka dědí písmo z první části odstavce. Čtení/zápis [NullableBool](../../com.aspose.slides/nullablebool).

**Parametry:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | byte |  |
### applyDefaultParagraphIndentsShifts() {#applyDefaultParagraphIndentsShifts--}
```
public abstract void applyDefaultParagraphIndentsShifts()
```

Nastavuje výchozí nenulové posuny pro efektivní odsazení odstavce a levý okraj, když jsou odrážky povoleny (jako to dělá PowerPoint při povolení odrážek/číslování odstavců). Pokud jsou odrážky zakázány, pouze resetuje odsazení odstavce a levý okraj (jako to dělá PowerPoint při zakázání odrážek/číslování odstavců). Posuny odsazení jsou aplikovány s ohledem na aktuální kontext odrážky – IBulletFormat.Type, .NumberedBulletStyle a výšku písma první části. Nenulové posuny odsazení jsou použity na efektivní odsazení a levý okraj aktuálního odstavce (aby výsledné hodnoty byly lokální).
### getEffective() {#getEffective--}
```
public abstract IBulletFormatEffectiveData getEffective()
```

Získává efektivní data formátování odrážek s použitou dědičností.

--------------------

> ```
> Tento příklad ukazuje, jak získat některé vlastnosti efektivního formátu odrážky.
>  
>  Presentation pres = new Presentation("MyPresentation.pptx");
>  try {
>      IAutoShape shape = (IAutoShape)pres.getSlides().get_Item(0).getShapes().get_Item(0);
>      IBulletFormatEffectiveData effectiveBulletFormat = shape.getTextFrame().getParagraphs().get_Item(0).getParagraphFormat().getBullet().getEffective();
>      System.out.println("Bullet type: " + effectiveBulletFormat.getType());
>      if (effectiveBulletFormat.getType() == BulletType.Numbered)
>      {
>          System.out.println("Numbered style: " + effectiveBulletFormat.getNumberedBulletStyle());
>          System.out.println("Starting number: " + effectiveBulletFormat.getNumberedBulletStartWith());
>      }
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Vrací:**
[IBulletFormatEffectiveData](../../com.aspose.slides/ibulletformateffectivedata) - A [IBulletFormatEffectiveData](../../com.aspose.slides/ibulletformateffectivedata).