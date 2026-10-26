---
title: GetHashCode()
second_title: Referência da API Aspose.Slides para C++
description: Retorna um código hash para o valor escalar especificado.
type: docs
weight: 2484
url: /pt/system/gethashcode/
---
## System::GetHashCode(const T&) function

Retorna um código hash para o valor escalar especificado.

```cpp
template<typename T> std::enable_if<std::is_scalar<T>::value, int>::type System::GetHashCode(const T &obj)
```

### Parâmetros de modelo

| Parâmetro | Descrição |
| --- | --- |
| T | O tipo do valor para o qual a função gera o código hash |

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| obj | const T& | O valor para gerar o código hash |

### Valor de retorno

O código hash gerado para o valor especificado

## System::GetHashCode(const T&) function

Retorna um código hash para o objeto especificado.

```cpp
template<typename T> std::enable_if<!std::is_scalar<T>::value &&System::IsSmartPtr<T>::value, int>::type System::GetHashCode(const T &obj)
```

### Parâmetros de modelo

| Parâmetro | Descrição |
| --- | --- |
| T | O tipo do objeto para o qual a função gera o código hash |

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| obj | const T& | O [SmartPtr](../smartptr/) apontando para o objeto para gerar o código hash |

### Valor de retorno

O código hash gerado para o objeto especificado

## System::GetHashCode(const T&) function

Retorna um código hash para o objeto especificado que é exceção.

```cpp
template<typename T> std::enable_if<System::IsExceptionWrapper<T>::value, int>::type System::GetHashCode(const T &obj)
```

### Parâmetros de modelo

| Parâmetro | Descrição |
| --- | --- |
| T | O tipo do objeto para o qual a função gera o código hash |

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| obj | const T& | O Exception Wrapper que contém o objeto para gerar o código hash |

### Valor de retorno

O código hash gerado para o objeto especificado

## System::GetHashCode(const T&) function

Retorna um código hash para o objeto especificado que não é um ponteiro inteligente nem exceção.

```cpp
template<typename T> std::enable_if<!std::is_scalar<T>::value &&!System::IsSmartPtr<T>::value &&!System::IsExceptionWrapper<T>::value, int>::type System::GetHashCode(const T &obj)
```

### Parâmetros de modelo

| Parâmetro | Descrição |
| --- | --- |
| T | O tipo do objeto para o qual a função gera o código hash |

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| obj | const T& | Uma referência const ao objeto para gerar o código hash |

### Valor de retorno

O código hash gerado para o objeto especificado

## System::GetHashCode(const std::thread::id&) function

Especialização para std::thread::id; retorna o código hash para o objeto thread especificado.

```cpp
int System::GetHashCode(const std::thread::id &id)
```

## Veja também

* Struct [IsSmartPtr](../issmartptr/)
* Struct [IsExceptionWrapper](../isexceptionwrapper/)
* Namespace [System](../)
* Library [Aspose.Slides](../../)