---
title: operator==()
second_title: Referência da API Aspose.Slides para C++
description: Compara dois pares chave-valor usando a semântica de 'equals'. Usa o operador == ou o método EqualsTo para ambas as chaves e valores, conforme definido.
type: docs
weight: 690
url: /pt/system.collections.generic/operator_equal_equal/
---
## System::Collections::Generic::operator==(const KeyValuePair\<TKey, TValue\>\&, const KeyValuePair\<TKey, TValue\>\&) função

Compara dois pares chave-valor usando a semântica de 'equals'. Usa o operador == ou o método EqualsTo para ambas as chaves e valores, conforme definido.

```cpp
template<typename TKey,typename TValue> bool System::Collections::Generic::operator==(const KeyValuePair<TKey, TValue> &left, const KeyValuePair<TKey, TValue> &right)
```

### Parâmetros de modelo

| Parâmetro | Descrição |
| --- | --- |
| TKey | Tipo da chave. |
| TValue | Tipo do valor. |

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| left | const [KeyValuePair](../keyvaluepair/)\<TKey, TValue\>\& | Operando LHS. |
| right | const [KeyValuePair](../keyvaluepair/)\<TKey, TValue\>\& | Operando RHS. |

### Valor de retorno

True se ambas as chaves e valores coincidirem, false caso contrário.

## Veja também

* Classe [KeyValuePair](../keyvaluepair/)
* Espaço de nomes [System::Collections::Generic](../)
* Biblioteca [Aspose.Slides](../../)