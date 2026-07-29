---
title: Subtract()
second_title: Aspose.Slides för C++ API-referens
description: Subtraherar bredd- och höjdvärden för det angivna SizeF-objektet från X- och Y-koordinatvärdena för det angivna PointF-objektet respektive.
type: docs
weight: 157
url: /sv/system.drawing/pointf/subtract/
---
## PointF::Subtract(const PointF\&, const SizeF\&) metod

Subtraherar bredd- och höjdvärden för det angivna [SizeF](../../sizef/)-objektet från X- och Y-koordinatvärdena för det angivna [PointF](../)-objektet respektive.

```cpp
static PointF System::Drawing::PointF::Subtract(const PointF &point, const SizeF &size)
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| point | const [PointF](../)\& | Punkten att översätta |
| size | const [SizeF](../../sizef/)\& | Det [SizeF](../../sizef/)-objektet som specificerar värdena att subtrahera från koordinatvärdena för **point** |

### Returvärde

Ett nytt [PointF](../)-objekt vars X-koordinatvärde är lika med resultatet av subtraktionen av breddvärdet för **size** från X-koordinatvärdet för **point** och Y-koordinatvärdet är lika med resultatet av subtraktionen av höjdvärdet för **size** från Y-koordinatvärdet för **point**.

## PointF::Subtract(const PointF\&, const Size\&) metod

Subtraherar bredd- och höjdvärden för det angivna [Size](../../size/)-objektet från X- och Y-koordinatvärdena för det angivna [PointF](../)-objektet respektive.

```cpp
static PointF System::Drawing::PointF::Subtract(const PointF &point, const Size &size)
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| point | const [PointF](../)\& | Punkten att översätta |
| size | const [Size](../../size/)\& | Det [Size](../../size/)-objektet som specificerar värdena att subtrahera från koordinatvärdena för **point** |

### Returvärde

Ett nytt [PointF](../)-objekt vars X-koordinatvärde är lika med resultatet av subtraktionen av breddvärdet för **size** från X-koordinatvärdet för **point** och Y-koordinatvärdet är lika med resultatet av subtraktionen av höjdvärdet för **size** från Y-koordinatvärdet för **point**.

## Se även

* Klass [PointF](../)
* Klass [SizeF](../../sizef/)
* Klass [Size](../../size/)
* Namnrymd [System::Drawing](../../)
* Bibliotek [Aspose.Slides](../../../)