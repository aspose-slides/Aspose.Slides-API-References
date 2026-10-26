---
title: CustomLineCap()
second_title: Référence de l'API Aspose.Slides pour C++
description: Construit une nouvelle instance de la classe CustomLineCap qui représente un cap de ligne défini par l'utilisateur avec les propriétés spécifiées.
type: docs
weight: 1
url: /fr/system.drawing.drawing2d/customlinecap/customlinecap/
---
## CustomLineCap::CustomLineCap(const SharedPtr\<GraphicsPath\>\&, const SharedPtr\<GraphicsPath\>\&, LineCap, float) constructeur

Construit une nouvelle instance de la classe [CustomLineCap](../) qui représente un cap de ligne défini par l'utilisateur avec les propriétés spécifiées.

```cpp
System::Drawing::Drawing2D::CustomLineCap::CustomLineCap(const SharedPtr<GraphicsPath> &fillPath, const SharedPtr<GraphicsPath> &strokePath, LineCap baseCap=LineCap::Flat, float baseInset=0)
```

### Paramètres

| Paramètre | Type | Description |
| --- | --- | --- |
| fillPath | const [SharedPtr](../../../system/sharedptr/)\<[GraphicsPath](../../graphicspath/)\>\& | Spécifie un remplissage pour le cap personnalisé |
| strokePath | const [SharedPtr](../../../system/sharedptr/)\<[GraphicsPath](../../graphicspath/)\>\& | Spécifie le contour du cap personnalisé |
| baseCap | [LineCap](../../linecap/) | Le cap de ligne de base à partir duquel le cap personnalisé est créé |
| baseInset | **float** | Spécifie la distance entre la ligne et le cap |

## Voir aussi

* Enum [LineCap](../../linecap/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [GraphicsPath](../../graphicspath/)
* Classe [CustomLineCap](../)
* Espace de noms [System::Drawing::Drawing2D](../../)
* Bibliothèque [Aspose.Slides](../../../)