---
title: IFindResultCallback
second_title: Aspose.Slides for Java API Reference
description: Διεπαφή callback που χρησιμοποιείται για την απόκτηση αποτελεσμάτων αναζήτησης κειμένου.
type: docs
url: /el/com.aspose.slides/ifindresultcallback/
---```
public interface IFindResultCallback
```

Διεπαφή callback που χρησιμοποιείται για την απόκτηση αποτελεσμάτων αναζήτησης κειμένου.
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [foundResult(ITextFrame textFrame, String sourceText, String foundText, int textPosition)](#foundResult-com.aspose.slides.ITextFrame-java.lang.String-java.lang.String-int-) | Μέθοδος callback που λαμβάνει δεδομένα για το κείμενο που βρέθηκε. |
### foundResult(ITextFrame textFrame, String sourceText, String foundText, int textPosition) {#foundResult-com.aspose.slides.ITextFrame-java.lang.String-java.lang.String-int-}
```
public abstract void foundResult(ITextFrame textFrame, String sourceText, String foundText, int textPosition)
```


Μέθοδος callback που λαμβάνει δεδομένα για το κείμενο που βρέθηκε.

**Παράμετροι:** 
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| textFrame | [ITextFrame](../../com.aspose.slides/itextframe) | Το [ITextFrame](../../com.aspose.slides/itextframe) στο οποίο βρέθηκε το κείμενο. |
| sourceText | java.lang.String | Το κείμενο προέλευσης στο οποίο βρέθηκε το κείμενο. |
| foundText | java.lang.String | Το βρεθέν κείμενο. |
| textPosition | int | Η θέση του βρεθέντος κειμένου. |