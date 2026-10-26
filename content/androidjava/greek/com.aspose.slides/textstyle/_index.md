---
title: TextStyle
second_title: Aspose.Slides για Android μέσω Αναφοράς API Java
description: Αυτή η κλάση περιέχει τις ιδιότητες μορφοποίησης του στυλ κειμένου.
type: docs
url: /el/com.aspose.slides/textstyle/
---
**Κληρονομικότητα:**
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject)

**Όλες οι Υλοποιημένες Διεπαφές:**
[com.aspose.slides.ITextStyle](../../com.aspose.slides/itextstyle), com.aspose.slides.IStyleColorOwner
```
public final class TextStyle extends PVIObject implements ITextStyle, IStyleColorOwner
```

Αυτή η κλάση περιέχει τις ιδιότητες μορφοποίησης του στυλ κειμένου.
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [getVersion()](#getVersion--) |  |
| [getLevel(int index)](#getLevel-int-) | Εάν υπάρχει το επίπεδο του στυλ, το επιστρέφει· διαφορετικά επιστρέφει null. |
| [getDefaultParagraphFormat()](#getDefaultParagraphFormat--) | Προεπιλεγμένες ιδιότητες παραγράφου. |
| [getEffective()](#getEffective--) | Λαμβάνει τα αποτελεσματικά δεδομένα μορφοποίησης του στυλ κειμένου με την εφαρμογή της κληρονομικότητας. |
### getVersion() {#getVersion--}
```
public long getVersion()
```

Έκδοση. Μόνο ανάγνωση long.

**Επιστρέφει:**
long
### getLevel(int index) {#getLevel-int-}
```
public final IParagraphFormat getLevel(int index)
```

Εάν υπάρχει το επίπεδο του στυλ, το επιστρέφει· διαφορετικά επιστρέφει null.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| index | int | Δείκτης αρχής 0 του επιπέδου. Πρέπει να βρίσκεται στο διάστημα 0..8. |

**Επιστρέφει:**
[IParagraphFormat](../../com.aspose.slides/iparagraphformat) - Διαμόρφωση του επιπέδου [IParagraphFormat](../../com.aspose.slides/iparagraphformat).
### getDefaultParagraphFormat() {#getDefaultParagraphFormat--}
```
public final IParagraphFormat getDefaultParagraphFormat()
```

Προεπιλεγμένες ιδιότητες παραγράφου. Μόνο ανάγνωση [IParagraphFormat](../../com.aspose.slides/iparagraphformat).

**Επιστρέφει:**
[IParagraphFormat](../../com.aspose.slides/iparagraphformat)
### getEffective() {#getEffective--}
```
public final ITextStyleEffectiveData getEffective()
```

Λαμβάνει τα αποτελεσματικά δεδομένα μορφοποίησης του στυλ κειμένου με την εφαρμογή της κληρονομικότητας.

--------------------

> ```
> This example demonstrates getting some of effective text style properties.
>  
>  Presentation pres = new Presentation("MyPresentation.pptx");
>  try
>  {
>      IAutoShape shape = (IAutoShape)pres.getSlides().get_Item(0).getShapes().get_Item(0);
>      ITextStyleEffectiveData effectiveTextStyle = shape.getTextFrame().getTextFrameFormat().getTextStyle().getEffective();
>      for (int i = 0; i <= 8; i++)
>      {
>          IParagraphFormatEffectiveData effectiveStyleLevel = effectiveTextStyle.getLevel(i);
>          System.out.println("= Effective paragraph formatting for style level #" + i + " =");
>          System.out.println("Depth: " + effectiveStyleLevel.getDepth());
>          System.out.println("Indent: " + effectiveStyleLevel.getIndent());
>          System.out.println("Alignment: " + effectiveStyleLevel.getAlignment());
>          System.out.println("Font alignment: " + effectiveStyleLevel.getFontAlignment());
>      }
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Επιστρέφει:**
[ITextStyleEffectiveData](../../com.aspose.slides/itextstyleeffectivedata) - Ένα [ITextStyleEffectiveData](../../com.aspose.slides/itextstyleeffectivedata).