---
title: IPresentation
second_title: Aspose.Slides για Android μέσω Αναφοράς API Java
description: Έγγραφο παρουσίασης
type: docs
url: /el/com.aspose.slides/ipresentation/
---
**All Implemented Interfaces:**
[com.aspose.slides.IPresentationComponent](../../com.aspose.slides/ipresentationcomponent), com.aspose.ms.System.IDisposable
```
public interface IPresentation extends IPresentationComponent, System.IDisposable
```

Έγγραφο παρουσίασης
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [getCurrentDateTime()](#getCurrentDateTime--) | Επιστρέφει ή ορίζει την ημερομηνία και ώρα που θα αντικαταστήσει το περιεχόμενο των πεδίων datetime. |
| [setCurrentDateTime(Date value)](#setCurrentDateTime-java.util.Date-) | Επιστρέφει ή ορίζει την ημερομηνία και ώρα που θα αντικαταστήσει το περιεχόμενο των πεδίων datetime. |
| [getHeaderFooterManager()](#getHeaderFooterManager--) | Επιστρέφει τον διαχειριστή HeaderFooter της παρουσίασης. |
| [getProtectionManager()](#getProtectionManager--) | Λαμβάνει τον διαχειριστή των δικαιωμάτων για αυτήν την παρουσίαση. |
| [getSlides()](#getSlides--) | Επιστρέφει λίστα με όλες τις διαφάνειες που ορίζονται στην παρουσίαση. |
| [getSections()](#getSections--) | Επιστρέφει λίστα με όλες τις ενότητες διαφανειών που ορίζονται στην παρουσίαση. |
| [getSlideSize()](#getSlideSize--) | Επιστρέφει το αντικείμενο μεγέθους διαφάνειας. |
| [getNotesSize()](#getNotesSize--) | Επιστρέφει το αντικείμενο μεγέθους διαφάνειας σημειώσεων. |
| [getLayoutSlides()](#getLayoutSlides--) | Επιστρέφει λίστα με όλες τις διαφάνειες διάταξης που ορίζονται στην παρουσίαση. |
| [getMasters()](#getMasters--) | Επιστρέφει λίστα με όλες τις κύριες διαφάνειες που ορίζονται στην παρουσίαση. |
| [getMasterNotesSlideManager()](#getMasterNotesSlideManager--) | Επιστρέφει τον διαχειριστή κύριων σημειώσεων. |
| [getMasterHandoutSlideManager()](#getMasterHandoutSlideManager--) | Επιστρέφει τον διαχειριστή κύριων φυλλαδίων. |
| [getFontsManager()](#getFontsManager--) | Επιστρέφει τον διαχειριστή γραμματοσειρών. |
| [getDefaultTextStyle()](#getDefaultTextStyle--) | Επιστρέφει το προεπιλεγμένο στυλ κειμένου για σχήματα. |
| [getCommentAuthors()](#getCommentAuthors--) | Επιστρέφει τη συλλογή των συγγραφέων σχολίων. |
| [getDocumentProperties()](#getDocumentProperties--) | Επιστρέφει το αντικείμενο DocumentProperties που περιέχει τις τυπικές και προσαρμοσμένες ιδιότητες του εγγράφου. |
| [getImages()](#getImages--) | Επιστρέφει τη συλλογή όλων των εικόνων στην παρουσίαση. |
| [getAudios()](#getAudios--) | Επιστρέφει τη συλλογή όλων των ενσωματωμένων αρχείων ήχου στην παρουσίαση. |
| [getVideos()](#getVideos--) | Επιστρέφει τη συλλογή όλων των ενσωματωμένων αρχείων βίντεο στην παρουσίαση. |
| [getCustomData()](#getCustomData--) | Επιστρέφει τα προσαρμοσμένα δεδομένα της παρουσίασης. |
| [getVbaProject()](#getVbaProject--) | Λαμβάνει το έργο VBA με μακροεντολές παρουσίασης. |
| [setVbaProject(IVbaProject value)](#setVbaProject-com.aspose.slides.IVbaProject-) | Λαμβάνει το έργο VBA με μακροεντολές παρουσίασης. |
| [getSourceFormat()](#getSourceFormat--) | Επιστρέφει πληροφορίες σχετικά με τη μορφή από την οποία φορτώθηκε η παρουσίαση. |
| [getMasterTheme()](#getMasterTheme--) | Επιστρέφει το κύριο θέμα της παρουσίασης. |
| [getHyperlinkQueries()](#getHyperlinkQueries--) | Παρέχει εύκολη πρόσβαση σε όλους τους υπερσυνδέσμους που περιέχονται σε όλες τις διαφάνειες της παρουσίασης (εκτός από τις κύριες, διατάξεις, διαφάνειες σημειώσεων). |
| [getViewProperties()](#getViewProperties--) | Λαμβάνει τις ιδιότητες προβολής για ολόκληρη την παρουσίαση. |
| [getFirstSlideNumber()](#getFirstSlideNumber--) | Αναπαριστά τον αριθμό της πρώτης διαφάνειας στην παρουσίαση. |
| [setFirstSlideNumber(int value)](#setFirstSlideNumber-int-) | Αναπαριστά τον αριθμό της πρώτης διαφάνειας στην παρουσίαση. |
| [getAllCustomXmlParts()](#getAllCustomXmlParts--) | Επιστρέφει όλα τα προσαρμοσμένα τμήματα δεδομένων στην παρουσίαση. |
| [getDigitalSignatures()](#getDigitalSignatures--) | Επιστρέφει τη συλλογή των υπογραφών που χρησιμοποιήθηκαν για την υπογραφή της παρουσίασης. |
| [getSensitivityLabels()](#getSensitivityLabels--) | Επιστρέφει τη συλλογή των ετικετών ευαισθησίας που εφαρμόζονται στο έγγραφο της παρουσίασης. |
| [save(String fname, int format)](#save-java.lang.String-int-) | Αποθηκεύει όλες τις διαφάνειες μιας παρουσίασης σε αρχείο με τη συγκεκριμένη μορφή. |
| [save(OutputStream stream, int format)](#save-java.io.OutputStream-int-) | Αποθηκεύει όλες τις διαφάνειες μιας παρουσίασης σε ροή με τη συγκεκριμένη μορφή. |
| [save(String fname, int format, ISaveOptions options)](#save-java.lang.String-int-com.aspose.slides.ISaveOptions-) | Αποθηκεύει όλες τις διαφάνειες μιας παρουσίασης σε αρχείο με τη συγκεκριμένη μορφή και με πρόσθετες επιλογές. |
| [save(OutputStream stream, int format, ISaveOptions options)](#save-java.io.OutputStream-int-com.aspose.slides.ISaveOptions-) | Αποθηκεύει όλες τις διαφάνειες μιας παρουσίασης σε ροή με τη συγκεκριμένη μορφή και με πρόσθετες επιλογές. |
| [save(String fname, int[] slides, int format)](#save-java.lang.String-int---int-) | Αποθηκεύει τις καθορισμένες διαφάνειες μιας παρουσίασης σε αρχείο με τη συγκεκριμένη μορφή. |
| [save(String fname, int[] slides, int format, ISaveOptions options)](#save-java.lang.String-int---int-com.aspose.slides.ISaveOptions-) | Αποθηκεύει τις καθορισμένες διαφάνειες μιας παρουσίασης σε αρχείο με τη συγκεκριμένη μορφή. |
| [save(OutputStream stream, int[] slides, int format)](#save-java.io.OutputStream-int---int-) | Αποθηκεύει τις καθορισμένες διαφάνειες μιας παρουσίασης σε ροή με τη συγκεκριμένη μορφή. |
| [save(OutputStream stream, int[] slides, int format, ISaveOptions options)](#save-java.io.OutputStream-int---int-com.aspose.slides.ISaveOptions-) | Αποθηκεύει τις καθορισμένες διαφάνειες μιας παρουσίασης σε ροή με τη συγκεκριμένη μορφή. |
| [save(IXamlOptions options)](#save-com.aspose.slides.IXamlOptions-) | Αποθηκεύει όλες τις διαφάνειες μιας παρουσίασης σε σύνολο αρχείων που αντιπροσωπεύουν σήμανση XAML. |
| [getImages(IRenderingOptions options)](#getImages-com.aspose.slides.IRenderingOptions-) | Επιστρέφει αντικείμενα Εικόνας Μικρογραφίας για όλες τις διαφάνειες μιας παρουσίασης. |
| [getImages(IRenderingOptions options, int[] slides)](#getImages-com.aspose.slides.IRenderingOptions-int---) | Επιστρέφει αντικείμενα Εικονας Μικρογραφίας για τις καθορισμένες διαφάνειες μιας παρουσίασης. |
| [getImages(IRenderingOptions options, float scaleX, float scaleY)](#getImages-com.aspose.slides.IRenderingOptions-float-float-) | Επιστρέφει αντικείμενα Εικόνας Μικρογραφίας για όλες τις διαφάνειες μιας παρουσίασης με προσαρμοσμένη κλιμάκωση. |
| [getImages(IRenderingOptions options, int[] slides, float scaleX, float scaleY)](#getImages-com.aspose.slides.IRenderingOptions-int---float-float-) | Επιστρέφει αντικείμενα Εικόνας Μικρογραφίας για τις καθορισμένες διαφάνειες μιας παρουσίασης με προσαρμοσμένη κλιμάκωση. |
| [getImages(IRenderingOptions options, Size imageSize)](#getImages-com.aspose.slides.IRenderingOptions-com.aspose.slides.android.Size-) | Επιστρέφει αντικείμενα Εικόνας Μικρογραφίας για όλες τις διαφάνειες μιας παρουσίασης με συγκεκριμένο μέγεθος. |
| [getImages(IRenderingOptions options, int[] slides, Size imageSize)](#getImages-com.aspose.slides.IRenderingOptions-int---com.aspose.slides.android.Size-) | Επιστρέφει αντικείμενα Εικόνας Μικρογραφίας για τις καθορισμένες διαφάνειες μιας παρουσίασης με συγκεκριμένο μέγεθος. |
| [getSlideById(long id)](#getSlideById-long-) | Επιστρέφει ένα Slide, MasterSlide ή LayoutSlide με βάση το Id. |
| [joinPortionsWithSameFormatting()](#joinPortionsWithSameFormatting--) | Ενώνει τμήματα κειμένου με ίδια μορφοποίηση σε όλες τις παραγράφους σε όλα τα αποδεκτά σχήματα σε όλες τις διαφάνειες. |
| [highlightText(String text, Integer highlightColor)](#highlightText-java.lang.String-java.lang.Integer-) | Επισημαίνει όλες τις αντιστοιχίες του δείγματος κειμένου με το καθορισμένο χρώμα. |
| [highlightText(String text, Integer highlightColor, ITextSearchOptions options, IFindResultCallback callback)](#highlightText-java.lang.String-java.lang.Integer-com.aspose.slides.ITextSearchOptions-com.aspose.slides.IFindResultCallback-) | Επισημαίνει όλες τις αντιστοιχίες του δείγματος κειμένου με το καθορισμένο χρώμα. |
| [highlightRegex(Pattern regex, Integer highlightColor, IFindResultCallback callback)](#highlightRegex-java.util.regex.Pattern-java.lang.Integer-com.aspose.slides.IFindResultCallback-) | Επισημαίνει όλες τις αντιστοιχίες της κανονικής έκφρασης με το καθορισμένο χρώμα. |
| [replaceText(String oldText, String newText, ITextSearchOptions options, IFindResultCallback callback)](#replaceText-java.lang.String-java.lang.String-com.aspose.slides.ITextSearchOptions-com.aspose.slides.IFindResultCallback-) | Αντικαθιστά όλες τις εμφανίσεις του καθορισμένου κειμένου με άλλο καθορισμένο κείμενο. |
| [replaceRegex(Pattern regex, String newText, IFindResultCallback callback)](#replaceRegex-java.util.regex.Pattern-java.lang.String-com.aspose.slides.IFindResultCallback-) | Αντικαθιστά όλες τις αντιστοιχίες της κανονικής έκφρασης με τη συγκεκριμένη συμβολοσειρά. |
### getCurrentDateTime() {#getCurrentDateTime--}
```
public abstract Date getCurrentDateTime()
```

Επιστρέφει ή ορίζει την ημερομηνία και ώρα που θα αντικαταστήσει το περιεχόμενο των πεδίων datetime. Ο χρόνος δημιουργίας αυτού του αντικειμένου Presentation από προεπιλογή. Ανάγνωση/εγγραφή java.util.Date.

**Επιστρέφει:**
java.util.Date
### setCurrentDateTime(Date value) {#setCurrentDateTime-java.util.Date-}
```
public abstract void setCurrentDateTime(Date value)
```

Επιστρέφει ή ορίζει την ημερομηνία και ώρα που θα αντικαταστήσει το περιεχόμενο των πεδίων datetime. Ο χρόνος δημιουργίας αυτού του αντικειμένου Presentation από προεπιλογή. Ανάγνωση/εγγραφή java.util.Date.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | java.util.Date |  |

### getHeaderFooterManager() {#getHeaderFooterManager--}
```
public abstract IPresentationHeaderFooterManager getHeaderFooterManager()
```

Επιστρέφει τον διαχειριστή HeaderFooter της παρουσίασης. Μόνο για ανάγνωση [IPresentationHeaderFooterManager](../../com.aspose.slides/ipresentationheaderfootermanager).

**Επιστρέφει:**
[IPresentationHeaderFooterManager](../../com.aspose.slides/ipresentationheaderfootermanager)
### getProtectionManager() {#getProtectionManager--}
```
public abstract IProtectionManager getProtectionManager()
```

Λαμβάνει τον διαχειριστή των δικαιωμάτων για αυτήν την παρουσίαση. Μόνο για ανάγνωση [IProtectionManager](../../com.aspose.slides/iprotectionmanager).

**Επιστρέφει:**
[IProtectionManager](../../com.aspose.slides/iprotectionmanager)
### getSlides() {#getSlides--}
```
public abstract ISlideCollection getSlides()
```

Επιστρέφει λίστα με όλες τις διαφάνειες που ορίζονται στην παρουσίαση. Μόνο για ανάγνωση [ISlideCollection](../../com.aspose.slides/islidecollection).

**Επιστρέφει:**
[ISlideCollection](../../com.aspose.slides/islidecollection)
### getSections() {#getSections--}
```
public abstract ISectionCollection getSections()
```

Επιστρέφει λίστα με όλες τις ενότητες διαφανειών που ορίζονται στην παρουσίαση. Μόνο για ανάγνωση [ISectionCollection](../../com.aspose.slides/isectioncollection).

**Επιστρέφει:**
[ISectionCollection](../../com.aspose.slides/isectioncollection)
### getSlideSize() {#getSlideSize--}
```
public abstract ISlideSize getSlideSize()
```

Επιστρέφει το αντικείμενο μεγέθους διαφάνειας. Μόνο για ανάγνωση [ISlideSize](../../com.aspose.slides/islidesize).

**Επιστρέφει:**
[ISlideSize](../../com.aspose.slides/islidesize)
### getNotesSize() {#getNotesSize--}
```
public abstract INotesSize getNotesSize()
```

Επιστρέφει το αντικείμενο μεγέθους διαφάνειας σημειώσεων. Μόνο για ανάγνωση [INotesSize](../../com.aspose.slides/inotessize).

**Επιστρέφει:**
[INotesSize](../../com.aspose.slides/inotessize)
### getLayoutSlides() {#getLayoutSlides--}
```
public abstract IGlobalLayoutSlideCollection getLayoutSlides()
```

Επιστρέφει λίστα με όλες τις διαφάνειες διάταξης που ορίζονται στην παρουσίαση. Μόνο για ανάγνωση [IGlobalLayoutSlideCollection](../../com.aspose.slides/igloballayoutslidecollection).

--------------------

Μπορείτε να έχετε πρόσβαση σε εναλλακτικό API για προσθήκη/ενσωμάτωση/αφαίρεση/κλωνοποίηση διαφανειών διάταξης χρησιμοποιώντας την ιδιότητα IMasterSlide.LayoutSlides.

**Επιστρέφει:**
[IGlobalLayoutSlideCollection](../../com.aspose.slides/igloballayoutslidecollection)
### getMasters() {#getMasters--}
```
public abstract IMasterSlideCollection getMasters()
```

Επιστρέφει λίστα με όλες τις κύριες διαφάνειες που ορίζονται στην παρουσίαση. Μόνο για ανάγνωση [IMasterSlideCollection](../../com.aspose.slides/imasterslidecollection).

**Επιστρέφει:**
[IMasterSlideCollection](../../com.aspose.slides/imasterslidecollection)
### getMasterNotesSlideManager() {#getMasterNotesSlideManager--}
```
public abstract IMasterNotesSlideManager getMasterNotesSlideManager()
```

Επιστρέφει τον διαχειριστή κύριων σημειώσεων. Μόνο για ανάγνωση [IMasterNotesSlideManager](../../com.aspose.slides/imasternotesslidemanager).

**Επιστρέφει:**
[IMasterNotesSlideManager](../../com.aspose.slides/imasternotesslidemanager)
### getMasterHandoutSlideManager() {#getMasterHandoutSlideManager--}
```
public abstract IMasterHandoutSlideManager getMasterHandoutSlideManager()
```

Επιστρέφει το διαχειριστή κύριων φυλλαδίων. Μόνο για ανάγνωση [IMasterHandoutSlideManager](../../com.aspose.slides/imasterhandoutslidemanager).

**Επιστρέφει:**
[IMasterHandoutSlideManager](../../com.aspose.slides/imasterhandoutslidemanager)
### getFontsManager() {#getFontsManager--}
```
public abstract IFontsManager getFontsManager()
```

Επιστρέφει τον διαχειριστή γραμματοσειρών. Μόνο για ανάγνωση [IFontsManager](../../com.aspose.slides/ifontsmanager).

**Επιστρέφει:**
[IFontsManager](../../com.aspose.slides/ifontsmanager)
### getDefaultTextStyle() {#getDefaultTextStyle--}
```
public abstract ITextStyle getDefaultTextStyle()
```

Επιστρέφει το προεπιλεγμένο στυλ κειμένου για σχήματα. Μόνο για ανάγνωση [ITextStyle](../../com.aspose.slides/itextstyle).

**Επιστρέφει:**
[ITextStyle](../../com.aspose.slides/itextstyle)
### getCommentAuthors() {#getCommentAuthors--}
```
public abstract ICommentAuthorCollection getCommentAuthors()
```

Επιστρέφει τη συλλογή των συγγραφέων σχολίων. Μόνο για ανάγνωση [ICommentAuthorCollection](../../com.aspose.slides/icommentauthorcollection).

**Επιστρέφει:**
[ICommentAuthorCollection](../../com.aspose.slides/icommentauthorcollection)
### getDocumentProperties() {#getDocumentProperties--}
```
public abstract IDocumentProperties getDocumentProperties()
```

Επιστρέφει το αντικείμενο DocumentProperties που περιέχει τις τυπικές και προσαρμοσμένες ιδιότητες του εγγράφου. Μόνο για ανάγνωση [IDocumentProperties](../../com.aspose.slides/idocumentproperties).

**Επιστρέφει:**
[IDocumentProperties](../../com.aspose.slides/idocumentproperties)
### getImages() {#getImages--}
```
public abstract IImageCollection getImages()
```

Επιστρέφει τη συλλογή όλων των εικόνων στην παρουσίαση. Μόνο για ανάγνωση [IImageCollection](../../com.aspose.slides/iimagecollection).

**Επιστρέφει:**
[IImageCollection](../../com.aspose.slides/iimagecollection)
### getAudios() {#getAudios--}
```
public abstract IAudioCollection getAudios()
```

Επιστρέφει τη συλλογή όλων των ενσωματωμένων αρχείων ήχου στην παρουσίαση. Μόνο για ανάγνωση [IAudioCollection](../../com.aspose.slides/iaudiocollection).

**Επιστρέφει:**
[IAudioCollection](../../com.aspose.slides/iaudiocollection)
### getVideos() {#getVideos--}
```
public abstract IVideoCollection getVideos()
```

Επιστρέφει τη συλλογή όλων των ενσωματωμένων αρχείων βίντεο στην παρουσίαση. Μόνο για ανάγνωση [IVideoCollection](../../com.aspose.slides/ivideocollection).

**Επιστρέφει:**
[IVideoCollection](../../com.aspose.slides/ivideocollection)
### getCustomData() {#getCustomData--}
```
public abstract ICustomData getCustomData()
```

Επιστρέφει τα προσαρμοσμένα δεδομένα της παρουσίασης. Μόνο για ανάγνωση [ICustomData](../../com.aspose.slides/icustomdata).

**Επιστρέφει:**
[ICustomData](../../com.aspose.slides/icustomdata)
### getVbaProject() {#getVbaProject--}
```
public abstract IVbaProject getVbaProject()
```

Λαμβάνει το έργο VBA με μακροεντολές παρουσίασης. Ανάγνωση/εγγραφή [IVbaProject](../../com.aspose.slides/ivbaproject).

**Επιστρέφει:**
[IVbaProject](../../com.aspose.slides/ivbaproject)
### setVbaProject(IVbaProject value) {#setVbaProject-com.aspose.slides.IVbaProject-}
```
public abstract void setVbaProject(IVbaProject value)
```

Λαμβάνει το έργο VBA με μακροεντολές παρουσίασης. Ανάγνωση/εγγραφή [IVbaProject](../../com.aspose.slides/ivbaproject).

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | [IVbaProject](../../com.aspose.slides/ivbaproject) |  |

### getSourceFormat() {#getSourceFormat--}
```
public abstract int getSourceFormat()
```

Επιστρέφει πληροφορίες σχετικά με τη μορφή από την οποία φορτώθηκε η παρουσίαση. Μόνο για ανάγνωση [SourceFormat](../../com.aspose.slides/sourceformat).

**Επιστρέφει:**
int
### getMasterTheme() {#getMasterTheme--}
```
public abstract IMasterTheme getMasterTheme()
```

Επιστρέφει το κύριο θέμα της παρουσίασης. Μόνο για ανάγνωση [IMasterTheme](../../com.aspose.slides/imastertheme).

**Επιστρέφει:**
[IMasterTheme](../../com.aspose.slides/imastertheme)
### getHyperlinkQueries() {#getHyperlinkQueries--}
```
public abstract IHyperlinkQueries getHyperlinkQueries()
```

Παρέχει εύκολη πρόσβαση σε όλους τους υπερσυνδέσμους που περιέχονται σε όλες τις διαφάνειες της παρουσίασης (εκτός από τις κύριες, διατάξεις, διαφάνειες σημειώσεων). Μόνο για ανάγνωση [IHyperlinkQueries](../../com.aspose.slides/ihyperlinkqueries).

**Επιστρέφει:**
[IHyperlinkQueries](../../com.aspose.slides/ihyperlinkqueries)
### getViewProperties() {#getViewProperties--}
```
public abstract IViewProperties getViewProperties()
```

Λαμβάνει τις ιδιότητες προβολής για ολόκληρη την παρουσίαση. Μόνο για ανάγνωση [IViewProperties](../../com.aspose.slides/iviewproperties).

**Επιστρέφει:**
[IViewProperties](../../com.aspose.slides/iviewproperties)
### getFirstSlideNumber() {#getFirstSlideNumber--}
```
public abstract int getFirstSlideNumber()
```

Αναπαριστά τον αριθμό της πρώτης διαφάνειας στην παρουσίαση. Ανάγνωση/εγγραφή int.

**Επιστρέφει:**
int
### setFirstSlideNumber(int value) {#setFirstSlideNumber-int-}
```
public abstract void setFirstSlideNumber(int value)
```

Αναπαριστά τον αριθμό της πρώτης διαφάνειας στην παρουσίαση. Ανάγνωση/εγγραφή int.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | int |  |

### getAllCustomXmlParts() {#getAllCustomXmlParts--}
```
public abstract ICustomXmlPart[] getAllCustomXmlParts()
```

Επιστρέφει όλα τα προσαρμοσμένα τμήματα δεδομένων στην παρουσίαση. Μόνο για ανάγνωση ICustomXmlPart[].

**Επιστρέφει:**
com.aspose.slides.ICustomXmlPart[]
### getDigitalSignatures() {#getDigitalSignatures--}
```
public abstract IDigitalSignatureCollection getDigitalSignatures()
```

Επιστρέφει τη συλλογή των υπογραφών που χρησιμοποιήθηκαν για την υπογραφή της παρουσίασης. Μόνο για ανάγνωση [IDigitalSignatureCollection](../../com.aspose.slides/idigitalsignaturecollection).

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

Επιστρέφει τη συλλογή των ετικετών ευαισθησίας που εφαρμόζονται στο έγγραφο της παρουσίασης. Μόνο για ανάγνωση [ISensitivityLabelCollection](../../com.aspose.slides/isensitivitylabelcollection).

--------------------

> ```
> Presentation pres = new Presentation("SomePresentation.pptx");
>  try {
>      ISensitivityLabelCollection sensitivityLabels = pres.getSensitivityLabels();
> 
>      // Εμφάνιση των εφαρμοσμένων ετικετών
>      for (ISensitivityLabel sensitivityLabel : sensitivityLabels)
>          System.out.println("Label Id " + sensitivityLabel.getId() + " from Azure AD site " + sensitivityLabel.getSiteId());
> 
>      // Προσθήκη της νέας ετικέτας
>      String labelIdString = "{xxxxxxxx-xxxx-xxxx-xxxx-xxxxxxxxxxxx}"; // Λήψη του αναγνωριστικού ευαίσθητης ετικέτας από την πολιτική
>      UUID siteIdGuid = UUID.fromString("{xxxxxxxx-xxxx-xxxx-xxxx-xxxxxxxxxxxx}"); // Λήψη του αναγνωριστικού τοποθεσίας Azure AD από την πολιτική
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

Αποθηκεύει όλες τις διαφάνειες μιας παρουσίασης σε αρχείο με τη συγκεκριμένη μορφή.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| fname | java.lang.String | Διαδρομή προς το δημιουργημένο αρχείο. |
| format | int | Μορφή των εξαγόμενων δεδομένων. |

### save(OutputStream stream, int format) {#save-java.io.OutputStream-int-}
```
public abstract void save(OutputStream stream, int format)
```

Αποθηκεύει όλες τις διαφάνειες μιας παρουσίασης σε ροή με τη συγκεκριμένη μορφή.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| stream | java.io.OutputStream | Ροή εξόδου. |
| format | int | Μορφή των εξαγόμενων δεδομένων. |

### save(String fname, int format, ISaveOptions options) {#save-java.lang.String-int-com.aspose.slides.ISaveOptions-}
```
public abstract void save(String fname, int format, ISaveOptions options)
```

Αποθηκεύει όλες τις διαφάνειες μιας παρουσίασης σε αρχείο με τη συγκεκριμένη μορφή και με πρόσθετες επιλογές.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| fname | java.lang.String | Διαδρομή προς το δημιουργημένο αρχείο. |
| format | int | Μορφή των εξαγόμενων δεδομένων. |
| options | [ISaveOptions](../../com.aspose.slides/isaveoptions) | Πρόσθετες επιλογές μορφής. |

### save(OutputStream stream, int format, ISaveOptions options) {#save-java.io.OutputStream-int-com.aspose.slides.ISaveOptions-}
```
public abstract void save(OutputStream stream, int format, ISaveOptions options)
```

Αποθηκεύει όλες τις διαφάνειες μιας παρουσίασης σε ροή με τη συγκεκριμένη μορφή και με πρόσθετες επιλογές.

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

Αποθηκεύει τις καθορισμένες διαφάνειες μιας παρουσίασης σε αρχείο με τη συγκεκριμένη μορφή.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| fname | java.lang.String | Διαδρομή προς το δημιουργημένο αρχείο. |
| slides | int[] | Πίνακας με θέσεις διαφανειών, αρχίζοντας από 1. |
| format | int | Μορφή των εξαγόμενων δεδομένων. |

### save(String fname, int[] slides, int format, ISaveOptions options) {#save-java.lang.String-int---int-com.aspose.slides.ISaveOptions-}
```
public abstract void save(String fname, int[] slides, int format, ISaveOptions options)
```

Αποθηκεύει τις καθορισμένες διαφάνειες μιας παρουσίασης σε αρχείο με τη συγκεκριμένη μορφή.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| fname | java.lang.String | Διαδρομή προς το δημιουργημένο αρχείο. |
| slides | int[] | Πίνακας με θέσεις διαφανειών, αρχίζοντας από 1. |
| format | int | Μορφή των εξαγόμενων δεδομένων. |
| options | [ISaveOptions](../../com.aspose.slides/isaveoptions) | Πρόσθετες επιλογές μορφής. |

### save(OutputStream stream, int[] slides, int format) {#save-java.io.OutputStream-int---int-}
```
public abstract void save(OutputStream stream, int[] slides, int format)
```

Αποθηκεύει τις καθορισμένες διαφάνειες μιας παρουσίασης σε ροή με τη συγκεκριμένη μορφή.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| stream | java.io.OutputStream | Ροή εξόδου. |
| slides | int[] | Πίνακας με θέσεις διαφανειών, αρχίζοντας από 1. |
| format | int | Μορφή των εξαγόμενων δεδομένων. |

### save(OutputStream stream, int[] slides, int format, ISaveOptions options) {#save-java.io.OutputStream-int---int-com.aspose.slides.ISaveOptions-}
```
public abstract void save(OutputStream stream, int[] slides, int format, ISaveOptions options)
```

Αποθηκεύει τις καθορισμένες διαφάνειες μιας παρουσίασης σε ροή με τη συγκεκριμένη μορφή.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| stream | java.io.OutputStream | Ροή εξόδου. |
| slides | int[] | Πίνακας με θέσεις διαφανειών, αρχίζοντας από 1. |
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

Επιστρέφει αντικείμενα Εικονίας Μικρογραφίας για όλες τις διαφάνειες μιας παρουσίασης.

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

Επιστρέφει αντικείμενα IImage Μικρογραφίας για τις καθορισμένες διαφάνειες μιας παρουσίασης.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| options | [IRenderingOptions](../../com.aspose.slides/irenderingoptions) | Επιλογές απόδοσης. |
| slides | int[] | Πίνακας με θέσεις διαφανειών, αρχίζοντας από 1. |

**Επιστρέφει:**
com.aspose.slides.IImage[] - IImage objects.
### getImages(IRenderingOptions options, float scaleX, float scaleY) {#getImages-com.aspose.slides.IRenderingOptions-float-float-}
```
public abstract IImage[] getImages(IRenderingOptions options, float scaleX, float scaleY)
```

Επιστρέφει αντικείμενα Εικονίας Μικρογραφίας για όλες τις διαφάνειες μιας παρουσίασης με προσαρμοσμένη κλιμάκωση.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| options | [IRenderingOptions](../../com.aspose.slides/irenderingoptions) | Επιλογές απόδοσης. |
| scaleX | float | Η τιμή με την οποία κλιμακώνεται αυτή η μικρογραφία στην κατεύθυνση του άξονα x. |
| scaleY | float | Η τιμή με την οποία κλιμακώνεται αυτή η μικρογραφία στην κατεύθυνση του άξονα y. |

**Επιστρέφει:**
com.aspose.slides.IImage[] - Bitmap objects.
### getImages(IRenderingOptions options, int[] slides, float scaleX, float scaleY) {#getImages-com.aspose.slides.IRenderingOptions-int---float-float-}
```
public abstract IImage[] getImages(IRenderingOptions options, int[] slides, float scaleX, float scaleY)
```

Επιστρέφει αντικείμενα Εικονίας Μικρογραφίας για τις καθορισμένες διαφάνειες μιας παρουσίασης με προσαρμοσμένη κλιμάκωση.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| options | [IRenderingOptions](../../com.aspose.slides/irenderingoptions) | Επιλογές απόδοσης. |
| slides | int[] | Πίνακας με θέσεις διαφανειών, αρχίζοντας από 1. |
| scaleX | float | Η τιμή με την οποία κλιμακώνεται αυτή η μικρογραφία στην κατεύθυνση του άξονα x. |
| scaleY | float | Η τιμή με την οποία κλιμακώνεται αυτή η μικρογραφία στην κατεύθυνση του άξονα y. |

**Επιστρέφει:**
com.aspose.slides.IImage[] - IImage objects.
### getImages(IRenderingOptions options, Size imageSize) {#getImages-com.aspose.slides.IRenderingOptions-com.aspose.slides.android.Size-}
```
public abstract IImage[] getImages(IRenderingOptions options, Size imageSize)
```

Επιστρέφει αντικείμενα Εικονίας Μικρογραφίας για όλες τις διαφάνειες μιας παρουσίασης με συγκεκριμένο μέγεθος.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| options | [IRenderingOptions](../../com.aspose.slides/irenderingoptions) | Επιλογές απόδοσης. |
| imageSize | [Size](../../com.aspose.slides.android/size) | Μέγεθος της εικόνας που θα δημιουργηθεί. |

**Επιστρέφει:**
com.aspose.slides.IImage[] - IImage objects.
### getImages(IRenderingOptions options, int[] slides, Size imageSize) {#getImages-com.aspose.slides.IRenderingOptions-int---com.aspose.slides.android.Size-}
```
public abstract IImage[] getImages(IRenderingOptions options, int[] slides, Size imageSize)
```

Επιστρέφει αντικείμενα Εικονίας Μικρογραφίας για τις καθορισμένες διαφάνειες μιας παρουσίασης με συγκεκριμένο μέγεθος.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| options | [IRenderingOptions](../../com.aspose.slides/irenderingoptions) | Επιλογές απόδοσης. |
| slides | int[] | Πίνακας με θέσεις διαφανειών, αρχίζοντας από 1. |
| imageSize | [Size](../../com.aspose.slides.android/size) | Μέγεθος της εικόνας που θα δημιουργηθεί. |

**Επιστρέφει:**
com.aspose.slides.IImage[] - IImage objects.
### getSlideById(long id) {#getSlideById-long-}
```
public abstract IBaseSlide getSlideById(long id)
```

Επιστρέφει ένα Slide, MasterSlide ή LayoutSlide με βάση το Id.

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

Ενώνει τμήματα κειμένου με ίδια μορφοποίηση σε όλες τις παραγράφους σε όλα τα αποδεκτά σχήματα σε όλες τις διαφάνειες.

### highlightText(String text, Integer highlightColor) {#highlightText-java.lang.String-java.lang.Integer-}
```
public abstract void highlightText(String text, Integer highlightColor)
```

Επισημαίνει όλες τις αντιστοιχίες του δείγματος κειμένου με το καθορισμένο χρώμα.

--------------------

> ```
> The following code sample shows how to highlight text in a PowerPoint presentation.
>  
>  Presentation presentation = new Presentation("SomePresentation.pptx");
>  try {
>      // επισημαίνοντας όλες τις ξεχωριστές εμφανίσεις του 'the'
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
| highlightColor | java.lang.Integer | Το χρώμα για επισήμανση του κειμένου. |

### highlightText(String text, Integer highlightColor, ITextSearchOptions options, IFindResultCallback callback) {#highlightText-java.lang.String-java.lang.Integer-com.aspose.slides.ITextSearchOptions-com.aspose.slides.IFindResultCallback-}
```
public abstract void highlightText(String text, Integer highlightColor, ITextSearchOptions options, IFindResultCallback callback)
```

Επισημαίνει όλες τις αντιστοιχίες του δείγματος κειμένου με το καθορισμένο χρώμα.

--------------------

> ```
> The following code sample shows how to highlight text in a PowerPoint presentation.
>  
>  Presentation presentation = new Presentation("SomePresentation.pptx");
>  try {
>      // επισημαίνοντας όλες τις ξεχωριστές εμφανίσεις του 'the'
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
| highlightColor | java.lang.Integer | Το χρώμα για επισήμανση του κειμένου. |
| options | [ITextSearchOptions](../../com.aspose.slides/itextsearchoptions) | Επιλογές αναζήτησης κειμένου [ITextSearchOptions](../../com.aspose.slides/itextsearchoptions). |
| callback | [IFindResultCallback](../../com.aspose.slides/ifindresultcallback) | Το αντικείμενο κλήσης για λήψη αποτελεσμάτων αναζήτησης [IFindResultCallback](../../com.aspose.slides/ifindresultcallback). |

### highlightRegex(Pattern regex, Integer highlightColor, IFindResultCallback callback) {#highlightRegex-java.util.regex.Pattern-java.lang.Integer-com.aspose.slides.IFindResultCallback-}
```
public abstract void highlightRegex(Pattern regex, Integer highlightColor, IFindResultCallback callback)
```

Επισημαίνει όλες τις αντιστοιχίες της κανονικής έκΦρασης με το καθορισμένο χρώμα.

--------------------

> ```
> The following code sample shows how to highlight text in a PowerPoint Presentation using a regular expression.
>  
>  Presentation presentation = new Presentation("SomePresentation.pptx");
>  try {
>      // επισημαίνοντας όλες τις ξεχωριστές εμφανίσεις του 'the'
>      presentation.highlightText("the", Color.MAGENTA);
>      presentation.save("SomePresentation-out2.pptx", SaveFormat.Pptx);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```


**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| regex | java.util.regex.Pattern | Η κανονική έκφραση java.util.regex.Pattern για λήψη των αλφαριθμητικών προς επισήμανση. |
| highlightColor | java.lang.Integer | Το χρώμα για επισήμανση του κειμένου. |
| callback | [IFindResultCallback](../../com.aspose.slides/ifindresultcallback) | Το αντικείμενο κλήσης για λήψη αποτελεσμάτων αναζήτησης [IFindResultCallback](../../com.aspose.slides/ifindresultcallback). |

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
>      // Αντικαταστήστε όλες τις ξεχωριστές εμφανίσεις του 'the' με '***'
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
| callback | [IFindResultCallback](../../com.aspose.slides/ifindresultcallback) | Το αντικείμενο κλήσης για λήψη αποτελεσμάτων αναζήτησης [IFindResultCallback](../../com.aspose.slides/ifindresultcallback). |

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
>      // Αντικαταστήστε όλες τις ξεχωριστές εμφανίσεις του 'the' με '***'
>      presentation.replaceText("the", "***", textSearchOptions, null);
>      presentation.save("SomePresentation-out2.pptx", SaveFormat.Pptx);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```


**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| regex | java.util.regex.Pattern | Η κανονική έκφραση java.util.regex.Pattern για λήψη των αλφαριθμητικών προς αντικατάσταση. |
| newText | java.lang.String | Η συμβολοσειρά που θα αντικαταστήσει όλες τις εμφανίσεις των αλφαριθμητικών που θα αντικατασταθούν. |
| callback | [IFindResultCallback](../../com.aspose.slides/ifindresultcallback) | Το αντικείμενο κλήσης για λήψη αποτελεσμάτων αναζήτησης [IFindResultCallback](../../com.aspose.slides/ifindresultcallback). |