---
title: Add()
second_title: Referência da API Aspose.Slides para C++
description: Adiciona uma Tab à coleção.
type: docs
weight: 53
url: /pt/aspose.slides/tabcollection/add/
---
## TabCollection::Add(double, TabAlignment) método

Adiciona um [Tab](../../tab/) à coleção.

```cpp
System::SharedPtr<ITab> Aspose::Slides::TabCollection::Add(double position, TabAlignment align) override
```

### Valor de Retorno

Tab adicionada.

## TabCollection::Add(System::SharedPtr\<ITab\>) método

Adiciona um [Tab](../../tab/) à coleção.

```cpp
int32_t Aspose::Slides::TabCollection::Add(System::SharedPtr<ITab> value) override
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | [System::SharedPtr](../../../system/sharedptr/)\<[ITab](../../itab/)\> | O objeto [Tab](../../tab/) a ser adicionado ao final da coleção. |

### Valor de Retorno

O índice no qual a aba foi adicionada.

## Veja Também

* Enum [TabAlignment](../../tabalignment/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* classe [ITab](../../itab/)
* classe [TabCollection](../)
* namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)