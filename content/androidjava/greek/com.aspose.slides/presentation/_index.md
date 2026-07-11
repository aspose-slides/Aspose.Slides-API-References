---
title: Presentation
second_title: Aspose.Slides για Android μέσω αναφοράς Java API
description: Αναπαριστά μια παρουσίαση Microsoft PowerPoint.
type: docs
url: /el/com.aspose.slides/presentation/
---
**Κληρονομία:**  
java.lang.Object

**Όλες οι Υλοποιημένες Διεπαφές:**  
[com.aspose.slides.IPresentation](../../com.aspose.slides/ipresentation), com.aspose.slides.IDOMObject  
```
public final class Presentation implements IPresentation, IDOMObject
```

Αναπαριστά μια παρουσίαση Microsoft PowerPoint.

--------------------

> ```
> The following example shows how to create PowerPoint Presentation.
>   
>  // Δημιουργεί ένα αντικείμενο Presentation που αντιπροσωπεύει ένα αρχείο παρουσίασης
>  Presentation pres = new Presentation();
>  try {
>      // Λαμβάνει την πρώτη διαφάνεια
>      ISlide slide = pres.getSlides().get_Item(0);
>      // Προσθέτει ένα αυτόματο σχήμα τύπου γραμμή
>      slide.getShapes().addAutoShape(ShapeType.Line, 50, 150, 300, 0);
>      // Αποθηκεύει το αρχείο παρουσίασης.
>      pres.save("NewPresentation_out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
>   
>   The following example shows how to open and save Presentation.
>   
>  // Φορτώνει οποιοδήποτε υποστηριζόμενο αρχείο στην Presentation π.χ. ppt, pptx, odp κλπ.
>  Presentation pres = new Presentation("Sample.odp");
>  try {
>      // Αποθηκεύει το αρχείο παρουσίασης.
>      pres.save("OutputPresenation.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

## Κατασκευαστές

| Κατασκευαστής | Περιγραφή |
| --- | --- |
| [Presentation()](#Presentation--) | Αυτός ο κατασκευαστής δημιουργεί νέα παρουσίαση από την αρχή. |
| [Presentation(LoadOptions loadOptions)](#Presentation-com.aspose.slides.LoadOptions-) | Αυτός ο κατασκευαστής δημιουργεί νέα παρουσίαση από την αρχή. |
| [Presentation(InputStream stream)](#Presentation-java.io.InputStream-) | Αυτός ο κατασκευαστής είναι ο κύριος μηχανισμός για την ανάγνωση μιας υπάρχουσας Presentation. |
| [Presentation(InputStream stream, LoadOptions loadOptions)](#Presentation-java.io.InputStream-com.aspose.slides.LoadOptions-) | Αυτός ο κατασκευαστής είναι ο κύριος μηχανισμός για την ανάγνωση μιας υπάρχουσας Presentation. |
| [Presentation(String file)](#Presentation-java.lang.String-) | Αυτός ο κατασκευαστής λαμβάνει τη διαδρομή αρχείου πηγής από την οποία διαβάζονται τα περιεχόμενα της Presentation. |
| [Presentation(String file, LoadOptions loadOptions)](#Presentation-java.lang.String-com.aspose.slides.LoadOptions-) | Αυτός ο κατασκευαστής λαμβάνει τη διαδρομή αρχείου πηγής από την οποία διαβάζονται τα περιεχόμενα της Presentation. |

## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [getCurrentDateTime()](#getCurrentDateTime--) | Επιστρέφει ή ορίζει την ημερομηνία και ώρα που θα αντικαταστήσει το περιεχόμενο των πεδίων datetime. |
| [setCurrentDateTime(Date value)](#setCurrentDateTime-java.util.Date-) | Επιστρέφει ή ορίζει την ημερομηνία και ώρα που θα αντικαταστήσει το περιεχόμενο των πεδίων datetime. |
| [getParent_Immediate()](#getParent-Immediate--) |  |
| [getHeaderFooterManager()](#getHeaderFooterManager--) | Επιστρέφει τον τρέχοντα διαχειριστή HeaderFooter. |
| [getProtectionManager()](#getProtectionManager--) | Λαμβάνει τον διαχειριστή των δικαιωμάτων για αυτή την παρουσίαση. |
| [getSlides()](#getSlides--) | Επιστρέφει μια λίστα με όλες τις διαφάνειες που ορίζονται στην παρουσίαση. |
| [getSections()](#getSections--) | Επιστρέφει μια λίστα με όλα τα τμήματα διαφανειών που ορίζονται στην παρουσίαση. |
| [getSlideSize()](#getSlideSize--) | Επιστρέφει το αντικείμενο μεγέθους διαφάνειας. |
| [getNotesSize()](#getNotesSize--) | Επιστρέφει το αντικείμενο μεγέθους διαφάνειας σημειώσεων. |
| [getLayoutSlides()](#getLayoutSlides--) | Επιστρέφει μια λίστα με όλες τις διαφάνειες διάταξης που ορίζονται στην παρουσίαση. |
| [getMasters()](#getMasters--) | Επιστρέφει μια λίδα με όλες τις κύριες διαφάνειες που ορίζονται στην παρουσίαση. |
| [getMasterNotesSlideManager()](#getMasterNotesSlideManager--) | Επιστρέφει τον διαχειριστή κύριων σημειώσεων. |
| [getMasterHandoutSlideManager()](#getMasterHandoutSlideManager--) | Επιστρέφει τον διαχειριστή κύριων φυλλαδίων. |
| [getFontsManager()](#getFontsManager--) | Επιστρέφει το διαχειριστή γραμματοσειρών. |
| [getDefaultTextStyle()](#getDefaultTextStyle--) | Επιστρέφει το προεπιλεγμένο στυλ κειμένου για σχήματα. |
| [getCommentAuthors()](#getCommentAuthors--) | Επιστρέφει τη συλλογή των συγγραφέων σχολίων. |
| [getDocumentProperties()](#getDocumentProperties--) | Επιστρέφει το αντικείμενο DocumentProperties που περιέχει τυπικές και προσαρμοσμένες ιδιότητες εγγράφου. |
| [getImages()](#getImages--) | Επιστρέφει τη συλλογή όλων των εικόνων στην παρουσίαση. |
| [getAudios()](#getAudios--) | Επιστρέφει τη συλλογή όλων των ενσωματωμένων αρχείων ήχου στην παρουσίαση. |
| [getVideos()](#getVideos--) | Επιστρέφει τη συλλογή όλων των ενσωματωμένων αρχείων βίντεο στην παρουσίαση. |
| [getSlideShowSettings()](#getSlideShowSettings--) | Επιστρέφει τις ρυθμίσεις προβολής διαφάνειας για την παρουσίαση. |
| [getDigitalSignatures()](#getDigitalSignatures--) | Επιστρέφει τη συλλογή των υπογραφών που χρησιμοποιήθηκαν για την υπογραφή της παρουσίασης. |
| [getCustomData()](#getCustomData--) | Επιστρέφει τα προσαρμοσμένα δεδομένα της παρουσίασης. |
| [getAllCustomXmlParts()](#getAllCustomXmlParts--) | Επιστρέφει όλα τα προσαρμοσμένα τμήματα δεδομένων στην παρουσίαση. |
| [getVbaProject()](#getVbaProject--) | Λαμβάνει ή ορίζει το έργο VBA με μακροεντολές παρουσίασης. |
| [setVbaProject(IVbaProject value)](#setVbaProject-com.aspose.slides.IVbaProject-) | Λαμβάνει ή ορίζει το έργο VBA με μακροεντολές παρουσίασης. |
| [getHyperlinkQueries()](#getHyperlinkQueries--) | Παρέχει εύκολη πρόσβαση σε όλους τους υπερσυνδέσμους που περιέχονται σε όλες τις διαφάνειες της παρουσίασης (όχι στις κύριες, διάταξης, σημειώσεων). |
| [getViewProperties()](#getViewProperties--) | Λαμβάνει τις ευρείες ιδιότητες προβολής της παρουσίασης. |
| [getFirstSlideNumber()](#getFirstSlideNumber--) | Αναπαριστά τον αριθμό της πρώτης διαφάνειας στην παρουσίαση. |
| [setFirstSlideNumber(int value)](#setFirstSlideNumber-int-) | Αναπαριστά τον αριθμό της πρώτης διαφάνειας στην παρουσίαση. |
| [getSensitivityLabels()](#getSensitivityLabels--) | Επιστρέφει τη συλλογή των ετικετών ευαισθησίας που εφαρμόζονται στο έγγραφο παρουσίασης. |
| [getSlideById(long id)](#getSlideById-long-) | Επιστρέφει μια Slide, MasterSlide ή LayoutSlide με βάση το Id. |
| [getSourceFormat()](#getSourceFormat--) | Επιστρέφει πληροφορίες σχετικά με τη μορφή από την οποία φορτώθηκε η παρουσίαση. |
| [getMasterTheme()](#getMasterTheme--) | Επιστρέφει το κύριο θέμα. |
| [save(String fname, int format)](#save-java.lang.String-int-) | Αποθηκεύει όλες τις διαφάνειες μιας παρουσίασης σε ένα αρχείο με την καθορισμένη μορφή. |
| [save(OutputStream stream, int format)](#save-java.io.OutputStream-int-) | Αποθηκεύει όλες τις διαφάνειες μιας παρουσίασης σε ροή με την καθορισμένη μορφή. |
| [save(String fname, int format, ISaveOptions options)](#save-java.lang.String-int-com.aspose.slides.ISaveOptions-) | Αποθηκεύει όλες τις διαφάνειες μιας παρουσίασης σε αρχείο με την καθορισμένη μορφή και με πρόσθετες επιλογές. |
| [save(OutputStream stream, int format, ISaveOptions options)](#save-java.io.OutputStream-int-com.aspose.slides.ISaveOptions-) | Αποθηκεύει όλες τις διαφάνειες μιας παρουσίασης σε ροή με την καθορισμένη μορφή και με πρόσθετες επιλογές. |
| [save(IXamlOptions options)](#save-com.aspose.slides.IXamlOptions-) | Αποθηκεύει όλες τις διαφάνειες μιας παρουσίασης σε σύνολο αρχείων που αντιπροσωπεύουν μορφοποίηση XAML. |
| [getImages(IRenderingOptions options)](#getImages-com.aspose.slides.IRenderingOptions-) | Επιστρέφει αντικείμενα Image για όλες τις διαφάνειες μιας παρουσίασης. |
| [getImages(IRenderingOptions options, int[] slides)](#getImages-com.aspose.slides.IRenderingOptions-int---) | Επιστρέφει αντικείμενα Thumbnail Image για τις καθορισμένες διαφάνειες της παρουσίασης. |
| [getImages(IRenderingOptions options, float scaleX, float scaleY)](#getImages-com.aspose.slides.IRenderingOptions-float-float-) | Επιστρέφει αντικείμενα Thumbnail Image για όλες τις διαφάνειες της παρουσίασης με προσαρμοσμένη κλιμάκωση. |
| [getImages(IRenderingOptions options, int[] slides, float scaleX, float scaleY)](#getImages-com.aspose.slides.IRenderingOptions-int---float-float-) | Επιστρέφει αντικείμενα Thumbnail Image για τις καθορισμένες διαφάνειες της παρουσίασης με προσαρμοσμένη κλιμάκωση. |
| [getImages(IRenderingOptions options, Size imageSize)](#getImages-com.aspose.slides.IRenderingOptions-com.aspose.slides.android.Size-) | Επιστρέφει αντικείμενα Thumbnail Image για όλες τις διαφάνειες της παρουσίασης με καθορισμένο μέγεθος. |
| [getImages(IRenderingOptions options, int[] slides, Size imageSize)](#getImages-com.aspose.slides.IRenderingOptions-int---com.aspose.slides.android.Size-) | Επιστρέφει αντικείμενα Thumbnail Image για τις καθορισμένες διαφάνειες της παρουσίασης με καθορισμένο μέγεθος. |
| [save(String fname, int[] slides, int format)](#save-java.lang.String-int---int-) | Αποθηκεύει τις καθορισμένες διαφάνειες μιας παρουσίασης σε αρχείο με την καθορισμένη μορφή και διατηρώντας τον αριθμό σελίδας. |
| [save(String fname, int[] slides, int format, ISaveOptions options)](#save-java.lang.String-int---int-com.aspose.slides.ISaveOptions-) | Αποθηκεύει τις καθορισμένες διαφάνειες μιας παρουσίασης σε αρχείο με την καθορισμένη μορφή και διατηρώντας τον αριθμό σελίδας. |
| [save(OutputStream stream, int[] slides, int format)](#save-java.io.OutputStream-int---int-) | Αποθηκεύει τις καθορισμένες διαφάνειες μιας παρουσίασης σε ροή με την καθορισμένη μορφή και διατηρώντας τον αριθμό σελίδας. |
| [save(OutputStream stream, int[] slides, int format, ISaveOptions options)](#save-java.io.OutputStream-int---int-com.aspose.slides.ISaveOptions-) | Αποθηκεύει τις καθορισμένες διαφάνειες μιας παρουσίασης σε ροή με την καθορισμένη μορφή και διατηρώντας τον αριθμό σελίδας. |
| [joinPortionsWithSameFormatting()](#joinPortionsWithSameFormatting--) | Ενώνει τμήματα κειμένου με την ίδια μορφοποίηση σε όλες τις παραγράφους σε όλα τα αποδεκτά σχήματα σε όλες τις διαφάνειες. |
| [dispose()](#dispose--) | Αποδεσμεύει όλους τους πόρους που χρησιμοποιεί αυτό το αντικείμενο Presentation. |
| [getPresentation()](#getPresentation--) | Επιστρέφει την γονική παρουσίαση ενός κειμένου. |
| [highlightText(String text, Integer highlightColor)](#highlightText-java.lang.String-java.lang.Integer-) | Επισημαίνει όλες τις αντιστοιχίες του δείγματος κειμένου με το καθορισμένο χρώμα. |
| [highlightText(String text, Integer highlightColor, ITextSearchOptions options, IFindResultCallback callback)](#highlightText-java.lang.String-java.lang.Integer-com.aspose.slides.ITextSearchOptions-com.aspose.slides.IFindResultCallback-) | Επισημαίνει όλες τις αντιστοιχίες του δείγματος κειμένου με το καθορισμένο χρώμα. |
| [highlightRegex(Pattern regex, Integer highlightColor, IFindResultCallback callback)](#highlightRegex-java.util.regex.Pattern-java.lang.Integer-com.aspose.slides.IFindResultCallback-) | Επισημαίνει όλες τις αντιστοιχίες της κανονικής έκφρασης με το καθορισμένο χρώμα. |
| [replaceText(String oldText, String newText, ITextSearchOptions options, IFindResultCallback callback)](#replaceText-java.lang.String-java.lang.String-com.aspose.slides.ITextSearchOptions-com.aspose.slides.IFindResultCallback-) | Αντικαθιστά όλες τις εμφανίσεις του καθορισμένου κειμένου με άλλο καθορισμένο κείμενο. |
| [replaceRegex(Pattern regex, String newText, IFindResultCallback callback)](#replaceRegex-java.util.regex.Pattern-java.lang.String-com.aspose.slides.IFindResultCallback-) | Αντικαθιστά όλες τις αντιστοιχίες της κανονικής έκφρασης με το καθορισμένο string. |

### Presentation() {#Presentation--}
```
public Presentation()
```

Αυτός ο κατασκευαστής δημιουργεί νέα παρουσίαση από την αρχή. Η δημιουργημένη παρουσίαση έχει μία κενή διαφάνεια.

### Presentation(LoadOptions loadOptions) {#Presentation-com.aspose.slides.LoadOptions-}
```
public Presentation(LoadOptions loadOptions)
```

Αυτός ο κατασκευαστής δημιουργεί νέα παρουσίαση από την αρχή. Η δημιουργημένη παρουσίαση έχει μία κενή διαφάνεια.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| loadOptions | [LoadOptions](../../com.aspose.slides/loadoptions) | Πρόσθετες επιλογές φόρτωσης. |

### Presentation(InputStream stream) {#Presentation-java.io.InputStream-}
```
public Presentation(InputStream stream)
```

Αυτός ο κατασκευαστής είναι ο κύριος μηχανισμός για την ανάγνωση μιας υπάρχουσας Presentation.

--------------------

> ```
> FileInputStream fis = new FileInputStream("demo.pptx");
>  Presentation pres = new Presentation(fis);
>  fis.close();
> ```


**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| stream | java.io.InputStream | Ροή εισόδου. |

### Presentation(InputStream stream, LoadOptions loadOptions) {#Presentation-java.io.InputStream-com.aspose.slides.LoadOptions-}
```
public Presentation(InputStream stream, LoadOptions loadOptions)
```

Αυτός ο κατασκευαστής είναι ο κύριος μηχανισμός για την ανάγνωση μιας υπάρχουσας Presentation.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| stream | java.io.InputStream | Ροή εισόδου. |
| loadOptions | [LoadOptions](../../com.aspose.slides/loadoptions) | Πρόσθετες επιλογές φόρτωσης. |

### Presentation(String file) {#Presentation-java.lang.String-}
```
public Presentation(String file)
```

Αυτός ο κατασκευαστής λαμβάνει τη διαδρομή αρχείου πηγής από την οποία διαβάζονται τα περιεχόμενα της Presentation.

--------------------

> ```
> Presentation pres = new Presentation("demo.pptx");
> ```


**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| file | java.lang.String | Αρχείο εισόδου. |

### Presentation(String file, LoadOptions loadOptions) {#Presentation-java.lang.String-com.aspose.slides.LoadOptions-}
```
public Presentation(String file, LoadOptions loadOptions)
```

Αυτός ο κατασκευαστής λαμβάνει τη διαδρομή αρχείου πηγής από την οποία διαβάζονται τα περιεχόμενα της Presentation.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| file | java.lang.String | Αρχείο εισόδου. |
| loadOptions | [LoadOptions](../../com.aspose.slides/loadoptions) | Πρόσθετες επιλογές φόρτωσης. |

### getCurrentDateTime() {#getCurrentDateTime--}
```
public final Date getCurrentDateTime()
```

Επιστρέφει ή ορίζει την ημερομηνία και ώρα που θα αντικαταστήσει το περιεχόμενο των πεδίων datetime. Η ώρα δημιουργίας αυτού του αντικειμένου Presentation είναι η προεπιλογή. Read/write java.util.Date.

**Επιστρέφει:**
java.util.Date

### setCurrentDateTime(Date value) {#setCurrentDateTime-java.util.Date-}
```
public final void setCurrentDateTime(Date value)
```

Επιστρέφει ή ορίζει την ημερομηνία και ώρα που θα αντικαταστήσει το περιεχόμενο των πεδίων datetime. Η ώρα δημιουργίας αυτού του αντικειμένου Presentation είναι η προεπιλογή. Read/write java.util.Date.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | java.util.Date |  |

### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```

