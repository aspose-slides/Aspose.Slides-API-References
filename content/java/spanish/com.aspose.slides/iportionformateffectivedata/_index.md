---
title: IPortionFormatEffectiveData
second_title: Referencia de API de Aspose.Slides para Java
description: Objeto inmutable que contiene propiedades de formato de porción de texto efectiva.
type: docs
url: /es/com.aspose.slides/iportionformateffectivedata/
---
**Todas las interfaces implementadas:**
[com.aspose.slides.IBasePortionFormatEffectiveData](../../com.aspose.slides/ibaseportionformateffectivedata)
```
public interface IPortionFormatEffectiveData extends IBasePortionFormatEffectiveData
```

Objeto inmutable que contiene propiedades de formato de porción de texto efectiva.

--------------------

Esta interfaz se usa junto con la interfaz [IPortionFormat](../../com.aspose.slides/iportionformat) para devolver valores de formato efectivos con herencia aplicada.
## Métodos

| Método | Descripción |
| --- | --- |
| [getBookmarkId()](#getBookmarkId--) | Devuelve el identificador del marcador. |
| [getHyperlinkClick()](#getHyperlinkClick--) | Devuelve el hipervínculo definido para clic del ratón. |
| [getHyperlinkMouseOver()](#getHyperlinkMouseOver--) | Devuelve el hipervínculo definido para pasar el ratón. |
### getBookmarkId() {#getBookmarkId--}
```
public abstract String getBookmarkId()
```


Devuelve el identificador del marcador. Solo lectura String.

**Devuelve:**
java.lang.String
### getHyperlinkClick() {#getHyperlinkClick--}
```
public abstract IHyperlink getHyperlinkClick()
```


Devuelve el hipervínculo definido para clic del ratón. Solo lectura [IHyperlink](../../com.aspose.slides/ihyperlink).

**Devuelve:**
[IHyperlink](../../com.aspose.slides/ihyperlink)
### getHyperlinkMouseOver() {#getHyperlinkMouseOver--}
```
public abstract IHyperlink getHyperlinkMouseOver()
```


Devuelve el hipervínculo definido para pasar el ratón. Solo lectura [IHyperlink](../../com.aspose.slides/ihyperlink).

**Devuelve:**
[IHyperlink](../../com.aspose.slides/ihyperlink)