---
title: Add()
second_title: Referência da API Aspose.Slides para C++
description: Adicionar novo comando ao caminho
type: docs
weight: 14
url: /pt/aspose.slides.animation/imotionpath/add/
---
## IMotionPath::Add(MotionCommandPathType, System::ArrayPtr\<System::Drawing::PointF\>, MotionPathPointsType, bool) método

Adicionar novo comando ao caminho

```cpp
virtual System::SharedPtr<IMotionCmdPath> Aspose::Slides::Animation::IMotionPath::Add(MotionCommandPathType type, System::ArrayPtr<System::Drawing::PointF> pts, MotionPathPointsType ptsType, bool bRelativeCoord)=0
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| type | [MotionCommandPathType](../../motioncommandpathtype/) | Tipo de comando para o comportamento do efeito de movimento de animação [MotionCommandPathType](../../motioncommandpathtype/) |
| pts | [System::ArrayPtr](../../../system/arrayptr/)\<[System::Drawing::PointF](../../../system.drawing/pointf/)\> | Matriz de pontos [System::Drawing::PointF](../../../system.drawing/pointf/)[] |
| ptsType | [MotionPathPointsType](../../motionpathpointstype/) | Tipo de pontos no caminho de movimento de animação [MotionPathPointsType](../../motionpathpointstype/) |
| bRelativeCoord | **bool** | Indica se deve usar coordenadas relativas ou não **bool** |

### Valor de Retorno

Comando de um caminho [IMotionCmdPath](../../imotioncmdpath/)

## Veja Também

* Enum [MotionCommandPathType](../../motioncommandpathtype/)
* Enum [MotionPathPointsType](../../motionpathpointstype/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Classe [IMotionCmdPath](../../imotioncmdpath/)
* Classe [PointF](../../../system.drawing/pointf/)
* Classe [IMotionPath](../)
* Namespace [Aspose::Slides::Animation](../../)
* Biblioteca [Aspose.Slides](../../../)