---
title: Add()
second_title: Referencia de la API de Aspose.Slides para C++
description: Añade una pestaña a la colección.
type: docs
weight: 14
url: /es/aspose.slides/itabcollection/add/
---
## ITabCollection::Add(double, TabAlignment) método

Añade un [Tab](../../tab/) a la colección.

```cpp
virtual System::SharedPtr<ITab> Aspose::Slides::ITabCollection::Add(double position, TabAlignment align)=0
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| position | **double** | [Tab](../../tab/) posición. |
| align | [TabAlignment](../../tabalignment/) | [Tab](../../tab/) alineación. |

### Valor devuelto

Tabulación añadida.

## ITabCollection::Add(System::SharedPtr\<ITab\>) método

Añade un [Tab](../../tab/) a la colección.

```cpp
virtual int32_t Aspose::Slides::ITabCollection::Add(System::SharedPtr<ITab> value)=0
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [System::SharedPtr](../../../system/sharedptr/)\<[ITab](../../itab/)\> | El objeto [Tab](../../tab/) que se añadirá al final de la colección. |

### Valor devuelto

El índice en el que se añadió el tab.

## Ver también

* Enum [TabAlignment](../../tabalignment/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [ITab](../../itab/)
* Class [ITabCollection](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)