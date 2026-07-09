---
title: FontSources
second_title: Référence de l'API Java Aspose.Slides pour Android
description: Fournit des sources de fichiers et de mémoire pour les polices externes.
type: docs
url: /fr/com.aspose.slides/fontsources/
---
**Héritage:** java.lang.Object

**Toutes les interfaces implémentées:**  
[com.aspose.slides.IFontSources](../../com.aspose.slides/ifontsources)
```
public class FontSources implements IFontSources
```

Fournit des sources de fichiers et de mémoire pour les polices externes.

## Constructeurs

| Constructeur | Description |
| --- | --- |
| [FontSources()](#FontSources--) | Crée de nouvelles options de police par défaut. |

## Méthodes

| Méthode | Description |
| --- | --- |
| [getFontFolders()](#getFontFolders--) | Dossiers contenant les fichiers de police. |
| [setFontFolders(String[] value)](#setFontFolders-java.lang.String---) | Dossiers contenant les fichiers de police. |
| [getMemoryFonts()](#getMemoryFonts--) | Une collection de polices représentées sous forme de tableaux d'octets. |
| [setMemoryFonts(byte[][] value)](#setMemoryFonts-byte-----) | Une collection de polices représentées sous forme de tableaux d'octets. |

### FontSources() {#FontSources--}
```
public FontSources()
```

Crée de nouvelles options de police par défaut.

### getFontFolders() {#getFontFolders--}
```
public final String[] getFontFolders()
```

Dossiers contenant les fichiers de police. Tous les fichiers de police situés dans ces dossiers sont inclus dans la collection. Dossiers recherchés de façon récursive.

**Renvoie :**  
java.lang.String[]

### setFontFolders(String[] value) {#setFontFolders-java.lang.String---}
```
public final void setFontFolders(String[] value)
```

Dossiers contenant les fichiers de police. Tous les fichiers de police situés dans ces dossiers sont inclus dans la collection. Dossiers recherchés de façon récursive.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | java.lang.String[] |  |

### getMemoryFonts() {#getMemoryFonts--}
```
public final byte[][] getMemoryFonts()
```

Une collection de polices représentées sous forme de tableaux d'octets.

**Renvoie :**  
byte[][]

### setMemoryFonts(byte[][] value) {#setMemoryFonts-byte-----}
```
public final void setMemoryFonts(byte[][] value)
```

Une collection de polices représentées sous forme de tableaux d'octets.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | byte[][] |  |