Επιστρέφει το αντικείμενο Parent_Immediate. Read-only IDOMObject.

**Επιστρέφει:**
com.aspose.slides.IDOMObject

### getHeaderFooterManager() {#getHeaderFooterManager--}
```
public final IPresentationHeaderFooterManager getHeaderFooterManager()
```

Επιστρέφει τον τρέχοντα διαχειριστή HeaderFooter. Read-only [IPresentationHeaderFooterManager](../../com.aspose.slides/ipresentationheaderfootermanager).

--------------------

> ```
> The following example shows how to set footer visibility inside Slide of PowerPoint Presentation.
>  
>  Presentation pres = new Presentation("presentation.ppt");
>  try
>  {
>      IBaseSlideHeaderFooterManager headerFooterManager = pres.getSlides().get_Item(0).getHeaderFooterManager();
>      if (!headerFooterManager.isFooterVisible()) // Η ιδιότητα IsFooterVisible χρησιμοποιείται για την ένδειξη ότι δεν υπάρχει υποδοχέα υποσέλιδου διαφάνειας.
>      {
>          headerFooterManager.setFooterVisibility(true); // Η μέθοδος SetFooterVisibility χρησιμοποιείται για την ενεργοποίηση του υποδοχέα υποσέλιδου διαφάνειας.
>      }
>      if (!headerFooterManager.isSlideNumberVisible()) // Η ιδιότητα IsSlideNumberVisible χρησιμοποιείται για την ένδειξη ότι δεν υπάρχει υποδοχέα αριθμού σελίδας διαφάνειας.
>      {
>          headerFooterManager.setSlideNumberVisibility(true); // Η μέθοδος SetSlideNumberVisibility χρησιμοποιείται για την ενεργοποίηση του υποδοχέα αριθμού σελίδας διαφάνειας.
>      }
>      if (!headerFooterManager.isDateTimeVisible()) // Η ιδιότητα IsDateTimeVisible χρησιμοποιείται για την ένδειξη ότι δεν υπάρχει υποδοχέα ημερομηνίας-ώρας διαφάνειας.
>      {
>          headerFooterManager.setDateTimeVisibility(true); // Η μέθοδος SetFooterVisibility χρησιμοποιείται για την ενεργοποίηση του υποδοχέα ημερομηνίας-ώρας διαφάνειας.
>      }
>      headerFooterManager.setFooterText("Footer text"); // Η μέθοδος SetFooterText χρησιμοποιείται για τον ορισμό κειμένου στο υποδοχέα υποσέλιδου διαφάνειας.
>      headerFooterManager.setDateTimeText("Date and time text"); // Η μέθοδος SetDateTimeText χρησιμοποιείται για τον ορισμό κειμένου στο υποδοχέα ημερομηνίας-ώρας διαφάνειας.
>      pres.save("Presentation.ppt", SaveFormat.Ppt);
>  }
>  finally
>  {
>      if (pres != null) pres.dispose();
>  }
>  
>  The following example shows how to set child footer visibility inside Slide.
>  
>  Presentation pres = new Presentation("presentation.ppt");
>  try
>  {
>      IMasterSlideHeaderFooterManager headerFooterManager = pres.getMasters().get_Item(0).getHeaderFooterManager();
>      headerFooterManager.setFooterAndChildFootersVisibility(true); // Η μέθοδος SetFooterAndChildFootersVisibility χρησιμοποιείται για την ενεργοποίηση του κύριου διαφάνειας και όλων των υποδοχέων υποσέλιδου.
>      headerFooterManager.setSlideNumberAndChildSlideNumbersVisibility(true); // Η μέθοδος SetSlideNumberAndChildSlideNumbersVisibility χρησιμοποιείται για την ενεργοποίηση του κύριου διαφάνειας και όλων των υποδοχέων αριθμού σελίδας.
>      headerFooterManager.setDateTimeAndChildDateTimesVisibility(true); // Η μέθοδος SetDateTimeAndChildDateTimesVisibility χρησιμοποιείται για την ενεργοποίηση του κύριου διαφάνειας και όλων των υποδοχέων ημερομηνίας-ώρας.
> 
>      headerFooterManager.setFooterAndChildFootersText("Footer text"); // Η μέθοδος SetFooterAndChildFootersText χρησιμοποιείται για τον ορισμό κειμένου στο κύριο διαφάνειας και όλους τους υποδοχείς υποσέλιδου.
>      headerFooterManager.setDateTimeAndChildDateTimesText("Date and time text"); // Η μέθοδος SetDateTimeAndChildDateTimesText χρησιμοποιείται για τον ορισμό κειμένου στο κύριο διαφάνειας και όλους τους υποδοχείς ημερομηνίας-ώρας.
>  }
>  finally
>  {
>      if (pres != null) pres.dispose();
>  }
> ```


