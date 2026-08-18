---
title: ISensitivityLabelCollection
second_title: Referência da API Aspose.Slides para Java
description: Representa uma coleção de rótulos de sensibilidade aplicados ao documento.
type: docs
url: /pt/com.aspose.slides/isensitivitylabelcollection/
---
**Todas as Interfaces Implementadas:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerable
```
public interface ISensitivityLabelCollection extends System.Collections.Generic.IGenericEnumerable<ISensitivityLabel>
```

Representa uma coleção de rótulos de sensibilidade aplicados ao documento.
## Métodos

| Método | Descrição |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Retorna o rótulo de sensibilidade pelo índice. |
| [add(String id, UUID siteId, boolean isEnabled, int methodType)](#add-java.lang.String-java.util.UUID-boolean-int-) | Adiciona o rótulo de sensibilidade ao final da coleção. |
| [add(ISensitivityLabel label)](#add-com.aspose.slides.ISensitivityLabel-) | Adiciona um SensitivityLabel à coleção. |
| [removeAt(int index)](#removeAt-int-) | Remove o rótulo de sensibilidade no índice especificado. |
| [clear()](#clear--) | Remove todos os elementos da coleção. |
| [getCount()](#getCount--) | Obtém o número de todos os elementos da coleção. |
### get_Item(int index) {#get-Item-int-}
```
public abstract ISensitivityLabel get_Item(int index)
```

Retorna o rótulo de sensibilidade pelo índice. Somente leitura [ISensitivityLabel](../../com.aspose.slides/isensitivitylabel).

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| index | int |  |

**Retorna:**
[ISensitivityLabel](../../com.aspose.slides/isensitivitylabel)
### add(String id, UUID siteId, boolean isEnabled, int methodType) {#add-java.lang.String-java.util.UUID-boolean-int-}
```
public abstract ISensitivityLabel add(String id, UUID siteId, boolean isEnabled, int methodType)
```

Adiciona o rótulo de sensibilidade ao final da coleção.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| id | java.lang.String | O id do rótulo de sensibilidade. |
| siteId | java.util.UUID | O identificador do site do Azure Active Directory (Azure AD). |
| isEnabled | boolean | Indicador que indica se o rótulo de sensibilidade está habilitado. |
| methodType | int | O método de atribuição para o rótulo de sensibilidade. |

**Retorna:**
[ISensitivityLabel](../../com.aspose.slides/isensitivitylabel)
### add(ISensitivityLabel label) {#add-com.aspose.slides.ISensitivityLabel-}
```
public abstract int add(ISensitivityLabel label)
```

Adiciona um SensitivityLabel à coleção.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| label | [ISensitivityLabel](../../com.aspose.slides/isensitivitylabel) | O objeto SensitivityLabel a ser adicionado ao final da coleção. |

**Retorna:**
int - O índice no qual o SensitivityLabel foi adicionado.
### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```

Remove o rótulo de sensibilidade no índice especificado.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| index | int | Índice do rótulo de sensibilidade que deve ser excluído. |

### clear() {#clear--}
```
public abstract void clear()
```

Remove todos os elementos da coleção.

### getCount() {#getCount--}
```
public abstract int getCount()
```

Obtém o número de todos os elementos da coleção. Somente leitura  int .

**Retorna:**
int