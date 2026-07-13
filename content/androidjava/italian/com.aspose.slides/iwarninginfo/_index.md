---
title: IWarningInfo
second_title: Aspose.Slides for Android via Java API Reference
description: Represents a base interface for all warnings.
type: docs
url: /it/com.aspose.slides/iwarninginfo/
---```
public interface IWarningInfo
```

Rappresenta un'interfaccia di base per tutti gli avvisi.
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [sendWarning(IWarningCallback receiver)](#sendWarning-com.aspose.slides.IWarningCallback-) | Se receiver non è nullo termina l'avviso verso un ricevitore specificato e lancia l'AbortRequestedException se receiver decide di abortire un'operazione. |
| [getWarningType()](#getWarningType--) | Restituisce un tipo di avviso. |
| [getDescription()](#getDescription--) | Restituisce una descrizione leggibile dall'uomo di questo avviso. |
### sendWarning(IWarningCallback receiver) {#sendWarning-com.aspose.slides.IWarningCallback-}
```
public abstract void sendWarning(IWarningCallback receiver)
```

Se receiver non è nullo termina l'avviso verso un ricevitore specificato e lancia l'AbortRequestedException se receiver decide di abortire un'operazione.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| receiver | [IWarningCallback](../../com.aspose.slides/iwarningcallback) | Oggetto ricevitore [IWarningCallback](../../com.aspose.slides/iwarningcallback) |

### getWarningType() {#getWarningType--}
```
public abstract int getWarningType()
```

Restituisce un tipo di avviso. Sola lettura [WarningType](../../com.aspose.slides/warningtype)(\#getWarningType.getWarningType).

**Restituisce:**
int
### getDescription() {#getDescription--}
```
public abstract String getDescription()
```

Restituisce una descrizione leggibile dall'uomo di questo avviso. Sola lettura String.

**Restituisce:**
java.lang.String