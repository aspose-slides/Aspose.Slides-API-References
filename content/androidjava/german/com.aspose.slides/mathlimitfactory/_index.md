---
title: MathLimitFactory
second_title: Aspose.Slides für Android über Java API Referenz
description: Ermöglicht die Erstellung von IMathLimit
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

Ermöglicht die Erstellung von IMathLimit

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
| [createMathLimit(IMathElement baseArg, IMathElement limit)](#createMathLimit-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-) | Erstellt IMathLimit mit Grenze unten |
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
| baseArg | [IMathElement](../../com.aspose.slides/imathelement) | Basisargument, auf das die Grenze angewendet wird |
| limit | [IMathElement](../../com.aspose.slides/imathelement) | Grenzelement |
| upperLimit | boolean | Legt die Platzierung der Grenze oben fest |

**Rückgabewert:**
[IMathLimit](../../com.aspose.slides/imathlimit) - neue mathematische Grenze
### createMathLimit(IMathElement baseArg, IMathElement limit) {#createMathLimit-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-}
```
public final IMathLimit createMathLimit(IMathElement baseArg, IMathElement limit)
```


Erstellt IMathLimit mit Grenze unten

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| baseArg | [IMathElement](../../com.aspose.slides/imathelement) | Basisargument, auf das die Grenze angewendet wird |
| limit | [IMathElement](../../com.aspose.slides/imathelement) | Grenzelement |

**Rückgabewert:**
[IMathLimit](../../com.aspose.slides/imathlimit) - neue mathematische Grenze