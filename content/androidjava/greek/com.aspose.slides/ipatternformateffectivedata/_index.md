---
title: IPatternFormatEffectiveData
second_title: Aspose.Slides for Android via Java API Reference
description: Αμετάβλητο αντικείμενο που περιέχει τις αποτελεσματικές ιδιότητες γεμίσματος μοτίβου.
type: docs
url: /el/com.aspose.slides/ipatternformateffectivedata/
---```
public interface IPatternFormatEffectiveData
```

Αμετάβλητο αντικείμενο που περιέχει τις αποτελεσματικές ιδιότητες γεμίσματος μοτίβου.

--------------------

Αυτή η διεπαφή χρησιμοποιείται ως μέρος των [IFillFormatEffectiveData](../../com.aspose.slides/ifillformateffectivedata) και [ILineFillFormatEffectiveData](../../com.aspose.slides/ilinefillformateffectivedata).
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [getPatternStyle()](#getPatternStyle--) | Επιστρέφει το στυλ μοτίβου. |
| [getForeColor()](#getForeColor--) | Επιστρέφει το χρώμα εμπρόσθιου μοτίβου. |
| [getBackColor()](#getBackColor--) | Επιστρέφει το χρώμα φόντου μοτίβου. |
| [getTileIImage(Integer background, Integer foreground)](#getTileIImage-java.lang.Integer-java.lang.Integer-) | Δημιουργεί μια εικόνα τύλου για το γέμισμα μοτίβου με καθορισμένα χρώματα. |
### getPatternStyle() {#getPatternStyle--}
```
public abstract byte getPatternStyle()
```


Επιστρέφει το στυλ μοτίβου. Μόνο για ανάγνωση [PatternStyle](../../com.aspose.slides/patternstyle).

**Επιστρέφει:**
`byte`
### getForeColor() {#getForeColor--}
```
public abstract Integer getForeColor()
```


Επιστρέφει το χρώμα εμπρόσθιου μοτίβου. Μόνο για ανάγνωση java.lang.Integer.

**Επιστρέφει:**
`java.lang.Integer`
### getBackColor() {#getBackColor--}
```
public abstract Integer getBackColor()
```


Επιστρέφει το χρώμα φόντου μοτίβου. Μόνο για ανάγνωση java.lang.Integer.

**Επιστρέφει:**
`java.lang.Integer`
### getTileIImage(Integer background, Integer foreground) {#getTileIImage-java.lang.Integer-java.lang.Integer-}
```
public abstract IImage getTileIImage(Integer background, Integer foreground)
```


Δημιουργεί μια εικόνα τύλου για το γέμισμα μοτίβου με καθορισμένα χρώματα.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| background | `java.lang.Integer` | Το φόντο `java.lang.Integer` για το μοτίβο. |
| foreground | `java.lang.Integer` | Το εμπρός `java.lang.Integer` για το μοτίβο. |

**Επιστρέφει:**
[IImage](../../com.aspose.slides/iimage) - Τίλ [IImage](../../com.aspose.slides/iimage).