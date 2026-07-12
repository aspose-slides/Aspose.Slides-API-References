---
title: IHyperlink
second_title: Aspose.Slides for Android via Java API Reference
description: Representa um hyperlink.
type: docs
url: /pt/com.aspose.slides/ihyperlink/
---```
public interface IHyperlink
```

Representa um hyperlink.
## Métodos

| Método | Descrição |
| --- | --- |
| [getActionType()](#getActionType--) | Retorna o tipo da ação do HyperLinkEx. |
| [getExternalUrl()](#getExternalUrl--) | Especifica o URL externo. Se esta propriedade deixar de ser nula, então a propriedade TargetSlide se torna nula. |
| [getExternalUrlOriginal()](#getExternalUrlOriginal--) | Representa um hyperlink definido para esta porção sem levar em conta o conteúdo real da porção. |
| [getTargetSlide()](#getTargetSlide--) | Se o HyperlinkEx apontar para um slide específico, retorna esse slide. |
| [getTargetFrame()](#getTargetFrame--) | Retorna o frame dentro do frameset HTML pai para o destino do hyperlink pai quando existir. |
| [setTargetFrame(String value)](#setTargetFrame-java.lang.String-) | Retorna o frame dentro do frameset HTML pai para o destino do hyperlink pai quando existir. |
| [getTooltip()](#getTooltip--) | Retorna a string que pode ser exibida em uma interface de usuário associada ao hyperlink pai. |
| [setTooltip(String value)](#setTooltip-java.lang.String-) | Retorna a string que pode ser exibida em uma interface de usuário associada ao hyperlink pai. |
| [getHistory()](#getHistory--) | Determina se o destino do hyperlink pai deve ser adicionado a uma lista de hyperlinks visualizados quando for invocado. |
| [setHistory(boolean value)](#setHistory-boolean-) | Determina se o destino do hyperlink pai deve ser adicionado a uma lista de hyperlinks visualizados quando for invocado. |
| [getHighlightClick()](#getHighlightClick--) | Determina se o hyperlink deve ser destacado ao clicar. |
| [setHighlightClick(boolean value)](#setHighlightClick-boolean-) | Determina se o hyperlink deve ser destacado ao clicar. |
| [getStopSoundOnClick()](#getStopSoundOnClick--) | Determina se o som deve ser interrompido ao clicar no hyperlink. |
| [setStopSoundOnClick(boolean value)](#setStopSoundOnClick-boolean-) | Determina se o som deve ser interrompido ao clicar no hyperlink. |
| [getSound()](#getSound--) | Representa o som em reprodução do hyperlink. |
| [setSound(IAudio value)](#setSound-com.aspose.slides.IAudio-) | Representa o som em reprodução do hyperlink. |
| [getColorSource()](#getColorSource--) | Representa a origem da cor do hyperlink – estilos ou formato da porção. |
| [setColorSource(int value)](#setColorSource-int-) | Representa a origem da cor do hyperlink – estilos ou formato da porção. |
| [equals(IHyperlink hlink)](#equals-com.aspose.slides.IHyperlink-) | Determina se duas instâncias de Hyperlink são iguais. |

### getActionType() {#getActionType--}
```
public abstract int getActionType()
```

Retorna o tipo da ação do HyperLinkEx. Somente leitura [HyperlinkActionType](../../com.aspose.slides/hyperlinkactiontype).

**Retorna:**
int

### getExternalUrl() {#getExternalUrl--}
```
public abstract String getExternalUrl()
```

Especifica o URL externo. Se esta propriedade deixar de ser nula, então a propriedade TargetSlide se torna nula. Somente leitura String.

**Retorna:**
java.lang.String

### getExternalUrlOriginal() {#getExternalUrlOriginal--}
```
public abstract String getExternalUrlOriginal()
```

Representa um hyperlink definido para esta porção sem levar em conta o conteúdo real da porção.

--------------------

O PowerPoint se comporta de maneira específica para links e seu texto correspondente em uma porção. Ele permite criar texto para o hyperlink na forma de um URL válido, diferente do endereço real do link. Nesse caso, ao visualizar o link na janela de edição, ele será alterado para corresponder à porção de texto. Esta propriedade representa o valor original do hyperlink.

**Retorna:**
java.lang.String

### getTargetSlide() {#getTargetSlide--}
```
public abstract ISlide getTargetSlide()
```

Se o HyperlinkEx apontar para um slide específico, retorna esse slide. Se a propriedade deixar de ser nula, então a propriedade ExternalUrl se torna nula. Somente leitura [ISlide](../../com.aspose.slides/islide).

**Retorna:**
[ISlide](../../com.aspose.slides/islide)

### getTargetFrame() {#getTargetFrame--}
```
public abstract String getTargetFrame()
```

Retorna o frame dentro do frameset HTML pai para o destino do hyperlink pai quando existir. Leitura/gravação String.

**Retorna:**
java.lang.String

### setTargetFrame(String value) {#setTargetFrame-java.lang.String-}
```
public abstract void setTargetFrame(String value)
```

Retorna o frame dentro do frameset HTML pai para o destino do hyperlink pai quando existir. Leitura/gravação String.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | java.lang.String |  |

### getTooltip() {#getTooltip--}
```
public abstract String getTooltip()
```

Retorna a string que pode ser exibida em uma interface de usuário associada ao hyperlink pai. Leitura/gravação String.

**Retorna:**
java.lang.String

### setTooltip(String value) {#setTooltip-java.lang.String-}
```
public abstract void setTooltip(String value)
```

Retorna a string que pode ser exibida em uma interface de usuário associada ao hyperlink pai. Leitura/gravação String.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | java.lang.String |  |

### getHistory() {#getHistory--}
```
public abstract boolean getHistory()
```

Determina se o destino do hyperlink pai deve ser adicionado a uma lista de hyperlinks visualizados quando for invocado. Leitura/gravação boolean.

**Retorna:**
boolean

### setHistory(boolean value) {#setHistory-boolean-}
```
public abstract void setHistory(boolean value)
```

Determina se o destino do hyperlink pai deve ser adicionado a uma lista de hyperlinks visualizados quando for invocado. Leitura/gravação boolean.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | boolean |  |

### getHighlightClick() {#getHighlightClick--}
```
public abstract boolean getHighlightClick()
```

Determina se o hyperlink deve ser destacado ao clicar. Leitura/gravação boolean.

**Retorna:**
boolean

### setHighlightClick(boolean value) {#setHighlightClick-boolean-}
```
public abstract void setHighlightClick(boolean value)
```

Determina se o hyperlink deve ser destacado ao clicar. Leitura/gravação boolean.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | boolean |  |

### getStopSoundOnClick() {#getStopSoundOnClick--}
```
public abstract boolean getStopSoundOnClick()
```

Determina se o som deve ser interrompido ao clicar no hyperlink. Leitura/gravação boolean.

**Retorna:**
boolean

### setStopSoundOnClick(boolean value) {#setStopSoundOnClick-boolean-}
```
public abstract void setStopSoundOnClick(boolean value)
```

Determina se o som deve ser interrompido ao clicar no hyperlink. Leitura/gravação boolean.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | boolean |  |

### getSound() {#getSound--}
```
public abstract IAudio getSound()
```

Representa o som em reprodução do hyperlink. Leitura/gravação [IAudio](../../com.aspose.slides/iaudio).

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>      ISlide slide = presentation.getSlides().get_Item(0);
> 
>      // Obtém o hyperlink da primeira forma
>      IHyperlink link = presentation.getSlides().get_Item(0).getShapes().get_Item(0).getHyperlinkClick();
> 
>      if (link.getSound() != null)
>      {
>          // Extrai o som do hyperlink em array de bytes
>          byte[] audioData = link.getSound().getBinaryData();
>      }
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```

**Retorna:**
[IAudio](../../com.aspose.slides/iaudio)

### setSound(IAudio value) {#setSound-com.aspose.slides.IAudio-}
```
public abstract void setSound(IAudio value)
```

Representa o som em reprodução do hyperlink. Leitura/gravação [IAudio](../../com.aspose.slides/iaudio).

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>      ISlide slide = presentation.getSlides().get_Item(0);
> 
>      // Obtém o hyperlink da primeira forma
>      IHyperlink link = presentation.getSlides().get_Item(0).getShapes().get_Item(0).getHyperlinkClick();
> 
>      if (link.getSound() != null)
>      {
>          // Extrai o som do hyperlink em array de bytes
>          byte[] audioData = link.getSound().getBinaryData();
>      }
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```


**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | [IAudio](../../com.aspose.slides/iaudio) |  |

### getColorSource() {#getColorSource--}
```
public abstract int getColorSource()
```

Representa a origem da cor do hyperlink – estilos ou formato da porção. Leitura/gravação [HyperlinkColorSource](../../com.aspose.slides/hyperlinkcolorsource).

**Retorna:**
int

### setColorSource(int value) {#setColorSource-int-}
```
public abstract void setColorSource(int value)
```

Representa a origem da cor do hyperlink – estilos ou formato da porção. Leitura/gravação [HyperlinkColorSource](../../com.aspose.slides/hyperlinkcolorsource).

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | int |  |

### equals(IHyperlink hlink) {#equals-com.aspose.slides.IHyperlink-}
```
public abstract boolean equals(IHyperlink hlink)
```

Determina se duas instâncias de Hyperlink são iguais.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| hlink | [IHyperlink](../../com.aspose.slides/ihyperlink) | O Hyperlink a ser comparado com o Hyperlink atual. |

**Retorna:**
boolean - **true** se o Hyperlink especificado for igual ao Hyperlink atual; caso contrário, **false**.