---
title: MathLimitFactory
second_title: Aspose.Slides für Java API Referenz
description: Ermöglicht das Erstellen von IMathLimit
type: docs
url: /de/com.aspose.slides/mathlimitfactory/
---
**Vererbung:**
java.lang.Object

**Alle implementierten Schnittstellen:**
[com.aspose.slides.IMathLimitFactory](../../com.aspose.slides/imathlimitfactory)
```
public class MathLimitFactory implements IMathLimitFactory
```

Ermöglicht das Erstellen von IMathLimit

--------------------

Für COM-Kompatibilität
## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [MathLimitFactory()](#MathLimitFactory--) |  |
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [createMathLimit(IMathElement baseArg, IMathElement limit, boolean upperLimit)](#createMathLimit-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-boolean-) | Erstellt IMathLimit |
| [createMathLimit(IMathElement baseArg, IMathElement limit)](#createMathLimit-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-) | Erstellt IMathLimit mit dem Limit unten |
### MathLimitFactory() {#MathLimitFactory--}
```
public MathLimitFactory()
```


### createMathLimit(IMathElement baseArg, IMathElement limit, boolean upperLimit) {#createMathLimit-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-boolean-}
```
public final IMathLimit createMathLimit(IMathElement baseArg, IMathElement limit, boolean upperLimit)
```


Erstellt IMathLimit

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| baseArg | [IMathElement](../../com.aspose.slides/imathelement) | Basisargument zum Anwenden des Limits |
| limit | [IMathElement](../../com.aspose.slides/imathelement) | Limit-Element |
| upperLimit | boolean | Legt die Platzierung des Limits oben fest |

**Rückgabewert:**
[IMathLimit](../../com.aspose.slides/imathlimit) - neues Mathematik-Limit
### createMathLimit(IMathElement baseArg, IMathElement limit) {#createMathLimit-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-}
```
public final IMathLimit createMathLimit(IMathElement baseArg, IMathElement limit)
```


Erstellt IMathLimit mit dem Limit unten

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| baseArg | [IMathElement](../../com.aspose.slides/imathelement) | Basisargument zum Anwenden des Limits |
| limit | [IMathElement](../../com.aspose.slides/imathelement) | Limit-Element |

**Rückgabewert:**
[IMathLimit](../../com.aspose.slides/imathlimit) - neues Mathematik-Limit