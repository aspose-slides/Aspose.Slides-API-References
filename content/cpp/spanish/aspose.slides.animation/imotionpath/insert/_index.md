---
title: Insert()
second_title: Referencia de API de Aspose.Slides para C++
description: Insertar nuevo comando en la ruta
type: docs
weight: 27
url: /es/aspose.slides.animation/imotionpath/insert/
---
## IMotionPath::Insert(int32_t, MotionCommandPathType, System::ArrayPtr\<System::Drawing::PointF\>, MotionPathPointsType, bool) método

Insertar nuevo comando en la ruta

```cpp
virtual void Aspose::Slides::Animation::IMotionPath::Insert(int32_t index, MotionCommandPathType type, System::ArrayPtr<System::Drawing::PointF> pts, MotionPathPointsType ptsType, bool bRelativeCoord)=0
```


### Arguments

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| index | **int32_t** | Índice para la inserción del comando **int32_t** |
| type | [MotionCommandPathType](../../motioncommandpathtype/) | Tipo de comando para el comportamiento del efecto de movimiento de animación [MotionCommandPathType](../../motioncommandpathtype/) |
| pts | [System::ArrayPtr](../../../system/arrayptr/)\<[System::Drawing::PointF](../../../system.drawing/pointf/)\> | Matriz de puntos [System::Drawing::PointF](../../../system.drawing/pointf/)[] |
| ptsType | [MotionPathPointsType](../../motionpathpointstype/) | Tipo de puntos en la ruta de movimiento de animación [MotionPathPointsType](../../motionpathpointstype/) |
| bRelativeCoord | **bool** | Indica si se deben usar coordenadas relativas o no **bool** |

## Ver también

* Enumeración [MotionCommandPathType](../../motioncommandpathtype/)
* Enumeración [MotionPathPointsType](../../motionpathpointstype/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Clase [PointF](../../../system.drawing/pointf/)
* Clase [IMotionPath](../)
* Espacio de nombres [Aspose::Slides::Animation](../../)
* Biblioteca [Aspose.Slides](../../../)