---
title: IHyperlinkQueries
second_title: Aspose.Slides for Android via Java API Reference
description: Provide easy access to contained hyperlinks.
type: docs
url: /pt/com.aspose.slides/ihyperlinkqueries/
---```
public interface IHyperlinkQueries
```

Fornece acesso fácil a hyperlinks contidos.
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

Obtém todos os subobjetos IHyperlinkContainer que contêm HyperlinkClick não nulo. Com o objeto IHyperlinkContainer fornecido, você pode gerenciar seu hyperlink (ler, atualizar ou remover). Veja a interface IHyperlinkContainer.

**Retorna:**
com.aspose.ms.System.Collections.Generic.IGenericList<com.aspose.slides.IHyperlinkContainer> - Todos os subobjetos IHyperlinkContainer que contêm HyperlinkClick não nulo
### getHyperlinkMouseOvers() {#getHyperlinkMouseOvers--}
```
public abstract System.Collections.Generic.IGenericList<IHyperlinkContainer> getHyperlinkMouseOvers()
```

Obtém todos os subobjetos IHyperlinkContainer que contêm HyperlinkMouseOver não nulo. Com o objeto IHyperlinkContainer fornecido, você pode gerenciar seu hyperlink (ler, atualizar ou remover). Veja a interface IHyperlinkContainer.

**Retorna:**
com.aspose.ms.System.Collections.Generic.IGenericList<com.aspose.slides.IHyperlinkContainer> - Todos os subobjetos IHyperlinkContainer que contêm HyperlinkMouseOver não nulo
### getAnyHyperlinks() {#getAnyHyperlinks--}
```
public abstract System.Collections.Generic.IGenericList<IHyperlinkContainer> getAnyHyperlinks()
```

Obtém todos os subobjetos IHyperlinkContainer que contêm HyperlinkMouseOver não nulo. Com o objeto IHyperlinkContainer fornecido, você pode gerenciar seu hyperlink (ler, atualizar ou remover). Veja a interface IHyperlinkContainer.

**Retorna:**
com.aspose.ms.System.Collections.Generic.IGenericList<com.aspose.slides.IHyperlinkContainer> - Todos os subobjetos IHyperlinkContainer que contêm HyperlinkMouseOver não nulo
### removeAllHyperlinks() {#removeAllHyperlinks--}
```
public abstract void removeAllHyperlinks()
```

Remove todos os hyperlinks HyperlinkClick e HyperlinkMouseOver contidos (em todos os subobjetos IHyperlinkContainer).