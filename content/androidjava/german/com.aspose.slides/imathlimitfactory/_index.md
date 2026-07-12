---
title: IMathLimitFactory
second_title: Aspose.Slides für Android über Java API-Referenz
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
| [createMathLimit(IMathElement baseArg, IMathElement limit)](#createMathLimit-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-) | Erstellt IMathLimit mit Grenze unten |
### createMathLimit(IMathElement baseArg, IMathElement limit, boolean upperLimit) {#createMathLimit-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-boolean-}
```
public abstract IMathLimit createMathLimit(IMathElement baseArg, IMathElement limit, boolean upperLimit)
```

Erstellt IMathLimit

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| baseArg | [IMathElement](../../com.aspose.slides/imathelement) | Basisargument, um die Grenze anzuwenden |
| limit | [IMathElement](../../com.aspose.slides/imathelement) | Grenzelement |
| upperLimit | boolean | Legt die Platzierung der Grenze oben fest |

**Rückgabewert:**
[IMathLimit](../../com.aspose.slides/imathlimit) - neuer mathematischer Grenzwert
### createMathLimit(IMathElement baseArg, IMathElement limit) {#createMathLimit-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-}
```
public abstract IMathLimit createMathLimit(IMathElement baseArg, IMathElement limit)
```

Erstellt IMathLimit mit Grenze unten

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| baseArg | [IMathElement](../../com.aspose.slides/imathelement) | Basisargument, um die Grenze anzuwenden |
| limit | [IMathElement](../../com.aspose.slides/imathelement) | Grenzelement |

**Rückgabewert:**
[IMathLimit](../../com.aspose.slides/imathlimit) - neuer mathematischer Grenzwert