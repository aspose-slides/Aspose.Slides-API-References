---
title: IPatternFormat
second_title: Aspose.Slides for Java API Reference
description: Αναπαριστά ένα μοτίβο για να γεμίσει ένα σχήμα.
type: docs
url: /el/com.aspose.slides/ipatternformat/
---``` 
public interface IPatternFormat
```

Αναπαριστά ένα μοτίβο για να γεμίσει ένα σχήμα.
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [getPatternStyle()](#getPatternStyle--) | Επιστρέφει ή ορίζει το στυλ μοτίβου. |
| [setPatternStyle(byte value)](#setPatternStyle-byte-) | Επιστρέφει ή ορίζει το στυλ μοτίβου. |
| [getForeColor()](#getForeColor--) | Επιστρέφει το χρώμα προσκόπου του μοτίβου. |
| [getBackColor()](#getBackColor--) | Επιστρέφει το χρώμα φόντου του μοτίβου. |
| [getTile(Color background, Color foreground)](#getTile-java.awt.Color-java.awt.Color-) | Δημιουργεί μια εικόνα πλακιδίου για τη γέμιση μοτίβου με καθορισμένα χρώματα. |
| [getTile(Color styleColor)](#getTile-java.awt.Color-) | Δημιουργεί μια εικόνα πλακιδίου για τη γέμιση μοτίβου. |
### getPatternStyle() {#getPatternStyle--}
```
public abstract byte getPatternStyle()
```

Επιστρέφει ή ορίζει το στυλ μοτίβου. Ανάγωση/εγγραφή [PatternStyle](../../com.aspose.slides/patternstyle).

**Επιστρέφει:**
byte
### setPatternStyle(byte value) {#setPatternStyle-byte-}
```
public abstract void setPatternStyle(byte value)
```

Επιστρέφει ή ορίζει το στυλ μοτίβου. Ανάγωση/εγγραφή [PatternStyle](../../com.aspose.slides/patternstyle).

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | byte |  |

### getForeColor() {#getForeColor--}
```
public abstract IColorFormat getForeColor()
```

Επιστρέφει το χρώμα προσκόπου του μοτίβου. Μόνο για ανάγνωση [IColorFormat](../../com.aspose.slides/icolorformat).

**Επιστρέφει:**
[IColorFormat](../../com.aspose.slides/icolorformat)
### getBackColor() {#getBackColor--}
```
public abstract IColorFormat getBackColor()
```

Επιστρέφει το χρώμα φόντου του μοτίβου. Μόνο για ανάγνωση [IColorFormat](../../com.aspose.slides/icolorformat).

**Επιστρέφει:**
[IColorFormat](../../com.aspose.slides/icolorformat)
### getTile(Color background, Color foreground) {#getTile-java.awt.Color-java.awt.Color-}
```
public abstract IImage getTile(Color background, Color foreground)
```

Δημιουργεί μια εικόνα πλακιδίου για τη γέμιση μοτίβου με καθορισμένα χρώματα.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| background | java.awt.Color | Το χρώμα φόντου java.awt.Color για το μοτίβο. |
| foreground | java.awt.Color | Το χρώμα προσκόπου java.awt.Color για το μοτίβο. |

**Επιστρέφει:**
[IImage](../../com.aspose.slides/iimage) - Tile java.awt.image.BufferedImage.
### getTile(Color styleColor) {#getTile-java.awt.Color-}
```
public abstract IImage getTile(Color styleColor)
```

Δημιουργεί μια εικόνα πλακιδίου για τη γέμιση μοτίβου.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| styleColor | java.awt.Color | Το προεπιλεγμένο java.awt.Color, ορίζεται στο αντικείμενο StyleEx του ShapeEx. Τα χρώματα γεμίσματος μπορούν να εξαρτώνται από αυτό. |

**Επιστρέφει:**
[IImage](../../com.aspose.slides/iimage) - Tile java.awt.image.BufferedImage.