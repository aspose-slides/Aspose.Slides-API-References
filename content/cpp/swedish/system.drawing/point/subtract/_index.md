---
title: Subtract()
second_title: Aspose.Slides för C++ API-referens
description: Subtraherar bredd- och höjdvärden för det angivna Size-objektet från X- och Y-koordinatvärdena för det angivna Point-objektet respektive.
type: docs
weight: 196
url: /sv/system.drawing/point/subtract/
---
## Point::Subtract(const Point\&, const Size\&) metod


Subtraherar bredd- och höjdvärden för det angivna [Size](../../size/)-objektet från X- och Y-koordinatvärdena för det angivna [Point](../)-objektet respektive.

```cpp
static Point System::Drawing::Point::Subtract(const Point &point, const Size &size)
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| point | const [Point](../)\& | Punkten som ska översättas |
| size | const [Size](../../size/)\& | [Size](../../size/)-objektet som specificerar värdena att subtrahera från koordinatvärdena för **point** |

### Returvärde

Ett nytt [Point](../)-objekt vars X-koordinatvärde är lika med resultatet av subtraktionen av breddvärdet för **size** från X-koordinatvärdet för **point**, och Y-koordinatvärdet är lika med resultatet av subtraktionen av höjdvärdet för **size** från Y-koordinatvärdet för **point**.

## Se även

* Klass [Point](../)
* Klass [Size](../../size/)
* Namnrymd [System::Drawing](../../)
* Bibliotek [Aspose.Slides](../../../)