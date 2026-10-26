---
title: IInterruptionToken
second_title: Aspose.Slides pro Android přes Java API Reference
description: Tato třída představuje token, který se používá k signalizaci dlouho běžících úloh, zda bylo požadováno přerušení.
type: docs
url: /cs/com.aspose.slides/iinterruptiontoken/
---```
public interface IInterruptionToken
```

Tato třída představuje token, který se používá k signalizaci dlouho běžících úloh, zda bylo požadováno přerušení.
## Metody

| Metoda | Popis |
| --- | --- |
| [isInterruptionRequested()](#isInterruptionRequested--) | Vrací true, pokud bylo požádáno o přerušení. |
| [throwIfInterruptionRequested()](#throwIfInterruptionRequested--) | Vyvolá výjimku, pokud bylo požádáno o přerušení. |
### isInterruptionRequested() {#isInterruptionRequested--}
```
public abstract boolean isInterruptionRequested()
```


Vrací true, pokud bylo požádáno o přerušení.

**Vrací:**
boolean
### throwIfInterruptionRequested() {#throwIfInterruptionRequested--}
```
public abstract void throwIfInterruptionRequested()
```


Vyvolá výjimku, pokud bylo požádáno o přerušení.