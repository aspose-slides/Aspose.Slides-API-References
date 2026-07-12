---
title: IMasterLayoutSlideCollection
second_title: Aspose.Slides para Android via Referência da API Java
description: Representa uma coleção de todos os slides de layout de um slide mestre definido.
type: docs
url: /pt/com.aspose.slides/imasterlayoutslidecollection/
---
**Todas as Interfaces Implementadas:**
[com.aspose.slides.ILayoutSlideCollection](../../com.aspose.slides/ilayoutslidecollection)
```
public interface IMasterLayoutSlideCollection extends ILayoutSlideCollection
```

Representa uma coleção de todos os slides de layout de um slide mestre definido. Extende a interface ILayoutSlideCollection com métodos para adicionar/inserir/remover/clonar slides de layout no contexto das coleções individuais de slides de layout do mestre.

## Métodos

| Método | Descrição |
| --- | --- |
| [addClone(ILayoutSlide sourceLayout)](#addClone-com.aspose.slides.ILayoutSlide-) | Adiciona uma cópia de um slide de layout especificado ao final da coleção. |
| [insertClone(int index, ILayoutSlide sourceLayout)](#insertClone-int-com.aspose.slides.ILayoutSlide-) | Insere uma cópia de um slide de layout especificado em posição especificada da coleção. |
| [add(byte layoutType, String layoutName)](#add-byte-java.lang.String-) | Adiciona um novo slide de layout ao final da coleção. |
| [insert(int index, byte layoutType, String layoutName)](#insert-int-byte-java.lang.String-) | Insere um novo slide de layout em posição especificada da coleção. |
| [removeAt(int index)](#removeAt-int-) | Remove o elemento no índice especificado da coleção. |
| [reorder(int index, ILayoutSlide layoutSlide)](#reorder-int-com.aspose.slides.ILayoutSlide-) | Move o slide de layout da coleção para a posição especificada. |

### addClone(ILayoutSlide sourceLayout) {#addClone-com.aspose.slides.ILayoutSlide-}
```
public abstract ILayoutSlide addClone(ILayoutSlide sourceLayout)
```

Adiciona uma cópia de um slide de layout especificado ao final da coleção.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| sourceLayout | [ILayoutSlide](../../com.aspose.slides/ilayoutslide) | Slide a ser clonado.

--------------------

1) O novo layout será vinculado ao slide mestre pai para esta coleção de slides de layout. Portanto, isso equivale a copiar/colar com a opção “Use Destination Theme” no PowerPoint. 2) Análogo deste método é o método [IGlobalLayoutSlideCollection.addClone(ILayoutSlide,IMasterSlide)](../../com.aspose.slides/igloballayoutslidecollection\#addClone-ILayoutSlide-IMasterSlide-) acessado através da propriedade [IPresentation.getLayoutSlides](../../com.aspose.slides/ipresentation\#getLayoutSlides).

**Retorna:**
[ILayoutSlide](../../com.aspose.slides/ilayoutslide) - Slide adicionado.

### insertClone(int index, ILayoutSlide sourceLayout) {#insertClone-int-com.aspose.slides.ILayoutSlide-}
```
public abstract ILayoutSlide insertClone(int index, ILayoutSlide sourceLayout)
```

Insere uma cópia de um slide de layout especificado em posição especificada da coleção.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| index | int | Índice do novo slide. |
| sourceLayout | [ILayoutSlide](../../com.aspose.slides/ilayoutslide) | Slide a ser clonado.

--------------------

O novo layout será vinculado ao slide mestre pai para esta coleção de slides de layout. Portanto, isso equivale a copiar/colar com a opção “Use Destination Theme” no PowerPoint.

**Retorna:**
[ILayoutSlide](../../com.aspose.slides/ilayoutslide) - Slide inserido.

### add(byte layoutType, String layoutName) {#add-byte-java.lang.String-}
```
public abstract ILayoutSlide add(byte layoutType, String layoutName)
```

Adiciona um novo slide de layout ao final da coleção.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| layoutType | byte | Tipo de layout para um novo layout. Tipos de layout suportados: Title, TitleOnly, Blank, TitleAndObject, VerticalText, VerticalTitleAndText, TwoObjects, SectionHeader, TwoTextAndTwoObjects, TitleObjectAndCaption, PictureAndCaption, Custom. Outros tipos de layout não são suportados atualmente: Text, TwoColumnText, Table, TextAndChart, ChartAndText, Diagram, Chart, TextAndClipArt, ClipArtAndText, TextAndObject, ObjectAndText, Object, TextAndMedia, MediaAndText, ObjectOverText, TextOverObject, TextAndTwoObjects, TwoObjectsAndText, TwoObjectsOverText, FourObjects, ClipArtAndVerticalText, VerticalTitleAndTextOverChart, ObjectAndTwoObject, TwoObjectsAndObject. |
| layoutName | java.lang.String | Nome para um novo layout. Se o nome passado já estiver em uso, será lançada uma ArgumentException. Se o parâmetro for nulo, o nome será gerado automaticamente de acordo com o tipo de layout passado (por exemplo “Title Slide” ou “1_Title Slide”, “2_..”, etc.).

--------------------

1) Layout adicionado para o valor SlideLayoutType.Custom de layoutType não contém marcadores nem formas. 2) Análogo deste método é o método [IGlobalLayoutSlideCollection.add(IMasterSlide,byte,String)](../../com.aspose.slides/igloballayoutslidecollection\#add-IMasterSlide-byte-String-) acessado através da propriedade [IPresentation.getLayoutSlides](../../com.aspose.slides/ipresentation\#getLayoutSlides).

**Retorna:**
[ILayoutSlide](../../com.aspose.slides/ilayoutslide) - Slide adicionado.

### insert(int index, byte layoutType, String layoutName) {#insert-int-byte-java.lang.String-}
```
public abstract ILayoutSlide insert(int index, byte layoutType, String layoutName)
```

Insere um novo slide de layout em posição especificada da coleção.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| index | int | Índice do novo slide. |
| layoutType | byte | Tipo de layout para um novo layout. Tipos de layout suportados: Title, TitleOnly, Blank, TitleAndObject, VerticalText, VerticalTitleAndText, TwoObjects, SectionHeader, TwoTextAndTwoObjects, TitleObjectAndCaption, PictureAndCaption, Custom. Outros tipos de layout não são suportados atualmente: Text, TwoColumnText, Table, TextAndChart, ChartAndText, Diagram, Chart, TextAndClipArt, ClipArtAndText, TextAndObject, ObjectAndText, Object, TextAndMedia, MediaAndText, ObjectOverText, TextOverObject, TextAndTwoObjects, TwoObjectsAndText, TwoObjectsOverText, FourObjects, ClipArtAndVerticalText, VerticalTitleAndTextOverChart, ObjectAndTwoObject, TwoObjectsAndObject. |
| layoutName | java.lang.String | Nome para um novo layout. Se o nome passado já estiver em uso, será lançada uma ArgumentException. Se o parâmetro for nulo, o nome será gerado automaticamente de acordo com o tipo de layout passado (por exemplo “Title Slide” ou “1_Title Slide”, “2_..”, etc.).

--------------------

Layout inserido para o valor SlideLayoutType.Custom de layoutType não contém marcadores nem formas.

**Retorna:**
[ILayoutSlide](../../com.aspose.slides/ilayoutslide) - Slide inserido.

### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```

Remove o elemento no índice especificado da coleção.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| index | int | O índice baseado em zero do elemento a ser removido.

--------------------

1) Para evitar a exceção PptxEditException, verifique antes a propriedade HasDependingSlides do layout. 2) Você também pode usar o método [ILayoutSlide.remove](../../com.aspose.slides/ilayoutslide\#remove) para simplificar o código.

### reorder(int index, ILayoutSlide layoutSlide) {#reorder-int-com.aspose.slides.ILayoutSlide-}
```
public abstract void reorder(int index, ILayoutSlide layoutSlide)
```

Move o slide de layout da coleção para a posição especificada.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| index | int | Índice alvo. |
| layoutSlide | [ILayoutSlide](../../com.aspose.slides/ilayoutslide) | Slide a ser movido. |