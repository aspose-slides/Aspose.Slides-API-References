---
title: BulletFormat
second_title: Aspose.Slides pro Java API Reference
description: Reprezentuje vlastnosti formátování odrážek odstavce.
type: docs
url: /cs/com.aspose.slides/bulletformat/
---
**Dědičnost:**
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject)

**Všechny implementované rozhraní:**
[com.aspose.slides.IBulletFormat](../../com.aspose.slides/ibulletformat)
```
public final class BulletFormat extends PVIObject implements IBulletFormat
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
| [getNumberedBulletStartWith()](#getNumberedBulletStartWith--) | Vrací nebo nastavuje první číslo, které se používá pro skupinu číslovaných odrážek bez dědičnosti. |
| [setNumberedBulletStartWith(short value)](#setNumberedBulletStartWith-short-) | Vrací nebo nastavuje první číslo, které se používá pro skupinu číslovaných odrážek bez dědičnosti. |
| [getNumberedBulletStyle()](#getNumberedBulletStyle--) | Vrací nebo nastavuje styl číslované odrážky bez dědičnosti. |
| [setNumberedBulletStyle(byte value)](#setNumberedBulletStyle-byte-) | Vrací nebo nastavuje styl číslované odrážky bez dědičnosti. |
| [isBulletHardColor()](#isBulletHardColor--) | Určuje, zda má odrážka vlastní barvu nebo ji dědí z první části odstavce. |
| [setBulletHardColor(byte value)](#setBulletHardColor-byte-) | Určuje, zda má odrážka vlastní barvu nebo ji dědí z první části odstavce. |
| [isBulletHardFont()](#isBulletHardFont--) | Určuje, zda má odrážka vlastní písmo nebo je děděno z první části odstavce. |
| [setBulletHardFont(byte value)](#setBulletHardFont-byte-) | Určuje, zda má odrážka vlastní písmo nebo je děděno z první části odstavce. |
| [getPicture()](#getPicture--) | Vrací obrázek použitý jako odrážka v odstavci bez dědičnosti. |
| [applyDefaultParagraphIndentsShifts()](#applyDefaultParagraphIndentsShifts--) | Nastavuje výchozí nenulové posuny pro efektivní odsazení odstavce (Indent) a MarginLeft, když jsou odrážky povoleny (jako to dělá PowerPoint při povolení odrážek/číslování v odstavci). |
| [getEffective()](#getEffective--) | Získává efektivní data formátování odrážky s aplikovanou dědičností. |
| [getVersion()](#getVersion--) |  |
### getType() {#getType--}
```
public final byte getType()
```

Vrací nebo nastavuje typ odrážky odstavce bez dědičnosti. Číst/zapisovat [BulletType](../../com.aspose.slides/bullettype).

**Vrací:**
byte
### setType(byte value) {#setType-byte-}
```
public final void setType(byte value)
```

Vrací nebo nastavuje typ odrážky odstavce bez dědičnosti. Číst/zapisovat [BulletType](../../com.aspose.slides/bullettype).

**Parametry:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | byte |  |
### getChar() {#getChar--}
```
public final char getChar()
```

Vrací nebo nastavuje znak odrážky odstavce bez dědičnosti. Číst/zapisovat char .

**Vrací:**
char
### setChar(char value) {#setChar-char-}
```
public final void setChar(char value)
```

Vrací nebo nastavuje znak odrážky odstavce bez dědičnosti. Číst/zapisovat char .

**Parametry:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | char |  |
### getFont() {#getFont--}
```
public final IFontData getFont()
```

Vrací nebo nastavuje písmo odrážky odstavce bez dědičnosti. Číst/zapisovat [IFontData](../../com.aspose.slides/ifontdata).

**Vrací:**
[IFontData](../../com.aspose.slides/ifontdata)
### setFont(IFontData value) {#setFont-com.aspose.slides.IFontData-}
```
public final void setFont(IFontData value)
```

Vrací nebo nastavuje písmo odrážky odstavce bez dědičnosti. Číst/zapisovat [IFontData](../../com.aspose.slides/ifontdata).

**Parametry:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [IFontData](../../com.aspose.slides/ifontdata) |  |
### getHeight() {#getHeight--}
```
public final float getHeight()
```

Vrací nebo nastavuje výšku odrážky odstavce bez dědičnosti. Hodnota Float.NaN určuje, že odrážka dědí výšku z první části odstavce. Číst/zapisovat float .

--------------------

Negativní hodnota výšky znamená, že výška je zadána v bodech, a pozitivní hodnota znamená, že výška je procentem okolního textu.

**Vrací:**
float
### setHeight(float value) {#setHeight-float-}
```
public final void setHeight(float value)
```

Vrací nebo nastavuje výšku odrážky odstavce bez dědičnosti. Hodnota Float.NaN určuje, že odrážka dědí výšku z první části odstavce. Číst/zapisovat float .

--------------------

Negativní hodnota výšky znamená, že výška je zadána v bodech, a pozitivní hodnota znamená, že výška je procentem okolního textu.

**Parametry:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | float |  |
### getColor() {#getColor--}
```
public final IColorFormat getColor()
```

Vrací formát barvy odrážky odstavce bez dědičnosti. Pouze pro čtení [IColorFormat](../../com.aspose.slides/icolorformat).

**Vrací:**
[IColorFormat](../../com.aspose.slides/icolorformat)
### getNumberedBulletStartWith() {#getNumberedBulletStartWith--}
```
public final short getNumberedBulletStartWith()
```

Vrací nebo nastavuje první číslo, které se používá pro skupinu číslovaných odrážek bez dědičnosti. Číst/zapisovat short .

**Vrací:**
short
### setNumberedBulletStartWith(short value) {#setNumberedBulletStartWith-short-}
```
public final void setNumberedBulletStartWith(short value)
```

Vrací nebo nastavuje první číslo, které se používá pro skupinu číslovaných odrážek bez dědičnosti. Číst/zapisovat short .

**Parametry:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | short |  |
### getNumberedBulletStyle() {#getNumberedBulletStyle--}
```
public final byte getNumberedBulletStyle()
```

Vrací nebo nastavuje styl číslované odrážky bez dědičnosti. Číst/zapisovat [NumberedBulletStyle](../../com.aspose.slides/numberedbulletstyle).

**Vrací:**
byte
### setNumberedBulletStyle(byte value) {#setNumberedBulletStyle-byte-}
```
public final void setNumberedBulletStyle(byte value)
```

Vrací nebo nastavuje styl číslované odrážky bez dědičnosti. Číst/zapisovat [NumberedBulletStyle](../../com.aspose.slides/numberedbulletstyle).

**Parametry:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | byte |  |
### isBulletHardColor() {#isBulletHardColor--}
```
public final byte isBulletHardColor()
```

Určuje, zda má odrážka vlastní barvu nebo ji dědí z první části odstavce. **NullableBool.True** pokud má odrážka vlastní barvu a **NullableBool.False** pokud odrážka dědí barvu z první části odstavce. Číst/zapisovat [NullableBool](../../com.aspose.slides/nullablebool).

**Vrací:**
byte
### setBulletHardColor(byte value) {#setBulletHardColor-byte-}
```
public final void setBulletHardColor(byte value)
```

Určuje, zda má odrážka vlastní barvu nebo ji dědí z první části odstavce. **NullableBool.True** pokud má odrážka vlastní barvu a **NullableBool.False** pokud odrážka dědí barvu z první části odstavce. Číst/zapisovat [NullableBool](../../com.aspose.slides/nullablebool).

**Parametry:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | byte |  |
### isBulletHardFont() {#isBulletHardFont--}
```
public final byte isBulletHardFont()
```

Určuje, zda má odrážka vlastní písmo nebo je děděno z první části odstavce. **NullableBool.True** pokud má odrážka vlastní písmo a **NullableBool.False** pokud odrážka dědí písmo z první části odstavce. Číst/zapisovat [NullableBool](../../com.aspose.slides/nullablebool).

**Vrací:**
byte
### setBulletHardFont(byte value) {#setBulletHardFont-byte-}
```
public final void setBulletHardFont(byte value)
```

Určuje, zda má odrážka vlastní písmo nebo je děděno z první části odstavce. **NullableBool.True** pokud má odrážka vlastní písmo a **NullableBool.False** pokud odrážka dědí písmo z první části odstavce. Číst/zapisovat [NullableBool](../../com.aspose.slides/nullablebool).

**Parametry:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | byte |  |
### getPicture() {#getPicture--}
```
public final ISlidesPicture getPicture()
```

Vrací obrázek použitý jako odrážka v odstavci bez dědičnosti. Pouze pro čtení [ISlidesPicture](../../com.aspose.slides/islidespicture).

**Vrací:**
[ISlidesPicture](../../com.aspose.slides/islidespicture)
### applyDefaultParagraphIndentsShifts() {#applyDefaultParagraphIndentsShifts--}
```
public final void applyDefaultParagraphIndentsShifts()
```

Nastavuje výchozí nenulové posuny pro efektivní odsazení odstavce (Indent) a MarginLeft, když jsou odrážky povoleny (jako to dělá PowerPoint při povolení odrážek/číslování v odstavci). Pokud jsou odrážky zakázány, pouze resetuje odsazení odstavce (Indent) a MarginLeft (jako to dělá PowerPoint při zakázání odrážek/číslování v odstavci). Posuny odsazení se aplikují vzhledem k aktuálnímu kontextu odrážky – IBulletFormat.Type, .NumberedBulletStyle a FontHeight první části. Nenulové posuny odsazení jsou aplikovány na efektivní Indent a MarginLeft aktuálního odstavce (výsledné hodnoty jsou lokální).
### getEffective() {#getEffective--}
```
public final IBulletFormatEffectiveData getEffective()
```

Získává efektivní data formátování odrážky s aplikovanou dědičností.

--------------------

> ```
> Tento příklad ukazuje získání některých efektivních vlastností formátu odrážky.
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
[IBulletFormatEffectiveData](../../com.aspose.slides/ibulletformateffectivedata) - Jedna [IBulletFormatEffectiveData](../../com.aspose.slides/ibulletformateffectivedata).
### getVersion() {#getVersion--}
```
public long getVersion()
```

Verze. Pouze pro čtení long.

**Vrací:**
long