---
title: IGlobalLayoutSlideCollection
second_title: Aspose.Slides para Android via Referência da API Java
description: Representa uma coleção de todos os slides de layout em uma apresentação.
type: docs
url: /pt/com.aspose.slides/igloballayoutslidecollection/
---
**Todas as Interfaces Implementadas:**
[com.aspose.slides.ILayoutSlideCollection](../../com.aspose.slides/ilayoutslidecollection)
```
public interface IGlobalLayoutSlideCollection extends ILayoutSlideCollection
```

Representa uma coleção de todos os slides de layout em uma apresentação. Estende a interface ILayoutSlideCollection com métodos para adicionar/duplicar slides de layout no contexto da união das coleções individuais de slides de layout mestre.
## Métodos

| Método | Descrição |
| --- | --- |
| [addClone(ILayoutSlide sourceLayout)](#addClone-com.aspose.slides.ILayoutSlide-) | Adiciona uma cópia de um slide de layout especificado à apresentação. |
| [addClone(ILayoutSlide sourceLayout, IMasterSlide destMaster)](#addClone-com.aspose.slides.ILayoutSlide-com.aspose.slides.IMasterSlide-) | Adiciona uma cópia de um slide de layout especificado à apresentação. |
| [add(IMasterSlide master, byte layoutType, String layoutName)](#add-com.aspose.slides.IMasterSlide-byte-java.lang.String-) | Adiciona um novo slide de layout à apresentação. |
### addClone(ILayoutSlide sourceLayout) {#addClone-com.aspose.slides.ILayoutSlide-}
```
public abstract ILayoutSlide addClone(ILayoutSlide sourceLayout)
```

Adiciona uma cópia de um slide de layout especificado à apresentação.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| sourceLayout | [ILayoutSlide](../../com.aspose.slides/ilayoutslide) | Slide a ser duplicado. |

--------------------

Ao duplicar um layout entre diferentes apresentações, o mestre do layout também pode ser duplicado para manter a formatação original. Um registro interno é usado para rastrear mestres duplicados automaticamente a fim de impedir a criação de múltiplas cópias do mesmo slide mestre. A duplicação manual de slides mestre não será impedida nem registrada.

**Retorno:**
[ILayoutSlide](../../com.aspose.slides/ilayoutslide) - Slide adicionado.
### addClone(ILayoutSlide sourceLayout, IMasterSlide destMaster) {#addClone-com.aspose.slides.ILayoutSlide-com.aspose.slides.IMasterSlide-}
```
public abstract ILayoutSlide addClone(ILayoutSlide sourceLayout, IMasterSlide destMaster)
```

Adiciona uma cópia de um slide de layout especificado à apresentação.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| sourceLayout | [ILayoutSlide](../../com.aspose.slides/ilayoutslide) | Slide a ser duplicado. |
| destMaster | [IMasterSlide](../../com.aspose.slides/imasterslide) | Slide mestre para um novo layout. |

--------------------

O novo layout será vinculado ao mestre definido na apresentação de destino. Portanto, isto é análogo a copiar/colar com a opção "Use Destination Theme" no PowerPoint.

**Retorno:**
[ILayoutSlide](../../com.aspose.slides/ilayoutslide) - Slide adicionado.
### add(IMasterSlide master, byte layoutType, String layoutName) {#add-com.aspose.slides.IMasterSlide-byte-java.lang.String-}
```
public abstract ILayoutSlide add(IMasterSlide master, byte layoutType, String layoutName)
```

Adiciona um novo slide de layout à apresentação.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| master | [IMasterSlide](../../com.aspose.slides/imasterslide) | Slide mestre para um novo layout. |
| layoutType | byte | Tipo de layout para um novo layout. Tipos de layout suportados: Title, TitleOnly, Blank, TitleAndObject, VerticalText, VerticalTitleAndText, TwoObjects, SectionHeader, TwoTextAndTwoObjects, TitleObjectAndCaption, PictureAndCaption, Custom. Outros tipos de layout não são suportados atualmente: Text, TwoColumnText, Table, TextAndChart, ChartAndText, Diagram, Chart, TextAndClipArt, ClipArtAndText, TextAndObject, ObjectAndText, Object, TextAndMedia, MediaAndText, ObjectOverText, TextOverObject, TextAndTwoObjects, TwoObjectsAndText, TwoObjectsOverText, FourObjects, ClipArtAndVerticalText, VerticalTitleAndTextOverChart, ObjectAndTwoObject, TwoObjectsAndObject. |
| layoutName | java.lang.String | Nome para um novo layout. Se o nome fornecido já estiver em uso, será lançada uma ArgumentException. Se o parâmetro for nulo, então o nome será gerado automaticamente de acordo com o tipo de layout informado (por exemplo "Title Slide" ou "1_Title Slide", "2_..", etc.). |

--------------------

1) Layout adicionado para o valor SlideLayoutType.Custom de layoutType não contém placeholders nem formas. 2) Análogo a este método é o método [IMasterLayoutSlideCollection.add(byte,String)](../../com.aspose.slides/imasterlayoutslidecollection\#add-byte-String-) acessado através da propriedade ([IMasterSlide.getLayoutSlides](../../com.aspose.slides/imasterslide\#getLayoutSlides)).

**Retorno:**
[ILayoutSlide](../../com.aspose.slides/ilayoutslide) - Slide adicionado.