---
title: IMathLimitFactory
second_title: Aspose.Slides for Android via Java API Reference
description: Allows to create IMathLimit
type: docs
url: /hu/com.aspose.slides/imathlimitfactory/
---```
public interface IMathLimitFactory
```

Lehetővé teszi az IMathLimit létrehozását

--------------------

COM kompatibilitásért
## Módszerek

| Módszer | Leírás |
| --- | --- |
| [createMathLimit(IMathElement baseArg, IMathElement limit, boolean upperLimit)](#createMathLimit-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-boolean-) | Létrehozza az IMathLimit |
| [createMathLimit(IMathElement baseArg, IMathElement limit)](#createMathLimit-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-) | Létrehozza az IMathLimit-et a limit alján |
### createMathLimit(IMathElement baseArg, IMathElement limit, boolean upperLimit) {#createMathLimit-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-boolean-}
```
public abstract IMathLimit createMathLimit(IMathElement baseArg, IMathElement limit, boolean upperLimit)
```

Létrehozza az IMathLimit

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| baseArg | [IMathElement](../../com.aspose.slides/imathelement) | Alap argumentum a limit alkalmazásához |
| limit | [IMathElement](../../com.aspose.slides/imathelement) | Limit elem |
| upperLimit | boolean | Beállítja a limit elhelyezését felül |

**Visszatérési érték:**
[IMathLimit](../../com.aspose.slides/imathlimit) - új matematikai limit
### createMathLimit(IMathElement baseArg, IMathElement limit) {#createMathLimit-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-}
```
public abstract IMathLimit createMathLimit(IMathElement baseArg, IMathElement limit)
```

Létrehozza az IMathLimit-et a limit alján

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| baseArg | [IMathElement](../../com.aspose.slides/imathelement) | Alap argumentum a limit alkalmazásához |
| limit | [IMathElement](../../com.aspose.slides/imathelement) | Limit elem |

**Visszatérési érték:**
[IMathLimit](../../com.aspose.slides/imathlimit) - új matematikai limit