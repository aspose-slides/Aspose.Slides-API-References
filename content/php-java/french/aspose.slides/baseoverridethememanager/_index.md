---
title: BaseOverrideThemeManager
second_title: Aspose.Sildes pour PHP via la référence API Java
description: 
type: docs

url: /fr/aspose.slides/baseoverridethememanager/
---
## BaseOverrideThemeManager classe

 Classe de base pour les classes qui fournissent un accès à différents types de thèmes remplacés.
 
### applyColorScheme {#applyColorScheme}

| Name | Description |
| --- | --- |
| applyColorScheme ([ExtraColorScheme](../extracolorscheme)) | Applique un schéma de couleur supplémentaire à une diapositive. |

 **Paramètres:**

| Name | Type | Description |
| --- | --- | --- |
| scheme | [ExtraColorScheme](../extracolorscheme) | L'objet IExtraColorScheme. |

 **Renvoie:**
void


---


### createThemeEffective {#createThemeEffective}

| Name | Description |
| --- | --- |
| createThemeEffective () | Renvoie l'objet thème. |

 **Renvoie:**
ThemeEffectiveData


---


### getOverrideTheme {#getOverrideTheme}

| Name | Description |
| --- | --- |
| getOverrideTheme () | Renvoie l'objet thème de substitution. Lecture/écriture IOverrideTheme. |

 **Renvoie:**
[OverrideTheme](../overridetheme)


---


### isOverrideThemeEnabled {#isOverrideThemeEnabled}

| Name | Description |
| --- | --- |
| isOverrideThemeEnabled () | Détermine si OverrideTheme remplace le thème effectif hérité ou non. Pour activer OverrideTheme pour le remplacement, utilisez les méthodes OverrideTheme.Init*(). Pour désactiver OverrideTheme du remplacement, utilisez la méthode OverrideTheme.Clear(). Booléen en lecture seule. |

 **Renvoie:**
boolean


---


### setOverrideTheme {#setOverrideTheme}

| Name | Description |
| --- | --- |
| setOverrideTheme ([OverrideTheme](../overridetheme)) | Renvoie l'objet thème de substitution. Lecture/écriture IOverrideTheme. |

 **Renvoie:**
void


---