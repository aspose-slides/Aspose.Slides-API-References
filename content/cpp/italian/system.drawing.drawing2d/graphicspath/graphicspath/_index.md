---
title: GraphicsPath()
second_title: Riferimento API Aspose.Slides per C++
description: Crea una nuova istanza della classe GraphicsPath con la modalità di riempimento specificata.
type: docs
weight: 1
url: /it/system.drawing.drawing2d/graphicspath/graphicspath/
---
## GraphicsPath::GraphicsPath(FillMode) costruttore

Costruisce una nuova istanza della classe [GraphicsPath](../) con la modalità di riempimento specificata.

```cpp
System::Drawing::Drawing2D::GraphicsPath::GraphicsPath(FillMode fillMode=FillMode::Alternate)
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| fillMode | [FillMode](../../fillmode/) | Specifica come l'interno del percorso chiuso rappresentato dall'oggetto creato deve essere riempito |

## GraphicsPath::GraphicsPath(const ArrayPtr\<Point\>\&, const ArrayPtr\<uint8_t\>\&, FillMode) costruttore

Costruisce una nuova istanza dell'oggetto [GraphicsPath](../) che rappresenta il percorso specificato.

```cpp
System::Drawing::Drawing2D::GraphicsPath::GraphicsPath(const ArrayPtr<Point> &pts, const ArrayPtr<uint8_t> &types, FillMode fillMode=FillMode::Alternate)
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| pts | const [ArrayPtr](../../../system/arrayptr/)\<[Point](../../../system.drawing/point/)\>\& | Un array contenente i punti che specificano il percorso che deve essere rappresentato dall'oggetto creato |
| types | const [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | Un array contenente i valori che specificano i tipi dei punti corrispondenti nell'array **pts** |
| fillMode | [FillMode](../../fillmode/) | Specifica come l'interno del percorso chiuso rappresentato dall'oggetto creato deve essere riempito |

## GraphicsPath::GraphicsPath(const ArrayPtr\<PointF\>\&, const ArrayPtr\<uint8_t\>\&, FillMode) costruttore

Costruisce una nuova istanza dell'oggetto [GraphicsPath](../) che rappresenta il percorso specificato.

```cpp
System::Drawing::Drawing2D::GraphicsPath::GraphicsPath(const ArrayPtr<PointF> &pts, const ArrayPtr<uint8_t> &types, FillMode fillMode=FillMode::Alternate)
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| pts | const [ArrayPtr](../../../system/arrayptr/)\<[PointF](../../../system.drawing/pointf/)\>\& | Un array contenente i punti che specificano il percorso che deve essere rappresentato dall'oggetto creato |
| types | const [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | Un array contenente i valori che specificano i tipi dei punti corrispondenti nell'array **pts** |
| fillMode | [FillMode](../../fillmode/) | Specifica come l'interno del percorso chiuso rappresentato dall'oggetto creato deve essere riempito |

## GraphicsPath::GraphicsPath(const SkPath\&) costruttore




```cpp
System::Drawing::Drawing2D::GraphicsPath::GraphicsPath(const SkPath &path)
```

## Vedi anche

* Enum [FillMode](../../fillmode/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Classe [GraphicsPath](../)
* Classe [Point](../../../system.drawing/point/)
* Classe [PointF](../../../system.drawing/pointf/)
* Namespace [System::Drawing::Drawing2D](../../)
* Libreria [Aspose.Slides](../../../)