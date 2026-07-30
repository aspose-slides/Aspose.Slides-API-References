---
title: GetRegionScans()
second_title: Riferimento API di Aspose.Slides per C++
description: Restituisce un array di strutture RectangleF che approssimano questa Region dopo che la trasformazione matriciale specificata è stata applicata.
type: docs
weight: 27
url: /it/system.drawing/region/getregionscans/
---
## Region::GetRegionScans(const SharedPtr\<Drawing2D::Matrix\>\&) const metodo


Restituisce un array di [RectangleF](../../rectanglef/) strutture che approssimano questo [Region](../) dopo che la trasformazione matriciale specificata è stata applicata.

```cpp
ArrayPtr<RectangleF> System::Drawing::Region::GetRegionScans(const SharedPtr<Drawing2D::Matrix> &matrix) const
```


### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| matrix | const [SharedPtr](../../../system/sharedptr/)\<[Drawing2D::Matrix](../../../system.drawing.drawing2d/matrix/)\>\& | Una Matrix che rappresenta una trasformazione geometrica da applicare alla regione. |

## Vedi anche

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [RectangleF](../../rectanglef/)
* Classe [Matrix](../../../system.drawing.drawing2d/matrix/)
* Classe [Region](../)
* Namespace [System::Drawing](../../)
* Libreria [Aspose.Slides](../../../)