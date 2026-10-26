---
title: SetByte()
second_title: Aspose.Slides para C++ Referência da API
description: Interpreta o array tipado especificado como um array de bytes bruto e define o valor do byte especificado no deslocamento de byte especificado.
type: docs
weight: 40
url: /pt/system/buffer/setbyte/
---
## Buffer::SetByte(const SharedPtr\<Array\<T\>\>\&, int, uint8_t) method

Interpreta o array tipado especificado como um array de bytes bruto e define o valor do byte especificado no deslocamento de byte especificado.

```cpp
template<typename T> static void System::Buffer::SetByte(const SharedPtr<Array<T>> &array, int index, uint8_t value)
```

### Parâmetros de modelo

| Parâmetro | Descrição |
| --- | --- |
| T | O tipo dos elementos do array |

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| array | const [SharedPtr](../../sharedptr/)\<[Array](../../array/)\<T\>\>\& | O array de destino |
| index | int | Deslocamento de base zero do byte a ser definido |
| value | **uint8_t** | O valor do byte a ser definido |

## Buffer::SetByte(const System::Details::ArrayView\<T\>\&, int, uint8_t) method

Interpreta o array tipado especificado como um array de bytes bruto e define o valor do byte especificado no deslocamento de byte especificado.

```cpp
template<typename T> static void System::Buffer::SetByte(const System::Details::ArrayView<T> &array, int index, uint8_t value)
```

### Parâmetros de modelo

| Parâmetro | Descrição |
| --- | --- |
| T | O tipo dos elementos do array |

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| array | const System::Details::ArrayView\<T\>\& | A visualização de array de destino |
| index | int | Deslocamento de base zero do byte a ser definido |
| value | **uint8_t** | O valor do byte a ser definido |

## Buffer::SetByte(const System::Details::StackArray\<T, N\>\&, int, uint8_t) method

Interpreta o array tipado especificado como um array de bytes bruto e define o valor do byte especificado no deslocamento de byte especificado.

```cpp
template<typename T,std::size_t> static void System::Buffer::SetByte(const System::Details::StackArray<T, N> &array, int index, uint8_t value)
```

### Parâmetros de modelo

| Parâmetro | Descrição |
| --- | --- |
| T | O tipo dos elementos do array |
| N | O tamanho do array de pilha |

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| array | const System::Details::StackArray\<T, N\>\& | O array de pilha de destino |
| index | int | Deslocamento de base zero do byte a ser definido |
| value | **uint8_t** | O valor do byte a ser definido |

## Ver Também

* Typedef [SharedPtr](../../sharedptr/)
* Classe [Array](../../array/)
* Classe [Buffer](../)
* Namespace [System](../../)
* Biblioteca [Aspose.Slides](../../../)