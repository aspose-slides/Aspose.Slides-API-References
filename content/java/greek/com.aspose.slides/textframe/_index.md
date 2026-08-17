---
title: TextFrame
second_title: Aspose.Slides για τη Java API Αναφορά
description: Αντιπροσωπεύει ένα TextFrame.
type: docs
url: /el/com.aspose.slides/textframe/
---
**Κληρονομικότητα:**
java.lang.Object

**Όλες οι Υλοποιημένες Διασυνδέσεις:**
[com.aspose.slides.ITextFrame](../../com.aspose.slides/itextframe), com.aspose.slides.IDOMObject
```
public final class TextFrame implements ITextFrame, IDOMObject
```

Αναπαριστά ένα TextFrame.
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [getParent_Immediate()](#getParent-Immediate--) |  |
| [getParagraphs()](#getParagraphs--) | Επιστρέφει τη λίστα όλων των παραγράφων σε ένα πλαίσιο. |
| [getText()](#getText--) | Ανακτά ή ορίζει το απλό κείμενο για ένα TextFrame. |
| [setText(String value)](#setText-java.lang.String-) | Ανακτά ή ορίζει το απλό κείμενο για ένα TextFrame. |
| [getTextFrameFormat()](#getTextFrameFormat--) | Επιστρέφει το αντικείμενο μορφοποίησης για αυτό το αντικείμενο TextFrame. |
| [getHyperlinkQueries()](#getHyperlinkQueries--) | Παρέχει εύκολη πρόσβαση στους ενσωματωμένους υπερσυνδέσμους. |
| [joinPortionsWithSameFormatting()](#joinPortionsWithSameFormatting--) | Συναρμολογεί τμήματα με την ίδια μορφοποίηση σε όλες τις παραγράφους. |
| [highlightText(String text, Color highlightColor)](#highlightText-java.lang.String-java.awt.Color-) | Επισημαίνει όλες τις αντιστοιχίες του δείγματος κειμένου με το καθορισμένο χρώμα. |
| [highlightText(String text, Color highlightColor, ITextHighlightingOptions options)](#highlightText-java.lang.String-java.awt.Color-com.aspose.slides.ITextHighlightingOptions-) | Επισημαίνει όλες τις αντιστοιχίες του δείγματος κειμένου με το καθορισμένο χρώμα. |
| [splitTextByColumns()](#splitTextByColumns--) | Διαιρεί το κείμενο του [ITextFrame](../../com.aspose.slides/itextframe) σε έναν πίνακα συμβολοσειρών, όπου κάθε στοιχείο αντιστοιχεί σε ξεχωριστή στήλη κειμένου μέσα στο πλαίσιο. |
| [highlightText(String text, Color highlightColor, ITextSearchOptions options, IFindResultCallback callback)](#highlightText-java.lang.String-java.awt.Color-com.aspose.slides.ITextSearchOptions-com.aspose.slides.IFindResultCallback-) | Επισημαίνει όλες τις αντιστοιχίες του δείγματος κειμένου με το καθορισμένο χρώμα. |
| [highlightRegex(String regex, Color highlightColor, ITextHighlightingOptions options)](#highlightRegex-java.lang.String-java.awt.Color-com.aspose.slides.ITextHighlightingOptions-) | Επισημαίνει όλες τις αντιστοιχίες της κανονικής έκφρασης με το καθορισμένο χρώμα. |
| [highlightRegex(Pattern regex, Color highlightColor, IFindResultCallback callback)](#highlightRegex-java.util.regex.Pattern-java.awt.Color-com.aspose.slides.IFindResultCallback-) | Επισημαίνει όλες τις αντιστοιχίες της κανονικής έκφρασης με το καθορισμένο χρώμα. |
| [replaceText(String oldText, String newText, ITextSearchOptions options, IFindResultCallback callback)](#replaceText-java.lang.String-java.lang.String-com.aspose.slides.ITextSearchOptions-com.aspose.slides.IFindResultCallback-) | Αντικαθιστά όλες τις εμφανίσεις του καθορισμένου κειμένου με άλλο καθορισμένο κείμενο. |
| [replaceRegex(Pattern regex, String newText, IFindResultCallback callback)](#replaceRegex-java.util.regex.Pattern-java.lang.String-com.aspose.slides.IFindResultCallback-) | Αντικαθιστά όλες τις αντιστοιχίες της κανονικής έκφρασης με το καθορισμένο συμβολοσειρά. |
| [getSlide()](#getSlide--) | Επιστρέφει τη γονική διαφάνεια ενός TextFrame. |
| [getPresentation()](#getPresentation--) | Επιστρέφει την γονική παρουσίαση ενός TextFrame. |
| [getParentShape()](#getParentShape--) | Επιστρέφει το γονικό σχήμα ή null εάν το γονικό αντικείμενο δεν υλοποιεί τη διεπαφή IShape. Μόνο-ανάγνωση [IShape](../../com.aspose.slides/ishape). |
| [getParentCell()](#getParentCell--) | Επιστρέφει το γονικό κελί ή null εάν το γονικό αντικείμενο δεν υλοποιεί τη διεπαφή ICell. |

### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```

Επιστρέφει το αντικείμενο Parent_Immediate. Μόνο-ανάγνωση IDOMObject.

**Επιστρέφει:**
com.aspose.slides.IDOMObject
### getParagraphs() {#getParagraphs--}
```
public final IParagraphCollection getParagraphs()
```

Επιστρέφει τη λίστα όλων των παραγράφων σε ένα πλαίσιο. Μόνο-ανάγνωση [IParagraphCollection](../../com.aspose.slides/iparagraphcollection).

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

Επιστρέφει το αντικείμενο μορφοποίησης για αυτό το αντικείμενο TextFrame. Μόνο-ανάγνωση [ITextFrameFormat](../../com.aspose.slides/itextframeformat).

**Επιστρέφει:**
[ITextFrameFormat](../../com.aspose.slides/itextframeformat)
### getHyperlinkQueries() {#getHyperlinkQueries--}
```
public final IHyperlinkQueries getHyperlinkQueries()
```

Παρέχει εύκολη πρόσβαση στους ενσωματωμένους υπερσυνδέσμους. Μόνο-ανάγνωση [IHyperlinkQueries](../../com.aspose.slides/ihyperlinkqueries).

**Επιστρέφει:**
[IHyperlinkQueries](../../com.aspose.slides/ihyperlinkqueries)
### joinPortionsWithSameFormatting() {#joinPortionsWithSameFormatting--}
```
public final void joinPortionsWithSameFormatting()
```

Συναρμολογεί τμήματα με την ίδια μορφοποίηση σε όλες τις παραγράφους.

### highlightText(String text, Color highlightColor) {#highlightText-java.lang.String-java.awt.Color-}
```
public final void highlightText(String text, Color highlightColor)
```

Επισημαίνει όλες τις αντιστοιχίες του δείγματος κειμένου με το καθορισμένο χρώμα.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| text | java.lang.String | Δείγμα κειμένου προς επισήμανση. |
| highlightColor | java.awt.Color | Το χρώμα με το οποίο θα επισημανθεί το κείμενο. |

### highlightText(String text, Color highlightColor, ITextHighlightingOptions options) {#highlightText-java.lang.String-java.awt.Color-com.aspose.slides.ITextHighlightingOptions-}
```
public final void highlightText(String text, Color highlightColor, ITextHighlightingOptions options)
```

Επισημαίνει όλες τις αντιστοιχίες του δείγματος κειμένου με το καθορισμένο χρώμα.

--------------------

> ```
> The following sample code shows how to Highlight Text in a TextFrame.
>  
>  try {
>      TextHighlightingOptions textHighlightingOptions = new TextHighlightingOptions();
>      textHighlightingOptions.setWholeWordsOnly(true);
>      // επισημαίνοντας όλες τις λέξεις 'important'
>      ((AutoShape)pres.getSlides().get_Item(0).getShapes().get_Item(0)).getTextFrame().highlightText("title", Color.BLUE);
>      // επισημαίνοντας όλες τις ξεχωριστές εμφανίσεις του 'the'
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
| highlightColor | java.awt.Color | Το χρώμα με το οποίο θα επισημανθεί το κείμενο. |
| options | [ITextHighlightingOptions](../../com.aspose.slides/itexthighlightingoptions) | Επιλογές επισήμανσης. |

### splitTextByColumns() {#splitTextByColumns--}
```
public final String[] splitTextByColumns()
```

Διαιρεί το κείμενο του [ITextFrame](../../com.aspose.slides/itextframe) σε έναν πίνακα συμβολοσειρών, όπου κάθε στοιχείο αντιστοιχεί σε ξεχωριστή στήλη κειμένου μέσα στο πλαίσιο.

--------------------

> ```
> The following example demonstrates how to use #splitTextByColumns.splitTextByColumns:
>  
>  Presentation pres = new Presentation("example.pptx");
>  try {
>      // Λάβετε το πρώτο σχήμα στη διαφάνεια και μετατρέψτε το σε ITextFrame
>      ITextFrame textFrame = (ITextFrame) pres.getSlides().get_Item(0).getShapes().get_Item(0);
>      // Διαχωρίστε το περιεχόμενο του πλαισίου κειμένου σε στήλες
>      String[] columnsText = textFrame.splitTextByColumns();
>      // Εκτυπώστε το κείμενο κάθε στήλης στην κονσόλα
>      for (String column : columnsText)
>          System.out.println(column);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Επιστρέφει:**
java.lang.String[] - Ένα σύνολο συμβολοσειρών, όπου κάθε συμβολοσειρά αντιπροσωπεύει το περιεχόμενο κειμένου μιας συγκεκριμένης στήλης στο [ITextFrame](../../com.aspose.slides/itextframe).

--------------------

Εάν το πλαίσιο κειμένου δεν περιέχει πολλαπλές στήλες, ο επιστρεφόμενος πίνακας θα έχει ένα μόνο στοιχείο που περιέχει ολόκληρο το κείμενο. Κενές στήλες θα αντιπροσωπεύονται ως κενές συμβολοσειρές στον πίνακα.
### highlightText(String text, Color highlightColor, ITextSearchOptions options, IFindResultCallback callback) {#highlightText-java.lang.String-java.awt.Color-com.aspose.slides.ITextSearchOptions-com.aspose.slides.IFindResultCallback-}
```
public final void highlightText(String text, Color highlightColor, ITextSearchOptions options, IFindResultCallback callback)
```

Επισημαίνει όλες τις αντιστοιχίες του δείγματος κειμένου με το καθορισμένο χρώμα.

--------------------

> ```
> The following code sample shows how to highlight text in a TextFrame.
>  
>  Presentation presentation = new Presentation("SomePresentation.pptx");
>  try {
>      TextSearchOptions textSearchOptions = new TextSearchOptions();
>      textSearchOptions.setWholeWordsOnly(true);
>      // επισημαίνοντας όλες τις λέξεις 'important'
>      ((AutoShape)presentation.getSlides().get_Item(0).getShapes().get_Item(0)).getTextFrame().highlightText("important", Color.BLUE);
>      // επισημαίνοντας όλες τις ξεχωριστές εμφανίσεις του 'the'
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
| highlightColor | java.awt.Color | Το χρώμα με το οποίο θα επισημανθεί το κείμενο. |
| options | [ITextSearchOptions](../../com.aspose.slides/itextsearchoptions) | Επιλογές αναζήτησης κειμένου [ITextSearchOptions](../../com.aspose.slides/itextsearchoptions). |
| callback | [IFindResultCallback](../../com.aspose.slides/ifindresultcallback) | Το αντικείμενο callback για λήψη αποτελεσμάτων αναζήτησης [IFindResultCallback](../../com.aspose.slides/ifindresultcallback). |

### highlightRegex(String regex, Color highlightColor, ITextHighlightingOptions options) {#highlightRegex-java.lang.String-java.awt.Color-com.aspose.slides.ITextHighlightingOptions-}
```
public final void highlightRegex(String regex, Color highlightColor, ITextHighlightingOptions options)
```

Επισημαίνει όλες τις αντιστοιχίες της κανονικής έκφρασης με το καθορισμένο χρώμα.

--------------------

> ```
> The following code sample shows how to highlight text in a TextFrame using a regular expression.
>  
>  Presentation pres = new Presentation("SomePresentation.pptx");
>  try {
>      TextHighlightingOptions options = new TextHighlightingOptions();
>      // επισημαίνοντας όλες τις λέξεις με 10 ή περισσότερα σύμβολα
>      ((AutoShape) pres.getSlides().get_Item(0).getShapes().get_Item(0)).getTextFrame().highlightRegex("\\b[^\\s){5,}\\b", Color.BLUE, options);
>      pres.save("SomePresentation-out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| regex | java.lang.String | Κείμενο της κανονικής έκφρασης για λήψη κειμένου προς επισήμανση. |
| highlightColor | java.awt.Color | Το χρώμα με το οποίο θα επισημανθεί το κείμενο. |
| options | [ITextHighlightingOptions](../../com.aspose.slides/itexthighlightingoptions) | Επιλογές επισήμανσης. |

### highlightRegex(Pattern regex, Color highlightColor, IFindResultCallback callback) {#highlightRegex-java.util.regex.Pattern-java.awt.Color-com.aspose.slides.IFindResultCallback-}
```
public final void highlightRegex(Pattern regex, Color highlightColor, IFindResultCallback callback)
```

Επισημαίνει όλες τις αντιστοιχίες της κανονικής έκφρασης με το καθορισμένο χρώμα.

--------------------

> ```
> The following code sample shows how to highlight text in a TextFrame using a regular expression.
>  
>  Presentation presentation = new Presentation("SomePresentation.pptx");
>  try {
>      Pattern regex = Pattern.compile("\\b[^\\s]{5,}\\b");
>      // επισημαίνοντας όλες τις λέξεις με 5 ή περισσότερα σύμβολα
>      ((AutoShape)presentation.getSlides().get_Item(0).getShapes().get_Item(0)).getTextFrame().highlightRegex(regex, Color.BLUE, null);
>      presentation.save("SomePresentation-out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```


**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| regex | java.util.regex.Pattern | Η κανονική έκφραση java.util.regex.Pattern για λήψη συμβολοσειρών προς επισήμανση. |
| highlightColor | java.awt.Color | Το χρώμα με το οποίο θα επισημανθεί το κείμενο. |
| callback | [IFindResultCallback](../../com.aspose.slides/ifindresultcallback) | Το αντικείμενο callback για λήψη αποτελεσμάτων αναζήτησης [IFindResultCallback](../../com.aspose.slides/ifindresultcallback). |

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
| oldText | java.lang.String | Η συμβολοσειρά που θα αντικατασταθεί. |
| newText | java.lang.String | Η συμβολοσειρά που θα αντικαταστήσει όλες τις εμφανίσεις του oldText. |
| options | [ITextSearchOptions](../../com.aspose.slides/itextsearchoptions) | Επιλογές αναζήτησης κειμένου [ITextSearchOptions](../../com.aspose.slides/itextsearchoptions). |
| callback | [IFindResultCallback](../../com.aspose.slides/ifindresultcallback) | Αντικείμενο callback για αποθήκευση αποτελέσματος λειτουργίας αντικατάστασης [IFindResultCallback](../../com.aspose.slides/ifindresultcallback). |

### replaceRegex(Pattern regex, String newText, IFindResultCallback callback) {#replaceRegex-java.util.regex.Pattern-java.lang.String-com.aspose.slides.IFindResultCallback-}
```
public final void replaceRegex(Pattern regex, String newText, IFindResultCallback callback)
```

Αντικαθιστά όλες τις αντιστοιχίες της κανονικής έκφρασης με το καθορισμένο συμβολοσειρά.

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
| regex | java.util.regex.Pattern | Η κανονική έκφραση java.util.regex.Pattern για λήψη συμβολοσειρών προς αντικατάσταση. |
| newText | java.lang.String | Η συμβολοσειρά που θα αντικαταστήσει όλες τις εμφανίσεις των συμβολοσειρών που θα αντικατασταθούν. |
| callback | [IFindResultCallback](../../com.aspose.slides/ifindresultcallback) | Αντικείμενο callback για αποθήκευση αποτελέσματος λειτουργίας αντικατάστασης [IFindResultCallback](../../com.aspose.slides/ifindresultcallback). |

### getSlide() {#getSlide--}
```
public final IBaseSlide getSlide()
```

Επιστρέφει τη γονική διαφάνεια ενός TextFrame. Μόνο-ανάγνωση [IBaseSlide](../../com.aspose.slides/ibaseslide).

**Επιστρέφει:**
[IBaseSlide](../../com.aspose.slides/ibaseslide)
### getPresentation() {#getPresentation--}
```
public final IPresentation getPresentation()
```

Επιστρέφει την γονική παρουσίαση ενός TextFrame. Μόνο-ανάγνωση [IPresentation](../../com.aspose.slides/ipresentation).

**Επιστρέφει:**
[IPresentation](../../com.aspose.slides/ipresentation)
### getParentShape() {#getParentShape--}
```
public final IShape getParentShape()
```

Επιστρέφει το γονικό σχήμα ή null εάν το γονικό αντικείμενο δεν υλοποιεί τη διεπαφή IShape. Μόνο-ανάγνωση [IShape](../../com.aspose.slides/ishape).

--------------------

> ```
> The following code sample shows 
>  
>  Presentation presentation = new Presentation("SomePresentation.pptx");
>  try {
>      AutoShape autoShape = (AutoShape)presentation.getSlides().get_Item(0).getShapes().get_Item(0);
>      Table table = (Table)presentation.getSlides().get_Item(0).getShapes().get_Item(1);
> 
>      // Αυτές οι δηλώσεις είναι πάντα αληθινές
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

Επιστρέφει το γονικό κελί ή null εάν το γονικό αντικείμενο δεν υλοποιεί τη διεπαφή ICell. Μόνο-ανάγνωση [ICell](../../com.aspose.slides/icell).

--------------------

> ```
> The following code sample shows 
>  
>  Presentation presentation = new Presentation("SomePresentation.pptx");
>  try {
>      AutoShape autoShape = (AutoShape)presentation.getSlides().get_Item(0).getShapes().get_Item(0);
>      Table table = (Table)presentation.getSlides().get_Item(0).getShapes().get_Item(1);
> 
>      // Αυτές οι δηλώσεις είναι πάντα αληθινές
>      Assert.assertTrue(table.get_Item(0,0).getTextFrame().getParentCell() == table.get_Item(0,0));
>      Assert.assertTrue(autoShape.getTextFrame().getParentCell() == null);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```

**Επιστρέφει:**
[ICell](../../com.aspose.slides/icell)