---
title: AddPath()
second_title: Aspose.Slides dla C++ – Referencja API
description: Dodaje określoną ścieżkę do ścieżki reprezentowanej przez bieżący obiekt.
type: docs
weight: 222
url: /pl/system.drawing.drawing2d/graphicspath/addpath/
---
## GraphicsPath::AddPath(const SharedPtr\<GraphicsPath\>\&, bool) metoda


Dodaje określoną ścieżkę do ścieżki reprezentowanej przez bieżący obiekt.

```cpp
void System::Drawing::Drawing2D::GraphicsPath::AddPath(const SharedPtr<GraphicsPath> &path, bool connect)
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| path | const [SharedPtr](../../../system/sharedptr/)\<[GraphicsPath](../)\>\& | Ścieżka do dodania |
| connect | **bool** | True określa, że ostatnia pierwsza figura w **path** jest częścią ostatniej figury ścieżki reprezentowanej przez bieżący obiekt; false określa, że pierwsza figura w **path** i ostatnia figura w ścieżce reprezentowanej przez bieżący obiekt są oddzielnymi figurami |

## Zobacz też

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasa [GraphicsPath](../)
* Przestrzeń nazw [System::Drawing::Drawing2D](../../)
* Biblioteka [Aspose.Slides](../../../)