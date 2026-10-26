---
title: FontSources
second_title: Aspose.Slides para Android via Referência da API Java
description: Fornece fontes externas a partir de arquivos e memória.
type: docs
url: /pt/com.aspose.slides/fontsources/
---
**Herança:**
java.lang.Object

**Todas as interfaces implementadas:**
[com.aspose.slides.IFontSources](../../com.aspose.slides/ifontsources)
```
public class FontSources implements IFontSources
```

Fornece fontes externas a partir de arquivos e memória.
## Construtores

| Construtor | Descrição |
| --- | --- |
| [FontSources()](#FontSources--) | Cria novas opções de fonte padrão. |
## Métodos

| Método | Descrição |
| --- | --- |
| [getFontFolders()](#getFontFolders--) | Pastas contendo arquivos de fonte. |
| [setFontFolders(String[] value)](#setFontFolders-java.lang.String---) | Pastas contendo arquivos de fonte. |
| [getMemoryFonts()](#getMemoryFonts--) | Uma coleção de fontes representada como arrays de bytes. |
| [setMemoryFonts(byte[][] value)](#setMemoryFonts-byte-----) | Uma coleção de fontes representada como arrays de bytes. |
### FontSources() {#FontSources--}
```
public FontSources()
```

Cria novas opções de fonte padrão.

### getFontFolders() {#getFontFolders--}
```
public final String[] getFontFolders()
```

Pastas contendo arquivos de fonte. Todos os arquivos de fonte localizados nessas pastas são incluídos na coleção. Pastas que são pesquisadas recursivamente.

**Retorna:**
java.lang.String[]
### setFontFolders(String[] value) {#setFontFolders-java.lang.String---}
```
public final void setFontFolders(String[] value)
```

Pastas contendo arquivos de fonte. Todos os arquivos de fonte localizados nessas pastas são incluídos na coleção. Pastas que são pesquisadas recursivamente.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | java.lang.String[] |  |

### getMemoryFonts() {#getMemoryFonts--}
```
public final byte[][] getMemoryFonts()
```

Uma coleção de fontes representada como arrays de bytes.

**Retorna:**
byte[][]
### setMemoryFonts(byte[][] value) {#setMemoryFonts-byte-----}
```
public final void setMemoryFonts(byte[][] value)
```

Uma coleção de fontes representada como arrays de bytes.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | byte[][] |  |