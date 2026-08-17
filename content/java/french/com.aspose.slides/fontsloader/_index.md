---
title: FontsLoader
second_title: Référence de l'API Aspose.Slides pour Java
description: Classe permettant de charger des polices personnalisées définies par l'utilisateur.
type: docs
url: /fr/com.aspose.slides/fontsloader/
---
**Héritage:**  
java.lang.Object

**Toutes les interfaces implémentées:**  
[com.aspose.slides.IFontsLoader](../../com.aspose.slides/ifontsloader)  
```
public final class FontsLoader implements IFontsLoader
```

Classe permettant de charger des polices personnalisées définies par l'utilisateur. À utiliser avant de créer tout objet de présentation.

## Méthodes

| Méthode | Description |
| --- | --- |
| [loadExternalFonts(String[] directories)](#loadExternalFonts-java.lang.String---) | Ajoute des dossiers supplémentaires pour rechercher des polices. |
| [loadExternalFont(byte[] data)](#loadExternalFont-byte---) | Ajoute une police à partir des données binaires |
| [getFontFolders()](#getFontFolders--) | Obtient les dossiers de polices. |
| [clearCache()](#clearCache--) | Libère toutes les polices personnalisées définies par l'utilisateur |

### loadExternalFonts(String[] directories) {#loadExternalFonts-java.lang.String---}
```
public static void loadExternalFonts(String[] directories)
```

Ajoute des dossiers supplémentaires pour rechercher des polices.

--------------------

> ```
> Les exemples suivants montrent comment charger des polices personnalisées depuis un .TTF
>  
>  String dataDir = "C:/Fonts";
>  // dossiers où chercher les polices
>  String[] folders = new String[] { dataDir };
>  // Charger les polices du répertoire personnalisé
>  FontsLoader.loadExternalFonts(folders);
>  // Effectuer du travail et rendre la présentation/les diapositives
>  Presentation pres = new Presentation("DefaultFonts.pptx");
>  try {
>      pres.save("NewFonts_out.pptx", SaveFormat.Pptx);
>      // Effacer le cache des polices
>      FontsLoader.clearCache();
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Paramètres:**
| Paramètre | Type | Description |
| --- | --- | --- |
| directories | java.lang.String[] | Répertoires pour lire des polices supplémentaires. |

### loadExternalFont(byte[] data) {#loadExternalFont-byte---}
```
public static void loadExternalFont(byte[] data)
```

Ajoute une police à partir des données binaires

**Paramètres:**
| Paramètre | Type | Description |
| --- | --- | --- |
| data | byte[] | Données de la police |

### getFontFolders() {#getFontFolders--}
```
public static String[] getFontFolders()
```

Obtient les dossiers de polices. Retourne les dossiers qui ont été ajoutés avec la méthode LoadExternalFonts ainsi que les dossiers de polices système

**Retour:**
java.lang.String[] - tableau contenant les noms de dossiers

### clearCache() {#clearCache--}
```
public static void clearCache()
```

Libère toutes les polices personnalisées définies par l'utilisateur

--------------------

Cette méthode doit nettoyer le cache des polices personnalisées définies par l'utilisateur.