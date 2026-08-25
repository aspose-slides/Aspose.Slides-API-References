---
title: FontsLoader
second_title: Aspose.Sildes pour PHP via la référence API Java
description: 
type: docs

url: /fr/aspose.slides/fontsloader/
---
## FontsLoader classe

 Classe pour charger les polices personnalisées définies par l'utilisateur.
Doit être utilisée avant de créer tout objet de présentation.
 
### clearCache {#clearCache}

| Nom | Description |
| --- | --- |
| clearCache () | Libère toutes les polices personnalisées définies par l'utilisateur. Cette méthode doit nettoyer le cache des polices personnalisées définies par l'utilisateur. |

 **Retour:**
void


---


### getFontFolders {#getFontFolders}

| Nom | Description |
| --- | --- |
| getFontFolders () | Obtient les dossiers de polices. Retourne les dossiers qui ont été ajoutés avec la méthode LoadExternalFonts ainsi que les dossiers de polices système |

 **Retour:**
String


---


### loadExternalFont {#loadExternalFont}

| Nom | Description |
| --- | --- |
| loadExternalFont (byte[]) | Ajoute une police à partir des données binaires |

 **Paramètres:**

| Nom | Type | Description |
| --- | --- | --- |
| data | byte[] | Données de la police |

 **Retour:**
void


---


### loadExternalFonts {#loadExternalFonts}

| Nom | Description |
| --- | --- |
| loadExternalFonts (java.lang.String[]) | Ajoute des dossiers supplémentaires pour rechercher des polices. |

 **Paramètres:**

| Nom | Type | Description |
| --- | --- | --- |
| directories | java.lang.String[] | Répertoires pour lire des polices supplémentaires. |

 **Retour:**
void


---