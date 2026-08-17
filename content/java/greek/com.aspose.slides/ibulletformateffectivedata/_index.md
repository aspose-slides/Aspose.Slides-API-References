---
title: IBulletFormatEffectiveData
second_title: Aspose.Slides για το Java API Reference
description: Αμετάβλητο αντικείμενο που περιέχει τις αποτελεσματικές ιδιότητες μορφοποίησης κουκκίδας παραγράφου.
type: docs
url: /el/com.aspose.slides/ibulletformateffectivedata/
---```
public interface IBulletFormatEffectiveData
```

Αμετάβλητο αντικείμενο που περιέχει τις αποτελεσματικές ιδιότητες μορφοποίησης κουκκίδας παραγράφου.

--------------------

This interface is used as a part of [IParagraphFormatEffectiveData](../../com.aspose.slides/iparagraphformateffectivedata).
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [getType()](#getType--) | Επιστρέφει τον τύπο της κουκκίδας μιας παραγράφου. |
| [getChar()](#getChar--) | Επιστρέφει το χαρακτήρα της κουκκίδας μιας παραγράφου. |
| [getActualBulletValue()](#getActualBulletValue--) | Επιστρέφει την πραγματική τιμή της κουκκίδας για την γονική παράγραφο. |
| [getFont()](#getFont--) | Επιστρέφει τη γραμματοσειρά της κουκκίδας μιας παραγράφου. |
| [getHeight()](#getHeight--) | Επιστρέφει το ύψος της κουκκίδας μιας παραγράφου. |
| [getNumberedBulletStartWith()](#getNumberedBulletStartWith--) | Επιστρέφει τον πρώτο αριθμό που χρησιμοποιείται για την ομάδα αριθμημένων κουκκίδων. |
| [getNumberedBulletStyle()](#getNumberedBulletStyle--) | Επιστρέφει το στυλ μιας αριθμημένης κουκκίδας. |
| [isBulletHardColor()](#isBulletHardColor--) | Καθορίζει αν η κουκκίδα έχει δικό της χρώμα ή το κληρονομεί από το πρώτο τμήμα στην παράγραφο. |
| [isBulletHardFont()](#isBulletHardFont--) | Καθορίζει αν η κουκκίδα έχει δική της γραμματοσειρά ή την κληρονομεί από το πρώτο τμήμα στην παράγραφο. |
| [getPicture()](#getPicture--) | Επιστρέφει την εικόνα που χρησιμοποιείται ως κουκκίδα στην παράγραφο. |
| [getFillFormat()](#getFillFormat--) | Επιστρέφει τη μορφή γεμίσματος της κουκκίδας μιας παραγράφου. |
### getType() {#getType--}
```
public abstract byte getType()
```


Επιστρέφει τον τύπο της κουκκίδας μιας παραγράφου. Μόνο για ανάγνωση [BulletType](../../com.aspose.slides/bullettype).

**Επιστρέφει:**
byte
### getChar() {#getChar--}
```
public abstract char getChar()
```


Επιστρέφει το χαρακτήρα της κουκκίδας μιας παραγράφου. Μόνο για ανάγνωση char.

**Επιστρέφει:**
char
### getActualBulletValue() {#getActualBulletValue--}
```
public abstract String getActualBulletValue()
```


Επιστρέφει την πραγματική τιμή της κουκκίδας για την γονική παράγραφο. Μόνο για ανάγνωση String.

**Επιστρέφει:**
java.lang.String
### getFont() {#getFont--}
```
public abstract IFontData getFont()
```


Επιστρέφει τη γραμματοσειρά της κουκκίδας μιας παραγράφου. Μόνο για ανάγνωση [IFontData](../../com.aspose.slides/ifontdata).

**Επιστρέφει:**
[IFontData](../../com.aspose.slides/ifontdata)
### getHeight() {#getHeight--}
```
public abstract float getHeight()
```


Επιστρέφει το ύψος της κουκκίδας μιας παραγράφου. Μόνο για ανάγνωση float.

**Επιστρέφει:**
float
### getNumberedBulletStartWith() {#getNumberedBulletStartWith--}
```
public abstract short getNumberedBulletStartWith()
```


Επιστρέφει τον πρώτο αριθμό που χρησιμοποιείται για την ομάδα αριθμημένων κουκκίδων. Μόνο για ανάγνωση short.

**Επιστρέφει:**
short
### getNumberedBulletStyle() {#getNumberedBulletStyle--}
```
public abstract byte getNumberedBulletStyle()
```


Επιστρέφει το στυλ μιας αριθμημένης κουκκίδας. Μόνο για ανάγνωση [NumberedBulletStyle](../../com.aspose.slides/numberedbulletstyle).

**Επιστρέφει:**
byte
### isBulletHardColor() {#isBulletHardColor--}
```
public abstract boolean isBulletHardColor()
```


Καθορίζει αν η κουκκίδα έχει δικό της χρώμα ή το κληρονομεί από το πρώτο τμήμα στην παράγραφο. Επιστρέφει **true** αν η κουκκίδα έχει δικό της χρώμα και **false** αν η κουκκίδα κληρονομεί το χρώμα από το πρώτο τμήμα στην παράγραφο. Μόνο για ανάγνωση boolean.

**Επιστρέφει:**
boolean
### isBulletHardFont() {#isBulletHardFont--}
```
public abstract boolean isBulletHardFont()
```


Καθορίζει αν η κουκκίδα έχει δική της γραμματοσειρά ή την κληρονομεί από το πρώτο τμήμα στην παράγραφο. Επιστρέφει **true** αν η κουκκίδα έχει δική της γραμματοσειρά και **true** αν η κουκκίδα κληρονομεί τη γραμματοσειρά από το πρώτο τμήμα στην παράγραφο. Μόνο για ανάγνωση boolean.

**Επιστρέφει:**
boolean
### getPicture() {#getPicture--}
```
public abstract IPictureEffectiveData getPicture()
```


Επιστρέφει την εικόνα που χρησιμοποιείται ως κουκκίδα στην παράγραφο. Μόνο για ανάγνωση [IPictureEffectiveData](../../com.aspose.slides/ipictureeffectivedata).

**Επιστρέφει:**
[IPictureEffectiveData](../../com.aspose.slides/ipictureeffectivedata)
### getFillFormat() {#getFillFormat--}
```
public abstract IFillFormatEffectiveData getFillFormat()
```


Επιστρέφει τη μορφή γεμίσματος της κουκκίδας μιας παραγράφου. Μόνο για ανάγνωση [IFillFormatEffectiveData](../../com.aspose.slides/ifillformateffectivedata).

--------------------

> ```
> This example demonstrates retrieving bullet's fill effective data.
>  
>  Presentation pres = new Presentation("SomePresentation.pptx");
>  try {
>      // Υπόθεση ότι το πρώτο σχήμα στην πρώτη διαφάνεια είναι AutoShape με κάποιο κείμενο...
>      // Εμφανίζει πληροφορίες σχετικά με τις κουκκίδες των παραγράφων κειμένου
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


**Επιστρέφει:**
[IFillFormatEffectiveData](../../com.aspose.slides/ifillformateffectivedata)