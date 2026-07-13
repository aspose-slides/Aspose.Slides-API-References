---
title: IWarningInfo
second_title: Aspose.Slides dla Androida za pośrednictwem dokumentacji API Java
description: Reprezentuje podstawowy interfejs dla wszystkich ostrzeżeń.
type: docs
url: /pl/com.aspose.slides/iwarninginfo/
---```
public interface IWarningInfo
```

Reprezentuje podstawowy interfejs dla wszystkich ostrzeżeń.
## Metody

| Metoda | Opis |
| --- | --- |
| [sendWarning(IWarningCallback receiver)](#sendWarning-com.aspose.slides.IWarningCallback-) | Jeśli receiver nie jest null, kończy ostrzeżenie do określonego receiver i rzuca AbortRequestedException, jeśli receiver zdecydował przerwać operację. |
| [getWarningType()](#getWarningType--) | Zwraca typ ostrzeżenia. |
| [getDescription()](#getDescription--) | Zwraca czytelną dla człowieka opis tego ostrzeżenia. |
### sendWarning(IWarningCallback receiver) {#sendWarning-com.aspose.slides.IWarningCallback-}
```
public abstract void sendWarning(IWarningCallback receiver)
```


Jeśli receiver nie jest null, kończy ostrzeżenie do określonego receiver i rzuca AbortRequestedException, jeśli receiver zdecydował przerwać operację.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| receiver | [IWarningCallback](../../com.aspose.slides/iwarningcallback) | Obiekt receiver [IWarningCallback](../../com.aspose.slides/iwarningcallback) |

### getWarningType() {#getWarningType--}
```
public abstract int getWarningType()
```


Zwraca typ ostrzeżenia. Tylko do odczytu [WarningType](../../com.aspose.slides/warningtype)(\#getWarningType.getWarningType).

**Zwraca:**
int
### getDescription() {#getDescription--}
```
public abstract String getDescription()
```


Zwraca czytelną dla człowieka opis tego ostrzeżenia. Tylko do odczytu String.

**Zwraca:**
java.lang.String