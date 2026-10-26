---
title: IWarningInfo
second_title: Aspose.Slides pour Java - Référence de l'API
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
| [sendWarning(IWarningCallback receiver)](#sendWarning-com.aspose.slides.IWarningCallback-) | Si receiver n'est pas nul, termine l'avertissement pour un récepteur spécifié et lève l'AbortRequestedException si receiver décide d'annuler l'opération. |
| [getWarningType()](#getWarningType--) | Renvoie un type d'avertissement. |
| [getDescription()](#getDescription--) | Renvoie une description lisible de cet avertissement. |
### sendWarning(IWarningCallback receiver) {#sendWarning-com.aspose.slides.IWarningCallback-}
```
public abstract void sendWarning(IWarningCallback receiver)
```


Si receiver n'est pas nul, termine l'avertissement pour un récepteur spécifié et lève l'AbortRequestedException si receiver décide d'annuler l'opération.

**Paramètres:**
| Paramètre | Type | Description |
| --- | --- | --- |
| receiver | [IWarningCallback](../../com.aspose.slides/iwarningcallback) | Objet récepteur [IWarningCallback](../../com.aspose.slides/iwarningcallback) |

### getWarningType() {#getWarningType--}
```
public abstract int getWarningType()
```


Renvoie un type d'avertissement. Lecture seule [WarningType](../../com.aspose.slides/warningtype)(\#getWarningType.getWarningType).

**Renvoie:**
int
### getDescription() {#getDescription--}
```
public abstract String getDescription()
```


Renvoie une description lisible de cet avertissement. Lecture seule String.

**Renvoie:**
java.lang.String