---
title: IWarningCallback
second_title: Aspose.Slides for Java API Reference
description: Interface voor klassen die een waarschuwing ontvangen
type: docs
url: /nl/com.aspose.slides/iwarningcallback/
---```
public interface IWarningCallback
```

Interface voor klassen die een waarschuwing ontvangen
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [warning(IWarningInfo warning)](#warning-com.aspose.slides.IWarningInfo-) | Callback-methode die een waarschuwing ontvangt en bepaalt of de bewerking moet worden afgebroken. |
### warning(IWarningInfo warning) {#warning-com.aspose.slides.IWarningInfo-}
```
public abstract int warning(IWarningInfo warning)
```


Callback-methode die een waarschuwing ontvangt en bepaalt of de bewerking moet worden afgebroken.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| warning | [IWarningInfo](../../com.aspose.slides/iwarninginfo) | Waarschuwing om te verwerken. |

**Retourwaarde:**
int - Beslissing over afbreken [ReturnAction](../../com.aspose.slides/returnaction).