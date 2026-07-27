---
title: IsNull()
second_title: Referência da API Aspose.Slides para C++
description: Verifica se um valor específico é nulo. Versão para tipos aritméticos e enumerados.
type: docs
weight: 1
url: /pt/system/testtools/isnull/
---
## TestTools::IsNull(T) método

Verifica se o valor específico é nulo. [Version](../../version/) para tipos aritméticos e enumerados.

```cpp
template<typename T> static std::enable_if<std::is_arithmetic<T>::value||std::is_enum<T>::value, bool>::type System::TestTools::IsNull(T obj)
```

### Parâmetros de Modelo

| Parâmetro | Descrição |
| --- | --- |
| T | Tipo do valor a ser verificado. |

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| obj | T | Valor a ser verificado se é nulo. |

### Valor de Retorno

Sempre retorna falso.

## TestTools::IsNull(const T\&) método

Verifica se o valor específico é nulo. [Version](../../version/) para tipos de valor não aritméticos e não enumerados.

```cpp
template<typename T> static std::enable_if<!std::is_arithmetic<T>::value &&!std::is_enum<T>::value, bool>::type System::TestTools::IsNull(const T &obj)
```

### Parâmetros de Modelo

| Parâmetro | Descrição |
| --- | --- |
| T | Tipo do valor a ser verificado. |

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| obj | const T\& | Valor a ser verificado se é nulo. |

### Valor de Retorno

Verdadeiro se o objeto for comparado a nullptr como verdadeiro, falso caso contrário.

## TestTools::IsNull(const SharedPtr\<T\>\&) método

Verifica se o valor específico é nulo. [Version](../../version/) para tipos de valor não aritméticos.

```cpp
template<typename T> static bool System::TestTools::IsNull(const SharedPtr<T> &obj)
```

### Parâmetros de Modelo

| Parâmetro | Descrição |
| --- | --- |
| T | Tipo do valor a ser verificado. |

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| obj | const [SharedPtr](../../sharedptr/)\<T\>\& | Valor a ser verificado se é nulo. |

### Valor de Retorno

Verdadeiro se o objeto for comparado a nullptr como verdadeiro, falso caso contrário.

## TestTools::IsNull(System::Collections::Generic::KeyValuePair\<K, V\>\&) método

Verifica se o valor específico é nulo. [Version](../../version/) para pares chave-valor.

```cpp
template<typename K,typename V> static bool System::TestTools::IsNull(System::Collections::Generic::KeyValuePair<K, V> &kvp)
```

### Parâmetros de Modelo

| Parâmetro | Descrição |
| --- | --- |
| K | Tipo da chave. |
| V | Tipo do valor. |

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| kvp | [System::Collections::Generic::KeyValuePair](../../../system.collections.generic/keyvaluepair/)\<K, V\>\& | Objeto do par. |

### Valor de Retorno

Verdadeiro se o par for considerado nulo, falso caso contrário.

## TestTools::IsNull(const System::String\&) método

Verifica se a string é nula.

```cpp
static bool System::TestTools::IsNull(const System::String &str)
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| str | const [System::String](../../string/)\& | [String](../../string/) para verificação. |

### Valor de Retorno

Verdadeiro se a string for considerada nula, falso caso contrário.

## Veja Também

* Typedef [SharedPtr](../../sharedptr/)
* Class [KeyValuePair](../../../system.collections.generic/keyvaluepair/)
* Class [String](../../string/)
* Struct [TestTools](../)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)