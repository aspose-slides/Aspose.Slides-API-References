---
title: IInterruptionTokenSource
second_title: Aspose.Slides for Java API Reference
description: Represents the source of .
type: docs
url: /pl/com.aspose.slides/iinterruptiontokensource/
---```
public interface IInterruptionTokenSource
```

Reprezentuje źródło [IInterruptionToken](../../com.aspose.slides/iinterruptiontoken).
## Metody

| Metoda | Opis |
| --- | --- |
| [getToken()](#getToken--) | Zwraca nowy token powiązany z tym [IInterruptionTokenSource](../../com.aspose.slides/iinterruptiontokensource). |
| [isInterruptionRequested()](#isInterruptionRequested--) | Zwraca true, jeśli przerwanie zostało żądane, w przeciwnym razie false. |
| [interrupt()](#interrupt--) | Inicjalizuje żądanie przerwania. |
### getToken() {#getToken--}
```
public abstract IInterruptionToken getToken()
```


Zwraca nowy token powiązany z tym [IInterruptionTokenSource](../../com.aspose.slides/iinterruptiontokensource).

**Zwraca:**
[IInterruptionToken](../../com.aspose.slides/iinterruptiontoken)
### isInterruptionRequested() {#isInterruptionRequested--}
```
public abstract boolean isInterruptionRequested()
```


Zwraca true, jeśli przerwanie zostało żądane, w przeciwnym razie false.

**Zwraca:**
boolean
### interrupt() {#interrupt--}
```
public abstract void interrupt()
```


Inicjalizuje żądanie przerwania.