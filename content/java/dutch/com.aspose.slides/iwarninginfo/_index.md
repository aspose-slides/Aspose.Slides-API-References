---
title: IWarningInfo
second_title: Aspose.Slides for Java API Reference
description: Stelt een basisinterface voor alle waarschuwingen voor.
type: docs
url: /nl/com.aspose.slides/iwarninginfo/
---```
public interface IWarningInfo
```

Stelt een basisinterface voor alle waarschuwingen voor.
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [sendWarning(IWarningCallback receiver)](#sendWarning-com.aspose.slides.IWarningCallback-) | Als receiver niet null is, beëindigt de waarschuwing naar een opgegeven receiver en gooit de AbortRequestedException als receiver besluit de bewerking te aborteren. |
| [getWarningType()](#getWarningType--) | Retourneert een type waarschuwing. |
| [getDescription()](#getDescription--) | Retourneert een leesbare beschrijving van deze waarschuwing. |
### sendWarning(IWarningCallback receiver) {#sendWarning-com.aspose.slides.IWarningCallback-}
```
public abstract void sendWarning(IWarningCallback receiver)
```

Als receiver niet null is, beëindigt de waarschuwing naar een opgegeven receiver en gooit de AbortRequestedException als receiver besluit de bewerking te aborteren.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| receiver | [IWarningCallback](../../com.aspose.slides/iwarningcallback) | Receiver object [IWarningCallback](../../com.aspose.slides/iwarningcallback) |

### getWarningType() {#getWarningType--}
```
public abstract int getWarningType()
```

Retourneert een type waarschuwing. Alleen-lezen [WarningType](../../com.aspose.slides/warningtype)(\#getWarningType.getWarningType).

**Retour:**
int
### getDescription() {#getDescription--}
```
public abstract String getDescription()
```

Retourneert een leesbare beschrijving van deze waarschuwing. Alleen-lezen String.

**Retour:**
java.lang.String