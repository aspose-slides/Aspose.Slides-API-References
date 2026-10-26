---
title: SlideUtil
second_title: Aspose.Slides για Android μέσω αναφοράς Java API
description: Προσφέρει μεθόδους που βοηθούν στην αναζήτηση σχημάτων και κειμένου σε μια παρουσίαση.
type: docs
url: /el/com.aspose.slides/slideutil/
---
**Κληρονομικότητα:**
java.lang.Object
```
public class SlideUtil
```

Προσφέρει μεθόδους που βοηθούν στην αναζήτηση σχημάτων και κειμένου σε μια παρουσίαση.

## Κατασκευαστές

| Κατασκευαστής | Περιγραφή |
| --- | --- |
| [SlideUtil()](#SlideUtil--) |  |

## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [findShape(IPresentation pres, String altText)](#findShape-com.aspose.slides.IPresentation-java.lang.String-) | Βρίσκει σχήμα με βάση το εναλλακτικό κείμενο σε παρουσίαση PPTX. |
| [findShape(IBaseSlide slide, String altText)](#findShape-com.aspose.slides.IBaseSlide-java.lang.String-) | Βρίσκει σχήμα με βάση το εναλλακτικό κείμενο σε μια διαφάνεια σε παρουσίαση PPTX. |
| [findShapesByPlaceholderType(IBaseSlide slide, byte placeholderType)](#findShapesByPlaceholderType-com.aspose.slides.IBaseSlide-byte-) | Αναζητά όλα τα σχήματα στην καθορισμένη διαφάνεια που ταιριάζουν με τον δεδομένο τύπο θέσης κράτησης. |
| [alignShapes(int alignmentType, boolean alignToSlide, IBaseSlide slide)](#alignShapes-int-boolean-com.aspose.slides.IBaseSlide-) | Αλλάζει τη θέση όλων των σχημάτων στη διαφάνεια. |
| [alignShapes(int alignmentType, boolean alignToSlide, IBaseSlide slide, int[] shapeIndexes)](#alignShapes-int-boolean-com.aspose.slides.IBaseSlide-int---) | Αλλάζει τη θέση των επιλεγμένων σχημάτων στη διαφάνεια. |
| [alignShapes(int alignmentType, boolean alignToSlide, IGroupShape groupShape)](#alignShapes-int-boolean-com.aspose.slides.IGroupShape-) | Αλλάζει τη θέση όλων των σχημάτων εντός της ομάδας σχημάτων. |
| [alignShapes(int alignmentType, boolean alignToSlide, IGroupShape groupShape, int[] shapeIndexes)](#alignShapes-int-boolean-com.aspose.slides.IGroupShape-int---) | Αλλάζει τη θέση των επιλεγμένων σχημάτων εντός της ομάδας σχημάτων. |
| [findAndReplaceText(IPresentation presentation, boolean withMasters, String find, String replace)](#findAndReplaceText-com.aspose.slides.IPresentation-boolean-java.lang.String-java.lang.String-) | Βρίσκει και αντικαθιστά κείμενο στην παρουσίαση με δεδομένη μορφή |
| [findAndReplaceText(IPresentation presentation, boolean withMasters, String find, String replace, PortionFormat format)](#findAndReplaceText-com.aspose.slides.IPresentation-boolean-java.lang.String-java.lang.String-com.aspose.slides.PortionFormat-) | Βρίσκει και αντικαθιστά κείμενο στην παρουσίαση με δεδομένη μορφή |
| [getAllTextBoxes(IBaseSlide slide)](#getAllTextBoxes-com.aspose.slides.IBaseSlide-) | Επιστρέφει όλα τα πλαίσια κειμένου σε μια διαφάνεια σε παρουσίαση PPTX. |
| [getTextBoxesContainsText(IBaseSlide slide, String text, boolean checkPlaceholderText)](#getTextBoxesContainsText-com.aspose.slides.IBaseSlide-java.lang.String-boolean-) | Επιστρέφει όλα τα πλαίσια κειμένου στην καθορισμένη διαφάνεια που περιέχουν το δεδομένο κείμενο. |
| [getAllTextFrames(IPresentation pres, boolean withMasters)](#getAllTextFrames-com.aspose.slides.IPresentation-boolean-) | Επιστρέφει όλα τα πλαίσια κειμένου σε παρουσίαση PPTX. |
| [toSaveFormat(int format)](#toSaveFormat-int-) | Μετατρέπει τη μορφή αρχείου πηγής στην αντίστοιχη [SaveFormat](../../com.aspose.slides/saveformat). |

### SlideUtil() {#SlideUtil--}
```
public SlideUtil()
```

### findShape(IPresentation pres, String altText) {#findShape-com.aspose.slides.IPresentation-java.lang.String-}
```
public static IShape findShape(IPresentation pres, String altText)
```

Βρίσκει σχήμα με βάση το εναλλακτικό κείμενο σε παρουσίαση PPTX.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| pres | [IPresentation](../../com.aspose.slides/ipresentation) | Σαρωμένη παρουσίαση. |
| altText | java.lang.String | Εναλλακτικό κείμενο ενός σχήματος. |

**Επιστρέφει:**
[IShape](../../com.aspose.slides/ishape) - Σχήμα ή null.

### findShape(IBaseSlide slide, String altText) {#findShape-com.aspose.slides.IBaseSlide-java.lang.String-}
```
public static IShape findShape(IBaseSlide slide, String altText)
```

Βρίσκει σχήμα με βάση το εναλλακτικό κείμενο σε μια διαφάνεια σε παρουσίαση PPTX.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| slide | [IBaseSlide](../../com.aspose.slides/ibaseslide) | Σαρωμένη διαφάνεια. |
| altText | java.lang.String | Εναλλακτικό κείμενο ενός σχήματος. |

**Επιστρέφει:**
[IShape](../../com.aspose.slides/ishape) - Σχήμα ή null.

### findShapesByPlaceholderType(IBaseSlide slide, byte placeholderType) {#findShapesByPlaceholderType-com.aspose.slides.IBaseSlide-byte-}
```
public static IShape[] findShapesByPlaceholderType(IBaseSlide slide, byte placeholderType)
```

Αναζητά όλα τα σχήματα στην καθορισμένη διαφάνεια που ταιριάζουν με τον δεδομένο τύπο θέσης κράτησης.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| slide | [IBaseSlide](../../com.aspose.slides/ibaseslide) | Η διαφάνεια στην οποία θα αναζητηθούν σχήματα. |
| placeholderType | byte | Ο τύπος της θέσης κράτησης για φιλτράρισμα των σχημάτων. |

**Επιστρέφει:**
com.aspose.slides.IShape[] - Ένα σύνολο από αντικείμενα [IShape](../../com.aspose.slides/ishape) που ταιριάζουν με τον καθορισμένο τύπο θέσης κράτησης.

### alignShapes(int alignmentType, boolean alignToSlide, IBaseSlide slide) {#alignShapes-int-boolean-com.aspose.slides.IBaseSlide-}
```
public static void alignShapes(int alignmentType, boolean alignToSlide, IBaseSlide slide)
```

Αλλάζει τη θέση όλων των σχημάτων στη διαφάνεια. Ευθυγραμμίζει τα σχήματα στα περιθώρια ή στο άκρο της διαφάνειας ή τα ευθυγραμμίζει μεταξύ τους.

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      SlideUtil.alignShapes(ShapesAlignmentType.AlignBottom, true, pres.getSlides().get_Item(0));
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| alignmentType | int | Καθορίζει ποιος τύπος στοίχισης θα εφαρμοστεί. |
| alignToSlide | boolean | Εάν είναι true, τα σχήματα θα ευθυγραμμιστούν σχετικά με τα άκρα της διαφάνειας. |
| slide | [IBaseSlide](../../com.aspose.slides/ibaseslide) | Γονική διαφάνεια. |

### alignShapes(int alignmentType, boolean alignToSlide, IBaseSlide slide, int[] shapeIndexes) {#alignShapes-int-boolean-com.aspose.slides.IBaseSlide-int---}
```
public static void alignShapes(int alignmentType, boolean alignToSlide, IBaseSlide slide, int[] shapeIndexes)
```

Αλλάζει τη θέση των επιλεγμένων σχημάτων στη διαφάνεια. Ευθυγραμμίζει τα σχήματα στα περιθώρια ή στο άκρο της διαφάνειας ή τα ευθυγραμμίζει μεταξύ τους.

--------------------

> ```
> Example:
>   
>   Presentation pres = new Presentation("pres.pptx");
>   try {
>      ISlide slide = pres.getSlides().get_Item(0);
>      IShape shape1 = slide.getShapes().get_Item(0);
>      IShape shape2 = slide.getShapes().get_Item(1);
>      SlideUtil.alignShapes(ShapesAlignmentType.AlignBottom, false, pres.getSlides().get_Item(0), new int[]
>      {
>          slide.getShapes().indexOf(shape1),
>          slide.getShapes().indexOf(shape2)
>      });
>   } finally {
>      if (pres != null) pres.dispose();
>   }
> ```

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| alignmentType | int | Καθορίζει ποιος τύπος στοίχισης θα εφαρμοστεί. |
| alignToSlide | boolean | Εάν είναι true, τα σχήματα θα ευθυγραμμιστούν σχετικά με τα άκρα της διαφάνειας. |
| slide | [IBaseSlide](../../com.aspose.slides/ibaseslide) | Γονική διαφάνεια. |
| shapeIndexes | int[] | Δείκτης των σχημάτων που θα ευθυγραμμιστούν. |

### alignShapes(int alignmentType, boolean alignToSlide, IGroupShape groupShape) {#alignShapes-int-boolean-com.aspose.slides.IGroupShape-}
```
public static void alignShapes(int alignmentType, boolean alignToSlide, IGroupShape groupShape)
```

Αλλάζει τη θέση όλων των σχημάτων εντός της ομάδας σχημάτων. Ευθυγραμμίζει τα σχήματα στα περιθώρια ή στο άκρο της διαφάνειας ή τα ευθυγραμμίζει μεταξύ τους.

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      ISlide slide = pres.getSlides().get_Item(0);
>      SlideUtil.alignShapes(ShapesAlignmentType.AlignLeft, false, (GroupShape) slide.getShapes().get_Item(0));
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| alignmentType | int | Καθορίζει ποιος τύπος στοίχισης θα εφαρμοστεί. |
| alignToSlide | boolean | Εάν είναι true, τα σχήματα θα ευθυγραμμιστούν σχετικά με τα άκρα της διαφάνειας. |
| groupShape | [IGroupShape](../../com.aspose.slides/igroupshape) | Γονική ομάδα σχήματος. |

### alignShapes(int alignmentType, boolean alignToSlide, IGroupShape groupShape, int[] shapeIndexes) {#alignShapes-int-boolean-com.aspose.slides.IGroupShape-int---}
```
public static void alignShapes(int alignmentType, boolean alignToSlide, IGroupShape groupShape, int[] shapeIndexes)
```

Αλλάζει τη θέση των επιλεγμένων σχημάτων εντός της ομάδας σχημάτων. Ευθυγραμμίζει τα σχήματα στα περιθώρια ή στο άκρο της διαφάνειας ή τα ευθυγραμμίζει μεταξύ τους.

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      ISlide slide = pres.getSlides().get_Item(0);
>      SlideUtil.alignShapes(ShapesAlignmentType.AlignLeft, false, (GroupShape)slide.getShapes().get_Item(0), new int[] { 0, 2 });
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| alignmentType | int | Καθορίζει ποιος τύπος στοίχισης θα εφαρμοστεί. |
| alignToSlide | boolean | Εάν είναι true, τα σχήματα θα ευθυγραμμιστούν σχετικά με τα άκρα της διαφάνειας. |
| groupShape | [IGroupShape](../../com.aspose.slides/igroupshape) | Γονική ομάδα σχήματος. |
| shapeIndexes | int[] | Δείκτης των σχημάτων που θα ευθυγραμμιστούν. |

### findAndReplaceText(IPresentation presentation, boolean withMasters, String find, String replace) {#findAndReplaceText-com.aspose.slides.IPresentation-boolean-java.lang.String-java.lang.String-}
```
public static void findAndReplaceText(IPresentation presentation, boolean withMasters, String find, String replace)
```

Βρίσκει και αντικαθιστά κείμενο στην παρουσίαση με δεδομένη μορφή

--------------------

> ```
> Presentation pres = new Presentation("pres.pptx");
>  try {
>      PortionFormat format = new PortionFormat();
>      format.setFontHeight(24f);
>      format.setFontItalic(NullableBool.True);
>      format.getFillFormat().setFillType(FillType.Solid);
>      format.getFillFormat().getSolidFillColor().setColor(Color.RED);
> 
>      SlideUtil.findAndReplaceText(pres, true, "[this block] ", "my text ", format);
>      pres.save("replaced.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| presentation | [IPresentation](../../com.aspose.slides/ipresentation) | Σαρωμένη παρουσίαση. |
| withMasters | boolean | Καθορίζει αν πρέπει να σαρωθούν οι κύριες διαφάνειες. |
| find | java.lang.String | Τιμή συμβολοσειράς προς εύρεση. |
| replace | java.lang.String | Τιμή συμβολοσειράς αντικατάστασης. χαρακτήρας της ευρεθείσας συμβολοσειράς |

### findAndReplaceText(IPresentation presentation, boolean withMasters, String find, String replace, PortionFormat format) {#findAndReplaceText-com.aspose.slides.IPresentation-boolean-java.lang.String-java.lang.String-com.aspose.slides.PortionFormat-}
```
public static void findAndReplaceText(IPresentation presentation, boolean withMasters, String find, String replace, PortionFormat format)
```

Βρίσκει και αντικαθιστά κείμενο στην παρουσίαση με δεδομένη μορφή

--------------------

> ```
> Presentation pres = new Presentation("pres.pptx");
>  try {
>      PortionFormat format = new PortionFormat();
>      format.setFontHeight(24f);
>      format.setFontItalic(NullableBool.True);
>      format.getFillFormat().setFillType(FillType.Solid);
>      format.getFillFormat().getSolidFillColor().setColor(Color.RED);
> 
>      SlideUtil.findAndReplaceText(pres, true, "[this block] ", "my text ", format);
>      pres.save("replaced.pptx", SaveFormat.Pptx);
>  finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| presentation | [IPresentation](../../com.aspose.slides/ipresentation) | Σαρωμένη παρουσίαση. |
| withMasters | boolean | Καθορίζει αν πρέπει να σαρωθούν οι κύριες διαφάνειες. |
| find | java.lang.String | Τιμή συμβολοσειράς προς εύρεση. |
| replace | java.lang.String | Τιμή συμβολοσειράς αντικατάστασης. |
| format | [PortionFormat](../../com.aspose.slides/portionformat) | Μορφή για αντικατάσταση τμήματος κειμένου. Εάν είναι null, θα χρησιμοποιηθεί η μορφή του πρώτου χαρακτήρα της ευρεθείσας συμβολοσειράς. |

### getAllTextBoxes(IBaseSlide slide) {#getAllTextBoxes-com.aspose.slides.IBaseSlide-}
```
public static ITextFrame[] getAllTextBoxes(IBaseSlide slide)
```

Επιστρέφει όλα τα πλαίσια κειμένου σε μια διαφάνεια σε παρουσίαση PPTX.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| slide | [IBaseSlide](../../com.aspose.slides/ibaseslide) | Σαρωμένη διαφάνεια. |

**Επιστρέφει:**
com.aspose.slides.ITextFrame[] - Σύνολο αντικειμένων [TextFrame](../../com.aspose.slides/textframe).

### getTextBoxesContainsText(IBaseSlide slide, String text, boolean checkPlaceholderText) {#getTextBoxesContainsText-com.aspose.slides.IBaseSlide-java.lang.String-boolean-}
```
public static ITextFrame[] getTextBoxesContainsText(IBaseSlide slide, String text, boolean checkPlaceholderText)
```

Επιστρέφει όλα τα πλαίσια κειμένου στην καθορισμένη διαφάνεια που περιέχουν το δεδομένο κείμενο.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| slide | [IBaseSlide](../../com.aspose.slides/ibaseslide) | Η διαφάνεια στην οποία θα πραγματοποιηθεί η αναζήτηση. |
| text | java.lang.String | Το κείμενο που θα αναζητηθεί εντός των πλαισίων κειμένου. |
| checkPlaceholderText | boolean | Καθορίζει αν θα συμπεριληφθούν πλαίσια κειμένου που είναι κενά, αλλά το κείμενο θέσης κράτησης περιέχει το αναζητούμενο κείμενο. |

**Επιστρέφει:**
com.aspose.slides.ITextFrame[] - Ένα σύνολο από αντικείμενα [ITextFrame](../../com.aspose.slides/itextframe) που περιέχουν το καθορισμένο κείμενο.

### getAllTextFrames(IPresentation pres, boolean withMasters) {#getAllTextFrames-com.aspose.slides.IPresentation-boolean-}
```
public static ITextFrame[] getAllTextFrames(IPresentation pres, boolean withMasters)
```

Επιστρέφει όλα τα πλαίσια κειμένου σε παρουσίαση PPTX.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| pres | [IPresentation](../../com.aspose.slides/ipresentation) | Σαρωμένη παρουσίαση. |
| withMasters | boolean | Καθορίζει αν πρέπει να σαρωθούν οι κύριες διαφάνειες. |

**Επιστρέφει:**
com.aspose.slides.ITextFrame[] - Σύνολο αντικειμένων [TextFrame](../../com.aspose.slides/textframe).

### toSaveFormat(int format) {#toSaveFormat-int-}
```
public static int toSaveFormat(int format)
```

Μετατρέπει τη μορφή αρχείου πηγής στην αντίστοιχη [SaveFormat](../../com.aspose.slides/saveformat).

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| format | int | Η μορφή αρχείου πηγής. |

**Επιστρέφει:**
int - Η αντίστοιχη τιμή [SaveFormat](../../com.aspose.slides/saveformat).