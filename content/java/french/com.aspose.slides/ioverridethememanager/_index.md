---
title: IOverrideThemeManager
second_title: "Référence de l'API Aspose.Slides pour Java"
description: Fournit un accès à différents types de thèmes remplacés.
type: docs
url: /fr/com.aspose.slides/ioverridethememanager/
---
**Toutes les interfaces implémentées :**
[com.aspose.slides.IThemeManager](../../com.aspose.slides/ithememanager)
```
public interface IOverrideThemeManager extends IThemeManager
```

Provides access to different types of overriden themes.
## Méthodes

| Méthode | Description |
| --- | --- |
| [isOverrideThemeEnabled()](#isOverrideThemeEnabled--) | Détermine si OverrideTheme remplace le thème effectif hérité ou non. |
| [getOverrideTheme()](#getOverrideTheme--) | Renvoie l'objet du thème de substitution. |
| [setOverrideTheme(IOverrideTheme value)](#setOverrideTheme-com.aspose.slides.IOverrideTheme-) | Renvoie l'objet du thème de substitution. |
### isOverrideThemeEnabled() {#isOverrideThemeEnabled--}
```
public abstract boolean isOverrideThemeEnabled()
```

Détermine si OverrideTheme remplace le thème effectif hérité ou non. Pour activer OverrideTheme pour le remplacement, utilisez les méthodes OverrideTheme.Init\*(). Pour désactiver OverrideTheme du remplacement, utilisez la méthode OverrideTheme.Clear(). Booléen en lecture seule.

**Renvoie :**  
boolean
### getOverrideTheme() {#getOverrideTheme--}
```
public abstract IOverrideTheme getOverrideTheme()
```

Renvoie l'objet du thème de substitution. Lecture/écriture [IOverrideTheme](../../com.aspose.slides/ioverridetheme).

**Renvoie :**  
[IOverrideTheme](../../com.aspose.slides/ioverridetheme)
### setOverrideTheme(IOverrideTheme value) {#setOverrideTheme-com.aspose.slides.IOverrideTheme-}
```
public abstract void setOverrideTheme(IOverrideTheme value)
```

Renvoie l'objet du thème de substitution. Lecture/écriture [IOverrideTheme](../../com.aspose.slides/ioverridetheme).

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [IOverrideTheme](../../com.aspose.slides/ioverridetheme) |  |