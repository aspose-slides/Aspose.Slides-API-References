---
title: IBehaviorPropertyCollection
second_title: Aspose.Slides para Android via Referência da API Java
description: Representa propriedades de temporização para o comportamento do efeito.
type: docs
url: /pt/com.aspose.slides/ibehaviorpropertycollection/
---
**Todas as Interfaces Implementadas:**
com.aspose.ms.System.Collections.Generic.IGenericList
```
public interface IBehaviorPropertyCollection extends System.Collections.Generic.IGenericList<IBehaviorProperty>
```

Representa propriedades de temporização para o comportamento do efeito.
## Métodos

| Método | Descrição |
| --- | --- |
| [add(String propertyValue)](#add-java.lang.String-) | Adiciona uma nova propriedade à coleção. |
| [indexOf(String propertyValue)](#indexOf-java.lang.String-) | Determina o índice de um item específico pelo valor da propriedade na Lista. |
| [insert(int index, String propertyValue)](#insert-int-java.lang.String-) | Insere uma nova propriedade (com o valor de propriedade especificado) na coleção no índice especificado. |
| [remove(String propertyValue)](#remove-java.lang.String-) | Remove a propriedade especificada da coleção. |
| [contains(String propertyValue)](#contains-java.lang.String-) | Determina se o [IGenericCollection](../../com.aspose.slides/igenericcollection) contém um valor específico. |
### add(String propertyValue) {#add-java.lang.String-}
```
public abstract void add(String propertyValue)
```

Adiciona uma nova propriedade à coleção.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| propertyValue | java.lang.String | Valor da propriedade a ser adicionada. |

### indexOf(String propertyValue) {#indexOf-java.lang.String-}
```
public abstract int indexOf(String propertyValue)
```

Determina o índice de um item específico pelo valor da propriedade na Lista.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| propertyValue | java.lang.String | valor da propriedade |

**Retorna:**
int - O índice da propriedade com o valor especificado
### insert(int index, String propertyValue) {#insert-int-java.lang.String-}
```
public abstract void insert(int index, String propertyValue)
```

Insere uma nova propriedade (com o valor de propriedade especificado) na coleção no índice especificado.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| index | int | Índice onde uma nova propriedade deve ser inserida. |
| propertyValue | java.lang.String | Valor da propriedade a ser adicionada. |

### remove(String propertyValue) {#remove-java.lang.String-}
```
public abstract boolean remove(String propertyValue)
```

Remove a propriedade especificada da coleção.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| propertyValue | java.lang.String | Valor da propriedade a ser removida. |

**Retorna:**
boolean - Verdadeiro se uma propriedade for removida com sucesso
### contains(String propertyValue) {#contains-java.lang.String-}
```
public abstract boolean contains(String propertyValue)
```

Determina se o [IGenericCollection](../../com.aspose.slides/igenericcollection) contém um valor específico.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| propertyValue | java.lang.String | Valor da propriedade a ser localizada no [IGenericCollection](../../com.aspose.slides/igenericcollection). |

**Retorna:**
boolean - verdadeiro se propertyValue for encontrado no [IGenericCollection](../../com.aspose.slides/igenericcollection); caso contrário, falso.