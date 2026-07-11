---
title: FillFormat
second_title: Aspose.Slides για Android μέσω Αναφοράς Java API
description: Αντιπροσωπεύει επιλογές μορφοποίησης γεμίσματος.
type: docs
url: /el/com.aspose.slides/fillformat/
---
**Κληρονομικότητα:**
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject)

**Όλες οι υλοποιημένες διεπαφές:**
[com.aspose.slides.IFillFormat](../../com.aspose.slides/ifillformat)
```
public final class FillFormat extends PVIObject implements IFillFormat
```

Αντιπροσωπεύει επιλογές μορφοποίησης γεμίσματος.
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [getVersion()](#getVersion--) |  |
| [getFillType()](#getFillType--) | Επιστρέφει ή ορίζει τον τύπο γεμίσματος. |
| [setFillType(byte value)](#setFillType-byte-) | Επιστρέφει ή ορίζει τον τύπο γεμίσματος. |
| [getSolidFillColor()](#getSolidFillColor--) | Επιστρέφει το χρώμα γεμίσματος. |
| [getGradientFormat()](#getGradientFormat--) | Επιστρέφει τη μορφή γεμίσματος διαβάθμισης. |
| [getPatternFormat()](#getPatternFormat--) | Επιστρέφει τη μορφή γεμίσματος μοτίβου. |
| [getPictureFillFormat()](#getPictureFillFormat--) | Επιστρέφει τη μορφή γεμίσματος εικόνας. |
| [getRotateWithShape()](#getRotateWithShape--) | Καθορίζει εάν το γέμισμα πρέπει να περιστρέφεται με το σχήμα. |
| [setRotateWithShape(byte value)](#setRotateWithShape-byte-) | Καθορίζει εάν το γέμισμα πρέπει να περιστρέφεται με το σχήμα. |
| [getEffective()](#getEffective--) | Λαμβάνει τα αποτελεσματικά δεδομένα μορφοποίησης γεμίσματος με την κληρονομική εφαρμογή. |
### getVersion() {#getVersion--}
```
public long getVersion()
```


Έκδοση. Μόνο για ανάγνωση long.

**Επιστρέφει:**
long
### getFillType() {#getFillType--}
```
public final byte getFillType()
```


Επιστρέφει ή ορίζει τον τύπο γεμίσματος. Ανάγνωση/Εγγραφή [FillType](../../com.aspose.slides/filltype).

**Επιστρέφει:**
byte
### setFillType(byte value) {#setFillType-byte-}
```
public final void setFillType(byte value)
```


Επιστρέφει ή ορίζει τον τύπο γεμίσματος. Ανάγνωση/Εγγραφή [FillType](../../com.aspose.slides/filltype).

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | byte |  |

### getSolidFillColor() {#getSolidFillColor--}
```
public final IColorFormat getSolidFillColor()
```


Επιστρέφει το χρώμα γεμίσματος. Μόνο για ανάγνωση [IColorFormat](../../com.aspose.slides/icolorformat).

**Επιστρέφει:**
[IColorFormat](../../com.aspose.slides/icolorformat)
### getGradientFormat() {#getGradientFormat--}
```
public final IGradientFormat getGradientFormat()
```


Επιστρέφει τη μορφή γεμίσματος διαβάθμισης. Μόνο για ανάγνωση [IGradientFormat](../../com.aspose.slides/igradientformat).

**Επιστρέφει:**
[IGradientFormat](../../com.aspose.slides/igradientformat)
### getPatternFormat() {#getPatternFormat--}
```
public final IPatternFormat getPatternFormat()
```


Επιστρέφει τη μορφή γεμίσματος μοτίβου. Μόνο για ανάγνωση [IPatternFormat](../../com.aspose.slides/ipatternformat).

**Επιστρέφει:**
[IPatternFormat](../../com.aspose.slides/ipatternformat)
### getPictureFillFormat() {#getPictureFillFormat--}
```
public final IPictureFillFormat getPictureFillFormat()
```


Επιστρέφει τη μορφή γεμίσματος εικόνας. Μόνο για ανάγνωση [IPictureFillFormat](../../com.aspose.slides/ipicturefillformat).

**Επιστρέφει:**
[IPictureFillFormat](../../com.aspose.slides/ipicturefillformat)
### getRotateWithShape() {#getRotateWithShape--}
```
public final byte getRotateWithShape()
```


Καθορίζει εάν το γέμισμα πρέπει να περιστρέφεται με το σχήμα. Ανάγνωση/Εγγραφή [NullableBool](../../com.aspose.slides/nullablebool).

**Επιστρέφει:**
byte
### setRotateWithShape(byte value) {#setRotateWithShape-byte-}
```
public final void setRotateWithShape(byte value)
```


Καθορίζει εάν το γέμισμα πρέπει να περιστρέφεται με το σχήμα. Ανάγνωση/Εγγραφή [NullableBool](../../com.aspose.slides/nullablebool).

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | byte |  |

### getEffective() {#getEffective--}
```
public final IFillFormatEffectiveData getEffective()
```


Λαμβάνει τα αποτελεσματικά δεδομένα μορφοποίησης γεμίσματος με την κληρονομική εφαρμογή.

--------------------

> ```
> This example demonstrates getting shape's effective fill format properties.
>  
>  Presentation pres = new Presentation("MyPresentation.pptx");
>  try
>  {
>  	IFillFormatEffectiveData effectiveFillFormat = pres.getSlides().get_Item(0).getShapes().get_Item(0).getFillFormat().getEffective();
>  	System.out.println("Type: " + effectiveFillFormat.getFillType());
>  	switch (effectiveFillFormat.getFillType())
>  	{
>  		case FillType.Solid:
>  			System.out.println("Fill color: " + effectiveFillFormat.getSolidFillColor());
>  			break;
>  		case FillType.Pattern:
>  			System.out.println("Pattern style: " + effectiveFillFormat.getPatternFormat().getPatternStyle());
>  			System.out.println("Fore color: " + effectiveFillFormat.getPatternFormat().getForeColor());
>  			System.out.println("Back color: " + effectiveFillFormat.getPatternFormat().getBackColor());
>  			break;
>  		case FillType.Gradient:
>  			System.out.println("Gradient direction: " + effectiveFillFormat.getGradientFormat().getGradientDirection());
>  			System.out.println("Gradient stops count: " + effectiveFillFormat.getGradientFormat().getGradientStops().size());
>  			break;
>  		case FillType.Picture:
>  			System.out.println("Picture width: " + effectiveFillFormat.getPictureFillFormat().getPicture().getImage().getWidth());
>  			System.out.println("Picture height: " + effectiveFillFormat.getPictureFillFormat().getPicture().getImage().getHeight());
>  			break;
>  	}
>  } finally {
>   if (pres != null) pres.dispose();
>  }
> ```


**Επιστρέφει:**
[IFillFormatEffectiveData](../../com.aspose.slides/ifillformateffectivedata) - A [IFillFormatEffectiveData](../../com.aspose.slides/ifillformateffectivedata).