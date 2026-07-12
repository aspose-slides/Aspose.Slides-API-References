---
title: IThemeEffectiveData
second_title: Aspose.Slides for Android via Java API Reference
description: Objeto imutável que contém propriedades de tema efetivas.
type: docs
url: /pt/com.aspose.slides/ithemeeffectivedata/
---```
public interface IThemeEffectiveData
```

Objeto imutável que contém propriedades de tema efetivas.

Esta interface é usada juntamente com a interface [ITheme](../../com.aspose.slides/itheme) para retornar valores de formatação efetivos com herança aplicada.
## Métodos

| Método | Descrição |
| --- | --- |
| [getColorScheme(Integer styleColor)](#getColorScheme-java.lang.Integer-) | Retorna o esquema de cores. |
| [getFontScheme()](#getFontScheme--) | Retorna o esquema de fontes. |
| [getFormatScheme()](#getFormatScheme--) | Retorna o esquema de formato de forma. |
### getColorScheme(Integer styleColor) {#getColorScheme-java.lang.Integer-}
```
public abstract IColorSchemeEffectiveData getColorScheme(Integer styleColor)
```

Retorna o esquema de cores.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| styleColor | java.lang.Integer | Color java.lang.Integer |

**Retorna:**
[IColorSchemeEffectiveData](../../com.aspose.slides/icolorschemeeffectivedata) - esquema de cores [IColorSchemeEffectiveData](../../com.aspose.slides/icolorschemeeffectivedata)
### getFontScheme() {#getFontScheme--}
```
public abstract IFontSchemeEffectiveData getFontScheme()
```

Retorna o esquema de fontes. Somente leitura [IFontSchemeEffectiveData](../../com.aspose.slides/ifontschemeeffectivedata).

**Retorna:**
[IFontSchemeEffectiveData](../../com.aspose.slides/ifontschemeeffectivedata)
### getFormatScheme() {#getFormatScheme--}
```
public abstract IFormatSchemeEffectiveData getFormatScheme()
```

Retorna o esquema de formato de forma. Somente leitura [IFormatSchemeEffectiveData](../../com.aspose.slides/iformatschemeeffectivedata).

**Retorna:**
[IFormatSchemeEffectiveData](../../com.aspose.slides/iformatschemeeffectivedata)