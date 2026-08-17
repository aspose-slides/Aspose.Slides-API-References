---
title: IPptOptions
second_title: Αναφορά API Aspose.Slides για Java
description: Παρέχει επιλογές που ελέγχουν πώς αποθηκεύεται μια παρουσίαση σε μορφή PPT.
type: docs
url: /el/com.aspose.slides/ipptoptions/
---
**Όλες οι Υλοποιημένες Διασυνδέσεις:**
[com.aspose.slides.ISaveOptions](../../com.aspose.slides/isaveoptions)
```
public interface IPptOptions extends ISaveOptions
```

Παρέχει επιλογές που ελέγχουν πώς αποθηκεύεται μια παρουσίαση σε μορφή PPT.
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [getRootDirectoryClsid()](#getRootDirectoryClsid--) | Represents the object class GUID (CLSID) that is stored in the root directory entry. |
| [setRootDirectoryClsid(UUID value)](#setRootDirectoryClsid-java.util.UUID-) | Represents the object class GUID (CLSID) that is stored in the root directory entry. |
### getRootDirectoryClsid() {#getRootDirectoryClsid--}
```
public abstract UUID getRootDirectoryClsid()
```

Αντιπροσωπεύει το GUID κλάσης αντικειμένου (CLSID) που αποθηκεύεται στην καταχώριση του ριζικού καταλόγου. Μπορεί να χρησιμοποιηθεί για την ενεργοποίηση COM της εφαρμογής του εγγράφου. Η προεπιλεγμένη τιμή είναι '64818D11-4F9B-11CF-86EA-00AA00B929E8' που αντιστοιχεί σε 'Microsoft Powerpoint.Slide.8'.

--------------------

> ```
> Presentation pres = new Presentation();
>  try {
>      PptOptions pptOptions = new PptOptions();
> 
>      /// ορίστε CLSID στο 'Microsoft Powerpoint.Show.8'
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
public abstract void setRootDirectoryClsid(UUID value)
```

Αντιπροσωπεύει το GUID κλάσης αντικειμένου (CLSID) που αποθηκεύεται στην καταχώριση του ριζικού καταλόγου. Μπορεί να χρησιμοποιηθεί για την ενεργοποίηση COM της εφαρμογής του εγγράφου. Η προεπιλεγμένη τιμή είναι '64818D11-4F9B-11CF-86EA-00AA00B929E8' που αντιστοιχεί σε 'Microsoft Powerpoint.Slide.8'.

--------------------

> ```
> Presentation pres = new Presentation();
>  try {
>      PptOptions pptOptions = new PptOptions();
> 
>      /// ορίστε CLSID στο 'Microsoft Powerpoint.Show.8'
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