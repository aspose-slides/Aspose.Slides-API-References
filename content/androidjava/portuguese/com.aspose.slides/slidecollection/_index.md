---
title: SlideCollection
second_title: Aspose.Slides para Android via Referência de API Java
description: Representa uma coleção de slides.
type: docs
url: /pt/com.aspose.slides/slidecollection/
---
**Herança:**
java.lang.Object, com.aspose.slides.DomObject

**Todas as Interfaces Implementadas:**
[com.aspose.slides.ISlideCollection](../../com.aspose.slides/islidecollection)
```
public final class SlideCollection extends DomObject<Presentation> implements ISlideCollection
```

Representa uma coleção de slides.
## Métodos

| Method | Description |
| --- | --- |
| [size()](#size--) | Obtém o número de elementos realmente contidos na coleção. |
| [get_Item(int index)](#get-Item-int-) | Obtém o elemento no índice especificado. |
| [addClone(ISlide sourceSlide)](#addClone-com.aspose.slides.ISlide-) | Adiciona uma cópia de um slide especificado ao final da coleção. |
| [addClone(ISlide sourceSlide, ISection section)](#addClone-com.aspose.slides.ISlide-com.aspose.slides.ISection-) | Adiciona uma cópia de um slide especificado ao final da seção especificada. |
| [insertClone(int index, ISlide sourceSlide)](#insertClone-int-com.aspose.slides.ISlide-) | Insere uma cópia de um slide especificado na posição especificada da coleção. |
| [addEmptySlide(ILayoutSlide layout)](#addEmptySlide-com.aspose.slides.ILayoutSlide-) | Adiciona um novo slide vazio ao final da coleção. |
| [insertEmptySlide(int index, ILayoutSlide layout)](#insertEmptySlide-int-com.aspose.slides.ILayoutSlide-) | Insere uma cópia de um slide especificado na posição especificada da coleção. |
| [addClone(ISlide sourceSlide, ILayoutSlide destLayout)](#addClone-com.aspose.slides.ISlide-com.aspose.slides.ILayoutSlide-) | Adiciona uma cópia de um slide especificado ao final da coleção. |
| [insertClone(int index, ISlide sourceSlide, ILayoutSlide destLayout)](#insertClone-int-com.aspose.slides.ISlide-com.aspose.slides.ILayoutSlide-) | Insere uma cópia de um slide especificado na posição especificada da coleção. |
| [addClone(ISlide sourceSlide, IMasterSlide destMaster, boolean allowCloneMissingLayout)](#addClone-com.aspose.slides.ISlide-com.aspose.slides.IMasterSlide-boolean-) | Adiciona uma cópia de um slide fonte especificado ao final da coleção. |
| [insertClone(int index, ISlide sourceSlide, IMasterSlide destMaster, boolean allowCloneMissingLayout)](#insertClone-int-com.aspose.slides.ISlide-com.aspose.slides.IMasterSlide-boolean-) | Insere uma cópia de um slide fonte especificado na posição especificada da coleção. |
| [remove(ISlide value)](#remove-com.aspose.slides.ISlide-) | Remove a primeira ocorrência de um objeto específico da coleção. |
| [removeAt(int index)](#removeAt-int-) | Remove o elemento no índice especificado da coleção. |
| [iterator()](#iterator--) | Retorna um enumerador que itera pela coleção. |
| [iteratorJava()](#iteratorJava--) | Retorna um iterator Java para toda a coleção. |
| [toArray()](#toArray--) | Cria e retorna um array com todos os slides. |
| [toArray(int startIndex, int count)](#toArray-int-int-) | Cria e retorna um array com todos os slides do intervalo especificado. |
| [reorder(int index, ISlide slide)](#reorder-int-com.aspose.slides.ISlide-) | Move o slide da coleção para a posição especificada. |
| [reorder(int index, ISlide[] slides)](#reorder-int-com.aspose.slides.ISlide...-) | Move slides da coleção para a posição especificada. |
| [indexOf(ISlide slide)](#indexOf-com.aspose.slides.ISlide-) | Retorna o índice do slide especificado na coleção. |
| [addFromPdf(String path)](#addFromPdf-java.lang.String-) | Cria slides a partir do documento PDF e os adiciona ao final da coleção. |
| [addFromPdf(String path, PdfImportOptions pdfImportOptions)](#addFromPdf-java.lang.String-com.aspose.slides.PdfImportOptions-) | Cria slides a partir do documento PDF e os adiciona ao final da coleção considerando as opções de importação de PDF. |
| [addFromPdf(InputStream pdfStream)](#addFromPdf-java.io.InputStream-) | Cria slides a partir do documento PDF e os adiciona ao final da coleção. |
| [addFromPdf(InputStream pdfStream, PdfImportOptions pdfImportOptions)](#addFromPdf-java.io.InputStream-com.aspose.slides.PdfImportOptions-) | Cria slides a partir do documento PDF e os adiciona ao final da coleção. |
| [addFromHtml(String htmlText, IExternalResourceResolver resolver, String uri)](#addFromHtml-java.lang.String-com.aspose.slides.IExternalResourceResolver-java.lang.String-) | Cria slides a partir de texto HTML e os adiciona ao final da coleção. |
| [addFromHtml(String htmlText)](#addFromHtml-java.lang.String-) | Cria slides a partir de texto HTML e os adiciona ao final da coleção. |
| [addFromHtml(InputStream htmlStream, IExternalResourceResolver resolver, String uri)](#addFromHtml-java.io.InputStream-com.aspose.slides.IExternalResourceResolver-java.lang.String-) | Cria slides a partir de texto HTML e os adiciona ao final da coleção. |
| [addFromHtml(InputStream htmlStream)](#addFromHtml-java.io.InputStream-) | Cria slides a partir de texto HTML e os adiciona ao final da coleção. |
| [insertFromHtml(int index, String htmlText, IExternalResourceResolver resolver, String uri)](#insertFromHtml-int-java.lang.String-com.aspose.slides.IExternalResourceResolver-java.lang.String-) | Cria slides a partir de texto HTML e os insere na coleção na posição especificada. |
| [insertFromHtml(int index, String htmlText, IExternalResourceResolver resolver, String uri, boolean useSlideWithIndexAsStart)](#insertFromHtml-int-java.lang.String-com.aspose.slides.IExternalResourceResolver-java.lang.String-boolean-) | Cria slides a partir de texto HTML e os insere na coleção na posição especificada. |
| [insertFromHtml(int index, String htmlText)](#insertFromHtml-int-java.lang.String-) | Cria slides a partir de texto HTML e os insere na coleção na posição especificada. |
| [insertFromHtml(int index, String htmlText, boolean useSlideWithIndexAsStart)](#insertFromHtml-int-java.lang.String-boolean-) | Cria slides a partir de texto HTML e os insere na coleção na posição especificada. |
| [insertFromHtml(int index, InputStream htmlStream, IExternalResourceResolver resolver, String uri)](#insertFromHtml-int-java.io.InputStream-com.aspose.slides.IExternalResourceResolver-java.lang.String-) | Cria slides a partir de texto HTML e os insere na coleção na posição especificada. |
| [insertFromHtml(int index, InputStream htmlStream, IExternalResourceResolver resolver, String uri, boolean useSlideWithIndexAsStart)](#insertFromHtml-int-java.io.InputStream-com.aspose.slides.IExternalResourceResolver-java.lang.String-boolean-) | Cria slides a partir de texto HTML e os insere na coleção na posição especificada. |
| [insertFromHtml(int index, InputStream htmlStream)](#insertFromHtml-int-java.io.InputStream-) | Cria slides a partir de texto HTML e os insere na coleção na posição especificada. |
| [insertFromHtml(int index, InputStream htmlStream, boolean useSlideWithIndexAsStart)](#insertFromHtml-int-java.io.InputStream-boolean-) | Cria slides a partir de texto HTML e os insere na coleção na posição especificada. |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | Copia todos os elementos da coleção para o array especificado. |
| [isSynchronized()](#isSynchronized--) | Retorna um valor indicando se o acesso à coleção é sincronizado (thread-safe). |
| [getSyncRoot()](#getSyncRoot--) | Retorna a raiz de sincronização. |
### size() {#size--}
```
public final int size()
```


Obtém o número de elementos realmente contidos na coleção. Somente leitura int.

**Retorna:**
int
### get_Item(int index) {#get-Item-int-}
```
public final ISlide get_Item(int index)
```


Obtém o elemento no índice especificado. Somente leitura [Slide](../../com.aspose.slides/slide).

**Parâmetros:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int |  |

**Retorna:**
[ISlide](../../com.aspose.slides/islide)
### addClone(ISlide sourceSlide) {#addClone-com.aspose.slides.ISlide-}
```
public final ISlide addClone(ISlide sourceSlide)
```


Adiciona uma cópia de um slide especificado ao final da coleção.

**Parâmetros:**
| Parameter | Type | Description |
| --- | --- | --- |
| sourceSlide | [ISlide](../../com.aspose.slides/islide) | Slide a ser clonado.

--------------------

Ao clonar um slide entre apresentações diferentes, o mestre do slide também pode ser clonado. Um registro interno é usado para rastrear mestres clonados automaticamente e impedir a criação de múltiplos clones do mesmo slide mestre. A clonagem manual de slides mestres não será impedida nem registrada. Se precisar de mais controle sobre o processo de clonagem, use \#addClone(ISlide,ILayoutSlide).addClone(ISlide,ILayoutSlide) ou \#addClone(ISlide,IMasterSlide,boolean).addClone(ISlide,IMasterSlide,boolean) para clonar slides, [IGlobalLayoutSlideCollection.addClone(ILayoutSlide)](../../com.aspose.slides/igloballayoutslidecollection\#addClone-ILayoutSlide-) ou [IGlobalLayoutSlideCollection.addClone(ILayoutSlide,IMasterSlide)](../../com.aspose.slides/igloballayoutslidecollection\#addClone-ILayoutSlide-IMasterSlide-) para clonar layouts e [IMasterSlideCollection.addClone(IMasterSlide)](../../com.aspose.slides/imasterslidecollection\#addClone-IMasterSlide-) para clonar mestres. |

**Retorna:**
[ISlide](../../com.aspose.slides/islide) - Novo slide.
### addClone(ISlide sourceSlide, ISection section) {#addClone-com.aspose.slides.ISlide-com.aspose.slides.ISection-}
```
public final ISlide addClone(ISlide sourceSlide, ISection section)
```


Adiciona uma cópia de um slide especificado ao final da seção especificada.

--------------------

> ```
> IPresentation presentation = new Presentation();
>  try
>  {
>      presentation.getSlides().get_Item(0).getShapes().addAutoShape(ShapeType.Rectangle, 200, 50, 300, 100);
>      presentation.getSections().addSection("Section 1", presentation.getSlides().get_Item(0));
>      
>      ISection section2 = presentation.getSections().appendEmptySection("Section 2");
>      presentation.getSlides().addClone(presentation.getSlides().get_Item(0), section2);
>      
>      // Agora a segunda seção contém uma cópia do primeiro slide.
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```

**Parâmetros:**
| Parameter | Type | Description |
| --- | --- | --- |
| sourceSlide | [ISlide](../../com.aspose.slides/islide) | Slide a ser clonado. |
| section | [ISection](../../com.aspose.slides/isection) | Seção para o novo slide. |

**Retorna:**
[ISlide](../../com.aspose.slides/islide) - Novo slide.
### insertClone(int index, ISlide sourceSlide) {#insertClone-int-com.aspose.slides.ISlide-}
```
public final ISlide insertClone(int index, ISlide sourceSlide)
```


Insere uma cópia de um slide especificado na posição especificada da coleção.

--------------------

> ```
> The following example shows how to clone at another position within Presentation.
>  
>  // Instanciar a classe Presentation que representa um arquivo de apresentação
>  Presentation pres = new Presentation("CloneWithInSamePresentation.pptx");
>  try {
>      // Clonar o slide desejado para o final da coleção de slides na mesma apresentação
>      ISlideCollection slds = pres.getSlides();
>      // Clonar o slide desejado para o índice especificado na mesma apresentação
>      slds.insertClone(2, pres.getSlides().get_Item(1));
>      // Gravar a apresentação modificada no disco
>      pres.save("Aspose_CloneWithInSamePresentation_out.pptx", SaveFormat.Pptx);
>  }
>  finally
>  {
>      if (pres != null) pres.dispose();
>  }
>  
>  The following example shows how to clone at another position within Presentation.
>  
>  // Instanciar a classe Presentation para carregar o arquivo de apresentação fonte
>  Presentation srcPres = new Presentation("CloneAtEndOfAnother.pptx");
>  try {
>      // Instanciar a classe Presentation para o PPTX de destino (onde o slide será clonado)
>      Presentation destPres = new Presentation();
>      try {
>          ISlideCollection slds = destPres.getSlides();
>          slds.insertClone(2, srcPres.getSlides().get_Item(0));
>          // Gravar a apresentação de destino no disco
>          destPres.save("Aspose2_out.pptx", SaveFormat.Pptx);
>      } finally {
>          if (destPres != null) destPres.dispose();
>      }
>  } finally {
>      if (srcPres != null) srcPres.dispose();
>  }
> ```

**Parâmetros:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | Índice do novo slide. |
| sourceSlide | [ISlide](../../com.aspose.slides/islide) | Slide a ser clonado.

--------------------

Ao clonar um slide entre apresentações diferentes, o mestre do slide também pode ser clonado. Um registro interno é usado para rastrear mestres clonados automaticamente e impedir a criação de múltiplos clones do mesmo slide mestre. A clonagem manual de slides mestres não será impedida nem registrada. Se precisar de mais controle sobre o processo de clonagem, use \#insertClone(int,ISlide,ILayoutSlide).insertClone(int,ISlide,ILayoutSlide) ou \#insertClone(int,ISlide,IMasterSlide,boolean).insertClone(int,ISlide,IMasterSlide,boolean) para clonar slides e [IMasterSlideCollection.addClone(IMasterSlide)](../../com.aspose.slides/imasterslidecollection\#addClone-IMasterSlide-) para clonar mestres. |

**Retorna:**
[ISlide](../../com.aspose.slides/islide) - Slide inserido.
### addEmptySlide(ILayoutSlide layout) {#addEmptySlide-com.aspose.slides.ILayoutSlide-}
```
public final ISlide addEmptySlide(ILayoutSlide layout)
```


Adiciona um novo slide vazio ao final da coleção.

**Parâmetros:**
| Parameter | Type | Description |
| --- | --- | --- |
| layout | [ILayoutSlide](../../com.aspose.slides/ilayoutslide) | Layout para o slide. |

**Retorna:**
[ISlide](../../com.aspose.slides/islide) - Slide adicionado.
### insertEmptySlide(int index, ILayoutSlide layout) {#insertEmptySlide-int-com.aspose.slides.ILayoutSlide-}
```
public final ISlide insertEmptySlide(int index, ILayoutSlide layout)
```


Insere uma cópia de um slide especificado na posição especificada da coleção.

**Parâmetros:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | Índice de um novo slide. |
| layout | [ILayoutSlide](../../com.aspose.slides/ilayoutslide) | Layout para o slide. |

**Retorna:**
[ISlide](../../com.aspose.slides/islide) - Slide inserido.
### addClone(ISlide sourceSlide, ILayoutSlide destLayout) {#addClone-com.aspose.slides.ISlide-com.aspose.slides.ILayoutSlide-}
```
public final ISlide addClone(ISlide sourceSlide, ILayoutSlide destLayout)
```


Adiciona uma cópia de um slide especificado ao final da coleção.

**Parâmetros:**
| Parameter | Type | Description |
| --- | --- | --- |
| sourceSlide | [ISlide](../../com.aspose.slides/islide) | Slide a ser clonado. |
| destLayout | [ILayoutSlide](../../com.aspose.slides/ilayoutslide) | Layout de slide para o novo slide. |

**Retorna:**
[ISlide](../../com.aspose.slides/islide) - Novo slide.
### insertClone(int index, ISlide sourceSlide, ILayoutSlide destLayout) {#insertClone-int-com.aspose.slides.ISlide-com.aspose.slides.ILayoutSlide-}
```
public final ISlide insertClone(int index, ISlide sourceSlide, ILayoutSlide destLayout)
```


Insere uma cópia de um slide especificado na posição especificada da coleção.

**Parâmetros:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | Índice do novo slide. |
| sourceSlide | [ISlide](../../com.aspose.slides/islide) | Slide a ser clonado. |
| destLayout | [ILayoutSlide](../../com.aspose.slides/ilayoutslide) | Layout de slide para o novo slide. |

**Retorna:**
[ISlide](../../com.aspose.slides/islide) - Slide inserido.
### addClone(ISlide sourceSlide, IMasterSlide destMaster, boolean allowCloneMissingLayout) {#addClone-com.aspose.slides.ISlide-com.aspose.slides.IMasterSlide-boolean-}
```
public final ISlide addClone(ISlide sourceSlide, IMasterSlide destMaster, boolean allowCloneMissingLayout)
```


Adiciona uma cópia de um slide fonte especificado ao final da coleção. O layout apropriado será selecionado automaticamente a partir do mestre especificado (o layout apropriado é o que tem o mesmo Tipo ou Nome do layout do slide fonte). Se não houver layout apropriado, o layout do slide fonte será clonado (se allowCloneMissingLayout for true) ou será lançada uma PptxEditException (se allowCloneMissingLayout for false).

**Parâmetros:**
| Parameter | Type | Description |
| --- | --- | --- |
| sourceSlide | [ISlide](../../com.aspose.slides/islide) | Slide a ser clonado. |
| destMaster | [IMasterSlide](../../com.aspose.slides/imasterslide) | Slide mestre para o novo slide. |
| allowCloneMissingLayout | boolean | Se não houver layout apropriado no mestre especificado, o layout do slide fonte será clonado (se allowCloneMissingLayout for true) ou será lançada uma PptxEditException (se allowCloneMissingLayout for false). |

**Retorna:**
[ISlide](../../com.aspose.slides/islide) - Novo slide.
### insertClone(int index, ISlide sourceSlide, IMasterSlide destMaster, boolean allowCloneMissingLayout) {#insertClone-int-com.aspose.slides.ISlide-com.aspose.slides.IMasterSlide-boolean-}
```
public final ISlide insertClone(int index, ISlide sourceSlide, IMasterSlide destMaster, boolean allowCloneMissingLayout)
```


Insere uma cópia de um slide fonte especificado na posição especificada da coleção. O layout apropriado será selecionado automaticamente a partir do mestre especificado (o layout apropriado é o que tem o mesmo Tipo ou Nome do layout do slide fonte). Se não houver layout apropriado, o layout do slide fonte será clonado (se allowCloneMissingLayout for true) ou será lançada uma PptxEditException (se allowCloneMissingLayout for false).

**Parâmetros:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | Índice do novo slide. |
| sourceSlide | [ISlide](../../com.aspose.slides/islide) | Slide a ser clonado. |
| destMaster | [IMasterSlide](../../com.aspose.slides/imasterslide) | Slide mestre para o novo slide. |
| allowCloneMissingLayout | boolean | Se não houver layout apropriado no mestre especificado, o layout do slide fonte será clonado (se allowCloneMissingLayout for true) ou será lançada uma PptxEditException (se allowCloneMissingLayout for false). |

**Retorna:**
[ISlide](../../com.aspose.slides/islide) - Slide inserido.
### remove(ISlide value) {#remove-com.aspose.slides.ISlide-}
```
public final void remove(ISlide value)
```


Remove a primeira ocorrência de um objeto específico da coleção.

**Parâmetros:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [ISlide](../../com.aspose.slides/islide) | O slide a ser removido da coleção. |

### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```


Remove o elemento no índice especificado da coleção.

**Parâmetros:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | O índice baseado em zero do elemento a ser removido. |

### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<ISlide> iterator()
```


Retorna um enumerador que itera pela coleção.

**Retorna:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.ISlide> - Um IGenericEnumerator que pode ser usado para iterar pela coleção.
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<ISlide> iteratorJava()
```


Retorna um iterator Java para toda a coleção.

**Retorna:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.ISlide> - Um java.util.Iterator para toda a coleção.
### toArray() {#toArray--}
```
public final ISlide[] toArray()
```


Cria e retorna um array com todos os slides.

**Retorna:**
com.aspose.slides.ISlide[] - Array de [Slide](../../com.aspose.slides/slide)
### toArray(int startIndex, int count) {#toArray-int-int-}
```
public final ISlide[] toArray(int startIndex, int count)
```


Cria e retorna um array com todos os slides do intervalo especificado.

**Parâmetros:**
| Parameter | Type | Description |
| --- | --- | --- |
| startIndex | int | Índice do primeiro slide a ser adicionado. |
| count | int | Número de slides a ser adicionado. |

**Retorna:**
com.aspose.slides.ISlide[] - Array de [Slide](../../com.aspose.slides/slide)
### reorder(int index, ISlide slide) {#reorder-int-com.aspose.slides.ISlide-}
```
public final void reorder(int index, ISlide slide)
```


Move o slide da coleção para a posição especificada.

**Parâmetros:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | Índice alvo. |
| slide | [ISlide](../../com.aspose.slides/islide) | Slide a mover. |

### reorder(int index, ISlide[] slides) {#reorder-int-com.aspose.slides.ISlide...-}
```
public final void reorder(int index, ISlide[] slides)
```


Move slides da coleção para a posição especificada. Slides serão posicionados a partir do índice na ordem em que aparecem na lista.

**Parâmetros:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | Índice alvo. |
| slides | [ISlide\[\]](../../com.aspose.slides/islide) | Slides a mover. |

### indexOf(ISlide slide) {#indexOf-com.aspose.slides.ISlide-}
```
public final int indexOf(ISlide slide)
```


Retorna o índice do slide especificado na coleção.

**Parâmetros:**
| Parameter | Type | Description |
| --- | --- | --- |
| slide | [ISlide](../../com.aspose.slides/islide) | Slide a localizar. |

**Retorna:**
int - Índice do slide ou -1 se o slide não pertencer a esta coleção.
### addFromPdf(String path) {#addFromPdf-java.lang.String-}
```
public final ISlide[] addFromPdf(String path)
```


Cria slides a partir do documento PDF e os adiciona ao final da coleção.

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation();
>  try {
>      pres.getSlides().addFromPdf("document.pdf");
>      pres.save("fromPdfDocument.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Parâmetros:**
| Parameter | Type | Description |
| --- | --- | --- |
| path | java.lang.String | Caminho para o documento PDF |

**Retorna:**
com.aspose.slides.ISlide[] - Slides adicionados
### addFromPdf(String path, PdfImportOptions pdfImportOptions) {#addFromPdf-java.lang.String-com.aspose.slides.PdfImportOptions-}
```
public final ISlide[] addFromPdf(String path, PdfImportOptions pdfImportOptions)
```


Cria slides a partir do documento PDF e os adiciona ao final da coleção considerando as opções de importação de PDF.

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation();
>  try {
>      PdfImportOptions pdfImportOptions = new PdfImportOptions();
>      pdfImportOptions.setDetectTables(true);
>      pres.getSlides().addFromPdf("document.pdf", pdfImportOptions);
>      pres.save("fromPdfDocument.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Parâmetros:**
| Parameter | Type | Description |
| --- | --- | --- |
| path | java.lang.String | Caminho para o documento PDF |
| pdfImportOptions | [PdfImportOptions](../../com.aspose.slides/pdfimportoptions) | Opções de importação de PDF |

**Retorna:**
com.aspose.slides.ISlide[] - Slides adicionados
### addFromPdf(InputStream pdfStream) {#addFromPdf-java.io.InputStream-}
```
public final ISlide[] addFromPdf(InputStream pdfStream)
```


Cria slides a partir do documento PDF e os adiciona ao final da coleção.

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation();
>  try {
>      FileInputStream stream = new FileInputStream("document.pdf");
>      pres.getSlides().addFromPdf(stream);
> 
>      pres.save("fromPdfDocument.pptx", SaveFormat.Pptx);
>  } catch (IOException e) {
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Parâmetros:**
| Parameter | Type | Description |
| --- | --- | --- |
| pdfStream | java.io.InputStream | Stream que será usado como fonte do documento PDF |

**Retorna:**
com.aspose.slides.ISlide[] - Slides adicionados
### addFromPdf(InputStream pdfStream, PdfImportOptions pdfImportOptions) {#addFromPdf-java.io.InputStream-com.aspose.slides.PdfImportOptions-}
```
public final ISlide[] addFromPdf(InputStream pdfStream, PdfImportOptions pdfImportOptions)
```


Cria slides a partir do documento PDF e os adiciona ao final da coleção.

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation();
>  try {
>      PdfImportOptions pdfImportOptions = new PdfImportOptions();
>      pdfImportOptions.setDetectTables(true);
> 
>      FileInputStream stream = new FileInputStream("document.pdf");
>      pres.getSlides().addFromPdf(stream, pdfImportOptions);
> 
>      pres.save("fromPdfDocument.pptx", SaveFormat.Pptx);
>  } catch (IOException e) {
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Parâmetros:**
| Parameter | Type | Description |
| --- | --- | --- |
| pdfStream | java.io.InputStream | Stream que será usado como fonte do documento PDF |
| pdfImportOptions | [PdfImportOptions](../../com.aspose.slides/pdfimportoptions) | Opções de importação de PDF |

**Retorna:**
com.aspose.slides.ISlide[] - Slides adicionados
### addFromHtml(String htmlText, IExternalResourceResolver resolver, String uri) {#addFromHtml-java.lang.String-com.aspose.slides.IExternalResourceResolver-java.lang.String-}
```
public final ISlide[] addFromHtml(String htmlText, IExternalResourceResolver resolver, String uri)
```


Cria slides a partir de texto HTML e os adiciona ao final da coleção.

**Parâmetros:**
| Parameter | Type | Description |
| --- | --- | --- |
| htmlText | java.lang.String | HTML a ser adicionado. |
| resolver | [IExternalResourceResolver](../../com.aspose.slides/iexternalresourceresolver) | Objeto de callback usado para buscar objetos externos. Se este parâmetro for nulo, todos os objetos externos serão ignorados. |
| uri | java.lang.String | URI do HTML especificado. Usado para resolver links relativos. |

**Retorna:**
com.aspose.slides.ISlide[] - Slides adicionados.
### addFromHtml(String htmlText) {#addFromHtml-java.lang.String-}
```
public final ISlide[] addFromHtml(String htmlText)
```


Cria slides a partir de texto HTML e os adiciona ao final da coleção.

**Parâmetros:**
| Parameter | Type | Description |
| --- | --- | --- |
| htmlText | java.lang.String | HTML a ser adicionado. |

**Retorna:**
com.aspose.slides.ISlide[] - Slides adicionados
### addFromHtml(InputStream htmlStream, IExternalResourceResolver resolver, String uri) {#addFromHtml-java.io.InputStream-com.aspose.slides.IExternalResourceResolver-java.lang.String-}
```
public final ISlide[] addFromHtml(InputStream htmlStream, IExternalResourceResolver resolver, String uri)
```


Cria slides a partir de texto HTML e os adiciona ao final da coleção.

**Parâmetros:**
| Parameter | Type | Description |
| --- | --- | --- |
| htmlStream | java.io.InputStream | Objeto Stream que será usado como fonte de um arquivo HTML. |
| resolver | [IExternalResourceResolver](../../com.aspose.slides/iexternalresourceresolver) | Objeto de callback usado para buscar objetos externos. Se este parâmetro for nulo, todos os objetos externos serão ignorados. |
| uri | java.lang.String | URI do HTML especificado. Usado para resolver links relativos. |

**Retorna:**
com.aspose.slides.ISlide[] - Slides adicionados.
### addFromHtml(InputStream htmlStream) {#addFromHtml-java.io.InputStream-}
```
public final ISlide[] addFromHtml(InputStream htmlStream)
```


Cria slides a partir de texto HTML e os adiciona ao final da coleção.

--------------------

> ```
> // Crie uma instância da classe Presentation.
>  Presentation pres = new Presentation();
>  try {
>      FileInputStream fos = null;
>      try {
>          fos = new FileInputStream("file.html");
>          // Chame o método AddFromHtml e passe o arquivo HTML.
>          pres.getSlides().addFromHtml(fos);
>          // Use o método Save para salvar o arquivo como um documento PowerPoint.
>          pres.save("MyPresentation.pptx", SaveFormat.Pptx);
>      } finally {
>          if (fos != null) fos.close();
>      }
>  } catch(IOException e) {
>  } finally {
>      if (pres != null) pres.dispose();
>  }
```

**Parâmetros:**
| Parameter | Type | Description |
| --- | --- | --- |
| htmlStream | java.io.InputStream | Objeto Stream que será usado como fonte de um arquivo HTML. |

**Retorna:**
com.aspose.slides.ISlide[] - Slides adicionados
### insertFromHtml(int index, String htmlText, IExternalResourceResolver resolver, String uri) {#insertFromHtml-int-java.lang.String-com.aspose.slides.IExternalResourceResolver-java.lang.String-}
```
public final ISlide[] insertFromHtml(int index, String htmlText, IExternalResourceResolver resolver, String uri)
```


Cria slides a partir de texto HTML e os insere na coleção na posição especificada.

**Parâmetros:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | Posição para inserção. |
| htmlText | java.lang.String | HTML a ser adicionado. |
| resolver | [IExternalResourceResolver](../../com.aspose.slides/iexternalresourceresolver) | Objeto de callback usado para buscar objetos externos. Se este parâmetro for nulo, todos os objetos externos serão ignorados. |
| uri | java.lang.String | URI do HTML especificado. Usado para resolver links relativos. |

**Retorna:**
com.aspose.slides.ISlide[] - Slides adicionados.
### insertFromHtml(int index, String htmlText, IExternalResourceResolver resolver, String uri, boolean useSlideWithIndexAsStart) {#insertFromHtml-int-java.lang.String-com.aspose.slides.IExternalResourceResolver-java.lang.String-boolean-}
```
public final ISlide[] insertFromHtml(int index, String htmlText, IExternalResourceResolver resolver, String uri, boolean useSlideWithIndexAsStart)
```


Cria slides a partir de texto HTML e os insere na coleção na posição especificada.

**Parâmetros:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | Posição para inserção. |
| htmlText | java.lang.String | HTML a ser adicionado. |
| resolver | [IExternalResourceResolver](../../com.aspose.slides/iexternalresourceresolver) | Objeto de callback usado para buscar objetos externos. Se este parâmetro for nulo, todos os objetos externos serão ignorados. |
| uri | java.lang.String | URI do HTML especificado. Usado para resolver links relativos. |
| useSlideWithIndexAsStart | boolean | Esta flag determina como iniciar a inserção: a partir de um novo slide ou a partir do slide com o índice especificado. Se **true**, a inserção de dados começará em um espaço vazio no slide com o índice especificado. Se **false**, os dados serão adicionados aos slides criados. |

**Retorna:**
com.aspose.slides.ISlide[] - Slides adicionados.
### insertFromHtml(int index, String htmlText) {#insertFromHtml-int-java.lang.String-}
```
public final ISlide[] insertFromHtml(int index, String htmlText)
```


Cria slides a partir de texto HTML e os insere na coleção na posição especificada.

**Parâmetros:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | Posição para inserção. |
| htmlText | java.lang.String | HTML a ser adicionado. |

**Retorna:**
com.aspose.slides.ISlide[] - Slides adicionados
### insertFromHtml(int index, String htmlText, boolean useSlideWithIndexAsStart) {#insertFromHtml-int-java.lang.String-boolean-}
```
public final ISlide[] insertFromHtml(int index, String htmlText, boolean useSlideWithIndexAsStart)
```


Cria slides a partir de texto HTML e os insere na coleção na posição especificada.

**Parâmetros:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | Posição para inserção. |
| htmlText | java.lang.String | HTML a ser adicionado. |
| useSlideWithIndexAsStart | boolean | Esta flag determina como iniciar a inserção: a partir de um novo slide ou a partir do slide com o índice especificado. Se **true**, a inserção de dados começará em um espaço vazio no slide com o índice especificado. Se **false**, os dados serão adicionados aos slides criados. |

**Retorna:**
com.aspose.slides.ISlide[] - Slides adicionados
### insertFromHtml(int index, InputStream htmlStream, IExternalResourceResolver resolver, String uri) {#insertFromHtml-int-java.io.InputStream-com.aspose.slides.IExternalResourceResolver-java.lang.String-}
```
public final ISlide[] insertFromHtml(int index, InputStream htmlStream, IExternalResourceResolver resolver, String uri)
```


Cria slides a partir de texto HTML e os insere na coleção na posição especificada.

**Parâmetros:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | Posição para inserção. |
| htmlStream | java.io.InputStream | Objeto Stream que será usado como fonte de um arquivo HTML. |
| resolver | [IExternalResourceResolver](../../com.aspose.slides/iexternalresourceresolver) | Objeto de callback usado para buscar objetos externos. Se este parâmetro for nulo, todos os objetos externos serão ignorados. |
| uri | java.lang.String | URI do HTML especificado. Usado para resolver links relativos. |

**Retorna:**
com.aspose.slides.ISlide[] - Slides adicionados.
### insertFromHtml(int index, InputStream htmlStream, IExternalResourceResolver resolver, String uri, boolean useSlideWithIndexAsStart) {#insertFromHtml-int-java.io.InputStream-com.aspose.slides.IExternalResourceResolver-java.lang.String-boolean-}
```
public final ISlide[] insertFromHtml(int index, InputStream htmlStream, IExternalResourceResolver resolver, String uri, boolean useSlideWithIndexAsStart)
```


Cria slides a partir de texto HTML e os insere na coleção na posição especificada.

**Parâmetros:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | Posição para inserção. |
| htmlStream | java.io.InputStream | Objeto Stream que será usado como fonte de um arquivo HTML. |
| resolver | [IExternalResourceResolver](../../com.aspose.slides/iexternalresourceresolver) | Objeto de callback usado para buscar objetos externos. Se este parâmetro for nulo, todos os objetos externos serão ignorados. |
| uri | java.lang.String | URI do HTML especificado. Usado para resolver links relativos. |
| useSlideWithIndexAsStart | boolean | Esta flag determina como iniciar a inserção: a partir de um novo slide ou a partir do slide com o índice especificado. Se **true**, a inserção de dados começará em um espaço vazio no slide com o índice especificado. Se **false**, os dados serão adicionados aos slides criados. |

**Retorna:**
com.aspose.slides.ISlide[] - Slides adicionados.
### insertFromHtml(int index, InputStream htmlStream) {#insertFromHtml-int-java.io.InputStream-}
```
public final ISlide[] insertFromHtml(int index, InputStream htmlStream)
```


Cria slides a partir de texto HTML e os insere na coleção na posição especificada.

**Parâmetros:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | Posição para inserção. |
| htmlStream | java.io.InputStream | Objeto Stream que será usado como fonte de um arquivo HTML. |

**Retorna:**
com.aspose.slides.ISlide[] - Slides adicionados
### insertFromHtml(int index, InputStream htmlStream, boolean useSlideWithIndexAsStart) {#insertFromHtml-int-java.io.InputStream-boolean-}
```
public final ISlide[] insertFromHtml(int index, InputStream htmlStream, boolean useSlideWithIndexAsStart)
```


Cria slides a partir de texto HTML e os insere na coleção na posição especificada.

**Parâmetros:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | Posição para inserção. |
| htmlStream | java.io.InputStream | Objeto Stream que será usado como fonte de um arquivo HTML. |
| useSlideWithIndexAsStart | boolean | Esta flag determina como iniciar a inserção: a partir de um novo slide ou a partir do slide com o índice especificado. Se **true**, a inserção de dados começará em um espaço vazio no slide com o índice especificado. Se **false**, os dados serão adicionados aos slides criados. |

**Retorna:**
com.aspose.slides.ISlide[] - Slides adicionados
### copyTo(System.Array array, int index) {#copyTo-com.aspose.ms.System.Array-int-}
```
public final void copyTo(System.Array array, int index)
```


Copia todos os elementos da coleção para o array especificado.

**Parâmetros:**
| Parameter | Type | Description |
| --- | --- | --- |
| array | com.aspose.ms.System.Array | Array de destino. |
| index | int | Índice inicial no array de destino. |

### isSynchronized() {#isSynchronized--}
```
public            



```


Retorna um valor indicando se o acesso à coleção é sincronizado (thread-safe). Somente leitura boolean.

**Retorna:**
boolean
### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```


Retorna a raiz de sincronização. Somente leitura Object.

**Retorna:**
java.lang.Object