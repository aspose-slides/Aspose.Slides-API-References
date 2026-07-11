---
title: IXpsOptions
second_title: Aspose.Slides για Android μέσω Java API Reference
description: Παρέχει επιλογές που ελέγχουν πώς αποθηκεύεται μια παρουσίαση σε μορφή XPS.
type: docs
url: /el/com.aspose.slides/ixpsoptions/
---
**Όλες οι υλοποιημένες διεπαφές:**  
[com.aspose.slides.ISaveOptions](../../com.aspose.slides/isaveoptions)
```
public interface IXpsOptions extends ISaveOptions
```

Παρέχει επιλογές που ελέγχουν πώς αποθηκεύεται μια παρουσίαση σε μορφή XPS.
## Μέθοδοι

| Method | Description |
| --- | --- |
| [getSaveMetafilesAsPng()](#getSaveMetafilesAsPng--) | True για μετατροπή όλων των metafiles που χρησιμοποιούνται σε μια παρουσίαση σε εικόνες PNG. |
| [setSaveMetafilesAsPng(boolean value)](#setSaveMetafilesAsPng-boolean-) | True για μετατροπή όλων των metafiles που χρησιμοποιούνται σε μια παρουσίαση σε εικόνες PNG. |
| [getDrawSlidesFrame()](#getDrawSlidesFrame--) | True για σχεδίαση μαύρου πλαισίου γύρω από κάθε διαφάνεια. |
| [setDrawSlidesFrame(boolean value)](#setDrawSlidesFrame-boolean-) | True για σχεδίαση μαύρου πλαισίου γύρω από κάθε διαφάνεια. |
| [getShowHiddenSlides()](#getShowHiddenSlides--) | Καθορίζει εάν το παραγόμενο έγγραφο πρέπει να περιλαμβάνει κρυφές διαφάνειες ή όχι. |
| [setShowHiddenSlides(boolean value)](#setShowHiddenSlides-boolean-) | Καθορίζει εάν το παραγόμενο έγγραφο πρέπει να περιλαμβάνει κρυφές διαφάνειες ή όχι. |

### getSaveMetafilesAsPng() {#getSaveMetafilesAsPng--}
```
public abstract boolean getSaveMetafilesAsPng()
```

True για μετατροπή όλων των metafiles που χρησιμοποιούνται σε μια παρουσίαση σε εικόνες PNG. Ανάγνωση/εγγραφή boolean.

--------------------

Η προεπιλογή είναι **true**.

**Επιστρέφει:**
boolean

### setSaveMetafilesAsPng(boolean value) {#setSaveMetafilesAsPng-boolean-}
```
public abstract void setSaveMetafilesAsPng(boolean value)
```

True για μετατροπή όλων των metafiles που χρησιμοποιούνται σε μια παρουσίαση σε εικόνες PNG. Ανάγνωση/εγγραφή boolean.

--------------------

Η προεπιλογή είναι **true**.

**Παράμετροι:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getDrawSlidesFrame() {#getDrawSlidesFrame--}
```
public abstract boolean getDrawSlidesFrame()
```

True για σχεδίαση μαύρου πλαισίου γύρω από κάθε διαφάνεια. Ανάγνωση/εγγραφή boolean.

--------------------

Η προεπιλογή είναι **false**.

**Επιστρέφει:**
boolean

### setDrawSlidesFrame(boolean value) {#setDrawSlidesFrame-boolean-}
```
public abstract void setDrawSlidesFrame(boolean value)
```

True για σχεδίαση μαύρου πλαισίου γύρω από κάθε διαφάνεια. Ανάγνωση/εγγραφή boolean.

--------------------

Η προεπιλογή είναι **false**.

**Παράμετροι:**
| Parameter | Type | Description |
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
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |