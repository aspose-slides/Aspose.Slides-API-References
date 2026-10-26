---
title: MasterThemeManager
second_title: Référence API Aspose.Slides pour Java
description: Fournit l'accès au thème maître de la présentation.
type: docs
url: /fr/com.aspose.slides/masterthememanager/
---
**Héritage :**
java.lang.Object, [com.aspose.slides.BaseThemeManager](../../com.aspose.slides/basethememanager)

**Toutes les interfaces implémentées :**
[com.aspose.slides.IMasterThemeManager](../../com.aspose.slides/imasterthememanager)
```
public class MasterThemeManager extends BaseThemeManager implements IMasterThemeManager
```

Fournit l'accès au thème maître de la présentation.
## Méthodes

| Méthode | Description |
| --- | --- |
| [getOverrideTheme()](#getOverrideTheme--) | Renvoie l'objet de thème de substitution. |
| [setOverrideTheme(IMasterTheme value)](#setOverrideTheme-com.aspose.slides.IMasterTheme-) | Renvoie l'objet de thème de substitution. |
| [createThemeEffective()](#createThemeEffective--) | Renvoie l'objet de thème. |
| [isOverrideThemeEnabled()](#isOverrideThemeEnabled--) | Détermine si OverrideTheme remplace le thème effectif hérité (Presentation.MasterTheme) ou non. |
| [setOverrideThemeEnabled(boolean value)](#setOverrideThemeEnabled-boolean-) | Détermine si OverrideTheme remplace le thème effectif hérité (Presentation.MasterTheme) ou non. |
| [applyColorScheme(IExtraColorScheme scheme)](#applyColorScheme-com.aspose.slides.IExtraColorScheme-) | Applique un schéma de couleur supplémentaire à une diapositive. |
### getOverrideTheme() {#getOverrideTheme--}
```
public final IMasterTheme getOverrideTheme()
```

Renvoie l'objet de thème de substitution. Lecture/écriture [IMasterTheme](../../com.aspose.slides/imastertheme).

**Retour :**
[IMasterTheme](../../com.aspose.slides/imastertheme)
### setOverrideTheme(IMasterTheme value) {#setOverrideTheme-com.aspose.slides.IMasterTheme-}
```
public final void setOverrideTheme(IMasterTheme value)
```

Renvoie l'objet de thème de substitution. Lecture/écriture [IMasterTheme](../../com.aspose.slides/imastertheme).

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [IMasterTheme](../../com.aspose.slides/imastertheme) |  |
### createThemeEffective() {#createThemeEffective--}
```
public final IThemeEffectiveData createThemeEffective()
```

Renvoie l'objet de thème.

**Retour :**
[IThemeEffectiveData](../../com.aspose.slides/ithemeeffectivedata)
### isOverrideThemeEnabled() {#isOverrideThemeEnabled--}
```
public final boolean isOverrideThemeEnabled()
```

Détermine si OverrideTheme remplace le thème effectif hérité (Presentation.MasterTheme) ou non. Lecture/écriture boolean.

**Retour :**
boolean
### setOverrideThemeEnabled(boolean value) {#setOverrideThemeEnabled-boolean-}
```
public final void setOverrideThemeEnabled(boolean value)
```

Détermine si OverrideTheme remplace le thème effectif hérité (Presentation.MasterTheme) ou non. Lecture/écriture boolean.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | boolean |  |
### applyColorScheme(IExtraColorScheme scheme) {#applyColorScheme-com.aspose.slides.IExtraColorScheme-}
```
public final void applyColorScheme(IExtraColorScheme scheme)
```

Applique un schéma de couleur supplémentaire à une diapositive.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| scheme | [IExtraColorScheme](../../com.aspose.slides/iextracolorscheme) | [IExtraColorScheme](../../com.aspose.slides/iextracolorscheme) objet. |