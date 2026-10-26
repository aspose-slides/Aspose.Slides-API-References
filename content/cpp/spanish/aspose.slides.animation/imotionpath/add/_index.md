---
title: Add()
second_title: Referencia de API de Aspose.Slides para C++
description: Agregar nuevo comando a la ruta
type: docs
weight: 14
url: /es/aspose.slides.animation/imotionpath/add/
---
## IMotionPath::Add(MotionCommandPathType, System::ArrayPtr\<System::Drawing::PointF\>, MotionPathPointsType, bool) método

Agregar un nuevo comando a la ruta

```cpp
virtual System::SharedPtr<IMotionCmdPath> Aspose::Slides::Animation::IMotionPath::Add(MotionCommandPathType type, System::ArrayPtr<System::Drawing::PointF> pts, MotionPathPointsType ptsType, bool bRelativeCoord)=0
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| type | [MotionCommandPathType](../../motioncommandpathtype/) | Tipo de comando para el comportamiento del efecto de movimiento de animación [MotionCommandPathType](../../motioncommandpathtype/) |
| pts | [System::ArrayPtr](../../../system/arrayptr/)\<[System::Drawing::PointF](../../../system.drawing/pointf/)\> | Arreglo de puntos [System::Drawing::PointF](../../../system.drawing/pointf/)[] |
| ptsType | [MotionPathPointsType](../../motionpathpointstype/) | Tipo de puntos en la ruta de movimiento de animación [MotionPathPointsType](../../motionpathpointstype/) |
| bRelativeCoord | **bool** | Indica si se deben usar coordenadas relativas o no **bool** |

### Valor de retorno

Comando de una ruta [IMotionCmdPath](../../imotioncmdpath/)

## Ver también

* Enum [MotionCommandPathType](../../motioncommandpathtype/)
* Enum [MotionPathPointsType](../../motionpathpointstype/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Clase [IMotionCmdPath](../../imotioncmdpath/)
* Clase [PointF](../../../system.drawing/pointf/)
* Clase [IMotionPath](../)
* Espacio de nombres [Aspose::Slides::Animation](../../)
* Library [Aspose.Slides](../../../)