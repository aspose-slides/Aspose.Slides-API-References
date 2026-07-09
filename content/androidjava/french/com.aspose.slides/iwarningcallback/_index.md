---
title: IWarningCallback
second_title: Aspose.Slides pour Android via la référence API Java
description: Interface pour les classes qui reçoivent des avertissements
type: docs
url: /fr/com.aspose.slides/iwarningcallback/
---
```
public interface IWarningCallback
```

Interface pour les classes qui reçoivent des avertissements
## Méthodes

| Méthode | Description |
| --- | --- |
| [warning(IWarningInfo warning)](#warning-com.aspose.slides.IWarningInfo-) | Méthode de rappel qui reçoit un avertissement et décide si l'opération doit être abandonnée. |
### warning(IWarningInfo warning) {#warning-com.aspose.slides.IWarningInfo-}
```
public abstract int warning(IWarningInfo warning)
```

Méthode de rappel qui reçoit un avertissement et décide si l'opération doit être abandonnée.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| warning | [IWarningInfo](../../com.aspose.slides/iwarninginfo) | Avertissement à traiter. |

**Renvoie :**
int - Décision d'abandon [ReturnAction](../../com.aspose.slides/returnaction).