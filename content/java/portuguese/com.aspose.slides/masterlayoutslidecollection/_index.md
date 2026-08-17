---
title: MasterLayoutSlideCollection
second_title: Referência da API Aspose.Slides para Java
description: Representa uma coleção de todos os layout slides do slide mestre definido.
type: docs
url: /pt/com.aspose.slides/masterlayoutslidecollection/
---
**Herança:**
java.lang.Object, [com.aspose.slides.LayoutSlideCollection](../../com.aspose.slides/layoutslidecollection)

**Todas as Interfaces Implementadas:**
[com.aspose.slides.IMasterLayoutSlideCollection](../../com.aspose.slides/imasterlayoutslidecollection)
```
public final class MasterLayoutSlideCollection extends LayoutSlideCollection implements IMasterLayoutSlideCollection
```

Representa uma coleção de todos os layout slides do slide mestre definido. Estende a classe LayoutSlideCollection com métodos para adicionar/inserir/remover/clonar/reordenar layout slides no contexto das coleções individuais de layout slides do mestre.

## Métodos

| Método | Descrição |
| --- | --- |
| [addClone(ILayoutSlide sourceLayout)](#addClone-com.aspose.slides.ILayoutSlide-) | Adiciona uma cópia de um layout slide especificado ao final da coleção. |
| [insertClone(int index, ILayoutSlide sourceLayout)](#insertClone-int-com.aspose.slides.ILayoutSlide-) | Insere uma cópia de um layout slide especificado em uma posição especificada da coleção. |
| [add(byte layoutType, String layoutName)](#add-byte-java.lang.String-) | Adiciona um novo layout slide ao final da coleção. |
| [insert(int index, byte layoutType, String layoutName)](#insert-int-byte-java.lang.String-) | Insere um novo layout slide em uma posição especificada da coleção. |
| [removeAt(int index)](#removeAt-int-) | Remove o elemento no índice especificado da coleção. |
| [reorder(int index, ILayoutSlide layoutSlide)](#reorder-int-com.aspose.slides.ILayoutSlide-) | Move o layout slide da coleção para a posição especificada. |
### addClone(ILayoutSlide sourceLayout) {#addClone-com.aspose.slides.ILayoutSlide-}
```
public final ILayoutSlide addClone(ILayoutSlide sourceLayout)
```

Adiciona uma cópia de um layout slide especificado ao final da coleção.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| sourceLayout | [ILayoutSlide](../../com.aspose.slides/ilayoutslide) | Slide a ser clonado. |

--------------------

1) O novo layout será vinculado ao slide mestre pai para esta coleção de layouts de slides. Portanto, isto é análogo a copiar/colar com a opção "Use Destination Theme" no PowerPoint. 2) Um análogo deste método é o método [IGlobalLayoutSlideCollection.addClone(ILayoutSlide,IMasterSlide)](../../com.aspose.slides/igloballayoutslidecollection\#addClone-ILayoutSlide-IMasterSlide-) acessado através da propriedade ([IPresentation.getLayoutSlides](../../com.aspose.slides/ipresentation\#getLayoutSlides)).

**Retorno:**
[ILayoutSlide](../../com.aspose.slides/ilayoutslide) - Slide adicionado.
### insertClone(int index, ILayoutSlide sourceLayout) {#insertClone-int-com.aspose.slides.ILayoutSlide-}
```
public final ILayoutSlide insertClone(int index, ILayoutSlide sourceLayout)
```

Insere uma cópia de um layout slide especificado em uma posição especificada da coleção.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| index | int | Índice do novo slide. |
| sourceLayout | [ILayoutSlide](../../com.aspose.slides/ilayoutslide) | Slide a ser clonado. |

--------------------

O novo layout será vinculado ao slide mestre pai para esta coleção de layouts de slides. Portanto, isto é análogo a copiar/colar com a opção "Use Destination Theme" no PowerPoint.

**Retorno:**
[ILayoutSlide](../../com.aspose.slides/ilayoutslide) - Slide inserido.
### add(byte layoutType, String layoutName) {#add-byte-java.lang.String-}
```
public final ILayoutSlide add(byte layoutType, String layoutName)
```

Adiciona um novo layout slide ao final da coleção.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| layoutType | byte | Tipo de layout para um novo layout. Tipos de layout suportados: Title, TitleOnly, Blank, TitleAndObject, VerticalText, VerticalTitleAndText, TwoObjects, SectionHeader, TwoTextAndTwoObjects, TitleObjectAndCaption, PictureAndCaption, Custom. Outros tipos de layout não são suportados atualmente: Text, TwoColumnText, Table, TextAndChart, ChartAndText, Diagram, Chart, TextAndClipArt, ClipArtAndText, TextAndObject, ObjectAndText, Object, TextAndMedia, MediaAndText, ObjectOverText, TextOverObject, TextAndTwoObjects, TwoObjectsAndText, TwoObjectsOverText, FourObjects, ClipArtAndVerticalText, VerticalTitleAndTextOverChart, ObjectAndTwoObject, TwoObjectsAndObject. |
| layoutName | java.lang.String | Nome para um novo layout. Se o nome fornecido já estiver em uso, será lançada uma ArgumentException. Se o parâmetro for nulo, o nome será gerado automaticamente de acordo com o tipo de layout fornecido (por exemplo "Title Slide" ou "1_Title Slide", "2_..", etc.). |

--------------------

1) O layout adicionado para o valor SlideLayoutType.Custom de layoutType não contém placeholders nem shapes. 2) Um análogo deste método é o método [IGlobalLayoutSlideCollection.add(IMasterSlide,byte,String)](../../com.aspose.slides/igloballayoutslidecollection\#add-IMasterSlide-byte-String-) acessado através da propriedade ([IPresentation.getLayoutSlides](../../com.aspose.slides/ipresentation\#getLayoutSlides)).

**Retorno:**
[ILayoutSlide](../../com.aspose.slides/ilayoutslide) - Slide adicionado.
### insert(int index, byte layoutType, String layoutName) {#insert-int-byte-java.lang.String-}
```
public final ILayoutSlide insert(int index, byte layoutType, String layoutName)
```

Insere um novo layout slide em uma posição especificada da coleção.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| index | int | Índice do novo slide. |
| layoutType | byte | Tipo de layout para um novo layout. Tipos de layout suportados: Title, TitleOnly, Blank, TitleAndObject, VerticalText, VerticalTitleAndText, TwoObjects, SectionHeader, TwoTextAndTwoObjects, TitleObjectAndCaption, PictureAndCaption, Custom. Outros tipos de layout não são suportados atualmente: Text, TwoColumnText, Table, TextAndChart, ChartAndText, Diagram, Chart, TextAndClipArt, ClipArtAndText, TextAndObject, ObjectAndText, Object, TextAndMedia, MediaAndText, ObjectOverText, TextOverObject, TextAndTwoObjects, TwoObjectsAndText, TwoObjectsOverText, FourObjects, ClipArtAndVerticalText, VerticalTitleAndTextOverChart, ObjectAndTwoObject, TwoObjectsAndObject. |
| layoutName | java.lang.String | Nome para um novo layout. Se o nome fornecido já estiver em uso, será lançada uma ArgumentException. Se o parâmetro for nulo, o nome será gerado automaticamente de acordo com o tipo de layout fornecido (por exemplo "Title Slide" ou "1_Title Slide", "2_..", etc.). |

--------------------

Layout inserido para o valor SlideLayoutType.Custom de layoutType não contém placeholders nem shapes.

**Retorno:**
[ILayoutSlide](../../com.aspose.slides/ilayoutslide) - Slide inserido.
### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```

Remove o elemento no índice especificado da coleção.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| index | int | O índice baseado em zero do elemento a ser removido. |

--------------------

1) Para evitar a exceção PptxEditException, verifique a propriedade HasDependingSlides do layout antes. 2) Você também pode usar o método [ILayoutSlide.remove](../../com.aspose.slides/ilayoutslide\#remove) para simplificar o código.

### reorder(int index, ILayoutSlide layoutSlide) {#reorder-int-com.aspose.slides.ILayoutSlide-}
```
public final void reorder(int index, ILayoutSlide layoutSlide)
```

Move o layout slide da coleção para a posição especificada.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| index | int | Índice de destino. |
| layoutSlide | [ILayoutSlide](../../com.aspose.slides/ilayoutslide) | Slide a ser movido. |