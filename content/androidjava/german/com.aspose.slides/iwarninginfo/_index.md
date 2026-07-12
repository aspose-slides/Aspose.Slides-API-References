---
title: IWarningInfo
second_title: Aspose.Slides for Android via Java API Reference
description: Stellt eine Basisschnittstelle für alle Warnungen dar.
type: docs
url: /de/com.aspose.slides/iwarninginfo/
---```
public interface IWarningInfo
```

Stellt eine Basisschnittstelle für alle Warnungen dar.
## Methods

| Methode | Beschreibung |
| --- | --- |
| [sendWarning(IWarningCallback receiver)](#sendWarning-com.aspose.slides.IWarningCallback-) | Wenn receiver nicht null ist, beendet er die Warnung an einen spezifizierten receiver und wirft die AbortRequestedException, wenn receiver beschlossen hat, den Vorgang abzubrechen. |
| [getWarningType()](#getWarningType--) | Gibt einen Warnungstyp zurück. |
| [getDescription()](#getDescription--) | Gibt eine menschenlesbare Beschreibung dieser Warnung zurück. |
### sendWarning(IWarningCallback receiver) {#sendWarning-com.aspose.slides.IWarningCallback-}
```
public abstract void sendWarning(IWarningCallback receiver)
```

Wenn receiver nicht null ist, beendet er die Warnung an einen spezifizierten receiver und wirft die AbortRequestedException, wenn receiver beschlossen hat, den Vorgang abzubrechen.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| receiver | [IWarningCallback](../../com.aspose.slides/iwarningcallback) | Receiver-Objekt [IWarningCallback](../../com.aspose.slides/iwarningcallback) |

### getWarningType() {#getWarningType--}
```
public abstract int getWarningType()
```

Gibt einen Warnungstyp zurück. Nur lesbar [WarningType](../../com.aspose.slides/warningtype)(\#getWarningType.getWarningType).

**Rückgabe:**
int
### getDescription() {#getDescription--}
```
public abstract String getDescription()
```

Gibt eine menschenlesbare Beschreibung dieser Warnung zurück. Nur lesbar String.

**Rückgabe:**
java.lang.String