**Επιστρέφει:**
[IPresentationHeaderFooterManager](../../com.aspose.slides/ipresentationheaderfootermanager)

### getProtectionManager() {#getProtectionManager--}
```
public final IProtectionManager getProtectionManager()
```

Λαμβάνει τον διαχειριστή των δικαιωμάτων για αυτή την παρουσίαση. Read-only [IProtectionManager](../../com.aspose.slides/iprotectionmanager).

**Επιστρέφει:**
[IProtectionManager](../../com.aspose.slides/iprotectionmanager)

### getSlides() {#getSlides--}
```
public final ISlideCollection getSlides()
```

Επιστρέφει μια λίστα με όλες τις διαφάνειες που ορίζονται στην παρουσίαση. Read-only [ISlideCollection](../../com.aspose.slides/islidecollection).

--------------------

> ```
> The following example shows how to set slides' background color of PowerPoint Presentation.
>  
>   // Δημιουργεί το αντικείμενο Presentation που αντιπροσωπεύει το αρχείο παρουσίασης
>   Presentation pres = new Presentation();
>   try
>   {
>       // Ορίζει το χρώμα φόντου της πρώτης ISlide σε Μπλε
>       pres.getSlides().get_Item(0).getBackground().setType(BackgroundType.OwnBackground);
>       pres.getSlides().get_Item(0).getBackground().getFillFormat().setFillType(FillType.Solid);
>       pres.getSlides().get_Item(0).getBackground().getFillFormat().getSolidFillColor().setColor(Color.BLUE);
>       pres.save("ContentBG_out.pptx", SaveFormat.Pptx);
>   }
>   finally
>   {
>       if (pres != null) pres.dispose();
>   }
>   
>   The following example shows how to set slides' background image of PowerPoint Presentation.
>   
>   // Δημιουργεί το αντικείμενο Presentation που αντιπροσωπεύει το αρχείο παρουσίασης
>   Presentation pres = new Presentation("SetImageAsBackground.pptx");
>   try {
>       // Ορίζει το φόντο με εικόνα
>       pres.getSlides().get_Item(0).getBackground().setType(BackgroundType.OwnBackground);
>       pres.getSlides().get_Item(0).getBackground().getFillFormat().setFillType(FillType.Picture);
>       pres.getSlides().get_Item(0).getBackground().getFillFormat().getPictureFillFormat().setPictureFillMode(PictureFillMode.Stretch);
>       // Προσθέτει εικόνα στη συλλογή εικόνων της παρουσίασης
>       FileInputStream fos = null;
>       try {
>           fos = new FileInputStream("Tulips.jpg");
>           IPPImage imgx = pres.getImages().addImage(fos);
>           pres.getSlides().get_Item(0).getBackground().getFillFormat().getPictureFillFormat().getPicture().setImage(imgx);
>       } finally {
>           if (fos != null) fos.close();
>       }
>       // Αποθηκεύει την παρουσίαση στον δίσκο
>       pres.save("ContentBG_Img_out.pptx", SaveFormat.Pptx);
>   } catch (IOException e) { }
>   finally
>   {
>       if (pres != null) pres.dispose();
>   }
>   
>   The following example shows how to add slide transition Presentation.
>   
>   // Δημιουργεί το αντικείμενο Presentation για να φορτώσει το πηγαίο αρχείο παρουσίασης
>   Presentation pres = new Presentation("AccessSlides.pptx");
>   try
>   {
>       // Εφαρμόζει μετάβαση τύπου κύκλου στη διαφάνεια 1
>       pres.getSlides().get_Item(0).getSlideShowTransition().setType(TransitionType.Circle);
>       // Εφαρμόζει μετάβαση τύπου comb στη διαφάνεια 2
>       pres.getSlides().get_Item(1).getSlideShowTransition().setType(TransitionType.Comb);
>       // Αποθηκεύει την παρουσίαση στον δίσκο
>       pres.save("SampleTransition_out.pptx", SaveFormat.Pptx);
>   }
>   finally
>   {
>       if (pres != null) pres.dispose();
>   }
>   
>   The following example shows how to add advanced slide Transition.
>   
>   // Δημιουργεί το αντικείμενο Presentation που αντιπροσωπεύει ένα αρχείο παρουσίασης
>   Presentation pres = new Presentation("BetterSlideTransitions.pptx");
>   try
>   {
>       // Εφαρμόζει μετάβαση τύπου κύκλου στη διαφάνεια 1
>       pres.getSlides().get_Item(0).getSlideShowTransition().setType(TransitionType.Circle);
>       // Ορίζει χρόνο μετάβασης 3 δευτερόλεπτα
>       pres.getSlides().get_Item(0).getSlideShowTransition().setAdvanceOnClick(true);
>       pres.getSlides().get_Item(0).getSlideShowTransition().setAdvanceAfterTime(3000);
>       // Εφαρμόζει μετάβαση τύπου comb στη διαφάνεια 2
>       pres.getSlides().get_Item(1).getSlideShowTransition().setType(TransitionType.Comb);
>       // Ορίζει χρόνο μετάβασης 5 δευτερόλεπτα
>       pres.getSlides().get_Item(1).getSlideShowTransition().setAdvanceOnClick(true);
>       pres.getSlides().get_Item(1).getSlideShowTransition().setAdvanceAfterTime(5000);
>       // Εφαρμόζει μετάβαση τύπου ζουμ στη διαφάνεια 3
>       pres.getSlides().get_Item(2).getSlideShowTransition().setType(TransitionType.Zoom);
>       // Ορίζει χρόνο μετάβασης 7 δευτερόλεπτα
>       pres.getSlides().get_Item(2).getSlideShowTransition().setAdvanceOnClick(true);
>       pres.getSlides().get_Item(2).getSlideShowTransition().setAdvanceAfterTime(7000);
>       // Αποθηκεύει την παρουσίαση στον δίσκο
>       pres.save("SampleTransition_out.pptx", SaveFormat.Pptx);
>   }
>   finally
>   {
>       if (pres != null) pres.dispose();
>   }
> ```


**Επιστρέφει:**
[ISlideCollection](../../com.aspose.slides/islidecollection)

### getSections() {#getSections--}
```
public final ISectionCollection getSections()
```

Επιστρέφει μια λίστα με όλα τα τμήματα διαφανειών που ορίζονται στην παρουσίαση. Read-only [ISectionCollection](../../com.aspose.slides/isectioncollection).

--------------------

