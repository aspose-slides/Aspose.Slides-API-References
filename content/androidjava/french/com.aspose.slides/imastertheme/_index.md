---
title: IMasterTheme
second_title: Référence de l'API Java Aspose.Slides pour Android
description: Représente un thème maître.
type: docs
url: /fr/com.aspose.slides/imastertheme/
---
**Toutes les interfaces implémentées :**
[com.aspose.slides.ITheme](../../com.aspose.slides/itheme)
```
public interface IMasterTheme extends ITheme
```

Représente un thème principal.
## Méthodes

| Méthode | Description |
| --- | --- |
| [getExtraColorSchemes()](#getExtraColorSchemes--) | Renvoie la collection de schémas de couleur supplémentaires. |
| [getName()](#getName--) | Renvoie le nom d'un thème. |
| [setName(String value)](#setName-java.lang.String-) | Renvoie le nom d'un thème. |
### getExtraColorSchemes() {#getExtraColorSchemes--}
```
public abstract IExtraColorSchemeCollection getExtraColorSchemes()
```


Renvoie la collection de schémas de couleur supplémentaires. Ces schémas n'affectent pas l'apparence de la présentation, ils peuvent être sélectionnés comme schéma de couleur principal pour une diapositive. Lecture seule [IExtraColorSchemeCollection](../../com.aspose.slides/iextracolorschemecollection).

**Renvoie :**
[IExtraColorSchemeCollection](../../com.aspose.slides/iextracolorschemecollection)
### getName() {#getName--}
```
public abstract String getName()
```


Renvoie le nom d'un thème. Lecture/écriture String.

**Renvoie :**
java.lang.String
### setName(String value) {#setName-java.lang.String-}
```
public abstract void setName(String value)
```


Renvoie le nom d'un thème. Lecture/écriture String.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |