---
title: BaseSlide
second_title: Referência da API Java do Aspose.Slides para Android
description: Representa dados comuns para todos os tipos de slide.
type: docs
url: /pt/com.aspose.slides/baseslide/
---
**Herança:**
java.lang.Object

**Todas as Interfaces Implementadas:**
[com.aspose.slides.IBaseSlide](../../com.aspose.slides/ibaseslide), com.aspose.slides.IDOMObject, com.aspose.slides.IStyleColorOwner
```
public abstract class BaseSlide implements IBaseSlide, IDOMObject, IStyleColorOwner
```

Representa dados comuns para todos os tipos de slide.
## Métodos

| Método | Descrição |
| --- | --- |
| [getShapes()](#getShapes--) | Retorna as formas de um slide. |
| [getControls()](#getControls--) | Retorna a coleção de controles ActiveX em um slide. |
| [getName()](#getName--) | Retorna ou define o nome de um slide. |
| [setName(String value)](#setName-java.lang.String-) | Retorna ou define o nome de um slide. |
| [getSlideId()](#getSlideId--) | Retorna o ID de um slide. |
| [equals(IBaseSlide slide)](#equals-com.aspose.slides.IBaseSlide-) | Determina se duas instâncias de IBaseSlide são iguais. |
| [joinPortionsWithSameFormatting()](#joinPortionsWithSameFormatting--) | Mescla trechos com a mesma formatação em todos os parágrafos de todas as formas aceitáveis. |
| [joinPortionsWithSameFormatting(IShapeCollection collection)](#joinPortionsWithSameFormatting-com.aspose.slides.IShapeCollection-) | Mescla trechos com a mesma formatação em todos os parágrafos de todas as formas aceitáveis. |
| [createThemeEffective()](#createThemeEffective--) | Retorna um tema efetivo para este slide. |
| [getCustomData()](#getCustomData--) | Retorna os dados personalizados do slide. |
| [getTimeline()](#getTimeline--) | Retorna o objeto da linha do tempo de animação. |
| [getSlideShowTransition()](#getSlideShowTransition--) | Retorna o objeto Transition que contém informações sobre como o slide especificado avança durante uma apresentação. |
| [getBackground()](#getBackground--) | Retorna o plano de fundo do slide. |
| [getHyperlinkQueries()](#getHyperlinkQueries--) | Fornece fácil acesso aos hyperlinks contidos. |
| [getShowMasterShapes()](#getShowMasterShapes--) | Especifica se as formas no slide mestre devem ser exibidas nos slides ou não. |
| [setShowMasterShapes(boolean value)](#setShowMasterShapes-boolean-) | Especifica se as formas no slide mestre devem ser exibidas nos slides ou não. |
| [findShapeByAltText(String altText)](#findShapeByAltText-java.lang.String-) | Encontra a primeira ocorrência de uma forma com o texto alternativo especificado. |
| [getParent_Immediate()](#getParent-Immediate--) |  |
| [getPresentation()](#getPresentation--) | Retorna a interface IPresentation. |
| [getSlide()](#getSlide--) |  |
### getShapes() {#getShapes--}
```
public final IShapeCollection getShapes()
```

Retorna as formas de um slide. Somente leitura [IShapeCollection](../../com.aspose.slides/ishapecollection).

**Retorna:**
[IShapeCollection](../../com.aspose.slides/ishapecollection)
### getControls() {#getControls--}
```
public final IControlCollection getControls()
```

Retorna a coleção de controles ActiveX em um slide. Somente leitura [IControlCollection](../../com.aspose.slides/icontrolcollection).

**Retorna:**
[IControlCollection](../../com.aspose.slides/icontrolcollection)
### getName() {#getName--}
```
public String getName()
```

Retorna ou define o nome de um slide. Leitura/gravação String.

**Retorna:**
java.lang.String
### setName(String value) {#setName-java.lang.String-}
```
public void setName(String value)
```

Retorna ou define o nome de um slide. Leitura/gravação String.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | java.lang.String |  |
### getSlideId() {#getSlideId--}
```
public final long getSlideId()
```

Retorna o ID de um slide. Somente leitura long.

**Retorna:**
long
### equals(IBaseSlide slide) {#equals-com.aspose.slides.IBaseSlide-}
```
public final boolean equals(IBaseSlide slide)
```

Determina se duas instâncias de IBaseSlide são iguais. O valor retornado é calculado com base na estrutura do slide e no conteúdo estático. Dois slides são iguais se todas as formas, estilos, textos, animações e outras configurações, etc., são iguais. A comparação não leva em conta valores de identificadores únicos, por exemplo SlideId, e conteúdo dinâmico, por exemplo valor de data atual em Placeholder de Data.

--------------------

> ```
> The following example shows how to compare two slides.
>  
>  Presentation presentation1 = new Presentation("AccessSlides.pptx");
>  try {
>      Presentation presentation2 = new Presentation("HelloWorld.pptx");
>      try {
>          for (int i = 0; i < presentation1.getMasters().size(); i++)
>          {
>              for (int j = 0; j < presentation2.getMasters().size(); j++)
>              {
>                  if (presentation1.getMasters().get_Item(i).equals(presentation2.getMasters().get_Item(j)))
>                      System.out.println(String.format("SomePresentation1 MasterSlide#%d is equal to SomePresentation2 MasterSlide#%d", i, j));
>              }
>          }
>      } finally {
>          if (presentation2 != null) presentation2.dispose();
>      }
>  } finally {
>      if (presentation1 != null) presentation1.dispose();
>  }
> ```


**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| slide | [IBaseSlide](../../com.aspose.slides/ibaseslide) | O IBaseSlide a ser comparado com o IBaseSlide atual. |

**Retorna:**
boolean -  **true**  se o IBaseSlide especificado for igual ao IBaseSlide atual; caso contrário,  **false** .
### joinPortionsWithSameFormatting() {#joinPortionsWithSameFormatting--}
```
public void joinPortionsWithSameFormatting()
```

Mescla trechos com a mesma formatação em todos os parágrafos de todas as formas aceitáveis.
### joinPortionsWithSameFormatting(IShapeCollection collection) {#joinPortionsWithSameFormatting-com.aspose.slides.IShapeCollection-}
```
public void joinPortionsWithSameFormatting(IShapeCollection collection)
```

Mescla trechos com a mesma formatação em todos os parágrafos de todas as formas aceitáveis.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| collection | [IShapeCollection](../../com.aspose.slides/ishapecollection) |  |
### createThemeEffective() {#createThemeEffective--}
```
public final IThemeEffectiveData createThemeEffective()
```

Retorna um tema efetivo para este slide.

**Retorna:**
[IThemeEffectiveData](../../com.aspose.slides/ithemeeffectivedata)
### getCustomData() {#getCustomData--}
```
public final ICustomData getCustomData()
```

Retorna os dados personalizados do slide. Somente leitura [ICustomData](../../com.aspose.slides/icustomdata).

**Retorna:**
[ICustomData](../../com.aspose.slides/icustomdata)
### getTimeline() {#getTimeline--}
```
public final IAnimationTimeLine getTimeline()
```

Retorna o objeto da linha do tempo de animação. Somente leitura [IAnimationTimeLine](../../com.aspose.slides/ianimationtimeline).

**Retorna:**
[IAnimationTimeLine](../../com.aspose.slides/ianimationtimeline)
### getSlideShowTransition() {#getSlideShowTransition--}
```
public ISlideShowTransition getSlideShowTransition()
```

Retorna o objeto Transition que contém informações sobre como o slide especificado avança durante uma apresentação. Somente leitura [ISlideShowTransition](../../com.aspose.slides/islideshowtransition).

**Retorna:**
[ISlideShowTransition](../../com.aspose.slides/islideshowtransition)
### getBackground() {#getBackground--}
```
public final IBackground getBackground()
```

Retorna o plano de fundo do slide. Somente leitura [IBackground](../../com.aspose.slides/ibackground).

**Retorna:**
[IBackground](../../com.aspose.slides/ibackground)
### getHyperlinkQueries() {#getHyperlinkQueries--}
```
public final IHyperlinkQueries getHyperlinkQueries()
```

Fornece fácil acesso aos hyperlinks contidos. Somente leitura [IHyperlinkQueries](../../com.aspose.slides/ihyperlinkqueries).

**Retorna:**
[IHyperlinkQueries](../../com.aspose.slides/ihyperlinkqueries)
### getShowMasterShapes() {#getShowMasterShapes--}
```
public abstract boolean getShowMasterShapes()
```

Especifica se as formas no slide mestre devem ser exibidas nos slides ou não. Para o próprio slide mestre esta propriedade sempre retorna false. Leitura/gravação boolean.

**Retorna:**
boolean
### setShowMasterShapes(boolean value) {#setShowMasterShapes-boolean-}
```
public abstract void setShowMasterShapes(boolean value)
```

Especifica se as formas no slide mestre devem ser exibidas nos slides ou não. Para o próprio slide mestre esta propriedade sempre retorna false. Leitura/gravação boolean.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | boolean |  |
### findShapeByAltText(String altText) {#findShapeByAltText-java.lang.String-}
```
public final IShape findShapeByAltText(String altText)
```

Encontra a primeira ocorrência de uma forma com o texto alternativo especificado.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| altText | java.lang.String | Texto alternativo. |

**Retorna:**
[IShape](../../com.aspose.slides/ishape) - objeto Shape ou null.
### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```

Retorna o objeto Parent_Immediate. Somente leitura IDOMObject.

**Retorna:**
com.aspose.slides.IDOMObject
### getPresentation() {#getPresentation--}
```
public final IPresentation getPresentation()
```

Retorna a interface IPresentation. Somente leitura [IPresentation](../../com.aspose.slides/ipresentation).

**Retorna:**
[IPresentation](../../com.aspose.slides/ipresentation)
### getSlide() {#getSlide--}
```
public final IBaseSlide getSlide()
```

Retorna o slide base. Somente leitura [IBaseSlide](../../com.aspose.slides/ibaseslide).

**Retorna:**
[IBaseSlide](../../com.aspose.slides/ibaseslide)