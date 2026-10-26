---
title: ICommonSlideViewProperties
second_title: Aspose.Slides for Android via Java API Reference
description: Representa propriedades comuns de visualização de slides.
type: docs
url: /pt/com.aspose.slides/icommonslideviewproperties/
---```
public interface ICommonSlideViewProperties
```

Representa propriedades comuns de visualização de slides.
## Métodos

| Método | Descrição |
| --- | --- |
| [getScale()](#getScale--) | Especifica a proporção de escala da visualização em porcentagens. |
| [setScale(int value)](#setScale-int-) | Especifica a proporção de escala da visualização em porcentagens. |
| [getVariableScale()](#getVariableScale--) | Especifica que o conteúdo da visualização deve ser dimensionado automaticamente para melhor se ajustar ao tamanho da janela atual. |
| [setVariableScale(boolean value)](#setVariableScale-boolean-) | Especifica que o conteúdo da visualização deve ser dimensionado automaticamente para melhor se ajustar ao tamanho da janela atual. |
| [getDrawingGuides()](#getDrawingGuides--) | Retorna a coleção dos guias de desenho. |
### getScale() {#getScale--}
```
public abstract int getScale()
```


Especifica a proporção de escala da visualização em porcentagens. Leitura/gravação int.

**Retorna:**
int
### setScale(int value) {#setScale-int-}
```
public abstract void setScale(int value)
```


Especifica a proporção de escala da visualização em porcentagens. Leitura/gravação int.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | int |  |

### getVariableScale() {#getVariableScale--}
```
public abstract boolean getVariableScale()
```


Especifica que o conteúdo da visualização deve ser dimensionado automaticamente para melhor se ajustar ao tamanho da janela atual. Leitura/gravação boolean.

**Retorna:**
boolean
### setVariableScale(boolean value) {#setVariableScale-boolean-}
```
public abstract void setVariableScale(boolean value)
```


Especifica que o conteúdo da visualização deve ser dimensionado automaticamente para melhor se ajustar ao tamanho da janela atual. Leitura/gravação boolean.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | boolean |  |

### getDrawingGuides() {#getDrawingGuides--}
```
public abstract IDrawingGuidesCollection getDrawingGuides()
```


Retorna a coleção dos guias de desenho. Somente leitura [IDrawingGuidesCollection](../../com.aspose.slides/idrawingguidescollection)

--------------------

> ```
> The following sample code shows how to add the new drawing guides in a PowerPoint presentation.
>  
>  Presentation pres = new Presentation();
>  try {
>      SizeF slideSize = pres.getSlideSize().getSize();
> 
>      IDrawingGuidesCollection guides = pres.getViewProperties().getSlideViewProperties().getDrawingGuides();
>      // Adicionando o novo guia de desenho vertical à direita do centro do slide
>      guides.add(Orientation.Vertical, (float)(slideSize.getWidth() / 2) + 12.5f);
>      // Adicionando o novo guia de desenho horizontal abaixo do centro do slide
>      guides.add(Orientation.Horizontal, (float)(slideSize.getHeight() / 2) + 12.5f);
> 
>      pres.save("DrawingGuides_out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Retorna:**
[IDrawingGuidesCollection](../../com.aspose.slides/idrawingguidescollection)