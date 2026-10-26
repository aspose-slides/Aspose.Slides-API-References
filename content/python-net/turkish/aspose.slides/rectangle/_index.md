---
title: Rectangle class
second_title: Aspose.Slides for Python via .NET API Referansı
description: Bir dikdörtgenin konum ve boyutunu temsil eden dört tamsayı setini saklar.
type: docs
url: /tr/aspose.slides/rectangle/
net_type: System.Drawing.Rectangle
---
## Rectangle sınıfı

Bir dikdörtgenin konum ve boyutunu temsil eden dört tamsayı setini saklar. .NET `System.Drawing.Rectangle` ile uyumludur.

`Rectangle` tipi aşağıdaki üyeleri sunar:

## Yapıcılar

| Constructor | Description |
| :- | :- |
| [`__init__(self, x=0, y=0, width=0, height=0)`](/slides/python-net/tr/aspose.slides/rectangle/__init__/#int-int-int-int) | Belirtilen konum ve boyuta sahip bir dikdörtgen oluşturur. Ondalık değerler tamsayılara kırpılır. |

## Özellikler

| Property | Description |
| :- | :- |
| [`x`](/slides/python-net/tr/aspose.slides/rectangle/x/) | Bu dikdörtgenin sol üst köşesinin x koordinatını alır.<br/>            Yalnızca okunabilir **int**. |
| [`y`](/slides/python-net/tr/aspose.slides/rectangle/y/) | Bu dikdörtgenin sol üst köşesinin y koordinatını alır.<br/>            Yalnızca okunabilir **int**. |
| [`width`](/slides/python-net/tr/aspose.slides/rectangle/width/) | Bu dikdörtgenin genişliğini alır.<br/>            Yalnızca okunabilir **int**. |
| [`height`](/slides/python-net/tr/aspose.slides/rectangle/height/) | Bu dikdörtgenin yüksekliğini alır.<br/>            Yalnızca okunabilir **int**. |
| [`left`](/slides/python-net/tr/aspose.slides/rectangle/left/) | Bu dikdörtgenin sol kenarının x koordinatını alır. `x`'e eşittir.<br/>            Yalnızca okunabilir **int**. |
| [`top`](/slides/python-net/tr/aspose.slides/rectangle/top/) | Bu dikdörtgenin üst kenarının y koordinatını alır. `y`'e eşittir.<br/>            Yalnızca okunabilir **int**. |
| [`right`](/slides/python-net/tr/aspose.slides/rectangle/right/) | Bu dikdörtgenin `x` ve `width` toplamı olan x koordinatını alır.<br/>            Yalnızca okunabilir **int**. |
| [`bottom`](/slides/python-net/tr/aspose.slides/rectangle/bottom/) | Bu dikdörtgenin `y` ve `height` toplamı olan y koordinatını alır.<br/>            Yalnızca okunabilir **int**. |
| [`is_empty`](/slides/python-net/tr/aspose.slides/rectangle/is_empty/) | Bu dikdörtgenin tüm sayısal özelliklerinin sıfır değerine sahip olup olmadığını belirtir.<br/>            Yalnızca okunabilir **bool**. |

## Yöntemler

| Method | Description |
| :- | :- |
| [`contains(self, x, y)`](/slides/python-net/tr/aspose.slides/rectangle/contains/#int-int) | Belirtilen noktanın bu dikdörtgen içinde olup olmadığını belirler. |
| [`contains(self, point)`](/slides/python-net/tr/aspose.slides/rectangle/contains/#point) | Belirtilen noktanın bu dikdörtgen içinde olup olmadığını belirler. |
| [`contains(self, rect)`](/slides/python-net/tr/aspose.slides/rectangle/contains/#rectangle) | `rect` tarafından temsil edilen dikdörtgen bölgenin tamamen bu dikdörtgen içinde olup olmadığını belirler. |

### Açıklamalar

Dikdörtgenler konum ve boyutlarıyla `==` ile karşılaştırılır ve sözlük anahtarları veya küme üyeleri olarak kullanılabilir.

### Ayrıca Bakınız
* modül [`aspose.slides`](/slides/python-net/tr/aspose.slides)
* kütüphane [`Aspose.Slides`](/slides/python-net)