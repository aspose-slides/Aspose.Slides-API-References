---
title: IWarningCallback
second_title: Aspose.Slides for Java API Reference
description: Interface for classes which receive warning
type: docs
url: /fr/com.aspose.slides/iwarningcallback/
---```
public interface IWarningCallback
```

Interface pour les classes qui reçoivent un avertissement
## Méthodes

| Méthode | Description |
| --- | --- |
| [warning(IWarningInfo warning)](#warning-com.aspose.slides.IWarningInfo-) | Méthode de rappel qui reçoit un avertissement et décide si l'opération doit être abandonnée. |
### warning(IWarningInfo warning) {#warning-com.aspose.slides.IWarningInfo-}
```
public abstract int warning(IWarningInfo warning)
```

Méthode de rappel qui reçoit un avertissement et décide si l'opération doit être abandonnée.

**Parameters:**  
**Paramètres:**  
| Paramètre | Type | Description |
| --- | --- | --- |
| warning | [IWarningInfo](../../com.aspose.slides/iwarninginfo) | Avertissement à traiter. |

**Returns:**  
**Renvoie:**  
int - Décision d'abandon [ReturnAction](../../com.aspose.slides/returnaction).