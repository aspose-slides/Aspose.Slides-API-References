---
title: IMathematicalTextFactory
second_title: Aspose.Slides for Android via Java API Reference
description: Permite criar um elemento MathematicalText
type: docs
url: /pt/com.aspose.slides/imathematicaltextfactory/
---```
public interface IMathematicalTextFactory
```

Permite criar um elemento MathematicalText

--------------------

Para compatibilidade COM
## Métodos

| Método | Descrição |
| --- | --- |
| [createMathematicalText()](#createMathematicalText--) | Criar elemento de texto matemático vazio |
| [createMathematicalText(char mathSymbol)](#createMathematicalText-char-) | Criar elemento de texto matemático com o valor especificado |
| [createMathematicalText(String mathText)](#createMathematicalText-java.lang.String-) | Criar elemento de texto matemático vazio com o valor especificado |
| [createMathematicalText(String mathText, IPortionFormat portionFormat)](#createMathematicalText-java.lang.String-com.aspose.slides.IPortionFormat-) | Criar elemento de texto matemático vazio com o valor especificado e propriedades de formatação |
### createMathematicalText() {#createMathematicalText--}
```
public abstract IMathematicalText createMathematicalText()
```


Criar elemento de texto matemático vazio

**Retorna:**
[IMathematicalText](../../com.aspose.slides/imathematicaltext) - novo Mathematical Text
### createMathematicalText(char mathSymbol) {#createMathematicalText-char-}
```
public abstract IMathematicalText createMathematicalText(char mathSymbol)
```


Criar elemento de texto matemático com o valor especificado

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| mathSymbol | char | símbolo único a ser usado como valor de texto |

**Retorna:**
[IMathematicalText](../../com.aspose.slides/imathematicaltext) - novo Mathematical Text
### createMathematicalText(String mathText) {#createMathematicalText-java.lang.String-}
```
public abstract IMathematicalText createMathematicalText(String mathText)
```


Criar elemento de texto matemático vazio com o valor especificado

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| mathText | java.lang.String | valor do texto |

**Retorna:**
[IMathematicalText](../../com.aspose.slides/imathematicaltext) - novo Mathematical Text
### createMathematicalText(String mathText, IPortionFormat portionFormat) {#createMathematicalText-java.lang.String-com.aspose.slides.IPortionFormat-}
```
public abstract IMathematicalText createMathematicalText(String mathText, IPortionFormat portionFormat)
```


Criar elemento de texto matemático vazio com o valor especificado e propriedades de formatação

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| mathText | java.lang.String | valor do texto |
| portionFormat | [IPortionFormat](../../com.aspose.slides/iportionformat) | configurações de formatação de texto |

**Retorna:**
[IMathematicalText](../../com.aspose.slides/imathematicaltext) - novo Mathematical Text