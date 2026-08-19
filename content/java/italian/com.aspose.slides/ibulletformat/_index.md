---
title: IBulletFormat
second_title: Aspose.Slides for Java API Reference
description: Rappresenta le proprietà di formattazione dei punti elenco del paragrafo.
type: docs
url: /it/com.aspose.slides/ibulletformat/
---```
public interface IBulletFormat
```

Rappresenta le proprietà di formattazione dei punti elenco del paragrafo.
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getType()](#getType--) | Restituisce o imposta il tipo di punto elenco di un paragrafo senza ereditarietà. |
| [setType(byte value)](#setType-byte-) | Restituisce o imposta il tipo di punto elenco di un paragrafo senza ereditarietà. |
| [getChar()](#getChar--) | Restituisce o imposta il carattere del punto elenco di un paragrafo senza ereditarietà. |
| [setChar(char value)](#setChar-char-) | Restituisce o imposta il carattere del punto elenco di un paragrafo senza ereditarietà. |
| [getFont()](#getFont--) | Restituisce o imposta il font del punto elenco di un paragrafo senza ereditarietà. |
| [setFont(IFontData value)](#setFont-com.aspose.slides.IFontData-) | Restituisce o imposta il font del punto elenco di un paragrafo senza ereditarietà. |
| [getHeight()](#getHeight--) | Restituisce o imposta l'altezza del punto elenco di un paragrafo senza ereditarietà. |
| [setHeight(float value)](#setHeight-float-) | Restituisce o imposta l'altezza del punto elenco di un paragrafo senza ereditarietà. |
| [getColor()](#getColor--) | Restituisce il formato colore di un punto elenco di un paragrafo senza ereditarietà. |
| [getPicture()](#getPicture--) | Restituisce l'immagine usata come punto elenco in un paragrafo senza ereditarietà. |
| [getNumberedBulletStartWith()](#getNumberedBulletStartWith--) | Restituisce o imposta il primo numero utilizzato per il gruppo di punti elenco numerati senza ereditarietà. |
| [setNumberedBulletStartWith(short value)](#setNumberedBulletStartWith-short-) | Restituisce o imposta il primo numero utilizzato per il gruppo di punti elenco numerati senza ereditarietà. |
| [getNumberedBulletStyle()](#getNumberedBulletStyle--) | Restituisce o imposta lo stile di un punto elenco numerato senza ereditarietà. |
| [setNumberedBulletStyle(byte value)](#setNumberedBulletStyle-byte-) | Restituisce o imposta lo stile di un punto elenco numerato senza ereditarietà. |
| [isBulletHardColor()](#isBulletHardColor--) | Determina se il punto elenco ha un colore proprio o lo eredita dalla prima porzione del paragrafo. |
| [setBulletHardColor(byte value)](#setBulletHardColor-byte-) | Determina se il punto elenco ha un colore proprio o lo eredita dalla prima porzione del paragrafo. |
| [isBulletHardFont()](#isBulletHardFont--) | Determina se il punto elenco ha un font proprio o lo eredita dalla prima porzione del paragrafo. |
| [setBulletHardFont(byte value)](#setBulletHardFont-byte-) | Determina se il punto elenco ha un font proprio o lo eredita dalla prima porzione del paragrafo. |
| [applyDefaultParagraphIndentsShifts()](#applyDefaultParagraphIndentsShifts--) | Imposta le spostamenti predefiniti diversi da zero per l'Indentazione e il MarginLeft effettivi del paragrafo quando i punti elenco sono abilitati (come fa PowerPoint se si abilita la punteggiatura/numerazione dei paragrafi). |
| [getEffective()](#getEffective--) | Ottiene i dati di formattazione del punto elenco effettivi con l'ereditarietà applicata. |
### getType() {#getType--}
```
public abstract byte getType()
```

Restituisce o imposta il tipo di punto elenco di un paragrafo senza ereditarietà. Lettura/scrittura [BulletType](../../com.aspose.slides/bullettype).

**Restituisce:**
byte
### setType(byte value) {#setType-byte-}
```
public abstract void setType(byte value)
```

Restituisce o imposta il tipo di punto elenco di un paragrafo senza ereditarietà. Lettura/scrittura [BulletType](../../com.aspose.slides/bullettype).

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | byte |  |
### getChar() {#getChar--}
```
public abstract char getChar()
```

Restituisce o imposta il carattere del punto elenco di un paragrafo senza ereditarietà. Lettura/scrittura char.

**Restituisce:**
char
### setChar(char value) {#setChar-char-}
```
public abstract void setChar(char value)
```

Restituisce o imposta il carattere del punto elenco di un paragrafo senza ereditarietà. Lettura/scrittura char.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | char |  |
### getFont() {#getFont--}
```
public abstract IFontData getFont()
```

Restituisce o imposta il font del punto elenco di un paragrafo senza ereditarietà. Lettura/scrittura [IFontData](../../com.aspose.slides/ifontdata).

**Restituisce:**
[IFontData](../../com.aspose.slides/ifontdata)
### setFont(IFontData value) {#setFont-com.aspose.slides.IFontData-}
```
public abstract void setFont(IFontData value)
```

Restituisce o imposta il font del punto elenco di un paragrafo senza ereditarietà. Lettura/scrittura [IFontData](../../com.aspose.slides/ifontdata).

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [IFontData](../../com.aspose.slides/ifontdata) |  |
### getHeight() {#getHeight--}
```
public abstract float getHeight()
```

Restituisce o imposta l'altezza del punto elenco di un paragrafo senza ereditarietà. Il valore Float.NaN determina che il punto elenco eredita l'altezza dalla prima porzione del paragrafo. Lettura/scrittura float.

**Restituisce:**
float
### setHeight(float value) {#setHeight-float-}
```
public abstract void setHeight(float value)
```

Restituisce o imposta l'altezza del punto elenco di un paragrafo senza ereditarietà. Il valore Float.NaN determina che il punto elenco eredita l'altezza dalla prima porzione del paragrafo. Lettura/scrittura float.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | float |  |
### getColor() {#getColor--}
```
public abstract IColorFormat getColor()
```

Restituisce il formato colore di un punto elenco di un paragrafo senza ereditarietà. Solo lettura [IColorFormat](../../com.aspose.slides/icolorformat).

**Restituisce:**
[IColorFormat](../../com.aspose.slides/icolorformat)
### getPicture() {#getPicture--}
```
public abstract ISlidesPicture getPicture()
```

Restituisce l'immagine usata come punto elenco in un paragrafo senza ereditarietà. Solo lettura [ISlidesPicture](../../com.aspose.slides/islidespicture).

**Restituisce:**
[ISlidesPicture](../../com.aspose.slides/islidespicture)
### getNumberedBulletStartWith() {#getNumberedBulletStartWith--}
```
public abstract short getNumberedBulletStartWith()
```

Restituisce o imposta il primo numero utilizzato per il gruppo di punti elenco numerati senza ereditarietà. Lettura/scrittura short.

**Restituisce:**
short
### setNumberedBulletStartWith(short value) {#setNumberedBulletStartWith-short-}
```
public abstract void setNumberedBulletStartWith(short value)
```

Restituisce o imposta il primo numero utilizzato per il gruppo di punti elenco numerati senza ereditarietà. Lettura/scrittura short.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | short |  |
### getNumberedBulletStyle() {#getNumberedBulletStyle--}
```
public abstract byte getNumberedBulletStyle()
```

Restituisce o imposta lo stile di un punto elenco numerato senza ereditarietà. Lettura/scrittura [NumberedBulletStyle](../../com.aspose.slides/numberedbulletstyle)(\#getNumberedBulletStyle.getNumberedBulletStyle/\#setNumberedBulletStyle(byte).setNumberedBulletStyle(byte)).

**Restituisce:**
byte
### setNumberedBulletStyle(byte value) {#setNumberedBulletStyle-byte-}
```
public abstract void setNumberedBulletStyle(byte value)
```

Restituisce o imposta lo stile di un punto elenco numerato senza ereditarietà. Lettura/scrittura [NumberedBulletStyle](../../com.aspose.slides/numberedbulletstyle)(\#getNumberedBulletStyle.getNumberedBulletStyle/\#setNumberedBulletStyle(byte).setNumberedBulletStyle(byte)).

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | byte |  |
### isBulletHardColor() {#isBulletHardColor--}
```
public abstract byte isBulletHardColor()
```

Determina se il punto elenco ha un colore proprio o lo eredita dalla prima porzione del paragrafo. **NullableBool\#True** se il punto elenco ha un colore proprio e **NullableBool\#False** se il punto elenco eredita il colore dalla prima porzione del paragrafo. Lettura/scrittura [NullableBool](../../com.aspose.slides/nullablebool).

**Restituisce:**
byte
### setBulletHardColor(byte value) {#setBulletHardColor-byte-}
```
public abstract void setBulletHardColor(byte value)
```

Determina se il punto elenco ha un colore proprio o lo eredita dalla prima porzione del paragrafo. **NullableBool\#True** se il punto elenco ha un colore proprio e **NullableBool\#False** se il punto elenco eredita il colore dalla prima porzione del paragrafo. Lettura/scrittura [NullableBool](../../com.aspose.slides/nullablebool).

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | byte |  |
### isBulletHardFont() {#isBulletHardFont--}
```
public abstract byte isBulletHardFont()
```

Determina se il punto elenco ha un font proprio o lo eredita dalla prima porzione del paragrafo. **NullableBool\#True** se il punto elenco ha un font proprio e **NullableBool\#False** se il punto elenco eredita il font dalla prima porzione del paragrafo. Lettura/scrittura [NullableBool](../../com.aspose.slides/nullablebool).

**Restituisce:**
byte
### setBulletHardFont(byte value) {#setBulletHardFont-byte-}
```
public abstract void setBulletHardFont(byte value)
```

Determina se il punto elenco ha un font proprio o lo eredita dalla prima porzione del paragrafo. **NullableBool\#True** se il punto elenco ha un font proprio e **NullableBool\#False** se il punto elenco eredita il font dalla prima porzione del paragrafo. Lettura/scrittura [NullableBool](../../com.aspose.slides/nullablebool).

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | byte |  |
### applyDefaultParagraphIndentsShifts() {#applyDefaultParagraphIndentsShifts--}
```
public abstract void applyDefaultParagraphIndentsShifts()
```

Imposta le spostamenti predefiniti diversi da zero per l'Indentazione e il MarginLeft effettivi del paragrafo quando i punti elenco sono abilitati (come fa PowerPoint se si abilita la punteggiatura/numerazione dei paragrafi). Se i punti elenco sono disabilitati, si resetta semplicemente l'Indentazione e il MarginLeft del paragrafo (come fa PowerPoint se si disabilita la punteggiatura/numerazione dei paragrafi). Gli spostamenti di indentazione vengono applicati in base al contesto corrente del punto elenco – IBulletFormat.Type, .NumberedBulletStyle e FontHeight della prima porzione. Gli spostamenti di indentazione diversi da zero vengono applicati a Indentazione e MarginLeft effettivi del paragrafo corrente (rendendo i valori di risultato valori locali).
### getEffective() {#getEffective--}
```
public abstract IBulletFormatEffectiveData getEffective()
```

Ottiene i dati di formattazione del punto elenco effettivi con l'ereditarietà applicata.

--------------------

> ```
> This example demonstrates getting some effective bullet format properties.
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

**Restituisce:**
[IBulletFormatEffectiveData](../../com.aspose.slides/ibulletformateffectivedata) - un [IBulletFormatEffectiveData](../../com.aspose.slides/ibulletformateffectivedata).