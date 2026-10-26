---
title: StaticCastArray()
second_title: Aspose.Slides para C++ Referência da API
description: Realiza a conversão dos elementos do array especificado para um tipo diferente. Sobrescreve para casos em que From é objeto SmartPtr.
type: docs
weight: 2978
url: /pt/system/staticcastarray/
---
## System::StaticCastArray(const System::SharedPtr\<System::Array\<From\>\>\&) função


Realiza a conversão dos elementos do array especificado para um tipo diferente. Sobrescreve para casos em que From é [SmartPtr](../smartptr/) obj.

```cpp
template<typename To,typename From> std::enable_if_t<System::IsSmartPtr<From>::value, System::SharedPtr<System::Array<To>>> System::StaticCastArray(const System::SharedPtr<System::Array<From>> &from)
```


### Parâmetros do modelo

| Parâmetro | Descrição |
| --- | --- |
| To | O tipo para o qual os elementos do array especificado serão convertidos |
| From | O tipo dos elementos dos quais os elementos do array serão convertidos |

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| from | const [System::SharedPtr](../sharedptr/)\<[System::Array](../array/)\<From\>\>\& | Ponteiro compartilhado para o array que contém os elementos a serem convertidos |

### Valor de Retorno

Um ponteiro para um novo array contendo elementos do tipo **To** equivalentes aos elementos de **from**.

Obsoleto
:   Adicionado para compatibilidade retroativa. Use ExplicitCast em vez disso.

## System::StaticCastArray(const System::SharedPtr\<System::Array\<From\>\>\&) função


Realiza a conversão dos elementos do array especificado para um tipo diferente. Sobrescreve para casos em que From é Boxable e To é [Object](../object/)[].

```cpp
template<typename To,typename From> std::enable_if_t<!System::IsSmartPtr<From>::value &&System::IsBoxable<From>::value &&std::is_same<To, System::SharedPtr<Object>>::value, System::SharedPtr<System::Array<To>>> System::StaticCastArray(const System::SharedPtr<System::Array<From>> &from)
```


### Parâmetros do modelo

| Parâmetro | Descrição |
| --- | --- |
| To | O tipo para o qual os elementos do array especificado serão convertidos |
| From | O tipo dos elementos dos quais os elementos do array serão convertidos |

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| from | const [System::SharedPtr](../sharedptr/)\<[System::Array](../array/)\<From\>\>\& | Ponteiro compartilhado para o array que contém os elementos a serem convertidos |

### Valor de Retorno

Um ponteiro para um novo array contendo elementos do tipo **To** equivalentes aos elementos de **from**.

Obsoleto
:   Adicionado para compatibilidade retroativa. Use ExplicitCast em vez disso.

## Veja Também

* Typedef [SharedPtr](../sharedptr/)
* Class [Array](../array/)
* Class [Object](../object/)
* Struct [IsSmartPtr](../issmartptr/)
* Struct [IsBoxable](../isboxable/)
* Namespace [System](../)
* Library [Aspose.Slides](../../)