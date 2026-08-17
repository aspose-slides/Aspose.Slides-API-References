---
title: SwfOptions
second_title: Aspose.Slides για Java – Αναφορά API
description: Παρέχει επιλογές που ελέγχουν πώς μια παρουσίαση αποθηκεύεται σε μορφή Swf.
type: docs
url: /el/com.aspose.slides/swfoptions/
---
**Inheritance:**  
java.lang.Object, [com.aspose.slides.SaveOptions](../../com.aspose.slides/saveoptions)

**All Implemented Interfaces:**  
[com.aspose.slides.ISwfOptions](../../com.aspose.slides/iswfoptions)  
```
public class SwfOptions extends SaveOptions implements ISwfOptions
```

Provides options that control how a presentation is saved in Swf format.

--------------------

> ```
> The following example shows how to convert PowerPoint to SWF Flash.
>  
>  // Δημιουργεί αντικείμενο Presentation που αντιπροσωπεύει ένα αρχείο παρουσίασης
>  Presentation pres = new Presentation("HelloWorld.pptx");
>  try {
>      SwfOptions swfOptions = new SwfOptions();
>      swfOptions.setViewerIncluded(false);
>      INotesCommentsLayoutingOptions notesOptions = swfOptions.getNotesCommentsLayouting();
>      notesOptions.setNotesPosition(NotesPositions.BottomFull);
>      // Αποθήκευση παρουσίασης και σελίδων σημειώσεων
>      pres.save("SaveAsSwf_out.swf", SaveFormat.Swf, swfOptions);
>      swfOptions.setViewerIncluded(true);
>      pres.save("SaveNotes_out.swf", SaveFormat.Swf, swfOptions);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

## Κατασκευαστές

| Constructor | Description |
| --- | --- |
| [SwfOptions()](#SwfOptions--) | Προεπιλεγμένος κατασκευαστής. |
## Μέθοδοι

| Method | Description |
| --- | --- |
| [getShowHiddenSlides()](#getShowHiddenSlides--) | Καθορίζει εάν το παραγόμενο έγγραφο πρέπει να περιλαμβάνει κρυφές διαφάνειες ή όχι. |
| [setShowHiddenSlides(boolean value)](#setShowHiddenSlides-boolean-) | Καθορίζει εάν το παραγόμενο έγγραφο πρέπει να περιλαμβάνει κρυφές διαφάνειες ή όχι. |
| [getCompressed()](#getCompressed--) | Καθορίζει εάν το παραγόμενο έγγραφο SWF πρέπει να συμπιεστεί ή όχι. |
| [setCompressed(boolean value)](#setCompressed-boolean-) | Καθορίζει εάν το παραγόμενο έγγραφο SWF πρέπει να συμπιεστεί ή όχι. |
| [getViewerIncluded()](#getViewerIncluded--) | Καθορίζει εάν το παραγόμενο έγγραφο SWF πρέπει να περιλαμβάνει τον ενσωματωμένο προβολέα εγγράφων ή όχι. |
| [setViewerIncluded(boolean value)](#setViewerIncluded-boolean-) | Καθορίζει εάν το παραγόμενο έγγραφο SWF πρέπει να περιλαμβάνει τον ενσωματωμένο προβολέα εγγράφων ή όχι. |
| [getShowPageBorder()](#getShowPageBorder--) | Καθορίζει εάν θα εμφανίζεται το περίγραμμα γύρω από τις σελίδες. |
| [setShowPageBorder(boolean value)](#setShowPageBorder-boolean-) | Καθορίζει εάν θα εμφανίζεται το περίγραμμα γύρω από τις σελίδες. |
| [getShowFullScreen()](#getShowFullScreen--) | Εμφάνιση/απόκρυψη κουμπιού πλήρους οθνης. |
| [setShowFullScreen(boolean value)](#setShowFullScreen-boolean-) | Εμφάνιση/απόκρυψη κουμπιού πλήρους οθνης. |
| [getShowPageStepper()](#getShowPageStepper--) | Εμφάνιση/απόκρυψη προοδευτή σελίδας. |
| [setShowPageStepper(boolean value)](#setShowPageStepper-boolean-) | Εμφάνιση/απόκρυψη προοδευτή σελίδας. |
| [getShowSearch()](#getShowSearch--) | Εμφάνιση/απόκρυψη περιοχής αναζήτησης. |
| [setShowSearch(boolean value)](#setShowSearch-boolean-) | Εμφάνιση/απόκρυψη περιοχής αναζήτησης. |
| [getShowTopPane()](#getShowTopPane--) | Εμφάνιση/απόκρυψη ολόκληρης της άνω περιοχής. |
| [setShowTopPane(boolean value)](#setShowTopPane-boolean-) | Εμφάνιση/απόκρυψη ολόκληρης της άνω περιοχής. |
| [getShowBottomPane()](#getShowBottomPane--) | Εμφάνιση/απόκρυψη της κάτω περιοχής. |
| [setShowBottomPane(boolean value)](#setShowBottomPane-boolean-) | Εμφάνιση/απόκρυψη της κάτω περιοχής. |
| [getShowLeftPane()](#getShowLeftPane--) | Εμφάνιση/απόκρυψη αριστερής περιοχής. |
| [setShowLeftPane(boolean value)](#setShowLeftPane-boolean-) | Εμφάνιση/απόκρυψη αριστερής περιοχής. |
| [getStartOpenLeftPane()](#getStartOpenLeftPane--) | Έναρξη με ανοιχτή αριστερή περιοχή. |
| [setStartOpenLeftPane(boolean value)](#setStartOpenLeftPane-boolean-) | Έναρξη με ανοιχτή αριστερή περιοχή. |
| [getEnableContextMenu()](#getEnableContextMenu--) | Ενεργοποίηση/απενεργοποίηση μενού περιβάλλοντος. |
| [setEnableContextMenu(boolean value)](#setEnableContextMenu-boolean-) | Ενεργοποίηση/απενεργοποίηση μενού περιβάλλοντος. |
| [getLogoImageBytes()](#getLogoImageBytes--) | Image that will be displayed as logo in the top right corner of the viewer. |
| [setLogoImageBytes(byte[] value)](#setLogoImageBytes-byte---) | Image that will be displayed as logo in the top right corner of the viewer. |
| [getLogoLink()](#getLogoLink--) | Αποκτά ή ορίζει τη πλήρη διεύθυνση υπερσύνδεσμου για ένα λογότυπο. |
| [setLogoLink(String value)](#setLogoLink-java.lang.String-) | Αποκτά ή ορίζει τη πλήρη διεύθυνση υπερσύνδεσμου για ένα λογότυπο. |
| [getJpegQuality()](#getJpegQuality--) | Καθορίζει την ποιότητα των εικόνων JPEG. |
| [setJpegQuality(int value)](#setJpegQuality-int-) | Καθορίζει την ποιότητα των εικόνων JPEG. |
| [getSlidesLayoutOptions()](#getSlidesLayoutOptions--) | Αποκτά ή ορίζει τη λειτουργία με την οποία οι διαφάνειες τοποθετούνται στη σελίδα κατά την εξαγωγή μιας παρουσίασης [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions). |
| [setSlidesLayoutOptions(ISlidesLayoutOptions value)](#setSlidesLayoutOptions-com.aspose.slides.ISlidesLayoutOptions-) | Αποκτά ή ορίζει τη λειτουργία με την οποία οι διαφάνειες τοποθετούνται στη σελίδα κατά την εξαγωγή μιας παρουσίασης [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions). |

### SwfOptions() {#SwfOptions--}
```
public SwfOptions()
```

Προεπιλεγμένος κατασκευαστής.

### getShowHiddenSlides() {#getShowHiddenSlides--}
```
public final boolean getShowHiddenSlides()
```

Καθορίζει εάν το παραγόμενο έγγραφο πρέπει να περιλαμβάνει κρυφές διαφάνειες ή όχι. Η προεπιλογή είναι false.

**Επιστρέφει:**
boolean
### setShowHiddenSlides(boolean value) {#setShowHiddenSlides-boolean-}
```
public final void setShowHiddenSlides(boolean value)
```

Καθορίζει εάν το παραγόμενο έγγραφο πρέπει να περιλαμβάνει κρυφές διαφάνειες ή όχι. Η προεπιλογή είναι false.

**Παράμετροι:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getCompressed() {#getCompressed--}
```
public final boolean getCompressed()
```

Καθορίζει εάν το παραγόμενο έγγραφο SWF πρέπει να συμπιεστεί ή όχι. Η προεπιλογή είναι true.

**Επιστρέφει:**
boolean
### setCompressed(boolean value) {#setCompressed-boolean-}
```
public final void setCompressed(boolean value)
```

Καθορίζει εάν το παραγόμενο έγγραφο SWF πρέπει να συμπιεστεί ή όχι. Η προεπιλογή είναι true.

**Παράμετροι:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getViewerIncluded() {#getViewerIncluded--}
```
public final boolean getViewerIncluded()
```

Καθορίζει εάν το παραγόμενο έγγραφο SWF πρέπει να περιλαμβάνει τον ενσωματωμένο προβολέα εγγράφων ή όχι. Η προεπιλογή είναι true.

**Επιστρέφει:**
boolean
### setViewerIncluded(boolean value) {#setViewerIncluded-boolean-}
```
public final void setViewerIncluded(boolean value)
```

Καθορίζει εάν το παραγόμενο έγγραφο SWF πρέπει να περιλαμβάνει τον ενσωματωμένο προβολέα εγγράφων ή όχι. Η προεπιλογή είναι true.

**Παράμετροι:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getShowPageBorder() {#getShowPageBorder--}
```
public final boolean getShowPageBorder()
```

Καθορίζει εάν θα εμφανίζεται το περίγραμμα γύρω από τις σελίδες. Η προεπιλογή είναι true.

**Επιστρέφει:**
boolean
### setShowPageBorder(boolean value) {#setShowPageBorder-boolean-}
```
public final void setShowPageBorder(boolean value)
```

Καθορίζει εάν θα εμφανίζεται το περίγραμμα γύρω από τις σελίδες. Η προεπιλογή είναι true.

**Παράμετροι:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getShowFullScreen() {#getShowFullScreen--}
```
public final boolean getShowFullScreen()
```

Εμφάνιση/απόκρυψη κουμπιού πλήρους οθνης. Μπορεί να αντικατασταθεί μέσω flashvars. Η προεπιλογή είναι true.

**Επιστρέφει:**
boolean
### setShowFullScreen(boolean value) {#setShowFullScreen-boolean-}
```
public final void setShowFullScreen(boolean value)
```

Εμφάνιση/απόκρυψη κουμπιού πλήρους οθνης. Μπορεί να αντικατασταθεί μέσω flashvars. Η προεπιλογή είναι true.

**Παράμετροι:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getShowPageStepper() {#getShowPageStepper--}
```
public final boolean getShowPageStepper()
```

Εμφάνιση/απόκρυψη προοδευτή σελίδας. Μπορεί να αντικατασταθεί μέσω flashvars. Η προεπιλογή είναι true.

**Επιστρέφει:**
boolean
### setShowPageStepper(boolean value) {#setShowPageStepper-boolean-}
```
public final void setShowPageStepper(boolean value)
```

Εμφάνιση/απόκρυψη προοδευτή σελίδας. Μπορεί να αντικατασταθεί μέσω flashvars. Η προεπιλογή είναι true.

**Παράμετροι:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getShowSearch() {#getShowSearch--}
```
public final boolean getShowSearch()
```

Εμφάνιση/απόκρυψη περιοχής αναζήτησης. Μπορεί να αντικατασταθεί μέσω flashvars. Η προεπιλογή είναι true.

**Επιστρέφει:**
boolean
### setShowSearch(boolean value) {#setShowSearch-boolean-}
```
public final void setShowSearch(boolean value)
```

Εμφάνιση/απόκρυψη περιοχής αναζήτησης. Μπορεί να αντικατασταθεί μέσω flashvars. Η προεπιλογή είναι true.

**Παράμετροι:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getShowTopPane() {#getShowTopPane--}
```
public final boolean getShowTopPane()
```

Εμφάνιση/απόκρυψη ολόκληρης της άνω περιοχής. Μπορεί να αντικατασταθεί μέσω flashvars. Η προεπιλογή είναι true.

**Επιστρέφει:**
boolean
### setShowTopPane(boolean value) {#setShowTopPane-boolean-}
```
public final void setShowTopPane(boolean value)
```

Εμφάνιση/απόκρυψη ολόκληρης της άνω περιοχής. Μπορεί να αντικατασταθεί μέσω flashvars. Η προεπιλογή είναι true.

**Παράμετροι:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getShowBottomPane() {#getShowBottomPane--}
```
public final boolean getShowBottomPane()
```

Εμφάνιση/απόκρυψη της κάτω περιοχής. Μπορεί να αντικατασταθεί μέσω flashvars. Η προεπιλογή είναι true.

**Επιστρέφει:**
boolean
### setShowBottomPane(boolean value) {#setShowBottomPane-boolean-}
```
public final void setShowBottomPane(boolean value)
```

Εμφάνιση/απόκρυψη της κάτω περιοχής. Μπορεί να αντικατασταθεί μέσω flashvars. Η προεπιλογή είναι true.

**Παράμετροι:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getShowLeftPane() {#getShowLeftPane--}
```
public final boolean getShowLeftPane()
```

Εμφάνιση/απόκρυψη αριστερής περιοχής. Μπορεί να αντικατασταθεί μέσω flashvars. Η προεπιλογή είναι true.

**Επιστρέφει:**
boolean
### setShowLeftPane(boolean value) {#setShowLeftPane-boolean-}
```
public final void setShowLeftPane(boolean value)
```

Εμφάνιση/απόκρυψη αριστερής περιοίας. Μπορεί να αντικατασταθεί μέσω flashvars. Η προεπιλογή είναι true.

**Παράμετροι:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getStartOpenLeftPane() {#getStartOpenLeftPane--}
```
public final boolean getStartOpenLeftPane()
```

Έναρξη με ανοιχτή αριστερή περιοχή. Μπορεί να αντικατασταθεί μέσω flashvars. Η προεπιλογή είναι false.

**Επιστρέφει:**
boolean
### setStartOpenLeftPane(boolean value) {#setStartOpenLeftPane-boolean-}
```
public final void setStartOpenLeftPane(boolean value)
```

Έναρξη με ανοιχτή αριστερή περιοχή. Μπορεί να αντικατασταθεί μέσω flashvars. Η προεπιλογή είναι false.

**Παράμετροι:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getEnableContextMenu() {#getEnableContextMenu--}
```
public final boolean getEnableContextMenu()
```

Ενεργοποίηση/απενεργοποίηση μενού περιβάλλοντος. Η προεπιλογή είναι true.

**Επιστρέφει:**
boolean
### setEnableContextMenu(boolean value) {#setEnableContextMenu-boolean-}
```
public final void setEnableContextMenu(boolean value)
```

Ενεργοποίηση/απενεργοποίηση μενού περιβάλλοντος. Η προεπιλογή είναι true.

**Παράμετροι:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getLogoImageBytes() {#getLogoImageBytes--}
```
public final byte[] getLogoImageBytes()
```

Εικόνα που θα εμφανίζεται ως λογότυπο στην επάνω δεξιά γωνία του προβολέα. Η εικόνα πρέπει να είναι PNG με διαστάσεις 32x64 pixels, διαφορετικά το λογότυπο μπορεί να εμφανιστεί εσφαλμένα.

**Επιστρέφει:**
byte[]
### setLogoImageBytes(byte[] value) {#setLogoImageBytes-byte---}
```
public final void setLogoImageBytes(byte[] value)
```

Εικόνα που θα εμφανίζεται ως λογότυπο στην επάνω δεξιά γωνία του προβολέα. Η εικόνα πρέπει να είναι PNG με διαστάσεις 32x64 pixels, διαφορετικά το λογότυπο μπορεί να εμφανιστεί εσφαλμένα.

**Παράμετροι:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | byte[] |  |

### getLogoLink() {#getLogoLink--}
```
public final String getLogoLink()
```

Αποκτά ή ορίζει τη πλήρη διεύθυνση υπερσύνδεσμου για ένα λογότυπο. Έχει αποτέλεσμα μόνο εάν έχει οριστεί ένα (\#getLogoImageBytes.getLogoImageBytes/\#setLogoImageBytes(byte[]).setLogoImageBytes(byte[])).

**Επιστρέφει:**
java.lang.String
### setLogoLink(String value) {#setLogoLink-java.lang.String-}
```
public final void setLogoLink(String value)
```

Αποκτά ή ορίζει τη πλήρη διεύθυνση υπερσύνδεσμου για ένα λογότυπο. Έχει αποτέλεσμα μόνο εάν έχει οριστεί ένα (\#getLogoImageBytes.getLogoImageBytes/\#setLogoImageBytes(byte[]).setLogoImageBytes(byte[])).

**Παράμετροι:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### getJpegQuality() {#getJpegQuality--}
```
public final int getJpegQuality()
```

Καθορίζει την ποιότητα των εικόνων JPEG. Η προεπιλογή είναι 95.

**Επιστρέφει:**
int
### setJpegQuality(int value) {#setJpegQuality-int-}
```
public final void setJpegQuality(int value)
```

Καθορίζει την ποιότητα των εικόνων JPEG. Η προεπιλογή είναι 95.

**Παράμετροι:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getSlidesLayoutOptions() {#getSlidesLayoutOptions--}
```
public final ISlidesLayoutOptions getSlidesLayoutOptions()
```

Αποκτά ή ορίζει τη λειτουργία με την οποία οι διαφάνειες τοποθετούνται στη σελίδα κατά την εξαγωγή μιας παρουσίασης [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions). Αυτή η ιδιότητα δεν υποστηρίζει την ανάθεση αντικειμένων τύπου [HandoutLayoutingOptions](../../com.aspose.slides/handoutlayoutingoptions)

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      NotesCommentsLayoutingOptions notesOptions = new NotesCommentsLayoutingOptions();
>      notesOptions.setCommentsPosition(CommentsPositions.Right);
> 
>      SwfOptions options = new SwfOptions();
>      options.setSlidesLayoutOptions(notesOptions);
> 
>      pres.save("pres.swf", SaveFormat.Swf, options);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Επιστρέφει:**
[ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions)
### setSlidesLayoutOptions(ISlidesLayoutOptions value) {#setSlidesLayoutOptions-com.aspose.slides.ISlidesLayoutOptions-}
```
public final void setSlidesLayoutOptions(ISlidesLayoutOptions value)
```

Αποκτά ή ορίζει τη λειτουργία με την οποία οι διαφάνειες τοποθετούνται στη σελίδα κατά την εξαγωγή μιας παρουσίασης [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions). Αυτή η ιδιότητα δεν υποστηρίζει την ανάθεση αντικειμένων τύπου [HandoutLayoutingOptions](../../com.aspose.slides/handoutlayoutingoptions).

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      NotesCommentsLayoutingOptions notesOptions = new NotesCommentsLayoutingOptions();
>      notesOptions.setCommentsPosition(CommentsPositions.Right);
> 
>      SwfOptions options = new SwfOptions();
>      options.setSlidesLayoutOptions(notesOptions);
> 
>      pres.save("pres.swf", SaveFormat.Swf, options);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Παράμετροι:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions) |  |