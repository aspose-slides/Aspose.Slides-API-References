---
title: IFontSources
second_title: Aspose.Slides for Android via Java API Reference
description: Fornece fontes de arquivo e memória para fontes externas.
type: docs
url: /pt/com.aspose.slides/ifontsources/
---```
public interface IFontSources
```

Fornece fontes de arquivo e memória para fontes externas.
## Métodos

| Método | Descrição |
| --- | --- |
| [getFontFolders()](#getFontFolders--) | Pastas que contêm arquivos de fontes. |
| [setFontFolders(String[] value)](#setFontFolders-java.lang.String---) | Pastas que contêm arquivos de fontes. |
| [getMemoryFonts()](#getMemoryFonts--) | Uma coleção de fontes representadas como arrays de bytes. |
| [setMemoryFonts(byte[][] value)](#setMemoryFonts-byte-----) | Uma coleção de fontes representadas como arrays de bytes. |
### getFontFolders() {#getFontFolders--}
```
public abstract String[] getFontFolders()
```

Pastas que contêm arquivos de fontes. Todos os arquivos de fontes localizados nessas pastas são incluídos na coleção. Pastas que são pesquisadas recursivamente.

**Retorna:**
java.lang.String[]
### setFontFolders(String[] value) {#setFontFolders-java.lang.String---}
```
public abstract void setFontFolders(String[] value)
```

Pastas que contêm arquivos de fontes. Todos os arquivos de fontes localizados nessas pastas são incluídos na coleção. Pastas que são pesquisadas recursivamente.

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