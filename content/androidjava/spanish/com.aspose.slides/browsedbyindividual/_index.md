---
title: BrowsedByIndividual
second_title: Aspose.Slides para Android mediante la referencia de API de Java
description: Ventana navegada por individuo
type: docs
url: /es/com.aspose.slides/browsedbyindividual/
---
**Herencia:**
java.lang.Object, [com.aspose.slides.SlideShowType](../../com.aspose.slides/slideshowtype)
```
public class BrowsedByIndividual extends SlideShowType
```

Navegado por individuo (ventana)

--------------------

> ```
> Presentation pres = new Presentation();
>  try {
>      pres.getSlideShowSettings().setSlideShowType(new BrowsedByIndividual());
>      pres.save("pres.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```
## Constructores

| Constructor | Descripción |
| --- | --- |
| [BrowsedByIndividual()](#BrowsedByIndividual--) | Inicializa una nueva instancia de la clase BrowsedByIndividual. |
## Métodos

| Método | Descripción |
| --- | --- |
| [getShowScrollbar()](#getShowScrollbar--) | Mostrar barra de desplazamiento en la ventana |
| [setShowScrollbar(boolean value)](#setShowScrollbar-boolean-) | Mostrar barra de desplazamiento en la ventana |
### BrowsedByIndividual() {#BrowsedByIndividual--}
```
public BrowsedByIndividual()
```


Inicializa una nueva instancia de la clase BrowsedByIndividual.

--------------------

> ```
> Presentation pres = new Presentation();
>  try {
>      pres.getSlideShowSettings().setSlideShowType(new BrowsedByIndividual());
>      pres.save("pres.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

### getShowScrollbar() {#getShowScrollbar--}
```
public final boolean getShowScrollbar()
```


Mostrar barra de desplazamiento en la ventana

**Devuelve:**
boolean
### setShowScrollbar(boolean value) {#setShowScrollbar-boolean-}
```
public final void setShowScrollbar(boolean value)
```


Mostrar barra de desplazamiento en la ventana

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | boolean |  |