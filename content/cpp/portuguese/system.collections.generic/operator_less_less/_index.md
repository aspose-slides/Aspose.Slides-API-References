---
title: operator<<()
second_title: Referência de API Aspose.Slides para C++
description: Inserir dados no fluxo usando codificação UTF-8.
type: docs
weight: 716
url: /pt/system.collections.generic/operator_less_less/
---
## System::Collections::Generic::operator<<(std::ostream\&, const KeyValuePair\<TKey, TValue\>\&) function

Inserir dados no fluxo usando codificação UTF-8.

```cpp
template<typename TKey,typename TValue> std::ostream & System::Collections::Generic::operator<<(std::ostream &stream, const KeyValuePair<TKey, TValue> &pair)
```

### Parâmetros de modelo

| Parâmetro | Descrição |
| --- | --- |
| TKey | Tipo da chave. |
| TValue | Tipo do valor. |

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| stream | std::ostream\& | Fluxo de saída para inserir os dados. |
| pair | const [KeyValuePair](../keyvaluepair/)\<TKey, TValue\>\& | [Data](../../system.data/) para inserir. |

### Valor de retorno

**stream**.

## System::Collections::Generic::operator<<(std::wostream\&, const KeyValuePair\<TKey, TValue\>\&) function

Inserir dados no fluxo.

```cpp
template<typename TKey,typename TValue> std::wostream & System::Collections::Generic::operator<<(std::wostream &stream, const KeyValuePair<TKey, TValue> &pair)
```

### Parâmetros de modelo

| Parâmetro | Descrição |
| --- | --- |
| TKey | Tipo da chave. |
| TValue | Tipo do valor. |

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| stream | std::wostream\& | Fluxo de saída para inserir os dados. |
| pair | const [KeyValuePair](../keyvaluepair/)\<TKey, TValue\>\& | [Data](../../system.data/) para inserir. |

### Valor de retorno

**stream**.

## Ver também

* Classe [KeyValuePair](../keyvaluepair/)
* Namespace [System::Collections::Generic](../)
* Biblioteca [Aspose.Slides](../../)