---
title: AddPath()
second_title: Aspose.Slides für C++ API-Referenz
description: Fügt den angegebenen Pfad zu dem Pfad hinzu, der vom aktuellen Objekt dargestellt wird.
type: docs
weight: 222
url: /de/system.drawing.drawing2d/graphicspath/addpath/
---
## GraphicsPath::AddPath(const SharedPtr\<GraphicsPath\>\&, bool) Methode

Fügt den angegebenen Pfad zu dem Pfad hinzu, der vom aktuellen Objekt dargestellt wird.

```cpp
void System::Drawing::Drawing2D::GraphicsPath::AddPath(const SharedPtr<GraphicsPath> &path, bool connect)
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| path | const [SharedPtr](../../../system/sharedptr/)\<[GraphicsPath](../)\>\& | Der hinzuzufügende Pfad |
| connect | **bool** | True gibt an, dass die letzte erste Figur im **path** Teil der letzten Figur des Pfads ist, der vom aktuellen Objekt dargestellt wird; false gibt an, dass die erste Figur im **path** und die letzte Figur des vom aktuellen Objekt dargestellten Pfads separate Figuren sind |

## Siehe auch

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [GraphicsPath](../)
* Namensraum [System::Drawing::Drawing2D](../../)
* Bibliothek [Aspose.Slides](../../../)