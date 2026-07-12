---
title: ISlideCollection
second_title: Aspose.Slides para Android via Referência da API Java
description: Representa uma coleção de slides.
type: docs
url: /pt/com.aspose.slides/islidecollection/
---
**Todas as Interfaces Implementadas:**
com.aspose.slides.IGenericCollection
```
public interface ISlideCollection extends IGenericCollection<ISlide>
```

Representa uma coleção de slides.
## Métodos

| Método | Descrição |
| --- | --- |
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
| [toArray()](#toArray--) | Cria e devolve um array com todos os slides. |
| [toArray(int startIndex, int count)](#toArray-int-int-) | Cria e devolve um array com todos os slides do intervalo especificado. |
| [reorder(int index, ISlide slide)](#reorder-int-com.aspose.slides.ISlide-) | Move o slide da coleção para a posição especificada. |
| [reorder(int index, ISlide[] slides)](#reorder-int-com.aspose.slides.ISlide...-) | Moves slides from the collection to the specified position. |
| [indexOf(ISlide slide)](#indexOf-com.aspose.slides.ISlide-) | Retorna o índice do slide especificado na coleção. |
| [addFromPdf(String path)](#addFromPdf-java.lang.String-) | Cria slides a partir do documento PDF e os adiciona ao final da coleção. |
| [addFromPdf(String path, PdfImportOptions pdfImportOptions)](#addFromPdf-java.lang.String-com.aspose.slides.PdfImportOptions-) | Cria slides a partir do documento PDF e os adiciona ao final da coleção considerando as opções de importação de PDF. |
| [addFromPdf(InputStream pdfStream, PdfImportOptions pdfImportOptions)](#addFromPdf-java.io.InputStream-com.aspose.slides.PdfImportOptions-) | Cria slides a partir do documento PDF e os adiciona ao final da coleção. |
| [addFromPdf(InputStream pdfStream)](#addFromPdf-java.io.InputStream-) | Cria slides a partir do documento PDF e os adiciona ao final da coleção. |
| [addFromHtml(String htmlText, IExternalResourceResolver resolver, String uri)](#addFromHtml-java.lang.String-com.aspose.slides.IExternalResourceResolver-java.lang.String-) | Cria slides a partir de texto HTML e os adiciona ao final da coleção. |
| [addFromHtml(String htmlText)](#addFromHtml-java.lang.String-) | Cria slides a partir de texto HTML e os adiciona ao final da coleção. |
| [addFromHtml(InputStream htmlStream, IExternalResourceResolver resolver, String uri)](#addFromHtml-java.io.InputStream-com.aspose.slides.IExternalResourceResolver-java.lang.String-) | Cria slides a partir de texto HTML e os adiciona ao final da coleção. |
| [addFromHtml(InputStream htmlStream)](#addFromHtml-java.io.InputStream-) | Cria slides a partir de texto HTML e os adiciona ao final da coleção. |
| [insertFromHtml(int index, String htmlText, IExternalResourceResolver resolver, String uri)](#insertFromHtml-int-java.lang.String-com.aspose.slides.IExternalResourceResolver-java.lang.String-) | Cria slides a partir de texto HTML e os insere na coleção na posição especificada. |
| [insertFromHtml(int index, String htmlText)](#insertFromHtml-int-java.lang.String-) | Cria slides a partir de texto HTML e os insere na coleção na posição especificada. |
| [insertFromHtml(int index, InputStream htmlStream, IExternalResourceResolver resolver, String uri)](#insertFromHtml-int-java.io.InputStream-com.aspose.slides.IExternalResourceResolver-java.lang.String-) | Cria slides a partir de texto HTML e os insere na coleção na posição especificada. |
| [insertFromHtml(int index, InputStream htmlStream)](#insertFromHtml-int-java.io.InputStream-) | Cria slides a partir de texto HTML e os insere na coleção na posição especificada. |
| [insertFromHtml(int index, String htmlText, boolean useSlideWithIndexAsStart)](#insertFromHtml-int-java.lang.String-boolean-) | Cria slides a partir de texto HTML e os insere na coleção na posição especificada. |
| [insertFromHtml(int index, String htmlText, IExternalResourceResolver resolver, String uri, boolean useSlideWithIndexAsStart)](#insertFromHtml-int-java.lang.String-com.aspose.slides.IExternalResourceResolver-java.lang.String-boolean-) | Cria slides a partir de texto HTML e os insere na coleção na posição especificada. |
| [insertFromHtml(int index, InputStream htmlStream, boolean useSlideWithIndexAsStart)](#insertFromHtml-int-java.io.InputStream-boolean-) | Cria slides a partir de texto HTML e os insere na coleção na posição especificada. |
| [insertFromHtml(int index, InputStream htmlStream, IExternalResourceResolver resolver, String uri, boolean useSlideWithIndexAsStart)](#insertFromHtml-int-java.io.InputStream-com.aspose.slides.IExternalResourceResolver-java.lang.String-boolean-) | Cria slides a partir de texto HTML e os insere na coleção na posição especificada. |
### get_Item(int index) {#get-Item-int-}
```
public abstract ISlide get_Item(int index)
```

Obtém o elemento no índice especificado. Somente leitura [ISlide](../../com.aspose.slides/islide).

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| index | int |  |

**Retorna:**
[ISlide](../../com.aspose.slides/islide)
### addClone(ISlide sourceSlide) {#addClone-com.aspose.slides.ISlide-}
```
public abstract ISlide addClone(ISlide sourceSlide)
```

Adiciona uma cópia de um slide especificado ao final da coleção.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| sourceSlide | [ISlide](../../com.aspose.slides/islide) | Slide a ser clonado. |

--------------------

Ao clonar um slide entre apresentações diferentes, o master do slide também pode ser clonado. Um registro interno é usado para rastrear masters clonados automaticamente para evitar a criação de múltiplos clones do mesmo master slide. A clonagem manual de masters não será nem impedida nem registrada. Se precisar de mais controle sobre o processo de clonagem, use \#addClone(ISlide,ILayoutSlide).addClone(ISlide,ILayoutSlide) ou \#addClone(ISlide,IMasterSlide,boolean).addClone(ISlide,IMasterSlide,boolean) para clonar slides, [IGlobalLayoutSlideCollection.addClone(ILayoutSlide)](../../com.aspose.slides/igloballayoutslidecollection\#addClone-ILayoutSlide-) ou [IGlobalLayoutSlideCollection.addClone(ILayoutSlide,IMasterSlide)](../../com.aspose.slides/igloballayoutslidecollection\#addClone-ILayoutSlide-IMasterSlide-) para clonar layouts e [IMasterSlideCollection.addClone(IMasterSlide)](../../com.aspose.slides/imasterslidecollection\#addClone-IMasterSlide-) para clonar masters. 

**Retorna:**
[ISlide](../../com.aspose.slides/islide) - Novo slide.
### addClone(ISlide sourceSlide, ISection section) {#addClone-com.aspose.slides.ISlide-com.aspose.slides.ISection-}
```
public abstract ISlide addClone(ISlide sourceSlide, ISection section)
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
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| sourceSlide | [ISlide](../../com.aspose.slides/islide) | Slide a ser clonado. |
| section | [ISection](../../com.aspose.slides/isection) | Seção para o novo slide. |

**Retorna:**
[ISlide](../../com.aspose.slides/islide) - Novo slide.
### insertClone(int index, ISlide sourceSlide) {#insertClone-int-com.aspose.slides.ISlide-}
```
public abstract ISlide insertClone(int index, ISlide sourceSlide)
```

Insere uma cópia de um slide especificado na posição especificada da coleção.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| index | int | Índice do novo slide. |
| sourceSlide | [ISlide](../../com.aspose.slides/islide) | Slide a ser clonado. |

--------------------

Ao clonar um slide entre apresentações diferentes, o master do slide também pode ser clonado. Um registro interno é usado para rastrear masters clonados automaticamente para evitar a criação de múltiplos clones do mesmo master slide. A clonagem manual de masters não será nem impedida nem registrada. Se precisar de mais controle sobre o processo de clonagem, use \#insertClone(int,ISlide,ILayoutSlide).insertClone(int,ISlide,ILayoutSlide) ou \#insertClone(int,ISlide,IMasterSlide,boolean).insertClone(int,ISlide,IMasterSlide,boolean) para clonar slides e [IMasterSlideCollection.addClone(IMasterSlide)](../../com.aspose.slides/imasterslidecollection\#addClone-IMasterSlide-) para clonar masters. 

**Retorna:**
[ISlide](../../com.aspose.slides/islide) - Slide inserido.
### addEmptySlide(ILayoutSlide layout) {#addEmptySlide-com.aspose.slides.ILayoutSlide-}
```
public abstract ISlide addEmptySlide(ILayoutSlide layout)
```

Adiciona um novo slide vazio ao final da coleção.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| layout | [ILayoutSlide](../../com.aspose.slides/ilayoutslide) | Layout para o slide. |

**Retorna:**
[ISlide](../../com.aspose.slides/islide) - Slide adicionado.
### insertEmptySlide(int index, ILayoutSlide layout) {#insertEmptySlide-int-com.aspose.slides.ILayoutSlide-}
```
public abstract ISlide insertEmptySlide(int index, ILayoutSlide layout)
```

Insere uma cópia de um slide especificado na posição especificada da coleção.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| index | int | Índice de um novo slide. |
| layout | [ILayoutSlide](../../com.aspose.slides/ilayoutslide) | Layout para o slide. |

**Retorna:**
[ISlide](../../com.aspose.slides/islide) - Slide inserido.
### addClone(ISlide sourceSlide, ILayoutSlide destLayout) {#addClone-com.aspose.slides.ISlide-com.aspose.slides.ILayoutSlide-}
```
public abstract ISlide addClone(ISlide sourceSlide, ILayoutSlide destLayout)
```

Adiciona uma cópia de um slide especificado ao final da coleção.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| sourceSlide | [ISlide](../../com.aspose.slides/islide) | Slide a ser clonado. |
| destLayout | [ILayoutSlide](../../com.aspose.slides/ilayoutslide) | Layout do slide para o novo slide. |

**Retorna:**
[ISlide](../../com.aspose.slides/islide) - Novo slide.
### insertClone(int index, ISlide sourceSlide, ILayoutSlide destLayout) {#insertClone-int-com.aspose.slides.ISlide-com.aspose.slides.ILayoutSlide-}
```
public abstract ISlide insertClone(int index, ISlide sourceSlide, ILayoutSlide destLayout)
```

Insere uma cópia de um slide especificado na posição especificada da coleção.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| index | int | Índice do novo slide. |
| sourceSlide | [ISlide](../../com.aspose.slides/islide) | Slide a ser clonado. |
| destLayout | [ILayoutSlide](../../com.aspose.slides/ilayoutslide) | Layout do slide para o novo slide. |

**Retorna:**
[ISlide](../../com.aspose.slides/islide) - Slide inserido.
### addClone(ISlide sourceSlide, IMasterSlide destMaster, boolean allowCloneMissingLayout) {#addClone-com.aspose.slides.ISlide-com.aspose.slides.IMasterSlide-boolean-}
```
public abstract ISlide addClone(ISlide sourceSlide, IMasterSlide destMaster, boolean allowCloneMissingLayout)
```

Adiciona uma cópia de um slide fonte especificado ao final da coleção. O layout apropriado será selecionado automaticamente a partir do master especificado (o layout apropriado é o que tem o mesmo Tipo ou Nome do layout do slide fonte). Se não houver layout apropriado, o layout do slide fonte será clonado (se allowCloneMissingLayout for true) ou será lançada uma PptxEditException (se allowCloneMissingLayout for false).

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| sourceSlide | [ISlide](../../com.aspose.slides/islide) | Slide a ser clonado. |
| destMaster | [IMasterSlide](../../com.aspose.slides/imasterslide) | Master slide para o novo slide. |
| allowCloneMissingLayout | boolean | Se não houver layout apropriado no master especificado, o layout do slide fonte será clonado (se allowCloneMissingLayout for true) ou será lançada uma PptxEditException (se allowCloneMissingLayout for false). |

**Retorna:**
[ISlide](../../com.aspose.slides/islide) - Novo slide.
### insertClone(int index, ISlide sourceSlide, IMasterSlide destMaster, boolean allowCloneMissingLayout) {#insertClone-int-com.aspose.slides.ISlide-com.aspose.slides.IMasterSlide-boolean-}
```
public abstract ISlide insertClone(int index, ISlide sourceSlide, IMasterSlide destMaster, boolean allowCloneMissingLayout)
```

Insere uma cópia de um slide fonte especificado na posição especificada da coleção. O layout apropriado será selecionado automaticamente a partir do master especificado (o layout apropriado é o que tem o mesmo Tipo ou Nome do layout do slide fonte). Se não houver layout apropriado, o layout do slide fonte será clonado (se allowCloneMissingLayout for true) ou será lançada uma PptxEditException (se allowCloneMissingLayout for false).

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| index | int | Índice do novo slide. |
| sourceSlide | [ISlide](../../com.aspose.slides/islide) | Slide a ser clonado. |
| destMaster | [IMasterSlide](../../com.aspose.slides/imasterslide) | Master slide para o novo slide. |
| allowCloneMissingLayout | boolean | Se não houver layout apropriado no master especificado, o layout do slide fonte será clonado (se allowCloneMissingLayout for true) ou será lançada uma PptxEditException (se allowCloneMissingLayout for false). |

**Retorna:**
[ISlide](../../com.aspose.slides/islide) - Slide inserido.
### remove(ISlide value) {#remove-com.aspose.slides.ISlide-}
```
public abstract void remove(ISlide value)
```

Remove a primeira ocorrência de um objeto específico da coleção.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | [ISlide](../../com.aspose.slides/islide) | O slide a ser removido da coleção. |

### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```

Remove o elemento no índice especificado da coleção.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| index | int | O índice baseado em zero do elemento a ser removido. |

### toArray() {#toArray--}
```
public abstract ISlide[] toArray()
```

Cria e devolve um array com todos os slides.

**Retorna:**
com.aspose.slides.ISlide[] - Array de [ISlide](../../com.aspose.slides/islide)
### toArray(int startIndex, int count) {#toArray-int-int-}
```
public abstract ISlide[] toArray(int startIndex, int count)
```

Cria e devolve um array com todos os slides do intervalo especificado.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| startIndex | int | Índice do primeiro slide a ser adicionado. |
| count | int | Número de slides a ser adicionado. |

**Retorna:**
com.aspose.slides.ISlide[] - Array de [ISlide](../../com.aspose.slides/islide)
### reorder(int index, ISlide slide) {#reorder-int-com.aspose.slides.ISlide-}
```
public abstract void reorder(int index, ISlide slide)
```

Move o slide da coleção para a posição especificada.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| index | int | Índice de destino. |
| slide | [ISlide](../../com.aspose.slides/islide) | Slide a ser movido. |

### reorder(int index, ISlide[] slides) {#reorder-int-com.aspose.slides.ISlide...-}
```
public abstract void reorder(int index, ISlide[] slides)
```

Moves slides from the collection to the specified position. Slides will be placed starting from index in order they appear in list.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| index | int | Índice de destino. |
| slides | [ISlide\[\]](../../com.aspose.slides/islide) | Slides a ser movidos. |

### indexOf(ISlide slide) {#indexOf-com.aspose.slides.ISlide-}
```
public abstract int indexOf(ISlide slide)
```

Retorna o índice do slide especificado na coleção.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| slide | [ISlide](../../com.aspose.slides/islide) | Slide a ser encontrado. |

**Retorna:**
int - Índice do slide ou -1 se o slide não pertencer a esta coleção.
### addFromPdf(String path) {#addFromPdf-java.lang.String-}
```
public abstract ISlide[] addFromPdf(String path)
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
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| path | java.lang.String | Um caminho para o documento PDF |

**Retorna:**
com.aspose.slides.ISlide[] - Slides adicionados
### addFromPdf(String path, PdfImportOptions pdfImportOptions) {#addFromPdf-java.lang.String-com.aspose.slides.PdfImportOptions-}
```
public abstract ISlide[] addFromPdf(String path, PdfImportOptions pdfImportOptions)
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
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| path | java.lang.String | Um caminho para o documento PDF |
| pdfImportOptions | [PdfImportOptions](../../com.aspose.slides/pdfimportoptions) | Opções para importação de PDF |

**Retorna:**
com.aspose.slides.ISlide[] - Slides adicionados
### addFromPdf(InputStream pdfStream, PdfImportOptions pdfImportOptions) {#addFromPdf-java.io.InputStream-com.aspose.slides.PdfImportOptions-}
```
public abstract ISlide[] addFromPdf(InputStream pdfStream, PdfImportOptions pdfImportOptions)
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
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| pdfStream | java.io.InputStream | Um fluxo que será usado como fonte do documento PDF |
| pdfImportOptions | [PdfImportOptions](../../com.aspose.slides/pdfimportoptions) | Opções para importação de PDF |

**Retorna:**
com.aspose.slides.ISlide[] - Slides adicionados
### addFromPdf(InputStream pdfStream) {#addFromPdf-java.io.InputStream-}
```
public abstract ISlide[] addFromPdf(InputStream pdfStream)
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
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| pdfStream | java.io.InputStream | Um fluxo que será usado como fonte do documento PDF |

**Retorna:**
com.aspose.slides.ISlide[] - Slides adicionados
### addFromHtml(String htmlText, IExternalResourceResolver resolver, String uri) {#addFromHtml-java.lang.String-com.aspose.slides.IExternalResourceResolver-java.lang.String-}
```
public abstract ISlide[] addFromHtml(String htmlText, IExternalResourceResolver resolver, String uri)
```

Cria slides a partir de texto HTML e os adiciona ao final da coleção.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| htmlText | java.lang.String | HTML a ser adicionado. |
| resolver | [IExternalResourceResolver](../../com.aspose.slides/iexternalresourceresolver) | Um objeto de callback usado para buscar objetos externos. Se este parâmetro for nulo, todos os objetos externos serão ignorados. |
| uri | java.lang.String | Um URI do HTML especificado. Usado para resolver links relativos. |

**Retorna:**
com.aspose.slides.ISlide[] - Slides adicionados.
### addFromHtml(String htmlText) {#addFromHtml-java.lang.String-}
```
public abstract ISlide[] addFromHtml(String htmlText)
```

Cria slides a partir de texto HTML e os adiciona ao final da coleção.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| htmlText | java.lang.String | HTML a ser adicionado. |

**Retorna:**
com.aspose.slides.ISlide[] - Slides adicionados
### addFromHtml(InputStream htmlStream, IExternalResourceResolver resolver, String uri) {#addFromHtml-java.io.InputStream-com.aspose.slides.IExternalResourceResolver-java.lang.String-}
```
public abstract ISlide[] addFromHtml(InputStream htmlStream, IExternalResourceResolver resolver, String uri)
```

Cria slides a partir de texto HTML e os adiciona ao final da coleção.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| htmlStream | java.io.InputStream | Um objeto Stream que será usado como fonte de um arquivo HTML. |
| resolver | [IExternalResourceResolver](../../com.aspose.slides/iexternalresourceresolver) | Um objeto de callback usado para buscar objetos externos. Se este parâmetro for nulo, todos os objetos externos serão ignorados. |
| uri | java.lang.String | Um URI do HTML especificado. Usado para resolver links relativos. |

**Retorna:**
com.aspose.slides.ISlide[] - Slides adicionados.
### addFromHtml(InputStream htmlStream) {#addFromHtml-java.io.InputStream-}
```
public abstract ISlide[] addFromHtml(InputStream htmlStream)
```

Cria slides a partir de texto HTML e os adiciona ao final da coleção.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| htmlStream | java.io.InputStream | Um objeto Stream que será usado como fonte de um arquivo HTML. |

**Retorna:**
com.aspose.slides.ISlide[] - Slides adicionados
### insertFromHtml(int index, String htmlText, IExternalResourceResolver resolver, String uri) {#insertFromHtml-int-java.lang.String-com.aspose.slides.IExternalResourceResolver-java.lang.String-}
```
public abstract ISlide[] insertFromHtml(int index, String htmlText, IExternalResourceResolver resolver, String uri)
```

Cria slides a partir de texto HTML e os insere na coleção na posição especificada.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| index | int | Posição para inserir. |
| htmlText | java.lang.String | HTML a ser adicionado. |
| resolver | [IExternalResourceResolver](../../com.aspose.slides/iexternalresourceresolver) | Um objeto de callback usado para buscar objetos externos. Se este parâmetro for nulo, todos os objetos externos serão ignorados. |
| uri | java.lang.String | Um URI do HTML especificado. Usado para resolver links relativos. |

**Retorna:**
com.aspose.slides.ISlide[] - Slides adicionados.
### insertFromHtml(int index, String htmlText) {#insertFromHtml-int-java.lang.String-}
```
public abstract ISlide[] insertFromHtml(int index, String htmlText)
```

Cria slides a partir de texto HTML e os insere na coleção na posição especificada.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| index | int | Posição para inserir. |
| htmlText | java.lang.String | HTML a ser adicionado. |

**Retorna:**
com.aspose.slides.ISlide[] - Slides adicionados
### insertFromHtml(int index, InputStream htmlStream, IExternalResourceResolver resolver, String uri) {#insertFromHtml-int-java.io.InputStream-com.aspose.slides.IExternalResourceResolver-java.lang.String-}
```
public abstract ISlide[] insertFromHtml(int index, InputStream htmlStream, IExternalResourceResolver resolver, String uri)
```

Cria slides a partir de texto HTML e os insere na coleção na posição especificada.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| index | int | Posição para inserir. |
| htmlStream | java.io.InputStream | Um objeto Stream que será usado como fonte de um arquivo HTML. |
| resolver | [IExternalResourceResolver](../../com.aspose.slides/iexternalresourceresolver) | Um objeto de callback usado para buscar objetos externos. Se este parâmetro for nulo, todos os objetos externos serão ignorados. |
| uri | java.lang.String | Um URI do HTML especificado. Usado para resolver links relativos. |

**Retorna:**
com.aspose.slides.ISlide[] - Slides adicionados.
### insertFromHtml(int index, InputStream htmlStream) {#insertFromHtml-int-java.io.InputStream-}
```
public abstract ISlide[] insertFromHtml(int index, InputStream htmlStream)
```

Cria slides a partir de texto HTML e os insere na coleção na posição especificada.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| index | int | Posição para inserir. |
| htmlStream | java.io.InputStream | Um objeto Stream que será usado como fonte de um arquivo HTML. |

**Retorna:**
com.aspose.slides.ISlide[] - Slides adicionados
### insertFromHtml(int index, String htmlText, boolean useSlideWithIndexAsStart) {#insertFromHtml-int-java.lang.String-boolean-}
```
public abstract ISlide[] insertFromHtml(int index, String htmlText, boolean useSlideWithIndexAsStart)
```

Cria slides a partir de texto HTML e os insere na coleção na posição especificada.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| index | int | Posição para inserir. |
| htmlText | java.lang.String | HTML a ser adicionado. |
| useSlideWithIndexAsStart | boolean | Esta bandeira determina como iniciar a inserção: a partir de um novo slide ou a partir do slide com o índice especificado. Se **true**, a inserção de dados começará em um espaço vazio no slide com o índice especificado. Se **false**, os dados serão adicionados aos slides criados. |

**Retorna:**
com.aspose.slides.ISlide[] - Slides adicionados
### insertFromHtml(int index, String htmlText, IExternalResourceResolver resolver, String uri, boolean useSlideWithIndexAsStart) {#insertFromHtml-int-java.lang.String-com.aspose.slides.IExternalResourceResolver-java.lang.String-boolean-}
```
public abstract ISlide[] insertFromHtml(int index, String htmlText, IExternalResourceResolver resolver, String uri, boolean useSlideWithIndexAsStart)
```

Cria slides a partir de texto HTML e os insere na coleção na posição especificada.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| index | int | Posição para inserir. |
| htmlText | java.lang.String | HTML a ser adicionado. |
| resolver | [IExternalResourceResolver](../../com.aspose.slides/iexternalresourceresolver) | Um objeto de callback usado para buscar objetos externos. Se este parâmetro for nulo, todos os objetos externos serão ignorados. |
| uri | java.lang.String | Um URI do HTML especificado. Usado para resolver links relativos. |
| useSlideWithIndexAsStart | boolean | Esta bandeira determina como iniciar a inserção: a partir de um novo slide ou a partir do slide com o índice especificado. Se **true**, a inserção de dados começará em um espaço vazio no slide com o índice especificado. Se **false**, os dados serão adicionados aos slides criados. |

**Retorna:**
com.aspose.slides.ISlide[] - Slides adicionados.
### insertFromHtml(int index, InputStream htmlStream, boolean useSlideWithIndexAsStart) {#insertFromHtml-int-java.io.InputStream-boolean-}
```
public abstract ISlide[] insertFromHtml(int index, InputStream htmlStream, boolean useSlideWithIndexAsStart)
```

Cria slides a partir de texto HTML e os insere na coleção na posição especificada.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| index | int | Posição para inserir. |
| htmlStream | java.io.InputStream | Um objeto Stream que será usado como fonte de um arquivo HTML. |
| useSlideWithIndexAsStart | boolean | Esta bandeira determina como iniciar a inserção: a partir de um novo slide ou a partir do slide com o índice especificado. Se **true**, a inserção de dados começará em um espaço vazio no slide com o índice especificado. Se **false**, os dados serão adicionados aos slides criados. |

**Retorna:**
com.aspose.slides.ISlide[] - Slides adicionados
### insertFromHtml(int index, InputStream htmlStream, IExternalResourceResolver resolver, String uri, boolean useSlideWithIndexAsStart) {#insertFromHtml-int-java.io.InputStream-com.aspose.slides.IExternalResourceResolver-java.lang.String-boolean-}
```
public abstract ISlide[] insertFromHtml(int index, InputStream htmlStream, IExternalResourceResolver resolver, String uri, boolean useSlideWithIndexAsStart)
```

Cria slides a partir de texto HTML e os insere na coleção na posição especificada.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| index | int | Posição para inserir. |
| htmlStream | java.io.InputStream | Um objeto Stream que será usado como fonte de um arquivo HTML. |
| resolver | [IExternalResourceResolver](../../com.aspose.slides/iexternalresourceresolver) | Um objeto de callback usado para buscar objetos externos. Se este parâmetro for nulo, todos os objetos externos serão ignorados. |
| uri | java.lang.String | Um URI do HTML especificado. Usado para resolver links relativos. |
| useSlideWithIndexAsStart | boolean | Esta bandeira determina como iniciar a inserção: a partir de um novo slide ou a partir do slide com o índice especificado. Se **true**, a inserção de dados começará em um espaço vazio no slide com o índice especificado. Se **false**, os dados serão adicionados aos slides criados. |

**Retorna:**
com.aspose.slides.ISlide[] - Slides adicionados.