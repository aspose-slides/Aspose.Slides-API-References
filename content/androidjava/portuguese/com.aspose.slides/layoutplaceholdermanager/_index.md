---
title: LayoutPlaceholderManager
second_title: Aspose.Slides para Android – Referência da API Java
description: Representa o gerenciador que permite adicionar espaços reservados ao slide de layout.
type: docs
url: /pt/com.aspose.slides/layoutplaceholdermanager/
---
**Herança:**
java.lang.Object

**Todas as Interfaces Implementadas:**
[com.aspose.slides.ILayoutPlaceholderManager](../../com.aspose.slides/ilayoutplaceholdermanager)
```
public class LayoutPlaceholderManager implements ILayoutPlaceholderManager
```

Representa o gerenciador que permite adicionar espaços reservados ao slide de layout.
## Métodos

| Método | Descrição |
| --- | --- |
| [addContentPlaceholder(float x, float y, float width, float height)](#addContentPlaceholder-float-float-float-float-) | Adiciona uma nova forma de espaço reservado ao slide de layout para armazenar conteúdo, como uma imagem, tabela, mídia ou texto. |
| [addVerticalContentPlaceholder(float x, float y, float width, float height)](#addVerticalContentPlaceholder-float-float-float-float-) | Adiciona uma nova forma de espaço reservado ao slide de layout para armazenar conteúdo, como uma imagem, tabela, mídia ou texto na direção vertical. |
| [addTextPlaceholder(float x, float y, float width, float height)](#addTextPlaceholder-float-float-float-float-) | Adiciona uma nova forma de espaço reservado ao slide de layout para armazenar conteúdo de texto. |
| [addVerticalTextPlaceholder(float x, float y, float width, float height)](#addVerticalTextPlaceholder-float-float-float-float-) | Adiciona uma nova forma de espaço reservado ao slide de layout para armazenar conteúdo de texto na direção vertical. |
| [addPicturePlaceholder(float x, float y, float width, float height)](#addPicturePlaceholder-float-float-float-float-) | Adiciona uma nova forma de espaço reservado ao slide de layout para armazenar uma imagem. |
| [addChartPlaceholder(float x, float y, float width, float height)](#addChartPlaceholder-float-float-float-float-) | Adiciona uma nova forma de espaço reservado ao slide de layout para armazenar um gráfico. |
| [addTablePlaceholder(float x, float y, float width, float height)](#addTablePlaceholder-float-float-float-float-) | Adiciona uma nova forma de espaço reservado ao slide de layout para armazenar uma tabela. |
| [addSmartArtPlaceholder(float x, float y, float width, float height)](#addSmartArtPlaceholder-float-float-float-float-) | Adiciona uma nova forma de espaço reservado ao slide de layout para armazenar um diagrama SmartArt. |
| [addMediaPlaceholder(float x, float y, float width, float height)](#addMediaPlaceholder-float-float-float-float-) | Adiciona uma nova forma de espaço reservado ao slide de layout para armazenar um objeto de mídia. |
| [addOnlineImagePlaceholder(float x, float y, float width, float height)](#addOnlineImagePlaceholder-float-float-float-float-) | Adiciona uma nova forma de espaço reservado ao slide de layout para armazenar uma imagem online. |
### addContentPlaceholder(float x, float y, float width, float height) {#addContentPlaceholder-float-float-float-float-}
```
public final IAutoShape addContentPlaceholder(float x, float y, float width, float height)
```

Adiciona uma nova forma de espaço reservado ao slide de layout para armazenar conteúdo, como uma imagem, tabela, mídia ou texto.

--------------------

> ```
> O exemplo a seguir mostra como adicionar a forma de placeholder de Conteúdo ao slide de layout.
>  Presentation pres = new Presentation();
>  try {
>      ILayoutSlide layout = pres.getLayoutSlides().getByType(SlideLayoutType.Blank);
>      IAutoShape placeholder = layout.getPlaceholderManager().addContentPlaceholder(20, 20, 500, 300);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| x | float | A coordenada X da nova forma de espaço reservado. |
| y | float | A coordenada Y da nova forma de espaço reservado. |
| width | float | A largura da nova forma de espaço reservado. |
| height | float | A altura da nova forma de espaço reservado. |

**Retorno:**
[IAutoShape](../../com.aspose.slides/iautoshape) - Criado [IAutoShape](../../com.aspose.slides/iautoshape) com um placeholder de Conteúdo.
### addVerticalContentPlaceholder(float x, float y, float width, float height) {#addVerticalContentPlaceholder-float-float-float-float-}
```
public final IAutoShape addVerticalContentPlaceholder(float x, float y, float width, float height)
```

Adiciona uma nova forma de espaço reservado ao slide de layout para armazenar conteúdo, como uma imagem, tabela, mídia ou texto na direção vertical.

--------------------

> ```
> O exemplo a seguir mostra como adicionar a forma de placeholder de Conteúdo (Vertical) ao slide de layout.
>  
>  Presentation pres = new Presentation();
>  try {
>      ILayoutSlide layout = pres.getLayoutSlides().getByType(SlideLayoutType.Blank);
>      IAutoShape placeholder = layout.getPlaceholderManager().addVerticalContentPlaceholder(20, 20, 300, 500);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| x | float | A coordenada X da nova forma de espaço reservado. |
| y | float | A coordenada Y da nova forma de espaço reservado. |
| width | float | A largura da nova forma de espaço reservado. |
| height | float | A altura da nova forma de espaço reservado. |

**Retorno:**
[IAutoShape](../../com.aspose.slides/iautoshape) - Criado [IAutoShape](../../com.aspose.slides/iautoshape) com um placeholder de Conteúdo (Vertical).
### addTextPlaceholder(float x, float y, float width, float height) {#addTextPlaceholder-float-float-float-float-}
```
public final IAutoShape addTextPlaceholder(float x, float y, float width, float height)
```

Adiciona uma nova forma de espaço reservado ao slide de layout para armazenar conteúdo de texto.

--------------------

> ```
> O exemplo a seguir mostra como adicionar a forma de placeholder de Texto ao slide de layout.
>  
>  Presentation pres = new Presentation();
>  try {
>      ILayoutSlide layout = pres.getLayoutSlides().getByType(SlideLayoutType.Blank);
>      IAutoShape placeholder = layout.getPlaceholderManager().addTextPlaceholder(20, 20, 500, 300);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| x | float | A coordenada X da nova forma de espaço reservado. |
| y | float | A coordenada Y da nova forma de espaço reservado. |
| width | float | A largura da nova forma de espaço reservado. |
| height | float | A altura da nova forma de espaço reservado. |

**Retorno:**
[IAutoShape](../../com.aspose.slides/iautoshape) - Criado [IAutoShape](../../com.aspose.slides/iautoshape) com um placeholder de Texto.
### addVerticalTextPlaceholder(float x, float y, float width, float height) {#addVerticalTextPlaceholder-float-float-float-float-}
```
public final IAutoShape addVerticalTextPlaceholder(float x, float y, float width, float height)
```

Adiciona uma nova forma de espaço reservado ao slide de layout para armazenar conteúdo de texto na direção vertical.

--------------------

> ```
> O exemplo a seguir mostra como adicionar a forma de placeholder de Texto (Vertical) ao slide de layout.
>  
>  Presentation pres = new Presentation();
>  try {
>      ILayoutSlide layout = pres.getLayoutSlides().getByType(SlideLayoutType.Blank);
>      IAutoShape placeholder = layout.getPlaceholderManager().addTextPlaceholder(20, 20, 500, 300);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| x | float | A coordenada X da nova forma de espaço reservado. |
| y | float | A coordenada Y da nova forma de espaço reservado. |
| width | float | A largura da nova forma de espaço reservado. |
| height | float | A altura da nova forma de espaço reservado. |

**Retorno:**
[IAutoShape](../../com.aspose.slides/iautoshape) - Criado [IAutoShape](../../com.aspose.slides/iautoshape) com um placeholder de Texto (Vertical).
### addPicturePlaceholder(float x, float y, float width, float height) {#addPicturePlaceholder-float-float-float-float-}
```
public final IAutoShape addPicturePlaceholder(float x, float y, float width, float height)
```

Adiciona uma nova forma de espaço reservado ao slide de layout para armazenar uma imagem.

--------------------

> ```
> O exemplo a seguir mostra como adicionar a forma de placeholder de Imagem ao slide de layout.
>  
>  Presentation pres = new Presentation();
>  try {
>      ILayoutSlide layout = pres.getLayoutSlides().getByType(SlideLayoutType.Blank);
>      IAutoShape placeholder = layout.getPlaceholderManager().addPicturePlaceholder(20, 20, 200, 200);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| x | float | A coordenada X da nova forma de espaço reservado. |
| y | float | A coordenada Y da nova forma de espaço reservado. |
| width | float | A largura da nova forma de espaço reservado. |
| height | float | A altura da nova forma de espaço reservado. |

**Retorno:**
[IAutoShape](../../com.aspose.slides/iautoshape) - Criado [IAutoShape](../../com.aspose.slides/iautoshape) com um placeholder de Imagem.
### addChartPlaceholder(float x, float y, float width, float height) {#addChartPlaceholder-float-float-float-float-}
```
public final IAutoShape addChartPlaceholder(float x, float y, float width, float height)
```

Adiciona uma nova forma de espaço reservado ao slide de layout para armazenar um gráfico.

--------------------

> ```
> O exemplo a seguir mostra como adicionar a forma de placeholder de Gráfico ao slide de layout.
>  
>  Presentation pres = new Presentation();
>  try {
>      ILayoutSlide layout = pres.getLayoutSlides().getByType(SlideLayoutType.Blank);
>      IAutoShape placeholder = layout.getPlaceholderManager().addChartPlaceholder(20, 20, 200, 200);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| x | float | A coordenada X da nova forma de espaço reservado. |
| y | float | A coordenada Y da nova forma de espaço reservado. |
| width | float | A largura da nova forma de espaço reservado. |
| height | float | A altura da nova forma de espaço reservado. |

**Retorno:**
[IAutoShape](../../com.aspose.slides/iautoshape) - Criado [IAutoShape](../../com.aspose.slides/iautoshape) com um placeholder de Gráfico.
### addTablePlaceholder(float x, float y, float width, float height) {#addTablePlaceholder-float-float-float-float-}
```
public final IAutoShape addTablePlaceholder(float x, float y, float width, float height)
```

Adiciona uma nova forma de espaço reservado ao slide de layout para armazenar uma tabela.

--------------------

> ```
> O exemplo a seguir mostra como adicionar a forma de placeholder de Tabela ao slide de layout.
>  
>  Presentation pres = new Presentation();
>  try {
>      ILayoutSlide layout = pres.getLayoutSlides().getByType(SlideLayoutType.Blank);
>      IAutoShape placeholder = layout.getPlaceholderManager().addTablePlaceholder(20, 20, 500, 200);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| x | float | A coordenada X da nova forma de espaço reservado. |
| y | float | A coordenada Y da nova forma de espaço reservado. |
| width | float | A largura da nova forma de espaço reservado. |
| height | float | A altura da nova forma de espaço reservado. |

**Retorno:**
[IAutoShape](../../com.aspose.slides/iautoshape) - Criado [IAutoShape](../../com.aspose.slides/iautoshape) com um placeholder de Tabela.
### addSmartArtPlaceholder(float x, float y, float width, float height) {#addSmartArtPlaceholder-float-float-float-float-}
```
public final IAutoShape addSmartArtPlaceholder(float x, float y, float width, float height)
```

Adiciona uma nova forma de espaço reservado ao slide de layout para armazenar um diagrama SmartArt.

--------------------

> ```
> O exemplo a seguir mostra como adicionar a forma de placeholder de SmartArt ao slide de layout.
>  
>  Presentation pres = new Presentation();
>  try {
>      ILayoutSlide layout = pres.getLayoutSlides().getByType(SlideLayoutType.Blank);
>      IAutoShape placeholder = layout.getPlaceholderManager().addSmartArtPlaceholder(20, 20, 200, 200);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| x | float | A coordenada X da nova forma de espaço reservado. |
| y | float | A coordenada Y da nova forma de espaço reservado. |
| width | float | A largura da nova forma de espaço reservado. |
| height | float | A altura da nova forma de espaço reservado. |

**Retorno:**
[IAutoShape](../../com.aspose.slides/iautoshape) - Criado [IAutoShape](../../com.aspose.slides/iautoshape) com um placeholder de SmartArt.
### addMediaPlaceholder(float x, float y, float width, float height) {#addMediaPlaceholder-float-float-float-float-}
```
public final IAutoShape addMediaPlaceholder(float x, float y, float width, float height)
```

Adiciona uma nova forma de espaço reservado ao slide de layout para armazenar um objeto de mídia.

--------------------

> ```
> O exemplo a seguir mostra como adicionar a forma de placeholder de Mídia ao slide de layout.
>  
>  Presentation pres = new Presentation();
>  try {
>      ILayoutSlide layout = pres.getLayoutSlides().getByType(SlideLayoutType.Blank);
>      IAutoShape placeholder = layout.getPlaceholderManager().addMediaPlaceholder(20, 20, 200, 200);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| x | float | A coordenada X da nova forma de espaço reservado. |
| y | float | A coordenada Y da nova forma de espaço reservado. |
| width | float | A largura da nova forma de espaço reservado. |
| height | float | A altura da nova forma de espaço reservado. |

**Retorno:**
[IAutoShape](../../com.aspose.slides/iautoshape) - Criado [IAutoShape](../../com.aspose.slides/iautoshape) com um placeholder de Mídia.
### addOnlineImagePlaceholder(float x, float y, float width, float height) {#addOnlineImagePlaceholder-float-float-float-float-}
```
public final IAutoShape addOnlineImagePlaceholder(float x, float y, float width, float height)
```

Adiciona uma nova forma de espaço reservado ao slide de layout para armazenar uma imagem online.

--------------------

> ```
> O exemplo a seguir mostra como adicionar a forma de placeholder de Imagem Online ao slide de layout.
>  
>  Presentation pres = new Presentation();
>  try {
>      ILayoutSlide layout = pres.getLayoutSlides().getByType(SlideLayoutType.Blank);
>      IAutoShape placeholder = layout.getPlaceholderManager().addOnlineImagePlaceholder(20, 20, 200, 200);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| x | float | A coordenada X da nova forma de espaço reservado. |
| y | float | A coordenada Y da nova forma de espaço reservado. |
| width | float | A largura da nova forma de espaço reservado. |
| height | float | A altura da nova forma de espaço reservado. |

**Retorno:**
[IAutoShape](../../com.aspose.slides/iautoshape) - Criado [IAutoShape](../../com.aspose.slides/iautoshape) com um placeholder de Imagem Online.