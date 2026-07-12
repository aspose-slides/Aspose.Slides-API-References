---
title: MasterSlideCollection
second_title: Aspose.Slides para Android via Referência da API Java
description: Representa uma coleção de slides mestres.
type: docs
url: /pt/com.aspose.slides/masterslidecollection/
---
**Herança:**
java.lang.Object, com.aspose.slides.DomObject

**Todas as Interfaces Implementadas:**
[com.aspose.slides.IMasterSlideCollection](../../com.aspose.slides/imasterslidecollection)
```
public final class MasterSlideCollection extends DomObject<Presentation> implements IMasterSlideCollection
```

Representa uma coleção de slides mestres.
## Methods

| Método | Descrição |
| --- | --- |
| [size()](#size--) | Obtém o número de elementos realmente contidos na coleção. |
| [get_Item(int index)](#get-Item-int-) | Obtém o elemento no índice especificado. |
| [remove(IMasterSlide value)](#remove-com.aspose.slides.IMasterSlide-) | Remove a primeira ocorrência de um objeto específico da coleção. |
| [removeAt(int index)](#removeAt-int-) | Remove o elemento no índice especificado da coleção. |
| [removeUnused(boolean ignorePreserveField)](#removeUnused-boolean-) | Remove slides mestres não usados. |
| [addClone(IMasterSlide sourceMaster)](#addClone-com.aspose.slides.IMasterSlide-) | Adiciona uma cópia de um slide mestre especificado ao final da coleção. |
| [insertClone(int index, IMasterSlide sourceMaster)](#insertClone-int-com.aspose.slides.IMasterSlide-) | Insere uma cópia de um slide mestre especificado na posição especificada da coleção. |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | Copia todos os elementos da coleção para o array especificado. |
| [isSynchronized()](#isSynchronized--) | Retorna um valor indicando se o acesso à coleção está sincronizado (thread-safe). |
| [getSyncRoot()](#getSyncRoot--) | Retorna uma raiz de sincronização. |
| [iterator()](#iterator--) | Retorna um enumerador que itera sobre a coleção. |
| [iteratorJava()](#iteratorJava--) | Retorna um iterador java para a coleção inteira. |
### size() {#size--}
```
public final int size()
```

Obtém o número de elementos realmente contidos na coleção. Somente leitura int.

**Retorna:**
int
### get_Item(int index) {#get-Item-int-}
```
public final IMasterSlide get_Item(int index)
```

Obtém o elemento no índice especificado. Somente leitura [MasterSlide](../../com.aspose.slides/masterslide).

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| index | int |  |

**Retorna:**
[IMasterSlide](../../com.aspose.slides/imasterslide)
### remove(IMasterSlide value) {#remove-com.aspose.slides.IMasterSlide-}
```
public final void remove(IMasterSlide value)
```

Remove a primeira ocorrência de um objeto específico da coleção.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | [IMasterSlide](../../com.aspose.slides/imasterslide) | O slide mestre a ser removido da coleção. |

### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```

Remove o elemento no índice especificado da coleção.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| index | int | O índice baseado em zero do elemento a ser removido.

--------------------

Para evitar o lançamento de PptxEditException, verifique a propriedade HasDependingSlides do mestre antes. |

### removeUnused(boolean ignorePreserveField) {#removeUnused-boolean-}
```
public final void removeUnused(boolean ignorePreserveField)
```

Remove slides mestres não usados.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| ignorePreserveField | boolean | Determina se este método deve remover mestres não usados mesmo se sua propriedade [MasterSlide.getPreserve](../../com.aspose.slides/masterslide\#getPreserve)/[MasterSlide.setPreserve(boolean)](../../com.aspose.slides/masterslide\#setPreserve-boolean-) estiver definida como true. |

### addClone(IMasterSlide sourceMaster) {#addClone-com.aspose.slides.IMasterSlide-}
```
public final IMasterSlide addClone(IMasterSlide sourceMaster)
```

Adiciona uma cópia de um slide mestre especificado ao final da coleção. Slides de layout vinculados também serão copiados.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| sourceMaster | [IMasterSlide](../../com.aspose.slides/imasterslide) | Slide a ser clonado. |

**Retorna:**
[IMasterSlide](../../com.aspose.slides/imasterslide) - Slide adicionado.
### insertClone(int index, IMasterSlide sourceMaster) {#insertClone-int-com.aspose.slides.IMasterSlide-}
```
public final IMasterSlide insertClone(int index, IMasterSlide sourceMaster)
```

Insere uma cópia de um slide mestre especificado na posição especificada da coleção. Slides de layout vinculados também serão copiados.

--------------------

> ```
> O exemplo abaixo mostra como clonar um slide mestre em outra apresentação PowerPoint.
>  
>  // Instanciar a classe Presentation para carregar o arquivo da apresentação fonte
>  Presentation srcPres = new Presentation("CloneToAnotherPresentationWithMaster.pptx");
>  try {
>      // Instanciar a classe Presentation para a apresentação de destino (onde o slide será clonado)
>      Presentation destPres = new Presentation();
>      try {
>          // Instanciar ISlide a partir da coleção de slides na apresentação fonte juntamente com
>          // Slide mestre
>          ISlide SourceSlide = srcPres.getSlides().get_Item(0);
>          IMasterSlide SourceMaster = SourceSlide.getLayoutSlide().getMasterSlide();
>          // Obter slides mestres da apresentação de destino
>          IMasterSlideCollection masters = destPres.getMasters();
>          // Clonar o slide mestre desejado da apresentação fonte para a coleção de mestres na
>          // Apresentação de destino
>          IMasterSlide iSlide = masters.addClone(SourceMaster);
>          // Coleção de slides na apresentação de destino
>          ISlideCollection slds = destPres.getSlides();
>          // Clonar o slide fonte para a coleção de slides de destino.
>          slds.addClone(SourceSlide, iSlide, true);
>          // Salvar a apresentação de destino no disco
>          destPres.save("CloneToAnotherPresentationWithMaster_out.pptx", SaveFormat.Pptx);
>      } finally {
>          if (destPres != null) destPres.dispose();
>      }
>  } finally {
>      if (srcPres != null) srcPres.dispose();
>  }
> ```


**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| index | int | Índice do novo slide. |
| sourceMaster | [IMasterSlide](../../com.aspose.slides/imasterslide) | Slide a ser clonado. |

**Retorna:**
[IMasterSlide](../../com.aspose.slides/imasterslide) - Slide mestre inserido.
### copyTo(System.Array array, int index) {#copyTo-com.aspose.ms.System.Array-int-}
```
public final void copyTo(System.Array array, int index)
```

Copia todos os elementos da coleção para o array especificado.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| array | com.aspose.ms.System.Array | Array de destino. |
| index | int | Índice inicial no array de destino. |

### isSynchronized() {#isSynchronized--}
```
public final boolean isSynchronized()
```

Retorna um valor indicando se o acesso à coleção está sincronizado (thread-safe). Somente leitura boolean.

**Retorna:**
boolean
### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```

Retorna uma raiz de sincronização. Somente leitura Object.

**Retorna:**
java.lang.Object
### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IMasterSlide> iterator()
```

Retorna um enumerador que itera sobre a coleção.

**Retorna:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IMasterSlide> - Um IGenericEnumerator que pode ser usado para iterar sobre a coleção.
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IMasterSlide> iteratorJava()
```

Retorna um iterador java para a coleção inteira.

**Retorna:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IMasterSlide> - Um java.util.Iterator para a coleção inteira.