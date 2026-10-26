---
title: PptOptions
second_title: Aspose.Slides για την αναφορά API της Java
description: Παρέχει επιλογές που ελέγχουν πώς αποθηκεύεται μια παρουσίαση σε μορφή PPT.
type: docs
url: /el/com.aspose.slides/pptoptions/
---
**Κληρονόμηση:**
java.lang.Object, [com.aspose.slides.SaveOptions](../../com.aspose.slides/saveoptions)

**Όλες οι Υλοποιημένες Διεπαφές:**
[com.aspose.slides.IPptOptions](../../com.aspose.slides/ipptoptions), java.lang.Cloneable
```
public class PptOptions extends SaveOptions implements IPptOptions, Cloneable
```

Παρέχει επιλογές που ελέγχουν πώς αποθηκεύεται μια παρουσίαση σε μορφή PPT.
## Κατασκευαστές

| Κατασκευαστής | Περιγραφή |
| --- | --- |
| [PptOptions()](#PptOptions--) |  |
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [getRootDirectoryClsid()](#getRootDirectoryClsid--) | Αναπαριστά το GUID (CLSID) της κλάσης αντικειμένου που αποθηκεύεται στην καταχώρηση του ριζικού καταλόγου. |
| [setRootDirectoryClsid(UUID value)](#setRootDirectoryClsid-java.util.UUID-) | Αναπαριστά το GUID (CLSID) της κλάσης αντικειμένου που αποθηκεύεται στην καταχώρηση του ριζικού καταλόγου. |
### PptOptions() {#PptOptions--}
```
public PptOptions()
```


### getRootDirectoryClsid() {#getRootDirectoryClsid--}
```
public final UUID getRootDirectoryClsid()
```


Αναπαριστά το GUID (CLSID) της κλάσης αντικειμένου που αποθηκεύεται στην καταχώρηση του ριζικού καταλόγου. Μπορεί να χρησιμοποιηθεί για ενεργοποίηση COM της εφαρμογής του εγγράφου. Η προεπιλεγμένη τιμή είναι '64818D11-4F9B-11CF-86EA-00AA00B929E8' που αντιστοιχεί στο 'Microsoft Powerpoint.Slide.8'.

--------------------

> ```
> Presentation pres = new Presentation();
>  try {
>      PptOptions pptOptions = new PptOptions();
> 
>      /// Ορίστε το CLSID σε 'Microsoft Powerpoint.Show.8'
>      pptOptions.setRootDirectoryClsid(UUID.fromString("64818D10-4F9B-11CF-86EA-00AA00B929E8"));
> 
>      pres.save("pres.ppt", SaveFormat.Ppt, pptOptions);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Επιστρέφει:**
java.util.UUID
### setRootDirectoryClsid(UUID value) {#setRootDirectoryClsid-java.util.UUID-}
```
public final void setRootDirectoryClsid(UUID value)
```


Αναπαριστά το GUID (CLSID) της κλάσης αντικειμένου που αποθηκεύεται στην καταχώρηση του ριζικού καταλόγου. Μπορεί να χρησιμοποιηθεί για ενεργοποίηση COM της εφαρμογής του εγγράφου. Η προεπιλεγμένη τιμή είναι '64818D11-4F9B-11CF-86EA-00AA00B929E8' που αντιστοιχεί στο 'Microsoft Powerpoint.Slide.8'.

--------------------

> ```
> Presentation pres = new Presentation();
>  try {
>      PptOptions pptOptions = new PptOptions();
> 
>      /// Ορίστε το CLSID σε 'Microsoft Powerpoint.Show.8'
>      pptOptions.setRootDirectoryClsid(UUID.fromString("64818D10-4F9B-11CF-86EA-00AA00B929E8"));
> 
>      pres.save("pres.ppt", SaveFormat.Ppt, pptOptions);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | java.util.UUID |  |