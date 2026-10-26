---
title: GetChildRows()
second_title: Referência da API Aspose.Slides for C++
description: Obtém linhas que são consideradas filhas através da relação especificada.
type: docs
weight: 27
url: /pt/system.data/datarow/getchildrows/
---
## DataRow::GetChildRows(const System::SharedPtr\<System::Data::DataRelation\>\&) método

Obtém linhas que são consideradas filhas através da relação especificada.

```cpp
System::ArrayPtr<System::SharedPtr<System::Data::DataRow>> System::Data::DataRow::GetChildRows(const System::SharedPtr<System::Data::DataRelation> &relation)
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| relation | const [System::SharedPtr](../../../system/sharedptr/)\<[System::Data::DataRelation](../../datarelation/)\>\& | Objeto Relation para especificar a relação entre linha pai e linha filha. |

### Valor de Retorno

[Array](../../../system/array/) de linhas filhas recuperadas.

## Veja Também

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [DataRow](../)
* Classe [DataRelation](../../datarelation/)
* Namespace [System::Data](../../)
* Biblioteca [Aspose.Slides](../../../)