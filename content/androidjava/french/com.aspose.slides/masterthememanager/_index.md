---
title: MasterThemeManager
second_title: Aspose.Slides pour Android via la Référence de l'API Java
description: Fournit un accès au thème maître de la présentation.
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

Fournit un accès au thème maître de la présentation.
## Méthodes

| Méthode | Description |
| --- | --- |
| [getOverrideTheme()](#getOverrideTheme--) | Renvoie l'objet du thème de substitution. |
| [setOverrideTheme(IMasterTheme value)](#setOverrideTheme-com.aspose.slides.IMasterTheme-) | Renvoie l'objet du thème de substitution. |
| [createThemeEffective()](#createThemeEffective--) | Renvoie l'objet du thème. |
| [isOverrideThemeEnabled()](#isOverrideThemeEnabled--) | Détermine si OverrideTheme remplace le thème effectif hérité (Presentation.MasterTheme) ou non. |
| [setOverrideThemeEnabled(boolean value)](#setOverrideThemeEnabled-boolean-) | Détermine si OverrideTheme remplace le thème effectif hérité (Presentation.MasterTheme) ou non. |
| [applyColorScheme(IExtraColorScheme scheme)](#applyColorScheme-com.aspose.slides.IExtraColorScheme-) | Applique un schéma de couleurs supplémentaire à une diapositive. |
### getOverrideTheme() {#getOverrideTheme--}
```
public final IMasterTheme getOverrideTheme()
```

Renvoie l'objet du thème de substitution. Lecture/écriture [IMasterTheme](../../com.aspose.slides/imastertheme).

**Renvoie :**
[IMasterTheme](../../com.aspose.slides/imastertheme)
### setOverrideTheme(IMasterTheme value) {#setOverrideTheme-com.aspose.slides.IMasterTheme-}
```
public final void setOverrideTheme(IMasterTheme value)
```

Renvoie l'objet du thème de substitution. Lecture/écriture [IMasterTheme](../../com.aspose.slides/imastertheme).

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [IMasterTheme](../../com.aspose.slides/imastertheme) |  |

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

Détermine si OverrideTheme remplace le thème effectif hérité (Presentation.MasterTheme) ou non. Lecture/écriture booléen.

**Renvoie :**
boolean
### setOverrideThemeEnabled(boolean value) {#setOverrideThemeEnabled-boolean-}
```
public final void setOverrideThemeEnabled(boolean value)
```

Détermine si OverrideTheme remplace le thème effectif hérité (Presentation.MasterTheme) ou non. Lecture/écriture booléen.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### applyColorScheme(IExtraColorScheme scheme) {#applyColorScheme-com.aspose.slides.IExtraColorScheme-}
```
public final void applyColorScheme(IExtraColorScheme scheme)
```

Applique un schéma de couleurs supplémentaire à une diapositive.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| scheme | [IExtraColorScheme](../../com.aspose.slides/iextracolorscheme) | [IExtraColorScheme](../../com.aspose.slides/iextracolorscheme) objet. |