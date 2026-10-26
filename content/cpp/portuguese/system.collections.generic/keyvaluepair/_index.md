---
title: KeyValuePair
second_title: Referência da API Aspose.Slides para C++
description: "Par de chave e valor. Este tipo deve ser alocado na pilha e passado para funções por valor ou por referência. Nunca use a classe System::SmartPtr para gerenciar objetos deste tipo."
type: docs
weight: 378
url: /pt/system.collections.generic/keyvaluepair/
---
## classe KeyValuePair


Par de chave e valor. Este tipo deve ser alocado na pilha e passado para funções por valor ou por referência. Nunca use a classe [System::SmartPtr](../../system/smartptr/) para gerenciar objetos deste tipo.

```cpp
template<typename TKey,typename TValue>class KeyValuePair
```

## Métodos

| Método | Descrição |
| --- | --- |
| const TKey\& [get_Key](./get_key/)() const | Obtém a chave. |
| const TValue\& [get_Value](./get_value/)() const | Obtém o valor. |
| int [GetHashCode](./gethashcode/)() const | Calcula o hash do par chave-valor ao fazer XOR dos hashes da chave e do valor. |
| **bool** [IsNull](./isnull/)() const | Sempre retorna false. |
|  [KeyValuePair](./keyvaluepair/)() | Inicializador de par chave-valor nulo. |
|  [KeyValuePair](./keyvaluepair/)(const TKey\&, const TValue\&) | Construtor. |
|  [KeyValuePair](./keyvaluepair/)(const std::pair\<OtherK, OtherV\>\&) | Construtor de conversão de tipo. |
| **bool** [operator<](./operator_less/)(const [KeyValuePair](./)\&) const | Correção para classes herdadas de IComparer<KeyValuePair<TKey, TValue>>, não compara nada. |
| [String](../../system/string/) [ToString](./tostring/)() const | Converte o par chave-valor para string. |

## Veja Também

* Espaço de nomes [System::Collections::Generic](../)
* Biblioteca [Aspose.Slides](../../)