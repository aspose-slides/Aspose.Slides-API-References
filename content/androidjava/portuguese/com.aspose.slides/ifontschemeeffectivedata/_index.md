---
title: IFontSchemeEffectiveData
second_title: Aspose.Slides for Android via Java API Reference
description: Objeto imutável que contém propriedades efetivas do esquema de fontes.
type: docs
url: /pt/com.aspose.slides/ifontschemeeffectivedata/
---```
public interface IFontSchemeEffectiveData
```

Objeto imutável que contém propriedades efetivas do esquema de fontes.

--------------------

Esta interface é usada como parte de [IThemeEffectiveData](../../com.aspose.slides/ithemeeffectivedata).
## Métodos

| Método | Descrição |
| --- | --- |
| [getMinor()](#getMinor--) | Retorna a coleção de fontes para a parte "body" do slide. |
| [getMajor()](#getMajor--) | Retorna a coleção de fontes para a parte "heading" do slide. |
| [getName()](#getName--) | Retorna o nome do esquema de fontes. |
### getMinor() {#getMinor--}
```
public abstract IFontsEffectiveData getMinor()
```

Retorna a coleção de fontes para a parte "body" do slide. Somente leitura [IFontsEffectiveData](../../com.aspose.slides/ifontseffectivedata).

**Retorna:**
[IFontsEffectiveData](../../com.aspose.slides/ifontseffectivedata)
### getMajor() {#getMajor--}
```
public abstract IFontsEffectiveData getMajor()
```

Retorna a coleção de fontes para a parte "heading" do slide. Somente leitura [IFontsEffectiveData](../../com.aspose.slides/ifontseffectivedata).

**Retorna:**
[IFontsEffectiveData](../../com.aspose.slides/ifontseffectivedata)
### getName() {#getName--}
```
public abstract String getName()
```

Retorna o nome do esquema de fontes. Somente leitura String.

**Retorna:**
java.lang.String