---
title: IColorChangeEffectiveData
second_title: Referência da API Aspose.Slides for Java
description: Objeto imutável que representa um efeito de Alteração de Cor.
type: docs
url: /pt/com.aspose.slides/icolorchangeeffectivedata/
---
**Todas as Interfaces Implementadas:**
[com.aspose.slides.IEffectEffectiveData](../../com.aspose.slides/ieffecteffectivedata)
```
public interface IColorChangeEffectiveData extends IEffectEffectiveData
```

Objeto imutável que representa um efeito de Alteração de Cor. Instâncias de FromColor são substituídas por instâncias de ToColor.
## Métodos

| Método | Descrição |
| --- | --- |
| [getFromColor()](#getFromColor--) | Cor que será substituída. |
| [getToColor()](#getToColor--) | Cor que substituirá. |
| [getUseAlpha()](#getUseAlpha--) | Retorna um valor booleano que determina se o componente alfa deve ser usado. |
### getFromColor() {#getFromColor--}
```
public abstract Color getFromColor()
```


Cor que será substituída. Somente leitura java.awt.Color.

**Retorna:**
java.awt.Color
### getToColor() {#getToColor--}
```
public abstract Color getToColor()
```


Cor que substituirá. Somente leitura java.awt.Color.

**Retorna:**
java.awt.Color
### getUseAlpha() {#getUseAlpha--}
```
public abstract boolean getUseAlpha()
```


Retorna um valor booleano que determina se o componente alfa deve ser usado. Somente leitura boolean.

**Retorna:**
boolean