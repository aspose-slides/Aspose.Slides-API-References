---
title: Sign()
second_title: Referência da API Aspose.Slides para C++
description: Determina o sinal do valor integral assinado especificado.
type: docs
weight: 274
url: /pt/system/mathf/sign/
---
## MathF::Sign(T) método

Determina o sinal do valor integral assinado especificado.

```cpp
template<typename T> static std::enable_if<std::is_integral<T>::value &&!std::is_unsigned<T>::value, int>::type System::MathF::Sign(T value)
```

### Parâmetros de modelo

| Parâmetro | Descrição |
| --- | --- |
| T | O tipo integral assinado |

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | T | O valor cujo sinal será determinado |

### Valor de retorno

- 1 se **value** for menor que 0; 0 se **value** for igual a 0; 1 se **value** for maior que 0

## MathF::Sign(T) método

Determina o sinal do valor de ponto flutuante especificado.

```cpp
template<typename T> static std::enable_if<std::is_floating_point<T>::value, int>::type System::MathF::Sign(T value)
```

### Parâmetros de modelo

| Parâmetro | Descrição |
| --- | --- |
| T | O tipo de ponto flutuante do argumento |

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | T | O valor cujo sinal será determinado |

### Valor de retorno

- 1 se **value** for menor que 0; 0 se **value** for igual a 0; 1 se **value** for maior que 0

## Veja Também

* Estrutura [MathF](../)
* Namespace [System](../../)
* Biblioteca [Aspose.Slides](../../../)