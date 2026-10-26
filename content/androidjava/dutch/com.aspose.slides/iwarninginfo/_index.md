---
title: IWarningInfo
second_title: Aspose.Slides for Android via Java API Reference
description: Vertegenwoordigt een basisinterface voor alle waarschuwingen.
type: docs
url: /nl/com.aspose.slides/iwarninginfo/
---```
public interface IWarningInfo
```

Vertegenwoordigt een basisinterface voor alle waarschuwingen.
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [sendWarning(IWarningCallback receiver)](#sendWarning-com.aspose.slides.IWarningCallback-) | Als receiver niet null is eindigt de waarschuwing naar een opgegeven receiver en wordt de AbortRequestedException gegooid als de receiver besluit de bewerking af te breken. |
| [getWarningType()](#getWarningType--) | Retourneert een type waarschuwing. |
| [getDescription()](#getDescription--) | Retourneert een menselijk leesbare beschrijving van deze waarschuwing. |
### sendWarning(IWarningCallback receiver) {#sendWarning-com.aspose.slides.IWarningCallback-}
```
public abstract void sendWarning(IWarningCallback receiver)
```


Als receiver niet null is eindigt de waarschuwing naar een opgegeven receiver en wordt de AbortRequestedException gegooid als de receiver besluit de bewerking af te breken.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| receiver | [IWarningCallback](../../com.aspose.slides/iwarningcallback) | Receiver-object [IWarningCallback](../../com.aspose.slides/iwarningcallback) |

### getWarningType() {#getWarningType--}
```
public abstract int getWarningType()
```


Retourneert een type waarschuwing. Alleen-lezen [WarningType](../../com.aspose.slides/warningtype)(\#getWarningType.getWarningType).

**Returns:**
int
### getDescription() {#getDescription--}
```
public abstract String getDescription()
```


Retourneert een menselijk leesbare beschrijving van deze waarschuwing. Alleen-lezen String.

**Returns:**
java.lang.String