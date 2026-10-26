---
title: Insert()
second_title: Referência da API Aspose.Slides para C++
description: Insere novo comando ao caminho
type: docs
weight: 27
url: /pt/aspose.slides.animation/imotionpath/insert/
---
## IMotionPath::Insert(int32_t, MotionCommandPathType, System::ArrayPtr\<System::Drawing::PointF\>, MotionPathPointsType, bool) method


Insere novo comando ao caminho

```cpp
virtual void Aspose::Slides::Animation::IMotionPath::Insert(int32_t index, MotionCommandPathType type, System::ArrayPtr<System::Drawing::PointF> pts, MotionPathPointsType ptsType, bool bRelativeCoord)=0
```


### Argumentos

| Parameter | Type | Description |
| --- | --- | --- |
| index | **int32_t** | Índice para inserção de comando **int32_t** |
| type | [MotionCommandPathType](../../motioncommandpathtype/) | Tipo de comando para comportamento do efeito de movimento de animação [MotionCommandPathType](../../motioncommandpathtype/) |
| pts | [System::ArrayPtr](../../../system/arrayptr/)\<[System::Drawing::PointF](../../../system.drawing/pointf/)\> | Array de pontos [System::Drawing::PointF](../../../system.drawing/pointf/)[] |
| ptsType | [MotionPathPointsType](../../motionpathpointstype/) | Tipo de pontos no caminho de movimento de animação [MotionPathPointsType](../../motionpathpointstype/) |
| bRelativeCoord | **bool** | Indica se deve usar coordenadas relativas ou não **bool** |

## Veja Também

* Enum [MotionCommandPathType](../../motioncommandpathtype/)
* Enum [MotionPathPointsType](../../motionpathpointstype/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Classe [PointF](../../../system.drawing/pointf/)
* Classe [IMotionPath](../)
* Namespace [Aspose::Slides::Animation](../../)
* Library [Aspose.Slides](../../../)