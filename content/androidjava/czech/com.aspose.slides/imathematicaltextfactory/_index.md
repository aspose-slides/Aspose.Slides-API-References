---
title: IMathematicalTextFactory
second_title: Aspose.Slides for Android via Java API Reference
description: Allows to create a MathematicalText element
type: docs
url: /cs/com.aspose.slides/imathematicaltextfactory/
---```
public interface IMathematicalTextFactory
```

Umožňuje vytvořit prvek MathematicalText

--------------------

Pro kompatibilitu s COM
## Metody

| Metoda | Popis |
| --- | --- |
| [createMathematicalText()](#createMathematicalText--) | Vytvoří prázdný prvek mathematical text |
| [createMathematicalText(char mathSymbol)](#createMathematicalText-char-) | Vytvoří prvek mathematical text se zadanou hodnotou |
| [createMathematicalText(String mathText)](#createMathematicalText-java.lang.String-) | Vytvoří prázdný prvek mathematical text se zadanou hodnotou |
| [createMathematicalText(String mathText, IPortionFormat portionFormat)](#createMathematicalText-java.lang.String-com.aspose.slides.IPortionFormat-) | Vytvoří prázdný prvek mathematical text se zadanou hodnotou a formátovacími vlastnostmi |
### createMathematicalText() {#createMathematicalText--}
```
public abstract IMathematicalText createMathematicalText()
```


Vytvoří prázdný prvek mathematical text

**Vrací:**
[IMathematicalText](../../com.aspose.slides/imathematicaltext) - nový Mathematical Text
### createMathematicalText(char mathSymbol) {#createMathematicalText-char-}
```
public abstract IMathematicalText createMathematicalText(char mathSymbol)
```


Vytvoří prvek mathematical text se zadanou hodnotou

**Parametry:**
| Parameter | Type | Description |
| --- | --- | --- |
| mathSymbol | char | jeden symbol použitý jako textová hodnota |

**Vrací:**
[IMathematicalText](../../com.aspose.slides/imathematicaltext) - nový Mathematical Text
### createMathematicalText(String mathText) {#createMathematicalText-java.lang.String-}
```
public abstract IMathematicalText createMathematicalText(String mathText)
```


Vytvoří prázdný prvek mathematical text se zadanou hodnotou

**Parametry:**
| Parameter | Type | Description |
| --- | --- | --- |
| mathText | java.lang.String | textová hodnota |

**Vrací:**
[IMathematicalText](../../com.aspose.slides/imathematicaltext) - nový Mathematical Text
### createMathematicalText(String mathText, IPortionFormat portionFormat) {#createMathematicalText-java.lang.String-com.aspose.slides.IPortionFormat-}
```
public abstract IMathematicalText createMathematicalText(String mathText, IPortionFormat portionFormat)
```


Vytvoří prázdný prvek mathematical text se zadanou hodnotou a formátovacími vlastnostmi

**Parametry:**
| Parameter | Type | Description |
| --- | --- | --- |
| mathText | java.lang.String | textová hodnota |
| portionFormat | [IPortionFormat](../../com.aspose.slides/iportionformat) | nastavení formátu textu |

**Vrací:**
[IMathematicalText](../../com.aspose.slides/imathematicaltext) - nový Mathematical Text