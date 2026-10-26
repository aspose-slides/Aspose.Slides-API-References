---
title: BaseOverrideThemeManager
second_title: Référence de l'API Aspose.Slides pour Java
description: Classe de base pour les classes qui offrent un accès à différents types de thèmes remplacés.
type: docs
url: /fr/com.aspose.slides/baseoverridethememanager/
---
**Héritage:**  
java.lang.Object, [com.aspose.slides.BaseThemeManager](../../com.aspose.slides/basethememanager)

**Toutes les interfaces implémentées:**  
[com.aspose.slides.IOverrideThemeManager](../../com.aspose.slides/ioverridethememanager)  
```
public abstract class BaseOverrideThemeManager extends BaseThemeManager implements IOverrideThemeManager
```

Classe de base pour les classes qui offrent un accès à différents types de thèmes remplacés.

## Méthodes

| Méthode | Description |
| --- | --- |
| [getOverrideTheme()](#getOverrideTheme--) | Renvoie l'objet de thème de substitution. |
| [setOverrideTheme(IOverrideTheme value)](#setOverrideTheme-com.aspose.slides.IOverrideTheme-) | Renvoie l'objet de thème de substitution. |
| [createThemeEffective()](#createThemeEffective--) | Renvoie l'objet de thème. |
| [isOverrideThemeEnabled()](#isOverrideThemeEnabled--) | Détermine si OverrideTheme remplace le thème effectif hérité ou non. |
| [applyColorScheme(IExtraColorScheme scheme)](#applyColorScheme-com.aspose.slides.IExtraColorScheme-) | Applique un schéma de couleurs supplémentaire à une diapositive. |

### getOverrideTheme() {#getOverrideTheme--}
```
public final IOverrideTheme getOverrideTheme()
```

Renvoie l'objet de thème de substitution. Lecture/écriture [IOverrideTheme](../../com.aspose.slides/ioverridetheme).

**Renvoie :**  
[IOverrideTheme](../../com.aspose.slides/ioverridetheme)

### setOverrideTheme(IOverrideTheme value) {#setOverrideTheme-com.aspose.slides.IOverrideTheme-}
```
public final void setOverrideTheme(IOverrideTheme value)
```

Renvoie l'objet de thème de substitution. Lecture/écriture [IOverrideTheme](../../com.aspose.slides/ioverridetheme).

**Paramètres :**  
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [IOverrideTheme](../../com.aspose.slides/ioverridetheme) |  |

### createThemeEffective() {#createThemeEffective--}
```
public final IThemeEffectiveData createThemeEffective()
```

Renvoie l'objet de thème.

**Renvoie :**  
[IThemeEffectiveData](../../com.aspose.slides/ithemeeffectivedata)

### isOverrideThemeEnabled() {#isOverrideThemeEnabled--}
```
public final boolean isOverrideThemeEnabled()
```

Détermine si OverrideTheme remplace le thème effectif hérité ou non. Pour activer OverrideTheme pour le remplacement, utilisez les méthodes OverrideTheme.Init\*(). Pour désactiver OverrideTheme du remplacement, utilisez la méthode OverrideTheme.Clear(). Lecture seule booléen.

**Renvoie :**  
boolean

### applyColorScheme(IExtraColorScheme scheme) {#applyColorScheme-com.aspose.slides.IExtraColorScheme-}
```
public final void applyColorScheme(IExtraColorScheme scheme)
```

Applique un schéma de couleurs supplémentaire à une diapositive.

**Paramètres :**  
| Paramètre | Type | Description |
| --- | --- | --- |
| scheme | [IExtraColorScheme](../../com.aspose.slides/iextracolorscheme) | L'objet [IExtraColorScheme](../../com.aspose.slides/iextracolorscheme). |