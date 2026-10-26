---
title: FontSources
second_title: Aspose.Slides para Android a través de la referencia API Java
description: Proporciona fuentes de archivo y memoria para fuentes externas.
type: docs
url: /es/com.aspose.slides/fontsources/
---
**Herencia:**
java.lang.Object

**Todas las interfaces implementadas:**
[com.aspose.slides.IFontSources](../../com.aspose.slides/ifontsources)
```
public class FontSources implements IFontSources
```

Proporciona fuentes de archivo y memoria para fuentes externas.
## Constructores

| Constructor | Descripción |
| --- | --- |
| [FontSources()](#FontSources--) | Crea nuevas opciones de fuente predeterminadas. |
## Métodos

| Método | Descripción |
| --- | --- |
| [getFontFolders()](#getFontFolders--) | Carpetas que contienen archivos de fuentes. |
| [setFontFolders(String[] value)](#setFontFolders-java.lang.String---) | Carpetas que contienen archivos de fuentes. |
| [getMemoryFonts()](#getMemoryFonts--) | Una colección de fuentes representadas como matrices de bytes. |
| [setMemoryFonts(byte[][] value)](#setMemoryFonts-byte-----) | Una colección de fuentes representadas como matrices de bytes. |
### FontSources() {#FontSources--}
```
public FontSources()
```


Crea nuevas opciones de fuente predeterminadas.

### getFontFolders() {#getFontFolders--}
```
public final String[] getFontFolders()
```


Carpetas que contienen archivos de fuentes. Todos los archivos de fuentes ubicados en estas carpetas se incluyen en la colección. Carpetas que se buscan de forma recursiva.

**Devuelve:**
java.lang.String[]
### setFontFolders(String[] value) {#setFontFolders-java.lang.String---}
```
public final void setFontFolders(String[] value)
```


Carpetas que contienen archivos de fuentes. Todos los archivos de fuentes ubicados en estas carpetas se incluyen en la colección. Carpetas que se buscan de forma recursiva.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | java.lang.String[] |  |

### getMemoryFonts() {#getMemoryFonts--}
```
public final byte[][] getMemoryFonts()
```


Una colección de fuentes representadas como matrices de bytes.

**Devuelve:**
byte[][]
### setMemoryFonts(byte[][] value) {#setMemoryFonts-byte-----}
```
public final void setMemoryFonts(byte[][] value)
```


Una colección de fuentes representadas como matrices de bytes.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | byte[][] |  |