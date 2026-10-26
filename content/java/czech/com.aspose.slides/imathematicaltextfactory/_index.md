---
title: IMathematicalTextFactory
second_title: Aspose.Slides for Java API Reference
description: Allows to create a MathematicalText element
type: docs
url: /cs/com.aspose.slides/imathematicaltextfactory/
---```
public interface IMathematicalTextFactory
```

Umožňuje vytvořit prvek MathematicalText

--------------------

Pro kompatibilitu s COM
## Methods

| Method | Description |
| --- | --- |
| [createMathematicalText()](#createMathematicalText--) | Vytvoří prázdný prvek matematického textu |
| [createMathematicalText(char mathSymbol)](#createMathematicalText-char-) | Vytvoří prvek matematického textu se zadanou hodnotou |
| [createMathematicalText(String mathText)](#createMathematicalText-java.lang.String-) | Vytvoří prázdný prvek matematického textu se zadanou hodnotou |
| [createMathematicalText(String mathText, IPortionFormat portionFormat)](#createMathematicalText-java.lang.String-com.aspose.slides.IPortionFormat-) | Vytvoří prázdný prvek matematického textu se zadanou hodnotou a vlastnostmi formátování |
### createMathematicalText() {#createMathematicalText--}
```
public abstract IMathematicalText createMathematicalText()
```


Vytvoří prázdný prvek matematického textu

**Returns:**
[IMathematicalText](../../com.aspose.slides/imathematicaltext) - new Mathematical Text
### createMathematicalText(char mathSymbol) {#createMathematicalText-char-}
```
public abstract IMathematicalText createMathematicalText(char mathSymbol)
```


Vytvoří prvek matematického textu se zadanou hodnotou

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| mathSymbol | char | jeden znak použitý jako hodnota textu |

**Returns:**
[IMathematicalText](../../com.aspose.slides/imathematicaltext) - new Mathematical Text
### createMathematicalText(String mathText) {#createMathematicalText-java.lang.String-}
```
public abstract IMathematicalText createMathematicalText(String mathText)
```


Vytvoří prázdný prvek matematického textu se zadanou hodnotou

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| mathText | java.lang.String | hodnota textu |

**Returns:**
[IMathematicalText](../../com.aspose.slides/imathematicaltext) - new Mathematical Text
### createMathematicalText(String mathText, IPortionFormat portionFormat) {#createMathematicalText-java.lang.String-com.aspose.slides.IPortionFormat-}
```
public abstract IMathematicalText createMathematicalText(String mathText, IPortionFormat portionFormat)
```


Vytvoří prázdný prvek matematického textu se zadanou hodnotou a vlastnostmi formátování

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| mathText | java.lang.String | hodnota textu |
| portionFormat | [IPortionFormat](../../com.aspose.slides/iportionformat) | nastavení formátu textu |

**Returns:**
[IMathematicalText](../../com.aspose.slides/imathematicaltext) - new Mathematical Text