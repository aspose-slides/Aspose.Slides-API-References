---
title: ByteLength()
second_title: Referência da API Aspose.Slides para C++
description: Determina o número de bytes ocupados por todos os elementos do array especificado.
type: docs
weight: 14
url: /pt/system/buffer/bytelength/
---
## Buffer::ByteLength(const SharedPtr\<Array\<T\>\>\&) método

Determina o número de bytes ocupados por todos os elementos do array especificado.

```cpp
template<class T> static int System::Buffer::ByteLength(const SharedPtr<Array<T>> &array)
```

### Parâmetros de modelo

| Parâmetro | Descrição |
| --- | --- |
| T | O tipo dos elementos do array |

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| array | const [SharedPtr](../../sharedptr/)\<[Array](../../array/)\<T\>\>\& | Um array |

### Valor de retorno

O número de bytes ocupados por todos os elementos do array especificado

## Buffer::ByteLength(const System::Details::ArrayView\<T\>\&) método

Determina o número de bytes ocupados por todos os elementos do array especificado.

```cpp
template<class T> static int System::Buffer::ByteLength(const System::Details::ArrayView<T> &array)
```

### Parâmetros de modelo

| Parâmetro | Descrição |
| --- | --- |
| T | O tipo dos elementos da visualização de array |

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| array | const System::Details::ArrayView\<T\>\& | Uma visualização de array |

### Valor de retorno

O número de bytes ocupados por todos os elementos da visualização de array especificada

## Buffer::ByteLength(const System::Details::StackArray\<T, N\>\&) método

Determina o número de bytes ocupados por todos os elementos do array especificado.

```cpp
template<class T,std::size_t> static int System::Buffer::ByteLength(const System::Details::StackArray<T, N> &array)
```

### Parâmetros de modelo

| Parâmetro | Descrição |
| --- | --- |
| T | O tipo dos elementos do array de pilha |
| N | O tamanho do array de pilha |

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| array | const System::Details::StackArray\<T, N\>\& | Um array de pilha |

### Valor de retorno

O número de bytes ocupados por todos os elementos do array de pilha especificado

## Ver Também

* Typedef [SharedPtr](../../sharedptr/)
* Class [Array](../../array/)
* Class [Buffer](../)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)