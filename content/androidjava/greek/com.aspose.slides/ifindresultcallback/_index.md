---
title: IFindResultCallback
second_title: Aspose.Slides για Android μέσω Java API Reference
description: Διεπαφή callback που χρησιμοποιείται για την λήψη του αποτελέσματος αναζήτησης κειμένου.
type: docs
url: /el/com.aspose.slides/ifindresultcallback/
---```
public interface IFindResultCallback
```

Διεπαφή callback που χρησιμοποιείται για την λήψη του αποτελέσματος αναζήτησης κειμένου.

## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [foundResult(ITextFrame textFrame, String sourceText, String foundText, int textPosition)](#foundResult-com.aspose.slides.ITextFrame-java.lang.String-java.lang.String-int-) | Μέθοδος callback που λαμβάνει δεδομένα σχετικά με το ευρεθέν κείμενο. |
### foundResult(ITextFrame textFrame, String sourceText, String foundText, int textPosition) {#foundResult-com.aspose.slides.ITextFrame-java.lang.String-java.lang.String-int-}
```
public abstract void foundResult(ITextFrame textFrame, String sourceText, String foundText, int textPosition)
```

Μέθοδος callback που λαμβάνει δεδομένα σχετικά με το ευρεθέν κείμενο.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| textFrame | [ITextFrame](../../com.aspose.slides/itextframe) | Το [ITextFrame](../../com.aspose.slides/itextframe) στο οποίο βρέθηκε το κείμενο. |
| sourceText | java.lang.String | Το κείμενο προέλευσης στο οποίο βρέθηκε το κείμενο. |
| foundText | java.lang.String | Το ευρεθέν κείμενο. |
| textPosition | int | Η θέση του ευρεθέντος κειμένου. |