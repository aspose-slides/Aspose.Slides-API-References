---
title: SwfOptions
second_title: Aspose.Slides για Android μέσω αναφοράς Java API
description: Παρέχει επιλογές που ελέγχουν πώς αποθηκεύεται μια παρουσίαση σε μορφή Swf.
type: docs
url: /el/com.aspose.slides/swfoptions/
---
**Κληρονομικότητα:**  
java.lang.Object, [com.aspose.slides.SaveOptions](../../com.aspose.slides/saveoptions)

**Όλες οι Υλοποιημένες Διεπαφές:**  
[com.aspose.slides.ISwfOptions](../../com.aspose.slides/iswfoptions)  
```
public class SwfOptions extends SaveOptions implements ISwfOptions
```

Παρέχει επιλογές που ελέγχουν πώς αποθηκεύεται μια παρουσίαση σε μορφή Swf.

--------------------

> ```
> The following example shows how to convert PowerPoint to SWF Flash.
>  
>  // Δημιουργήστε ένα αντικείμενο Presentation που αντιπροσωπεύει ένα αρχείο παρουσίασης
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
| [getShowHiddenSlides()](#getShowHiddenSlides--) | Καθορίζει αν το παραγόμενο έγγραφο πρέπει να περιλαμβάνει κρυφές διαφάνειες ή όχι. |
| [setShowHiddenSlides(boolean value)](#setShowHiddenSlides-boolean-) | Καθορίζει αν το παραγόμενο έγγραφο πρέπει να περιλαμβάνει κρυφές διαφάνειες ή όχι. |
| [getCompressed()](#getCompressed--) | Καθορίζει αν το παραγόμενο έγγραφο SWF πρέπει να συμπιεστεί ή όχι. |
| [setCompressed(boolean value)](#setCompressed-boolean-) | Καθορίζει αν το παραγόμενο έγγραφο SWF πρέπει να συμπιεστεί ή όχι. |
| [getViewerIncluded()](#getViewerIncluded--) | Καθορίζει αν το παραγόμενο έγγραφο SWF πρέπει να περιλαμβάνει τον ενσωματωμένο προγραμματιστή προβολής εγγράφου ή όχι. |
| [setViewerIncluded(boolean value)](#setViewerIncluded-boolean-) | Καθορίζει αν το παραγόμενο έγγραφο SWF πρέπει να περιλαμβάνει τον ενσωματωμένο προγραμματιστή προβολής εγγράφου ή όχι. |
| [getShowPageBorder()](#getShowPageBorder--) | Καθορίζει αν θα εμφανίζεται το περίγραμμα γύρω από τις σελίδες. |
| [setShowPageBorder(boolean value)](#setShowPageBorder-boolean-) | Καθορίζει αν θα εμφανίζεται το περίγραμμα γύρω από τις σελίδες. |
| [getShowFullScreen()](#getShowFullScreen--) | Εμφάνιση/απόκρυψη κουμπιού πλήρους οθόνης. |
| [setShowFullScreen(boolean value)](#setShowFullScreen-boolean-) | Εμφάνιση/απόκρυψη κουμπιού πλήρους οθόνης. |
| [getShowPageStepper()](#getShowPageStepper--) | Εμφάνιση/απόκρυψη βηματιστή σελίδας. |
| [setShowPageStepper(boolean value)](#setShowPageStepper-boolean-) | Εμφάνιση/απόκρυψη βηματιστή σελίδας. |
| [getShowSearch()](#getShowSearch--) | Εμφάνιση/απόκρυψη ενότητας αναζήτησης. |
| [setShowSearch(boolean value)](#setShowSearch-boolean-) | Εμφάνιση/απόκρυψη ενότητας αναζήτησης. |
| [getShowTopPane()](#getShowTopPane--) | Εμφάνιση/απόκρυψη ολόκληρης της επάνω περιοχής. |
| [setShowTopPane(boolean value)](#setShowTopPane-boolean-) | Εμφάνιση/απόκρυψη ολόκληρης της επάνω περιοχής. |
| [getShowBottomPane()](#getShowBottomPane--) | Εμφάνιση/απόκρυψη κάτω περιοχής. |
| [setShowBottomPane(boolean value)](#setShowBottomPane-boolean-) | Εμφάνιση/απόκρυψη κάτω περιοχής. |
| [getShowLeftPane()](#getShowLeftPane--) | Εμφάνιση/απόκρυψη αριστερής περιοχής. |
| [setShowLeftPane(boolean value)](#setShowLeftPane-boolean-) | Εμφάνιση/απόκρυψη αριστερής περιοχής. |
| [getStartOpenLeftPane()](#getStartOpenLeftPane--) | Έναρξη με ανοιχτή αριστερή περιοχή. |
| [setStartOpenLeftPane(boolean value)](#setStartOpenLeftPane-boolean-) | Έναρξη με ανοιχτή αριστερή περιοχή. |
| [getEnableContextMenu()](#getEnableContextMenu--) | Ενεργοποίηση/απενεργοποίηση του μενού περιβάλλοντος. |
| [setEnableContextMenu(boolean value)](#setEnableContextMenu-boolean-) | Ενεργοποίηση/απενεργοποίηση του μενού περιβάλλοντος. |
| [getLogoImageBytes()](#getLogoImageBytes--) | Εικόνα που θα εμφανίζεται ως λογότυπο στην επάνω δεξιά γωνία του προβολέα. |
| [setLogoImageBytes(byte[] value)](#setLogoImageBytes-byte---) | Εικόνα που θα εμφανίζεται ως λογότυπο στην επάνω δεξιά γωνία του προβολέα. |
| [getLogoLink()](#getLogoLink--) | Λαμβάνει ή ορίζει τη διεύθυνση του πλήρους υπερσυνδέσμου για ένα λογότυπο. |
| [setLogoLink(String value)](#setLogoLink-java.lang.String-) | Λαμβάνει ή ορίζει τη διεύθυνση του πλήρους υπερσυνδέσμου για ένα λογότυπο. |
| [getJpegQuality()](#getJpegQuality--) | Καθορίζει την ποιότητα των εικόνων JPEG. |
| [setJpegQuality(int value)](#setJpegQuality-int-) | Καθορίζει την ποιότητα των εικόνων JPEG. |
| [getSlidesLayoutOptions()](#getSlidesLayoutOptions--) | Λαμβάνει ή ορίζει τη λειτουργία με την οποία τοποθετούνται οι διαφάνειες στη σελίδα κατά την εξαγωγή μιας παρουσίασης [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions). |
| [setSlidesLayoutOptions(ISlidesLayoutOptions value)](#setSlidesLayoutOptions-com.aspose.slides.ISlidesLayoutOptions-) | Λαμβάνει ή ορίζει τη λειτουργία με την οποία τοποθετούνται οι διαφάνειες στη σελίδα κατά την εξαγωγή μιας παρουσίασης [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions). |
### SwfOptions() {#SwfOptions--}
```
public SwfOptions()
```


Προεπιλεγμένος κατασκευαστής.

### getShowHiddenSlides() {#getShowHiddenSlides--}
```
public final boolean getShowHiddenSlides()
```


Καθορίζει αν το παραγόμενο έγγραφο πρέπει να περιλαμβάνει κρυφές διαφάνειες ή όχι. Η προεπιλογή είναι false.

**Επιστρέφει:**  
boolean
### setShowHiddenSlides(boolean value) {#setShowHiddenSlides-boolean-}
```
public final void setShowHiddenSlides(boolean value)
```


Καθορίζει αν το παραγόμενο έγγραφο πρέπει να περιλαμβάνει κρυφές διαφάνειες ή όχι. Η προεπιλογή είναι false.

**Παράμετροι:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |
### getCompressed() {#getCompressed--}
```
public final boolean getCompressed()
```


Καθορίζει αν το παραγόμενο έγγραφο SWF πρέπει να συμπιεστεί ή όχι. Η προεπιλογή είναι true.

**Επιστρέφει:**  
boolean
### setCompressed(boolean value) {#setCompressed-boolean-}
```
public final void setCompressed(boolean value)
```


Καθορίζει αν το παραγόμενο έγγραφο SWF πρέπει να συμπιεστεί ή όχι. Η προεπιλογή είναι true.

**Παράμετροι:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |
### getViewerIncluded() {#getViewerIncluded--}
```
public final boolean getViewerIncluded()
```


Καθορίζει αν το παραγόμενο έγγραφο SWF πρέπει να περιλαμβάνει τον ενσωματωμένο προγραμματιστή προβολής εγγράφου ή όχι. Η προεπιλογή είναι true.

**Επιστρέφει:**  
boolean
### setViewerIncluded(boolean value) {#setViewerIncluded-boolean-}
```
public final void setViewerIncluded(boolean value)
```


Καθορίζει αν το παραγόμενο έγγραφο SWF πρέπει να περιλαμβάνει τον ενσωματωμένο προγραμματιστή προβολής εγγράφου ή όχι. Η προεπιλογή είναι true.

**Παράμετροι:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |
### getShowPageBorder() {#getShowPageBorder--}
```
public final boolean getShowPageBorder()
```


Καθορίζει αν θα εμφανίζεται το περίγραμμα γύρω από τις σελίδες. Η προεπιλογή είναι true.

**Επιστρέφει:**  
boolean
### setShowPageBorder(boolean value) {#setShowPageBorder-boolean-}
```
public final void setShowPageBorder(boolean value)
```


Καθορίζει αν θα εμφανίζεται το περίγραμμα γύρω από τις σελίδες. Η προεπιλογή είναι true.

**Παράμετροι:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |
### getShowFullScreen() {#getShowFullScreen--}
```
public final boolean getShowFullScreen()
```


Εμφάνιση/απόκρυψη κουμπιού πλήρους οθόνης. Μπορεί να παρακαμφθεί σε flashvars. Η προεπιλογή είναι true.

**Επιστρέφει:**  
boolean
### setShowFullScreen(boolean value) {#setShowFullScreen-boolean-}
```
public final void setShowFullScreen(boolean value)
```


Εμφάνιση/απόκρυψη κουμπιού πλήρους οθόνης. Μπορεί να παρακαμφθεί σε flashvars. Η προεπιλογή είναι true.

**Παράμετροι:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |
### getShowPageStepper() {#getShowPageStepper--}
```
public final boolean getShowPageStepper()
```


Εμφάνιση/απόκρυψη βηματιστή σελίδας. Μπορεί να παρακαμφθεί σε flashvars. Η προεπιλογή είναι true.

**Επιστρέφει:**  
boolean
### setShowPageStepper(boolean value) {#setShowPageStepper-boolean-}
```
public final void setShowPageStepper(boolean value)
```


Εμφάνιση/απόκρυψη βηματιστή σελίδας. Μπορεί να παρακαμφθεί σε flashvars. Η προεπιλογή είναι true.

**Παράμετροι:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |
### getShowSearch() {#getShowSearch--}
```
public final boolean getShowSearch()
```


Εμφάνιση/απόκρυψη ενότητας αναζήτησης. Μπορεί να παρακαμφθεί σε flashvars. Η προεπιλογή είναι true.

**Επιστρέφει:**  
boolean
### setShowSearch(boolean value) {#setShowSearch-boolean-}
```
public final void setShowSearch(boolean value)
```


Εμφάνιση/απόκρυψη ενότητας αναζήτησης. Μπορεί να παρακαμφθεί σε flashvars. Η προεπιλογή είναι true.

**Παράμετροι:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |
### getShowTopPane() {#getShowTopPane--}
```
public final boolean getShowTopPane()
```


Εμφάνιση/απόκρυψη ολόκληρης της επάνω περιοχής. Μπορεί να παρακαμφθεί σε flashvars. Η προεπιλογή είναι true.

**Επιστρέφει:**  
boolean
### setShowTopPane(boolean value) {#setShowTopPane-boolean-}
```
public final void setShowTopPane(boolean value)
```


Εμφάνιση/απόκρυψη ολόκληρης της επάνω περιοχής. Μπορεί να παρακαμφθεί σε flashvars. Η προεπιλογή είναι true.

**Παράμετροι:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |
### getShowBottomPane() {#getShowBottomPane--}
```
public final boolean getShowBottomPane()
```


Εμφάνιση/απόκρυψη κάτω περιοχής. Μπορεί να παρακαμφθεί σε flashvars. Η προεπιλογή είναι true.

**Επιστρέφει:**  
boolean
### setShowBottomPane(boolean value) {#setShowBottomPane-boolean-}
```
public final void setShowBottomPane(boolean value)
```


Εμφάνιση/απόκρυψη κάτω περιοχής. Μπορεί να παρακαμφθεί σε flashvars. Η προεπιλογή είναι true.

**Παράμετροι:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |
### getShowLeftPane() {#getShowLeftPane--}
```
public final boolean getShowLeftPane()
```


Εμφάνιση/απόκρυψη αριστερής περιοχής. Μπορεί να παρακαμφθεί σε flashvars. Η προεπιλογή είναι true.

**Επιστρέφει:**  
boolean
### setShowLeftPane(boolean value) {#setShowLeftPane-boolean-}
```
public final void setShowLeftPane(boolean value)
```


Εμφάνιση/απόκρυψη αριστερής περιοχής. Μπορεί να παρακαμφθεί σε flashvars. Η προεπιλογή είναι true.

**Παράμετροι:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |
### getStartOpenLeftPane() {#getStartOpenLeftPane--}
```
public final boolean getStartOpenLeftPane()
```


Έναρξη με ανοιχτή αριστερή περιοχή. Μπορεί να παρακαμφθεί σε flashvars. Η προεπιλογή είναι false.

**Επιστρέφει:**  
boolean
### setStartOpenLeftPane(boolean value) {#setStartOpenLeftPane-boolean-}
```
public final void setStartOpenLeftPane(boolean value)
```


Έναρξη με ανοιχτή αριστερή περιοχή. Μπορεί να παρακαμφθεί σε flashvars. Η προεπιλογή είναι false.

**Παράμετροι:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |
### getEnableContextMenu() {#getEnableContextMenu--}
```
public final boolean getEnableContextMenu()
```


Ενεργοποίηση/απενεργοποίηση του μενού περιβάλλοντος. Η προεπιλογή είναι true.

**Επιστρέφει:**  
boolean
### setEnableContextMenu(boolean value) {#setEnableContextMenu-boolean-}
```
public final void setEnableContextMenu(boolean value)
```


Ενεργοποίηση/απενεργοποίηση του μενού περιβάλλοντος. Η προεπιλογή είναι true.

**Παράμετροι:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |
### getLogoImageBytes() {#getLogoImageBytes--}
```
public final byte[] getLogoImageBytes()
```


Εικόνα που θα εμφανίζεται ως λογότυπο στην επάνω δεξιά γωνία του προβολέα. Η εικόνα πρέπει να είναι PNG 32x64 pixels, διαφορετικά το λογότυπο μπορεί να εμφανιστεί εσφαλμένα.

**Επιστρέφει:**  
byte[]
### setLogoImageBytes(byte[] value) {#setLogoImageBytes-byte---}
```
public final void setLogoImageBytes(byte[] value)
```


Εικόνα που θα εμφανίζεται ως λογότυπο στην επάνω δεξιά γωνία του προβολέα. Η εικόνα πρέπει να είναι PNG 32x64 pixels, διαφορετικά το λογότυπο μπορεί να εμφανιστεί εσφαλμένα.

**Παράμετροι:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | byte[] |  |
### getLogoLink() {#getLogoLink--}
```
public final String getLogoLink()
```


Λαμβάνει ή ορίζει τη διεύθυνση του πλήρους υπερσυνδέσμου για ένα λογότυπο. Έχει ισχύ μόνο αν ο (\#getLogoImageBytes.getLogoImageBytes/\#setLogoImageBytes(byte[]).setLogoImageBytes(byte[])) έχει οριστεί.

**Επιστρέφει:**  
java.lang.String
### setLogoLink(String value) {#setLogoLink-java.lang.String-}
```
public final void setLogoLink(String value)
```


Λαμβάνει ή ορίζει τη διεύθυνση του πλήρους υπερσυνδέσμου για ένα λογότυπο. Έχει ισχύ μόνο αν ο (\#getLogoImageBytes.getLogoImageBytes/\#setLogoImageBytes(byte[]).setLogoImageBytes(byte[])) έχει οριστεί.

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


Λαμβάνει ή ορίζει τη λειτουργία με την οποία τοποθετούνται οι διαφάνειες στη σελίδα κατά την εξαγωγή μιας παρουσίασης [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions). Αυτή η ιδιότητα δεν υποστηρίζει την ανάθεση αντικειμένων τύπου [HandoutLayoutingOptions](../../com.aspose.slides/handoutlayoutingoptions)

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      NotesCommentsLayoutingOptions notesOptions = new NotesCommentsLayoutingOptions();
>      notesOptions.setCommentsPosition(CommentsPositions.Right);
> 
>      SwfOptions options = new SwwOptions();
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


Λαμβάνει ή ορίζει τη λειτουργία με την οποία τοποθετούνται οι διαφάνειες στη σελίδα κατά την εξαγωγή μιας παρουσίασης [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions). Αυτή η ιδιότητα δεν υποστηρίζει την ανάθεση αντικειμένων τύπου [HandoutLayoutingOptions](../../com.aspose.slides/handoutlayoutingoptions).

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