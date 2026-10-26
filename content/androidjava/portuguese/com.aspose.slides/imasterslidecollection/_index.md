---
title: IMasterSlideCollection
second_title: Aspose.Slides para Android via Referência da API Java
description: Representa uma coleção de slides mestre.
type: docs
url: /pt/com.aspose.slides/imasterslidecollection/
---
**Todas as Interfaces Implementadas:**
com.aspose.slides.IGenericCollection
```
public interface IMasterSlideCollection extends IGenericCollection<IMasterSlide>
```

Representa uma coleção de slides mestre.
## Métodos

| Método | Descrição |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Obtém o elemento no índice especificado. |
| [remove(IMasterSlide value)](#remove-com.aspose.slides.IMasterSlide-) | Remove a primeira ocorrência de um objeto específico da coleção. |
| [removeAt(int index)](#removeAt-int-) | Remove o elemento no índice especificado da coleção. |
| [removeUnused(boolean ignorePreserveField)](#removeUnused-boolean-) | Remove slides mestre não utilizados. |
| [addClone(IMasterSlide sourceMaster)](#addClone-com.aspose.slides.IMasterSlide-) | Adiciona uma cópia de um slide mestre especificado ao final da coleção. |
| [insertClone(int index, IMasterSlide sourceMaster)](#insertClone-int-com.aspose.slides.IMasterSlide-) | Insere uma cópia de um slide mestre especificado na posição especificada da coleção. |
### get_Item(int index) {#get-Item-int-}
```
public abstract IMasterSlide get_Item(int index)
```

Obtém o elemento no índice especificado. Somente leitura [IMasterSlide](../../com.aspose.slides/imasterslide).

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| index | int |  |

**Retorno:**
[IMasterSlide](../../com.aspose.slides/imasterslide)
### remove(IMasterSlide value) {#remove-com.aspose.slides.IMasterSlide-}
```
public abstract void remove(IMasterSlide value)
```

Remove a primeira ocorrência de um objeto específico da coleção.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | [IMasterSlide](../../com.aspose.slides/imasterslide) | O slide mestre a ser removido da coleção. |

### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```

Remove o elemento no índice especificado da coleção.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| index | int | O índice baseado em zero do elemento a ser removido. |

### removeUnused(boolean ignorePreserveField) {#removeUnused-boolean-}
```
public abstract void removeUnused(boolean ignorePreserveField)
```

Remove slides mestre não utilizados.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| ignorePreserveField | boolean | Determina se este método deve remover um mestre não usado mesmo que sua propriedade [IMasterSlide.getPreserve](../../com.aspose.slides/imasterslide\#getPreserve)/[IMasterSlide.setPreserve(boolean)](../../com.aspose.slides/imasterslide\#setPreserve-boolean-) esteja definida como true. |

### addClone(IMasterSlide sourceMaster) {#addClone-com.aspose.slides.IMasterSlide-}
```
public abstract IMasterSlide addClone(IMasterSlide sourceMaster)
```

Adiciona uma cópia de um slide mestre especificado ao final da coleção. Slides de layout vinculados também serão copiados.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| sourceMaster | [IMasterSlide](../../com.aspose.slides/imasterslide) | Slide a ser clonado. |

**Retorno:**
[IMasterSlide](../../com.aspose.slides/imasterslide) - Slide adicionado.
### insertClone(int index, IMasterSlide sourceMaster) {#insertClone-int-com.aspose.slides.IMasterSlide-}
```
public abstract IMasterSlide insertClone(int index, IMasterSlide sourceMaster)
```

Insere uma cópia de um slide mestre especificado na posição especificada da coleção. Slides de layout vinculados também serão copiados.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| index | int | Índice do novo slide. |
| sourceMaster | [IMasterSlide](../../com.aspose.slides/imasterslide) | Slide a ser clonado. |

**Retorno:**
[IMasterSlide](../../com.aspose.slides/imasterslide) - Slide mestre inserido.