> ```
> The following examples shows how to create Sections in a PowerPoint Presentation.
>  
>  Presentation pres = new Presentation();
>  try {
>      ISlide defaultSlide = pres.getSlides().get_Item(0);
>      ISlide newSlide1 = pres.getSlides().addEmptySlide(pres.getLayoutSlides().get_Item(0));
>      ISlide newSlide2 = pres.getSlides().addEmptySlide(pres.getLayoutSlides().get_Item(0));
>      ISlide newSlide3 = pres.getSlides().addEmptySlide(pres.getLayoutSlides().get_Item(0));
>      ISlide newSlide4 = pres.getSlides().addEmptySlide(pres.getLayoutSlides().get_Item(0));
>      ISection section1 = pres.getSections().addSection("Section 1", newSlide1);
>      // section1 θα λήξει στο newSlide2 και μετά από αυτό θα ξεκινήσει το section2
>      ISection section2 = pres.getSections().addSection("Section 2", newSlide3);
>      pres.save("pres-sections.pptx", SaveFormat.Pptx);
>      pres.getSections().reorderSectionWithSlides(section2, 0);
>      pres.save("pres-sections-moved.pptx", SaveFormat.Pptx);
>      pres.getSections().removeSectionWithSlides(section2);
>      pres.getSections().appendEmptySection("Last empty section");
>      pres.save("pres-section-with-empty.pptx",SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
>  
>  The following examples shows how to changing the names of Sections.
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      ISection section = pres.getSections().get_Item(0);
>      section.setName("My section");
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Επιστρέφει:**
[ISectionCollection](../../com.aspose.slides/isectioncollection)

### getSlideSize() {#getSlideSize--}
```
public final ISlideSize getSlideSize()
```

Επιστρέφει το αντικείμενο μεγέθους διαφάνειας. Read-only [ISlideSize](../../com.aspose.slides/islidesize).

--------------------

> ```
> The following example shows how to change the slide size in a PowerPoint Presentation.
>  
>  Presentation pres = new Presentation("pres-4x3-aspect-ratio.pptx");
>  try {
>      pres.getSlideSize().setSize(SlideSizeType.OnScreen16x9, SlideSizeScaleType.DoNotScale);
>      pres.save("pres-4x3-aspect-ratio.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
>  
>  The following example shows how to set slide size with respect to content scaling for a PowerPoint Presentation.
>  
>  // Δημιουργεί ένα αντικείμενο Presentation που αντιπροσωπεύει ένα αρχείο παρουσίασης
>  Presentation presentation = new Presentation("AccessSlides.pptx");
>  try {
>      Presentation auxPresentation = new Presentation();
>      try {
>          ISlide slide = presentation.getSlides().get_Item(0);
>          // Ορίζει το μέγεθος διαφάνειας των παραγόμενων παρουσιάσεων στο μέγεθος της πηγής
>          presentation.getSlideSize().setSize(540, 720, SlideSizeScaleType.EnsureFit); // Η μέθοδος SetSize χρησιμοποιείται για τον ορισμό του μεγέθους διαφάνειας με κλιμάκωση του περιεχομένου ώστε να εξασφαλιστεί η προσαρμογή
>          presentation.getSlideSize().setSize(SlideSizeType.A4Paper, SlideSizeScaleType.Maximize); // Η μέθοδος SetSize χρησιμοποιείται για τον ορισμό του μεγέθους διαφάνειας με μεγιστοποίηση του περιεχομένου
>          // Αποθηκεύει την παρουσίαση στον δίσκο
>          auxPresentation.save("Set_Size&Type_out.pptx", SaveFormat.Pptx);
>      } finally {
>          if (auxPresentation != null) auxPresentation.dispose();
>      }
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
>  
>  The following example shows how to specifying custom slide sizes in a PowerPoint Presentation.
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      pres.getSlideSize().setSize(780, 540, SlideSizeScaleType.DoNotScale); // Μέγεθος χαρτιού A4
>      pres.save("pres-a4-slide-size.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Επιστρέφει:**
[ISlideSize](../../com.aspose.slides/islidesize)

### getNotesSize() {#getNotesSize--}
```
public final INotesSize getNotesSize()
```

Επιστρέφει το αντικείμενο μεγέθους διαφάνειας σημειώσεων. Read-only [INotesSize](../../com.aspose.slides/inotessize).

**Επιστρέφει:**
[INotesSize](../../com.aspose.slides/inotessize)

### getLayoutSlides() {#getLayoutSlides--}
```
public final IGlobalLayoutSlideCollection getLayoutSlides()
```

Επιστρέφει μια λίστα με όλες τις διαφάνειες διάταξης που ορίζονται στην παρουσίαση. Read-only [IGlobalLayoutSlideCollection](../../com.aspose.slides/igloballayoutslidecollection).

--------------------

Μπορείτε να έχετε πρόσβαση σε εναλλακτικό API για προσθήκη/εισαγωγή/αφαίρεση/κλωνοποίηση διαφανειών διάταξης χρησιμοποιώντας την ιδιότητα IMasterSlide.LayoutSlides.

**Επιστρέφει:**
[IGlobalLayoutSlideCollection](../../com.aspose.slides/igloballayoutslidecollection)

### getMasters() {#getMasters--}
```
public final IMasterSlideCollection getMasters()
```

Επιστρέφει μια λίστα με όλες τις κύριες διαφάνειες που ορίζονται στην παρουσίαση. Read-only [IMasterSlideCollection](../../com.aspose.slides/imasterslidecollection).

--------------------

> ```
> The following examples shows how to adding Images to Master Slides of PowerPoint Presentation.
>  
>  Presentation pres = new Presentation();
>  try {
>      ISlide slide = pres.getSlides().get_Item(0);
>      IMasterSlide masterSlide = slide.getLayoutSlide().getMasterSlide();
>      FileInputStream fos = null;
>      try {
>          fos = new FileInputStream("image.png");
>          IPPImage image = pres.getImages().addImage(fos);
>          masterSlide.getShapes().addPictureFrame(ShapeType.Rectangle, 10, 10, 100, 100, image);
>      } finally {
>          if (fos != null) fos.close();
>      }
>      pres.save("pres.pptx", SaveFormat.Pptx);
>  } catch(IOException e) {
>  } finally {
>      if (pres != null) pres.dispose();
>  }
>  
>  The following examples shows how to change the background color of the master slide of PowerPoint Presentation.
>  
>  // Δημιουργεί το αντικείμενο Presentation που αντιπροσωπεύει το αρχείο παρουσίασης
>  Presentation pres = new Presentation();
>  try
>  {
>      // Ορίζει το χρώμα φόντου της κύριας ISlide σε Πράσινο δάσους
>      pres.getMasters().get_Item(0).getBackground().setType(BackgroundType.OwnBackground);
>      pres.getMasters().get_Item(0).getBackground().getFillFormat().setFillType(FillType.Solid);
>      pres.getMasters().get_Item(0).getBackground().getFillFormat().getSolidFillColor().setColor(Color.GREEN);
>      // Αποθηκεύει την παρουσίαση στον δίσκο
>      pres.save("SetSlideBackgroundMaster_out.pptx", SaveFormat.Pptx);
>  }
>  finally
>  {
>      if (pres != null) pres.dispose();
>  }
>  
>  The following examples shows how to add slide layout to PowerPoint Presentation.
>  
>  // Δημιουργεί το αντικείμενο Presentation που αντιπροσωπεύει το αρχείο παρουσίασης
>  Presentation presentation = new Presentation("AccessSlides.pptx");
>  try
>  {
>      // Προσπάθεια αναζήτησης κατά τύπο διάταξης διαφάνειας
>      IMasterLayoutSlideCollection layoutSlides = presentation.getMasters().get_Item(0).getLayoutSlides();
>      ILayoutSlide layoutSlide = null;
>      if (layoutSlides.getByType(SlideLayoutType.TitleAndObject) != null)
>          layoutSlide = layoutSlides.getByType(SlideLayoutType.TitleAndObject);
>      else
>          layoutSlide = layoutSlides.getByType(SlideLayoutType.Title);
> 
>      if (layoutSlide == null)
>      {
>          // Η περίπτωση όταν μια παρουσίαση δεν περιέχει κάποιον τύπο διατάξεων.
>          // Το αρχείο παρουσίασης περιέχει μόνο τύπους διατάξεων Blank και Custom.
>          // Αλλά οι διαφάνειες διάταξης με τύπους Custom έχουν διαφορετικά ονόματα διαφανειών,
>          // όπως "Title", "Title and Content", κλπ. Και είναι δυνατό να χρησιμοποιηθούν αυτά
>          // ονόματα για επιλογή διάταξης διαφάνειας.
>          // Επίσης είναι δυνατό να χρησιμοποιηθεί το σύνολο τύπων placeholder σχήματος. Για παράδειγμα,
>          // Η διαφάνεια Title πρέπει να έχει μόνο τύπο placeholder Title, κλπ.
>          for (ILayoutSlide titleAndObjectLayoutSlide : (Iterable) layoutSlides)
>          {
>              if ("Title and Object".equals(titleAndObjectLayoutSlide.getName()))
>              {
>                  layoutSlide = titleAndObjectLayoutSlide;
>                  break;
>              }
>          }
>          if (layoutSlide == null)
>          {
>              for (ILayoutSlide titleLayoutSlide : (Iterable) layoutSlides)
>              {
>                  if ("Title".equals(titleLayoutSlide.getName()))
>                  {
>                      layoutSlide = titleLayoutSlide;
>                      break;
>                  }
>              }
>              if (layoutSlide == null)
>              {
>                  layoutSlide = layoutSlides.getByType(SlideLayoutType.Blank);
>                  if (layoutSlide == null)
>                  {
>                      layoutSlide = layoutSlides.add(SlideLayoutType.TitleAndObject, "Title and Object");
>                  }
>              }
>          }
>      }
>      // Προσθήκη κενής διαφάνειας με την προστιθέμενη διάταξη διαφάνειας
>      presentation.getSlides().insertEmptySlide(0, layoutSlide);
>      // Αποθήκευση παρουσίασης
>      presentation.save("AddLayoutSlides_out.pptx", SaveFormat.Pptx);
>  }
>  finally
>  {
>      if (presentation != null) presentation.dispose();
>  }
> ```


**Επιστρέφει:**
[IMasterSlideCollection](../../com.aspose.slides/imasterslidecollection)

### getMasterNotesSlideManager() {#getMasterNotesSlideManager--}
```
public final IMasterNotesSlideManager getMasterNotesSlideManager()
```

Επιστρέφει τον διαχειριστή κύριων σημειώσεων. Read-only [IMasterNotesSlideManager](../../com.aspose.slides/imasternotesslidemanager).

**Επιστρέφει:**
[IMasterNotesSlideManager](../../com.aspose.slides/imasternotesslidemanager)

### getMasterHandoutSlideManager() {#getMasterHandoutSlideManager--}
```
public final IMasterHandoutSlideManager getMasterHandoutSlideManager()
```

Επιστρέφει τον διαχειριστή κύριων φυλλαδίων. Read-only [IMasterHandoutSlideManager](../../com.aspose.slides/imasterhandoutslidemanager).

**Επιστρέφει:**
[IMasterHandoutSlideManager](../../com.aspose.slides/imasterhandoutslidemanager)

### getFontsManager() {#getFontsManager--}
```
public final IFontsManager getFontsManager()
```

Επιστρέφει το διαχειριστή γραμματοσειρών. Read-only [IFontsManager](../../com.aspose.slides/ifontsmanager).

--------------------

> ```
> The following example shows how to add embedded fonts to PowerPoint Presentation.
>  
>  // Φορτώνει την παρουσίαση
>  Presentation pres = new Presentation("Fonts.pptx");
>  try {
>      // Φορτώνει τη γραμματοσειρά πηγής που θα αντικατασταθεί
>      IFontData sourceFont = new FontData("Arial");
>      IFontData[] allFonts = pres.getFontsManager().getFonts();
>      for (IFontData font : allFonts)
>      {
>          boolean fontAlreadyEmbedded = false;
>          IFontData[] embeddedFonts = pres.getFontsManager().getEmbeddedFonts();
>          for (int i = 0; i < embeddedFonts.length; i++)
>          {
>              if (embeddedFonts[i].equals(font))
>              {
>                  fontAlreadyEmbedded = true;
>                  break;
>              }
>          }
>          if (!fontAlreadyEmbedded) {
>              pres.getFontsManager().addEmbeddedFont(font, EmbedFontCharacters.All);
>          }
>      }
>      // Αποθηκεύει την παρουσίαση
>      pres.save("AddEmbeddedFont_out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Επιστρέφει:**
[IFontsManager](../../com.aspose.slides/ifontsmanager)

### getDefaultTextStyle() {#getDefaultTextStyle--}
```
public final ITextStyle getDefaultTextStyle()
```

Επιστρέφει το προεπιλεγμένο στυλ κειμένου για σχήματα. Read-only [ITextStyle](../../com.aspose.slides/itextstyle).

**Επιστρέφει:**
[ITextStyle](../../com.aspose.slides/itextstyle)

### getCommentAuthors() {#getCommentAuthors--}
```
public final ICommentAuthorCollection getCommentAuthors()
```

Επιστρέφει τη συλλογή των συγγραφέων σχολίων. Read-only [ICommentAuthorCollection](../../com.aspose.slides/icommentauthorcollection).

**Επιστρέφει:**
[ICommentAuthorCollection](../../com.aspose.slides/icommentauthorcollection)

### getDocumentProperties() {#getDocumentProperties--}
```
public final IDocumentProperties getDocumentProperties()
```

Επιστρέφει το αντικείμενο DocumentProperties που περιέχει τυπικές και προσαρμοσμένες ιδιότητες εγγράφου. Read-only [IDocumentProperties](../../com.aspose.slides/idocumentproperties).

**Επιστρέφει:**
[IDocumentProperties](../../com.aspose.slides/idocumentproperties)

### getImages() {#getImages--}
```
public final IImageCollection getImages()
```

Επιστρέφει τη συλλογή όλων των εικόνων στην παρουσίαση. Read-only [IImageCollection](../../com.aspose.slides/iimagecollection).

--------------------

> ```
> The following examples shows how to add image as BLOB in PowerPoint Presentation.
>  
>  // δημιουργεί μια νέα παρουσίαση στην οποία θα προστεθεί η εικόνα.
>  Presentation pres = new Presentation();
>  try
>  {
>      // υποθέτουμε ότι έχουμε το μεγάλο αρχείο εικόνας που θέλουμε να συμπεριλάβουμε στην παρουσίαση
>      FileInputStream fip = new FileInputStream("large_image.jpg");
>      try
>      {
>          // Ας προσθέσουμε την εικόνα στην παρουσίαση - επιλέγουμε τη συμπεριφορά KeepLocked επειδή
>          // δεν προτίθεμαι να αποκτήσω πρόσβαση στο αρχείο "largeImage.png".
>          IPPImage img = pres.getImages().addImage(fip, LoadingStreamBehavior.KeepLocked);
>          pres.getSlides().get_Item(0).getShapes().addPictureFrame(ShapeType.Rectangle, 0, 0, 300, 200, img);
>          // Αποθηκεύει την παρουσίαση. Καθώς παραγίνεται μια μεγάλη παρουσίαση, η χρήση μνήμης
>          // μένει χαμηλή κατά τη διάρκεια του κύκλου ζωής του αντικειμένου pres.
>          pres.save("presentationWithLargeImage.pptx", SaveFormat.Pptx);
>      }
>      finally
>      {
>          fip.close();
>      }
>  }
>  catch (java.io.IOException e) { }
>  finally
>  {
>      pres.dispose();
>  }
>  
>  The following examples add a hyperlink to an image in a PowerPoint Presentation.
>  
>  Presentation pres = new Presentation();
>  try {
>      FileInputStream fos = null;
>      try {
>          fos = new FileInputStream("image.png");
>          // Προσθέτει εικόνα στην παρουσίαση
>          IPPImage image = pres.getImages().addImage(fos);
>          // Δημιουργεί πλαίσιο εικόνας στη διαφάνεια 1 βασισμένο στην προηγουμένως προστιθέμενη εικόνα
>          IPictureFrame pictureFrame = pres.getSlides().get_Item(0).getShapes().addPictureFrame(ShapeType.Rectangle, 10, 10, 100, 100, image);
>          pictureFrame.setHyperlinkClick(new Hyperlink("https://www.aspose.com/"));
>          pictureFrame.getHyperlinkClick().setTooltip("More than 70% Fortune 100 companies trust Aspose APIs");
>      } finally {
>          if (fos != null) fos.close();
>      }
>      pres.save("pres-out.pptx", SaveFormat.Pptx);
>  } catch (IOException e){ }
>  finally
>  {
>      if (pres != null) pres.dispose();
>  }
> ```


**Επιστρέφει:**
[IImageCollection](../../com.aspose.slides/iimagecollection)

### getAudios() {#getAudios--}
```
public final IAudioCollection getAudios()
```

Επιστρέφει τη συλλογή όλων των ενσωματωμένων αρχείων ήχου στην παρουσίαση. Read-only [IAudioCollection](../../com.aspose.slides/iaudiocollection).

--------------------

> ```
> The following examples shows how to add a hyperlink to an audio file.
>  
>  Presentation pres = new Presentation();
>  try {
>      FileInputStream fos = null;
>      try {
>          fos = new FileInputStream("audio.mp3");
>          IAudio audio = pres.getAudios().addAudio(fos);
>          IAudioFrame audioFrame = pres.getSlides().get_Item(0).getShapes().addAudioFrameEmbedded(10, 10, 100, 100, audio);
>          audioFrame.setHyperlinkClick(new Hyperlink("https://www.aspose.com/"));
>          audioFrame.getHyperlinkClick().setTooltip("More than 70% Fortune 100 companies trust Aspose APIs");
>      } finally {
>          if (fos != null) fos.close();
>      }
>      pres.save("pres-out.pptx", SaveFormat.Pptx);
>  }
>  catch (IOException e) {}
>  finally
>  {
>      if (pres != null) pres.dispose();
>  }
> ```


**Επιστρέφει:**
[IAudioCollection](../../com.aspose.slides/iaudiocollection)

### getVideos() {#getVideos--}
```
public final IVideoCollection getVideos()
```

Επιστρέφει τη συλλογή όλων των ενσωματωμένων αρχείων βίντεο στην παρουσίαση. Read-only [IVideoCollection](../../com.aspose.slides/ivideocollection).

--------------------

> ```
> The following examples shows how to create embedded Video Frame in a PowerPoint Presentation.
>  
>  // Instantiate Presentation class that represents the PPTX
>  Presentation pres = new Presentation();
>  try {
>      // Get the first slide
>      ISlide sld = pres.getSlides().get_Item(0);
>      // Embedd vide inside presentation
>      IVideo vid = pres.getVideos().addVideo(new FileInputStream("Wildlife.mp4"));
>      // Add Video Frame
>      IVideoFrame vf = sld.getShapes().addVideoFrame(50, 150, 300, 350, vid);
>      // Set video to Video Frame
>      vf.setEmbeddedVideo(vid);
>      // Set Play Mode and Volume of the Video
>      vf.setPlayMode(VideoPlayModePreset.Auto);
>      vf.setVolume(AudioVolumeMode.Loud);
>      // Write the PPTX file to disk
>      pres.save("VideoFrame_out.pptx", SaveFormat.Pptx);
>  } catch(IOException e) {
>  } finally {
>      if (pres != null) pres.dispose();
>  }
>  
>  The following examples shows how to add a video passing path to the video file directly into AddVideoFrame method for PowerPoint Presentation.
>  
>  Presentation pres = new Presentation();
>  try {
>      ISlide sld = pres.getSlides().get_Item(0);
>      IVideoFrame vf = sld.getShapes().addVideoFrame(50, 150, 300, 150, "video1.avi");
>  } finally {
>      if (pres != null) pres.dispose();
>  }
>  
>  The following examples shows how to add large file through BLOB to a Presentation.
>  
>  // Creates a new presentation to which the video will be added
>  Presentation pres = new Presentation();
>  try {
>      FileInputStream fileStream = new FileInputStream("veryLargeVideo.avi");
>      try {
>          // Let's add the video to the presentation - we chose the KeepLocked behavior because we do
>          //not intend to access the "veryLargeVideo.avi" file.
>          IVideo video = pres.getVideos().addVideo(fileStream, LoadingStreamBehavior.KeepLocked);
>          pres.getSlides().get_Item(0).getShapes().addVideoFrame(0, 0, 480, 270, video);
>          // Saves the presentation. While a large presentation gets outputted, the memory consumption
>          // stays low through the pres object's lifecycle
>          pres.save("presentationWithLargeVideo.pptx", SaveFormat.Pptx);
>      } finally {
>          if (fileStream != null) fileStream.close();
>      }
>  } catch(IOException e) {
>  } finally {
>      if (pres != null) pres.dispose();
>  }
>  
>  The following examples shows how to export large file through BLOB from PowerPoint Presentation.
>  
>  LoadOptions loadOptions = new LoadOptions();
>  // Locks the source file and does NOT load it into memory
>  loadOptions.getBlobManagementOptions().setPresentationLockingBehavior(PresentationLockingBehavior.KeepLocked);
>  // Creates a Presentation's instance, locks the "hugePresentationWithAudiosAndVideos.pptx" file.
>  Presentation pres = new Presentation("Large  Video File Test1.pptx", loadOptions);
>  try {
>      // Let's save each video to a file. To prevent high memory usage, we need a buffer that will be used
>      // to transfer the data from the presentation's video stream to a stream for a newly created video file.
>      byte[] buffer = new byte[81024];
>      // Iterates through the videos
>      for (int index = 0; index < pres.getVideos().size(); index++) {
>          IVideo video = pres.getVideos().get_Item(index);
>          // Opens the presentation video stream. Please, note that we intentionally avoided accessing properties
>          // like video.BinaryData - because this property returns a byte array containing a full video, which then
>          // causes bytes to be loaded into memory. We use video.GetStream, which will return Stream - and does NOT
>          //  require us to load the whole video into the memory.
>          InputStream presVideoStream = video.getStream();
>          try {
>              FileOutputStream outputFileStream = new FileOutputStream("video{index}.avi");
>              try {
>                  int bytesRead;
>                  while ((bytesRead = presVideoStream.read(buffer, 0, buffer.length)) > 0) {
>                      outputFileStream.write(buffer, 0, bytesRead);
>                  }
>              } finally {
>                  if (outputFileStream != null) outputFileStream.close();
>              }
>          } finally {
>              if (presVideoStream != null) presVideoStream.close();
>          }
>          // Memory consumption will remain low regardless of the size of the video or presentation,
>      }
>      // If necessary, you can apply the same steps for audio files.
>  } catch(IOException e) {
>  } finally {
>      if (pres != null) pres.dispose();
>  }
>  
>  The following examples shows how to add a hyperlink to a video in a PowerPoint Presentation.
>  
>  Presentation pres = new Presentation();
>  try {
>      IVideo video = pres.getVideos().addVideo(Files.readAllBytes(Paths.get("video.avi")));
>      IVideoFrame videoFrame = pres.getSlides().get_Item(0).getShapes().addVideoFrame(10, 10, 100, 100, video);
>      videoFrame.setHyperlinkClick(new Hyperlink("https://www.aspose.com/"));
>      videoFrame.getHyperlinkClick().setTooltip("More than 70% Fortune 100 companies trust Aspose APIs");
>      pres.save("pres-out.pptx", SaveFormat.Pptx);
>  } catch(IOException e) {
>  } finally {
>      if (pres != null) pres.dispose();
>  }
>  
>  The following examples shows how to create Video Frame with Video from Web Source in a PowerPoint Presentation.
>  
>  public static void run()
>  {
>      Presentation pres = new Presentation();
>      try {
>          addVideoFromYouTube(pres, "Tj75Arhq5ho");
>          pres.save("AddVideoFrameFromWebSource_out.pptx", SaveFormat.Pptx);
>      } catch(IOException e) {
>      } finally {
>          if (pres != null) pres.dispose();
>      }
>  }
>  private static void addVideoFromYouTube(Presentation pres, String videoId) throws IOException
>  {
>      //add videoFrame
>      IVideoFrame videoFrame = pres.getSlides().get_Item(0).getShapes().addVideoFrame(10, 10, 427, 240, "https://www.youtube.com/embed/" + videoId);
>      videoFrame.setPlayMode(VideoPlayModePreset.Auto);
> 
>      //load thumbnail
>      String thumbnailUri = "http://img.youtube.com/vi/" + videoId + "/hqdefault.jpg";
>      URL url = new URL(thumbnailUri);
>      URLConnection connection = url.openConnection();
>      connection.setConnectTimeout(5000);
>      connection.setReadTimeout(10000);
>      InputStream input = connection.getInputStream();
>      ByteArrayOutputStream output = new ByteArrayOutputStream();
>      try
>      {
>          byte[] buffer = new byte[8192];
>          for (int count; (count = input.read(buffer)) > 0; )
>          {
>              output.write(buffer, 0, count);
>          }
>          videoFrame.getPictureFormat().getPicture().setImage(pres.getImages().addImage(output.toByteArray()));
>      } finally {
>          if (input != null) input.close();
>          if (output != null) output.close();
>      }
>  }
>  
>  The following examples shows how to extract Video from slide of PowerPoint Presentation.
>  
>  // Instantiate a Presentation object that represents a presentation file
>  Presentation presentation = new Presentation("Video.pptx");
>  try {
>      for (ISlide slide : presentation.getSlides())
>      {
>          for (IShape shape : presentation.getSlides().get_Item(0).getShapes())
>          {
>              if (shape instanceof VideoFrame)
>              {
>                  IVideoFrame vf = (IVideoFrame) shape;
>                  String type = vf.getEmbeddedVideo().getContentType();
>                  int ss = type.lastIndexOf('/');
>                  type = type.substring(ss + 1);
>                  byte[] buffer = vf.getEmbeddedVideo().getBinaryData();
>                  FileOutputStream fop = new FileOutputStream("NewVideo_out." + type);
>                  try
>                  {
>                      fop.write(buffer);
>                      fop.flush();
>                      fop.close();
>                  }
>                  finally
>                  {
>                      if (presentation != null) presentation.dispose();
>                  }
>              }
>          }
>      }
>  } catch(IOException e) {
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```

**Επιστρέφει:**
[IVideoCollection](../../com.aspose.slides/ivideocollection)

### getSlideShowSettings() {#getSlideShowSettings--}
```
public final SlideShowSettings getSlideShowSettings()
```

Επιστρέφει τις ρυθμίσεις προβολής διαφανειών για την παρουσίαση.

**Επιστρέφει:**
[SlideShowSettings](../../com.aspose.slides/slideshowsettings)

### getDigitalSignatures() {#getDigitalSignatures--}
```
public final IDigitalSignatureCollection getDigitalSignatures()
```

Επιστρέφει τη συλλογή των υπογραφών που χρησιμοποιήθηκαν για την υπογραφή της παρουσίασης. Read-only [IDigitalSignatureCollection](../../com.aspose.slides/idigitalsignaturecollection).

--------------------

> ```
> Presentation pres = new Presentation("SomePresentationSigned.pptx");
>  try
>  {
>      if (pres.getDigitalSignatures().size() > 0)
>      {
>          boolean allSignaturesAreValid = true;
>          System.out.println("Signatures used to sign the presentation: ");
>          for (IDigitalSignature signature : pres.getDigitalSignatures())
>          {
>             System.out.println(signature.getCertificate().hashCode() + ", "
>                   + signature.getSignTime().toString() + " -- " + (signature.isValid() ? "VALID" : "INVALID"));
>             allSignaturesAreValid &= signature.isValid();
>          }
>          if (allSignaturesAreValid)
>             System.out.println("Presentation is genuine, all signatures are valid.");
>          else
>             System.out.println("Presentation has been modified since signing.");
>      }
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Επιστρέφει:**
[IDigitalSignatureCollection](../../com.aspose.slides/idigitalsignaturecollection)

### getCustomData() {#getCustomData--}
```
public final ICustomData getCustomData()
```

Επιστρέφει τα προσαρμοσμένα δεδομένα της παρουσίασης. Read-only [ICustomData](../../com.aspose.slides/icustomdata).

**Επιστρέφει:**
[ICustomData](../../com.aspose.slides/icustomdata)

### getAllCustomXmlParts() {#getAllCustomXmlParts--}
```
public final ICustomXmlPart[] getAllCustomXmlParts()
```

Επιστρέφει όλα τα προσαρμοσμένα τμήματα δεδομένων στην παρουσίαση. Read-only ICustomXmlPart[].

--------------------

> ```
> The following examples show how to clear all custom xml parts from PowerPoint Presentation.
>  
>  Presentation pres = new Presentation("PresentationWithCustomXml.pptx");
>  try {
>      // Επανάληψη σε όλα τα προσαρμοσμένα XML τμήματα
>      for (ICustomXmlPart item : pres.getAllCustomXmlParts())
>      {
>          item.remove();
>      }
>      pres.save("out.pptx", SaveFormat.Pptx);
>  }
>  finally
>  {
>      if (pres != null) pres.dispose();
>  }
> ```


**Επιστρέφει:**
com.aspose.slides.ICustomXmlPart[]

### getVbaProject() {#getVbaProject--}
```
public final IVbaProject getVbaProject()
```

Λαμβάνει ή ορίζει το έργο VBA με μακροεντολές παρουσίασης. Read/write [IVbaProject](../../com.aspose.slides/ivbaproject).

**Επιστρέφει:**
[IVbaProject](../../com.aspose.slides/ivbaproject)

### setVbaProject(IVbaProject value) {#setVbaProject-com.aspose.slides.IVbaProject-}
```
public final void setVbaProject(IVbaProject value)
```

Λαμβάνει ή ορίζει το έργο VBA με μακροεντολές παρουσίασης. Read/write [IVbaProject](../../com.aspose.slides/ivbaproject).

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | [IVbaProject](../../com.aspose.slides/ivbaproject) |  |

### getHyperlinkQueries() {#getHyperlinkQueries--}
```
public final IHyperlinkQueries getHyperlinkQueries()
```

Παρέχει εύκολη πρόσβαση σε όλους τους υπερσυνδέσμους που περιέχονται σε όλες τις διαφάνειες της παρουσίασης (όχι στις κύριες, διάταξης, σημειώσεων). Read-only [IHyperlinkQueries](../../com.aspose.slides/ihyperlinkqueries).

**Επιστρέφει:**
[IHyperlinkQueries](../../com.aspose.slides/ihyperlinkqueries)

### getViewProperties() {#getViewProperties--}
```
public final IViewProperties getViewProperties()
```

Λαμβάνει τις ευρείες ιδιότητες προβολής της παρουσίασης. Read-only [IViewProperties](../../com.aspose.slides/iviewproperties).

**Επιστρέφει:**
[IViewProperties](../../com.aspose.slides/iviewproperties)

### getFirstSlideNumber() {#getFirstSlideNumber--}
```
public final int getFirstSlideNumber()
```

Αναπαριστά τον αριθμό της πρώτης διαφάνειας στην παρουσίαση.

**Επιστρέφει:**
int

### setFirstSlideNumber(int value) {#setFirstSlideNumber-int-}
```
public final void setFirstSlideNumber(int value)
```

Αναπαριστά τον αριθμό της πρώτης διαφάνειας στην παρουσίαση.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | int |  |

### getSensitivityLabels() {#getSensitivityLabels--}
```
public final ISensitivityLabelCollection getSensitivityLabels()
```

Επιστρέφει τη συλλογή των ετικετών ευαισθησίας που εφαρμόζονται στο έγγραφο παρουσίασης. Read-only [ISensitivityLabelCollection](../../com.aspose.slides/isensitivitylabelcollection).

--------------------

> ```
> Presentation pres = new Presentation("SomePresentation.pptx");
>  try {
>      ISensitivityLabelCollection sensitivityLabels = pres.getSensitivityLabels();
> 
>      // Εκτυπώνει τις εφαρμοσμένες ετικέτες
>      for (ISensitivityLabel sensitivityLabel : sensitivityLabels)
>          System.out.println("Label Id " + sensitivityLabel.getId() + " from Azure AD site " + sensitivityLabel.getSiteId());
> 
>      // Προσθέτει τη νέα ετικέτα
>      String labelIdString = "{xxxxxxxx-xxxx-xxxx-xxxx-xxxxxxxxxxxx}"; // Λαμβάνει το Id της ετικέτας ευαισθησίας από την πολιτική
>      UUID siteIdGuid = UUID.fromString("{xxxxxxxx-xxxx-xxxx-xxxx-xxxxxxxxxxxx}"); // Λαμβάνει το αναγνωριστικό του Azure AD site από την πολιτική
>      ISensitivityLabel label = sensitivityLabels.add(labelIdString, siteIdGuid, true, SensitivityLabelAssignmentType.Privileged);
>      label.getContentMarkTypes().addItem(SensitivityLabelContentType.Footer);
> 
>      pres.save("SensitivityLabel.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Επιστρέφει:**
[ISensitivityLabelCollection](../../com.aspose.slides/isensitivitylabelcollection)

### getSlideById(long id) {#getSlideById-long-}
```
public final IBaseSlide getSlideById(long id)
```

Επιστρέφει μια Slide, MasterSlide ή LayoutSlide με βάση το Id.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| id | long | Id μιας διαφάνειας. |

**Επιστρέφει:**
[IBaseSlide](../../com.aspose.slides/ibaseslide) - IBaseSlide object.

### getSourceFormat() {#getSourceFormat--}
```
public final int getSourceFormat()
```

Επιστρέφει πληροφορίες σχετικά με τη μορφή από την οποία φορτώθηκε η παρουσίαση. Read-only [SourceFormat](../../com.aspose.slides/sourceformat).

**Επιστρέφει:**
int

### getMasterTheme() {#getMasterTheme--}
```
public final IMasterTheme getMasterTheme()
```

Επιστρέφει το κύριο θέμα. Read-only [IMasterTheme](../../com.aspose.slides/imastertheme).

--------------------

> ```
> The following examples shows how to change a theme effect by altering parts of elements of PowerPoint Presentation.
>  
>  //Δημιουργεί ένα αντικείμενο παρουσίασης που αντιπροσωπεύει ένα αρχείο παρουσίασης
>  Presentation pres = new Presentation("Subtle_Moderate_Intense.pptx");
>  try {
>      pres.getMasterTheme().getFormatScheme().getLineStyles().get_Item(0).getFillFormat().getSolidFillColor().setColor(Color.RED);
>      ((FillFormat)pres.getMasterTheme().getFormatScheme().getLineStyles().get_Item(2)).setFillType(FillType.Solid);
>      ((FillFormat)pres.getMasterTheme().getFormatScheme().getLineStyles().get_Item(2)).getSolidFillColor().setColor(Color.GREEN);
>      ((EffectStyle)pres.getMasterTheme().getFormatScheme().getLineStyles().get_Item(2)).getEffectFormat().getOuterShadowEffect().setDistance(10f);
>      pres.save("Design_04_Subtle_Moderate_Intense-out.pptx", SaveFormat.Pptx);
>  }
>  finally
>  {
>      if (pres != null) pres.dispose();
>  }
> ```


**Επιστρέφει:**
[IMasterTheme](../../com.aspose.slides/imastertheme)

### save(String fname, int format) {#save-java.lang.String-int-}
```
public final void save(String fname, int format)
```

Αποθηκεύει όλες τις διαφάνειες μιας παρουσίασης σε αρχείο με την καθορισμένη μορφή.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| fname | java.lang.String | Διαδρομή του δημιουργημένου αρχείου. |
| format | int | Μορφή των εξαγόμενων δεδομένων. |

### save(OutputStream stream, int format) {#save-java.io.OutputStream-int-}
```
public final void save(OutputStream stream, int format)
```

Αποθηκεύει όλες τις διαφάνειες μιας παρουσίασης σε ροή με την καθορισμένη μορφή.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| stream | java.io.OutputStream | Ροή εξόδου. |
| format | int | Μορφή των εξαγόμενων δεδομένων. |

### save(String fname, int format, ISaveOptions options) {#save-java.lang.String-int-com.aspose.slides.ISaveOptions-}
```
public final void save(String fname, int format, ISaveOptions options)
```

Αποθηκεύει όλες τις διαφάνειες μιας παρουσίασης σε αρχείο με την καθορισμένη μορφή και με πρόσθετες επιλογές.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| fname | java.lang.String | Διαδρομή του δημιουργημένου αρχείου. |
| format | int | Μορφή των εξαγόμενων δεδομένων. |
| options | [ISaveOptions](../../com.aspose.slides/isaveoptions) | Πρόσθετες επιλογές μορφής. |

### save(OutputStream stream, int format, ISaveOptions options) {#save-java.io.OutputStream-int-com.aspose.slides.ISaveOptions-}
```
public final void save(OutputStream stream, int format, ISaveOptions options)
```

Αποθηκεύει όλες τις διαφάνειες μιας παρουσίασης σε ροή με την καθορισμένη μορφή και με πρόσθετες επιλογές.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| stream | java.io.OutputStream | Ροή εξόδου. |
| format | int | Μορφή των εξαγόμενων δεδομένων. |
| options | [ISaveOptions](../../com.aspose.slides/isaveoptions) | Πρόσθετες επιλογές μορφής. |

### save(IXamlOptions options) {#save-com.aspose.slides.IXamlOptions-}
```
public final void save(IXamlOptions options)
```

Αποθηκεύει όλες τις διαφάνειες μιας παρουσίασης σε σύνολο αρχείων που αντιπροσωπεύουν μορφοποίηση XAML.

--------------------

> ```
> Presentation pres = new Presentation("pres.pptx");
>  try {
>      XamlOptions xamlOptions = new XamlOptions();
>      xamlOptions.setExportHiddenSlides(true);
> 
>      pres.save(xamlOptions);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| options | [IXamlOptions](../../com.aspose.slides/ixamloptions) | Οι επιλογές μορφής XAML. |

### getImages(IRenderingOptions options) {#getImages-com.aspose.slides.IRenderingOptions-}
```
public final IImage[] getImages(IRenderingOptions options)
```

Επιστρέφει αντικείμενα Image για όλες τις διαφάνειες μιας παρουσίασης.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| options | [IRenderingOptions](../../com.aspose.slides/irenderingoptions) | Επιλογές Tiff. |

**Επιστρέφει:**
com.aspose.slides.IImage[] - Image objects.

### getImages(IRenderingOptions options, int[] slides) {#getImages-com.aspose.slides.IRenderingOptions-int---}
```
public final IImage[] getImages(IRenderingOptions options, int[] slides)
```

Επιστρέφει αντικείμενα Thumbnail Image για τις καθορισμένες διαφάνειες μιας παρουσίασης.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| options | [IRenderingOptions](../../com.aspose.slides/irenderingoptions) | Επιλογές Tiff. |
| slides | int[] | Πίνακας με θέσεις διαφανειών, ξεκινώντας από το 1. |

**Επιστρέφει:**
com.aspose.slides.IImage[] - Image objects.

### getImages(IRenderingOptions options, float scaleX, float scaleY) {#getImages-com.aspose.slides.IRenderingOptions-float-float-}
```
public final IImage[] getImages(IRenderingOptions options, float scaleX, float scaleY)
```

Επιστρέφει αντικείμενα Thumbnail Image για όλες τις διαφάνειες μιας παρουσίασης με προσαρμοσμένη κλιμάκωση.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| options | [IRenderingOptions](../../com.aspose.slides/irenderingoptions) | Επιλογές Tiff. |
| scaleX | float | Η τιμή με την οποία κλιμακώνεται το Thumbnail στην κατεύθυνση του άξονα x. |
| scaleY | float | Η τιμή με την οποία κλιμακώνεται το Thumbnail στην κατεύθυνση του άξονα y. |

**Επιστρέφει:**
com.aspose.slides.IImage[] - Image objects.

### getImages(IRenderingOptions options, int[] slides, float scaleX, float scaleY) {#getImages-com.aspose.slides.IRenderingOptions-int---float-float-}
```
public final IImage[] getImages(IRenderingOptions options, int[] slides, float scaleX, float scaleY)
```

Επιστρέφει αντικείμενα Thumbnail Image για τις καθορισμένες διαφάνειες μιας παρουσίασης με προσαρμοσμένη κλιμάκωση.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| options | [IRenderingOptions](../../com.aspose.slides/irenderingoptions) | Επιλογές Tiff. |
| slides | int[] | Πίνακας με θέσεις διαφανειών, ξεκινώντας από το 1. |
| scaleX | float | Η τιμή με την οποία κλιμακώνεται το Thumbnail στην κατεύθυνση του άξονα x. |
| scaleY | float | Η τιμή με την οποία κλιμακώνεται το Thumbnail στην κατεύθυνση του άξονα y. |

**Επιστρέφει:**
com.aspose.slides.IImage[] - Image objects.

### getImages(IRenderingOptions options, Size imageSize) {#getImages-com.aspose.slides.IRenderingOptions-com.aspose.slides.android.Size-}
```
public final IImage[] getImages(IRenderingOptions options, Size imageSize)
```

Επιστρέφει αντικείμενα Thumbnail Image για όλες τις διαφάνειες μιας παρουσίασης με καθορισμένο μέγεθος.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| options | [IRenderingOptions](../../com.aspose.slides/irenderingoptions) | Επιλογές Tiff. |
| imageSize | [Size](../../com.aspose.slides.android/size) | Μέγεθος της εικόνας που θα δημιουργηθεί. |

**Επιστρέφει:**
com.aspose.slides.IImage[] - Image objects.

### getImages(IRenderingOptions options, int[] slides, Size imageSize) {#getImages-com.aspose.slides.IRenderingOptions-int---com.aspose.slides.android.Size-}
```
public final IImage[] getImages(IRenderingOptions options, int[] slides, Size imageSize)
```

Επιστρέφει αντικείμενα Thumbnail Image για τις καθορισμένες διαφάνειες μιας παρουσίασης με καθορισμένο μέγεθος.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| options | [IRenderingOptions](../../com.aspose.slides/irenderingoptions) | Επιλογές Tiff. |
| slides | int[] | Πίνακας με θέσεις διαφανειών, ξεκινώντας από το 1. |
| imageSize | [Size](../../com.aspose.slides.android/size) | Μέγεθος της εικόνας που θα δημιουργηθεί. |

**Επιστρέφει:**
com.aspose.slides.IImage[] - Image objects.

### save(String fname, int[] slides, int format) {#save-java.lang.String-int---int-}
```
public final void save(String fname, int[] slides, int format)
```

Αποθηκεύει τις καθορισμένες διαφάνειες μιας παρουσίασης σε αρχείο με την καθορισμένη μορφή και διατηρώντας τον αριθμό σελίδας.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| fname | java.lang.String | Διαδρομή του δημιουργημένου αρχείου. |
| slides | int[] | Πίνακας με θέσεις διαφανειών, ξεκινώντας από το 1. |
| format | int | Μορφή των εξαγόμενων δεδομένων. |

### save(String fname, int[] slides, int format, ISaveOptions options) {#save-java.lang.String-int---int-com.aspose.slides.ISaveOptions-}
```
public final void save(String fname, int[] slides, int format, ISaveOptions options)
```

Αποθηκεύει τις καθορισμένες διαφάνειες μιας παρουσίασης σε αρχείο με την καθορισμένη μορφή και διατηρώντας τον αριθμό σελίδας.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| fname | java.lang.String | Διαδρομή του δημιουργημένου αρχείου. |
| slides | int[] | Πίνακας με θέσεις διαφανειών, ξεκινώντας από το 1. |
| format | int | Μορφή των εξαγόμενων δεδομένων. |
| options | [ISaveOptions](../../com.aspose.slides/isaveoptions) | Πρόσθετες επιλογές μορφής. |

### save(OutputStream stream, int[] slides, int format) {#save-java.io.OutputStream-int---int-}
```
public final void save(OutputStream stream, int[] slides, int format)
```

Αποθηκεύει τις καθορισμένες διαφάνειες μιας παρουσίασης σε ροή με την καθορισμένη μορφή και διατηρώντας τον αριθμό σελίδας.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| stream | java.io.OutputStream | Ροή εξόδου. |
| slides | int[] | Πίνακας με θέσεις διαφανειών, ξεκινώντας από το 1. |
| format | int | Μορφή των εξαγόμενων δεδομένων. |

### save(OutputStream stream, int[] slides, int format, ISaveOptions options) {#save-java.io.OutputStream-int---int-com.aspose.slides.ISaveOptions-}
```
public final void save(OutputStream stream, int[] slides, int format, ISaveOptions options)
```

Αποθηκεύει τις καθορισμένες διαφάνειες μιας παρουσίασης σε ροή με την καθορισμένη μορφή και διατηρώντας τον αριθμό σελίδας.

--------------------

> ```
> The following example shows how to convert PowerPoint to PNG.
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      for (int index = 0; index < pres.getSlides().size(); index++) {
>          ISlide slide = pres.getSlides().get_Item(index);
>          FileOutputStream out = new FileOutputStream("slide_" + index + ".png");
>          slide.getThumbnail().compress(android.graphics.Bitmap.CompressFormat.PNG, 100, out);
>          out.flush();
>          out.close();
>      }
>  } catch(IOException e) {
>  } finally {
>      if (pres != null) pres.dispose();
>  }
>  
>  The following example shows how to convert PowerPoint to PNG with custom dimensions.
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      float scaleX = 2f;
>      float scaleY = 2f;
>      for (int index = 0; index < pres.getSlides().size(); index++) {
>          ISlide slide = pres.getSlides().get_Item(index);
>          FileOutputStream out = new FileOutputStream("slide_" + index + ".png");
>          slide.getThumbnail(scaleX, scaleY).compress(android.graphics.Bitmap.CompressFormat.PNG, 100, out);
>          out.flush();
>          out.close();
>      }
>  } catch(IOException e) {
>  } finally {
>      if (pres != null) pres.dispose();
>  }
>  
>  The following example shows how to convert PowerPoint to PNG with custom size.
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      com.aspose.slides.android.Size size = new com.aspose.slides.android.Size(960, 720);
>      for (int index = 0; index < pres.getSlides().size(); index++) {
>          ISlide slide = pres.getSlides().get_Item(index);
>          FileOutputStream out = new FileOutputStream("slide_" + index + ".png");
>          slide.getThumbnail(size).compress(android.graphics.Bitmap.CompressFormat.PNG, 100, out);
>          out.flush();
>          out.close();
>      }
>  } catch(IOException e) {
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| stream | java.io.OutputStream | Ροή εξόδου. |
| slides | int[] | Πίνακας με θέσεις διαφανειών, ξεκινώντας από το 1. |
| format | int | Μορφή των εξαγόμενων δεδομένων. |
| options | [ISaveOptions](../../com.aspose.slides/isaveoptions) | Πρόσθετες επιλογές μορφής. |

### joinPortionsWithSameFormatting() {#joinPortionsWithSameFormatting--}
```
public final void joinPortionsWithSameFormatting()
```

Ενώνει τμήματα κειμένου με την ίδια μορφοποίηση σε όλες τις παραγράφους σε όλα τα αποδεκτά σχήματα σε όλες τις διαφάνειες.

### dispose() {#dispose--}
```
public final void dispose()
```

Αποδεσμεύει όλους τους πόρους που χρησιμοποιεί αυτό το αντικείμενο Presentation.

### getPresentation() {#getPresentation--}
```
public final IPresentation getPresentation()
```

Επιστρέφει την γονική παρουσίαση ενός κειμένου. Read-only [IPresentation](../../com.aspose.slides/ipresentation).

**Επιστρέφει:**
[IPresentation](../../com.aspose.slides/ipresentation)

### highlightText(String text, Integer highlightColor) {#highlightText-java.lang.String-java.lang.Integer-}
```
public final void highlightText(String text, Integer highlightColor)
```

Επισημαίνει όλες τις αντιστοιχίες του δείγματος κειμένου με το καθορισμένο χρώμα.

--------------------

> ```
> The following code sample shows how to highlight text in a PowerPoint presentation.
>  
>  Presentation presentation = new Presentation("SomePresentation.pptx");
>  try {
>      // Επισημαίνοντας όλες τις ξεχωριστές εμφανίσεις του 'the'
>      presentation.highlightText("the", Color.MAGENTA);
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

### highlightText(String text, Integer highlightColor, ITextSearchOptions options, IFindResultCallback callback) {#highlightText-java.lang.String-java.lang.Integer-com.aspose.slides.ITextSearchOptions-com.aspose.slides.IFindResultCallback-}
```
public final void highlightText(String text, Integer highlightColor, ITextSearchOptions options, IFindResultCallback callback)
```

Επισημαίνει όλες τις αντιστοιχίες του δείγματος κειμένου με το καθορισμένο χρώμα.

--------------------

> ```
> The following code sample shows how to highlight text in a PowerPoint presentation.
>  
>  Presentation presentation = new Presentation("SomePresentation.pptx");
>  try {
>      TextSearchOptions textSearchOptions = new TextSearchOptions();
>      textSearchOptions.setWholeWordsOnly(true);
>      // Επισημαίνοντας όλες τις ξεχωριστές εμφανίσεις του 'the'
>      presentation.highlightText("the", Color.MAGENTA, textSearchOptions, null);
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
| callback | [IFindResultCallback](../../com.aspose.slides/ifindresultcallback) | Το αντικείμενο callback για λήψη αποτελεσμάτων αναζήτησης [IFindResultCallback](../../com.aspose.slides/ifindresultcallback). |

### highlightRegex(Pattern regex, Integer highlightColor, IFindResultCallback callback) {#highlightRegex-java.util.regex.Pattern-java.lang.Integer-com.aspose.slides.IFindResultCallback-}
```
public final void highlightRegex(Pattern regex, Integer highlightColor, IFindResultCallback callback)
```

Επισημαίνει όλες τις αντιστοιχίες της κανονικής έκφρασης με το καθορισμένο χρώμα.

--------------------

> ```
> The following code sample shows how to highlight text in a PowerPoint Presentation using a regular expression.
>  
>  Presentation presentation = new Presentation("SomePresentation.pptx");
>  try {
>      Pattern regex = Pattern.compile("\\b[^\\s]{10,}\\b");
>      // Επισημαίνοντας όλες τις λέξεις με 10 σύμβολα ή περισσότερα
>      presentation.highlightRegex(regex, Color.BLUE, null);
>      presentation.save("SomePresentation-out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```


**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| regex | java.util.regex.Pattern | Η κανονική έκφραση java.util.regex.Pattern για λήψη συμβολοσειρών προς επισήμανση. |
| highlightColor | java.lang.Integer | Το χρώμα για την επισήμανση του κειμένου. |
| callback | [IFindResultCallback](../../com.aspose.slides/ifindresultcallback) | Το αντικείμενο callback για λήψη αποτελεσμάτων αναζήτησης [IFindResultCallback](../../com.aspose.slides/ifindresultcallback). |

### replaceText(String oldText, String newText, ITextSearchOptions options, IFindResultCallback callback) {#replaceText-java.lang.String-java.lang.String-com.aspose.slides.ITextSearchOptions-com.aspose.slides.IFindResultCallback-}
```
public final void replaceText(String oldText, String newText, ITextSearchOptions options, IFindResultCallback callback)
```

Αντικαθιστά όλες τις εμφανίσεις του καθορισμένου κειμένου με άλλο καθορισμένο κείμενο.

--------------------

> ```
> The following sample code shows how to replace one specified string with another specified string.
>  
>  Presentation presentation = new Presentation("SomePresentation.pptx")
>  try {
>      TextSearchOptions textSearchOptions = new TextSearchOptions();
>      textSearchOptions.setWholeWordsOnly(true);
>      // Αντικαθιστά όλες τις ξεχωριστές εμφανίσεις του 'the' με '***'
>      presentation.replaceText("the", "***", textSearchOptions, null);
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
| callback | [IFindResultCallback](../../com.aspose.slides/ifindresultcallback) | Το αντικείμενο callback για λήψη αποτελεσμάτων αναζήτησης [IFindResultCallback](../../com.aspose.slides/ifindresultcallback). |

### replaceRegex(Pattern regex, String newText, IFindResultCallback callback) {#replaceRegex-java.util.regex.Pattern-java.lang.String-com.aspose.slides.IFindResultCallback-}
```
public final void replaceRegex(Pattern regex, String newText, IFindResultCallback callback)
```

Αντικαθιστά όλες τις αντιστοιχίες της κανονικής έκφρασης με την καθορισμένη συμβολοσειρά.

--------------------

> ```
> The following code sample shows how to replace text using regular expression with the specified string.
>  Presentation presentation = new Presentation("SomePresentation.pptx");
>  try {
>      Pattern regex = Pattern.compile("\\b[^\\s]{10,}\\b");
>      // Αντικαθιστά όλες τις λέξεις με 10 σύμβολα ή περισσότερα με '***'
>      presentation.replaceRegex(regex, "***", null);
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
| callback | [IFindResultCallback](../../com.aspose.slides/ifindresultcallback) | Το αντικείμενο callback για λήψη αποτελεσμάτων αναζήτησης [IFindResultCallback](../../com.aspose.slides/ifindresultcallback). |