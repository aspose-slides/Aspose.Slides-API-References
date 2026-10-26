---
title: IThemeEffectiveData
second_title: Aspose.Slides for Java API Reference
description: Immutable object which contains effective theme properties.
type: docs
url: /pt/com.aspose.slides/ithemeeffectivedata/
---```
public interface IThemeEffectiveData
```

Objeto imutável que contém propriedades de tema efetivas.

--------------------

Esta interface é usada junto com a interface [ITheme](../../com.aspose.slides/itheme) para retornar valores de formatação efetiva com herança aplicada.
## Métodos

| Método | Descrição |
| --- | --- |
| [getColorScheme(Color styleColor)](#getColorScheme-java.awt.Color-) | Retorna o esquema de cores. |
| [getFontScheme()](#getFontScheme--) | Retorna o esquema de fontes. |
| [getFormatScheme()](#getFormatScheme--) | Retorna o esquema de formato de forma. |
### getColorScheme(Color styleColor) {#getColorScheme-java.awt.Color-}
```
public abstract IColorSchemeEffectiveData getColorScheme(Color styleColor)
```


Retorna o esquema de cores.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| styleColor | java.awt.Color | Color java.awt.Color |

**Retorno:**
[IColorSchemeEffectiveData](../../com.aspose.slides/icolorschemeeffectivedata) - esquema de cores [IColorSchemeEffectiveData](../../com.aspose.slides/icolorschemeeffectivedata)
### getFontScheme() {#getFontScheme--}
```
public abstract IFontSchemeEffectiveData getFontScheme()
```


Retorna o esquema de fontes. Somente leitura [IFontSchemeEffectiveData](../../com.aspose.slides/ifontschemeeffectivedata).

**Retorno:**
[IFontSchemeEffectiveData](../../com.aspose.slides/ifontschemeeffectivedata)
### getFormatScheme() {#getFormatScheme--}
```
public abstract IFormatSchemeEffectiveData getFormatScheme()
```


Retorna o esquema de formato de forma. Somente leitura [IFormatSchemeEffectiveData](../../com.aspose.slides/iformatschemeeffectivedata).

**Retorno:**
[IFormatSchemeEffectiveData](../../com.aspose.slides/iformatschemeeffectivedata)