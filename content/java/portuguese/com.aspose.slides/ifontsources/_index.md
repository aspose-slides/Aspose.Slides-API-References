---
title: IFontSources
second_title: Aspose.Slides for Java API Reference
description: Provides file and memory sources for external fonts.
type: docs
url: /pt/com.aspose.slides/ifontsources/
---```
public interface IFontSources
```

Fornece fontes de arquivo e de memória para fontes externas.
## Métodos

| Método | Descrição |
| --- | --- |
| [getFontFolders()](#getFontFolders--) | Pastas contendo arquivos de fonte. |
| [setFontFolders(String[] value)](#setFontFolders-java.lang.String---) | Pastas contendo arquivos de fonte. |
| [getMemoryFonts()](#getMemoryFonts--) | Uma coleção de fontes representadas como arrays de bytes. |
| [setMemoryFonts(byte[][] value)](#setMemoryFonts-byte-----) | Uma coleção de fontes representadas como arrays de bytes. |
### getFontFolders() {#getFontFolders--}
```
public abstract String[] getFontFolders()
```


Pastas contendo arquivos de fonte. Todos os arquivos de fonte localizados nessas pastas são incluídos na coleção. Pastas pesquisadas recursivamente.

**Retorna:**
java.lang.String[]
### setFontFolders(String[] value) {#setFontFolders-java.lang.String---}
```
public abstract void setFontFolders(String[] value)
```


Pastas contendo arquivos de fonte. Todos os arquivos de fonte localizados nessas pastas são incluídos na coleção. Pastas pesquisadas recursivamente.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | java.lang.String[] |  |

### getMemoryFonts() {#getMemoryFonts--}
```
public abstract byte[][] getMemoryFonts()
```


Uma coleção de fontes representadas como arrays de bytes.

**Retorna:**
byte[][]
### setMemoryFonts(byte[][] value) {#setMemoryFonts-byte-----}
```
public abstract void setMemoryFonts(byte[][] value)
```


Uma coleção de fontes representadas como arrays de bytes.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | byte[][] |  |