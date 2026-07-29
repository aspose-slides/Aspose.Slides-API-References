---
title: Add()
second_title: Aspose.Slides för C++ API-referens
description: Lägger till bredd- och höjdvärden för det angivna SizeF-objektet till X- och Y-koordinatvärdena för det angivna PointF-objektet respektive.
type: docs
weight: 144
url: /sv/system.drawing/pointf/add/
---
## PointF::Add(const PointF\&, const SizeF\&) metod

Lägger till bredd- och höjdvärden för det angivna [SizeF](../../sizef/)-objektet till X- och Y-koordinatvärdena för det angivna [PointF](../)-objektet respektive.

```cpp
static PointF System::Drawing::PointF::Add(const PointF &point, const SizeF &size)
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| point | const [PointF](../)\& | Punkten att förflytta |
| size | const [SizeF](../../sizef/)\& | Det [SizeF](../../sizef/)-objektet som specificerar värdena att lägga till koordinatavärdena för **point** |

### Returvärde

Ett nytt [PointF](../)-objekt vars X-koordinatvärde är lika med summan av X-koordinatvärdet för **point** och breddvärdet för **size** samt Y-koordinatvärdet är lika med summan av Y-koordinatvärdet för **point** och höjdvärdet för **size**.

## PointF::Add(const PointF\&, const Size\&) metod

Lägger till bredd- och höjdvärden för det angivna [Size](../../size/)-objektet till X- och Y-koordinatvärdena för det angivna [PointF](../)-objektet respektive.

```cpp
static PointF System::Drawing::PointF::Add(const PointF &point, const Size &size)
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| point | const [PointF](../)\& | Punkten att förflytta |
| size | const [Size](../../size/)\& | Det [Size](../../size/)-objektet som specificerar värdena att lägga till koordinatavärdena för **point** |

### Returvärde

Ett nytt [PointF](../)-objekt vars X-koordinatvärde är lika med summan av X-koordinatvärdet för **point** och breddvärdet för **size** samt Y-koordinatvärdet är lika med summan av Y-koordinatvärdet för **point** och höjdvärdet för **size**.

## Se även

* Klass [PointF](../)
* Klass [SizeF](../../sizef/)
* Klass [Size](../../size/)
* Namnrymd [System::Drawing](../../)
* Bibliotek [Aspose.Slides](../../../)