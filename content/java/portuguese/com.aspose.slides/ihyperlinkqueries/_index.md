---
title: IHyperlinkQueries
second_title: Aspose.Slides for Java API Reference
description: Fornece acesso fácil aos hyperlinks contidos.
type: docs
url: /pt/com.aspose.slides/ihyperlinkqueries/
---```
public interface IHyperlinkQueries
```

Fornece acesso fácil aos hyperlinks contidos.
## Métodos

| Método | Descrição |
| --- | --- |
| [getHyperlinkClicks()](#getHyperlinkClicks--) | Obtém todos os subobjetos IHyperlinkContainer que contêm HyperlinkClick não nulo. |
| [getHyperlinkMouseOvers()](#getHyperlinkMouseOvers--) | Obtém todos os subobjetos IHyperlinkContainer que contêm HyperlinkMouseOver não nulo. |
| [getAnyHyperlinks()](#getAnyHyperlinks--) | Obtém todos os subobjetos IHyperlinkContainer que contêm HyperlinkMouseOver não nulo. |
| [removeAllHyperlinks()](#removeAllHyperlinks--) | Remove todos os hyperlinks HyperlinkClick e HyperlinkMouseOver contidos (em todos os subobjetos IHyperlinkContainer). |
### getHyperlinkClicks() {#getHyperlinkClicks--}
```
public abstract System.Collections.Generic.IGenericList<IHyperlinkContainer> getHyperlinkClicks()
```


Obtém todos os subobjetos IHyperlinkContainer que contêm HyperlinkClick não nulo. Com o objeto IHyperlinkContainer fornecido, você pode gerenciar seu hyperlink (ler, atualizar ou remover). Consulte a interface IHyperlinkContainer.

**Retorna:**
com.aspose.ms.System.Collections.Generic.IGenericList<com.aspose.slides.IHyperlinkContainer> - All IHyperlinkContainer subobjects that contain not null HyperlinkClick
### getHyperlinkMouseOvers() {#getHyperlinkMouseOvers--}
```
public abstract System.Collections.Generic.IGenericList<IHyperlinkContainer> getHyperlinkMouseOvers()
```


Obtém todos os subobjetos IHyperlinkContainer que contêm HyperlinkMouseOver não nulo. Com o objeto IHyperlinkContainer fornecido, você pode gerenciar seu hyperlink (ler, atualizar ou remover). Consulte a interface IHyperlinkContainer.

**Retorna:**
com.aspose.ms.System.Collections.Generic.IGenericList<com.aspose.slides.IHyperlinkContainer> - All IHyperlinkContainer subobjects that contain not null HyperlinkMouseOver
### getAnyHyperlinks() {#getAnyHyperlinks--}
```
public abstract System.Collections.Generic.IGenericList<IHyperlinkContainer> getAnyHyperlinks()
```


Obtém todos os subobjetos IHyperlinkContainer que contêm HyperlinkMouseOver não nulo. Com o objeto IHyperlinkContainer fornecido, você pode gerenciar seu hyperlink (ler, atualizar ou remover). Consulte a interface IHyperlinkContainer.

**Retorna:**
com.aspose.ms.System.Collections.Generic.IGenericList<com.aspose.slides.IHyperlinkContainer> - All IHyperlinkContainer subobjects that contain not null HyperlinkMouseOver
### removeAllHyperlinks() {#removeAllHyperlinks--}
```
public abstract void removeAllHyperlinks()
```


Remove todos os hyperlinks HyperlinkClick e HyperlinkMouseOver contidos (em todos os subobjetos IHyperlinkContainer).