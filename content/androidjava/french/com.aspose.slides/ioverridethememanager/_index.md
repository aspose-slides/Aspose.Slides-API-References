---
title: IOverrideThemeManager
second_title: Aspose.Slides pour Android via la référence de l'API Java
description: Fournit un accès à différents types de thèmes remplacés.
type: docs
url: /fr/com.aspose.slides/ioverridethememanager/
---
**Toutes les interfaces implémentées:**
[com.aspose.slides.IThemeManager](../../com.aspose.slides/ithememanager)
```
public interface IOverrideThemeManager extends IThemeManager
```

Fournit un accès à différents types de thèmes remplacés.
## Méthodes

| Méthode | Description |
| --- | --- |
| [isOverrideThemeEnabled()](#isOverrideThemeEnabled--) | Détermine si OverrideTheme remplace le thème effectif hérité ou non. |
| [getOverrideTheme()](#getOverrideTheme--) | Renvoie l'objet de thème de remplacement. |
| [setOverrideTheme(IOverrideTheme value)](#setOverrideTheme-com.aspose.slides.IOverrideTheme-) | Renvoie l'objet de thème de remplacement. |
### isOverrideThemeEnabled() {#isOverrideThemeEnabled--}
```
public abstract boolean isOverrideThemeEnabled()
```

Détermine si OverrideTheme remplace le thème effectif hérité ou non. Pour activer OverrideTheme pour le remplacement, utilisez les méthodes OverrideTheme.Init\*(). Pour désactiver OverrideTheme du remplacement, utilisez la méthode OverrideTheme.Clear(). Booléen en lecture seule.

**Renvoie:**  
boolean
### getOverrideTheme() {#getOverrideTheme--}
```
public abstract IOverrideTheme getOverrideTheme()
```

Renvoie l'objet de thème de remplacement. Lecture/écriture [IOverrideTheme](../../com.aspose.slides/ioverridetheme).

**Renvoie:**  
[IOverrideTheme](../../com.aspose.slides/ioverridetheme)
### setOverrideTheme(IOverrideTheme value) {#setOverrideTheme-com.aspose.slides.IOverrideTheme-}
```
public abstract void setOverrideTheme(IOverrideTheme value)
```

Renvoie l'objet de thème de remplacement. Lecture/écriture [IOverrideTheme](../../com.aspose.slides/ioverridetheme).

**Paramètres:**  
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [IOverrideTheme](../../com.aspose.slides/ioverridetheme) |  |