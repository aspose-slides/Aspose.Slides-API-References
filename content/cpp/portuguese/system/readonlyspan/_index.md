---
title: ReadOnlySpan
second_title: Referência da API Aspose.Slides para C++
description: Encaminhamento para uso dentro da classe Span.
type: docs
weight: 1210
url: /pt/system/readonlyspan/
---
## ReadOnlySpan classe

Encaminhamento para uso dentro da classe [Span](../span/).

```cpp
template<typename T>class ReadOnlySpan : public System::Details::SpanCore<const T, ReadOnlySpan<T>, Span<T>>
```

### Parâmetros de modelo

| Parâmetro | Descrição |
| --- | --- |
| T | O tipo dos elementos no span. Esta classe fornece uma forma segura de tipo para trabalhar com sequências contíguas de objetos de maneira somente leitura. Pode ser usada para envolver arrays, arrays de pilha ou ponteiros brutos mantendo a verificação de limites. O [ReadOnlySpan](./) não possui a memória a que aponta – é apenas uma visualização da memória existente. |

## Métodos

| Método | Descrição |
| --- | --- |
|  [ReadOnlySpan](./readonlyspan/)(const [Span](../span/)\<T\>\&) | Constrói um span somente leitura a partir de um span regular. |
| static [ThisType](./) [to_ReadOnlySpan](./to_readonlyspan/)(const typename BaseType::ArrayPtrT\&) | Converte um array para um [ReadOnlySpan](./). |

## Observações

Representa uma região contígua somente leitura de memória arbitrária.

## Ver também

* Espaço de nomes [System](../)
* Biblioteca [Aspose.Slides](../../)