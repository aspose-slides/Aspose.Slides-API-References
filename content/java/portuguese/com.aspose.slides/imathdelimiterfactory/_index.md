---
title: IMathDelimiterFactory
second_title: Aspose.Slides for Java API Reference
description: Permite criar um delimitador matemático
type: docs
url: /pt/com.aspose.slides/imathdelimiterfactory/
---```
public interface IMathDelimiterFactory
```

Permite criar um delimitador matemático

--------------------

Para compatibilidade COM
## Métodos

| Método | Descrição |
| --- | --- |
| [createMathDelimiter(IMathElement element)](#createMathDelimiter-com.aspose.slides.IMathElement-) | Create a math delimiter by applying to the element |
| [createMathDelimiter(IMathElementCollection mathElements)](#createMathDelimiter-com.aspose.slides.IMathElementCollection-) | Create a math delimiter by applying to the element |
### createMathDelimiter(IMathElement element) {#createMathDelimiter-com.aspose.slides.IMathElement-}
```
public abstract IMathDelimiter createMathDelimiter(IMathElement element)
```


Cria um delimitador matemático aplicando ao elemento

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| element | [IMathElement](../../com.aspose.slides/imathelement) | elemento matemático ao qual aplicar o delimitador |

**Retorna:**
[IMathDelimiter](../../com.aspose.slides/imathdelimiter) - novo delimitador matemático
### createMathDelimiter(IMathElementCollection mathElements) {#createMathDelimiter-com.aspose.slides.IMathElementCollection-}
```
public abstract IMathDelimiter createMathDelimiter(IMathElementCollection mathElements)
```


Cria um delimitador matemático aplicando ao elemento

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| mathElements | [IMathElementCollection](../../com.aspose.slides/imathelementcollection) | elementos matemáticos aos quais aplicar o delimitador |

**Retorna:**
[IMathDelimiter](../../com.aspose.slides/imathdelimiter) - novo delimitador matemático