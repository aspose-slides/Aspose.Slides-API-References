---
title: IBaseSlide
second_title: Aspose.Slides para Android via Referência da API Java
description: Representa dados comuns para todos os tipos de slide.
type: docs
url: /pt/com.aspose.slides/ibaseslide/
---
**Todas as Interfaces Implementadas:**
[com.aspose.slides.IThemeable](../../com.aspose.slides/ithemeable)
```
public interface IBaseSlide extends IThemeable
```

Representa dados comuns para todos os tipos de slide.
## Métodos

| Método | Descrição |
| --- | --- |
| [getShapes()](#getShapes--) | Returns the shapes of a slide. |
| [getControls()](#getControls--) | Returns the collection of ActiveX controls on a slide. |
| [getName()](#getName--) | Returns or sets the name of a slide. |
| [setName(String value)](#setName-java.lang.String-) | Returns or sets the name of a slide. |
| [getSlideId()](#getSlideId--) | Returns the ID of a slide. |
| [getCustomData()](#getCustomData--) | Returns the slide's custom data. |
| [getTimeline()](#getTimeline--) | Returns animation timeline object. |
| [getSlideShowTransition()](#getSlideShowTransition--) | Returns the TransitionEx object which contains information about how the specified slide advances during a slide show. |
| [getBackground()](#getBackground--) | Returns slide's background. |
| [getHyperlinkQueries()](#getHyperlinkQueries--) | Provides easy access to contained hyperlinks. |
| [getShowMasterShapes()](#getShowMasterShapes--) | Specifies if shapes on the master slide should be shown on slides or not. |
| [setShowMasterShapes(boolean value)](#setShowMasterShapes-boolean-) | Specifies if shapes on the master slide should be shown on slides or not. |
| [findShapeByAltText(String altText)](#findShapeByAltText-java.lang.String-) | Finds first occurrence of a shape with the specified alternative text. |
| [joinPortionsWithSameFormatting()](#joinPortionsWithSameFormatting--) | Joins runs with same formatting in all paragraphs in all acceptable shapes. |
| [equals(IBaseSlide slide)](#equals-com.aspose.slides.IBaseSlide-) | Determines whether the two IBaseSlide instances are equal. |
### getShapes() {#getShapes--}
```
public abstract IShapeCollection getShapes()
```

Retorna as formas de um slide. Somente leitura [IShapeCollection](../../com.aspose.slides/ishapecollection).

**Retorna:**
[IShapeCollection](../../com.aspose.slides/ishapecollection)
### getControls() {#getControls--}
```
public abstract IControlCollection getControls()
```

Retorna a coleção de controles ActiveX em um slide. Somente leitura [IControlCollection](../../com.aspose.slides/icontrolcollection).

**Retorna:**
[IControlCollection](../../com.aspose.slides/icontrolcollection)
### getName() {#getName--}
```
public abstract String getName()
```

Retorna ou define o nome de um slide. Leitura/gravação String.

**Retorna:**
java.lang.String
### setName(String value) {#setName-java.lang.String-}
```
public abstract void setName(String value)
```

Retorna ou define o nome de um slide. Leitura/gravação String.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | java.lang.String |  |
### getSlideId() {#getSlideId--}
```
public abstract long getSlideId()
```

Retorna o ID de um slide. Somente leitura long.

**Retorna:**
long
### getCustomData() {#getCustomData--}
```
public abstract ICustomData getCustomData()
```

Retorna os dados personalizados do slide. Somente leitura [ICustomData](../../com.aspose.slides/icustomdata).

**Retorna:**
[ICustomData](../../com.aspose.slides/icustomdata)
### getTimeline() {#getTimeline--}
```
public abstract IAnimationTimeLine getTimeline()
```

Retorna o objeto da linha do tempo de animação. Somente leitura [IAnimationTimeLine](../../com.aspose.slides/ianimationtimeline).

**Retorna:**
[IAnimationTimeLine](../../com.aspose.slides/ianimationtimeline)
### getSlideShowTransition() {#getSlideShowTransition--}
```
public abstract ISlideShowTransition getSlideShowTransition()
```

Retorna o objeto TransitionEx que contém informações sobre como o slide especificado avança durante a apresentação. Somente leitura [ISlideShowTransition](../../com.aspose.slides/islideshowtransition).

**Retorna:**
[ISlideShowTransition](../../com.aspose.slides/islideshowtransition)
### getBackground() {#getBackground--}
```
public abstract IBackground getBackground()
```

Retorna o plano de fundo do slide. Somente leitura [IBackground](../../com.aspose.slides/ibackground).

**Retorna:**
[IBackground](../../com.aspose.slides/ibackground)
### getHyperlinkQueries() {#getHyperlinkQueries--}
```
public abstract IHyperlinkQueries getHyperlinkQueries()
```

Fornece acesso fácil a hyperlinks contidos. Somente leitura [IHyperlinkQueries](../../com.aspose.slides/ihyperlinkqueries).

**Retorna:**
[IHyperlinkQueries](../../com.aspose.slides/ihyperlinkqueries)
### getShowMasterShapes() {#getShowMasterShapes--}
```
public abstract boolean getShowMasterShapes()
```

Especifica se as formas no slide mestre devem ser exibidas nos slides ou não. Para o próprio slide mestre, esta propriedade sempre retorna false. Leitura/gravação boolean.

**Retorna:**
boolean
### setShowMasterShapes(boolean value) {#setShowMasterShapes-boolean-}
```
public abstract void setShowMasterShapes(boolean value)
```

Especifica se as formas no slide mestre devem ser exibidas nos slides ou não. Para o próprio slide mestre, esta propriedade sempre retorna false. Leitura/gravação boolean.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | boolean |  |
### findShapeByAltText(String altText) {#findShapeByAltText-java.lang.String-}
```
public abstract IShape findShapeByAltText(String altText)
```

Encontra a primeira ocorrência de uma forma com o texto alternativo especificado.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| altText | java.lang.String | Texto alternativo. |

**Retorna:**
[IShape](../../com.aspose.slides/ishape) - ShapeEx objeto ou nulo.
### joinPortionsWithSameFormatting() {#joinPortionsWithSameFormatting--}
```
public abstract void joinPortionsWithSameFormatting()
```

Une sequências com a mesma formatação em todos os parágrafos em todas as formas aceitáveis.
### equals(IBaseSlide slide) {#equals-com.aspose.slides.IBaseSlide-}
```
public abstract boolean equals(IBaseSlide slide)
```

Determina se duas instâncias IBaseSlide são iguais. O valor retornado é calculado com base na estrutura do slide e no conteúdo estático. Dois slides são iguais se todas as formas, estilos, textos, animações e outras configurações, etc., forem iguais. A comparação não leva em consideração valores de identificadores únicos, por exemplo SlideId, e conteúdo dinâmico, como o valor da data atual em um marcador de posição de data.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| slide | [IBaseSlide](../../com.aspose.slides/ibaseslide) | O IBaseSlide para comparar com o IBaseSlide atual. |

**Retorna:**
boolean - **true** se o IBaseSlide especificado for igual ao IBaseSlide atual; caso contrário, **false**.