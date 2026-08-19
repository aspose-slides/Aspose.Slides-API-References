---
title: IWarningInfo
second_title: Aspose.Slides for Java API Reference
description: Represents a base interface for all warnings.
type: docs
url: /sv/com.aspose.slides/iwarninginfo/
---```
public interface IWarningInfo
```

Representerar ett grundgränssnitt för alla varningar.
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [sendWarning(IWarningCallback receiver)](#sendWarning-com.aspose.slides.IWarningCallback-) | Om receiver inte är null avslutar varningen till en angiven receiver och kastar AbortRequestedException om receiver beslutade att avbryta en operation. |
| [getWarningType()](#getWarningType--) | Returnerar en typ av varning. |
| [getDescription()](#getDescription--) | Returnerar en människoläsbar beskrivning av denna varning. |
### sendWarning(IWarningCallback receiver) {#sendWarning-com.aspose.slides.IWarningCallback-}
```
public abstract void sendWarning(IWarningCallback receiver)
```


Om receiver inte är null avslutar varningen till en angiven receiver och kastar AbortRequestedException om receiver beslutade att avbryta en operation.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| receiver | [IWarningCallback](../../com.aspose.slides/iwarningcallback) | Mottagarobjekt [IWarningCallback](../../com.aspose.slides/iwarningcallback) |

### getWarningType() {#getWarningType--}
```
public abstract int getWarningType()
```


Returnerar en typ av varning. Skrivskyddad [WarningType](../../com.aspose.slides/warningtype)(\#getWarningType.getWarningType).

**Returnerar:**
int
### getDescription() {#getDescription--}
```
public abstract String getDescription()
```


Returnerar en människoläsbar beskrivning av denna varning. Skrivskyddad String.

**Returnerar:**
java.lang.String