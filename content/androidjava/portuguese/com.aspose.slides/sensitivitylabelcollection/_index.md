---
title: SensitivityLabelCollection
second_title: Aspose.Slides para Android via Referência da API Java
description: Representa uma coleção de rótulos de sensibilidade aplicados ao documento.
type: docs
url: /pt/com.aspose.slides/sensitivitylabelcollection/
---
**Inheritance:**
java.lang.Object, com.aspose.slides.DomObject

**All Implemented Interfaces:**
[com.aspose.slides.ISensitivityLabelCollection](../../com.aspose.slides/isensitivitylabelcollection)
```
public final class SensitivityLabelCollection extends DomObject<Presentation> implements ISensitivityLabelCollection
```

Representa uma coleção de rótulos de sensibilidade aplicados ao documento.
## Métodos

| Método | Descrição |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Retorna o rótulo de sensibilidade por índice. |
| [add(String id, UUID siteId, boolean isEnabled, int methodType)](#add-java.lang.String-java.util.UUID-boolean-int-) | Adiciona o rótulo de sensibilidade ao final da coleção. |
| [add(ISensitivityLabel label)](#add-com.aspose.slides.ISensitivityLabel-) | Adiciona um SensitivityLabel à coleção. |
| [removeAt(int index)](#removeAt-int-) | Remove o rótulo de sensibilidade no índice especificado. |
| [clear()](#clear--) | Remove todos os elementos da coleção. |
| [iterator()](#iterator--) | Retorna um enumerador que itera através da coleção. |
| [getCount()](#getCount--) | Retorna o número de elementos na coleção. |
| [copyTo(ISensitivityLabel[] array, int index)](#copyTo-com.aspose.slides.ISensitivityLabel---int-) | Copia todos os elementos da coleção para o array especificado. |
### get_Item(int index) {#get-Item-int-}
```
public final ISensitivityLabel get_Item(int index)
```


Retorna o rótulo de sensibilidade por índice.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| index | int |  |

**Retorna:**
[ISensitivityLabel](../../com.aspose.slides/isensitivitylabel)
### add(String id, UUID siteId, boolean isEnabled, int methodType) {#add-java.lang.String-java.util.UUID-boolean-int-}
```
public final ISensitivityLabel add(String id, UUID siteId, boolean isEnabled, int methodType)
```


Adiciona o rótulo de sensibilidade ao final da coleção.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| id | java.lang.String | O id do rótulo de sensibilidade. |
| siteId | java.util.UUID | O identificador do site do Azure Active Directory (Azure AD). |
| isEnabled | boolean | Indicador que informa se o rótulo de sensibilidade está habilitado. |
| methodType | int | O método de atribuição para o rótulo de sensibilidade. |

**Retorna:**
[ISensitivityLabel](../../com.aspose.slides/isensitivitylabel)
### add(ISensitivityLabel label) {#add-com.aspose.slides.ISensitivityLabel-}
```
public final int add(ISensitivityLabel label)
```


Adiciona um SensitivityLabel à coleção.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| label | [ISensitivityLabel](../../com.aspose.slides/isensitivitylabel) | O objeto SensitivityLabel a ser adicionado ao final da coleção. |

**Retorna:**
int - O índice em que o SensitivityLabel foi adicionado.
### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```


Remove o rótulo de sensibilidade no índice especificado.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| index | int | Índice do rótulo de sensibilidade que deve ser excluído. |

### clear() {#clear--}
```
public final void clear()
```


Remove todos os elementos da coleção.

### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<ISensitivityLabel> iterator()
```


Retorna um enumerador que itera através da coleção.

**Retorna:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.ISensitivityLabel> - Um System.Collections.Generic.IEnumerator1 que pode ser usado para iterar através da coleção.
### getCount() {#getCount--}
```
public final int getCount()
```


Retorna o número de elementos na coleção. Somente leitura  int .

**Retorna:**
int
### copyTo(ISensitivityLabel[] array, int index) {#copyTo-com.aspose.slides.ISensitivityLabel---int-}
```
public final void copyTo(ISensitivityLabel[] array, int index)
```


Copia todos os elementos da coleção para o array especificado.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| array | [ISensitivityLabel\[\]](../../com.aspose.slides/isensitivitylabel) | Array de destino. |
| index | int | Índice inicial no array de destino. |