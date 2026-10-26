---
title: IFontSources
second_title: Aspose.Slides for Java API Reference
description: Provides file and memory sources for external fonts.
type: docs
url: /it/com.aspose.slides/ifontsources/
---```
public interface IFontSources
```

Fornisce sorgenti di file e di memoria per i font esterni.
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getFontFolders()](#getFontFolders--) | Cartelle contenenti file di font. |
| [setFontFolders(String[] value)](#setFontFolders-java.lang.String---) | Cartelle contenenti file di font. |
| [getMemoryFonts()](#getMemoryFonts--) | Una collezione di font rappresentata come array di byte. |
| [setMemoryFonts(byte[][] value)](#setMemoryFonts-byte-----) | Una collezione di font rappresentata come array di byte. |
### getFontFolders() {#getFontFolders--}
```
public abstract String[] getFontFolders()
```

Cartelle contenenti file di font. Tutti i file di font situati in queste cartelle sono inclusi nella collezione. Cartelle che vengono cercate ricorsivamente.

**Restituisce:**
java.lang.String[]
### setFontFolders(String[] value) {#setFontFolders-java.lang.String---}
```
public abstract void setFontFolders(String[] value)
```

Cartelle contenenti file di font. Tutti i file di font situati in queste cartelle sono inclusi nella collezione. Cartelle che vengono cercate ricorsivamente.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | java.lang.String[] |  |
### getMemoryFonts() {#getMemoryFonts--}
```
public abstract byte[][] getMemoryFonts()
```

Una collezione di font rappresentata come array di byte.

**Restituisce:**
byte[][]
### setMemoryFonts(byte[][] value) {#setMemoryFonts-byte-----}
```
public abstract void setMemoryFonts(byte[][] value)
```

Una collezione di font rappresentata come array di byte.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | byte[][] |  |