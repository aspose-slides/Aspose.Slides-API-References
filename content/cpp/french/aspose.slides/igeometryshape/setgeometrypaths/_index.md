---
title: SetGeometryPaths()
second_title: Référence de l'API Aspose.Slides pour C++
description: "Met à jour la géométrie de la forme à partir d'un tableau d'IGeometryPath. Les coordonnées doivent être relatives au coin supérieur gauche de la forme. Change le type de la forme (ShapeType) en ShapeType::Custom."
type: docs
weight: 79
url: /fr/aspose.slides/igeometryshape/setgeometrypaths/
---
## IGeometryShape::SetGeometryPaths(System::ArrayPtr\<System::SharedPtr\<IGeometryPath\>\>) méthode

Met à jour la géométrie de la forme à partir d'un tableau de [IGeometryPath](../../igeometrypath/). Les coordonnées doivent être relatives au coin supérieur gauche de la forme. Change le type de la forme ([ShapeType](../../shapetype/)) en [ShapeType::Custom](../../shapetype/).

```cpp
virtual void Aspose::Slides::IGeometryShape::SetGeometryPaths(System::ArrayPtr<System::SharedPtr<IGeometryPath>> geometryPaths)=0
```

### Paramètres

| Paramètre | Type | Description |
| --- | --- | --- |
| geometryPaths | [System::ArrayPtr](../../../system/arrayptr/)\<[System::SharedPtr](../../../system/sharedptr/)\<[IGeometryPath](../../igeometrypath/)\>\> | Chemins de géométrie du tableau |

## Remarques



Exemple:
```cpp
using namespace System;
using namespace Aspose::Slides;

auto pres = MakeObject<Presentation>();
auto shape = AsCast<GeometryShape>(pres->get_Slides()->idx_get(0)->get_Shapes()->AddAutoShape(ShapeType::Rectangle, 100.0f, 100.0f, 200.0f, 100.0f));

auto geometryPath = shape->GetGeometryPaths()->idx_get(0);

geometryPath->LineTo(100.0f, 50.0f, 1);
geometryPath->LineTo(100.0f, 50.0f, 4);

shape->SetGeometryPath(geometryPath);

pres->Save(u"output.pptx", SaveFormat::Pptx);
```

## Voir aussi

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IGeometryPath](../../igeometrypath/)
* Class [IGeometryShape](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)