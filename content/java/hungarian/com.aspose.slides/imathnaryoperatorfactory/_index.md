---
title: IMathNaryOperatorFactory
second_title: Aspose.Slides Java API-referencia
description: Lehetővé teszi az IMathNaryOperator létrehozását
type: docs
url: /hu/com.aspose.slides/imathnaryoperatorfactory/
---```
public interface IMathNaryOperatorFactory
```

Lehetővé teszi az IMathNaryOperator létrehozását

--------------------

COM kompatibilitáshoz
## Módszerek

| Módszer | Leírás |
| --- | --- |
| [createMathNaryOperator(char operatorSymbol, IMathElement baseArgument, IMathElement lowerLimit, IMathElement upperLimit)](#createMathNaryOperator-char-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-) | Létrehozza az IMathNaryOperator |
| [createMathNaryOperator(char operatorSymbol, IMathElement baseArgument, IMathElement lowerLimit)](#createMathNaryOperator-char-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-) | Létrehozza az IMathNaryOperator |
| [createMathNaryOperator(char operatorSymbol, IMathElement baseArgument)](#createMathNaryOperator-char-com.aspose.slides.IMathElement-) | Létrehozza az IMathNaryOperator |
### createMathNaryOperator(char operatorSymbol, IMathElement baseArgument, IMathElement lowerLimit, IMathElement upperLimit) {#createMathNaryOperator-char-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-}
```
public abstract IMathNaryOperator createMathNaryOperator(char operatorSymbol, IMathElement baseArgument, IMathElement lowerLimit, IMathElement upperLimit)
```


Létrehozza az IMathNaryOperator

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| operatorSymbol | char | Az operátor jele |
| baseArgument | [IMathElement](../../com.aspose.slides/imathelement) | Alapargumentum az operátor alkalmazásához |
| lowerLimit | [IMathElement](../../com.aspose.slides/imathelement) | Alsó határ |
| upperLimit | [IMathElement](../../com.aspose.slides/imathelement) | Felső határ |

**Visszatérési érték:**
[IMathNaryOperator](../../com.aspose.slides/imathnaryoperator) - new IMathNaryOperator
### createMathNaryOperator(char operatorSymbol, IMathElement baseArgument, IMathElement lowerLimit) {#createMathNaryOperator-char-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-}
```
public abstract IMathNaryOperator createMathNaryOperator(char operatorSymbol, IMathElement baseArgument, IMathElement lowerLimit)
```


Létrehozza az IMathNaryOperator

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| operatorSymbol | char | Az operátor jele |
| baseArgument | [IMathElement](../../com.aspose.slides/imathelement) | Alapargumentum az operátor alkalmazásához |
| lowerLimit | [IMathElement](../../com.aspose.slides/imathelement) | Alsó határ |

**Visszatérési érték:**
[IMathNaryOperator](../../com.aspose.slides/imathnaryoperator) - new IMathNaryOperator
### createMathNaryOperator(char operatorSymbol, IMathElement baseArgument) {#createMathNaryOperator-char-com.aspose.slides.IMathElement-}
```
public abstract IMathNaryOperator createMathNaryOperator(char operatorSymbol, IMathElement baseArgument)
```


Létrehozza az IMathNaryOperator

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| operatorSymbol | char | Az operátor jele |
| baseArgument | [IMathElement](../../com.aspose.slides/imathelement) | Alapargumentum az operátor alkalmazásához |

**Visszatérési érték:**
[IMathNaryOperator](../../com.aspose.slides/imathnaryoperator) - new IMathNaryOperator