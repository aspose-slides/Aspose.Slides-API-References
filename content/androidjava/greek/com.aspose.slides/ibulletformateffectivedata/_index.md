---
title: IBulletFormatEffectiveData
second_title: Aspose.Slides for Android via Java API Reference
description: Αμετάβλητο αντικείμενο που περιέχει τις αποτελεσματικές ιδιότητες μορφοποίησης σφαίρας παραγράφου.
type: docs
url: /el/com.aspose.slides/ibulletformateffectivedata/
---```
public interface IBulletFormatEffectiveData
```

Αμετάβλητο αντικείμενο που περιέχει τις αποτελεσματικές ιδιότητες μορφοποίησης σφαίρας παραγράφου.

--------------------

Αυτό το interface χρησιμοποιείται ως μέρος του [IParagraphFormatEffectiveData](../../com.aspose.slides/iparagraphformateffectivedata).
## Methods

| Method | Description |
| --- | --- |
| [getType()](#getType--) | Επιστρέφει τον τύπο σφαίρας μιας παραγράφου. |
| [getChar()](#getChar--) | Επιστρέφει το χαρακτήρα σφαίρας μιας παραγράφου. |
| [getActualBulletValue()](#getActualBulletValue--) | Επιστρέφει την πραγματική τιμή σφαίρας για την γονική παράγραφο. |
| [getFont()](#getFont--) | Επιστρέφει τη γραμματοσειρά σφαίρας μιας παραγράφου. |
| [getHeight()](#getHeight--) | Επιστρέφει το ύψος σφαίρας μιας παραγράφου. |
| [getNumberedBulletStartWith()](#getNumberedBulletStartWith--) | Επιστρέφει τον πρώτο αριθμό που χρησιμοποιείται για την ομάδα αριθμημένων σφαίρων. |
| [getNumberedBulletStyle()](#getNumberedBulletStyle--) | Επιστρέφει το στυλ μιας αριθμημένης σφαίρας. |
| [isBulletHardColor()](#isBulletHardColor--) | Καθορίζει εάν η σφαίρα έχει το δικό της χρώμα ή το κληρονομεί από το πρώτο τμήμα στην παράγραφο. |
| [isBulletHardFont()](#isBulletHardFont--) | Καθορίζει εάν η σφαίρα έχει τη δική της γραμματοσειρά ή την κληρονομεί από το πρώτο τμήμα στην παράγραφο. |
| [getPicture()](#getPicture--) | Επιστρέφει την εικόνα που χρησιμοποιείται ως σφαίρα στην παράγραφο. |
| [getFillFormat()](#getFillFormat--) | Επιστρέφει τη μορφή γεμίσματος σφαίρας μιας παραγράφου. |
### getType() {#getType--}
```
public abstract byte getType()
```


Επιστρέφει τον τύπο σφαίρας μιας παραγράφου. Μόνο για ανάγνωση [BulletType](../../com.aspose.slides/bullettype).

**Επιστρέφει:**
byte
### getChar() {#getChar--}
```
public abstract char getChar()
```


Επιστρέφει το χαρακτήρα σφαίρας μιας παραγράφου. Μόνο για ανάγνωση char.

**Επιστρέφει:**
char
### getActualBulletValue() {#getActualBulletValue--}
```
public abstract String getActualBulletValue()
```


Επιστρέφει την πραγματική τιμή σφαίρας για την γονική παράγραφο. Μόνο για ανάγνωση String.

**Επιστρέφει:**
java.lang.String
### getFont() {#getFont--}
```
public abstract IFontData getFont()
```


Επιστρέφει τη γραμματοσειρά σφαίρας μιας παραγράφου. Μόνο για ανάγνωση [IFontData](../../com.aspose.slides/ifontdata).

**Επιστρέφει:**
[IFontData](../../com.aspose.slides/ifontdata)
### getHeight() {#getHeight--}
```
public abstract float getHeight()
```


Επιστρέφει το ύψος σφαίρας μιας παραγράφου. Μόνο για ανάγνωση float.

**Επιστρέφει:**
float
### getNumberedBulletStartWith() {#getNumberedBulletStartWith--}
```
public abstract short getNumberedBulletStartWith()
```


Επιστρέφει τον πρώτο αριθμό που χρησιμοποιείται για την ομάδα αριθμημένων σφαίρων. Μόνο για ανάγνωση short.

**Επιστρέφει:**
short
### getNumberedBulletStyle() {#getNumberedBulletStyle--}
```
public abstract byte getNumberedBulletStyle()
```


Επιστρέφει το στυλ μιας αριθμημένης σφαίρας. Μόνο για ανάγνωση [NumberedBulletStyle](../../com.aspose.slides/numberedbulletstyle).

**Επιστρέφει:**
byte
### isBulletHardColor() {#isBulletHardColor--}
```
public abstract boolean isBulletHardColor()
```


Καθορίζει εάν η σφαίρα έχει το δικό της χρώμα ή το κληρονομεί από το πρώτο τμήμα στην παράγραφο. Επιστρέφει **true** εάν η σφαίρα έχει το δικό της χρώμα και **false** εάν η σφαίρα κληρονομεί το χρώμα από το πρώτο τμήμα στην παράγραφο. Μόνο για ανάγνωση boolean.

**Επιστρέφει:**
boolean
### isBulletHardFont() {#isBulletHardFont--}
```
public abstract boolean isBulletHardFont()
```


Καθορίζει εάν η σφαίρα έχει τη δική της γραμματοσειρά ή την κληρονομεί από το πρώτο τμήμα στην παράγραφο. Επιστρέφει **true** εάν η σφαίρα έχει τη δική της γραμματοσειρά και **true** εάν η σφαίρα κληρονομεί τη γραμματοσειρά από το πρώτο τμήμα στην παράγραφο. Μόνο για ανάγνωση boolean.

**Επιστρέφει:**
boolean
### getPicture() {#getPicture--}
```
public abstract IPictureEffectiveData getPicture()
```


Επιστρέφει την εικόνα που χρησιμοποιείται ως σφαίρα στην παράγραφο. Μόνο για ανάγνωση [IPictureEffectiveData](../../com.aspose.slides/ipictureeffectivedata).

**Επιστρέφει:**
[IPictureEffectiveData](../../com.aspose.slides/ipictureeffectivedata)
### getFillFormat() {#getFillFormat--}
```
public abstract IFillFormatEffectiveData getFillFormat()
```


Επιστρέφει τη μορφή γεμίσματος σφαίρας μιας παραγράφου. Μόνο για ανάγνωση [IFillFormatEffectiveData](../../com.aspose.slides/ifillformateffectivedata).

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

**Επιστρέφει:**
[IFillFormatEffectiveData](../../com.aspose.slides/ifillformateffectivedata)