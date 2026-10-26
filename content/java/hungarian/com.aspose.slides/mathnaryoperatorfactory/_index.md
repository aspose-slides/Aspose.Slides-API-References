---
title: MathNaryOperatorFactory
second_title: Aspose.Slides Java API Referencia
description: Lehetővé teszi az IMathNaryOperator létrehozását
type: docs
url: /hu/com.aspose.slides/mathnaryoperatorfactory/
---
**Öröklés:**
java.lang.Object

**Minden megvalósított interfész:**
[com.aspose.slides.IMathNaryOperatorFactory](../../com.aspose.slides/imathnaryoperatorfactory)
```
public class MathNaryOperatorFactory implements IMathNaryOperatorFactory
```

Lehetővé teszi az IMathNaryOperator létrehozását

--------------------

A COM kompatibilitáshoz
## Konstruktorok

| Konstruktor | Leírás |
| --- | --- |
| [MathNaryOperatorFactory()](#MathNaryOperatorFactory--) |  |
## Metódusok

| Metódus | Leírás |
| --- | --- |
| [createMathNaryOperator(char operatorSymbol, IMathElement baseArgument, IMathElement lowerLimit, IMathElement upperLimit)](#createMathNaryOperator-char-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-) | Létrehozza az IMathNaryOperator objektumot |
| [createMathNaryOperator(char operatorSymbol, IMathElement baseArgument, IMathElement lowerLimit)](#createMathNaryOperator-char-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-) | Létrehozza az IMathNaryOperator objektumot |
| [createMathNaryOperator(char operatorSymbol, IMathElement baseArgument)](#createMathNaryOperator-char-com.aspose.slides.IMathElement-) | Létrehozza az IMathNaryOperator objektumot |
### MathNaryOperatorFactory() {#MathNaryOperatorFactory--}
```
public MathNaryOperatorFactory()
```

### createMathNaryOperator(char operatorSymbol, IMathElement baseArgument, IMathElement lowerLimit, IMathElement upperLimit) {#createMathNaryOperator-char-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-}
```
public final IMathNaryOperator createMathNaryOperator(char operatorSymbol, IMathElement baseArgument, IMathElement lowerLimit, IMathElement upperLimit)
```

Létrehozza az IMathNaryOperator objektumot

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| operatorSymbol | char | Az operátor jele |
| baseArgument | [IMathElement](../../com.aspose.slides/imathelement) | Alapargumentum az operátor alkalmazásához |
| lowerLimit | [IMathElement](../../com.aspose.slides/imathelement) | Alsó határ |
| upperLimit | [IMathElement](../../com.aspose.slides/imathelement) | Felső határ |

**Visszatérési érték:**
[IMathNaryOperator](../../com.aspose.slides/imathnaryoperator) - új IMathNaryOperator
### createMathNaryOperator(char operatorSymbol, IMathElement baseArgument, IMathElement lowerLimit) {#createMathNaryOperator-char-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-}
```
public final IMathNaryOperator createMathNaryOperator(char operatorSymbol, IMathElement baseArgument, IMathElement lowerLimit)
```

Létrehozza az IMathNaryOperator objektumot

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| operatorSymbol | char | Az operátor jele |
| baseArgument | [IMathElement](../../com.aspose.slides/imathelement) | Alapargumentum az operátor alkalmazásához |
| lowerLimit | [IMathElement](../../com.aspose.slides/imathelement) | Alsó határ |

**Visszatérési érték:**
[IMathNaryOperator](../../com.aspose.slides/imathnaryoperator) - új IMathNaryOperator
### createMathNaryOperator(char operatorSymbol, IMathElement baseArgument) {#createMathNaryOperator-char-com.aspose.slides.IMathElement-}
```
public final IMathNaryOperator createMathNaryOperator(char operatorSymbol, IMathElement baseArgument)
```

Létrehozza az IMathNaryOperator objektumot

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| operatorSymbol | char | Az operátor jele |
| baseArgument | [IMathElement](../../com.aspose.slides/imathelement) | Alapargumentum az operátor alkalmazásához |

**Visszatérési érték:**
[IMathNaryOperator](../../com.aspose.slides/imathnaryoperator) - új IMathNaryOperator