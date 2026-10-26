---
title: TextStyle
second_title: Αναφορά API του Aspose.Slides για Java
description: Αυτή η κλάση περιέχει τις ιδιότητες διαμόρφωσης του στυλ κειμένου.
type: docs
url: /el/com.aspose.slides/textstyle/
---
**Κληρονόμηση:**
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject)

**Όλες οι Υλοποιημένες Διεπαφές:**
[com.aspose.slides.ITextStyle](../../com.aspose.slides/itextstyle), com.aspose.slides.IStyleColorOwner
```
public final class TextStyle extends PVIObject implements ITextStyle, IStyleColorOwner
```

Αυτή η κλάση περιέχει τις ιδιότητες διαμόρφωσης του στυλ κειμένου.
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [getVersion()](#getVersion--) |  |
| [getLevel(int index)](#getLevel-int-) | Εάν υπάρχει επίπεδο στυλ, το επιστρέφει, διαφορετικά επιστρέφει null. |
| [getDefaultParagraphFormat()](#getDefaultParagraphFormat--) | Προεπιλεγμένες ιδιότητες παραγράφου. |
| [getEffective()](#getEffective--) | Λαμβάνει τα δεδομένα διαμόρφωσης του αποτελεσματικού στυλ κειμένου με την εφαρμοσμένη κληρονόμηση. |
### getVersion() {#getVersion--}
```
public long getVersion()
```


Έκδοση. Μόνο για ανάγνωση long.

**Επιστρέφει:**
long
### getLevel(int index) {#getLevel-int-}
```
public final IParagraphFormat getLevel(int index)
```


Εάν υπάρχει επίπεδο στυλ, το επιστρέφει, διαφορετικά επιστρέφει null.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| index | int | Μηδενική βάση δείκτης του επιπέδου. Πρέπει να είναι στο διάστημα 0..8. |

**Επιστρέφει:**
[IParagraphFormat](../../com.aspose.slides/iparagraphformat) - Διαμόρφωση επιπέδου [IParagraphFormat](../../com.aspose.slides/iparagraphformat).
### getDefaultParagraphFormat() {#getDefaultParagraphFormat--}
```
public final IParagraphFormat getDefaultParagraphFormat()
```


Προεπιλεγμένες ιδιότητες παραγράφου. Μόνο για ανάγνωση [IParagraphFormat](../../com.aspose.slides/iparagraphformat).

**Επιστρέφει:**
[IParagraphFormat](../../com.aspose.slides/iparagraphformat)
### getEffective() {#getEffective--}
```
public final ITextStyleEffectiveData getEffective()
```


Λαμβάνει τα δεδομένα διαμόρφωσης του αποτελεσματικού στυλ κειμένου με την εφαρμοσμένη κληρονόμηση.

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