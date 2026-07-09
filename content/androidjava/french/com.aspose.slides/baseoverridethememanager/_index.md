---
title: BaseOverrideThemeManager
second_title: Aspose.Slides pour Android via la référence API Java
description: Classe de base pour les classes qui donnent accès à différents types de thèmes remplacés.
type: docs
url: /fr/com.aspose.slides/baseoverridethememanager/
---
**Héritage :**
java.lang.Object, [com.aspose.slides.BaseThemeManager](../../com.aspose.slides/basethememanager)

**Toutes les interfaces implémentées :**
[com.aspose.slides.IOverrideThemeManager](../../com.aspose.slides/ioverridethememanager)
```
public abstract class BaseOverrideThemeManager extends BaseThemeManager implements IOverrideThemeManager
```

Classe de base pour les classes qui donnent accès à différents types de thèmes remplacés.
## Méthodes

| Méthode | Description |
| --- | --- |
| [getOverrideTheme()](#getOverrideTheme--) | Renvoie l'objet du thème de substitution. |
| [setOverrideTheme(IOverrideTheme value)](#setOverrideTheme-com.aspose.slides.IOverrideTheme-) | Renvoie l'objet du thème de substitution. |
| [createThemeEffective()](#createThemeEffective--) | Renvoie l'objet du thème. |
| [isOverrideThemeEnabled()](#isOverrideThemeEnabled--) | Détermine si OverrideTheme remplace le thème effectif hérité ou non. |
| [applyColorScheme(IExtraColorScheme scheme)](#applyColorScheme-com.aspose.slides.IExtraColorScheme-) | Applique un schéma de couleur supplémentaire à une diapositive. |
### getOverrideTheme() {#getOverrideTheme--}
```
public final IOverrideTheme getOverrideTheme()
```

Renvoie l'objet du thème de substitution. Lecture/écriture [IOverrideTheme](../../com.aspose.slides/ioverridetheme).

**Renvoie :**
[IOverrideTheme](../../com.aspose.slides/ioverridetheme)
### setOverrideTheme(IOverrideTheme value) {#setOverrideTheme-com.aspose.slides.IOverrideTheme-}
```
public final void setOverrideTheme(IOverrideTheme value)
```

Renvoie l'objet du thème de substitution. Lecture/écriture [IOverrideTheme](../../com.aspose.slides/ioverridetheme).

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [IOverrideTheme](../../com.aspose.slides/ioverridetheme) |  |
### createThemeEffective() {#createThemeEffective--}
```
public final IThemeEffectiveData createThemeEffective()
```

Renvoie l'objet du thème.

**Renvoie :**
[IThemeEffectiveData](../../com.aspose.slides/ithemeeffectivedata)
### isOverrideThemeEnabled() {#isOverrideThemeEnabled--}
```
public final boolean isOverrideThemeEnabled()
```

Détermine si OverrideTheme remplace le thème effectif hérité ou non. Pour activer OverrideTheme pour la substitution, utilisez les méthodes OverrideTheme.Init\*(). Pour désactiver OverrideTheme de la substitution, utilisez la méthode OverrideTheme.Clear(). Booléen en lecture seule.

**Renvoie :**
boolean
### applyColorScheme(IExtraColorScheme scheme) {#applyColorScheme-com.aspose.slides.IExtraColorScheme-}
```
public final void applyColorScheme(IExtraColorScheme scheme)
```

Applique un schéma de couleur supplémentaire à une diapositive.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| scheme | [IExtraColorScheme](../../com.aspose.slides/iextracolorscheme) | L'objet [IExtraColorScheme](../../com.aspose.slides/iextracolorscheme). |