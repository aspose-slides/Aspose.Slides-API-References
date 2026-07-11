---
title: TextFrame
second_title: Aspose.Slides για Android μέσω Αναφοράς Java API
description: Αναπαριστά ένα TextFrame.
type: docs
url: /el/com.aspose.slides/textframe/
---
**Κληρονόμηση:**
java.lang.Object

**Όλες οι Υλοποιημένες Διεπαφές:**
[com.aspose.slides.ITextFrame](../../com.aspose.slides/itextframe), com.aspose.slides.IDOMObject
```
public final class TextFrame implements ITextFrame, IDOMObject
```

Αντιπροσωπεύει ένα TextFrame.
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [getParent_Immediate()](#getParent-Immediate--) |  |
| [getParagraphs()](#getParagraphs--) | Επιστρέφει τη λίστα όλων των παραγράφων σε ένα πλαίσιο. |
| [getText()](#getText--) | Ανακτά ή ορίζει το απλό κείμενο για ένα TextFrame. |
| [setText(String value)](#setText-java.lang.String-) | Ανακτά ή ορίζει το απλό κείμενο για ένα TextFrame. |
| [getTextFrameFormat()](#getTextFrameFormat--) | Επιστρέφει το αντικείμενο μορφοποίησης για αυτό το αντικείμενο TextFrame. |
| [getHyperlinkQueries()](#getHyperlinkQueries--) | Παρέχει εύκολη πρόσβαση στους ενσωματωμένους υπερσύνδεσμους. |
| [joinPortionsWithSameFormatting()](#joinPortionsWithSameFormatting--) | Συγχωνεύει τις διαδοχές με την ίδια μορφοποίηση σε όλες τις παραγράφους. |
| [highlightText(String text, Integer highlightColor)](#highlightText-java.lang.String-java.lang.Integer-) | Τονίζει όλα τα ταιριάσματα του δείγματος κειμένου με το καθορισμένο χρώμα. |
| [highlightText(String text, Integer highlightColor, ITextHighlightingOptions options)](#highlightText-java.lang.String-java.lang.Integer-com.aspose.slides.ITextHighlightingOptions-) | Τονίζει όλα τα ταιριάσματα του δείγματος κειμένου με το καθορισμένο χρώμα. |
| [splitTextByColumns()](#splitTextByColumns--) | Διαιρεί το περιεχόμενο κειμένου του [ITextFrame](../../com.aspose.slides/itextframe) σε έναν πίνακα συμβολοσειρών, όπου κάθε στοιχείο αντιστοιχεί σε μια ξεχωριστή στήλη κειμένου μέσα στο πλαίσιο. |
| [highlightText(String text, Integer highlightColor, ITextSearchOptions options, IFindResultCallback callback)](#highlightText-java.lang.String-java.lang.Integer-com.aspose.slides.ITextSearchOptions-com.aspose.slides.IFindResultCallback-) | Τονίζει όλα τα ταιριάσματα του δείγματος κειμένου με το καθορισμένο χρώμα. |
| [highlightRegex(String regex, Integer highlightColor, ITextHighlightingOptions options)](#highlightRegex-java.lang.String-java.lang.Integer-com.aspose.slides.ITextHighlightingOptions-) | Τονίζει όλα τα ταιριάσματα της κανονικής έκφρασης με το καθορισμένο χρώμα. |
| [highlightRegex(Pattern regex, Integer highlightColor, IFindResultCallback callback)](#highlightRegex-java.util.regex.Pattern-java.lang.Integer-com.aspose.slides.IFindResultCallback-) | Τονίζει όλα τα ταιριάσματα της κανονικής έκφρασης με το καθορισμένο χρώμα. |
| [replaceText(String oldText, String newText, ITextSearchOptions options, IFindResultCallback callback)](#replaceText-java.lang.String-java.lang.String-com.aspose.slides.ITextSearchOptions-com.aspose.slides.IFindResultCallback-) | Αντικαθιστά όλες τις εμφανίσεις του καθορισμένου κειμένου με άλλο καθορισμένο κείμενο. |
| [replaceRegex(Pattern regex, String newText, IFindResultCallback callback)](#replaceRegex-java.util.regex.Pattern-java.lang.String-com.aspose.slides.IFindResultCallback-) | Αντικαθιστά όλα τα ταιριάσματα της κανονικής έκφρασης με το καθορισμένο συμβολοσειρά. |
| [getSlide()](#getSlide--) | Επιστρέφει τη γονική διαφάνεια ενός TextFrame. |
| [getPresentation()](#getPresentation--) | Επιστρέφει την γονική παρουσίαση ενός TextFrame. |
| [getParentShape()](#getParentShape--) | Επιστρέφει το γονικό σχήμα ή null εάν το γονικό αντικείμενο δεν υλοποιεί τη διεπαφή IShape Μόνο για ανάγνωση [IShape](../../com.aspose.slides/ishape). |
| [getParentCell()](#getParentCell--) | Επιστρέφει το γονικό κελί ή null εάν το γονικό αντικείμενο δεν υλοποιεί τη διεπαφή ICell. |

### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```

Επιστρέφει το αντικείμενο Parent_Immediate. Μόνο για ανάγνωση IDOMObject.

**Επιστρέφει:**
com.aspose.slides.IDOMObject

### getParagraphs() {#getParagraphs--}
```
public final IParagraphCollection getParagraphs()
```

Επιστρέφει τη λίστα όλων των παραγράφων σε ένα πλαίσιο. Μόνο για ανάγνωση [IParagraphCollection](../../com.aspose.slides/iparagraphcollection).

**Επιστρέφει:**
[IParagraphCollection](../../com.aspose.slides/iparagraphcollection)

### getText() {#getText--}
```
public final String getText()
```

Ανακτά ή ορίζει το απλό κείμενο για ένα TextFrame. Ανάγνωση/εγγραφή String.

Τιμή: Το κείμενο.

**Επιστρέφει:**
java.lang.String

### setText(String value) {#setText-java.lang.String-}
```
public final void setText(String value)
```

Ανακτά ή ορίζει το απλό κείμενο για ένα TextFrame. Ανάγνωση/εγγραφή String.

Τιμή: Το κείμενο.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | java.lang.String |  |

### getTextFrameFormat() {#getTextFrameFormat--}
```
public final ITextFrameFormat getTextFrameFormat()
```

Επιστρέφει το αντικείμενο μορφοποίησης για αυτό το αντικείμενο TextFrame. Μόνο για ανάγνωση [ITextFrameFormat](../../com.aspose.slides/itextframeformat).

**Επιστρέφει:**
[ITextFrameFormat](../../com.aspose.slides/itextframeformat)

### getHyperlinkQueries() {#getHyperlinkQueries--}
```
public final IHyperlinkQueries getHyperlinkQueries()
```

Παρέχει εύκολη πρόσβαση στους ενσωματωμένους υπερσύνδεσμους. Μόνο για ανάγνωση [IHyperlinkQueries](../../com.aspose.slides/ihyperlinkqueries).

**Επιστρέφει:**
[IHyperlinkQueries](../../com.aspose.slides/ihyperlinkqueries)

### joinPortionsWithSameFormatting() {#joinPortionsWithSameFormatting--}
```
public final void joinPortionsWithSameFormatting()
```

Συγχωνεύει τις διαδοχές με την ίδια μορφοποίηση σε όλες τις παραγράφους.

### highlightText(String text, Integer highlightColor) {#highlightText-java.lang.String-java.lang.Integer-}
```
public final void highlightText(String text, Integer highlightColor)
```

Τονίζει όλα τα ταιριάσματα του δείγματος κειμένου με το καθορισμένο χρώμα.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| text | java.lang.String | Δείγμα κειμένου προς επισήμανση. |
| highlightColor | java.lang.Integer | Το χρώμα για την επισήμανση του κειμένου. |

### highlightText(String text, Integer highlightColor, ITextHighlightingOptions options) {#highlightText-java.lang.String-java.lang.Integer-com.aspose.slides.ITextHighlightingOptions-}
```
public final void highlightText(String text, Integer highlightColor, ITextHighlightingOptions options)
```

Τονίζει όλα τα ταιριάσματα του δείγματος κειμένου με το καθορισμένο χρώμα.

--------------------

> ```
> The following sample code shows how to Highlight Text in a TextFrame.
>  
>  try {
>      TextHighlightingOptions textHighlightingOptions = new TextHighlightingOptions();
>      textHighlightingOptions.setWholeWordsOnly(true);
>      // highlighting all words 'important'
>      ((AutoShape)pres.getSlides().get_Item(0).getShapes().get_Item(0)).getTextFrame().highlightText("title", Color.BLUE);
>      // highlighting all separate 'the' occurrences
>      ((AutoShape)pres.getSlides().get_Item(0).getShapes().get_Item(0)).getTextFrame().highlightText("to", Color.MAGENTA, textHighlightingOptions);
>      pres.save("SomePresentation-out2.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| text | java.lang.String | Το κείμενο προς επισήμανση. |
| highlightColor | java.lang.Integer | Το χρώμα για την επισήμανση του κειμένου. |
| options | [ITextHighlightingOptions](../../com.aspose.slides/itexthighlightingoptions) | Επιλογές επισήμανσης. |

### splitTextByColumns() {#splitTextByColumns--}
```
public final String[] splitTextByColumns()
```

Διαιρεί το περιεχόμενο κειμένου του [ITextFrame](../../com.aspose.slides/itextframe) σε έναν πίνακα συμβολοσειρών, όπου κάθε στοιχείο αντιστοιχεί σε μια ξεχωριστή στήλη κειμένου μέσα στο πλαίσιο.

--------------------

> ```
> The following example demonstrates how to use #splitTextByColumns.splitTextByColumns:
>  
>  Presentation pres = new Presentation("example.pptx");
>  try {
>      // Get the first shape on the slide and cast it to ITextFrame
>      ITextFrame textFrame = (ITextFrame) pres.getSlides().get_Item(0).getShapes().get_Item(0);
>      // Split the text frame content into columns
>      String[] columnsText = textFrame.splitTextByColumns();
>      // Print each column's text to the console
>      for (String column : columnsText)
>          System.out.println(column);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Επιστρέφει:**
java.lang.String[] - Ένας πίνακας συμβολοσειρών, όπου κάθε συμβολοσειρά αντιπροσωπεύει το περιεχόμενο κειμένου μιας συγκεκριμένης στήλης στο [ITextFrame](../../com.aspose.slides/itextframe).

--------------------

Αν το πλαίσιο κειμένου δεν περιέχει πολλαπλές στήλες, ο επιστρεφόμενος πίνακας θα έχει ένα μοναδικό στοιχείο που περιέχει ολόκληρο το κείμενο. Κενές στήλες θα παρουσιαστούν ως κενές συμβολοσειρές στον πίνακα.

### highlightText(String text, Integer highlightColor, ITextSearchOptions options, IFindResultCallback callback) {#highlightText-java.lang.String-java.lang.Integer-com.aspose.slides.ITextSearchOptions-com.aspose.slides.IFindResultCallback-}
```
public final void highlightText(String text, Integer highlightColor, ITextSearchOptions options, IFindResultCallback callback)
```

Τονίζει όλα τα ταιριάσματα του δείγματος κειμένου με το καθορισμένο χρώμα.

--------------------

> ```
> The following code sample shows how to highlight text in a TextFrame.
>  
>  Presentation presentation = new Presentation("SomePresentation.pptx");
>  try {
>      TextSearchOptions textSearchOptions = new TextSearchOptions();
>      textSearchOptions.setWholeWordsOnly(true);
>      // επισήμανση όλων των λέξεων 'important'
>      ((AutoShape)presentation.getSlides().get_Item(0).getShapes().get_Item(0)).getTextFrame().highlightText("important", Color.BLUE);
>      // επισήμανση όλων των ξεχωριστών εμφανίσεων του 'the'
>      ((AutoShape)presentation.getSlides().get_Item(0).getShapes().get_Item(0)).getTextFrame().highlightText("the", Color.MAGENTA, textSearchOptions, null);
>      presentation.save("SomePresentation-out2.pptx", SaveFormat.Pptx);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```


**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| text | java.lang.String | Το κείμενο προς επισήμανση. |
| highlightColor | java.lang.Integer | Το χρώμα για την επισήμανση του κειμένου. |
| options | [ITextSearchOptions](../../com.aspose.slides/itextsearchoptions) | Επιλογές αναζήτησης κειμένου [ITextSearchOptions](../../com.aspose.slides/itextsearchoptions). |
| callback | [IFindResultCallback](../../com.aspose.slides/ifindresultcallback) | Το αντικείμενο κλήσης για λήψη αποτελεσμάτων αναζήτησης [IFindResultCallback](../../com.aspose.slides/ifindresultcallback). |

### highlightRegex(String regex, Integer highlightColor, ITextHighlightingOptions options) {#highlightRegex-java.lang.String-java.lang.Integer-com.aspose.slides.ITextHighlightingOptions-}
```
public final void highlightRegex(String regex, Integer highlightColor, ITextHighlightingOptions options)
```

Τονίζει όλα τα ταιριάσματα της κανονικής έκφρασης με το καθορισμένο χρώμα.

--------------------

> ```
> The following code sample shows how to highlight text in a TextFrame using a regular expression.
>  
>  Presentation pres = new Presentation("SomePresentation.pptx");
>  try {
>      TextHighlightingOptions options = new TextHighlightingOptions();
>      // επισήμανση όλων των λέξεων με 10 ή περισσότερα σύμβολα
>      ((AutoShape) pres.getSlides().get_Item(0).getShapes().get_Item(0)).getTextFrame().highlightRegex("\\b[^\\s){5,}\\b", Color.BLUE, options);
>      pres.save("SomePresentation-out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| regex | java.lang.String | Κείμενο κανονικής έκφρασης για την επισήμανση. |
| highlightColor | java.lang.Integer | Το χρώμα για την επισήμανση του κειμένου. |
| options | [ITextHighlightingOptions](../../com.aspose.slides/itexthighlightingoptions) | Επιλογές επισήμανσης. |

### highlightRegex(Pattern regex, Integer highlightColor, IFindResultCallback callback) {#highlightRegex-java.util.regex.Pattern-java.lang.Integer-com.aspose.slides.IFindResultCallback-}
```
public final void highlightRegex(Pattern regex, Integer highlightColor, IFindResultCallback callback)
```

Τονίζει όλα τα ταιριάσματα της κανονικής έκφρασης με το καθορισμένο χρώμα.

--------------------

> ```
> The following code sample shows how to highlight text in a TextFrame using a regular expression.
>  
>  Presentation presentation = new Presentation("SomePresentation.pptx");
>  try {
>      Pattern regex = Pattern.compile("\\b[^\\s]{5,}\\b");
>      // επισήμανση όλων των λέξεων με 5 ή περισσότερα σύμβολα
>      ((AutoShape)presentation.getSlides().get_Item(0).getShapes().get_Item(0)).getTextFrame().highlightRegex(regex, Color.BLUE, null);
>      presentation.save("SomePresentation-out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```


**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| regex | java.util.regex.Pattern | Η κανονική έκφραση java.util.regex.Pattern για την επισήμανση. |
| highlightColor | java.lang.Integer | Το χρώμα για την επισήμανση του κειμένου. |
| callback | [IFindResultCallback](../../com.aspose.slides/ifindresultcallback) | Το αντικείμενο κλήσης για λήψη αποτελεσμάτων αναζήτησης [IFindResultCallback](../../com.aspose.slides/ifindresultcallback). |

### replaceText(String oldText, String newText, ITextSearchOptions options, IFindResultCallback callback) {#replaceText-java.lang.String-java.lang.String-com.aspose.slides.ITextSearchOptions-com.aspose.slides.IFindResultCallback-}
```
public final void replaceText(String oldText, String newText, ITextSearchOptions options, IFindResultCallback callback)
```

Αντικαθιστά όλες τις εμφανίσεις του καθορισμένου κειμένου με άλλο καθορισμένο κείμενο.

--------------------

> ```
> The following sample code shows how to replace one speified string with another speified string.
>  
>  Presentation presentation = new Presentation("SomePresentation.pptx");
>  try {
>      TextSearchOptions textSearchOptions = new TextSearchOptions();
>      textSearchOptions.setWholeWordsOnly(true);
>      // Αντικαταστήστε όλες τις ξεχωριστές εμφανίσεις του 'the' με '***'
>      ((AutoShape)presentation.getSlides().get_Item(0).getShapes().get_Item(0)).getTextFrame().replaceText("the", "***", textSearchOptions, null);
>      presentation.save("SomePresentation-out2.pptx", SaveFormat.Pptx);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```


**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| oldText | java.lang.String | Η συμβολοσειρά προς αντικατάσταση. |
| newText | java.lang.String | Η συμβολοσειρά που θα αντικαταστήσει όλες τις εμφανίσεις του oldText. |
| options | [ITextSearchOptions](../../com.aspose.slides/itextsearchoptions) | Επιλογές αναζήτησης κειμένου [ITextSearchOptions](../../com.aspose.slides/itextsearchoptions). |
| callback | [IFindResultCallback](../../com.aspose.slides/ifindresultcallback) | Αντικείμενο κλήσης για αποθήκευση του αποτελέσματος της αντικατάστασης [IFindResultCallback](../../com.aspose.slides/ifindresultcallback). |

### replaceRegex(Pattern regex, String newText, IFindResultCallback callback) {#replaceRegex-java.util.regex.Pattern-java.lang.String-com.aspose.slides.IFindResultCallback-}
```
public final void replaceRegex(Pattern regex, String newText, IFindResultCallback callback)
```

Αντικαθιστά όλα τα ταιριάσματα της κανονικής έκφρασης με το καθορισμένο συμβολοσειρά.

--------------------

> ```
> The following sample code shows how to replace text using regular expression with specified string.
>  
>  Presentation presentation = new Presentation("SomePresentation.pptx");
>  try {
>      Pattern regex = Pattern.compile("\\b[^\\s]{5,}\\b");
>      // Αντικαταστήστε όλες τις λέξεις με 5 ή περισσότερα σύμβολα με '***'
>      ((AutoShape)presentation.getSlides().get_Item(0).getShapes().get_Item(0)).getTextFrame().replaceRegex(regex, "***", null);
>      presentation.save("SomePresentation-out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```


**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| regex | java.util.regex.Pattern | Η κανονική έκφραση java.util.regex.Pattern για τις συμβολοσειρές προς αντικατάσταση. |
| newText | java.lang.String | Η συμβολοσειρά που θα αντικαταστήσει όλες τις εμφανίσεις των συμβολοσειρών προς αντικατάσταση. |
| callback | [IFindResultCallback](../../com.aspose.slides/ifindresultcallback) | Αντικείμενο κλήσης για αποθήκευση του αποτελέσματος της αντικατάστασης [IFindResultCallback](../../com.aspose.slides/ifindresultcallback). |

### getSlide() {#getSlide--}
```
public final IBaseSlide getSlide()
```

Επιστρέφει τη γονική διαφάνεια ενός TextFrame. Μόνο για ανάγνωση [IBaseSlide](../../com.aspose.slides/ibaseslide).

**Επιστρέφει:**
[IBaseSlide](../../com.aspose.slides/ibaseslide)

### getPresentation() {#getPresentation--}
```
public final IPresentation getPresentation()
```

Επιστρέφει την γονική παρουσίαση ενός TextFrame. Μόνο για ανάγνωση [IPresentation](../../com.aspose.slides/ipresentation).

**Επιστρέφει:**
[IPresentation](../../com.aspose.slides/ipresentation)

### getParentShape() {#getParentShape--}
```
public final IShape getParentShape()
```

Επιστρέφει το γονικό σχήμα ή null εάν το γονικό αντικείμενο δεν υλοποιεί τη διεπαφή IShape Μόνο για ανάγνωση [IShape](../../com.aspose.slides/ishape).

--------------------

> ```
> The following code sample shows 
>  
>  Presentation presentation = new Presentation("SomePresentation.pptx");
>  try {
>      AutoShape autoShape = (AutoShape)presentation.getSlides().get_Item(0).getShapes().get_Item(0);
>      Table table = (Table)presentation.getSlides().get_Item(0).getShapes().get_Item(1);
> 
>      // Αυτές οι δηλώσεις είναι πάντα αληθείς
>      Assert.assertTrue(autoShape.getTextFrame().getParentShape() == autoShape);
>      Assert.assertTrue((table.get_Item(0,0).getTextFrame()).getParentShape() == null);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```


**Επιστρέφει:**
[IShape](../../com.aspose.slides/ishape)

### getParentCell() {#getParentCell--}
```
public final ICell getParentCell()
```

Επιστρέφει το γονικό κελί ή null εάν το γονικό αντικείμενο δεν υλοποιεί τη διεπαφή ICell. Μόνο για ανάγνωση [ICell](../../com.aspose.slides/icell).

--------------------

> ```
> The following code sample shows 
>  
>  Presentation presentation = new Presentation("SomePresentation.pptx");
>  try {
>      AutoShape autoShape = (AutoShape)presentation.getSlides().get_Item(0).getShapes().get_Item(0);
>      Table table = (Table)presentation.getSlides().get_Item(0).getShapes().get_Item(1);
> 
>      // Αυτές οι δηλώσεις είναι πάντα αληθείς
>      Assert.assertTrue(table.get_Item(0,0).getTextFrame().getParentCell() == table.get_Item(0,0));
>      Assert.assertTrue(autoShape.getTextFrame().getParentCell() == null);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```


**Επιστρέφει:**
[ICell](../../com.aspose.slides/icell)