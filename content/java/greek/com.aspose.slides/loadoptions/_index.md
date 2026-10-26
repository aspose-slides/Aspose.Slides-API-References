---
title: LoadOptions
second_title: Aspose.Slides για την Αναφορά API της Java
description: Επιτρέπει τον καθορισμό πρόσθετων επιλογών, όπως μορφή ή προεπιλεγμένη γραμματοσειρά, κατά τη φόρτωση μιας παρουσίασης.
type: docs
url: /el/com.aspose.slides/loadoptions/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.aspose.slides.ILoadOptions](../../com.aspose.slides/iloadoptions)
```
public class LoadOptions implements ILoadOptions
```

Επιτρέπει να καθορίσετε πρόσθετες επιλογές (όπως μορφή ή προεπιλεγμένη γραμματοσειρά) κατά τη φόρτωση μιας παρουσίασης.
## Κατασκευαστές

| Κατασκευαστής | Περιγραφή |
| --- | --- |
| [LoadOptions()](#LoadOptions--) | Δημιουργεί νέες προεπιλεγμένες επιλογές φόρτωσης. |
| [LoadOptions(int loadFormat)](#LoadOptions-int-) | Δημιουργεί νέες επιλογές φόρτωσης. |
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [getLoadFormat()](#getLoadFormat--) | Επιστρέφει ή ορίζει τη μορφή μιας παρουσίασης για φόρτωση. |
| [setLoadFormat(int value)](#setLoadFormat-int-) | Επιστρέφει ή ορίζει τη μορφή μιας παρουσίασης για φόρτωση. |
| [getDefaultRegularFont()](#getDefaultRegularFont--) | Επιστρέφει ή ορίζει την Κανονική γραμματοσειρά που χρησιμοποιείται εάν δεν βρεθεί η πηγαία γραμματοσειρά. |
| [setDefaultRegularFont(String value)](#setDefaultRegularFont-java.lang.String-) | Επιστρέφει ή ορίζει την Κανονική γραμματοσειρά που χρησιμοποιείται εάν δεν βρεθεί η πηγαία γραμματοσειρά. |
| [getDefaultSymbolFont()](#getDefaultSymbolFont--) | Επιστρέφει ή ορίζει τη Συμβολική γραμματοσειρά που χρησιμοποιείται εάν δεν βρεθεί η πηγαία γραμματοσειρά. |
| [setDefaultSymbolFont(String value)](#setDefaultSymbolFont-java.lang.String-) | Επιστρέφει ή ορίζει τη Συμβολική γραμματοσειρά που χρησιμοποιείται εάν δεν βρεθεί η πηγαία γραμματοσειρά. |
| [getDefaultAsianFont()](#getDefaultAsianFont--) | Επιστρέφει ή ορίζει την Ασιατική γραμματοσειρά που χρησιμοποιείται εάν δεν βρεθεί η πηγαία γραμματοσειρά. |
| [setDefaultAsianFont(String value)](#setDefaultAsianFont-java.lang.String-) | Επιστρέφει ή ορίζει την Ασιατική γραμματοσειρά που χρησιμοποιείται εάν δεν βρεθεί η πηγαία γραμματοσειρά. |
| [getPassword()](#getPassword--) | Λαμβάνει ή ορίζει τον κωδικό πρόσβασης. |
| [setPassword(String value)](#setPassword-java.lang.String-) | Λαμβάνει ή ορίζει τον κωδικό πρόσβασης. |
| [getOnlyLoadDocumentProperties()](#getOnlyLoadDocumentProperties--) | Αυτή η ιδιότητα είναι χρήσιμη εάν το αρχείο παρουσίασης είναι προστατευμένο με κωδικό. |
| [setOnlyLoadDocumentProperties(boolean value)](#setOnlyLoadDocumentProperties-boolean-) | Αυτή η ιδιότητα είναι χρήσιμη εάν το αρχείο παρουσίασης είναι προστατευμένο με κωδικό. |
| [getWarningCallback()](#getWarningCallback--) | Επιστρέφει ή ορίζει ένα αντικείμενο που λαμβάνει προειδοποιήσεις και αποφασίζει εάν η διαδικασία φόρτωσης θα συνεχιστεί ή θα διακοπεί. |
| [setWarningCallback(IWarningCallback value)](#setWarningCallback-com.aspose.slides.IWarningCallback-) | Επιστρέφει ή ορίζει ένα αντικείμενο που λαμβάνει προειδοποιήσεις και αποφασίζει εάν η διαδικασία φόρτωσης θα συνεχιστεί ή θα διακοπεί. |
| [getBlobManagementOptions()](#getBlobManagementOptions--) | Αντιπροσωπεύει τις επιλογές που μπορούν να χρησιμοποιηθούν για τη διαχείριση της συμπεριφοράς χειρισμού Binary Large Objects (BLOBs), όπως η χρήση προσωρινών αρχείων ή το μέγιστο αριθμό bytes BLOBs στη μνήμη. |
| [setBlobManagementOptions(IBlobManagementOptions value)](#setBlobManagementOptions-com.aspose.slides.IBlobManagementOptions-) | Αντιπροσωπεύει τις επιλογές που μπορούν να χρησιμοποιηθούν για τη διαχείριση της συμπεριφοράς χειρισμού Binary Large Objects (BLOBs), όπως η χρήση προσωρινών αρχείων ή το μέγιστο αριθμό bytes BLOBs στη μνήμη. |
| [getDocumentLevelFontSources()](#getDocumentLevelFontSources--) | Καθορίζει πηγές για εξωτερικές γραμματοσειρές που θα χρησιμοποιηθούν από την παρουσίαση. |
| [setDocumentLevelFontSources(IFontSources value)](#setDocumentLevelFontSources-com.aspose.slides.IFontSources-) | Καθορίζει πηγές για εξωτερικές γραμματοσειρές που θα χρησιμοποιηθούν από την παρουσίαση. |
| [getInterruptionToken()](#getInterruptionToken--) | Το διακριτικό για παρακολούθηση αιτημάτων διακοπής. |
| [setInterruptionToken(IInterruptionToken value)](#setInterruptionToken-com.aspose.slides.IInterruptionToken-) | Το διακριτικό για παρακολούθηση αιτημάτων διακοπής. |
| [getResourceLoadingCallback()](#getResourceLoadingCallback--) | Επιστρέφει ή ορίζει διεπαφή callback που διαχειρίζεται τη φόρτωση εξωτερικών πόρων. |
| [setResourceLoadingCallback(IResourceLoadingCallback value)](#setResourceLoadingCallback-com.aspose.slides.IResourceLoadingCallback-) | Επιστρέφει ή ορίζει διεπαφή callback που διαχειρίζεται τη φόρτωση εξωτερικών πόρων. |
| [getSpreadsheetOptions()](#getSpreadsheetOptions--) | Λαμβάνει επιλογές για λογιστικά φύλλα. |
| [setSpreadsheetOptions(ISpreadsheetOptions value)](#setSpreadsheetOptions-com.aspose.slides.ISpreadsheetOptions-) | Λαμβάνει επιλογές για λογιστικά φύλλα. |
| [getDefaultTextLanguage()](#getDefaultTextLanguage--) | Επιστρέφει ή ορίζει τη προεπιλεγμένη γλώσσα για το κείμενο της παρουσίασης. |
| [setDefaultTextLanguage(String value)](#setDefaultTextLanguage-java.lang.String-) | Επιστρέφει ή ορίζει τη προεπιλεγμένη γλώσσα για το κείμενο της παρουσίασης. |
| [getDeleteEmbeddedBinaryObjects()](#getDeleteEmbeddedBinaryObjects--) | Καθορίζει εάν το Aspose.Slides θα διαγράψει όλα τα ενσωματωμένα δυαδικά αντικείμενα κατά τη φόρτωση της παρουσίασης. |
| [setDeleteEmbeddedBinaryObjects(boolean value)](#setDeleteEmbeddedBinaryObjects-boolean-) | Καθορίζει εάν το Aspose.Slides θα διαγράψει όλα τα ενσωματωμένα δυαδικά αντικείμενα κατά τη φόρτωση της παρουσίασης. |
### LoadOptions() {#LoadOptions--}
```
public LoadOptions()
```

Δημιουργεί νέες προεπιλεγμένες επιλογές φόρτωσης.

### LoadOptions(int loadFormat) {#LoadOptions-int-}
```
public LoadOptions(int loadFormat)
```

Δημιουργεί νέες επιλογές φόρτωσης.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| loadFormat | int | Μορφή μιας παρουσίασης για φόρτωση. |

### getLoadFormat() {#getLoadFormat--}
```
public final int getLoadFormat()
```

Επιστρέφει ή ορίζει τη μορφή μιας παρουσίασης για φόρτωση. Ανάγνωση/εγγραφή [LoadFormat](../../com.aspose.slides/loadformat).

**Επιστρέφει:**
int
### setLoadFormat(int value) {#setLoadFormat-int-}
```
public final void setLoadFormat(int value)
```

Επιστρέφει ή ορίζει τη μορφή μιας παρουσίασης για φόρτωση. Ανάγνωση/εγγραφή [LoadFormat](../../com.aspose.slides/loadformat).

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | int |  |

### getDefaultRegularFont() {#getDefaultRegularFont--}
```
public final String getDefaultRegularFont()
```

Επιστρέφει ή ορίζει την Κανονική γραμματοσειρά που χρησιμοποιείται εάν δεν βρεθεί η πηγαία γραμματοσειρά. Ανάγνωση/εγγραφή String.

--------------------

> ```
> The following example shows how to set default fonts for rendering PowerPoint Presentation.
>  
>  // Χρησιμοποιήστε επιλογές φόρτωσης για να ορίσετε τις προεπιλεγμένες κανονικές και ασιατικές γραμματοσειρές
>  LoadOptions loadOptions = new LoadOptions(LoadFormat.Auto);
>  loadOptions.setDefaultRegularFont("Wingdings");
>  loadOptions.setDefaultAsianFont("Wingdings");
>  // Φορτώστε την παρουσίαση
>  Presentation pres = new Presentation("DefaultFonts.pptx", loadOptions);
>  try {
>      // Δημιουργήστε μικρογραφία διαφάνειας
>      BufferedImage slideImage = pres.getSlides().get_Item(0).getThumbnail(1, 1);
>      ImageIO.write(slideImage, "PNG", new File("output_out.png"));
>      // Δημιουργήστε PDF
>      pres.save("output_out.pdf", SaveFormat.Pdf);
>      // Δημιουργήστε XPS
>      pres.save("output_out.xps", SaveFormat.Xps);
>  } catch(IOException e) {
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Επιστρέφει:**
java.lang.String
### setDefaultRegularFont(String value) {#setDefaultRegularFont-java.lang.String-}
```
public final void setDefaultRegularFont(String value)
```

Επιστρέφει ή ορίζει την Κανονική γραμματοσειρά που χρησιμοποιείται εάν δεν βρεθεί η πηγαία γραμματοσειρά. Ανάγνωση/εγγραφή String.

--------------------

> ```
> The following example shows how to set default fonts for rendering PowerPoint Presentation.
>  
>  // Χρησιμοποιήστε επιλογές φόρτωσης για να ορίσετε τις προεπιλεγμένες κανονικές και ασιατικές γραμματοσειρές
>  LoadOptions loadOptions = new LoadOptions(LoadFormat.Auto);
>  loadOptions.setDefaultRegularFont("Wingdings");
>  loadOptions.setDefaultAsianFont("Wingdings");
>  // Φορτώστε την παρουσίαση
>  Presentation pres = new Presentation("DefaultFonts.pptx", loadOptions);
>  try {
>      // Δημιουργήστε μικρογραφία διαφάνειας
>      BufferedImage slideImage = pres.getSlides().get_Item(0).getThumbnail(1, 1);
>      ImageIO.write(slideImage, "PNG", new File("output_out.png"));
>      // Δημιουργήστε PDF
>      pres.save("output_out.pdf", SaveFormat.Pdf);
>      // Δημιουργήστε XPS
>      pres.save("output_out.xps", SaveFormat.Xps);
>  } catch(IOException e) {
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | java.lang.String |  |

### getDefaultSymbolFont() {#getDefaultSymbolFont--}
```
public final String getDefaultSymbolFont()
```

Επιστρέφει ή ορίζει τη Συμβολική γραμματοσειρά που χρησιμοποιείται εάν δεν βρεθεί η πηγαία γραμματοσειρά. Ανάγνωση/εγγραφή String.

**Επιστρέφει:**
java.lang.String
### setDefaultSymbolFont(String value) {#setDefaultSymbolFont-java.lang.String-}
```
public final void setDefaultSymbolFont(String value)
```

Επιστρέφει ή ορίζει τη Συμβολική γραμματοσειρά που χρησιμοποιείται εάν δεν βρεθεί η πηγαία γραμματοσειρά. Ανάγνωση/εγγραφή String.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | java.lang.String |  |

### getDefaultAsianFont() {#getDefaultAsianFont--}
```
public final String getDefaultAsianFont()
```

Επιστρέφει ή ορίζει την Ασιατική γραμματοσειρά που χρησιμοποιείται εάν δεν βρεθεί η πηγαία γραμματοσειρά. Ανάγνωση/εγγραφή String.

**Επιστρέφει:**
java.lang.String
### setDefaultAsianFont(String value) {#setDefaultAsianFont-java.lang.String-}
```
public final void setDefaultAsianFont(String value)
```

Επιστρέφει ή ορίζει την Ασιατική γραμματοσειρά που χρησιμοποιείται εάν δεν βρεθεί η πηγαία γραμματοσειρά. Ανάγνωση/εγγραφή String.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | java.lang.String |  |

### getPassword() {#getPassword--}
```
public final String getPassword()
```

Λαμβάνει ή ορίζει τον κωδικό πρόσβασης. Ανάγνωση/εγγραφή String.

--------------------

> ```
> The following sample code shows how to open password protected PowerPoint Presentation.
>  
>  LoadOptions loadOptions = new LoadOptions();
>  loadOptions.setPassword("YOUR_PASSWORD");
>  Presentation pres = new Presentation("pres.pptx", loadOptions);
>  try {
>  // εργαστείτε με την αποκρυπτογραφημένη παρουσίαση
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

Τιμή: Ο κωδικός πρόσβασης.

**Επιστρέφει:**
java.lang.String
### setPassword(String value) {#setPassword-java.lang.String-}
```
public final void setPassword(String value)
```

Λαμβάνει ή ορίζει τον κωδικό πρόσβασης. Ανάγνωση/εγγραφή String.

--------------------

> ```
> The following sample code shows how to open password protected PowerPoint Presentation.
>  
>  LoadOptions loadOptions = new LoadOptions();
>  loadOptions.setPassword("YOUR_PASSWORD");
>  Presentation pres = new Presentation("pres.pptx", loadOptions);
>  try {
>  // εργαστείτε με την αποκρυπτογραφημένη παρουσίαση
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


Τιμή: Ο κωδικός πρόσβασης.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | java.lang.String |  |

### getOnlyLoadDocumentProperties() {#getOnlyLoadDocumentProperties--}
```
public final boolean getOnlyLoadDocumentProperties()
```

Αυτή η ιδιότητα είναι χρήσιμη εάν το αρχείο παρουσίασης είναι προστατευμένο με κωδικό. Η τιμή true σημαίνει ότι θα φορτωθούν μόνο οι ιδιότητες εγγράφου από ένα κρυπτογραφημένο αρχείο παρουσίασης και ο κωδικός θα αγνοηθεί. Η τιμή false σημαίνει ότι όλη η κρυπτογραφημένη παρουσίαση θα φορτωθεί με χρήση του σωστού κωδικού. Εάν η παρουσίαση δεν είναι κρυπτογραφημένη, η τιμή της ιδιότητας αγνοείται πάντα. Εάν οι ιδιότητες εγγράφου ενός κρυπτογραφημένου αρχείου δεν είναι δημόσιες και η τιμή της ιδιότητας είναι true, οι ιδιότητες δεν μπορούν να φορτωθούν και θα ριχθεί εξαίρεση. Ανάγνωση/εγγραφή boolean.

**Επιστρέφει:**
boolean
### setOnlyLoadDocumentProperties(boolean value) {#setOnlyLoadDocumentProperties-boolean-}
```
public final void setOnlyLoadDocumentProperties(boolean value)
```

Αυτή η ιδιότητα είναι χρήσιμη εάν το αρχείο παρουσίασης είναι προστατευμένο με κωδικό. Η τιμή true σημαίνει ότι θα φορτωθούν μόνο οι ιδιότητες εγγράφου από ένα κρυπτογραφημένο αρχείο παρουσίασης και ο κωδικός θα αγνοηθεί. Η τιμή false σημαίνει ότι όλη η κρυπτογραφημένη παρουσίαση θα φορτωθεί με χρήση του σωστού κωδικού. Εάν η παρουσίαση δεν είναι κρυπτογραφημένη, η τιμή της ιδιότητας αγνοείται πάντα. Εάν οι ιδιότητες εγγράφου ενός κρυπτογραφημένου αρχείου δεν είναι δημόσιες και η τιμή της ιδιότητας είναι true, οι ιδιότητες δεν μπορούν να φορτωθούν και θα ριχθεί εξαίρεση. Ανάγνωση/εγγραφή boolean.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | boolean |  |

### getWarningCallback() {#getWarningCallback--}
```
public final IWarningCallback getWarningCallback()
```

Επιστρέφει ή ορίζει ένα αντικείμενο που λαμβάνει προειδοποιήσεις και αποφασίζει εάν η διαδικασία φόρτωσης θα συνεχιστεί ή θα διακοπεί. Ανάγνωση/εγγραφή [IWarningCallback](../../com.aspose.slides/iwarningcallback).

**Επιστρέφει:**
[IWarningCallback](../../com.aspose.slides/iwarningcallback)
### setWarningCallback(IWarningCallback value) {#setWarningCallback-com.aspose.slides.IWarningCallback-}
```
public final void setWarningCallback(IWarningCallback value)
```

Επιστρέφει ή ορίζει ένα αντικείμενο που λαμβάνει προειδοποιήσεις και αποφασίζει εάν η διαδικασία φόρτωσης θα συνεχιστεί ή θα διακοπεί. Ανάγνωση/εγγραφή [IWarningCallback](../../com.aspose.slides/iwarningcallback).

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | [IWarningCallback](../../com.aspose.slides/iwarningcallback) |  |

### getBlobManagementOptions() {#getBlobManagementOptions--}
```
public final IBlobManagementOptions getBlobManagementOptions()
```

Αντιπροσωπεύει τις επιλογές που μπορούν να χρησιμοποιηθούν για τη διαχείριση της συμπεριφοράς χειρισμού Binary Large Objects (BLOBs), όπως η χρήση προσωρινών αρχείων ή το μέγιστο αριθμό bytes BLOBs στη μνήμη. Αυτές οι επιλογές προορίζονται να ρυθμίσουν το βέλτιστο λόγο απόδοσης/κατανάλωσης μνήμης για ένα συγκεκριμένο περιβάλλον ή απαιτήσεις.

--------------------

Ένα Binary Large Object (BLOB) είναι δυαδικά δεδομένα αποθηκευμένα ως μια ενιαία οντότητα – π.χ. το BLOB μπορεί να είναι ήχο, βίντεο ή η ίδια η παρουσίαση.

**Επιστρέφει:**
[IBlobManagementOptions](../../com.aspose.slides/iblobmanagementoptions)
### setBlobManagementOptions(IBlobManagementOptions value) {#setBlobManagementOptions-com.aspose.slides.IBlobManagementOptions-}
```
public final void setBlobManagementOptions(IBlobManagementOptions value)
```

Αντιπροσωπεύει τις επιλογές που μπορούν να χρησιμοποιηθούν για τη διαχείριση της συμπεριφοράς χειρισμού Binary Large Objects (BLOBs), όπως η χρήση προσωρινών αρχείων ή το μέγιστο αριθμό bytes BLOBs στη μνήμη. Αυτές οι επιλογές προορίζονται να ρυθμίσουν το βέλτιστο λόγο απόδοσης/κατανάλωσης μνήμης για ένα συγκεκριμένο περιβάλλον ή απαιτήσεις.

--------------------

Ένα Binary Large Object (BLOB) είναι δυαδικά δεδομένα αποθηκευμένα ως μια ενιαία οντότητα – π.χ. το BLOB μπορεί να είναι ήχος, βίντεο ή η ίδια η παρουσίαση.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | [IBlobManagementOptions](../../com.aspose.slides/iblobmanagementoptions) |  |

### getDocumentLevelFontSources() {#getDocumentLevelFontSources--}
```
public final IFontSources getDocumentLevelFontSources()
```

Καθορίζει πηγές για εξωτερικές γραμματοσειρές που θα χρησιμοποιηθούν από την παρουσίαση. Αυτές οι γραμματοσειρές είναι διαθέσιμες στην παρουσίαση καθ' όλη τη διάρκεια ζωής της και δεν μοιράζονται με άλλες παρουσιάσεις.

--------------------

> ```
> Το παρακάτω παράδειγμα δείχνει πώς να ορίσετε προσαρμοσμένες γραμματοσειρές που χρησιμοποιούνται με την Παρουσίαση PowerPoint.
>  
>  byte[] memoryFont1 = Files.readAllBytes(Paths.get("customfonts\\CustomFont1.ttf"));
>  byte[] memoryFont2 = Files.readAllBytes(Paths.get("customfonts\\CustomFont2.ttf"));
>  LoadOptions loadOptions = new LoadOptions();
>  loadOptions.getDocumentLevelFontSources().setFontFolders(new String[] { "assets\\fonts", "global\\fonts" });
>  loadOptions.getDocumentLevelFontSources().setMemoryFonts(new byte[][] { memoryFont1, memoryFont2 });
>  IPresentation presentation = new Presentation("MyPresentation.pptx", loadOptions);
>  try {
>  // εργαστείτε με την παρουσίαση
>  //CustomFont1, CustomFont2 καθώς και οι γραμματοσειρές από τους φακέλους assets\fonts & global\fonts και τους υποφακέλους τους είναι διαθέσιμες στην παρουσίαση
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```


**Επιστρέφει:**
[IFontSources](../../com.aspose.slides/ifontsources)
### setDocumentLevelFontSources(IFontSources value) {#setDocumentLevelFontSources-com.aspose.slides.IFontSources-}
```
public final void setDocumentLevelFontSources(IFontSources value)
```

Καθορίζει πηγές για εξωτερικές γραμματοσειρές που θα χρησιμοποιηθούν από την παρουσίαση. Αυτές οι γραμματοσειρές είναι διαθέσιμες στην παρουσίαση καθ' όλη τη διάρκεια ζωής της και δεν μοιράζονται με άλλες παρουσιάσεις.

--------------------

> ```
> Το παρακάτω παράδειγμα δείχνει πώς να ορίσετε προσαρμοσμένες γραμματοσειρές που χρησιμοποιούνται με την Παρουσίαση PowerPoint.
>  
>  byte[] memoryFont1 = Files.readAllBytes(Paths.get("customfonts\\CustomFont1.ttf"));
>  byte[] memoryFont2 = Files.readAllBytes(Paths.get("customfonts\\CustomFont2.ttf"));
>  LoadOptions loadOptions = new LoadOptions();
>  loadOptions.getDocumentLevelFontSources().setFontFolders(new String[] { "assets\\fonts", "global\\fonts" });
>  loadOptions.getDocumentLevelFontSources().setMemoryFonts(new byte[][] { memoryFont1, memoryFont2 });
>  IPresentation presentation = new Presentation("MyPresentation.pptx", loadOptions);
>  try {
>  // εργαστείτε με την παρουσίαση
>  //CustomFont1, CustomFont2 καθώς και οι γραμματοσειρές από τους φακέλους assets\fonts & global\fonts και τους υποφακέλους τους είναι διαθέσιμες στην παρουσίαση
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```


**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | [IFontSources](../../com.aspose.slides/ifontsources) |  |

### getInterruptionToken() {#getInterruptionToken--}
```
public final IInterruptionToken getInterruptionToken()
```

Το διακριτικό για παρακολούθηση αιτημάτων διακοπής.

--------------------

Αυτό το διακριτικό διαχειρίζεται ολόκληρη τη διάρκεια ζωής της διεπαφής [IPresentation](../../com.aspose.slides/ipresentation). Οποιαδήποτε μακροχρόνια λειτουργία, όπως η φόρτωση ή η αποθήκευση μιας παρουσίασης, θα διακοπεί μέσω κλήσης της μεθόδου [InterruptionTokenSource.interrupt](../../com.aspose.slides/interruptiontokensource\#interrupt) του [InterruptionTokenSource](../../com.aspose.slides/interruptiontokensource).

**Επιστρέφει:**
[IInterruptionToken](../../com.aspose.slides/iinterruptiontoken)
### setInterruptionToken(IInterruptionToken value) {#setInterruptionToken-com.aspose.slides.IInterruptionToken-}
```
public final void setInterruptionToken(IInterruptionToken value)
```

Το διακριτικό για παρακολούθηση αιτημάτων διακοπής.

--------------------

Αυτό το διακριτικό διαχειρίζεται ολόκληρη τη διάρκεια ζωής της διεπαφής [IPresentation](../../com.aspose.slides/ipresentation). Οποιαδήποτε μακροχρόνια λειτουργία, όπως η φόρτωση ή η αποθήκευση μιας παρουσίασης, θα διακοπεί μέσω κλήσης της μεθόδου [InterruptionTokenSource.interrupt](../../com.aspose.slides/interruptiontokensource\#interrupt) του [InterruptionTokenSource](../../com.aspose.slides/interruptiontokensource).

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | [IInterruptionToken](../../com.aspose.slides/iinterruptiontoken) |  |

### getResourceLoadingCallback() {#getResourceLoadingCallback--}
```
public final IResourceLoadingCallback getResourceLoadingCallback()
```

Επιστρέφει ή ορίζει διεπαφή callback που διαχειρίζεται τη φόρτωση εξωτερικών πόρων. Ανάγνωση/εγγραφή [IResourceLoadingCallback](../../com.aspose.slides/iresourceloadingcallback).

**Επιστρέφει:**
[IResourceLoadingCallback](../../com.aspose.slides/iresourceloadingcallback)
### setResourceLoadingCallback(IResourceLoadingCallback value) {#setResourceLoadingCallback-com.aspose.slides.IResourceLoadingCallback-}
```
public final void setResourceLoadingCallback(IResourceLoadingCallback value)
```

Επιστρέφει ή ορίζει διεπαφή callback που διαχειρίζεται τη φόρτωση εξωτερικών πόρων. Ανάγνωση/εγγραφή [IResourceLoadingCallback](../../com.aspose.slides/iresourceloadingcallback).

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | [IResourceLoadingCallback](../../com.aspose.slides/iresourceloadingcallback) |  |

### getSpreadsheetOptions() {#getSpreadsheetOptions--}
```
public final ISpreadsheetOptions getSpreadsheetOptions()
```

Λαμβάνει επιλογές για λογιστικά φύλλα. Για παράδειγμα, αυτές οι επιλογές επηρεάζουν τον υπολογισμό τύπων για διαγράμματα.

**Επιστρέφει:**
[ISpreadsheetOptions](../../com.aspose.slides/ispreadsheetoptions)
### setSpreadsheetOptions(ISpreadsheetOptions value) {#setSpreadsheetOptions-com.aspose.slides.ISpreadsheetOptions-}
```
public final void setSpreadsheetOptions(ISpreadsheetOptions value)
```

Λαμβάνει επιλογές για λογιστικά φύλλα. Για παράδειγμα, αυτές οι επιλογές επηρεάζουν τον υπολογισμό τύπων για διαγράμματα.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | [ISpreadsheetOptions](../../com.aspose.slides/ispreadsheetoptions) |  |

### getDefaultTextLanguage() {#getDefaultTextLanguage--}
```
public final String getDefaultTextLanguage()
```

Επιστρέφει ή ορίζει τη προεπιλεγμένη γλώσσα για το κείμενο της παρουσίασης. Ανάγνωση/εγγραφή String.

--------------------

> ```
> Example:
>   
>  // Χρησιμοποιήστε επιλογές φόρτωσης για να ορίσετε την προεπιλεγμένη γλώσσα κειμένου
>  LoadOptions loadOptions = new LoadOptions();
>  loadOptions.setDefaultTextLanguage("en-US");
>  Presentation pres = new Presentation(loadOptions);
>  try {
>      // Προσθέστε νέο σχήμα ορθογωνίου με κείμενο
>      IAutoShape shp = pres.getSlides().get_Item(0).getShapes().addAutoShape(ShapeType.Rectangle, 50, 50, 150, 50);
>      shp.getTextFrame().setText("New Text");
>      // Ελέγξτε τη γλώσσα του πρώτου τμήματος
>      System.out.println(shp.getTextFrame().getParagraphs().get_Item(0).getPortions().get_Item(0).getPortionFormat().getLanguageId());
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Επιστρέφει:**
java.lang.String
### setDefaultTextLanguage(String value) {#setDefaultTextLanguage-java.lang.String-}
```
public final void setDefaultTextLanguage(String value)
```

Επιστρέφει ή ορίζει τη προεπιλεγμένη γλώσσα για το κείμενο της παρουσίασης. Ανάγνωση/εγγραφή String.

--------------------

> ```
> Example:
>   
>  // Χρησιμοποιήστε επιλογές φόρτωσης για να ορίσετε την προεπιλεγμένη γλώσσα κειμένου
>  LoadOptions loadOptions = new LoadOptions();
>  loadOptions.setDefaultTextLanguage("en-US");
>  Presentation pres = new Presentation(loadOptions);
>  try {
>      // Προσθέστε νέο σχήμα ορθογωνίου με κείμενο
>      IAutoShape shp = pres.getSlides().get_Item(0).getShapes().addAutoShape(ShapeType.Rectangle, 50, 50, 150, 50);
>      shp.getTextFrame().setText("New Text");
>      // Ελέγξτε τη γλώσσα του πρώτου τμήματος
>      System.out.println(shp.getTextFrame().getParagraphs().get_Item(0).getPortions().get_Item(0).getPortionFormat().getLanguageId());
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | java.lang.String |  |

### getDeleteEmbeddedBinaryObjects() {#getDeleteEmbeddedBinaryObjects--}
```
public final boolean getDeleteEmbeddedBinaryObjects()
```

Καθορίζει εάν το Aspose.Slides θα διαγράψει όλα τα ενσωματωμένα δυαδικά αντικείμενα κατά τη φόρτωση της παρουσίασης.

Οι τύποι των ενσωματωμένων δυαδικών αντικειμένων:

Ανάγνωση/εγγραφή boolean.

--------------------

> ```
> The following example shows how to load the presentation without any embedded binary objects.
>  
>  LoadOptions loadOptions = new LoadOptions();
>  loadOptions.setDeleteEmbeddedBinaryObjects(true);
>  Presentation pres = new Presentation("pres.ppt", loadOptions);
>  try {
>      pres.save("output_WithoutBinaryObjects.ppt", SaveFormat.Ppt);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

--------------------

Η προεπιλογή είναι **false**.

**Επιστρέφει:**
boolean
### setDeleteEmbeddedBinaryObjects(boolean value) {#setDeleteEmbeddedBinaryObjects-boolean-}
```
public final void setDeleteEmbeddedBinaryObjects(boolean value)
```

Καθορίζει εάν το Aspose.Slides θα διαγράψει όλα τα ενσωματωμένα δυαδικά αντικείμενα κατά τη φόρτωση της παρουσίασης.

Οι τύποι των ενσωματωμένων δυαδικών αντικειμένων:

Ανάγνωση/εγγραφή boolean.

--------------------

> ```
> Το παρακάτω παράδειγμα δείχνει πώς να φορτώσετε την παρουσίαση χωρίς ενσωματωμένα δυαδικά αντικείμενα.
>  
>  LoadOptions loadOptions = new LoadOptions();
>  loadOptions.setDeleteEmbeddedBinaryObjects(true);
>  Presentation pres = new Presentation("pres.ppt", loadOptions);
>  try {
>      pres.save("output_WithoutBinaryObjects.ppt", SaveFormat.Ppt);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


--------------------

Η προεπιλογή είναι **false**.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | boolean |  |