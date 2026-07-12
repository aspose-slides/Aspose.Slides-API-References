---
title: MasterTheme
second_title: Aspose.Slides para Android via Referência da API Java
description: Representa um tema mestre.
type: docs
url: /pt/com.aspose.slides/mastertheme/
---
**Herança:**
java.lang.Object, [com.aspose.slides.Theme](../../com.aspose.slides/theme)

**Todas as Interfaces Implementadas:**
[com.aspose.slides.IMasterTheme](../../com.aspose.slides/imastertheme)
```
public final class MasterTheme extends Theme implements IMasterTheme
```

Representa um tema mestre.
## Métodos

| Método | Descrição |
| --- | --- |
| [getColorScheme()](#getColorScheme--) | Retorna o esquema de cores. |
| [getFontScheme()](#getFontScheme--) | Retorna o esquema de fontes. |
| [getFormatScheme()](#getFormatScheme--) | Retorna o esquema de formato de forma. |
| [getExtraColorSchemes()](#getExtraColorSchemes--) | Retorna a coleção de esquemas de cores adicionais. |
| [getName()](#getName--) | Retorna o nome de um tema. |
| [setName(String value)](#setName-java.lang.String-) | Retorna o nome de um tema. |
| [getVersion()](#getVersion--) |  |
### getColorScheme() {#getColorScheme--}
```
public IColorScheme getColorScheme()
```


Retorna o esquema de cores. Somente leitura [IColorScheme](../../com.aspose.slides/icolorscheme).

**Retorna:**
[IColorScheme](../../com.aspose.slides/icolorscheme)
### getFontScheme() {#getFontScheme--}
```
public IFontScheme getFontScheme()
```


Retorna o esquema de fontes. Somente leitura [IFontScheme](../../com.aspose.slides/ifontscheme).

**Retorna:**
[IFontScheme](../../com.aspose.slides/ifontscheme)
### getFormatScheme() {#getFormatScheme--}
```
public IFormatScheme getFormatScheme()
```


Retorna o esquema de formato de forma. Somente leitura [IFormatScheme](../../com.aspose.slides/iformatscheme).

**Retorna:**
[IFormatScheme](../../com.aspose.slides/iformatscheme)
### getExtraColorSchemes() {#getExtraColorSchemes--}
```
public final IExtraColorSchemeCollection getExtraColorSchemes()
```


Retorna a coleção de esquemas de cores adicionais. Esses esquemas não afetam a aparência da apresentação, podendo ser selecionados como esquema de cores principal para um slide. Somente leitura [IExtraColorSchemeCollection](../../com.aspose.slides/iextracolorschemecollection).

**Retorna:**
[IExtraColorSchemeCollection](../../com.aspose.slides/iextracolorschemecollection)
### getName() {#getName--}
```
public final String getName()
```


Retorna o nome de um tema. Leitura/gravação String.

**Retorna:**
java.lang.String
### setName(String value) {#setName-java.lang.String-}
```
public final void setName(String value)
```


Retorna o nome de um tema. Leitura/gravação String.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | java.lang.String |  |

### getVersion() {#getVersion--}
```
public long getVersion()
```


Versão. Somente leitura long.

**Retorna:**
long