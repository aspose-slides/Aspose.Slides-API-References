---
title: AddPath()
second_title: Aspose.Slides pro C++ – referenční příručka API
description: Přidá zadanou cestu do cesty reprezentované aktuálním objektem.
type: docs
weight: 222
url: /cs/system.drawing.drawing2d/graphicspath/addpath/
---
## GraphicsPath::AddPath(const SharedPtr\<GraphicsPath\>\&, bool) metoda

Přidá zadanou cestu do cesty reprezentované aktuálním objektem.

```cpp
void System::Drawing::Drawing2D::GraphicsPath::AddPath(const SharedPtr<GraphicsPath> &path, bool connect)
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| path | const [SharedPtr](../../../system/sharedptr/)\<[GraphicsPath](../)\>\& | Cesta, která se má přidat |
| connect | **bool** | True určuje, že poslední figura v **path** je součástí poslední figury cesty reprezentované aktuálním objektem; false určuje, že první figura v **path** a poslední figura v cestě reprezentované aktuálním objektem jsou samostatné figury |

## Viz také

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [GraphicsPath](../)
* Namespace [System::Drawing::Drawing2D](../../)
* Library [Aspose.Slides](../../../)