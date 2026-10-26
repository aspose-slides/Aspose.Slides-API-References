---
title: IMathematicalTextFactory
second_title: Aspose.Slides for Android via Java API Reference
description: Allows to create a MathematicalText element
type: docs
url: /el/com.aspose.slides/imathematicaltextfactory/
---```
public interface IMathematicalTextFactory
```

Επιτρέπει τη δημιουργία ενός στοιχείου MathematicalText

--------------------

Για συμβατότητα COM
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [createMathematicalText()](#createMathematicalText--) | Create empty mathematical text element |
| [createMathematicalText(char mathSymbol)](#createMathematicalText-char-) | Create mathematical text element with the specified value |
| [createMathematicalText(String mathText)](#createMathematicalText-java.lang.String-) | Create empty mathematical text element with the specified value |
| [createMathematicalText(String mathText, IPortionFormat portionFormat)](#createMathematicalText-java.lang.String-com.aspose.slides.IPortionFormat-) | Create empty mathematical text element with the specified value and formatting properties |
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
| mathSymbol | char | μεμονωμένο σύμβολο που θα χρησιμοποιηθεί ως τιμή κειμένου |

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