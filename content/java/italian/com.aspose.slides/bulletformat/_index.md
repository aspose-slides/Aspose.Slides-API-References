---
title: BulletFormat
second_title: Riferimento API Aspose.Slides per Java
description: Rappresenta le proprietà di formattazione dei puntatori di paragrafo.
type: docs
url: /it/com.aspose.slides/bulletformat/
---
**Eredità:**
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject)

**Tutte le interfacce implementate:**
[com.aspose.slides.IBulletFormat](../../com.aspose.slides/ibulletformat)
```
public final class BulletFormat extends PVIObject implements IBulletFormat
```

Rappresenta le proprietà di formattazione dei puntatori di paragrafo.
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getType()](#getType--) | Restituisce o imposta il tipo di puntatore di un paragrafo senza ereditarietà. |
| [setType(byte value)](#setType-byte-) | Restituisce o imposta il tipo di puntatore di un paragrafo senza ereditarietà. |
| [getChar()](#getChar--) | Restituisce o imposta il carattere di puntatore di un paragrafo senza ereditarietà. |
| [setChar(char value)](#setChar-char-) | Restituisce o imposta il carattere di puntatore di un paragrafo senza ereditarietà. |
| [getFont()](#getFont--) | Restituisce o imposta il font di puntatore di un paragrafo senza ereditarietà. |
| [setFont(IFontData value)](#setFont-com.aspose.slides.IFontData-) | Restituisce o imposta il font di puntatore di un paragrafo senza ereditarietà. |
| [getHeight()](#getHeight--) | Restituisce o imposta l'altezza del puntatore di un paragrafo senza ereditarietà. |
| [setHeight(float value)](#setHeight-float-) | Restituisce o imposta l'altezza del puntatore di un paragrafo senza ereditarietà. |
| [getColor()](#getColor--) | Restituisce il formato colore di un puntatore di un paragrafo senza ereditarietà. |
| [getNumberedBulletStartWith()](#getNumberedBulletStartWith--) | Restituisce o imposta il primo numero usato per il gruppo di puntatori numerati senza ereditarietà. |
| [setNumberedBulletStartWith(short value)](#setNumberedBulletStartWith-short-) | Restituisce o imposta il primo numero usato per il gruppo di puntatori numerati senza ereditarietà. |
| [getNumberedBulletStyle()](#getNumberedBulletStyle--) | Restituisce o imposta lo stile di un puntatore numerato senza ereditarietà. |
| [setNumberedBulletStyle(byte value)](#setNumberedBulletStyle-byte-) | Restituisce o imposta lo stile di un puntatore numerato senza ereditarietà. |
| [isBulletHardColor()](#isBulletHardColor--) | Determina se il puntatore ha un colore proprio o lo eredita dalla prima porzione nel paragrafo. |
| [setBulletHardColor(byte value)](#setBulletHardColor-byte-) | Determina se il puntatore ha un colore proprio o lo eredita dalla prima porzione nel paragrafo. |
| [isBulletHardFont()](#isBulletHardFont--) | Determina se il puntatore ha un font proprio o lo eredita dalla prima porzione nel paragrafo. |
| [setBulletHardFont(byte value)](#setBulletHardFont-byte-) | Determina se il puntatore ha un font proprio o lo eredita dalla prima porzione nel paragrafo. |
| [getPicture()](#getPicture--) | Restituisce l'immagine utilizzata come puntatore in un paragrafo senza ereditarietà. |
| [applyDefaultParagraphIndentsShifts()](#applyDefaultParagraphIndentsShifts--) | Imposta gli spostamenti predefiniti non nulli per l'Indent effettivo del paragrafo e MarginLeft quando i puntatori sono abilitati (come fa PowerPoint se si attivano i puntatori/numerazione nel paragrafo). |
| [getEffective()](#getEffective--) | Ottiene i dati di formattazione del puntatore effettivi con l'ereditarietà applicata. |
| [getVersion()](#getVersion--) |  |
### getType() {#getType--}
```
public final byte getType()
```


Restituisce o imposta il tipo di puntatore di un paragrafo senza ereditarietà. Lettura/Scrittura [BulletType](../../com.aspose.slides/bullettype).

**Restituisce:**
byte
### setType(byte value) {#setType-byte-}
```
public final void setType(byte value)
```


Restituisce o imposta il tipo di puntatore di un paragrafo senza ereditarietà. Lettura/Scrittura [BulletType](../../com.aspose.slides/bullettype).

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | byte |  |

### getChar() {#getChar--}
```
public final char getChar()
```


Restituisce o imposta il carattere di puntatore di un paragrafo senza ereditarietà. Lettura/Scrittura char .

**Restituisce:**
char
### setChar(char value) {#setChar-char-}
```
public final void setChar(char value)
```


Restituisce o imposta il carattere di puntatore di un paragrafo senza ereditarietà. Lettura/Scrittura char .

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | char |  |

### getFont() {#getFont--}
```
public final IFontData getFont()
```


Restituisce o imposta il font di puntatore di un paragrafo senza ereditarietà. Lettura/Scrittura [IFontData](../../com.aspose.slides/ifontdata).

**Restituisce:**
[IFontData](../../com.aspose.slides/ifontdata)
### setFont(IFontData value) {#setFont-com.aspose.slides.IFontData-}
```
public final void setFont(IFontData value)
```


Restituisce o imposta il font di puntatore di un paragrafo senza ereditarietà. Lettura/Scrittura [IFontData](../../com.aspose.slides/ifontdata).

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [IFontData](../../com.aspose.slides/ifontdata) |  |

### getHeight() {#getHeight--}
```
public final float getHeight()
```


Restituisce o imposta l'altezza del puntatore di un paragrafo senza ereditarietà. Il valore Float.NaN determina che il puntatore eredita l'altezza dalla prima porzione nel paragrafo. Lettura/Scrittura float .

--------------------

Un valore di altezza negativo indica che l'altezza è espressa in punti e un valore positivo indica che l'altezza è una percentuale del testo circostante.

**Restituisce:**
float
### setHeight(float value) {#setHeight-float-}
```
public final void setHeight(float value)
```


Restituisce o imposta l'altezza del puntatore di un paragrafo senza ereditarietà. Il valore Float.NaN determina che il puntatore eredita l'altezza dalla prima porzione nel paragrafo. Lettura/Scrittura float .

--------------------

Un valore di altezza negativo indica che l'altezza è espressa in punti e un valore positivo indica che l'altezza è una percentuale del testo circostante.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | float |  |

### getColor() {#getColor--}
```
public final IColorFormat getColor()
```


Restituisce il formato colore di un puntatore di un paragrafo senza ereditarietà. Solo lettura [IColorFormat](../../com.aspose.slides/icolorformat).

**Restituisce:**
[IColorFormat](../../com.aspose.slides/icolorformat)
### getNumberedBulletStartWith() {#getNumberedBulletStartWith--}
```
public final short getNumberedBulletStartWith()
```


Restituisce o imposta il primo numero usato per il gruppo di puntatori numerati senza ereditarietà. Lettura/Scrittura short .

**Restituisce:**
short
### setNumberedBulletStartWith(short value) {#setNumberedBulletStartWith-short-}
```
public final void setNumberedBulletStartWith(short value)
```


Restituisce o imposta il primo numero usato per il gruppo di puntatori numerati senza ereditarietà. Lettura/Scrittura short .

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | short |  |

### getNumberedBulletStyle() {#getNumberedBulletStyle--}
```
public final byte getNumberedBulletStyle()
```


Restituisce o imposta lo stile di un puntatore numerato senza ereditarietà. Lettura/Scrittura [NumberedBulletStyle](../../com.aspose.slides/numberedbulletstyle).

**Restituisce:**
byte
### setNumberedBulletStyle(byte value) {#setNumberedBulletStyle-byte-}
```
public final void setNumberedBulletStyle(byte value)
```


Restituisce o imposta lo stile di un puntatore numerato senza ereditarietà. Lettura/Scrittura [NumberedBulletStyle](../../com.aspose.slides/numberedbulletstyle).

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | byte |  |

### isBulletHardColor() {#isBulletHardColor--}
```
public final byte isBulletHardColor()
```


Determina se il puntatore ha un colore proprio o lo eredita dalla prima porzione nel paragrafo. **NullableBool.True** se il puntatore ha un colore proprio e **NullableBool.False** se il puntatore eredita il colore dalla prima porzione nel paragrafo. Lettura/Scrittura [NullableBool](../../com.aspose.slides/nullablebool).

**Restituisce:**
byte
### setBulletHardColor(byte value) {#setBulletHardColor-byte-}
```
public final void setBulletHardColor(byte value)
```


Determina se il puntatore ha un colore proprio o lo eredita dalla prima porzione nel paragrafo. **NullableBool.True** se il puntatore ha un colore proprio e **NullableBool.False** se il puntatore eredita il colore dalla prima porzione nel paragrafo. Lettura/Scrittura [NullableBool](../../com.aspose.slides/nullablebool).

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | byte |  |

### isBulletHardFont() {#isBulletHardFont--}
```
public final byte isBulletHardFont()
```


Determina se il puntatore ha un font proprio o lo eredita dalla prima porzione nel paragrafo. **NullableBool.True** se il puntatore ha un font proprio e **NullableBool.False** se il puntatore eredita il font dalla prima porzione nel paragrafo. Lettura/Scrittura [NullableBool](../../com.aspose.slides/nullablebool).

**Restituisce:**
byte
### setBulletHardFont(byte value) {#setBulletHardFont-byte-}
```
public final void setBulletHardFont(byte value)
```


Determina se il puntatore ha un font proprio o lo eredita dalla prima porzione nel paragrafo. **NullableBool.True** se il puntatore ha un font proprio e **NullableBool.False** se il puntatore eredita il font dalla prima porzione nel paragrafo. Lettura/Scrittura [NullableBool](../../com.aspose.slides/nullablebool).

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | byte |  |

### getPicture() {#getPicture--}
```
public final ISlidesPicture getPicture()
```


Restituisce l'immagine utilizzata come puntatore in un paragrafo senza ereditarietà. Solo lettura [ISlidesPicture](../../com.aspose.slides/islidespicture).

**Restituisce:**
[ISlidesPicture](../../com.aspose.slides/islidespicture)
### applyDefaultParagraphIndentsShifts() {#applyDefaultParagraphIndentsShifts--}
```
public final void applyDefaultParagraphIndentsShifts()
```


Imposta gli spostamenti predefiniti non nulli per l'Indent effettivo del paragrafo e MarginLeft quando i puntatori sono abilitati (come fa PowerPoint se si attivano i puntatori/numerazione nel paragrafo). Se i puntatori sono disabilitati, ripristina semplicemente l'Indent e il MarginLeft del paragrafo (come fa PowerPoint se si disabilitano i puntatori/numerazione). Gli spostamenti di indentazione vengono applicati in base al contesto corrente del puntatore — IBulletFormat.Type, .NumberedBulletStyle e FontHeight della prima porzione. Gli spostamenti di indentazione non nulli vengono applicati all'Indent e al MarginLeft effettivi del paragrafo corrente (rendendo i valori risultanti valori locali).

### getEffective() {#getEffective--}
```
public final IBulletFormatEffectiveData getEffective()
```


Ottiene i dati di formattazione del puntatore effettivi con l'ereditarietà applicata.

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
[IBulletFormatEffectiveData](../../com.aspose.slides/ibulletformateffectivedata) - A [IBulletFormatEffectiveData](../../com.aspose.slides/ibulletformateffectivedata).
### getVersion() {#getVersion--}
```
public long getVersion()
```


Versione. Solo lettura long.

**Restituisce:**
long