---
title: MathLimitFactory
second_title: Aspose.Slides Androidra a Java API referencián keresztül
description: Lehetővé teszi az IMathLimit létrehozását
type: docs
url: /hu/com.aspose.slides/mathlimitfactory/
---
**Öröklés:**
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
| [createMathLimit(IMathElement baseArg, IMathElement limit, boolean upperLimit)](#createMathLimit-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-boolean-) | Létrehozza az IMathLimit-et |
| [createMathLimit(IMathElement baseArg, IMathElement limit)](#createMathLimit-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-) | Létrehozza az IMathLimit-et a korláttal alul |
### MathLimitFactory() {#MathLimitFactory--}
```
public MathLimitFactory()
```


### createMathLimit(IMathElement baseArg, IMathElement limit, boolean upperLimit) {#createMathLimit-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-boolean-}
```
public final IMathLimit createMathLimit(IMathElement baseArg, IMathElement limit, boolean upperLimit)
```


Létrehozza az IMathLimit-et

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| baseArg | [IMathElement](../../com.aspose.slides/imathelement) | Az alap argumentum a korlát alkalmazásához |
| limit | [IMathElement](../../com.aspose.slides/imathelement) | Korlátozó elem |
| upperLimit | boolean | Beállítja a korlát elhelyezkedését felül |

**Visszatérési érték:**
[IMathLimit](../../com.aspose.slides/imathlimit) - új matematikai korlát
### createMathLimit(IMathElement baseArg, IMathElement limit) {#createMathLimit-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-}
```
public final IMathLimit createMathLimit(IMathElement baseArg, IMathElement limit)
```


Létrehozza az IMathLimit-et a korláttal alul

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| baseArg | [IMathElement](../../com.aspose.slides/imathelement) | Az alap argumentum a korlát alkalmazásához |
| limit | [IMathElement](../../com.aspose.slides/imathelement) | Korlátozó elem |

**Visszatérési érték:**
[IMathLimit](../../com.aspose.slides/imathlimit) - új matematikai korlát