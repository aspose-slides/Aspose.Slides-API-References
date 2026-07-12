---
title: IFontSources
second_title: Aspose.Slides for Android via Java API Reference
description: Proporciona fuentes de archivo y de memoria para fuentes externas.
type: docs
url: /es/com.aspose.slides/ifontsources/
---```
public interface IFontSources
```

Proporciona fuentes de archivo y de memoria para fuentes externas.
## Métodos

| Método | Descripción |
| --- | --- |
| [getFontFolders()](#getFontFolders--) | Carpetas que contienen archivos de fuentes. |
| [setFontFolders(String[] value)](#setFontFolders-java.lang.String---) | Carpetas que contienen archivos de fuentes. |
| [getMemoryFonts()](#getMemoryFonts--) | Una colección de fuentes representadas como matrices de bytes. |
| [setMemoryFonts(byte[][] value)](#setMemoryFonts-byte-----) | Una colección de fuentes representadas como matrices de bytes. |
### getFontFolders() {#getFontFolders--}
```
public abstract String[] getFontFolders()
```


Carpetas que contienen archivos de fuentes. Todos los archivos de fuentes ubicados en estas carpetas se incluyen en la colección. Carpetas que se buscan de forma recursiva.

**Devuelve:**
java.lang.String[]
### setFontFolders(String[] value) {#setFontFolders-java.lang.String---}
```
public abstract void setFontFolders(String[] value)
```


Carpetas que contienen archivos de fuentes. Todos los archivos de fuentes ubicados en estas carpetas se incluyen en la colección. Carpetas que se buscan de forma recursiva.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | java.lang.String[] |  |

### getMemoryFonts() {#getMemoryFonts--}
```
public abstract byte[][] getMemoryFonts()
```


Una colección de fuentes representadas como matrices de bytes.

**Devuelve:**
byte[][]
### setMemoryFonts(byte[][] value) {#setMemoryFonts-byte-----}
```
public abstract void setMemoryFonts(byte[][] value)
```


Una colección de fuentes representadas como matrices de bytes.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | byte[][] |  |