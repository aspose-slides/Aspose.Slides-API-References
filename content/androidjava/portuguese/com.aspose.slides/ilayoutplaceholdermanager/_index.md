---
title: ILayoutPlaceholderManager
second_title: Aspose.Slides for Android via Java API Reference
description: Represents manager that allows you to add placeholders to the layout slide.
type: docs
url: /pt/com.aspose.slides/ilayoutplaceholdermanager/
---```
public interface ILayoutPlaceholderManager
```

Representa o gerenciador que permite adicionar marcadores de posição ao slide de layout.
## Métodos

| Método | Descrição |
| --- | --- |
| [addContentPlaceholder(float x, float y, float width, float height)](#addContentPlaceholder-float-float-float-float-) | Adiciona uma nova forma de marcador de posição ao slide de layout para conter conteúdo, como uma imagem, tabela, mídia ou texto. |
| [addVerticalContentPlaceholder(float x, float y, float width, float height)](#addVerticalContentPlaceholder-float-float-float-float-) | Adiciona uma nova forma de marcador de posição ao slide de layout para conter conteúdo, como uma imagem, tabela, mídia ou texto em direção vertical. |
| [addTextPlaceholder(float x, float y, float width, float height)](#addTextPlaceholder-float-float-float-float-) | Adiciona uma nova forma de marcador de posição ao slide de layout para conter conteúdo de texto. |
| [addVerticalTextPlaceholder(float x, float y, float width, float height)](#addVerticalTextPlaceholder-float-float-float-float-) | Adiciona uma nova forma de marcador de posição ao slide de layout para conter conteúdo de texto em direção vertical. |
| [addPicturePlaceholder(float x, float y, float width, float height)](#addPicturePlaceholder-float-float-float-float-) | Adiciona uma nova forma de marcador de posição ao slide de layout para conter uma imagem. |
| [addChartPlaceholder(float x, float y, float width, float height)](#addChartPlaceholder-float-float-float-float-) | Adiciona uma nova forma de marcador de posição ao slide de layout para conter um gráfico. |
| [addTablePlaceholder(float x, float y, float width, float height)](#addTablePlaceholder-float-float-float-float-) | Adiciona uma nova forma de marcador de posição ao slide de layout para conter uma tabela. |
| [addSmartArtPlaceholder(float x, float y, float width, float height)](#addSmartArtPlaceholder-float-float-float-float-) | Adiciona uma nova forma de marcador de posição ao slide de layout para conter um diagrama SmartArt. |
| [addMediaPlaceholder(float x, float y, float width, float height)](#addMediaPlaceholder-float-float-float-float-) | Adiciona uma nova forma de marcador de posição ao slide de layout para conter um objeto de mídia. |
| [addOnlineImagePlaceholder(float x, float y, float width, float height)](#addOnlineImagePlaceholder-float-float-float-float-) | Adiciona uma nova forma de marcador de posição ao slide de layout para conter uma imagem online. |
### addContentPlaceholder(float x, float y, float width, float height) {#addContentPlaceholder-float-float-float-float-}
```
public abstract IAutoShape addContentPlaceholder(float x, float y, float width, float height)
```

Adiciona uma nova forma de marcador de posição ao slide de layout para conter conteúdo, como uma imagem, tabela, mídia ou texto.

--------------------

> ```
> O exemplo a seguir mostra como adicionar a forma de marcador de posição Content ao slide de layout.
>  
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
| x | float | A coordenada X da nova forma de marcador de posição. |
| y | float | A coordenada Y da nova forma de marcador de posição. |
| width | float | A largura da nova forma de marcador de posição. |
| height | float | A altura da nova forma de marcador de posição. |

**Retorna:**
[IAutoShape](../../com.aspose.slides/iautoshape) - Criado [IAutoShape](../../com.aspose.slides/iautoshape) com um marcador de posição de Conteúdo.
### addVerticalContentPlaceholder(float x, float y, float width, float height) {#addVerticalContentPlaceholder-float-float-float-float-}
```
public abstract IAutoShape addVerticalContentPlaceholder(float x, float y, float width, float height)
```

Adiciona uma nova forma de marcador de posição ao slide de layout para conter conteúdo, como uma imagem, tabela, mídia ou texto em direção vertical.

--------------------

> ```
> O exemplo a seguir mostra como adicionar a forma de marcador de posição Content (Vertical) ao slide de layout.
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
| x | float | A coordenada X da nova forma de marcador de posição. |
| y | float | A coordenada Y da nova forma de marcador de posição. |
| width | float | A largura da nova forma de marcador de posição. |
| height | float | A altura da nova forma de marcador de posição. |

**Retorna:**
[IAutoShape](../../com.aspose.slides/iautoshape) - Criado [IAutoShape](../../com.aspose.slides/iautoshape) com um marcador de posição de Conteúdo (Vertical).
### addTextPlaceholder(float x, float y, float width, float height) {#addTextPlaceholder-float-float-float-float-}
```
public abstract IAutoShape addTextPlaceholder(float x, float y, float width, float height)
```

Adiciona uma nova forma de marcador de posição ao slide de layout para conter conteúdo de texto.

--------------------

> ```
> O exemplo a seguir mostra como adicionar a forma de marcador de posição Text ao slide de layout.
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
| x | float | A coordenada X da nova forma de marcador de posição. |
| y | float | A coordenada Y da nova forma de marcador de posição. |
| width | float | A largura da nova forma de marcador de posição. |
| height | float | A altura da nova forma de marcador de posição. |

**Retorna:**
[IAutoShape](../../com.aspose.slides/iautoshape) - Criado [IAutoShape](../../com.aspose.slides/iautoshape) com um marcador de posição de Texto.
### addVerticalTextPlaceholder(float x, float y, float width, float height) {#addVerticalTextPlaceholder-float-float-float-float-}
```
public abstract IAutoShape addVerticalTextPlaceholder(float x, float y, float width, float height)
```

Adiciona uma nova forma de marcador de posição ao slide de layout para conter conteúdo de texto em direção vertical.

--------------------

> ```
> O exemplo a seguir mostra como adicionar a forma de marcador de posição Text (Vertical) ao slide de layout.
>  
>  Presentation pres = new Presentation();
>  try {
>      ILayoutSlide layout = pres.getLayoutSlides().getByType(SlideLayoutType.Blank);
>      IAutoShape placeholder = layout.getPlaceholderManager().addVerticalTextPlaceholder(20, 20, 300, 500);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| x | float | A coordenada X da nova forma de marcador de posição. |
| y | float | A coordenada Y da nova forma de marcador de posição. |
| width | float | A largura da nova forma de marcador de posição. |
| height | float | A altura da nova forma de marcador de posição. |

**Retorna:**
[IAutoShape](../../com.aspose.slides/iautoshape) - Criado [IAutoShape](../../com.aspose.slides/iautoshape) com um marcador de posição de Texto (Vertical).
### addPicturePlaceholder(float x, float y, float width, float height) {#addPicturePlaceholder-float-float-float-float-}
```
public abstract IAutoShape addPicturePlaceholder(float x, float y, float width, float height)
```

Adiciona uma nova forma de marcador de posição ao slide de layout para conter uma imagem.

--------------------

> ```
> O exemplo a seguir mostra como adicionar a forma de marcador de posição Picture ao slide de layout.
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
| x | float | A coordenada X da nova forma de marcador de posição. |
| y | float | A coordenada Y da nova forma de marcador de posição. |
| width | float | A largura da nova forma de marcador de posição. |
| height | float | A altura da nova forma de marcador de posição. |

**Retorna:**
[IAutoShape](../../com.aspose.slides/iautoshape) - Criado [IAutoShape](../../com.aspose.slides/iautoshape) com um marcador de posição de Imagem.
### addChartPlaceholder(float x, float y, float width, float height) {#addChartPlaceholder-float-float-float-float-}
```
public abstract IAutoShape addChartPlaceholder(float x, float y, float width, float height)
```

Adiciona uma nova forma de marcador de posição ao slide de layout para conter um gráfico.

--------------------

> ```
> O exemplo a seguir mostra como adicionar a forma de marcador de posição Chart ao slide de layout.
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
| x | float | A coordenada X da nova forma de marcador de posição. |
| y | float | A coordenada Y da nova forma de marcador de posição. |
| width | float | A largura da nova forma de marcador de posição. |
| height | float | A altura da nova forma de marcador de posição. |

**Retorna:**
[IAutoShape](../../com.aspose.slides/iautoshape) - Criado [IAutoShape](../../com.aspose.slides/iautoshape) com um marcador de posição de Gráfico.
### addTablePlaceholder(float x, float y, float width, float height) {#addTablePlaceholder-float-float-float-float-}
```
public abstract IAutoShape addTablePlaceholder(float x, float y, float width, float height)
```

Adiciona uma nova forma de marcador de posição ao slide de layout para conter uma tabela.

--------------------

> ```
> O exemplo a seguir mostra como adicionar a forma de marcador de posição Table ao slide de layout.
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
| x | float | A coordenada X da nova forma de marcador de posição. |
| y | float | A coordenada Y da nova forma de marcador de posição. |
| width | float | A largura da nova forma de marcador de posição. |
| height | float | A altura da nova forma de marcador de posição. |

**Retorna:**
[IAutoShape](../../com.aspose.slides/iautoshape) - Criado [IAutoShape](../../com.aspose.slides/iautoshape) com um marcador de posição de Tabela.
### addSmartArtPlaceholder(float x, float y, float width, float height) {#addSmartArtPlaceholder-float-float-float-float-}
```
public abstract IAutoShape addSmartArtPlaceholder(float x, float y, float width, float height)
```

Adiciona uma nova forma de marcador de posição ao slide de layout para conter um diagrama SmartArt.

--------------------

> ```
> The following example shows how to add the SmartArt placeholder shape to the layout slide.
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
| x | float | A coordenada X da nova forma de marcador de posição. |
| y | float | A coordenada Y da nova forma de marcador de posição. |
| width | float | A largura da nova forma de marcador de posição. |
| height | float | A altura da nova forma de marcador de posição. |

**Retorna:**
[IAutoShape](../../com.aspose.slides/iautoshape) - Criado [IAutoShape](../../com.aspose.slides/iautoshape) com um marcador de posição de SmartArt.
### addMediaPlaceholder(float x, float y, float width, float height) {#addMediaPlaceholder-float-float-float-float-}
```
public abstract IAutoShape addMediaPlaceholder(float x, float y, float width, float height)
```

Adiciona uma nova forma de marcador de posição ao slide de layout para conter um objeto de mídia.

--------------------

> ```
> O exemplo a seguir mostra como adicionar a forma de marcador de posição Media ao slide de layout.
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
| x | float | A coordenada X da nova forma de marcador de posição. |
| y | float | A coordenada Y da nova forma de marcador de posição. |
| width | float | A largura da nova forma de marcador de posição. |
| height | float | A altura da nova forma de marcador de posição. |

**Retorna:**
[IAutoShape](../../com.aspose.slides/iautoshape) - Criado [IAutoShape](../../com.aspose.slides/iautoshape) com um marcador de posição de Mídia.
### addOnlineImagePlaceholder(float x, float y, float width, float height) {#addOnlineImagePlaceholder-float-float-float-float-}
```
public abstract IAutoShape addOnlineImagePlaceholder(float x, float y, float width, float height)
```

Adiciona uma nova forma de marcador de posição ao slide de layout para conter uma imagem online.

--------------------

> ```
> The following example shows how to add the Online Image placeholder shape to the layout slide.
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
| x | float | A coordenada X da nova forma de marcador de posição. |
| y | float | A coordenada Y da nova forma de marcador de posição. |
| width | float | A largura da nova forma de marcador de posição. |
| height | float | A altura da nova forma de marcador de posição. |

**Retorna:**
[IAutoShape](../../com.aspose.slides/iautoshape) - Criado [IAutoShape](../../com.aspose.slides/iautoshape) com um marcador de posição de Imagem Online.