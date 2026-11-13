---
title: IPresentation
second_title: Αναφορά API Aspose.Slides για Java
description: Έγγραφο παρουσίασης
type: docs
url: /el/com.aspose.slides/ipresentation/
---
**Όλα τα Υλοποιημένα Interfaces:**
[com.aspose.slides.IPresentationComponent](../../com.aspose.slides/ipresentationcomponent), com.aspose.ms.System.IDisposable
```
public interface IPresentation extends IPresentationComponent, System.IDisposable
```

Presentation document
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [getCurrentDateTime()](#getCurrentDateTime--) | Επιστέ



ρει ή ορίζει την ημερομηνία και ώρα που θα αντικαταστήσει το περιεχόμενο των πεδίων datetime. Η ώρα δημιουργίας αυτού του Presentation αντικειμένου εξ ορισμού. Ανάγνωση/εγγραφή java.util.Date. |
| [setCurrentDateTime(Date value)](#setCurrentDateTime-java.util.Date-) | Επιστρέφει ή ορίζει την ημερομηνία και ώρα που θα αντικαταστήσει το περιεχόμενο των πεδίων datetime. Η ώρα δημιουργίας αυτού του Presentation αντικειμένου εξ ορισμού. Ανάγνωση/εγγραφή java.util.Date. |
| [getHeaderFooterManager()](#getHeaderFooterManager--) | Επιστρέφει το διαχειριστή HeaderFooter της παρουσίασης. |
| [getProtectionManager()](#getProtectionManager--) | Λαμβάνει το διαχειριστή των αδειών για αυτήν την παρουσίαση. |
| [getSlides()](#getSlides--) | Επιστρέφει λίστα με όλες τις διαφάνειες που ορίζονται στην παρουσίαση. |
| [getSections()](#getSections--) | Επιστρέφει λίστα με όλες τις ενότητες διαφανειών που ορίζονται στην παρουσίαση. |
| [getSlideSize()](#getSlideSize--) | Επιστρέφει αντικείμενο μεγέθους διαφάνειας. |
| [getNotesSize()](#getNotesSize--) | Επιστρέφει αντικείμενο μεγέθους διαφάνειας σημειώσεων. |
| [getLayoutSlides()](#getLayoutSlides--) | Επιστρέφει λίστα με όλες τις διαφάνειες διάταξης που ορίζονται στην παρουσίαση. |
| [getMasters()](#getMasters--) | Επιστρέφει λίστα με όλες τις κύριες διαφάνειες που ορίζονται στην παρουσίαση. |
| [getMasterNotesSlideManager()](#getMasterNotesSlideManager--) | Επιστρέφει το διαχειριστή notes master. |
| [getMasterHandoutSlideManager()](#getMasterHandoutSlideManager--) | Επιστρέφει το διαχειριστή handout master. |
| [getFontsManager()](#getFontsManager--) | Επιστρέφει το διαχειριστή γραμματοσειρών. |
| [getDefaultTextStyle()](#getDefaultTextStyle--) | Επιστρέφει το προεπιλεγμένο στυλ κειμένου για σχήματα. |
| [getCommentAuthors()](#getCommentAuthors--) | Επιστρέφει τη συλλογή των συγγραφέων σχολίων. |
| [getDocumentProperties()](#getDocumentProperties--) | Επιστρέφει το αντικείμενο DocumentProperties που περιέχει τυπικές και προσαρμοσμένες ιδιότητες εγγράφου. |
| [getImages()](#getImages--) | Επιστρέφει τη συλλογή όλων των εικόνων στην παρουσίαση. |
| [getAudios()](#getAudios--) | Επιστρέφει τη συλλογή όλων των ενσωματωμένων αρχείων ήχου στην παρουσίαση. |
| [getVideos()](#getVideos--) | Επιστρέφει τη συλλογή όλων των ενσωματωμένων αρχείων βίντεο στην παρουσίαση. |
| [getCustomData()](#getCustomData--) | Επιστρέφει τα προσαρμοσμένα δεδομένα της παρουσίασης. |
| [getVbaProject()](#getVbaProject--) | Λαμβάνει το VBA project με μακροεντολές παρουσίασης. |
| [setVbaProject(IVbaProject value)](#setVbaProject-com.aspose.slides.IVbaProject-) | Λαμβάνει το VBA project με μακροεντολές παρουσίασης. |
| [getSourceFormat()](#getSourceFormat--) | Επιστρέφει πληροφορίες σχετικά με τη μορφή από την οποία φορτώθηκε η παρουσίαση. |
| [getMasterTheme()](#getMasterTheme--) | Επιστρέφει το κύριο θέμα της παρουσίασης. |
| [getHyperlinkQueries()](#getHyperlinkQueries--) | Παρέχει εύκολη πρόσβαση σε όλους τους υπερσυνδέσμους που περιέχονται σε όλες τις διαφάνειες παρουσίασης (εκτός από master, layout, notes). |
| [getViewProperties()](#getViewProperties--) | Λαμβάνει τις γενικές ιδιότητες προβολής της παρουσίασης. |
| [getFirstSlideNumber()](#getFirstSlideNumber--) | Αναπαριστά τον αριθμό της πρώτης διαφάνειας στην παρουσίαση. |
| [setFirstSlideNumber(int value)](#setFirstSlideNumber-int-) | Αναπαριστά τον αριθμό της πρώτης διαφάνειας στην παρουσίαση. |
| [getAllCustomXmlParts()](#getAllCustomXmlParts--) | Επιστρέφει όλα τα προσαρμοσμένα τμήματα δεδομένων στην παρουσίαση. |
| [getDigitalSignatures()](#getDigitalSignatures--) | Επιστρέφει τη συλλογή των ψηφιακών υπογραφών που χρησιμοποιήθηκαν για την υπογραφή της παρουσίασης. |
| [getSensitivityLabels()](#getSensitivityLabels--) | Επιστρέφει τη συλλογή των ετικετών ευαισθησίας που εφαρμόστηκαν στο έγγραφο παρουσίασης. |
| [save(String fname, int format)](#save-java.lang.String-int-) | Αποθηκεύει όλες τις διαφάνειες μιας παρουσίασης σε αρχείο με την καθορισμένη μορφή. |
| [save(OutputStream stream, int format)](#save-java.io.OutputStream-int-) | Αποθηκεύει όλες τις διαφάνειες μιας παρουσίασης σε ροή (stream) με την καθορισμένη μορφή. |
| [save(String fname, int format, ISaveOptions options)](#save-java.lang.String-int-com.aspose.slides.ISaveOptions-) | Αποθηκεύει όλες τις διαφάνειες μιας παρουσίασης σε αρχείο με την καθορισμένη μορφή και με πρόσθετες επιλογές. |
| [save(OutputStream stream, int format, ISaveOptions options)](#save-java.io.OutputStream-int-com.aspose.slides.ISaveOptions-) | Αποθηκεύει όλες τις διαφάνειες μιας παρουσίασης σε ροή (stream) με την καθορισμένη μορφή και με πρόσθετες επιλογές. |
| [save(String fname, int[] slides, int format)](#save-java.lang.String-int---int-) | Αποθηκεύει τις καθορισμένες διαφάνειες μιας παρουσίασης σε αρχείο με την καθορισμένη μορφή. |
| [save(String fname, int[] slides, int format, ISaveOptions options)](#save-java.lang.String-int---int-com.aspose.slides.ISaveOptions-) | Αποθηκεύει τις καθορισμένες διαφάνειες μιας παρουσίασης σε αρχείο με την καθορισμένη μορφή. |
| [save(OutputStream stream, int[] slides, int format)](#save-java.io.OutputStream-int---int-) | Αποθηκεύει τις καθορισμένες διαφάνειες μιας παρουσίασης σε ροή (stream) με την καθορισμένη μορφή. |
| [save(OutputStream stream, int[] slides, int format, ISaveOptions options)](#save-java.io.OutputStream-int---int-com.aspose.slides.ISaveOptions-) | Αποθηκεύει τις καθορισμένες διαφάνειες μιας παρουσίασης σε ροή (stream) με την καθορισμένη μορφή. |
| [save(IXamlOptions options)](#save-com.aspose.slides.IXamlOptions-) | Αποθηκεύει όλες τις διαφάνειες μιας παρουσίασης σε σύνολο αρχείων που αντιπροσωπεύουν σήμανση XAML. |
| [getImages(IRenderingOptions options)](#getImages-com.aspose.slides.IRenderingOptions-) | Επιστρέφει αντικείμενα Thumbnail Image για όλες τις διαφάνειες της παρουσίασης. |
| [getImages(IRenderingOptions options, int[] slides)](#getImages-com.aspose.slides.IRenderingOptions-int---) | Επιστρέφει αντικείμενα Thumbnail IImage για τις καθορισμένες διαφάνειες της παρουσίασης. |
| [getImages(IRenderingOptions options, float scaleX, float scaleY)](#getImages-com.aspose.slides.IRenderingOptions-float-float-) | Επιστρέφει αντικείμενα Thumbnail Image για όλες τις διαφάνειες της παρουσίασης με προσαρμοσμένη κλιμάκωση. |
| [getImages(IRenderingOptions options, int[] slides, float scaleX, float scaleY)](#getImages-com.aspose.slides.IRenderingOptions-int---float-float-) | Επιστρέφει αντικείμενα Thumbnail Image για τις καθορισμένες διαφάνειες της παρουσίασης με προσαρμοσμένη κλιμάκωση. |
| [getImages(IRenderingOptions options, Dimension imageSize)](#getImages-com.aspose.slides.IRenderingOptions-java.awt.Dimension-) | Επιστρέφει αντικείμενα Thumbnail Image για όλες τις διαφάνειες της παρουσίασης με καθορισμένο μέγεθος. |
| [getImages(IRenderingOptions options, int[] slides, Dimension imageSize)](#getImages-com.aspose.slides.IRenderingOptions-int---java.awt.Dimension-) | Επιστρέφει αντικείμενα Thumbnail Image για τις καθορισμένες διαφάνειες της παρουσίασης με καθορισμένο μέγεθος. |
| [getSlideById(long id)](#getSlideById-long-) | Επιστρέφει Slide, MasterSlide ή LayoutSlide κατά Id. |
| [joinPortionsWithSameFormatting()](#joinPortionsWithSameFormatting--) | Ενώνει τμήματα κειμένου με την ίδια μορφοποίηση σε όλες τις παραγράφους σε όλα τα αποδεκτά σχήματα σε όλες τις διαφάνειες. |
| [highlightText(String text, Color highlightColor)](#highlightText-java.lang.String-java.awt.Color-) | Επισημαίνει όλες τις εμφανίσεις του δείγματος κειμένου με το καθορισμένο χρώμα. |
| [highlightText(String text, Color highlightColor, ITextSearchOptions options, IFindResultCallback callback)](#highlightText-java.lang.String-java.awt.Color-com.aspose.slides.ITextSearchOptions-com.aspose.slides.IFindResultCallback-) | Επισημαίνει όλες τις εμφανίσεις του δείγματος κειμένου με το καθορισμένο χρώμα. |
| [highlightRegex(Pattern regex, Color highlightColor, IFindResultCallback callback)](#highlightRegex-java.util.regex.Pattern-java.awt.Color-com.aspose.slides.IFindResultCallback-) | Επισημαίνει όλες τις εμφανίσεις της κανονικής έκφρασης με το καθορισμένο χρώμα. |
| [replaceText(String oldText, String newText, ITextSearchOptions options, IFindResultCallback callback)](#replaceText-java.lang.String-java.lang.String-com.aspose.slides.ITextSearchOptions-com.aspose.slides.IFindResultCallback-) | Αντικαθιστά όλες τις εμφανίσεις του καθορισμένου κειμένου με άλλο καθορισμένο κείμενο. |
| [replaceRegex(Pattern regex, String newText, IFindResultCallback callback)](#replaceRegex-java.util.regex.Pattern-java.lang.String-com.aspose.slides.IFindResultCallback-) | Αντικαθιστά όλες τις εμφανίσεις της κανονικής έκφρασης με τη συγκεκριμένη συμβολοσειρά. |
| [refreshChartsData()](#refreshChartsData--) | Επαναφορτώνει τα δεδομένα για όλα τα διαγράμματα στην παρουσίαση από τα αντίστοιχα βιβλία εργασίας. |
| [refreshChartsData(boolean skipFailedCharts)](#refreshChartsData-boolean-) | Επαναφορτώνει τα δεδομένα για όλα τα διαγράμματα στην παρουσίαση από τα αντίστοιχα βιβλία εργασίας. |

### getCurrentDateTime() {#getCurrentDateTime--}
```
public abstract Date getCurrentDateTime()
```

**Επιστρέφει ή ορίζει** ημερομηνία και ώρα που θα αντικαταστήσει το περιεχόμενο των πεδίων datetime. Η ώρα δημιουργίας αυτού του Presentation αντικειμένου εξ ορισμού. **Ανάγνωση/εγγραφή** java.util.Date.

**Επιστρέφει:**
java.util.Date

### setCurrentDateTime(Date value) {#setCurrentDateTime-java.util.Date-}
```
public abstract void setCurrentDateTime(Date value)
```

**Επιστρέφει ή ορίζει** ημερομηνία και ώρα που θα αντικαταστήσει το περιεχόμενο των πεδίων datetime. Η ώρα δημιουργίας αυτού του Presentation αντικειμένου εξ ορισμού. **Ανάγνωση/εγγραφή** java.util.Date.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | java.util.Date |  |

### getHeaderFooterManager() {#getHeaderFooterManager--}
```
public abstract IPresentationHeaderFooterManager getHeaderFooterManager()
```

**Επιστρέφει** το διαχειριστή HeaderFooter της παρουσίασης. **Μόνο-ανάγνωση** [IPresentationHeaderFooterManager](../../com.aspose.slides/ipresentationheaderfootermanager).

**Επιστρέφει:**
[IPresentationHeaderFooterManager](../../com.aspose.slides/ipresentationheaderfootermanager)

### getProtectionManager() {#getProtectionManager--}
```
public abstract IProtectionManager getProtectionManager()
```

**Λαμβάνει** το διαχειριστή των αδειών για αυτήν την παρουσίαση. **Μόνο-ανάγνωση** [IProtectionManager](../../com.aspose.slides/iprotectionmanager).

**Επιστρέφει:**
[IProtectionManager](../../com.aspose.slides/iprotectionmanager)

### getSlides() {#getSlides--}
```
public abstract ISlideCollection getSlides()
```

**Επιστρέφει** λίστα με όλες τις διαφάνειες που ορίζονται στην παρουσίαση. **Μόνο-ανάγνωση** [ISlideCollection](../../com.aspose.slides/islidecollection).

**Επιστρέφει:**
[ISlideCollection](../../com.aspose.slides/islidecollection)

### getSections() {#getSections--}
```
public abstract ISectionCollection getSections()
```

**Επιστρέφει** λίστα με όλες τις ενότητες διαφανειών που ορίζονται στην παρουσίαση. **Μόνο-ανάγνωση** [ISectionCollection](../../com.aspose.slides/isectioncollection).

**Επιστρέφει:**
[ISectionCollection](../../com.aspose.slides/isectioncollection)

### getSlideSize() {#getSlideSize--}
```
public abstract ISlideSize getSlideSize()
```

**Επιστρέφει** αντικείμενο μεγέθους διαφάνειας. **Μόνο-ανάγνωση** [ISlideSize](../../com.aspose.slides/islidesize).

**Επιστρέφει:**
[ISlideSize](../../com.aspose.slides/islidesize)

### getNotesSize() {#getNotesSize--}
```
public abstract INotesSize getNotesSize()
```

**Επιστρέφει** αντικείμενο μεγέθους διαφάνειας σημειώσεων. **Μόνο-ανάγνωση** [INotesSize](../../com.aspose.slides/inotessize).

**Επιστρέφει:**
[INotesSize](../../com.aspose.slides/inotessize)

### getLayoutSlides() {#getLayoutSlides--}
```
public abstract IGlobalLayoutSlideCollection getLayoutSlides()
```

**Επιστρέφει** λίστα με όλες τις διαφάνειες διάταξης που ορίζονται στην παρουσίαση. **Μόνο-ανάγνωση** [IGlobalLayoutSlideCollection](../../com.aspose.slides/igloballayoutslidecollection).

--------------------

Μπορείτε να έχετε πρόσβαση σε εναλλακτικό API για προσθήκη/εισαγωγή/αφαίρεση/κλωνοποίηση διαφανειών διάταξης χρησιμοποιώντας την ιδιότητα IMasterSlide.LayoutSlides.

**Επιστρέφει:**
[IGlobalLayoutSlideCollection](../../com.aspose.slides/igloballayoutslidecollection)

### getMasters() {#getMasters--}
```
public abstract IMasterSlideCollection getMasters()
```

**Επιστρέφει** λίστα με όλες τις κύριες διαφάνειες που ορίζονται στην παρουσίαση. **Μόνο-ανάγνωση** [IMasterSlideCollection](../../com.aspose.slides/imasterslidecollection).

**Επιστρέφει:**
[IMasterSlideCollection](../../com.aspose.slides/imasterslidecollection)

### getMasterNotesSlideManager() {#getMasterNotesSlideManager--}
```
public abstract IMasterNotesSlideManager getMasterNotesSlideManager()
```

**Επιστρέφει** το διαχειριστή notes master. **Μόνο-ανάγνωση** [IMasterNotesSlideManager](../../com.aspose.slides/imasternotesslidemanager).

**Επιστρέφει:**
[IMasterNotesSlideManager](../../com.aspose.slides/imasternotesslidemanager)

### getMasterHandoutSlideManager() {#getMasterHandoutSlideManager--}
```
public abstract IMasterHandoutSlideManager getMasterHandoutSlideManager()
```

**Επιστρέφει** το διαχειριστή handout master. **Μόνο-ανάγνωση** [IMasterHandoutSlideManager](../../com.aspose.slides/imasterhandoutslidemanager).

**Επιστρέφει:**
[IMasterHandoutSlideManager](../../com.aspose.slides/imasterhandoutslidemanager)

### getFontsManager() {#getFontsManager--}
```
public abstract IFontsManager getFontsManager()
```

**Επιστρέφει** το διαχειριστή γραμματοσειρών. **Μόνο-ανάγνωση** [IFontsManager](../../com.aspose.slides/ifontsmanager).

**Επιστρέφει:**
[IFontsManager](../../com.aspose.slides/ifontsmanager)

### getDefaultTextStyle() {#getDefaultTextStyle--}
```
public abstract ITextStyle getDefaultTextStyle()
```

**Επιστρέφει** το προεπιλεγμένο στυλ κειμένου για σχήματα. **Μόνο-ανάγνωση** [ITextStyle](../../com.aspose.slides/itextstyle).

**Επιστρέφει:**
[ITextStyle](../../com.aspose.slides/itextstyle)

### getCommentAuthors() {#getCommentAuthors--}
```
public abstract ICommentAuthorCollection getCommentAuthors()
```

**Επιστρέφει** τη συλλογή των συγγραφέων σχολίων. **Μόνο-ανάγνωση** [ICommentAuthorCollection](../../com.aspose.slides/icommentauthorcollection).

**Επιστρέφει:**
[ICommentAuthorCollection](../../com.aspose.slides/icommentauthorcollection)

### getDocumentProperties() {#getDocumentProperties--}
```
public abstract IDocumentProperties getDocumentProperties()
```

**Επιστρέφει** το αντικείμενο DocumentProperties που περιέχει τυπικές και προσαρμοσμένες ιδιότητες εγγράφου. **Μόνο-ανάγνωση** [IDocumentProperties](../../com.aspose.slides/idocumentproperties).

**Επιστρέφει:**
[IDocumentProperties](../../com.aspose.slides/idocumentproperties)

### getImages() {#getImages--}
```
public abstract IImageCollection getImages()
```

**Επιστρέφει** τη συλλογή όλων των εικόνων στην παρουσίαση. **Μόνο-ανάγνωση** [IImageCollection](../../com.aspose.slides/iimagecollection).

**Επιστρέφει:**
[IImageCollection](../../com.aspose.slides/iimagecollection)

### getAudios() {#getAudios--}
```
public abstract IAudioCollection getAudios()
```

**Επιστρέφει** τη συλλογή όλων των ενσωματωμένων αρχείων ήχου στην παρουσίαση. **Μόνο-ανάγνωση** [IAudioCollection](../../com.aspose.slides/iaudiocollection).

**Επιστρέφει:**
[IAudioCollection](../../com.aspose.slides/iaudiocollection)

### getVideos() {#getVideos--}
```
public abstract IVideoCollection getVideos()
```

**Επιστρέφει** τη συλλογή όλων των ενσωματωμένων αρχείων βίντεο στην παρουσίαση. **Μόνο-ανάγνωση** [IVideoCollection](../../com.aspose.slides/ivideocollection).

**Επιστρέφει:**
[IVideoCollection](../../com.aspose.slides/ivideocollection)

### getCustomData() {#getCustomData--}
```
public abstract ICustomData getCustomData()
```

**Επιστρέφει** τα προσαρμοσμένα δεδομένα της παρουσίασης. **Μόνο-ανάγνωση** [ICustomData](../../com.aspose.slides/icustomdata).

**Επιστρέφει:**
[ICustomData](../../com.aspose.slides/icustomdata)

### getVbaProject() {#getVbaProject--}
``` 
public abstract IVbaProject getVbaProject()
```

**Λαμβάνει** το VBA project με μακροεντολές παρουσίασης. **Ανάγνωση/εγγραφή** [IVbaProject](../../com.aspose.slides/ivbaproject).

**Επιστρέφει:**
[IVbaProject](../../com.aspose.slides/ivbaproject)

### setVbaProject(IVbaProject value) {#setVbaProject-com.aspose.slides.IVbaProject-}
```
public abstract void setVbaProject(IVbaProject value)
```

**Λαμβάνει** το VBA project με μακροεντολές παρουσίασης. **Ανάγνωση/εγγραφή** [IVbaProject](../../com.aspose.slides/ivbaproject).

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | [IVbaProject](../../com.aspose.slides/ivbaproject) |  |

### getSourceFormat() {#getSourceFormat--}
```
public abstract int getSourceFormat()
```

**Επιστρέφει** πληροφορίες σχετικά με τη μορφή από την οποία φορτώθηκε η παρουσίαση. **Μόνο-ανάγνωση** [SourceFormat](../../com.aspose.slides/sourceformat).

**Επιστρέφει:**
int

### getMasterTheme() {#getMasterTheme--}
```
public abstract IMasterTheme getMasterTheme()
```

**Επιστρέφει** το κύριο θέμα της παρουσίασης. **Μόνο-ανάγνωση** [IMasterTheme](../../com.aspose.slides/imastertheme).

**Επιστρέφει:**
[IMasterTheme](../../com.aspose.slides/imastertheme)

### getHyperlinkQueries() {#getHyperlinkQueries--}
```
public abstract IHyperlinkQueries getHyperlinkQueries()
```

**Παρέχει** εύκολη πρόσβαση σε όλους τους υπερσυνδέσμους που περιέχονται σε όλες τις διαφάνειες παρουσίασης (εκτός από master, layout, notes). **Μόνο-ανάγνωση** [IHyperlinkQueries](../../com.aspose.slides/ihyperlinkqueries).

**Επιστρέφει:**
[IHyperlinkQueries](../../com.aspose.slides/ihyperlinkqueries)

### getViewProperties() {#getViewProperties--}
```
public abstract IViewProperties getViewProperties()
```

**Λαμβάνει** τις γενικές ιδιότητες προβολής της παρουσίασης. **Μόνο-ανάγνωση** [IViewProperties](../../com.aspose.slides/iviewproperties).

**Επιστρέφει:**
[IViewProperties](../../com.aspose.slides/iviewproperties)

### getFirstSlideNumber() {#getFirstSlideNumber--}
```
public abstract int getFirstSlideNumber()
```

**Αναπαριστά** τον αριθμό της πρώτης διαφάνειας στην παρουσίαση. **Ανάγνωση/εγγραφή** int.

**Επιστρέφει:**
int

### setFirstSlideNumber(int value) {#setFirstSlideNumber-int-}
```
public abstract void setFirstSlideNumber(int value)
```

**Αναπαριστά** τον αριθμό της πρώτης διαφάνειας στην παρουσίαση. **Ανάγνωση/εγγραφή** int.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | int |  |

### getAllCustomXmlParts() {#getAllCustomXmlParts--}
```
public abstract ICustomXmlPart[] getAllCustomXmlParts()
```

**Επιστρέφει** όλα τα προσαρμοσμένα τμήματα δεδομένων στην παρουσίαση. **Μόνο-ανάγνωση** ICustomXmlPart[].

**Επιστρέφει:**
com.aspose.slides.ICustomXmlPart[]

### getDigitalSignatures() {#getDigitalSignatures--}
```
public abstract IDigitalSignatureCollection getDigitalSignatures()
```

**Επιστρέφει** τη συλλογή των ψηφιακών υπογραφών που χρησιμοποιήθηκαν για την υπογραφή της παρουσίασης. **Μόνο-ανάγνωση** [IDigitalSignatureCollection](../../com.aspose.slides/idigitalsignaturecollection).

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
>                    + signature.getSignTime().toString() + " -- " + (signature.isValid() ? "VALID" : "INVALID"));
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

### getSensitivityLabels() {#getSensitivityLabels--}
```
public abstract ISensitivityLabelCollection getSensitivityLabels()
```

**Επιστρέφει** τη συλλογή των ετικετών ευαισθησίας που εφαρμόστηκαν στο έγγραφο παρουσίασης. **Μόνο-ανάγνωση** [ISensitivityLabelCollection](../../com.aspose.slides/isensitivitylabelcollection).

--------------------

> ```
> Presentation pres = new Presentation("SomePresentation.pptx");
>  try {
>      ISensitivityLabelCollection sensitivityLabels = pres.getSensitivityLabels();
> 
>      // Εκτύπωση των εφαρμοσμένων ετικετών
>      for (ISensitivityLabel sensitivityLabel : sensitivityLabels)
>          System.out.println("Label Id " + sensitivityLabel.getId() + " from Azure AD site " + sensitivityLabel.getSiteId());
> 
>      // Προσθήκη της νέας ετικέτας
>      String labelIdString = "{xxxxxxxx-xxxx-xxxx-xxxx-xxxxxxxxxxxx}"; // Λάβετε το αναγνωριστικό της ετικέτας ευαισθησίας από την πολιτική
>      UUID siteIdGuid = UUID.fromString("{xxxxxxxx-xxxx-xxxx-xxxx-xxxxxxxxxxxx}"); // Λάβετε το αναγνωριστικό του Azure AD site από την πολιτική
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

### save(String fname, int format) {#save-java.lang.String-int-}
```
public abstract void save(String fname, int format)
```

**Αποθηκεύει** όλες τις διαφάνειες μιας παρουσίασης σε αρχείο με την καθορισμένη μορφή.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| fname | java.lang.String | Διαδρομή προς το δημιουργημένο αρχείο. |
| format | int | Μορφή των εξαγόμενων δεδομένων. |

### save(OutputStream stream, int format) {#save-java.io.OutputStream-int-}
```
public abstract void save(OutputStream stream, int format)
```

**Αποθηκεύει** όλες τις διαφάνειες μιας παρουσίασης σε ροή (stream) με την καθορισμένη μορφή.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| stream | java.io.OutputStream | Ροή εξόδου. |
| format | int | Μορφή των εξαγόμενων δεδομένων. |

### save(String fname, int format, ISaveOptions options) {#save-java.lang.String-int-com.aspose.slides.ISaveOptions-}
```
public abstract void save(String fname, int format, ISaveOptions options)
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
public abstract void save(OutputStream stream, int format, ISaveOptions options)
```

Αποθηκεύει όλες τις διαφάνειες μιας παρουσίασης σε ροή σε καθορισμένη μορφή και με πρόσθετες επιλογές.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| stream | java.io.OutputStream | Ροή εξόδου. |
| format | int | Μορφή των εξαγόμενων δεδομένων. |
| options | [ISaveOptions](../../com.aspose.slides/isaveoptions) | Πρόσθετες επιλογές μορφής. |

### save(String fname, int[] slides, int format) {#save-java.lang.String-int---int-}
```
public abstract void save(String fname, int[] slides, int format)
```

Αποθηκεύει καθορισμένες διαφάνειες μιας παρουσίασης σε αρχείο με την καθορισμένη μορφή.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| fname | java.lang.String | Διαδρομή του δημιουργημένου αρχείου. |
| slides | int[] | Πίνακας με τις θέσεις των διαφανειών, ξεκινώντας από το 1. |
| format | int | Μορφή των εξαγόμενων δεδομένων. |

### save(String fname, int[] slides, int format, ISaveOptions options) {#save-java.lang.String-int---int-com.aspose.slides.ISaveOptions-}
```
public abstract void save(String fname, int[] slides, int format, ISaveOptions options)
```

Αποθηκεύει καθορισμένες διαφάνειες μιας παρουσίασης σε αρχείο με την καθορισμένη μορφή.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| fname | java.lang.String | Διαδρομή του δημιουργημένου αρχείου. |
| slides | int[] | Πίνακας με τις θέσεις των διαφανειών, ξεκινώντας από το 1. |
| format | int | Μορφή των εξαγόμενων δεδομένων. |
| options | [ISaveOptions](../../com.aspose.slides/isaveoptions) | Πρόσθετες επιλογές μορφής. |

### save(OutputStream stream, int[] slides, int format) {#save-java.io.OutputStream-int---int-}
```
public abstract void save(OutputStream stream, int[] slides, int format)
```

Αποθηκεύει καθορισμένες διαφάνειες μιας παρουσίασης σε ροή στην καθορισμένη μορφή.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| stream | java.io.OutputStream | Ροή εξόδου. |
| slides | int[] | Πίνακας με τις θέσεις των διαφανειών, ξεκινώντας από το 1. |
| format | int | Μορφή των εξαγόμενων δεδομένων. |

### save(OutputStream stream, int[] slides, int format, ISaveOptions options) {#save-java.io.OutputStream-int---int-com.aspose.slides.ISaveOptions-}
```
public abstract void save(OutputStream stream, int[] slides, int format, ISaveOptions options)
```

Αποθηκεύει καθορισμένες διαφάνειες μιας παρουσίασης σε ροή στην καθορισμένη μορφή.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| stream | java.io.OutputStream | Ροή εξόδου. |
| slides | int[] | Πίνακας με τις θέσεις των διαφανειών, ξεκινώντας από το 1. |
| format | int | Μορφή των εξαγόμενων δεδομένων. |
| options | [ISaveOptions](../../com.aspose.slides/isaveoptions) | Πρόσθετες επιλογές μορφής. |

### save(IXamlOptions options) {#save-com.aspose.slides.IXamlOptions-}
```
public abstract void save(IXamlOptions options)
```

Αποθηκεύει όλες τις διαφάνειες μιας παρουσίασης σε σύνολο αρχείων που αντιπροσωπεύουν σήμανση XAML.

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
public abstract IImage[] getImages(IRenderingOptions options)
```

Επιστρέφει αντικείμενα Thumbnail Image για όλες τις διαφάνειες μιας παρουσίασης.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| options | [IRenderingOptions](../../com.aspose.slides/irenderingoptions) | Επιλογές απόδοσης. |

**Επιστρέφει:**
com.aspose.slides.IImage[] - IImage objects.

### getImages(IRenderingOptions options, int[] slides) {#getImages-com.aspose.slides.IRenderingOptions-int---}
```
public abstract IImage[] getImages(IRenderingOptions options, int[] slides)
```

Επιστρέφει αντικείμενα Thumbnail IImage για καθορισμένες διαφάνειες μιας παρουσίασης.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| options | [IRenderingOptions](../../com.aspose.slides/irenderingoptions) | Επιλογές απόδοσης. |
| slides | int[] | Πίνακας με τις θέσεις των διαφανειών, ξεκινώντας από το 1. |

**Επιστρέφει:**
com.aspose.slides.IImage[] - IImage objects.

### getImages(IRenderingOptions options, float scaleX, float scaleY) {#getImages-com.aspose.slides.IRenderingOptions-float-float-}
```
public abstract IImage[] getImages(IRenderingOptions options, float scaleX, float scaleY)
```

Επιστρέφει αντικείμενα Thumbnail Image για όλες τις διαφάνειες μιας παρουσίασης με προσαρμοσμένη κλιμάκωση.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| options | [IRenderingOptions](../../com.aspose.slides/irenderingoptions) | Επιλογές απόδοσης. |
| scaleX | float | Η τιμή με την οποία κλιμακώνεται αυτό το Thumbnail στην κατεύθυνση του άξονα x. |
| scaleY | float | Η τιμή με την οποία κλιμακώνεται αυτό το Thumbnail στην κατεύθυνση του άξονα y. |

**Επιστρέφει:**
com.aspose.slides.IImage[] - Bitmap objects.

### getImages(IRenderingOptions options, int[] slides, float scaleX, float scaleY) {#getImages-com.aspose.slides.IRenderingOptions-int---float-float-}
```
public abstract IImage[] getImages(IRenderingOptions options, int[] slides, float scaleX, float scaleY)
```

Επιστρέφει αντικείμενα Thumbnail Image για καθορισμένες διαφάνειες μιας παρουσίασης με προσαρμοσμένη κλιμάκωση.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| options | [IRenderingOptions](../../com.aspose.slides/irenderingoptions) | Επιλογές απόδοσης. |
| slides | int[] | Πίνακας με τις θέσεις των διαφανειών, ξεκινώντας από το 1. |
| scaleX | float | Η τιμή με την οποία κλιμακώνεται αυτό το Thumbnail στην κατεύθυνση του άξονα x. |
| scaleY | float | Η τιμή με την οποία κλιμακώνεται αυτό το Thumbnail στην κατεύθυνση του άξονα y. |

**Επιστρέφει:**
com.aspose.slides.IImage[] - IImage objects.

### getImages(IRenderingOptions options, Dimension imageSize) {#getImages-com.aspose.slides.IRenderingOptions-java.awt.Dimension-}
```
public abstract IImage[] getImages(IRenderingOptions options, Dimension imageSize)
```

Επιστρέφει αντικείμενα Thumbnail Image για όλες τις διαφάνειες μιας παρουσίασης με καθορισμένο μέγεθος.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| options | [IRenderingOptions](../../com.aspose.slides/irenderingoptions) | Επιλογές απόδοσης. |
| imageSize | java.awt.Dimension | Μέγεθος της εικόνας που θα δημιουργηθεί. |

**Επιστρέφει:**
com.aspose.slides.IImage[] - IImage objects.

### getImages(IRenderingOptions options, int[] slides, Dimension imageSize) {#getImages-com.aspose.slides.IRenderingOptions-int---java.awt.Dimension-}
```
public abstract IImage[] getImages(IRenderingOptions options, int[] slides, Dimension imageSize)
```

Επιστρέφει αντικείμενα Thumbnail Image για καθορισμένες διαφάνειες μιας παρουσίασης με καθορισμένο μέγεθος.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| options | [IRenderingOptions](../../com.aspose.slides/irenderingoptions) | Επιλογές απόδοσης. |
| slides | int[] | Πίνακας με τις θέσεις των διαφανειών, ξεκινώντας από το 1. |
| imageSize | java.awt.Dimension | Μέγεθος της εικόνας που θα δημιουργηθεί. |

**Επιστρέφει:**
com.aspose.slides.IImage[] - IImage objects.

### getSlideById(long id) {#getSlideById-long-}
```
public abstract IBaseSlide getSlideById(long id)
```

Επιστρέφει ένα Slide, MasterSlide ή LayoutSlide κατά Id.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| id | long | Id μιας διαφάνειας. |

**Επιστρέφει:**
[IBaseSlide](../../com.aspose.slides/ibaseslide) - IBaseSlide object.

### joinPortionsWithSameFormatting() {#joinPortionsWithSameFormatting--}
```
public abstract void joinPortionsWithSameFormatting()
```

Συνδυάζει τμήματα με την ίδια μορφοποίηση σε όλες τις παραγράφους σε όλα τα αποδεκτά σχήματα σε όλες τις διαφάνειες.

### highlightText(String text, Color highlightColor) {#highlightText-java.lang.String-java.awt.Color-}
```
public abstract void highlightText(String text, Color highlightColor)
```

Τονίζει όλες τις αντιστοιχίες του δείγματος κειμένου με το καθορισμένο χρώμα.

--------------------

> ```
> The following code sample shows how to highlight text in a PowerPoint presentation.
>  
>  Presentation presentation = new Presentation("SomePresentation.pptx");
>  try {
>      // επισήμανση όλων των ξεχωριστών εμφανίσεων του 'the'
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
| highlightColor | java.awt.Color | Το χρώμα για την επισήμανση του κειμένου. |

### highlightText(String text, Color highlightColor, ITextSearchOptions options, IFindResultCallback callback) {#highlightText-java.lang.String-java.awt.Color-com.aspose.slides.ITextSearchOptions-com.aspose.slides.IFindResultCallback-}
```
public abstract void highlightText(String text, Color highlightColor, ITextSearchOptions options, IFindResultCallback callback)
```

Τονίζει όλες τις αντιστοιχίες του δείγματος κειμένου με το καθορισμένο χρώμα.

--------------------

> ```
> The following code sample shows how to highlight text in a PowerPoint presentation.
>  
>  Presentation presentation = new Presentation("SomePresentation.pptx");
>  try {
>      // επισήμανση όλων των ξεχωριστών εμφανίσεων του 'the'
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
| highlightColor | java.awt.Color | Το χρώμα για την επισήμανση του κειμένου. |
| options | [ITextSearchOptions](../../com.aspose.slides/itextsearchoptions) | Επιλογές αναζήτησης κειμένου [ITextSearchOptions](../../com.aspose.slides/itextsearchoptions). |
| callback | [IFindResultCallback](../../com.aspose.slides/ifindresultcallback) | Το αντικείμενο callback για τη λήψη αποτελεσμάτων αναζήτησης [IFindResultCallback](../../com.aspose.slides/ifindresultcallback). |

### highlightRegex(Pattern regex, Color highlightColor, IFindResultCallback callback) {#highlightRegex-java.util.regex.Pattern-java.awt.Color-com.aspose.slides.IFindResultCallback-}
```
public abstract void highlightRegex(Pattern regex, Color highlightColor, IFindResultCallback callback)
```

Τονίζει όλες τις αντιστοιχίες της κανονικής έκφρασης με το καθορισμένο χρώμα.

--------------------

> ```
> The following code sample shows how to highlight text in a PowerPoint Presentation using a regular expression.
>  
>  Presentation presentation = new Presentation("SomePresentation.pptx");
>  try {
>      // επισήμανση όλων των ξεχωριστών εμφανίσεων του 'the'
>      presentation.highlightText("the", Color.MAGENTA);
>      presentation.save("SomePresentation-out2.pptx", SaveFormat.Pptx);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```


**Παράμετρος:**  
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| regex | java.util.regex.Pattern | Η κανονική έκφραση java.util.regex.Pattern για την απόκτηση των συμβολοσειρών προς επισήμανση. |
| highlightColor | java.awt.Color | Το χρώμα για την επισήμανση του κειμένου. |
| callback | [IFindResultCallback](../../com.aspose.slides/ifindresultcallback) | Το αντικείμενο callback για τη λήψη αποτελεσμάτων αναζήτησης [IFindResultCallback](../../com.aspose.slides/ifindresultcallback). |

### replaceText(String oldText, String newText, ITextSearchOptions options, IFindResultCallback callback) {#replaceText-java.lang.String-java.lang.String-com.aspose.slides.ITextSearchOptions-com.aspose.slides.IFindResultCallback-}
```
public abstract void replaceText(String oldText, String newText, ITextSearchOptions options, IFindResultCallback callback)
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
>      // Αντικατάσταση όλων των ξεχωριστών εμφανίσεων του 'the' με '***'
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
| newText | java.lang.String | Η συμβολοσειρά για την αντικατάσταση όλων των εμφανίσεων του oldText. |
| options | [ITextSearchOptions](../../com.aspose.slides/itextsearchoptions) | Επιλογές αναζήτησης κειμένου [ITextSearchOptions](../../com.aspose.slides/itextsearchoptions). |
| callback | [IFindResultCallback](../../com.aspose.slides/ifindresultcallback) | Το αντικείμενο callback για τη λήψη αποτελεσμάτων αναζήτησης [IFindResultCallback](../../com.aspose.slides/ifindresultcallback). |

### replaceRegex(Pattern regex, String newText, IFindResultCallback callback) {#replaceRegex-java.util.regex.Pattern-java.lang.String-com.aspose.slides.IFindResultCallback-}
```
public abstract void replaceRegex(Pattern regex, String newText, IFindResultCallback callback)
```

Αντικαθιστά όλες τις αντιστοιχίες της κανονικής έκφρασης με τη συγκεκριμένη συμβολοσειρά.

--------------------

> ```
> The following code sample shows how to replace text using regular expression with the specified string.
>  
>  Presentation presentation = new Presentation("SomePresentation.pptx")
>  try {
>      TextSearchOptions textSearchOptions = new TextSearchOptions();
>      textSearchOptions.setWholeWordsOnly(true);
>      // Αντικατάσταση όλων των ξεχωριστών εμφανίσεων του 'the' με '***'
>      presentation.replaceText("the", "***", textSearchOptions, null);
>      presentation.save("SomePresentation-out2.pptx", SaveFormat.Pptx);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```


**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| regex | java.util.regex.Pattern | Η κανονική έκφραση java.util.regex.Pattern για την απόκτηση των συμβολοσειρών προς αντικατάσταση. |
| newText | java.lang.String | Η συμβολοσειρά για την αντικατάσταση όλων των εμφανίσεων των συμβολοσειρών που θα αντικατασταθούν. |
| callback | [IFindResultCallback](../../com.aspose.slides/ifindresultcallback) | Το αντικείμενο callback για τη λήψη αποτελεσμάτων αναζήτησης [IFindResultCallback](../../com.aspose.slides/ifindresultcallback). |

### refreshChartsData() {#refreshChartsData--}
```
public abstract void refreshChartsData()
```

Επαναφορτώνει τα δεδομένα για όλα τα γραφήματα στην παρουσίαση από τα βιβλία εργασίας προέλευσης.

--------------------

> ```
> Presentation presentation = new Presentation("PresentationWithCharts.pptx");
>  try {
>      presentation.refreshChartsData();
>      presentation.save("PresentationWithCharts-out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```


### refreshChartsData(boolean skipFailedCharts) {#refreshChartsData-boolean-}
```
public abstract void refreshChartsData(boolean skipFailedCharts)
```

Επαναφορτώνει τα δεδομένα για όλα τα γραφήματα στην παρουσίαση από τα βιβλία εργασίας προέλευσης.

--------------------

> ```
> Presentation presentation = new Presentation("PresentationWithCharts.pptx");
>  try {
>      presentation.refreshChartsData();
>      presentation.save("PresentationWithCharts-out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```


**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| skipFailedCharts | boolean | Καθορίζει αν η διαδικασία ανανέωσης συνεχίζεται εάν ένα γράφημα αποτύχει να ενημερωθεί. Εάν true, τα γραφήματα που προκαλούν εξαίρεση παραλείπονται· διαφορετικά η εξαίρεση προωθείται. |