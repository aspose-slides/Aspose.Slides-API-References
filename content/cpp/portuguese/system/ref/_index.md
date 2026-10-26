---
title: Ref()
second_title: Referência da API Aspose.Slides para C++
description: Cria referência ao objeto DynamicWeakPtr. Usado pelo tradutor ao passar argumentos de função por referência.
type: docs
weight: 2458
url: /pt/system/ref/
---
## System::Ref(DynamicWeakPtr\<T, trunkMode, weakLeafs...\>\&) função

Cria referência ao objeto [DynamicWeakPtr](../dynamicweakptr/). Usado pelo tradutor ao passar argumentos de função por referência.

```cpp
template<typename T,SmartPtrMode,unsigned int ...> DynamicWeakPtr<T, trunkMode, weakLeafs...>::Reference System::Ref(DynamicWeakPtr<T, trunkMode, weakLeafs...> &ptr)
```

### Parâmetros de modelo

| Parâmetro | Descrição |
| --- | --- |
| T | Tipo do apontado. |
| trunkMode | Modo do ponteiro inteligente em si. |
| weakLeafs | Índices dos argumentos de modelo para os quais o método SetTemplateWeakPtr deve ser chamado. |

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| ptr | [DynamicWeakPtr](../dynamicweakptr/)\<T, trunkMode, weakLeafs...\>\& | Ponteiro inteligente ao qual criar referência. |

### Valor de retorno

Referência de ponteiro inteligente.

## System::Ref(T\&) função

Função auxiliar para obter referências a objetos. Usada para garantir que [System::DynamicWeakPtr](../dynamicweakptr/) atualize o objeto referenciado após atribuições.

```cpp
template<typename T> T & System::Ref(T &value)
```

### Parâmetros de modelo

| Parâmetro | Descrição |
| --- | --- |
| T | Tipo ao qual criar referência. |

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | T\& | Valor ao qual criar referência. |

### Valor de retorno

Referência ao valor passado para esta função.

## Veja também

* Classe [DynamicWeakPtr](../dynamicweakptr/)
* Namespace [System](../)
* Biblioteca [Aspose.Slides](../../)