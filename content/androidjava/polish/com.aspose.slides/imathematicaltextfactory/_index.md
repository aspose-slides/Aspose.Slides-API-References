---
title: IMathematicalTextFactory
second_title: Aspose.Slides for Android via Java API Reference
description: Allows to create a MathematicalText element
type: docs
url: /pl/com.aspose.slides/imathematicaltextfactory/
---```
public interface IMathematicalTextFactory
```

Umożliwia tworzenie elementu MathematicalText

--------------------

Dla zgodności z COM
## Metody

| Method | Description |
| --- | --- |
| [createMathematicalText()](#createMathematicalText--) | Utwórz pusty element tekstowy matematyczny |
| [createMathematicalText(char mathSymbol)](#createMathematicalText-char-) | Utwórz element tekstowy matematyczny o określonej wartości |
| [createMathematicalText(String mathText)](#createMathematicalText-java.lang.String-) | Utwórz pusty element tekstowy matematyczny o określonej wartości |
| [createMathematicalText(String mathText, IPortionFormat portionFormat)](#createMathematicalText-java.lang.String-com.aspose.slides.IPortionFormat-) | Utwórz pusty element tekstowy matematyczny o określonej wartości i właściwościach formatowania |
### createMathematicalText() {#createMathematicalText--}
```
public abstract IMathematicalText createMathematicalText()
```


Utwórz pusty element tekstowy matematyczny

**Zwraca:**
[IMathematicalText](../../com.aspose.slides/imathematicaltext) - new Mathematical Text
### createMathematicalText(char mathSymbol) {#createMathematicalText-char-}
```
public abstract IMathematicalText createMathematicalText(char mathSymbol)
```


Utwórz element tekstowy matematyczny o określonej wartości

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| mathSymbol | char | pojedynczy symbol używany jako wartość tekstowa |

**Zwraca:**
[IMathematicalText](../../com.aspose.slides/imathematicaltext) - new Mathematical Text
### createMathematicalText(String mathText) {#createMathematicalText-java.lang.String-}
```
public abstract IMathematicalText createMathematicalText(String mathText)
```


Utwórz pusty element tekstowy matematyczny o określonej wartości

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| mathText | java.lang.String | wartość tekstowa |

**Zwraca:**
[IMathematicalText](../../com.aspose.slides/imathematicaltext) - new Mathematical Text
### createMathematicalText(String mathText, IPortionFormat portionFormat) {#createMathematicalText-java.lang.String-com.aspose.slides.IPortionFormat-}
```
public abstract IMathematicalText createMathematicalText(String mathText, IPortionFormat portionFormat)
```


Utwórz pusty element tekstowy matematyczny o określonej wartości i właściwościach formatowania

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| mathText | java.lang.String | wartość tekstowa |
| portionFormat | [IPortionFormat](../../com.aspose.slides/iportionformat) | ustawienia formatu tekstu |

**Zwraca:**
[IMathematicalText](../../com.aspose.slides/imathematicaltext) - new Mathematical Text