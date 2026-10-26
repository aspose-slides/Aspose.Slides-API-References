---
title: Zip64Mode
second_title: Aspose.Slides για Android μέσω Αναφοράς Java API
description: Καθορίζει πότε να χρησιμοποιηθούν οι επεκτάσεις μορφής ZIP64 για το αρχείο OpenXML.
type: docs
url: /el/com.aspose.slides/zip64mode/
---
**Κληρονομικότητα:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class Zip64Mode extends System.Enum
```

Καθορίζει πότε να χρησιμοποιηθούν οι επεκτάσεις μορφής ZIP64 για το αρχείο OpenXML.

--------------------

Το αρχείο OpenXML είναι ένα αρχείο ZIP που έχει όριο 4 GB (2^32 bytes) στο μη συμπιεσμένο μέγεθος ενός αρχείου, στο συμπιεσμένο μέγεθος ενός αρχείου και στο συνολικό μέγεθος του αρχείου, καθώς και όριο 65 535 (2^16-1) αρχείων στο αρχείο. Οι επεκτάσεις μορφής ZIP64 αυξάνουν τα όρια σε 2^64.
## Πεδία

| Πεδίο | Περιγραφή |
| --- | --- |
| [Never](#Never) | Να μην χρησιμοποιηθούν οι επεκτάσεις μορφής ZIP64. |
| [IfNecessary](#IfNecessary) | Χρησιμοποιήστε τις επεκτάσεις μορφής ZIP64 εάν είναι απαραίτητο. |
| [Always](#Always) | Πάντα να χρησιμοποιούνται οι επεκτάσεις μορφής ZIP64. |
### Never {#Never}
```
public static final int Never
```

Να μην χρησιμοποιηθούν οι επεκτάσεις μορφής ZIP64.

### IfNecessary {#IfNecessary}
```
public static final int IfNecessary
```

Χρησιμοποιήστε τις επεκτάσεις μορφής ZIP64 εάν είναι απαραίτητο.

### Always {#Always}
```
public static final int Always
```

Πάντα να χρησιμοποιούνται οι επεκτάσεις μορφής ZIP64.