---
title: IPortionFormatEffectiveData
second_title: Referência da API Aspose.Slides para Java
description: Objeto imutável que contém propriedades de formatação de porção de texto efetiva.
type: docs
url: /pt/com.aspose.slides/iportionformateffectivedata/
---
**Todas as interfaces implementadas:**
[com.aspose.slides.IBasePortionFormatEffectiveData](../../com.aspose.slides/ibaseportionformateffectivedata)
```
public interface IPortionFormatEffectiveData extends IBasePortionFormatEffectiveData
```

Objeto imutável que contém propriedades de formatação de porção de texto efetiva.

--------------------

Esta interface é usada juntamente com a interface [IPortionFormat](../../com.aspose.slides/iportionformat) para retornar valores de formatação efetiva com herança aplicada.
## Métodos

| Método | Descrição |
| --- | --- |
| [getBookmarkId()](#getBookmarkId--) | Retorna o identificador do marcador. |
| [getHyperlinkClick()](#getHyperlinkClick--) | Retorna o hyperlink definido para clique do mouse. |
| [getHyperlinkMouseOver()](#getHyperlinkMouseOver--) | Retorna o hyperlink definido para passagem do mouse. |
### getBookmarkId() {#getBookmarkId--}
```
public abstract String getBookmarkId()
```


Retorna o identificador do marcador. Somente leitura String.

**Retorna:**
java.lang.String
### getHyperlinkClick() {#getHyperlinkClick--}
```
public abstract IHyperlink getHyperlinkClick()
```


Retorna o hyperlink definido para clique do mouse. Somente leitura [IHyperlink](../../com.aspose.slides/ihyperlink).

**Retorna:**
[IHyperlink](../../com.aspose.slides/ihyperlink)
### getHyperlinkMouseOver() {#getHyperlinkMouseOver--}
```
public abstract IHyperlink getHyperlinkMouseOver()
```


Retorna o hyperlink definido para passagem do mouse. Somente leitura [IHyperlink](../../com.aspose.slides/ihyperlink).

**Retorna:**
[IHyperlink](../../com.aspose.slides/ihyperlink)