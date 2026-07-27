---
title: Sign()
second_title: Referência da API Aspose.Slides for C++
description: Determina o sinal do valor integral com sinal especificado.
type: docs
weight: 274
url: /pt/system/math/sign/
---
## Math::Sign(T) método


Determina o sinal do valor integral com sinal especificado.

```cpp
template<typename T> static std::enable_if<std::is_integral<T>::value &&!std::is_unsigned<T>::value, int>::type System::Math::Sign(T value)
```


### Parâmetros de modelo

| Parâmetro | Descrição |
| --- | --- |
| T | O tipo inteiro com sinal |

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | T | O valor cujo sinal será determinado |

### Valor de retorno

- 1 se **value** for menor que 0; 0 se **value** for igual a 0; 1 se **value** for maior que 0

## Math::Sign(T) método


Determina o sinal do valor de ponto flutuante especificado.

```cpp
template<typename T> static std::enable_if<std::is_floating_point<T>::value, int>::type System::Math::Sign(T value)
```


### Parâmetros de modelo

| Parâmetro | Descrição |
| --- | --- |
| T | O tipo ponto flutuante do argumento |

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | T | O valor cujo sinal será determinado |

### Valor de retorno

- 1 se **value** for menor que 0; 0 se **value** for igual a 0; 1 se **value** for maior que 0

## Math::Sign(const Decimal\&) método


Determina o sinal do valor decimal especificado.

```cpp
static int System::Math::Sign(const Decimal &value)
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | const [Decimal](../../decimal/)\& | O valor cujo sinal será determinado |

### Valor de retorno

- 1 se **value** for menor que 0; 0 se **value** for igual a 0; 1 se **value** for maior que 0

## Veja Também

* Classe [Decimal](../../decimal/)
* Estrutura [Math](../)
* Espaço de nomes [System](../../)
* Biblioteca [Aspose.Slides](../../../)