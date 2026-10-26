---
title: ISwfOptions
second_title: Aspose.Slides για Android μέσω Java API Reference
description: Παρέχει επιλογές που ελέγχουν πώς αποθηκεύεται μια παρουσίαση σε μορφή SWF.
type: docs
url: /el/com.aspose.slides/iswfoptions/
---
**Όλες οι υλοποιημένες διεπαφές:**
[com.aspose.slides.ISaveOptions](../../com.aspose.slides/isaveoptions)
```
public interface ISwfOptions extends ISaveOptions
```

Παρέχει επιλογές που ελέγχουν πώς αποθηκεύεται μια παρουσίαση σε μορφή SWF.
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [getCompressed()](#getCompressed--) | Καθορίζει αν το παραγόμενο έγγραφο SWF πρέπει να συμπιεστεί ή όχι. |
| [setCompressed(boolean value)](#setCompressed-boolean-) | Καθορίζει αν το παραγόμενο έγγραφο SWF πρέπει να συμπιεστεί ή όχι. |
| [getViewerIncluded()](#getViewerIncluded--) | Καθορίζει αν το παραγόμενο έγγραφο SWF πρέπει να περιλαμβάνει τον ενσωματωμένο προβολέα εγγράφου ή όχι. |
| [setViewerIncluded(boolean value)](#setViewerIncluded-boolean-) | Καθορίζει αν το παραγόμενο έγγραφο SWF πρέπει να περιλαμβάνει τον ενσωματωμένο προβολέα εγγράφου ή όχι. |
| [getShowPageBorder()](#getShowPageBorder--) | Καθορίζει αν το περίγραμμα γύρω από τις σελίδες πρέπει να εμφανίζεται. |
| [setShowPageBorder(boolean value)](#setShowPageBorder-boolean-) | Καθορίζει αν το περίγραμμα γύρω από τις σελίδες πρέπει να εμφανίζεται. |
| [getShowHiddenSlides()](#getShowHiddenSlides--) | Καθορίζει αν το παραγόμενο έγγραφο πρέπει να περιλαμβάνει κρυφές διαφάνειες ή όχι. |
| [setShowHiddenSlides(boolean value)](#setShowHiddenSlides-boolean-) | Καθορίζει αν το παραγόμενο έγγραφο πρέπει να περιλαμβάνει κρυφές διαφάνειες ή όχι. |
| [getShowFullScreen()](#getShowFullScreen--) | Εμφανίζει/αποκρύπτει το κουμπί πλήρους οθόνης. |
| [setShowFullScreen(boolean value)](#setShowFullScreen-boolean-) | Εμφανίζει/αποκρύπτει το κουμπί πλήρους οθόνης. |
| [getShowPageStepper()](#getShowPageStepper--) | Εμφανίζει/αποκρύπτει τον επιλογέα σελίδας. |
| [setShowPageStepper(boolean value)](#setShowPageStepper-boolean-) | Εμφανίζει/αποκρύπτει τον επιλογέα σελίδας. |
| [getShowSearch()](#getShowSearch--) | Εμφανίζει/αποκρύπτει την ενότητα αναζήτησης. |
| [setShowSearch(boolean value)](#setShowSearch-boolean-) | Εμφανίζει/αποκρύπτει την ενότητα αναζήτησης. |
| [getShowTopPane()](#getShowTopPane--) | Εμφανίζει/αποκρύπτει ολόκληρο το πάνω πάνελ. |
| [setShowTopPane(boolean value)](#setShowTopPane-boolean-) | Εμφανίζει/αποκρύπτει ολόκληρο το πάνω πάνελ. |
| [getShowBottomPane()](#getShowBottomPane--) | Εμφανίζει/αποκρύπτει το κάτω πάνελ. |
| [setShowBottomPane(boolean value)](#setShowBottomPane-boolean-) | Εμφανίζει/αποκρύπτει το κάτω πάνελ. |
| [getShowLeftPane()](#getShowLeftPane--) | Εμφανίζει/αποκρύπτει το αριστερό πάνελ. |
| [setShowLeftPane(boolean value)](#setShowLeftPane-boolean-) | Εμφανίζει/αποκρύπτει το αριστερό πάνελ. |
| [getStartOpenLeftPane()](#getStartOpenLeftPane--) | Ξεκινά με ανοιχτό το αριστερό πάνελ. |
| [setStartOpenLeftPane(boolean value)](#setStartOpenLeftPane-boolean-) | Ξεκινά με ανοιχτό το αριστερό πάνελ. |
| [getEnableContextMenu()](#getEnableContextMenu--) | Ενεργοποιεί/απενεργοποιεί το μενού περιβάλλοντος. |
| [setEnableContextMenu(boolean value)](#setEnableContextMenu-boolean-) | Ενεργοποιεί/απενεργοποιεί το μενού περιβάλλοντος. |
| [getLogoImageBytes()](#getLogoImageBytes--) | Εικόνα που θα εμφανίζεται ως λογότυπο στην επάνω δεξιά γωνία του προβολέα. |
| [setLogoImageBytes(byte[] value)](#setLogoImageBytes-byte---) | Εικόνα που θα εμφανίζεται ως λογότυπο στην επάνω δεξιά γωνία του προβολέα. |
| [getLogoLink()](#getLogoLink--) | Λαμβάνει ή ορίζει τη διεύθυνση πλήρους υπερσύνδεσμου για ένα λογότυπο. |
| [setLogoLink(String value)](#setLogoLink-java.lang.String-) | Λαμβάνει ή ορίζει τη διεύθυνση πλήρους υπερσύνδεσμου για ένα λογότυπο. |
| [getJpegQuality()](#getJpegQuality--) | Καθορίζει την ποιότητα των εικόνων JPEG. |
| [setJpegQuality(int value)](#setJpegQuality-int-) | Καθορίζει την ποιότητα των εικόνων JPEG. |
| [getSlidesLayoutOptions()](#getSlidesLayoutOptions--) | Λαμβάνει ή ορίζει τη λειτουργία με την οποία τοποθετούνται οι διαφάνειες στη σελίδα κατά την εξαγωγή μιας παρουσίασης [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions). |
| [setSlidesLayoutOptions(ISlidesLayoutOptions value)](#setSlidesLayoutOptions-com.aspose.slides.ISlidesLayoutOptions-) | Λαμβάνει ή ορίζει τη λειτουργία με την οποία τοποθετούνται οι διαφάνειες στη σελίδα κατά την εξαγωγή μιας παρουσίασης [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions). |

### getCompressed() {#getCompressed--}
```
public abstract boolean getCompressed()
```

Καθορίζει αν το παραγόμενο έγγραφο SWF πρέπει να συμπιεστεί ή όχι. Η προεπιλογή είναι true.

**Επιστρέφει:**
boolean
### setCompressed(boolean value) {#setCompressed-boolean-}
```
public abstract void setCompressed(boolean value)
```

Καθορίζει αν το παραγόμενο έγγραφο SWF πρέπει να συμπιεστεί ή όχι. Η προεπιλογή είναι true.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | boolean |  |

### getViewerIncluded() {#getViewerIncluded--}
```
public abstract boolean getViewerIncluded()
```

Καθορίζει αν το παραγόμενο έγγραφο SWF πρέπει να περιλαμβάνει τον ενσωματωμένο προβολέα εγγράφου ή όχι. Η προεπιλογή είναι true.

**Επιστρέφει:**
boolean
### setViewerIncluded(boolean value) {#setViewerIncluded-boolean-}
```
public abstract void setViewerIncluded(boolean value)
```

Καθορίζει αν το παραγόμενο έγγραφο SWF πρέπει να περιλαμβάνει τον ενσωματωμένο προβολέα εγγράφου ή όχι. Η προεπιλογή είναι true.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | boolean |  |

### getShowPageBorder() {#getShowPageBorder--}
```
public abstract boolean getShowPageBorder()
```

Καθορίζει αν το περίγραμμα γύρω από τις σελίδες πρέπει να εμφανίζεται. Η προεπιλογή είναι true.

**Επιστρέφει:**
boolean
### setShowPageBorder(boolean value) {#setShowPageBorder-boolean-}
```
public abstract void setShowPageBorder(boolean value)
```

Καθορίζει αν το περίγραμμα γύρω από τις σελίδες πρέπει να εμφανίζεται. Η προεπιλογή είναι true.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | boolean |  |

### getShowHiddenSlides() {#getShowHiddenSlides--}
```
public abstract boolean getShowHiddenSlides()
```

Καθορίζει αν το παραγόμενο έγγραφο πρέπει να περιλαμβάνει κρυφές διαφάνειες ή όχι. Η προεπιλογή είναι false.

**Επιστρέφει:**
boolean
### setShowHiddenSlides(boolean value) {#setShowHiddenSlides-boolean-}
```
public abstract void setShowHiddenSlides(boolean value)
```

Καθορίζει αν το παραγόμενο έγγραφο πρέπει να περιλαμβάνει κρυφές διαφάνειες ή όχι. Η προεπιλογή είναι false.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | boolean |  |

### getShowFullScreen() {#getShowFullScreen--}
```
public abstract boolean getShowFullScreen()
```

Εμφανίζει/αποκρύπτει το κουμπί πλήρους οθόνης. Μπορεί να παρακαμφθεί στα flashvars. Η προεπιλογή είναι true.

**Επιστρέφει:**
boolean
### setShowFullScreen(boolean value) {#setShowFullScreen-boolean-}
```
public abstract void setShowFullScreen(boolean value)
```

Εμφανίζει/αποκρύπτει το κουμπί πλήρους οθόνης. Μπορεί να παρακαμφθεί στα flashvars. Η προεπιλογή είναι true.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | boolean |  |

### getShowPageStepper() {#getShowPageStepper--}
```
public abstract boolean getShowPageStepper()
```

Εμφανίζει/αποκρύπτει τον επιλογέα σελίδας. Μπορεί να παρακαμφθεί στα flashvars. Η προεπιλογή είναι true.

**Επιστρέφει:**
boolean
### setShowPageStepper(boolean value) {#setShowPageStepper-boolean-}
```
public abstract void setShowPageStepper(boolean value)
```

Εμφανίζει/αποκρύπτει τον επιλογέα σελίδας. Μπορεί να παρακαμφθεί στα flashvars. Η προεπιλογή είναι true.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | boolean |  |

### getShowSearch() {#getShowSearch--}
```
public abstract boolean getShowSearch()
```

Εμφανίζει/αποκρύπτει την ενότητα αναζήτησης. Μπορεί να παρακαμφθεί στα flashvars. Η προεπιλογή είναι true.

**Επιστρέφει:**
boolean
### setShowSearch(boolean value) {#setShowSearch-boolean-}
```
public abstract void setShowSearch(boolean value)
```

Εμφανίζει/αποκρύπτει την ενότητα αναζήτησης. Μπορεί να παρακαμφθεί στα flashvars. Η προεπιλογή είναι true.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | boolean |  |

### getShowTopPane() {#getShowTopPane--}
```
public abstract boolean getShowTopPane()
```

Εμφανίζει/αποκρύπτει ολόκληρο το πάνω πάνελ. Μπορεί να παρακαμφθεί στα flashvars. Η προεπιλογή είναι true.

**Επιστρέφει:**
boolean
### setShowTopPane(boolean value) {#setShowTopPane-boolean-}
```
public abstract void setShowTopPane(boolean value)
```

Εμφανίζει/αποκρύπτει ολόκληρο το πάνω πάνελ. Μπορεί να παρακαμφθεί στα flashvars. Η προεπιλογή είναι true.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | boolean |  |

### getShowBottomPane() {#getShowBottomPane--}
```
public abstract boolean getShowBottomPane()
```

Εμφανίζει/αποκρύπτει το κάτω πάνελ. Μπορεί να παρακαμφθεί στα flashvars. Η προεπιλογή είναι true.

**Επιστρέφει:**
boolean
### setShowBottomPane(boolean value) {#setShowBottomPane-boolean-}
```
public abstract void setShowBottomPane(boolean value)
```

Εμφανίζει/αποκρύπτει το κάτω πάνελ. Μπορεί να παρακαμφθεί στα flashvars. Η προεπιλογή είναι true.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | boolean |  |

### getShowLeftPane() {#getShowLeftPane--}
```
public abstract boolean getShowLeftPane()
```

Εμφανίζει/αποκρύπτει το αριστερό πάνελ. Μπορεί να παρακαμφθεί στα flashvars. Η προεπιλογή είναι true.

**Επιστρέφει:**
boolean
### setShowLeftPane(boolean value) {#setShowLeftPane-boolean-}
```
public abstract void setShowLeftPane(boolean value)
```

Εμφανίζει/αποκρύπτει το αριστερό πάνελ. Μπορεί να παρακαμφθεί στα flashvars. Η προεπιλογή είναι true.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | boolean |  |

### getStartOpenLeftPane() {#getStartOpenLeftPane--}
```
public abstract boolean getStartOpenLeftPane()
```

Ξεκινά με ανοιχτό το αριστερό πάνελ. Μπορεί να παρακαμφθεί στα flashvars. Η προεπιλογή είναι false.

**Επιστρέφει:**
boolean
### setStartOpenLeftPane(boolean value) {#setStartOpenLeftPane-boolean-}
```
public abstract void setStartOpenLeftPane(boolean value)
```

Ξεκινά με ανοιχτό το αριστερό πάνελ. Μπορεί να παρακαμφθεί στα flashvars. Η προεπιλογή είναι false.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | boolean |  |

### getEnableContextMenu() {#getEnableContextMenu--}
```
public abstract boolean getEnableContextMenu()
```

Ενεργοποιεί/απενεργοποιεί το μενού περιβάλλοντος. Η προεπιλογή είναι true.

**Επιστρέφει:**
boolean
### setEnableContextMenu(boolean value) {#setEnableContextMenu-boolean-}
```
public abstract void setEnableContextMenu(boolean value)
```

Ενεργοποιεί/απενεργοποιεί το μενού περιβάλλοντος. Η προεπιλογή είναι true.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | boolean |  |

### getLogoImageBytes() {#getLogoImageBytes--}
```
public abstract byte[] getLogoImageBytes()
```

Εικόνα που θα εμφανίζεται ως λογότυπο στην επάνω δεξιά γωνία του προβολέα. Η εικόνα πρέπει να είναι PNG 32x64 pixel, διαφορετικά το λογότυπο μπορεί να εμφανιστεί εσφαλμένα.

**Επιστρέφει:**
byte[]
### setLogoImageBytes(byte[] value) {#setLogoImageBytes-byte---}
```
public abstract void setLogoImageBytes(byte[] value)
```

Εικόνα που θα εμφανίζεται ως λογότυπο στην επάνω δεξιά γωνία του προβολέα. Η εικόνα πρέπει να είναι PNG 32x64 pixel, διαφορετικά το λογότυπο μπορεί να εμφανιστεί εσφαλμένα.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | byte[] |  |

### getLogoLink() {#getLogoLink--}
```
public abstract String getLogoLink()
```

Λαμβάνει ή ορίζει τη διεύθυνση πλήρους υπερσύνδεσμου για ένα λογότυπο. Έχει ισχύ μόνο αν έχει οριστεί ένα (\#getLogoImageBytes.getLogoImageBytes/\#setLogoImageBytes(byte[]).setLogoImageBytes(byte[])).

**Επιστρέφει:**
java.lang.String
### setLogoLink(String value) {#setLogoLink-java.lang.String-}
```
public abstract void setLogoLink(String value)
```

Λαμβάνει ή ορίζει τη διεύθυνση πλήρους υπερσύνδεσμου για ένα λογότυπο. Έχει ισχύ μόνο αν έχει οριστεί ένα (\#getLogoImageBytes.getLogoImageBytes/\#setLogoImageBytes(byte[]).setLogoImageBytes(byte[])).

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

Λαμβάνει ή ορίζει τη λειτουργία με την οποία τοποθετούνται οι διαφάνειες στη σελίδα κατά την εξαγωγή μιας παρουσίασης [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions). Αυτή η ιδιότητα δεν υποστηρίζει την ανάθεση αντικειμένων τύπου [HandoutLayoutingOptions](../../com.aspose.slides/handoutlayoutingoptions)

--------------------

> ```
> Παράδειγμα:
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

Λαμβάνει ή ορίζει τη λειτουργία με την οποία τοποθετούνται οι διαφάνειες στη σελίδα κατά την εξαγωγή μιας παρουσίασης [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions). Αυτή η ιδιότητα δεν υποστηρίζει την ανάθεση αντικειμένων τύπου [HandoutLayoutingOptions](../../com.aspose.slides/handoutlayoutingoptions)

--------------------

> ```
> Παράδειγμα:
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