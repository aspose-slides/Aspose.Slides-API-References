---
title: IWarningCallback
second_title: Aspose.Slides for Android via Java API Reference
description: Interface voor klassen die waarschuwingen ontvangen
type: docs
url: /nl/com.aspose.slides/iwarningcallback/
---```
public interface IWarningCallback
```

Interface voor klassen die waarschuwingen ontvangen
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [warning(IWarningInfo warning)](#warning-com.aspose.slides.IWarningInfo-) | Callback-methode die waarschuwingsbericht ontvangt en beslist of de bewerking moet worden afgebroken. |
### warning(IWarningInfo warning) {#warning-com.aspose.slides.IWarningInfo-}
```
public abstract int warning(IWarningInfo warning)
```


Callback-methode die waarschuwingsbericht ontvangt en beslist of de bewerking moet worden afgebroken.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| warning | [IWarningInfo](../../com.aspose.slides/iwarninginfo) | Waarschuwing om te verwerken. |

**Returns:**
int - Beslissing tot afbreken [ReturnAction](../../com.aspose.slides/returnaction).