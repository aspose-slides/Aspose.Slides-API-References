---
title: Add()
second_title: Referencia de API de Aspose.Slides para C++
description: Agrega un Tab a la colección.
type: docs
weight: 53
url: /es/aspose.slides/tabcollection/add/
---
## TabCollection::Add(double, TabAlignment) método

Agrega un [Tab](../../tab/) a la colección.

```cpp
System::SharedPtr<ITab> Aspose::Slides::TabCollection::Add(double position, TabAlignment align) override
```

### Valor devuelto

Tabulador añadido.

## TabCollection::Add(System::SharedPtr\<ITab\>) método

Agrega un [Tab](../../tab/) a la colección.

```cpp
int32_t Aspose::Slides::TabCollection::Add(System::SharedPtr<ITab> value) override
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [System::SharedPtr](../../../system/sharedptr/)\<[ITab](../../itab/)\> | El objeto [Tab](../../tab/) que se agregará al final de la colección. |

### Valor devuelto

El índice en el que se añadió el tabulador.

## Ver también

* Enumeración [TabAlignment](../../tabalignment/)
* Definición de tipo [SharedPtr](../../../system/sharedptr/)
* Clase [ITab](../../itab/)
* Clase [TabCollection](../)
* Espacio de nombres [Aspose::Slides](../../)
* Biblioteca [Aspose.Slides](../../../)