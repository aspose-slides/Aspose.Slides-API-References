---
title: IWarningInfo
second_title: Riferimento API di Aspose.Slides per Java
description: Rappresenta un'interfaccia di base per tutti gli avvisi.
type: docs
url: /it/com.aspose.slides/iwarninginfo/
---```
public interface IWarningInfo
```

Rappresenta un'interfaccia di base per tutti gli avvisi.
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [sendWarning(IWarningCallback receiver)](#sendWarning-com.aspose.slides.IWarningCallback-) | If receiver is not null ends warning to a specified receiver and throws the AbortRequestedException if receiver decided to abort a operation. |
| [getWarningType()](#getWarningType--) | Returns a type of warning. |
| [getDescription()](#getDescription--) | Returns a human readable description of this warning. |
### sendWarning(IWarningCallback receiver) {#sendWarning-com.aspose.slides.IWarningCallback-}
```
public abstract void sendWarning(IWarningCallback receiver)
```

If receiver is not null ends warning to a specified receiver and throws the AbortRequestedException if receiver decided to abort a operation.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| receiver | [IWarningCallback](../../com.aspose.slides/iwarningcallback) | Receiver object [IWarningCallback](../../com.aspose.slides/iwarningcallback) |
### getWarningType() {#getWarningType--}
```
public abstract int getWarningType()
```

Restituisce un tipo di avviso. Solo lettura [WarningType](../../com.aspose.slides/warningtype)(\#getWarningType.getWarningType).

**Restituisce:**
int
### getDescription() {#getDescription--}
```
public abstract String getDescription()
```

Restituisce una descrizione leggibile dall'uomo di questo avviso. Solo lettura String.

**Restituisce:**
java.lang.String