---
title: Span
second_title: Referência da API Aspose.Slides para C++
description: "Representa uma região contígua de memória arbitrária semelhante ao std::span do C++20."
type: docs
weight: 1262
url: /pt/system/span/
---
## Span classe

Representa uma região contígua de memória arbitrária semelhante ao std::span do C++20.

```cpp
template<typename T>class Span : public System::Details::SpanCore<T, Span<T>, Span<T>>
```

### Parâmetros de modelo

| Parâmetro | Descrição |
| --- | --- |
| T | O tipo dos elementos no span. Esta classe fornece uma maneira segura de tipo para trabalhar com sequências contíguas de objetos. Pode ser usada para envolver arrays, arrays de pilha ou ponteiros brutos enquanto mantém a verificação de limites. O [Span](./) não possui a memória à qual aponta - é apenas uma visualização da memória existente. |

## Métodos

| Método | Descrição |
| --- | --- |
| void [Clear](./clear/)() const | Limpa o conteúdo do span definindo todos os elementos para o valor padrão. |
| void [Fill](./fill/)(const T\&) const | Preenche o span com o valor especificado. |
| static [ThisType](./) [to_Span](./to_span/)(const typename BaseType::ArrayPtrT\&) | Converte um array para um [Span](./). |

## Veja também

* Namespace [System](../)
* Library [Aspose.Slides](../../)