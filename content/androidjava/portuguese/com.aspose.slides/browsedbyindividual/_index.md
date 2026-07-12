---
title: BrowsedByIndividual
second_title: Aspose.Slides para Android via Referência da API Java
description: Navegado por janela individual
type: docs
url: /pt/com.aspose.slides/browsedbyindividual/
---
**Herança:**
java.lang.Object, [com.aspose.slides.SlideShowType](../../com.aspose.slides/slideshowtype)
```
public class BrowsedByIndividual extends SlideShowType
```

Navegado por indivíduo (janela)

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
## Construtores

| Construtor | Descrição |
| --- | --- |
| [BrowsedByIndividual()](#BrowsedByIndividual--) | Inicializa uma nova instância da classe BrowsedByIndividual. |
## Métodos

| Método | Descrição |
| --- | --- |
| [getShowScrollbar()](#getShowScrollbar--) | Mostrar barra de rolagem na janela |
| [setShowScrollbar(boolean value)](#setShowScrollbar-boolean-) | Mostrar barra de rolagem na janela |
### BrowsedByIndividual() {#BrowsedByIndividual--}
```
public BrowsedByIndividual()
```


Inicializa uma nova instância da classe BrowsedByIndividual.

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


Mostrar barra de rolagem na janela

**Retorna:**
boolean
### setShowScrollbar(boolean value) {#setShowScrollbar-boolean-}
```
public final void setShowScrollbar(boolean value)
```


Mostrar barra de rolagem na janela

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | boolean |  |