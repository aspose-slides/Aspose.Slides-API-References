---
title: IsDefined()
second_title: Referência da API Aspose.Slides para C++
description: NÃO IMPLEMENTADO. Indica se um ou mais atributos do tipo especificado ou de seus tipos derivados são aplicados a este membro.
type: docs
weight: 157
url: /pt/system/typeinfo/isdefined/
---
## TypeInfo::IsDefined(const TypeInfo\&, bool) const method


NÃO IMPLEMENTADO. Indica se um ou mais atributos do tipo especificado ou de seus tipos derivados são aplicados a este membro.

```cpp
bool System::TypeInfo::IsDefined(const TypeInfo &attributeType, bool inherit) const
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| attributeType | const [TypeInfo](../)\& | O tipo do atributo personalizado a ser pesquisado. A pesquisa inclui tipos derivados. |
| inherit | **bool** | true para pesquisar a cadeia de herança deste membro a fim de encontrar os atributos; caso contrário, false. Este parâmetro é ignorado para propriedades e eventos. |

### Valor de Retorno

true se uma ou mais instâncias de attributeType ou de qualquer um de seus tipos derivados forem aplicadas a este membro; caso contrário, false.

## Ver Também

* Classe [TypeInfo](../)
* Namespace [System](../../)
* Biblioteca [Aspose.Slides](../../../)