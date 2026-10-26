---
title: IFontSources
second_title: Aspose.Slides for Android via Java API Reference
description: Fornisce font esterni da file e memoria.
type: docs
url: /it/com.aspose.slides/ifontsources/
---```
public interface IFontSources
```

Fornisce font esterni da file e memoria.
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getFontFolders()](#getFontFolders--) | Cartelle contenenti file di font. |
| [setFontFolders(String[] value)](#setFontFolders-java.lang.String---) | Cartelle contenenti file di font. |
| [getMemoryFonts()](#getMemoryFonts--) | Una raccolta di font rappresentati come array di byte. |
| [setMemoryFonts(byte[][] value)](#setMemoryFonts-byte-----) | Una raccolta di font rappresentati come array di byte. |
### getFontFolders() {#getFontFolders--}
```
public abstract String[] getFontFolders()
```

Cartelle contenenti file di font. Tutti i file di font situati in queste cartelle sono inclusi nella raccolta. Cartelle ricorsivamente ricercate.

**Restituisce:**
java.lang.String[]
### setFontFolders(String[] value) {#setFontFolders-java.lang.String---}
```
public abstract void setFontFolders(String[] value)
```

Cartelle contenenti file di font. Tutti i file di font situati in queste cartelle sono inclusi nella raccolta. Cartelle ricorsivamente ricercate.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | java.lang.String[] |  |
### getMemoryFonts() {#getMemoryFonts--}
```
public abstract byte[][] getMemoryFonts()
```

Una raccolta di font rappresentati come array di byte.

**Restituisce:**
byte[][]
### setMemoryFonts(byte[][] value) {#setMemoryFonts-byte-----}
```
public abstract void setMemoryFonts(byte[][] value)
```

Una raccolta di font rappresentati come array di byte.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | byte[][] |  |