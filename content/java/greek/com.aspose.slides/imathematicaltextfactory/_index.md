---
title: IMathematicalTextFactory
second_title: Aspose.Slides for Java API Reference
description: Allows to create a MathematicalText element
type: docs
url: /el/com.aspose.slides/imathematicaltextfactory/
---```
public interface IMathematicalTextFactory
```

Επιτρέπει τη δημιουργία ενός στοιχείου MathematicalText

--------------------

Για συμβατότητα με COM
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [createMathematicalText()](#createMathematicalText--) | Δημιουργεί κενό στοιχείο μαθηματικού κειμένου |
| [createMathematicalText(char mathSymbol)](#createMathematicalText-char-) | Δημιουργεί στοιχείο μαθηματικού κειμένου με την καθορισμένη τιμή |
| [createMathematicalText(String mathText)](#createMathematicalText-java.lang.String-) | Δημιουργεί κενό στοιχείο μαθηματικού κειμένου με την καθορισμένη τιμή |
| [createMathematicalText(String mathText, IPortionFormat portionFormat)](#createMathematicalText-java.lang.String-com.aspose.slides.IPortionFormat-) | Δημιουργεί κενό στοιχείο μαθηματικού κειμένου με την καθορισμένη τιμή και ιδιότητες μορφοποίησης |
### createMathematicalText() {#createMathematicalText--}
```
public abstract IMathematicalText createMathematicalText()
```

Δημιουργεί κενό στοιχείο μαθηματικού κειμένου

**Επιστρέφει:**
[IMathematicalText](../../com.aspose.slides/imathematicaltext) - new Mathematical Text
### createMathematicalText(char mathSymbol) {#createMathematicalText-char-}
```
public abstract IMathematicalText createMathematicalText(char mathSymbol)
```

Δημιουργεί στοιχείο μαθηματικού κειμένου με την καθορισμένη τιμή

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| mathSymbol | char | μονό σύμβολο που θα χρησιμοποιηθεί ως τιμή κειμένου |

**Επιστρέφει:**
[IMathematicalText](../../com.aspose.slides/imathematicaltext) - new Mathematical Text
### createMathematicalText(String mathText) {#createMathematicalText-java.lang.String-}
```
public abstract IMathematicalText createMathematicalText(String mathText)
```

Δημιουργεί κενό στοιχείο μαθηματικού κειμένου με την καθορισμένη τιμή

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| mathText | java.lang.String | τιμή κειμένου |

**Επιστρέφει:**
[IMathematicalText](../../com.aspose.slides/imathematicaltext) - new Mathematical Text
### createMathematicalText(String mathText, IPortionFormat portionFormat) {#createMathematicalText-java.lang.String-com.aspose.slides.IPortionFormat-}
```
public abstract IMathematicalText createMathematicalText(String mathText, IPortionFormat portionFormat)
```

Δημιουργεί κενό στοιχείο μαθηματικού κειμένου με την καθορισμένη τιμή και ιδιότητες μορφοποίησης

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| mathText | java.lang.String | τιμή κειμένου |
| portionFormat | [IPortionFormat](../../com.aspose.slides/iportionformat) | ρυθμίσεις μορφοποίησης κειμένου |

**Επιστρέφει:**
[IMathematicalText](../../com.aspose.slides/imathematicaltext) - new Mathematical Text