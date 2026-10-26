---
title: PatternFormat
second_title: Aspose.Slides για Android μέσω Java API Αναφορά
description: Αναπαριστά ένα μοτίβο για το γέμισμα ενός σχήματος.
type: docs
url: /el/com.aspose.slides/patternformat/
---
**Κληρονομία:**  
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject)

**Όλες οι Υλοποιημένες Διεπαφές:**  
[com.aspose.slides.IPatternFormat](../../com.aspose.slides/ipatternformat)  
```
public final class PatternFormat extends PVIObject implements IPatternFormat
```

Αναπαριστά ένα μοτίβο για τη γεμίσματος ενός σχήματος.

## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [getVersion()](#getVersion--) |  |
| [getPatternStyle()](#getPatternStyle--) | Επιστρέφει ή ορίζει το στυλ μοτίβου. |
| [setPatternStyle(byte value)](#setPatternStyle-byte-) | Επιστρέφει ή ορίζει το στυλ μοτίβου. |
| [getForeColor()](#getForeColor--) | Επιστρέφει το χρώμα προσώπου του μοτίβου. |
| [getBackColor()](#getBackColor--) | Επιστρέφει το χρώμα φόντου του μοτίβου. |
| [getTile(Integer background, Integer foreground)](#getTile-java.lang.Integer-java.lang.Integer-) | Δημιουργεί μια εικόνα κελιού για τη γεμίζουσα μοτίβου με καθορισμένα χρώματα. |
| [getTile(Integer styleColor)](#getTile-java.lang.Integer-) | Δημιουργεί μια εικόνα κελιού για τη γεμίζουσα μοτίβου. |

### getVersion() {#getVersion--}
```
public long getVersion()
```

Έκδοση. Μόνο για ανάγνωση long.

**Επιστρέφει:**
long

### getPatternStyle() {#getPatternStyle--}
```
public final byte getPatternStyle()
```

Επιστρέφει ή ορίζει το στυλ μοτίβου. Ανάγνωση/εγγραφή [PatternStyle](../../com.aspose.slides/patternstyle).

**Επιστρέφει:**
byte

### setPatternStyle(byte value) {#setPatternStyle-byte-}
```
public final void setPatternStyle(byte value)
```

Επιστρέφει ή ορίζει το στυλ μοτίβου. Ανάγνωση/εγγραφή [PatternStyle](../../com.aspose.slides/patternstyle).

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | byte |  |

### getForeColor() {#getForeColor--}
```
public final IColorFormat getForeColor()
```

Επιστρέφει το χρώμα προσώπου του μοτίβου. Μόνο για ανάγνωση [IColorFormat](../../com.aspose.slides/icolorformat).

**Επιστρέφει:**
[IColorFormat](../../com.aspose.slides/icolorformat)

### getBackColor() {#getBackColor--}
```
public final IColorFormat getBackColor()
```

Επιστρέφει το χρώμα φόντου του μοτίβου. Μόνο για ανάγνωση [IColorFormat](../../com.aspose.slides/icolorformat).

**Επιστρέφει:**
[IColorFormat](../../com.aspose.slides/icolorformat)

### getTile(Integer background, Integer foreground) {#getTile-java.lang.Integer-java.lang.Integer-}
```
public final IImage getTile(Integer background, Integer foreground)
```

Δημιουργεί μια εικόνα κελιού για τη γεμίζουσα μοτίβου με καθορισμένα χρώματα.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| background | java.lang.Integer | Το background java.lang.Integer για το μοτίβο. |
| foreground | java.lang.Integer | Το foreground java.lang.Integer για το μοτίβο. |

**Επιστρέφει:**
[IImage](../../com.aspose.slides/iimage) - Κελί [IImage](../../com.aspose.slides/iimage).

### getTile(Integer styleColor) {#getTile-java.lang.Integer-}
```
public final IImage getTile(Integer styleColor)
```

Δημιουργεί μια εικόνα κελιού για τη γεμίζουσα μοτίβου.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| styleColor | java.lang.Integer | Το προεπιλεγμένο java.lang.Integer |

**Επιστρέφει:**
[IImage](../../com.aspose.slides/iimage) - Κελί [IImage](../../com.aspose.slides/iimage).