---
title: Equals()
second_title: Referencia de API de Aspose.Slides para C++
description: Determina si la región especificada es idéntica a la región representada por el objeto actual en la superficie de dibujo especificada.
type: docs
weight: 157
url: /es/system.drawing/region/equals/
---
## Region::Equals(const SharedPtr\<Region\>\&, const SharedPtr\<Graphics\>\&) método

Determina si la región especificada es idéntica a la región representada por el objeto actual en la superficie de dibujo especificada.

```cpp
bool System::Drawing::Region::Equals(const SharedPtr<Region> &r, const SharedPtr<Graphics> &g)
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| r | const [SharedPtr](../../../system/sharedptr/)\<[Region](../)\>\& | La región para comparar con esta región |
| g | const [SharedPtr](../../../system/sharedptr/)\<[Graphics](../../graphics/)\>\& | Una superficie de dibujo |

### Valor de retorno

True si el interior de la región especificada es idéntico al interior de la región representada por el objeto actual cuando se aplica la transformación asociada al parámetro **g**; de lo contrario, false

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Region](../)
* Class [Graphics](../../graphics/)
* Namespace [System::Drawing](../../)
* Library [Aspose.Slides](../../../)