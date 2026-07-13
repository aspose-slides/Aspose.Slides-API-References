---
title: BulletFormat
second_title: Aspose.Slides per Android tramite Riferimento API Java
description: Rappresenta le proprietà di formattazione dei punti elenco del paragrafo.
type: docs
url: /it/com.aspose.slides/bulletformat/
---
**Ereditarietà:**
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject)

**Tutte le interfacce implementate:**
[com.aspose.slides.IBulletFormat](../../com.aspose.slides/ibulletformat)
```
public final class BulletFormat extends PVIObject implements IBulletFormat
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
| [getNumberedBulletStartWith()](#getNumberedBulletStartWith--) | Restituisce o imposta il primo numero utilizzato per il gruppo di punti elenco numerati senza ereditarietà. |
| [setNumberedBulletStartWith(short value)](#setNumberedBulletStartWith-short-) | Restituisce o imposta il primo numero utilizzato per il gruppo di punti elenco numerati senza ereditarietà. |
| [getNumberedBulletStyle()](#getNumberedBulletStyle--) | Restituisce o imposta lo stile di un punto elenco numerato senza ereditarietà. |
| [setNumberedBulletStyle(byte value)](#setNumberedBulletStyle-byte-) | Restituisce o imposta lo stile di un punto elenco numerato senza ereditarietà. |
| [isBulletHardColor()](#isBulletHardColor--) | Determina se il punto elenco ha un colore proprio o lo eredita dalla prima porzione del paragrafo. |
| [setBulletHardColor(byte value)](#setBulletHardColor-byte-) | Determina se il punto elenco ha un colore proprio o lo eredita dalla prima porzione del paragrafo. |
| [isBulletHardFont()](#isBulletHardFont--) | Determina se il punto elenco ha un font proprio o lo eredita dalla prima porzione del paragrafo. |
| [setBulletHardFont(byte value)](#setBulletHardFont-byte-) | Determina se il punto elenco ha un font proprio o lo eredita dalla prima porzione del paragrafo. |
| [getPicture()](#getPicture--) | Restituisce l'immagine usata come punto elenco in un paragrafo senza ereditarietà. |
| [applyDefaultParagraphIndentsShifts()](#applyDefaultParagraphIndentsShifts--) | Imposta gli spostamenti non zero predefiniti per l'Indent efficace del paragrafo e MarginLeft quando i punti elenco sono abilitati (come fa PowerPoint se si attivano i punti elenco/numerazione). |
| [getEffective()](#getEffective--) | Ottiene i dati di formattazione del punto elenco efficaci con l'ereditarietà applicata. |
| [getVersion()](#getVersion--) |  |

### getType() {#getType--}
```
public final byte getType()
```

Restituisce o imposta il tipo di punto elenco di un paragrafo senza ereditarietà. Lettura/scrittura [BulletType](../../com.aspose.slides/bullettype).

**Restituisce:**
byte

### setType(byte value) {#setType-byte-}
```
public final void setType(byte value)
```

Restituisce o imposta il tipo di punto elenco di un paragrafo senza ereditarietà. Lettura/scrittura [BulletType](../../com.aspose.slides/bullettype).

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | byte |  |

### getChar() {#getChar--}
```
public final char getChar()
```

Restituisce o imposta il carattere del punto elenco di un paragrafo senza ereditarietà. Lettura/scrittura  char .

**Restituisce:**
char

### setChar(char value) {#setChar-char-}
```
public final void setChar(char value)
```

Restituisce o imposta il carattere del punto elenco di un paragrafo senza ereditarietà. Lettura/scrittura  char .

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | char |  |

### getFont() {#getFont--}
```
public final IFontData getFont()
```

Restituisce o imposta il font del punto elenco di un paragrafo senza ereditarietà. Lettura/scrittura [IFontData](../../com.aspose.slides/ifontdata).

**Restituisce:**
[IFontData](../../com.aspose.slides/ifontdata)

### setFont(IFontData value) {#setFont-com.aspose.slides.IFontData-}
```
public final void setFont(IFontData value)
```

Restituisce o imposta il font del punto elenco di un paragrafo senza ereditarietà. Lettura/scrittura [IFontData](../../com.aspose.slides/ifontdata).

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [IFontData](../../com.aspose.slides/ifontdata) |  |

### getHeight() {#getHeight--}
```
public final float getHeight()
```

Restituisce o imposta l'altezza del punto elenco di un paragrafo senza ereditarietà. Il valore Float.NaN determina che il punto elenco eredita l'altezza dalla prima porzione del paragrafo. Lettura/scrittura  float .

--------------------

Un valore di altezza negativo indica che l'altezza è espressa in punti, mentre un valore positivo indica che l'altezza è una percentuale del testo circostante.

**Restituisce:**
float

### setHeight(float value) {#setHeight-float-}
```
public final void setHeight(float value)
```

Restituisce o imposta l'altezza del punto elenco di un paragrafo senza ereditarietà. Il valore Float.NaN determina che il punto elenco eredita l'altezza dalla prima porzione del paragrafo. Lettura/scrittura  float .

--------------------

Un valore di altezza negativo indica che l'altezza è espressa in punti, mentre un valore positivo indica che l'altezza è una percentuale del testo circostante.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | float |  |

### getColor() {#getColor--}
```
public final IColorFormat getColor()
```

Restituisce il formato colore di un punto elenco di un paragrafo senza ereditarietà. Solo lettura [IColorFormat](../../com.aspose.slides/icolorformat).

**Restituisce:**
[IColorFormat](../../com.aspose.slides/icolorformat)

### getNumberedBulletStartWith() {#getNumberedBulletStartWith--}
```
public final short getNumberedBulletStartWith()
```

Restituisce o imposta il primo numero utilizzato per il gruppo di punti elenco numerati senza ereditarietà. Lettura/scrittura  short .

**Restituisce:**
short

### setNumberedBulletStartWith(short value) {#setNumberedBulletStartWith-short-}
```
public final void setNumberedBulletStartWith(short value)
```

Restituisce o imposta il primo numero utilizzato per il gruppo di punti elenco numerati senza ereditarietà. Lettura/scrittura  short .

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | short |  |

### getNumberedBulletStyle() {#getNumberedBulletStyle--}
```
public final byte getNumberedBulletStyle()
```

Restituisce o imposta lo stile di un punto elenco numerato senza ereditarietà. Lettura/scrittura [NumberedBulletStyle](../../com.aspose.slides/numberedbulletstyle).

**Restituisce:**
byte

### setNumberedBulletStyle(byte value) {#setNumberedBulletStyle-byte-}
```
public final void setNumberedBulletStyle(byte value)
```

Restituisce o imposta lo stile di un punto elenco numerato senza ereditarietà. Lettura/scrittura [NumberedBulletStyle](../../com.aspose.slides/numberedbulletstyle).

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | byte |  |

### isBulletHardColor() {#isBulletHardColor--}
```
public final byte isBulletHardColor()
```

Determina se il punto elenco ha un colore proprio o lo eredita dalla prima porzione del paragrafo. **NullableBool.True** if bullet has own color and **NullableBool.False** if bullet inherits color from the first portion in the paragraph. Lettura/scrittura [NullableBool](../../com.aspose.slides/nullablebool).

**Restituisce:**
byte

### setBulletHardColor(byte value) {#setBulletHardColor-byte-}
```
public final void setBulletHardColor(byte value)
```

Determina se il punto elenco ha un colore proprio o lo eredita dalla prima porzione del paragrafo. **NullableBool.True** if bullet has own color and **NullableBool.False** if bullet inherits color from the first portion in the paragraph. Lettura/scrittura [NullableBool](../../com.aspose.slides/nullablebool).

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | byte |  |

### isBulletHardFont() {#isBulletHardFont--}
```
public final byte isBulletHardFont()
```

Determina se il punto elenco ha un font proprio o lo eredita dalla prima porzione del paragrafo. **NullableBool.True** if bullet has own font and **NullableBool.False** if bullet inherits font from the first portion in the paragraph. Lettura/scrittura [NullableBool](../../com.aspose.slides/nullablebool).

**Restituisce:**
byte

### setBulletHardFont(byte value) {#setBulletHardFont-byte-}
```
public final void setBulletHardFont(byte value)
```

Determina se il punto elenco ha un font proprio o lo eredita dalla prima porzione del paragrafo. **NullableBool.True** if bullet has own font and **NullableBool.False** if bullet inherits font from the first portion in the paragraph. Lettura/scrittura [NullableBool](../../com.aspose.slides/nullablebool).

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | byte |  |

### getPicture() {#getPicture--}
```
public final ISlidesPicture getPicture()
```

Restituisce l'immagine usata come punto elenco in un paragrafo senza ereditarietà. Solo lettura [ISlidesPicture](../../com.aspose.slides/islidespicture).

**Restituisce:**
[ISlidesPicture](../../com.aspose.slides/islidespicture)

### applyDefaultParagraphIndentsShifts() {#applyDefaultParagraphIndentsShifts--}
```
public final void applyDefaultParagraphIndentsShifts()
```

Imposta gli spostamenti non zero predefiniti per l'Indent efficace del paragrafo e MarginLeft quando i punti elenco sono abilitati (come fa PowerPoint se si attivano i punti elenco/numerazione). Se i punti elenco sono disabilitati, reimposta semplicemente Indent e MarginLeft del paragrafo (come fa PowerPoint se si disabilitano i punti elenco/numerazione). Gli spostamenti di indentazione sono applicati rispetto al contesto corrente del bullet – IBulletFormat.Type, .NumberedBulletStyle e FontHeight della prima porzione. Gli spostamenti di indentazione non zero sono applicati a Indent e MarginLeft efficaci del paragrafo corrente (rendono i valori risultanti valori locali).

### getEffective() {#getEffective--}
```
public final IBulletFormatEffectiveData getEffective()
```

Ottiene i dati di formattazione del bullet efficaci con l'ereditarietà applicata.

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
[IBulletFormatEffectiveData](../../com.aspose.slides/ibulletformateffectivedata) - Un [IBulletFormatEffectiveData](../../com.aspose.slides/ibulletformateffectivedata).

### getVersion() {#getVersion--}
```
public long getVersion()
```

Versione. Solo lettura long.

**Restituisce:**
long