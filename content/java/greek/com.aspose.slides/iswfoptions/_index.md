---
title: ISwfOptions
second_title: Αναφορά API Aspose.Slides για Java
description: Παρέχει επιλογές που ελέγχουν πώς αποθηκεύεται μια παρουσίαση σε μορφή SWF.
type: docs
url: /el/com.aspose.slides/iswfoptions/
---
**All Implemented Interfaces:**
[com.aspose.slides.ISaveOptions](../../com.aspose.slides/isaveoptions)
```
public interface ISwfOptions extends ISaveOptions
```

Παρέχει επιλογές που ελέγχουν πώς αποθηκεύεται μια παρουσίαση σε μορφή SWF.

## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [getCompressed()](#getCompressed--) | Καθορίζει εάν το παραγόμενο έγγραφο SWF πρέπει να συμπιεστεί ή όχι. |
| [setCompressed(boolean value)](#setCompressed-boolean-) | Καθορίζει εάν το παραγόμενο έγγραφο SWF πρέπει να συμπιεστεί ή όχι. |
| [getViewerIncluded()](#getViewerIncluded--) | Καθορίζει εάν το παραγόμενο έγγραφο SWF πρέπει να περιλαμβάνει τον ενσωματωμένο προβολέα εγγράφων ή όχι. |
| [setViewerIncluded(boolean value)](#setViewerIncluded-boolean-) | Καθορίζει εάν το παραγόμενο έγγραφο SWF πρέπει να περιλαμβάνει τον ενσωματωμένο προβολέα εγγράφων ή όχι. |
| [getShowPageBorder()](#getShowPageBorder--) | Καθορίζει εάν θα εμφανίζεται το περίγραμμα γύρω από τις σελίδες. |
| [setShowPageBorder(boolean value)](#setShowPageBorder-boolean-) | Καθορίζει εάν θα εμφανίζεται το περίγραμμα γύρω από τις σελίδες. |
| [getShowHiddenSlides()](#getShowHiddenSlides--) | Καθορίζει εάν το παραγόμενο έγγραφο πρέπει να περιλαμβάνει κρυφές διαφάνειες ή όχι. |
| [setShowHiddenSlides(boolean value)](#setShowHiddenSlides-boolean-) | Καθορίζει εάν το παραγόμενο έγγραφο πρέπει να περιλαμβάνει κρυφές διαφάνειες ή όχι. |
| [getShowFullScreen()](#getShowFullScreen--) | Εμφάνιση/απόκρυψη κουμπιού πλήρους οθόνης. |
| [setShowFullScreen(boolean value)](#setShowFullScreen-boolean-) | Εμφάνιση/απόκρυψη κουμπιού πλήρους οθόνης. |
| [getShowPageStepper()](#getShowPageStepper--) | Εμφάνιση/απόκρυψη βηματιδίου σελίδας. |
| [setShowPageStepper(boolean value)](#setShowPageStepper-boolean-) | Εμφάνιση/απόκρυψη βηματιδίου σελίδας. |
| [getShowSearch()](#getShowSearch--) | Εμφάνιση/απόκρυψη ενότητας αναζήτησης. |
| [setShowSearch(boolean value)](#setShowSearch-boolean-) | Εμφάνιση/απόκρυψη ενότητας αναζήτησης. |
| [getShowTopPane()](#getShowTopPane--) | Εμφάνιση/απόκρυψη ολόκληρης της επάνω περιοχής. |
| [setShowTopPane(boolean value)](#setShowTopPane-boolean-) | Εμφάνιση/απόκρυψη ολόκληρης της επάνω περιοχής. |
| [getShowBottomPane()](#getShowBottomPane--) | Εμφάνιση/απόκρυψη κάτω περιοχής. |
| [setShowBottomPane(boolean value)](#setShowBottomPane-boolean-) | Εμφάνιση/απόκρυψη κάτω περιοχής. |
| [getShowLeftPane()](#getShowLeftPane--) | Εμφάνιση/απόκρυψη αριστερής περιοχής. |
| [setShowLeftPane(boolean value)](#setShowLeftPane-boolean-) | Εμφάνιση/απόκρυψη αριστερής περιοχής. |
| [getStartOpenLeftPane()](#getStartOpenLeftPane--) | Έναρξη με ανοιγμένη αριστερή περιοχή. |
| [setStartOpenLeftPane(boolean value)](#setStartOpenLeftPane-boolean-) | Έναρξη με ανοιγμένη αριστερή περιοχή. |
| [getEnableContextMenu()](#getEnableContextMenu--) | Ενεργοποίηση/απενεργοποίηση μενού περιβάλλοντος. |
| [setEnableContextMenu(boolean value)](#setEnableContextMenu-boolean-) | Ενεργοποίηση/απενεργοποίηση μενού περιβάλλοντος. |
| [getLogoImageBytes()](#getLogoImageBytes--) | Εικόνα που θα εμφανίζεται ως λογότυπο στην επάνω δεξιά γωνία του προβολέα. Η εικόνα πρέπει να είναι PNG 32x64 pixels, διαφορετικά το λογότυπο μπορεί να εμφανιστεί λανθασμένα. |
| [setLogoImageBytes(byte[] value)](#setLogoImageBytes-byte---) | Εικόνα που θα εμφανίζεται ως λογότυπο στην επάνω δεξιά γωνία του προβολέα. Η εικόνα πρέπει να είναι PNG 32x64 pixels, διαφορετικά το λογότυπο μπορεί να εμφανιστεί λανθασμένα. |
| [getLogoLink()](#getLogoLink--) | Λαμβάνει ή ορίζει τη πλήρη διεύθυνση υπερσυνδέσμου για ένα λογότυπο. |
| [setLogoLink(String value)](#setLogoLink-java.lang.String-) | Λαμβάνει ή ορίζει τη πλήρη διεύθυνση υπερσυνδέσμου για ένα λογότυπο. |
| [getJpegQuality()](#getJpegQuality--) | Καθορίζει την ποιότητα των εικόνων JPEG. |
| [setJpegQuality(int value)](#setJpegQuality-int-) | Καθορίζει την ποιότητα των εικόνων JPEG. |
| [getSlidesLayoutOptions()](#getSlidesLayoutOptions--) | Λαμβάνει ή ορίζει τη λειτουργία με την οποία οι διαφάνειες τοποθετούνται στη σελίδα κατά την εξαγωγή μιας παρουσίασης [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions). |
| [setSlidesLayoutOptions(ISlidesLayoutOptions value)](#setSlidesLayoutOptions-com.aspose.slides.ISlidesLayoutOptions-) | Λαμβάνει ή ορίζει τη λειτουργία με την οποία οι διαφάνειες τοποθετούνται στη σελίδα κατά την εξαγωγή μιας παρουσίασης [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions). |

### getCompressed() {#getCompressed--}
```
public abstract boolean getCompressed()
```

Καθορίζει εάν το παραγόμενο έγγραφο SWF πρέπει να συμπιεστεί ή όχι. Η προεπιλογή είναι true.

**Επιστρέφει:**
boolean

### setCompressed(boolean value) {#setCompressed-boolean-}
```
public abstract void setCompressed(boolean value)
```

Καθορίζει εάν το παραγόμενο έγγραφο SWF πρέπει να συμπιεστεί ή όχι. Η προεπιλογή είναι true.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | boolean |  |

### getViewerIncluded() {#getViewerIncluded--}
```
public abstract boolean getViewerIncluded()
```

Καθορίζει εάν το παραγόμενο έγγραφο SWF πρέπει να περιλαμβάνει τον ενσωματωμένο προβολέα εγγράφων ή όχι. Η προεπιλογή είναι true.

**Επιστρέφει:**
boolean

### setViewerIncluded(boolean value) {#setViewerIncluded-boolean-}
```
public abstract void setViewerIncluded(boolean value)
```

Καθορίζει εάν το παραγόμενο έγγραφο SWF πρέπει να περιλαμβάνει τον ενσωματωμένο προβολέα εγγράφων ή όχι. Η προεπιλογή είναι true.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | boolean |  |

### getShowPageBorder() {#getShowPageBorder--}
```
public abstract boolean getShowPageBorder()
```

Καθορίζει εάν θα εμφανίζεται το περίγραμμα γύρω από τις σελίδες. Η προεπιλογή είναι true.

**Επιστρέφει:**
boolean

### setShowPageBorder(boolean value) {#setShowPageBorder-boolean-}
```
public abstract void setShowPageBorder(boolean value)
```

Καθορίζει εάν θα εμφανίζεται το περίγραμμα γύρω από τις σελίδες. Η προεπιλογή είναι true.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | boolean |  |

### getShowHiddenSlides() {#getShowHiddenSlides--}
```
public abstract boolean getShowHiddenSlides()
```

Καθορίζει εάν το παραγόμενο έγγραφο πρέπει να περιλαμβάνει κρυφές διαφάνειες ή όχι. Η προεπιλογή είναι false.

**Επιστρέφει:**
boolean

### setShowHiddenSlides(boolean value) {#setShowHiddenSlides-boolean-}
```
public abstract void setShowHiddenSlides(boolean value)
```

Καθορίζει εάν το παραγόμενο έγγραφο πρέπει να περιλαμβάνει κρυφές διαφάνειες ή όχι. Η προεπιλογή είναι false.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | boolean |  |

### getShowFullScreen() {#getShowFullScreen--}
```
public abstract boolean getShowFullScreen()
```

Εμφάνιση/απόκρυψη κουμπιού πλήρους οθόνης. Μπορεί να παρακαμφθεί μέσω flashvars. Η προεπιλογή είναι true.

**Επιστρέφει:**
boolean

### setShowFullScreen(boolean value) {#setShowFullScreen-boolean-}
```
public abstract void setShowFullScreen(boolean value)
```

Εμφάνιση/απόκρυψη κουμπιού πλήρους οθόνης. Μπορεί να παρακαμφθεί μέσω flashvars. Η προεπιλογή είναι true.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | boolean |  |

### getShowPageStepper() {#getShowPageStepper--}
```
public abstract boolean getShowPageStepper()
```

Εμφάνιση/απόκρυψη βηματιδίου σελίδας. Μπορεί να παρακαμφθεί μέσω flashvars. Η προεπιλογή είναι true.

**Επιστρέφει:**
boolean

### setShowPageStepper(boolean value) {#setShowPageStepper-boolean-}
```
public abstract void setShowPageStepper(boolean value)
```

Εμφάνιση/απόκρυψη βηματιδίου σελίδας. Μπορεί να παρακαμφθεί μέσω flashvars. Η προεπιλογή είναι true.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | boolean |  |

### getShowSearch() {#getShowSearch--}
```
public abstract boolean getShowSearch()
```

Εμφάνιση/απόκρυψη ενότητας αναζήτησης. Μπορεί να παρακαμφθεί μέσω flashvars. Η προεπιλογή είναι true.

**Επιστρέφει:**
boolean

### setShowSearch(boolean value) {#setShowSearch-boolean-}
```
public abstract void setShowSearch(boolean value)
```

Εμφάνιση/απόκρυψη ενότητας αναζήτησης. Μπορεί να παρακαμφθεί μέσω flashvars. Η προεπιλογή είναι true.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | boolean |  |

### getShowTopPane() {#getShowTopPane--}
```
public abstract boolean getShowTopPane()
```

Εμφάνιση/απόκρυψη ολόκληρης της επάνω περιοχής. Μπορεί να παρακαμφθεί μέσω flashvars. Η προεπιλογή είναι true.

**Επιστρέφει:**
boolean

### setShowTopPane(boolean value) {#setShowTopPane-boolean-}
```
public abstract void setShowTopPane(boolean value)
```

Εμφάνιση/απόκρυψη ολόκληρης της επάνω περιοχής. Μπορεί να παρακαμφθεί μέσω flashvars. Η προεπιλογή είναι true.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | boolean |  |

### getShowBottomPane() {#getShowBottomPane--}
```
public abstract boolean getShowBottomPane()
```

Εμφάνιση/απόκρυψη κάτω περιοχής. Μπορεί να παρακαμφθεί μέσω flashvars. Η προεπιλογή είναι true.

**Επιστρέφει:**
boolean

### setShowBottomPane(boolean value) {#setShowBottomPane-boolean-}
```
public abstract void setShowBottomPane(boolean value)
```

Εμφάνιση/απόκρυψη κάτω περιοχής. Μπορεί να παρακαμφθεί μέσω flashvars. Η προεπιλογή είναι true.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | boolean |  |

### getShowLeftPane() {#getShowLeftPane--}
```
public abstract boolean getShowLeftPane()
```

Εμφάνιση/απόκρυψη αριστερής περιοχής. Μπορεί να παρακαμφθεί μέσω flashvars. Η προεπιλογή είναι true.

**Επιστρέφει:**
boolean

### setShowLeftPane(boolean value) {#setShowLeftPane-boolean-}
```
public abstract void setShowLeftPane(boolean value)
```

Εμφάνιση/απόκρυψη αριστερής περιοχής. Μπορεί να παρακαμφθεί μέσω flashvars. Η προεπιλογή είναι true.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | boolean |  |

### getStartOpenLeftPane() {#getStartOpenLeftPane--}
```
public abstract boolean getStartOpenLeftPane()
```

Έναρξη με ανοιγμένη αριστερή περιοχή. Μπορεί να παρακαμφθεί μέσω flashvars. Η προεπιλογή είναι false.

**Επιστρέφει:**
boolean

### setStartOpenLeftPane(boolean value) {#setStartOpenLeftPane-boolean-}
```
public abstract void setStartOpenLeftPane(boolean value)
```

Έναρξη με ανοιγμένη αριστερή περιοχή. Μπορεί να παρακαμφθεί μέσω flashvars. Η προεπιλογή είναι false.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | boolean |  |

### getEnableContextMenu() {#getEnableContextMenu--}
```
public abstract boolean getEnableContextMenu()
```

Ενεργοποίηση/απενεργοποίηση μενού περιβάλλοντος. Η προεπιλογή είναι true.

**Επιστρέφει:**
boolean

### setEnableContextMenu(boolean value) {#setEnableContextMenu-boolean-}
```
public abstract void setEnableContextMenu(boolean value)
```

Ενεργοποίηση/απενεργοποίηση μενού περιβάλλοντος. Η προεπιλογή είναι true.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | boolean |  |

### getLogoImageBytes() {#getLogoImageBytes--}
```
public abstract byte[] getLogoImageBytes()
```

Εικόνα που θα εμφανίζεται ως λογότυπο στην επάνω δεξιά γωνία του προβολέα. Η εικόνα πρέπει να είναι PNG 32x64 pixels, διαφορετικά το λογότυπο μπορεί να εμφανιστεί λανθασμένα.

**Επιστρέφει:**
byte[]

### setLogoImageBytes(byte[] value) {#setLogoImageBytes-byte---}
```
public abstract void setLogoImageBytes(byte[] value)
```

Εικόνα που θα εμφανίζεται ως λογότυπο στην επάνω δεξιά γωνία του προβολέα. Η εικόνα πρέπει να είναι PNG 32x64 pixels, διαφορετικά το λογότυπο μπορεί να εμφανιστεί λανθασμένα.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | byte[] |  |

### getLogoLink() {#getLogoLink--}
```
public abstract String getLogoLink()
```

Λαμβάνει ή ορίζει τη πλήρη διεύθυνση υπερσυνδέσμου για ένα λογότυπο. Έχει αποτέλεσμα μόνο εάν έχει οριστεί ένα (\#getLogoImageBytes.getLogoImageBytes/\#setLogoImageBytes(byte[]).setLogoImageBytes(byte[])).

**Επιστρέφει:**
java.lang.String

### setLogoLink(String value) {#setLogoLink-java.lang.String-}
```
public abstract void setLogoLink(String value)
```

Λαμβάνει ή ορίζει τη πλήρη διεύθυνση υπερσυνδέσμου για ένα λογότυπο. Έχει αποτέλεσμα μόνο εάν έχει οριστεί ένα (\#getLogoImageBytes.getLogoImageBytes/\#setLogoImageBytes(byte[]).setLogoImageBytes(byte[])).

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | java.lang.String |  |

### getJpegQuality() {#getJpegQuality--}
```
public abstract int getJpegQuality()
```

Καθορίζει την ποιότητα των εικόνων JPEG. Η προεπιλογή είναι 95.

**Επιστρέφει:**
int

### setJpegQuality(int value) {#setJpegQuality-int-}
```
public abstract void setJpegQuality(int value)
```

Καθορίζει την ποιότητα των εικόνων JPEG. Η προεπιλογή είναι 95.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | int |  |

### getSlidesLayoutOptions() {#getSlidesLayoutOptions--}
```
public abstract ISlidesLayoutOptions getSlidesLayoutOptions()
```

Λαμβάνει ή ορίζει τη λειτουργία με την οποία οι διαφάνειες τοποθετούνται στη σελίδα κατά την εξαγωγή μιας παρουσίασης [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions). Αυτή η ιδιότητα δεν υποστηρίζει την ανάθεση αντικειμένων τύπου [HandoutLayoutingOptions](../../com.aspose.slides/handoutlayoutingoptions)

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
public abstract void setSlidesLayoutOptions(ISlidesLayoutOptions value)
```

Λαμβάνει ή ορίζει τη λειτουργία με την οποία οι διαφάνειες τοποθετούνται στη σελίδα κατά την εξαγωγή μιας παρουσίασης [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions). Αυτή η ιδιότητα δεν υποστηρίζει την ανάθεση αντικειμένων τύπου [HandoutLayoutingOptions](../../com.aspose.slides/handoutlayoutingoptions)

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
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions) |  |