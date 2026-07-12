---
title: IHyperlinkQueries
second_title: Aspose.Slides para Android a través de la referencia de API Java
description: Proporcione un acceso fácil a los hipervínculos contenidos.
type: docs
url: /es/com.aspose.slides/ihyperlinkqueries/
---```
public interface IHyperlinkQueries
```

Proporcione un acceso fácil a los hipervínculos contenidos.
## Métodos

| Método | Descripción |
| --- | --- |
| [getHyperlinkClicks()](#getHyperlinkClicks--) | Obtenga todos los subobjetos IHyperlinkContainer que contienen un HyperlinkClick no nulo. |
| [getHyperlinkMouseOvers()](#getHyperlinkMouseOvers--) | Obtenga todos los subobjetos IHyperlinkContainer que contienen un HyperlinkMouseOver no nulo. |
| [getAnyHyperlinks()](#getAnyHyperlinks--) | Obtenga todos los subobjetos IHyperlinkContainer que contienen un HyperlinkMouseOver no nulo. |
| [removeAllHyperlinks()](#removeAllHyperlinks--) | Elimina todos los hipervínculos HyperlinkClick y HyperlinkMouseOver contenidos (en todos los subobjetos IHyperlinkContainer). |
### getHyperlinkClicks() {#getHyperlinkClicks--}
```
public abstract System.Collections.Generic.IGenericList<IHyperlinkContainer> getHyperlinkClicks()
```

Obtenga todos los subobjetos IHyperlinkContainer que contienen un HyperlinkClick no nulo. Con el objeto IHyperlinkContainer proporcionado, puede gestionar su hipervínculo (leer, actualizar o eliminar). Vea la interfaz IHyperlinkContainer.

**Devuelve:**
com.aspose.ms.System.Collections.Generic.IGenericList<com.aspose.slides.IHyperlinkContainer> - Todos los subobjetos IHyperlinkContainer que contienen un HyperlinkClick no nulo
### getHyperlinkMouseOvers() {#getHyperlinkMouseOvers--}
```
public abstract System.Collections.Generic.IGenericList<IHyperlinkContainer> getHyperlinkMouseOvers()
```

Obtenga todos los subobjetos IHyperlinkContainer que contienen un HyperlinkMouseOver no nulo. Con el objeto IHyperlinkContainer proporcionado, puede gestionar su hipervínculo (leer, actualizar o eliminar). Vea la interfaz IHyperlinkContainer.

**Devuelve:**
com.aspose.ms.System.Collections.Generic.IGenericList<com.aspose.slides.IHyperlinkContainer> - Todos los subobjetos IHyperlinkContainer que contienen un HyperlinkMouseOver no nulo
### getAnyHyperlinks() {#getAnyHyperlinks--}
```
public abstract System.Collections.Generic.IGenericList<IHyperlinkContainer> getAnyHyperlinks()
```

Obtenga todos los subobjetos IHyperlinkContainer que contienen un HyperlinkMouseOver no nulo. Con el objeto IHyperlinkContainer proporcionado, puede gestionar su hipervínculo (leer, actualizar o eliminar). Vea la interfaz IHyperlinkContainer.

**Devuelve:**
com.aspose.ms.System.Collections.Generic.IGenericList<com.aspose.slides.IHyperlinkContainer> - Todos los subobjetos IHyperlinkContainer que contienen un HyperlinkMouseOver no nulo
### removeAllHyperlinks() {#removeAllHyperlinks--}
```
public abstract void removeAllHyperlinks()
```

Elimina todos los hipervínculos HyperlinkClick y HyperlinkMouseOver contenidos (en todos los subobjetos IHyperlinkContainer).