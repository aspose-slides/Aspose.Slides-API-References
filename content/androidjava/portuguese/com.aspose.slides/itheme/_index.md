---
title: ITheme
second_title: Aspose.Slides para Android via Referência da API Java
description: Representa um tema.
type: docs
url: /pt/com.aspose.slides/itheme/
---
**Todas as Interfaces Implementadas:**
[com.aspose.slides.IPresentationComponent](../../com.aspose.slides/ipresentationcomponent)
```
public interface ITheme extends IPresentationComponent
```

Representa um tema.
## Métodos

| Método | Descrição |
| --- | --- |
| [getColorScheme()](#getColorScheme--) | Retorna o esquema de cores. |
| [getFontScheme()](#getFontScheme--) | Retorna o esquema de fontes. |
| [getFormatScheme()](#getFormatScheme--) | Retorna o esquema de formato de forma. |
| [getEffective()](#getEffective--) | Obtém os dados efetivos do tema com a herança aplicada. |
### getColorScheme() {#getColorScheme--}
```
public abstract IColorScheme getColorScheme()
```


Retorna o esquema de cores. Somente leitura [IColorScheme](../../com.aspose.slides/icolorscheme).

**Retorna:**
[IColorScheme](../../com.aspose.slides/icolorscheme)
### getFontScheme() {#getFontScheme--}
```
public abstract IFontScheme getFontScheme()
```


Retorna o esquema de fontes. Somente leitura [IFontScheme](../../com.aspose.slides/ifontscheme).

**Retorna:**
[IFontScheme](../../com.aspose.slides/ifontscheme)
### getFormatScheme() {#getFormatScheme--}
```
public abstract IFormatScheme getFormatScheme()
```


Retorna o esquema de formato de forma. Somente leitura [IFormatScheme](../../com.aspose.slides/iformatscheme).

**Retorna:**
[IFormatScheme](../../com.aspose.slides/iformatscheme)
### getEffective() {#getEffective--}
```
public abstract IThemeEffectiveData getEffective()
```


Obtém os dados efetivos do tema com a herança aplicada.

**Retorna:**
[IThemeEffectiveData](../../com.aspose.slides/ithemeeffectivedata) - Um [IThemeEffectiveData](../../com.aspose.slides/ithemeeffectivedata).