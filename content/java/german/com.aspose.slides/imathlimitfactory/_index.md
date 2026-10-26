---
title: IMathLimitFactory
second_title: Aspose.Slides für Java API Referenz
description: Ermöglicht das Erstellen von IMathLimit
type: docs
url: /de/com.aspose.slides/imathlimitfactory/
---```
public interface IMathLimitFactory
```

Ermöglicht das Erstellen von IMathLimit

--------------------

Für COM-Kompatibilität
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [createMathLimit(IMathElement baseArg, IMathElement limit, boolean upperLimit)](#createMathLimit-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-boolean-) | Erstellt IMathLimit |
| [createMathLimit(IMathElement baseArg, IMathElement limit)](#createMathLimit-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-) | Erstellt IMathLimit mit Limit am unteren Rand |
### createMathLimit(IMathElement baseArg, IMathElement limit, boolean upperLimit) {#createMathLimit-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-boolean-}
```
public abstract IMathLimit createMathLimit(IMathElement baseArg, IMathElement limit, boolean upperLimit)
```

Erstellt IMathLimit

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| baseArg | [IMathElement](../../com.aspose.slides/imathelement) | Basisargument, auf das das Limit angewendet wird |
| limit | [IMathElement](../../com.aspose.slides/imathelement) | Limit-Element |
| upperLimit | boolean | Legt die Platzierung des Limits oben fest |

**Rückgabewert:**
[IMathLimit](../../com.aspose.slides/imathlimit) - neues Math-Limit
### createMathLimit(IMathElement baseArg, IMathElement limit) {#createMathLimit-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-}
```
public abstract IMathLimit createMathLimit(IMathElement baseArg, IMathElement limit)
```

Erstellt IMathLimit mit Limit am unteren Rand

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| baseArg | [IMathElement](../../com.aspose.slides/imathelement) | Basisargument, auf das das Limit angewendet wird |
| limit | [IMathElement](../../com.aspose.slides/imathelement) | Limit-Element |

**Rückgabewert:**
[IMathLimit](../../com.aspose.slides/imathlimit) - neues Math-Limit