---
title: IMathematicalTextFactory
second_title: Aspose.Slides for Java API Reference
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
| [createMathematicalText()](#createMathematicalText--) | Criar elemento MathematicalText vazio |
| [createMathematicalText(char mathSymbol)](#createMathematicalText-char-) | Criar elemento MathematicalText com o valor especificado |
| [createMathematicalText(String mathText)](#createMathematicalText-java.lang.String-) | Criar elemento MathematicalText vazio com o valor especificado |
| [createMathematicalText(String mathText, IPortionFormat portionFormat)](#createMathematicalText-java.lang.String-com.aspose.slides.IPortionFormat-) | Criar elemento MathematicalText vazio com o valor especificado e propriedades de formatação |
### createMathematicalText() {#createMathematicalText--}
```
public abstract IMathematicalText createMathematicalText()
```

Criar elemento MathematicalText vazio

**Retorna:**
[IMathematicalText](../../com.aspose.slides/imathematicaltext) - new Mathematical Text
### createMathematicalText(char mathSymbol) {#createMathematicalText-char-}
```
public abstract IMathematicalText createMathematicalText(char mathSymbol)
```

Criar elemento MathematicalText com o valor especificado

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| mathSymbol | char | símbolo único a ser usado como valor de texto |

**Retorna:**
[IMathematicalText](../../com.aspose.slides/imathematicaltext) - new Mathematical Text
### createMathematicalText(String mathText) {#createMathematicalText-java.lang.String-}
```
public abstract IMathematicalText createMathematicalText(String mathText)
```

Criar elemento MathematicalText vazio com o valor especificado

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| mathText | java.lang.String | valor de texto |

**Retorna:**
[IMathematicalText](../../com.aspose.slides/imathematicaltext) - new Mathematical Text
### createMathematicalText(String mathText, IPortionFormat portionFormat) {#createMathematicalText-java.lang.String-com.aspose.slides.IPortionFormat-}
```
public abstract IMathematicalText createMathematicalText(String mathText, IPortionFormat portionFormat)
```

Criar elemento MathematicalText vazio com o valor especificado e propriedades de formatação

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| mathText | java.lang.String | valor de texto |
| portionFormat | [IPortionFormat](../../com.aspose.slides/iportionformat) | configurações de formato de texto |

**Retorna:**
[IMathematicalText](../../com.aspose.slides/imathematicaltext) - new Mathematical Text