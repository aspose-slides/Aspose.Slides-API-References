---
title: IPatternFormatEffectiveData
second_title: Aspose.Slides for Java API Reference
description: Immutable object which contains effective pattern filling properties.
type: docs
url: /el/com.aspose.slides/ipatternformateffectivedata/
---```
public interface IPatternFormatEffectiveData
```

Ακίνητο αντικείμενο που περιέχει αποτελεσματικές ιδιότητες γεμίσματος μοτίβου.

--------------------

Αυτή η διεπαφή χρησιμοποιείται ως μέρος του [IFillFormatEffectiveData](../../com.aspose.slides/ifillformateffectivedata) και του [ILineFillFormatEffectiveData](../../com.aspose.slides/ilinefillformateffectivedata).
## Μέθοδοι

| Method | Description |
| --- | --- |
| [getPatternStyle()](#getPatternStyle--) | Επιστρέφει το στυλ του μοτίβου. |
| [getForeColor()](#getForeColor--) | Επιστρέφει το χρώμα του μοτίβου στο προσκήνιο. |
| [getBackColor()](#getBackColor--) | Επιστρέφει το χρώμα του μοτίβου στο παρασκήνιο. |
| [getTileIImage(Color background, Color foreground)](#getTileIImage-java.awt.Color-java.awt.Color-) | Δημιουργεί μια εικόνα πλακιδίου για το γέμισμα μοτίβου με καθορισμένα χρώματα. |
### getPatternStyle() {#getPatternStyle--}
```
public abstract byte getPatternStyle()
```


Επιστρέφει το στυλ του μοτίβου. Μόνο για ανάγνωση [PatternStyle](../../com.aspose.slides/patternstyle).

**Επιστρέφει:**
byte
### getForeColor() {#getForeColor--}
```
public abstract Color getForeColor()
```


Επιστρέφει το χρώμα του μοτίβου στο προσκήνιο. Μόνο για ανάγνωση java.awt.Color.

**Επιστρέφει:**
java.awt.Color
### getBackColor() {#getBackColor--}
```
public abstract Color getBackColor()
```


Επιστρέφει το χρώμα του μοτίβου στο παρασκήνιο. Μόνο για ανάγνωση java.awt.Color.

**Επιστρέφει:**
java.awt.Color
### getTileIImage(Color background, Color foreground) {#getTileIImage-java.awt.Color-java.awt.Color-}
```
public abstract IImage getTileIImage(Color background, Color foreground)
```


Δημιουργεί μια εικόνα πλακιδίου για το γέμισμα μοτίβου με καθορισμένα χρώματα.

**Παράμετροι:**
| Parameter | Type | Description |
| --- | --- | --- |
| background | java.awt.Color | Το χρώμα java.awt.Color του παρασκηνίου για το μοτίβο. |
| foreground | java.awt.Color | Το χρώμα java.awt.Color του προσκηνίου για το μοτίβο. |

**Επιστρέφει:**
[IImage](../../com.aspose.slides/iimage) - Πλακίδιο [IImage](../../com.aspose.slides/iimage).