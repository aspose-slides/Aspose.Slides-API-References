---
title: IBulletFormatEffectiveData
second_title: Aspose.Slides per Android tramite API di riferimento Java
description: Oggetto immutabile che contiene le proprietà effettive di formattazione dei puntatori di paragrafo.
type: docs
url: /it/com.aspose.slides/ibulletformateffectivedata/
---```
public interface IBulletFormatEffectiveData
```

Oggetto immutabile che contiene le proprietà effettive di formattazione dei puntatori di paragrafo.

--------------------

Questa interfaccia è usata come parte di [IParagraphFormatEffectiveData](../../com.aspose.slides/iparagraphformateffectivedata).
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getType()](#getType--) | Restituisce il tipo di puntatore di un paragrafo. |
| [getChar()](#getChar--) | Restituisce il carattere del puntatore di un paragrafo. |
| [getActualBulletValue()](#getActualBulletValue--) | Restituisce il valore reale del puntatore per il paragrafo genitore. |
| [getFont()](#getFont--) | Restituisce il font del puntatore di un paragrafo. |
| [getHeight()](#getHeight--) | Restituisce l'altezza del puntatore di un paragrafo. |
| [getNumberedBulletStartWith()](#getNumberedBulletStartWith--) | Restituisce il primo numero usato per il gruppo di puntatori numerati. |
| [getNumberedBulletStyle()](#getNumberedBulletStyle--) | Restituisce lo stile di un puntatore numerato. |
| [isBulletHardColor()](#isBulletHardColor--) | Determina se il puntatore ha un colore proprio o lo eredita dalla prima porzione del paragrafo. |
| [isBulletHardFont()](#isBulletHardFont--) | Determina se il puntatore ha un font proprio o lo eredita dalla prima porzione del paragrafo. |
| [getPicture()](#getPicture--) | Restituisce l'immagine usata come puntatore nel paragrafo. |
| [getFillFormat()](#getFillFormat--) | Restituisce il formato di riempimento del puntatore di un paragrafo. |
### getType() {#getType--}
```
public abstract byte getType()
```


Restituisce il tipo di puntatore di un paragrafo. Solo lettura [BulletType](../../com.aspose.slides/bullettype).

**Restituisce:**
byte
### getChar() {#getChar--}
```
public abstract char getChar()
```


Restituisce il carattere del puntatore di un paragrafo. Solo lettura char.

**Restituisce:**
char
### getActualBulletValue() {#getActualBulletValue--}
```
public abstract String getActualBulletValue()
```


Restituisce il valore reale del puntatore per il paragrafo genitore. Solo lettura String.

**Restituisce:**
java.lang.String
### getFont() {#getFont--}
```
public abstract IFontData getFont()
```


Restituisce il font del puntatore di un paragrafo. Solo lettura [IFontData](../../com.aspose.slides/ifontdata).

**Restituisce:**
[IFontData](../../com.aspose.slides/ifontdata)
### getHeight() {#getHeight--}
```
public abstract float getHeight()
```


Restituisce l'altezza del puntatore di un paragrafo. Solo lettura float.

**Restituisce:**
float
### getNumberedBulletStartWith() {#getNumberedBulletStartWith--}
```
public abstract short getNumberedBulletStartWith()
```


Restituisce il primo numero usato per il gruppo di puntatori numerati. Solo lettura short.

**Restituisce:**
short
### getNumberedBulletStyle() {#getNumberedBulletStyle--}
```
public abstract byte getNumberedBulletStyle()
```


Restituisce lo stile di un puntatore numerato. Solo lettura [NumberedBulletStyle](../../com.aspose.slides/numberedbulletstyle).

**Restituisce:**
byte
### isBulletHardColor() {#isBulletHardColor--}
```
public abstract boolean isBulletHardColor()
```


Determina se il puntatore ha un colore proprio o lo eredita dalla prima porzione del paragrafo. Restituisce **true** se il puntatore ha un colore proprio e **false** se il puntatore eredita il colore dalla prima porzione del paragrafo. Solo lettura boolean.

**Restituisce:**
boolean
### isBulletHardFont() {#isBulletHardFont--}
```
public abstract boolean isBulletHardFont()
```


Determina se il puntatore ha un font proprio o lo eredita dalla prima porzione del paragrafo. Restituisce **true** se il puntatore ha un font proprio e **true** se il puntatore eredita il font dalla prima porzione del paragrafo. Solo lettura boolean.

**Restituisce:**
boolean
### getPicture() {#getPicture--}
```
public abstract IPictureEffectiveData getPicture()
```


Restituisce l'immagine usata come puntatore nel paragrafo. Solo lettura [IPictureEffectiveData](../../com.aspose.slides/ipictureeffectivedata).

**Restituisce:**
[IPictureEffectiveData](../../com.aspose.slides/ipictureeffectivedata)
### getFillFormat() {#getFillFormat--}
```
public abstract IFillFormatEffectiveData getFillFormat()
```


Restituisce il formato di riempimento del puntatore di un paragrafo. Solo lettura [IFillFormatEffectiveData](../../com.aspose.slides/ifillformateffectivedata).

--------------------

> ```
> This example demonstrates retrieving bullet's fill effective data.
>  
>  Presentation pres = new Presentation("SomePresentation.pptx");
>  try {
>      // Assume that the first shape on the first slide is AutoShape with some text...
>      // Output information about text paragraphs' bullets
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