---
title: GetCustomAttribute()
second_title: Referência da API Aspose.Slides para C++
description: Pesquisa o atributo personalizado aplicado que possui o tipo especificado e que é aplicado ao tipo representado pelo objeto atual.
type: docs
weight: 573
url: /pt/system/typeinfo/getcustomattribute/
---
## TypeInfo::GetCustomAttribute(const TypeInfo\&) const método

Procura o atributo personalizado aplicado que possui o tipo especificado e que é aplicado ao tipo representado pelo objeto atual.

```cpp
ObjectPtr System::TypeInfo::GetCustomAttribute(const TypeInfo &attributeType) const
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| attributeType | const [TypeInfo](../)\& | A referência constante ao objeto [TypeInfo](../) que representa o tipo do atributo a ser pesquisado |

### Valor de Retorno

Um ponteiro para um objeto que representa o atributo encontrado, ou ponteiro nulo se nenhum atributo for encontrado que corresponda aos critérios de pesquisa

## Veja Também

* Classe [SmartPtr](../../smartptr/)
* Classe [TypeInfo](../)
* Espaço de nomes [System](../../)
* Biblioteca [Aspose.Slides](../../../)