---
title: FontsLoader
second_title: Aspose.Slides pour Android via la référence de l'API Java
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

Classe permettant de charger des polices personnalisées définies par l'utilisateur. Doit être utilisée avant de créer tout objet de présentation.
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
> L'exemple suivant montre comment charger des polices personnalisées à partir de .TTF
>  
>  String dataDir = "C:/Fonts";
>  // dossiers où rechercher des polices
>  String[] folders = new String[] { dataDir };
>  // Charge les polices du répertoire de polices personnalisées
>  FontsLoader.loadExternalFonts(folders);
>  // Effectuer un traitement et rendre la présentation/les diapositives
>  Presentation pres = new Presentation("DefaultFonts.pptx");
>  try {
>      pres.save("NewFonts_out.pptx", SaveFormat.Pptx);
>      // Effacer le cache des polices
>      FontsLoader.clearCache();
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| directories | java.lang.String[] | Directories to read additional fonts. |

### loadExternalFont(byte[] data) {#loadExternalFont-byte---}
```
public static void loadExternalFont(byte[] data)
```

Adds font from the binary data

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| data | byte[] | Font's data |

### getFontFolders() {#getFontFolders--}
```
public static String[] getFontFolders()
```

Gets font folders. Returns folders that have been added with LoadExternalFonts method as well as system font folders

**Returns:**
java.lang.String[] - array containing folder names
### clearCache() {#clearCache--}
```
public static void clearCache()


Releases all custom fonts defined by user

--------------------

Cette méthode doit vider le cache contenant les polices personnalisées définies par l'utilisateur.