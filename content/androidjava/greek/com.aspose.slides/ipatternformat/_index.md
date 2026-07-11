---
title: IPatternFormat
second_title: Aspose.Slides for Android via Java API Reference
description: Represents a pattern to fill a shape.
type: docs
url: /el/com.aspose.slides/ipatternformat/
---```
public interface IPatternFormat
```

Αναπαριστά ένα μοτίβο για γέμισμα ενός σχήματος.
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [getPatternStyle()](#getPatternStyle--) | Επιστρέφει ή θέτει το στυλ του μοτίβου. |
| [setPatternStyle(byte value)](#setPatternStyle-byte-) | Επιστρέφει ή θέτει το στυλ του μοτίβου. |
| [getForeColor()](#getForeColor--) | Επιστρέφει το χρώμα προσκήνιου του μοτίβου. |
| [getBackColor()](#getBackColor--) | Επιστρέφει το χρώμα φόντου του μοτίβου. |
| [getTile(Integer background, Integer foreground)](#getTile-java.lang.Integer-java.lang.Integer-) | Δημιουργεί μια εικόνα πλακιδίου για το γέμισμα με μοτίβο με καθορισμένα χρώματα. |
| [getTile(Integer styleColor)](#getTile-java.lang.Integer-) | Δημιουργεί μια εικόνα πλακιδίου για το γέμισμα με μοτίβο. |
### getPatternStyle() {#getPatternStyle--}
```
public abstract byte getPatternStyle()
```

Επιστρέφει ή θέτει το στυλ του μοτίβου. Ανάγ/εγγραφή [PatternStyle](../../com.aspose.slides/patternstyle).

**Επιστρέφει:**
byte
### setPatternStyle(byte value) {#setPatternStyle-byte-}
```
public abstract void setPatternStyle(byte value)
```

Επιστρέφει ή θέτει το στυλ του μοτίβου. Ανάγ/εγγραφή [PatternStyle](../../com.aspose.slides/patternstyle).

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | byte |  |

### getForeColor() {#getForeColor--}
```
public abstract IColorFormat getForeColor()
```

Επιστρέφει το χρώμα προσκήνιου του μοτίβου. Μόνο ανάγνωση [IColorFormat](../../com.aspose.slides/icolorformat).

**Επιστρέφει:**
[IColorFormat](../../com.aspose.slides/icolorformat)
### getBackColor() {#getBackColor--}
```
public abstract IColorFormat getBackColor()
```

Επιστρέφει το χρώμα φόντου του μοτίβου. Μόνο ανάγνωση [IColorFormat](../../com.aspose.slides/icolorformat).

**Επιστρέφει:**
[IColorFormat](../../com.aspose.slides/icolorformat)
### getTile(Integer background, Integer foreground) {#getTile-java.lang.Integer-java.lang.Integer-}
```
public abstract IImage getTile(Integer background, Integer foreground)
```

Δημιουργεί μια εικόνα πλακιδίου για το γέμισμα με μοτίβο με καθορισμένα χρώματα.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| background | java.lang.Integer | Το background java.lang.Integer για το μοτίβο. |
| foreground | java.lang.Integer | Το foreground java.lang.Integer για το μοτίβο. |

**Επιστρέφει:**
[IImage](../../com.aspose.slides/iimage) - Tile android.graphics.Bitmap.
### getTile(Integer styleColor) {#getTile-java.lang.Integer-}
```
public abstract IImage getTile(Integer styleColor)
```

Δημιουργεί μια εικόνα πλακιδίου για το γέμισμα με μοτίβο.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| styleColor | java.lang.Integer | Το default java.lang.Integer, ορισμένο στο αντικείμενο StyleEx του ShapeEx. Τα χρώματα του Fill μπορούν να εξαρτώνται από αυτό. |

**Επιστρέφει:**
[IImage](../../com.aspose.slides/iimage) - Tile android.graphics.Bitmap.