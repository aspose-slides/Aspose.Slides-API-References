---
title: AddPath()
second_title: Aspose.Slides för C++ API-referens
description: Lägger till den angivna vägen i den väg som representeras av det aktuella objektet.
type: docs
weight: 222
url: /sv/system.drawing.drawing2d/graphicspath/addpath/
---
## GraphicsPath::AddPath(const SharedPtr\<GraphicsPath\>\&, bool) metod


Lägger till den angivna vägen i den väg som representeras av det aktuella objektet.

```cpp
void System::Drawing::Drawing2D::GraphicsPath::AddPath(const SharedPtr<GraphicsPath> &path, bool connect)
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| path | const [SharedPtr](../../../system/sharedptr/)\<[GraphicsPath](../)\>\& | Sökvägen som ska läggas till |
| connect | **bool** | True specificerar att den sista första figuren i **path** är en del av den sista figuren i den väg som representeras av det aktuella objektet; false specificerar att den första figuren i **path** och den sista figuren i den väg som representeras av det aktuella objektet är separata figurer |

## Se även

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klass [GraphicsPath](../)
* Namnrymd [System::Drawing::Drawing2D](../../)
* Bibliotek [Aspose.Slides](../../../)