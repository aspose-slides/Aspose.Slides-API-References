---
title: MathLimitFactory
second_title: Aspose.Slides Java API referencia
description: Lehetővé teszi az IMathLimit létrehozását
type: docs
url: /hu/com.aspose.slides/mathlimitfactory/
---
**Öröklődés:**
java.lang.Object

**Minden megvalósított interfész:**
[com.aspose.slides.IMathLimitFactory](../../com.aspose.slides/imathlimitfactory)
```
public class MathLimitFactory implements IMathLimitFactory
```

Lehetővé teszi az IMathLimit létrehozását

--------------------

COM kompatibilitáshoz
## Konstruktorok

| Konstruktor | Leírás |
| --- | --- |
| [MathLimitFactory()](#MathLimitFactory--) |  |
## Metódusok

| Metódus | Leírás |
| --- | --- |
| [createMathLimit(IMathElement baseArg, IMathElement limit, boolean upperLimit)](#createMathLimit-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-boolean-) | Létrehozza az IMathLimit |
| [createMathLimit(IMathElement baseArg, IMathElement limit)](#createMathLimit-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-) | Létrehozza az IMathLimitet az alsó határral |
### MathLimitFactory() {#MathLimitFactory--}
```
public MathLimitFactory()
```

### createMathLimit(IMathElement baseArg, IMathElement limit, boolean upperLimit) {#createMathLimit-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-boolean-}
```
public final IMathLimit createMathLimit(IMathElement baseArg, IMathElement limit, boolean upperLimit)
```

Létrehozza az IMathLimit

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| baseArg | [IMathElement](../../com.aspose.slides/imathelement) | Az alapargumentum a határ alkalmazásához |
| limit | [IMathElement](../../com.aspose.slides/imathelement) | Határ elem |
| upperLimit | boolean | Beállítja a határ elhelyezését felül |

**Visszatérési érték:**
[IMathLimit](../../com.aspose.slides/imathlimit) - új matematikai határ
### createMathLimit(IMathElement baseArg, IMathElement limit) {#createMathLimit-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-}
```
public final IMathLimit createMathLimit(IMathElement baseArg, IMathElement limit)
```

Létrehozza az IMathLimitet az alsó határral

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| baseArg | [IMathElement](../../com.aspose.slides/imathelement) | Az alapargumentum a határ alkalmazásához |
| limit | [IMathElement](../../com.aspose.slides/imathelement) | Határ elem |

**Visszatérési érték:**
[IMathLimit](../../com.aspose.slides/imathlimit) - új matematikai határ