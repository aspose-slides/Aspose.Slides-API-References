---
title: IFontSources
second_title: Aspose.Slides for Android via Java API Reference
description: Provides file and memory sources for external fonts.
type: docs
url: /fr/com.aspose.slides/ifontsources/
---```
public interface IFontSources
```

Fournit des sources de fichiers et de mémoire pour les polices externes.
## Méthodes

| Méthode | Description |
| --- | --- |
| [getFontFolders()](#getFontFolders--) | Dossiers contenant des fichiers de police. |
| [setFontFolders(String[] value)](#setFontFolders-java.lang.String---) | Dossiers contenant des fichiers de police. |
| [getMemoryFonts()](#getMemoryFonts--) | Une collection de polices représentées sous forme de tableaux d’octets. |
| [setMemoryFonts(byte[][] value)](#setMemoryFonts-byte-----) | Une collection de polices représentées sous forme de tableaux d’octets. |
### getFontFolders() {#getFontFolders--}
```
public abstract String[] getFontFolders()
```

Dossiers contenant des fichiers de police. Tous les fichiers de police situés dans ces dossiers sont inclus dans la collection. Dossiers recherchés de manière récursive.

**Renvoie :**
java.lang.String[]
### setFontFolders(String[] value) {#setFontFolders-java.lang.String---}
```
public abstract void setFontFolders(String[] value)
```

Dossiers contenant des fichiers de police. Tous les fichiers de police situés dans ces dossiers sont inclus dans la collection. Dossiers recherchés de manière récursive.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | java.lang.String[] |  |
### getMemoryFonts() {#getMemoryFonts--}
```
public abstract byte[][] getMemoryFonts()
```

Une collection de polices représentées sous forme de tableaux d’octets.

**Renvoie :**
byte[][]
### setMemoryFonts(byte[][] value) {#setMemoryFonts-byte-----}
```
public abstract void setMemoryFonts(byte[][] value)
```

Une collection de polices représentées sous forme de tableaux d’octets.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | byte[][] |  |