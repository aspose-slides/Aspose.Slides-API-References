---
title: Hyperlink
second_title: Referência da API Aspose.Slides para Java
description: Representa um hyperlink.
type: docs
url: /pt/com.aspose.slides/hyperlink/
---
**Herança:**
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject)

**Todas as Interfaces Implementadas:**
[com.aspose.slides.IHyperlink](../../com.aspose.slides/ihyperlink), com.aspose.slides.IDOMObject
```
public final class Hyperlink extends PVIObject implements IHyperlink, IDOMObject
```

Representa um hyperlink.
## Construtores

| Construtor | Descrição |
| --- | --- |
| [Hyperlink(String url)](#Hyperlink-java.lang.String-) | Cria uma instância de um hyperlink. |
| [Hyperlink(ISlide slide)](#Hyperlink-com.aspose.slides.ISlide-) | Cria uma instância de um hyperlink que aponta para um slide específico. |
| [Hyperlink(Hyperlink source, String targetFrame, String tooltip, boolean history, boolean stopSoundsOnClick, boolean highlightClick)](#Hyperlink-com.aspose.slides.Hyperlink-java.lang.String-java.lang.String-boolean-boolean-boolean-) | Cria uma instância de um hyperlink usando outro hyperlink como origem, sobrescrevendo propriedades secundárias. |
## Métodos

| Método | Descrição |
| --- | --- |
| [getVersion()](#getVersion--) |  |
| [getNoAction()](#getNoAction--) | Retorna um hyperlink especial "do nothing". |
| [getMedia()](#getMedia--) | Retorna um hyperlink especial "play mediafile". |
| [getNextSlide()](#getNextSlide--) | Retorna um hyperlink para o próximo slide. |
| [getPreviousSlide()](#getPreviousSlide--) | Retorna um hyperlink para o slide anterior. |
| [getFirstSlide()](#getFirstSlide--) | Retorna um hyperlink para o primeiro slide da apresentação. |
| [getLastSlide()](#getLastSlide--) | Retorna um hyperlink para o último slide da apresentação. |
| [getLastVievedSlide()](#getLastVievedSlide--) | Retorna um hyperlink para o último slide visualizado. |
| [getEndShow()](#getEndShow--) | Retorna um hyperlink que termina a apresentação. |
| [getActionType()](#getActionType--) | Retorna o tipo de ação do Hyperlink. |
| [getExternalUrl()](#getExternalUrl--) | Especifica a URL externa. |
| [getTargetSlide()](#getTargetSlide--) | Se o Hyperlink tem como alvo um slide específico, retorna este slide. |
| [getExternalUrlOriginal()](#getExternalUrlOriginal--) | Representa um hyperlink definido para esta porção sem considerar o conteúdo real da porção. |
| [getTargetFrame()](#getTargetFrame--) | Retorna o frame dentro do frameset HTML pai para o alvo do hyperlink pai quando existente. |
| [setTargetFrame(String value)](#setTargetFrame-java.lang.String-) | Retorna o frame dentro do frameset HTML pai para o alvo do hyperlink pai quando existente. |
| [getTooltip()](#getTooltip--) | Retorna a string que pode ser exibida em uma interface de usuário associada ao hyperlink pai. |
| [setTooltip(String value)](#setTooltip-java.lang.String-) | Retorna a string que pode ser exibida em uma interface de usuário associada ao hyperlink pai. |
| [getHistory()](#getHistory--) | Determina se o alvo do hyperlink pai deve ser adicionado a uma lista de hyperlinks visualizados quando invocado. |
| [setHistory(boolean value)](#setHistory-boolean-) | Determina se o alvo do hyperlink pai deve ser adicionado a uma lista de hyperlinks visualizados quando invocado. |
| [getHighlightClick()](#getHighlightClick--) | Determina se o hyperlink deve ser destacado ao ser clicado. |
| [setHighlightClick(boolean value)](#setHighlightClick-boolean-) | Determina se o hyperlink deve ser destacado ao ser clicado. |
| [getStopSoundOnClick()](#getStopSoundOnClick--) | Determina se o som deve ser interrompido ao clicar no hyperlink. |
| [setStopSoundOnClick(boolean value)](#setStopSoundOnClick-boolean-) | Determina se o som deve ser interrompido ao clicar no hyperlink. |
| [getSound()](#getSound--) | Representa o som em reprodução do hyperlink. |
| [setSound(IAudio value)](#setSound-com.aspose.slides.IAudio-) | Representa o som em reprodução do hyperlink. |
| [getColorSource()](#getColorSource--) | Representa a origem da cor do hyperlink - estilos ou formato da porção. |
| [setColorSource(int value)](#setColorSource-int-) | Representa a origem da cor do hyperlink - estilos ou formato da porção. |
| [equals(Object obj)](#equals-java.lang.Object-) | Determina se duas instâncias de Hyperlink são iguais. |
| [equals(IHyperlink hlink)](#equals-com.aspose.slides.IHyperlink-) | Determina se duas instâncias de Hyperlink são iguais. |
| [op_Equality(Hyperlink hlink1, Hyperlink hlink2)](#op-Equality-com.aspose.slides.Hyperlink-com.aspose.slides.Hyperlink-) | Teste dois hyperlinks para igualdade. |
| [op_Inequality(Hyperlink hlink1, Hyperlink hlink2)](#op-Inequality-com.aspose.slides.Hyperlink-com.aspose.slides.Hyperlink-) | Teste dois hyperlinks para desigualdade. |
| [hashCode()](#hashCode--) | Serve como função hash para um tipo específico, adequada para uso em algoritmos de hash e estruturas de dados como uma tabela hash. |
| [getParent_Immediate()](#getParent-Immediate--) |  |
### Hyperlink(String url) {#Hyperlink-java.lang.String-}
```
public Hyperlink(String url)
```

Cria uma instância de um hyperlink.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| url | java.lang.String | URL do Hyperlink. |

### Hyperlink(ISlide slide) {#Hyperlink-com.aspose.slides.ISlide-}
```
public Hyperlink(ISlide slide)
```

Cria uma instância de um hyperlink que aponta para um slide específico. Observação: o hyperlink criado deve ser atribuído a algum objeto da mesma apresentação, caso contrário o link será salvo como NoAction.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| slide | [ISlide](../../com.aspose.slides/islide) | Slide de destino. |

### Hyperlink(Hyperlink source, String targetFrame, String tooltip, boolean history, boolean stopSoundsOnClick, boolean highlightClick) {#Hyperlink-com.aspose.slides.Hyperlink-java.lang.String-java.lang.String-boolean-boolean-boolean-}
```
public Hyperlink(Hyperlink source, String targetFrame, String tooltip, boolean history, boolean stopSoundsOnClick, boolean highlightClick)
```

Cria uma instância de um hyperlink usando outro hyperlink como origem, sobrescrevendo propriedades secundárias.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| source | [Hyperlink](../../com.aspose.slides/hyperlink) | Hyperlink de origem |
| targetFrame | java.lang.String | Frame de destino |
| tooltip | java.lang.String | Texto da dica de ferramenta |
| history | boolean | Determina se o alvo do hyperlink pai deve ser adicionado a uma lista de hyperlinks visualizados quando invocado. |
| stopSoundsOnClick | boolean | Determina se o som deve ser interrompido ao clicar no hyperlink. |
| highlightClick | boolean | Determina se o hyperlink deve ser destacado ao ser clicado. |

### getVersion() {#getVersion--}
```
public long getVersion()
```

Versão. Somente leitura long.

**Retorna:**
long
### getNoAction() {#getNoAction--}
```
public static Hyperlink getNoAction()
```

Retorna um hyperlink especial "do nothing". Somente leitura [Hyperlink](../../com.aspose.slides/hyperlink).

**Retorna:**
[Hyperlink](../../com.aspose.slides/hyperlink)
### getMedia() {#getMedia--}
```
public static Hyperlink getMedia()
```

Retorna um hyperlink especial "play mediafile". Usado em AudioFrame e VideoFrame. Somente leitura [Hyperlink](../../com.aspose.slides/hyperlink).

**Retorna:**
[Hyperlink](../../com.aspose.slides/hyperlink)
### getNextSlide() {#getNextSlide--}
```
public static Hyperlink getNextSlide()
```

Retorna um hyperlink para o próximo slide. Somente leitura [Hyperlink](../../com.aspose.slides/hyperlink).

**Retorna:**
[Hyperlink](../../com.aspose.slides/hyperlink)
### getPreviousSlide() {#getPreviousSlide--}
```
public static Hyperlink getPreviousSlide()
```

Retorna um hyperlink para o slide anterior. Somente leitura [Hyperlink](../../com.aspose.slides/hyperlink).

**Retorna:**
[Hyperlink](../../com.aspose.slides/hyperlink)
### getFirstSlide() {#getFirstSlide--}
```
public static Hyperlink getFirstSlide()
```

Retorna um hyperlink para o primeiro slide da apresentação. Somente leitura [Hyperlink](../../com.aspose.slides/hyperlink).

**Retorna:**
[Hyperlink](../../com.aspose.slides/hyperlink)
### getLastSlide() {#getLastSlide--}
```
public static Hyperlink getLastSlide()
```

Retorna um hyperlink para o último slide da apresentação. Somente leitura [Hyperlink](../../com.aspose.slides/hyperlink).

**Retorna:**
[Hyperlink](../../com.aspose.slides/hyperlink)
### getLastVievedSlide() {#getLastVievedSlide--}
```
public static Hyperlink getLastVievedSlide()
```

Retorna um hyperlink para o último slide visualizado. Somente leitura [Hyperlink](../../com.aspose.slides/hyperlink).

**Retorna:**
[Hyperlink](../../com.aspose.slides/hyperlink)
### getEndShow() {#getEndShow--}
```
public static Hyperlink getEndShow()
```

Retorna um hyperlink que termina a apresentação. Somente leitura [Hyperlink](../../com.aspose.slides/hyperlink).

**Retorna:**
[Hyperlink](../../com.aspose.slides/hyperlink)
### getActionType() {#getActionType--}
```
public final int getActionType()
```

Retorna o tipo de ação do Hyperlink. Somente leitura [HyperlinkActionType](../../com.aspose.slides/hyperlinkactiontype).

**Retorna:**
int
### getExternalUrl() {#getExternalUrl--}
```
public final String getExternalUrl()
```

Especifica a URL externa. Somente leitura String.

**Retorna:**
java.lang.String
### getTargetSlide() {#getTargetSlide--}
```
public final ISlide getTargetSlide()
```

Se o Hyperlink tem como alvo um slide específico, retorna este slide. Somente leitura [ISlide](../../com.aspose.slides/islide).

**Retorna:**
[ISlide](../../com.aspose.slides/islide)
### getExternalUrlOriginal() {#getExternalUrlOriginal--}
```
public final String getExternalUrlOriginal()
```

Representa um hyperlink definido para esta porção sem considerar o conteúdo real da porção.

--------------------

O PowerPoint se comporta de forma específica para links e seu texto correspondente em uma porção. Ele permite criar texto para o hyperlink na forma de uma URL válida, diferente do endereço real do link. Nesse caso, ao visualizar o link na janela de edição, ele será alterado para corresponder à porção de texto. Esta propriedade representa o valor original do hyperlink.

**Retorna:**
java.lang.String
### getTargetFrame() {#getTargetFrame--}
```
public final String getTargetFrame()
```

Retorna o frame dentro do frameset HTML pai para o alvo do hyperlink pai quando existente. Leitura/gravação String.

**Retorna:**
java.lang.String
### setTargetFrame(String value) {#setTargetFrame-java.lang.String-}
```
public final void setTargetFrame(String value)
```

Retorna o frame dentro do frameset HTML pai para o alvo do hyperlink pai quando existente. Leitura/gravação String.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | java.lang.String |  |

### getTooltip() {#getTooltip--}
```
public final String getTooltip()
```

Retorna a string que pode ser exibida em uma interface de usuário associada ao hyperlink pai. Leitura/gravação String.

**Retorna:**
java.lang.String
### setTooltip(String value) {#setTooltip-java.lang.String-}
```
public final void setTooltip(String value)
```

Retorna a string que pode ser exibida em uma interface de usuário associada ao hyperlink pai. Leitura/gravação String.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | java.lang.String |  |

### getHistory() {#getHistory--}
```
public final boolean getHistory()
```

Determina se o alvo do hyperlink pai deve ser adicionado a uma lista de hyperlinks visualizados quando invocado. Leitura/gravação boolean.

**Retorna:**
boolean
### setHistory(boolean value) {#setHistory-boolean-}
```
public final void setHistory(boolean value)
```

Determina se o alvo do hyperlink pai deve ser adicionado a uma lista de hyperlinks visualizados quando invocado. Leitura/gravação boolean.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | boolean |  |

### getHighlightClick() {#getHighlightClick--}
```
public final boolean getHighlightClick()
```

Determina se o hyperlink deve ser destacado ao ser clicado. Leitura/gravação boolean.

**Retorna:**
boolean
### setHighlightClick(boolean value) {#setHighlightClick-boolean-}
```
public final void setHighlightClick(boolean value)
```

Determina se o hyperlink deve ser destacado ao ser clicado. Leitura/gravação boolean.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | boolean |  |

### getStopSoundOnClick() {#getStopSoundOnClick--}
```
public final boolean getStopSoundOnClick()
```

Determina se o som deve ser interrompido ao clicar no hyperlink. Leitura/gravação boolean.

**Retorna:**
boolean
### setStopSoundOnClick(boolean value) {#setStopSoundOnClick-boolean-}
```
public final void setStopSoundOnClick(boolean value)
```

Determina se o som deve ser interrompido ao clicar no hyperlink. Leitura/gravação boolean.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | boolean |  |

### getSound() {#getSound--}
```
public final IAudio getSound()
```

Representa o som em reprodução do hyperlink. Leitura/gravação [IAudio](../../com.aspose.slides/iaudio).

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>      ISlide slide = presentation.getSlides().get_Item(0);
> 
>      // Obtenha o hyperlink da primeira forma
>      IHyperlink link = presentation.getSlides().get_Item(0).getShapes().get_Item(0).getHyperlinkClick();
> 
>      if (link.getSound() != null)
>      {
>          // Extrair o som do hyperlink em um array de bytes
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
public final void setSound(IAudio value)
```

Representa o som em reprodução do hyperlink. Leitura/gravação [IAudio](../../com.aspose.slides/iaudio).

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>      ISlide slide = presentation.getSlides().get_Item(0);
> 
>      // Obtenha o hyperlink da primeira forma
>      IHyperlink link = presentation.getSlides().get_Item(0).getShapes().get_Item(0).getHyperlinkClick();
> 
>      if (link.getSound() != null)
>      {
>          // Extrair o som do hyperlink em um array de bytes
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
public final int getColorSource()
```

Representa a origem da cor do hyperlink - estilos ou formato da porção. Leitura/gravação [HyperlinkColorSource](../../com.aspose.slides/hyperlinkcolorsource).

**Retorna:**
int
### setColorSource(int value) {#setColorSource-int-}
```
public final void setColorSource(int value)
```

Representa a origem da cor do hyperlink - estilos ou formato da porção. Leitura/gravação [HyperlinkColorSource](../../com.aspose.slides/hyperlinkcolorsource).

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | int |  |

### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```

Determina se duas instâncias de Hyperlink são iguais.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| obj | java.lang.Object | O Hyperlink a ser comparado com o Hyperlink atual. |

**Retorna:**
boolean - **true** se o Hyperlink especificado for igual ao Hyperlink atual; caso contrário, **false**.
### equals(IHyperlink hlink) {#equals-com.aspose.slides.IHyperlink-}
```
public final boolean equals(IHyperlink hlink)
```

Determina se duas instâncias de Hyperlink são iguais.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| hlink | [IHyperlink](../../com.aspose.slides/ihyperlink) | O Hyperlink a ser comparado com o Hyperlink atual. |

**Retorna:**
boolean - **true** se o Hyperlink especificado for igual ao Hyperlink atual; caso contrário, **false**.
### op_Equality(Hyperlink hlink1, Hyperlink hlink2) {#op-Equality-com.aspose.slides.Hyperlink-com.aspose.slides.Hyperlink-}
```
public static boolean op_Equality(Hyperlink hlink1, Hyperlink hlink2)
```

Teste dois hyperlinks para igualdade.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| hlink1 | [Hyperlink](../../com.aspose.slides/hyperlink) | Primeiro hyperlink a ser testado. |
| hlink2 | [Hyperlink](../../com.aspose.slides/hyperlink) | Segundo hyperlink a ser testado. |

**Retorna:**
boolean - **true** se os hyperlinks forem iguais.
### op_Inequality(Hyperlink hlink1, Hyperlink hlink2) {#op-Inequality-com.aspose.slides.Hyperlink-com.aspose.slides.Hyperlink-}
```
public static boolean op_Inequality(Hyperlink hlink1, Hyperlink hlink2)
```

Teste dois hyperlinks para desigualdade.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| hlink1 | [Hyperlink](../../com.aspose.slides/hyperlink) | Primeiro hyperlink a ser testado. |
| hlink2 | [Hyperlink](../../com.aspose.slides/hyperlink) | Segundo hyperlink a ser testado. |

**Retorna:**
boolean - **false** se os hyperlinks forem iguais.
### hashCode() {#hashCode--}
```
public int hashCode()
```

Serve como função hash para um tipo específico, adequada para uso em algoritmos de hash e estruturas de dados como uma tabela hash.

**Retorna:**
int - Código hash para uma URL.
### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```

Retorna o objeto Parent_Immediate. Somente leitura IDOMObject.

**Retorna:**
com.aspose.slides.IDOMObject