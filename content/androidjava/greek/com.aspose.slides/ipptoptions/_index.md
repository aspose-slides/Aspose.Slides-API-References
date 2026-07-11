---
title: IPptOptions
second_title: Aspose.Slides για Android μέσω Αναφοράς API Java
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
| [getRootDirectoryClsid()](#getRootDirectoryClsid--) | Αντιπροσωπεύει το GUID (CLSID) της κλάσης αντικειμένου που αποθηκεύεται στην καταχώριση της ρίζας καταλόγου. |
| [setRootDirectoryClsid(UUID value)](#setRootDirectoryClsid-java.util.UUID-) | Αντιπροσωπεύει το GUID (CLSID) της κλάσης αντικειμένου που αποθηκεύεται στην καταχώριση της ρίζας καταλόγου. |
### getRootDirectoryClsid() {#getRootDirectoryClsid--}
```
public abstract UUID getRootDirectoryClsid()
```

Αντιπροσωπεύει το GUID (CLSID) της κλάσης αντικειμένου που αποθηκεύεται στην καταχώριση της ρίζας καταλόγου. Μπορεί να χρησιμοποιηθεί για ενεργοποίηση COM της εφαρμογής του εγγράφου. Η προεπιλεγμένη τιμή είναι '64818D11-4F9B-11CF-86EA-00AA00B929E8' που αντιστοιχεί στο 'Microsoft Powerpoint.Slide.8'.

--------------------

> ```
> Presentation pres = new Presentation();
>  try {
>      PptOptions pptOptions = new PptOptions();
> 
>      /// ορίστε το CLSID σε 'Microsoft Powerpoint.Show.8'
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

Αντιπροσωπεύει το GUID (CLSID) της κλάσης αντικειμένου που αποθηκεύεται στην καταχώριση της ρίζας καταλόγου. Μπορεί να χρησιμοποιηθεί για ενεργοποίηση COM της εφαρμογής του εγγράφου. Η προεπιλεγμένη τιμή είναι '64818D11-4F9B-11CF-86EA-00AA00B929E8' που αντιστοιχεί στο 'Microsoft Powerpoint.Slide.8'.

--------------------

> ```
> Presentation pres = new Presentation();
>  try {
>      PptOptions pptOptions = new PptOptions();
> 
>      /// ορίστε το CLSID σε 'Microsoft Powerpoint.Show.8'
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