---
title: ITextFrame
second_title: Aspose.Slides για Android μέσω Αναφοράς Java API
description: Αντιπροσωπεί ένα TextFrame.
type: docs
url: /el/com.aspose.slides/itextframe/
---
**Όλες οι Υλοποιημένες Διεπαφές:**
[com.aspose.slides.ISlideComponent](../../com.aspose.slides/islidecomponent)
```
public interface ITextFrame extends ISlideComponent
```

Αντιπροσωπεί ένα TextFrame.
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [getParagraphs()](#getParagraphs--) | Επιστρέφει τη λίστα όλων των παραγράφων σε ένα πλαίσιο. |
| [getText()](#getText--) | Λαμβάνει ή ορίζει το καθαρό κείμενο για ένα TextFrame. |
| [setText(String value)](#setText-java.lang.String-) | Λαμβάνει ή ορίζει το καθαρό κείμενο για ένα TextFrame. |
| [getTextFrameFormat()](#getTextFrameFormat--) | Επιστρέφει το αντικείμενο μορφοποίησης για αυτό το αντικείμενο TextFrame. |
| [getHyperlinkQueries()](#getHyperlinkQueries--) | Παρέχει εύκολη πρόσβαση στους ενσωματωμένους υπερσυνδέσμους. |
| [getParentShape()](#getParentShape--) | Επιστρέφει το γονικό σχήμα ή null εάν το γονικό αντικείμενο δεν υλοποιεί το διεπαφή IShape. Μόνο για ανάγνωση [IShape](../../com.aspose.slides/ishape). |
| [getParentCell()](#getParentCell--) | Επιστρέφει το γονικό κελί ή null εάν το γονικό αντικείμενο δεν υλοποιεί το διεπαφή ICell. |
| [joinPortionsWithSameFormatting()](#joinPortionsWithSameFormatting--) | Ενώζει τα τμήματα με την ίδια μορφοποίηση σε όλες τις παραγράφους. |
| [highlightText(String text, Integer highlightColor)](#highlightText-java.lang.String-java.lang.Integer-) | Τονίζει όλες τις αντιστοιχίες του κειμένου δείγματος με το καθορισμένο χρώμα. |
| [splitTextByColumns()](#splitTextByColumns--) | Διαιρεί το περιεχόμενο κειμένου του [ITextFrame](../../com.aspose.slides/itextframe) σε έναν πίνακα συμβολοσειρών, όπου κάθε στοιχείο αντιστοιχεί σε μια ξεχωριστή στήλη κειμένου εντός του πλαισίου. |
| [highlightText(String text, Integer highlightColor, ITextHighlightingOptions options)](#highlightText-java.lang.String-java.lang.Integer-com.aspose.slides.ITextHighlightingOptions-) | Τονίζει όλες τις αντιστοιχίες του κειμένου δείγματος με το καθορισμένο χρώμα. |
| [highlightText(String text, Integer highlightColor, ITextSearchOptions options, IFindResultCallback callback)](#highlightText-java.lang.String-java.lang.Integer-com.aspose.slides.ITextSearchOptions-com.aspose.slides.IFindResultCallback-) | Τονίζει όλες τις αντιστοιχίες του κειμένου δείγματος με το καθορισμένο χρώμα. |
| [highlightRegex(Pattern regex, Integer highlightColor, IFindResultCallback callback)](#highlightRegex-java.util.regex.Pattern-java.lang.Integer-com.aspose.slides.IFindResultCallback-) | Τονίζει όλες τις αντιστοιχίες της κανονικής έκφρασης με το καθορισμένο χρώμα. |
| [highlightRegex(String regex, Integer highlightColor, ITextHighlightingOptions options)](#highlightRegex-java.lang.String-java.lang.Integer-com.aspose.slides.ITextHighlightingOptions-) | Τονίζει όλες τις αντιστοιχίες της κανονικής έκφρασης με το καθορισμένο χρώμα. |
| [replaceText(String oldText, String newText, ITextSearchOptions options, IFindResultCallback callback)](#replaceText-java.lang.String-java.lang.String-com.aspose.slides.ITextSearchOptions-com.aspose.slides.IFindResultCallback-) | Αντικαθιστά όλες τις εμφανίσεις του καθορισμένου κειμένου με άλλο καθορισμένο κείμενο. |
| [replaceRegex(Pattern regex, String newText, IFindResultCallback callback)](#replaceRegex-java.util.regex.Pattern-java.lang.String-com.aspose.slides.IFindResultCallback-) | Αντικαθιστά όλες τις αντιστοιχίες της κανονικής έκφρασης με τη συγκεκριμένη συμβολοσειρά. |

### getParagraphs() {#getParagraphs--}
```
public abstract IParagraphCollection getParagraphs()
```

Επιστρέφει τη λίστα όλων των παραγράφων σε ένα πλαίσιο. Μόνο για ανάγνωση [IParagraphCollection](../../com.aspose.slides/iparagraphcollection).

**Επιστρέφει:**
[IParagraphCollection](../../com.aspose.slides/iparagraphcollection)

### getText() {#getText--}
```
public abstract String getText()
```

Λαμβάνει ή ορίζει το καθαρό κείμενο για ένα TextFrame. Ανάγνωση/Εγγραφή String.

Τιμή: Το κείμενο.

**Επιστρέφει:**
java.lang.String

### setText(String value) {#setText-java.lang.String-}
```
public abstract void setText(String value)
```

Λαμβάνει ή ορίζει το καθαρό κείμενο για ένα TextFrame. Ανάγνωση/Εγγραφή String.

Τιμή: Το κείμενο.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | java.lang.String |  |

### getTextFrameFormat() {#getTextFrameFormat--}
```
public abstract ITextFrameFormat getTextFrameFormat()
```

Επιστρέφει το αντικείμενο μορφοποίησης για αυτό το αντικείμενο TextFrame. Μόνο για ανάγνωση [ITextFrameFormat](../../com.aspose.slides/itextframeformat).

**Επιστρέφει:**
[ITextFrameFormat](../../com.aspose.slides/itextframeformat)

### getHyperlinkQueries() {#getHyperlinkQueries--}
```
public abstract IHyperlinkQueries getHyperlinkQueries()
```

Παρέχει εύκολη πρόσβαση στους ενσωματωμένους υπερσυνδέσμους. Μόνο για ανάγνωση [IHyperlinkQueries](../../com.aspose.slides/ihyperlinkqueries).

**Επιστρέφει:**
[IHyperlinkQueries](../../com.aspose.slides/ihyperlinkqueries)

### getParentShape() {#getParentShape--}
```
public abstract IShape getParentShape()
```

Επιστρέφει το γονικό σχήμα ή null εάν το γονικό αντικείμενο δεν υλοποιεί το διεπαφή IShape. Μόνο για ανάγνωση [IShape](../../com.aspose.slides/ishape).

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
public abstract ICell getParentCell()
```

Επιστρέφει το γονικό κελί ή null εάν το γονικό αντικείμενο δεν υλοποιεί το διεπαφή ICell. Μόνο για ανάγνωση [ICell](../../com.aspose.slides/icell).

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

### joinPortionsWithSameFormatting() {#joinPortionsWithSameFormatting--}
```
public abstract void joinPortionsWithSameFormatting()
```

Ενώζει τα τμήματα με την ίδια μορφοποίηση σε όλες τις παραγράφους.

### highlightText(String text, Integer highlightColor) {#highlightText-java.lang.String-java.lang.Integer-}
```
public abstract void highlightText(String text, Integer highlightColor)
```

Τονίζει όλες τις αντιστοιχίες του κειμένου δείγματος με το καθορισμένο χρώμα.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| text | java.lang.String | Το κείμενο προς επισήμανση. |
| highlightColor | java.lang.Integer | Το χρώμα για επισήμανση του κειμένου. |

### splitTextByColumns() {#splitTextByColumns--}
```
public abstract String[] splitTextByColumns()
```

Διαιρεί το περιεχόμενο κειμένου του [ITextFrame](../../com.aspose.slides/itextframe) σε έναν πίνακα συμβολοσειρών, όπου κάθε στοιχείο αντιστοιχεί σε μια ξεχωριστή στήλη κειμένου εντός του πλαισίου.

--------------------

> ```
> The following example demonstrates how to use #splitTextByColumns.splitTextByColumns:
>  
>  Presentation pres = new Presentation("example.pptx");
>  try {
>      // Λάβετε το πρώτο σχήμα στη διαφάνεια και μετατρέψτε το σε ITextFrame
>      ITextFrame textFrame = (ITextFrame) pres.getSlides().get_Item(0).getShapes().get_Item(0);
>      // Διαιρεί το περιεχόμενο του πλαισίου κειμένου σε στήλες
>      String[] columnsText = textFrame.splitTextByColumns();
>      // Εκτυπώνει το κείμενο κάθε στήλης στην κονσόλα
>      for (String column : columnsText)
>          System.out.println(column);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Επιστρέφει:**
java.lang.String[] - Ένας πίνακας συμβολοσειρών, όπου κάθε συμβολοσειρά αντιπροσωπεύει το περιεχόμενο κειμένου μιας συγκεκριμένης στήλης στο [ITextFrame](../../com.aspose.slides/itextframe).

Αν το πλαίσιο κειμένου δεν περιέχει πολλαπλές στήλες, ο επιστρεφόμενος πίνακας θα έχει ένα μοναδικό στοιχείο που περιέχει ολόκληρο το κείμενο. Κενές στήλες θα αντιπροσωπεύονται ως κενές συμβολοσειρές στον πίνακα.

### highlightText(String text, Integer highlightColor, ITextHighlightingOptions options) {#highlightText-java.lang.String-java.lang.Integer-com.aspose.slides.ITextHighlightingOptions-}
```
public abstract void highlightText(String text, Integer highlightColor, ITextHighlightingOptions options)
```

Τονίζει όλες τις αντιστοιχίες του κειμένου δείγματος με το καθορισμένο χρώμα.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| text | java.lang.String | Το κείμενο προς επισήμανση. |
| highlightColor | java.lang.Integer | Το χρώμα για επισήμανση του κειμένου. |
| options | [ITextHighlightingOptions](../../com.aspose.slides/itexthighlightingoptions) | Επιλογές επισήμανσης. |

### highlightText(String text, Integer highlightColor, ITextSearchOptions options, IFindResultCallback callback) {#highlightText-java.lang.String-java.lang.Integer-com.aspose.slides.ITextSearchOptions-com.aspose.slides.IFindResultCallback-}
```
public abstract void highlightText(String text, Integer highlightColor, ITextSearchOptions options, IFindResultCallback callback)
```

Τονίζει όλες τις αντιστοιχίες του κειμένου δείγματος με το καθορισμένο χρώμα.

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
| highlightColor | java.lang.Integer | Το χρώμα για επισήμανση του κειμένου. |
| options | [ITextSearchOptions](../../com.aspose.slides/itextsearchoptions) | Επιλογές αναζήτησης κειμένου [ITextSearchOptions](../../com.aspose.slides/itextsearchoptions). |
| callback | [IFindResultCallback](../../com.aspose.slides/ifindresultcallback) | Το αντικείμενο callback για λήψη αποτελεσμάτων αναζήτησης [IFindResultCallback](../../com.aspose.slides/ifindresultcallback). |

### highlightRegex(Pattern regex, Integer highlightColor, IFindResultCallback callback) {#highlightRegex-java.util.regex.Pattern-java.lang.Integer-com.aspose.slides.IFindResultCallback-}
```
public abstract void highlightRegex(Pattern regex, Integer highlightColor, IFindResultCallback callback)
```

Τονίζει όλες τις αντιστοιχίες της κανονικής έκφρασης με το καθορισμένο χρώμα.

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
| regex | java.util.regex.Pattern | Η κανονική έκφραση java.util.regex.Pattern για λήψη συμβολοσειρών προς επισήμανση. |
| highlightColor | java.lang.Integer | Το χρώμα για επισήμανση του κειμένου. |
| callback | [IFindResultCallback](../../com.aspose.slides/ifindresultcallback) | Το αντικείμενο callback για λήψη αποτελεσμάτων αναζήτησης [IFindResultCallback](../../com.aspose.slides/ifindresultcallback). |

### highlightRegex(String regex, Integer highlightColor, ITextHighlightingOptions options) {#highlightRegex-java.lang.String-java.lang.Integer-com.aspose.slides.ITextHighlightingOptions-}
```
public abstract void highlightRegex(String regex, Integer highlightColor, ITextHighlightingOptions options)
```

Τονίζει όλες τις αντιστοιχίες της κανονικής έκφρασης με το καθορισμένο χρώμα.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| regex | java.lang.String | Κείμενο της κανονικής έκφρασης για λήψη κειμένου προς επισήμανση. |
| highlightColor | java.lang.Integer | Το χρώμα για επισήμανση του κειμένου. |
| options | [ITextHighlightingOptions](../../com.aspose.slides/itexthighlightingoptions) | Επιλογές επισήμανσης. |

### replaceText(String oldText, String newText, ITextSearchOptions options, IFindResultCallback callback) {#replaceText-java.lang.String-java.lang.String-com.aspose.slides.ITextSearchOptions-com.aspose.slides.IFindResultCallback-}
```
public abstract void replaceText(String oldText, String newText, ITextSearchOptions options, IFindResultCallback callback)
```

Αντικαθιστά όλες τις εμφανίσεις του καθορισμένου κειμένου με άλλο καθορισμένο κείμενο.

--------------------

> ```
> The following sample code shows how to replace one specified string with another specified string.
>  
>  Presentation presentation = new Presentation("SomePresentation.pptx");
>  try {
>      TextSearchOptions textSearchOptions = new TextSearchOptions();
>      textSearchOptions.setWholeWordsOnly(true);
>      // Αντικαθιστά όλες τις ξεχωριστές εμφανίσεις του 'the' με '***'
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
| newText | java.lang.String | Η συμβολοσειρά για αντικατάσταση όλων των εμφανίσεων του oldText. |
| options | [ITextSearchOptions](../../com.aspose.slides/itextsearchoptions) | Επιλογές αναζήτησης κειμένου [ITextSearchOptions](../../com.aspose.slides/itextsearchoptions). |
| callback | [IFindResultCallback](../../com.aspose.slides/ifindresultcallback) | Το αντικείμενο callback για λήψη αποτελεσμάτων αναζήτησης [IFindResultCallback](../../com.aspose.slides/ifindresultcallback). |

### replaceRegex(Pattern regex, String newText, IFindResultCallback callback) {#replaceRegex-java.util.regex.Pattern-java.lang.String-com.aspose.slides.IFindResultCallback-}
```
public abstract void replaceRegex(Pattern regex, String newText, IFindResultCallback callback)
```

Αντικαθιστά όλες τις αντιστοιχίες της κανονικής έκφρασης με τη συγκεκριμένη συμβολοσειρά.

--------------------

> ```
> The following code sample shows how to replace text using regular expression with the specified string.
>  
>  Presentation presentation = new Presentation("SomePresentation.pptx");
>  try {
>      Pattern regex = Pattern.compile("\\b[^\\s]{5,}\\b");
>      // Αντικαθιστά όλες τις λέξεις με 5 ή περισσότερα σύμβολα με '***'
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
| newText | java.lang.String | Η συμβολοσειρά για αντικατάσταση όλων των εμφανίσεων των συμβολοσειρών που πρέπει να αντικατασταθούν. |
| callback | [IFindResultCallback](../../com.aspose.slides/ifindresultcallback) | Το αντικείμενο callback για λήψη αποτελεσμάτων αναζήτησης [IFindResultCallback](../../com.aspose.slides/ifindresultcallback). |