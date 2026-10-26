---
title: IWarningInfo
second_title: Aspose.Slides pour Android via la référence de l'API Java
description: Représente une interface de base pour tous les avertissements.
type: docs
url: /fr/com.aspose.slides/iwarninginfo/
---```
public interface IWarningInfo
```

Représente une interface de base pour tous les avertissements.
## Méthodes

| Méthode | Description |
| --- | --- |
| [sendWarning(IWarningCallback receiver)](#sendWarning-com.aspose.slides.IWarningCallback-) | Si le récepteur n’est pas nul, termine l’avertissement pour le récepteur spécifié et lève l’AbortRequestedException si le récepteur décide d’annuler une opération. |
| [getWarningType()](#getWarningType--) | Renvoie un type d’avertissement. |
| [getDescription()](#getDescription--) | Renvoie une description lisible par l’homme de cet avertissement. |
### sendWarning(IWarningCallback receiver) {#sendWarning-com.aspose.slides.IWarningCallback-}
```
public abstract void sendWarning(IWarningCallback receiver)
```

Si le récepteur n’est pas nul, termine l’avertissement pour le récepteur spécifié et lève l’AbortRequestedException si le récepteur décide d’annuler une opération.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| receiver | [IWarningCallback](../../com.aspose.slides/iwarningcallback) | Objet récepteur [IWarningCallback](../../com.aspose.slides/iwarningcallback) |

### getWarningType() {#getWarningType--}
```
public abstract int getWarningType()
```

Renvoie un type d’avertissement. Lecture seule [WarningType](../../com.aspose.slides/warningtype)(\#getWarningType.getWarningType).

**Renvoie :**
int
### getDescription() {#getDescription--}
```
public abstract String getDescription()
```

Renvoie une description lisible par l’homme de cet avertissement. Lecture seule String.

**Renvoie :**
java.lang.String