---
title: Add()
second_title: Referência da API Aspose.Slides para C++
description: Adiciona uma Tab à coleção.
type: docs
weight: 14
url: /pt/aspose.slides/itabcollection/add/
---
## ITabCollection::Add(double, TabAlignment) método

Adiciona um [Tab](../../tab/) à coleção.

```cpp
virtual System::SharedPtr<ITab> Aspose::Slides::ITabCollection::Add(double position, TabAlignment align)=0
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| position | **double** | [Tab](../../tab/) posição. |
| align | [TabAlignment](../../tabalignment/) | [Tab](../../tab/) alinhamento. |

### Valor de Retorno

Tab adicionada.

## ITabCollection::Add(System::SharedPtr\<ITab\>) método

Adiciona um [Tab](../../tab/) à coleção.

```cpp
virtual int32_t Aspose::Slides::ITabCollection::Add(System::SharedPtr<ITab> value)=0
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | [System::SharedPtr](../../../system/sharedptr/)\<[ITab](../../itab/)\> | O objeto [Tab](../../tab/) a ser adicionado ao final da coleção. |

### Valor de Retorno

O índice no qual o tab foi adicionado.

## Veja Também

* Enum [TabAlignment](../../tabalignment/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [ITab](../../itab/)
* Classe [ITabCollection](../)
* Namespace [Aspose::Slides](../../)
* Biblioteca [Aspose.Slides](../../../)