---
title: CommonSlideViewProperties
second_title: Aspose.Slides para Android via Referência da API Java
description: Representa propriedades comuns de visualização de slide.
type: docs
url: /pt/com.aspose.slides/commonslideviewproperties/
---
**Herança:**
java.lang.Object

**Todas as Interfaces Implementadas:**
[com.aspose.slides.ICommonSlideViewProperties](../../com.aspose.slides/icommonslideviewproperties)
```
public class CommonSlideViewProperties implements ICommonSlideViewProperties
```

Representa propriedades de visualização de slide comuns.

--------------------

> ```
> The following example shows how to set the zoom value for slide of PowerPoint Presentation.
>  
>  // Instancia um objeto Presentation que representa um arquivo de apresentação
>  Presentation pres = new Presentation("demo.pptx");
>  try {
>      // Definindo as Propriedades de Visualização da Apresentação
>      pres.getViewProperties().getSlideViewProperties().setScale(100); // Valor de zoom em porcentagem para a visualização do slide
>      pres.getViewProperties().getNotesViewProperties().setScale(100); // Valor de zoom em porcentagem para a visualização de notas
>      pres.save("Zoom_out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```
## Métodos

| Método | Descrição |
| --- | --- |
| [getScale()](#getScale--) | Especifica a proporção de escala da visualização em porcentagens. |
| [setScale(int value)](#setScale-int-) | Especifica a proporção de escala da visualização em porcentagens. |
| [getVariableScale()](#getVariableScale--) | Especifica que o conteúdo da visualização deve ser dimensionado automaticamente para se ajustar ao tamanho da janela atual. |
| [setVariableScale(boolean value)](#setVariableScale-boolean-) | Especifica que o conteúdo da visualização deve ser dimensionado automaticamente para se ajustar ao tamanho da janela atual. |
| [getDrawingGuides()](#getDrawingGuides--) | Retorna a coleção de guias de desenho. |
### getScale() {#getScale--}
```
public final int getScale()
```


Especifica a proporção de escala da visualização em porcentagens. Leitura/Gravação int.

**Retorna:**
int
### setScale(int value) {#setScale-int-}
```
public final void setScale(int value)
```


Especifica a proporção de escala da visualização em porcentagens. Leitura/Gravação int.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | int |  |

### getVariableScale() {#getVariableScale--}
```
public final boolean getVariableScale()
```


Especifica que o conteúdo da visualização deve ser dimensionado automaticamente para se ajustar ao tamanho da janela atual. Leitura/Gravação boolean.

**Retorna:**
boolean
### setVariableScale(boolean value) {#setVariableScale-boolean-}
```
public final void setVariableScale(boolean value)
```


Especifica que o conteúdo da visualização deve ser dimensionado automaticamente para se ajustar ao tamanho da janela atual. Leitura/Gravação boolean.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | boolean |  |

### getDrawingGuides() {#getDrawingGuides--}
```
public final IDrawingGuidesCollection getDrawingGuides()
```


Retorna a coleção de guias de desenho. Somente leitura [IDrawingGuidesCollection](../../com.aspose.slides/idrawingguidescollection)

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
>      guides.add(Orientation.Vertical, (float)(slideSize.getWidth()) / 2 + 12.5f);
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