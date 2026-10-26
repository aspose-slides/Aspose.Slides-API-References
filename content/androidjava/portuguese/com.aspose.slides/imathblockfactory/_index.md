---
title: IMathBlockFactory
second_title: Aspose.Slides for Android via Java API Reference
description: Permite criar um bloco matemático
type: docs
url: /pt/com.aspose.slides/imathblockfactory/
---```
public interface IMathBlockFactory
```

Permite criar um bloco matemático

--------------------

Para compatibilidade COM
## Métodos

| Method | Description |
| --- | --- |
| [createMathBlock()](#createMathBlock--) | Cria um bloco matemático |
| [createMathBlock(IMathElement mathElement)](#createMathBlock-com.aspose.slides.IMathElement-) | Cria um bloco matemático e coloca o elemento nele |
| [createMathBlock(IMathElementCollection mathElements)](#createMathBlock-com.aspose.slides.IMathElementCollection-) | Cria um bloco matemático e coloca elementos nele |
### createMathBlock() {#createMathBlock--}
```
public abstract IMathBlock createMathBlock()
```

Cria um bloco matemático

**Retorna:**
[IMathBlock](../../com.aspose.slides/imathblock) - novo bloco matemático
### createMathBlock(IMathElement mathElement) {#createMathBlock-com.aspose.slides.IMathElement-}
```
public abstract IMathBlock createMathBlock(IMathElement mathElement)
```

Cria um bloco matemático e coloca o elemento nele

**Parâmetros:**
| Parameter | Type | Description |
| --- | --- | --- |
| mathElement | [IMathElement](../../com.aspose.slides/imathelement) | Um elemento matemático |

**Retorna:**
[IMathBlock](../../com.aspose.slides/imathblock) - novo bloco matemático
### createMathBlock(IMathElementCollection mathElements) {#createMathBlock-com.aspose.slides.IMathElementCollection-}
```
public abstract IMathBlock createMathBlock(IMathElementCollection mathElements)
```

Cria um bloco matemático e coloca elementos nele

**Parâmetros:**
| Parameter | Type | Description |
| --- | --- | --- |
| mathElements | [IMathElementCollection](../../com.aspose.slides/imathelementcollection) | elementos matemáticos |

**Retorna:**
[IMathBlock](../../com.aspose.slides/imathblock) - novo bloco matemático