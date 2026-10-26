---
title: PatternFormat
second_title: Αναφορά API του Aspose.Slides για Java
description: Αντιπροσωπεύει ένα μοτίβο για τη γέμιση ενός σχήματος.
type: docs
url: /el/com.aspose.slides/patternformat/
---
**Κληρονόμηση:**
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject)

**Όλες οι Υλοποιημένες Διεπαφές:**
[com.aspose.slides.IPatternFormat](../../com.aspose.slides/ipatternformat)
```
public final class PatternFormat extends PVIObject implements IPatternFormat
```

Αντιπροσωπεύει ένα μοτίβο για τη γέμιση ενός σχήματος.
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [getVersion()](#getVersion--) |  |
| [getPatternStyle()](#getPatternStyle--) | Επιστρέφει ή ορίζει το στυλ μοτίβου. |
| [setPatternStyle(byte value)](#setPatternStyle-byte-) | Επιστρέφει ή ορίζει το στυλ μοτίβου. |
| [getForeColor()](#getForeColor--) | Επιστρέφει το χρώμα πρώτου πλάνου του μοτίβου. |
| [getBackColor()](#getBackColor--) | Επιστρέφει το χρώμα φόντου του μοτίβου. |
| [getTile(Color background, Color foreground)](#getTile-java.awt.Color-java.awt.Color-) | Δημιουργεί μια εικόνα πλακιδίου για τη γέμιση του μοτίβου με καθορισμένα χρώματα. |
| [getTile(Color styleColor)](#getTile-java.awt.Color-) | Δημιουργεί μια εικόνα πλακιδίου για τη γέμιση του μοτίβου. |
### getVersion() {#getVersion--}
```
public long getVersion()
```


Έκδοση. Μόνο ανάγνωση long.

**Επιστρέφει:**
long
### getPatternStyle() {#getPatternStyle--}
```
public final byte getPatternStyle()
```


Επιστρέφει ή ορίζει το στυλ μοτίβου. Ανάγνωση/Εγγραφή [PatternStyle](../../com.aspose.slides/patternstyle).

**Επιστρέφει:**
byte
### setPatternStyle(byte value) {#setPatternStyle-byte-}
```
public final void setPatternStyle(byte value)
```


Επιστρέφει ή ορίζει το στυλ μοτίβου. Ανάγνωση/Εγγραφή [PatternStyle](../../com.aspose.slides/patternstyle).

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | byte |  |

### getForeColor() {#getForeColor--}
```
public final IColorFormat getForeColor()
```


Επιστρέφει το χρώμα πρώτου πλάνου του μοτίβου. Μόνο ανάγνωση [IColorFormat](../../com.aspose.slides/icolorformat).

**Επιστρέφει:**
[IColorFormat](../../com.aspose.slides/icolorformat)
### getBackColor() {#getBackColor--}
```
public final IColorFormat getBackColor()
```


Επιστρέφει το χρώμα φόντου του μοτίβου. Μόνο ανάγνωση [IColorFormat](../../com.aspose.slides/icolorformat).

**Επιστρέφει:**
[IColorFormat](../../com.aspose.slides/icolorformat)
### getTile(Color background, Color foreground) {#getTile-java.awt.Color-java.awt.Color-}
```
public final IImage getTile(Color background, Color foreground)
```


Δημιουργεί μια εικόνα πλακιδίου για τη γέμιση του μοτίβου με καθορισμένα χρώματα.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| background | java.awt.Color | Το χρώμα φόντου java.awt.Color για το μοτίβο. |
| foreground | java.awt.Color | Το χρώμα πρώτου πλάνου java.awt.Color για το μοτίβο. |

**Επιστρέφει:**
[IImage](../../com.aspose.slides/iimage) - Πλακίδιο [IImage](../../com.aspose.slides/iimage).
### getTile(Color styleColor) {#getTile-java.awt.Color-}
```
public final IImage getTile(Color styleColor)
```


Δημιουργεί μια εικόνα πλακιδίου για τη γέμιση του μοτίβου.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| styleColor | java.awt.Color | Το προεπιλεγμένο java.awt.Color |

**Επιστρέφει:**
[IImage](../../com.aspose.slides/iimage) - Πλακίδιο [IImage](../../com.aspose.slides/iimage).