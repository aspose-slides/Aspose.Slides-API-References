---
title: IBulletFormatEffectiveData
second_title: Aspose.Slides for Java API Reference
description: Immutable object which contains effective paragraph bullet formatting properties.
type: docs
url: /it/com.aspose.slides/ibulletformateffectivedata/
---```
public interface IBulletFormatEffectiveData
```

Oggetto immutabile che contiene le proprietà di formattazione dei punti elenco del paragrafo effettive.

--------------------

Questa interfaccia è usata come parte di [IParagraphFormatEffectiveData](../../com.aspose.slides/iparagraphformateffectivedata).
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getType()](#getType--) | Restituisce il tipo di elenco puntato di un paragrafo. |
| [getChar()](#getChar--) | Restituisce il carattere di elenco puntato di un paragrafo. |
| [getActualBulletValue()](#getActualBulletValue--) | Restituisce il valore effettivo dell'elenco puntato per il paragrafo genitore. |
| [getFont()](#getFont--) | Restituisce il carattere dell'elenco puntato di un paragrafo. |
| [getHeight()](#getHeight--) | Restituisce l'altezza dell'elenco puntato di un paragrafo. |
| [getNumberedBulletStartWith()](#getNumberedBulletStartWith--) | Restituisce il primo numero utilizzato per il gruppo di elenchi puntati numerati. |
| [getNumberedBulletStyle()](#getNumberedBulletStyle--) | Restituisce lo stile di un elenco puntato numerato. |
| [isBulletHardColor()](#isBulletHardColor--) | Determina se l'elenco puntato ha un colore proprio o lo eredita dalla prima porzione del paragrafo. |
| [isBulletHardFont()](#isBulletHardFont--) | Determina se l'elenco puntato ha un carattere proprio o lo eredita dalla prima porzione del paragrafo. |
| [getPicture()](#getPicture--) | Restituisce l'immagine usata come elenco puntato nel paragrafo. |
| [getFillFormat()](#getFillFormat--) | Restituisce il formato di riempimento dell'elenco puntato di un paragrafo. |
### getType() {#getType--}
```
public abstract byte getType()
```

Restituisce il tipo di elenco puntato di un paragrafo. Solo lettura [BulletType](../../com.aspose.slides/bullettype).

**Restituisce:**
byte
### getChar() {#getChar--}
```
public abstract char getChar()
```

Restituisce il carattere di elenco puntato di un paragrafo. Solo lettura char.

**Restituisce:**
char
### getActualBulletValue() {#getActualBulletValue--}
```
public abstract String getActualBulletValue()
```

Restituisce il valore effettivo dell'elenco puntato per il paragrafo genitore. Solo lettura String.

**Restituisce:**
java.lang.String
### getFont() {#getFont--}
```
public abstract IFontData getFont()
```

Restituisce il carattere dell'elenco puntato di un paragrafo. Solo lettura [IFontData](../../com.aspose.slides/ifontdata).

**Restituisce:**
[IFontData](../../com.aspose.slides/ifontdata)
### getHeight() {#getHeight--}
```
public abstract float getHeight()
```

Restituisce l'altezza dell'elenco puntato di un paragrafo. Solo lettura float.

**Restituisce:**
float
### getNumberedBulletStartWith() {#getNumberedBulletStartWith--}
```
public abstract short getNumberedBulletStartWith()
```

Restituisce il primo numero utilizzato per il gruppo di elenchi puntati numerati. Solo lettura short.

**Restituisce:**
short
### getNumberedBulletStyle() {#getNumberedBulletStyle--}
```
public abstract byte getNumberedBulletStyle()
```

Restituisce lo stile di un elenco puntato numerato. Solo lettura [NumberedBulletStyle](../../com.aspose.slides/numberedbulletstyle).

**Restituisce:**
byte
### isBulletHardColor() {#isBulletHardColor--}
```
public abstract boolean isBulletHardColor()
```

Determina se l'elenco puntato ha un colore proprio o lo eredita dalla prima porzione del paragrafo. Restituisce **true** se l'elenco puntato ha un colore proprio e **false** se l'elenco puntato eredita il colore dalla prima porzione del paragrafo. Solo lettura boolean.

**Restituisce:**
boolean
### isBulletHardFont() {#isBulletHardFont--}
```
public abstract boolean isBulletHardFont()
```

Determina se l'elenco puntato ha un carattere proprio o lo eredita dalla prima porzione del paragrafo. Restituisce **true** se l'elenco puntato ha un carattere proprio e **true** se l'elenco puntato eredita il carattere dalla prima porzione del paragrafo. Solo lettura boolean.

**Restituisce:**
boolean
### getPicture() {#getPicture--}
```
public abstract IPictureEffectiveData getPicture()
```

Restituisce l'immagine usata come elenco puntato nel paragrafo. Solo lettura [IPictureEffectiveData](../../com.aspose.slides/ipictureeffectivedata).

**Restituisce:**
[IPictureEffectiveData](../../com.aspose.slides/ipictureeffectivedata)
### getFillFormat() {#getFillFormat--}
```
public abstract IFillFormatEffectiveData getFillFormat()
```

Restituisce il formato di riempimento dell'elenco puntato di un paragrafo. Solo lettura [IFillFormatEffectiveData](../../com.aspose.slides/ifillformateffectivedata).

--------------------

> ```
> This example demonstrates retrieving bullet's fill effective data.
>  
>  Presentation pres = new Presentation("SomePresentation.pptx");
>  try {
>      // Supponiamo che la prima forma nella prima diapositiva sia un'AutoShape con del testo...
>      // Mostra le informazioni sui punti elenco dei paragrafi di testo
>      AutoShape autoShape = (AutoShape)pres.getSlides().get_Item(0).getShapes().get_Item(0);
>      for (IParagraph para : autoShape.getTextFrame().getParagraphs())
>      {
>          IBulletFormatEffectiveData bulletFormatEffective = para.getParagraphFormat().getBullet().getEffective();
>          System.out.println("Bullet type: " + bulletFormatEffective.getType());
>          if (bulletFormatEffective.getType() != BulletType.None)
>          {
>              System.out.println("Bullet fill type: " + bulletFormatEffective.getFillFormat().getFillType());
>              switch (bulletFormatEffective.getFillFormat().getFillType())
>              {
>                  case FillType.Solid:
>                      System.out.println("Solid fill color: " + bulletFormatEffective.getFillFormat().getSolidFillColor());
>                      break;
>                  case FillType.Gradient:
>                      System.out.println("Gradient stops count: " + bulletFormatEffective.getFillFormat().getGradientFormat().getGradientStops().size());
>                      for (IGradientStopEffectiveData gradStop : bulletFormatEffective.getFillFormat().getGradientFormat().getGradientStops())
>                          System.out.println(gradStop.getPosition() + ": " + gradStop.getColor());
>                      break;
>                  case FillType.Pattern:
>                      System.out.println("Pattern style: " + bulletFormatEffective.getFillFormat().getPatternFormat().getPatternStyle());
>                      System.out.println("Fore color: " + bulletFormatEffective.getFillFormat().getPatternFormat().getForeColor());
>                      System.out.println("Back color: " + bulletFormatEffective.getFillFormat().getPatternFormat().getBackColor());
>                      break;
>              }
>          }
>          System.out.println();
>      }
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Restituisce:**
[IFillFormatEffectiveData](../../com.aspose.slides/ifillformateffectivedata)