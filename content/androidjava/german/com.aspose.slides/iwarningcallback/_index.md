---
title: IWarningCallback
second_title: Aspose.Slides für Android via Java API-Referenz
description: Schnittstelle für Klassen, die Warnungen erhalten
type: docs
url: /de/com.aspose.slides/iwarningcallback/
---```
public interface IWarningCallback
```

Schnittstelle für Klassen, die Warnungen erhalten
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [warning(IWarningInfo warning)](#warning-com.aspose.slides.IWarningInfo-) | Callback-Methode, die eine Warnung empfängt und entscheidet, ob der Vorgang abgebrochen werden soll. |
### warning(IWarningInfo warning) {#warning-com.aspose.slides.IWarningInfo-}
```
public abstract int warning(IWarningInfo warning)
```

Callback-Methode, die eine Warnung empfängt und entscheidet, ob der Vorgang abgebrochen werden soll.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| warning | [IWarningInfo](../../com.aspose.slides/iwarninginfo) | Warnung zur Verarbeitung. |

**Rückgabewert:**
int - Abbruchentscheidung [ReturnAction](../../com.aspose.slides/returnaction).