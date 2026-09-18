---
title: StreamWrapper class
second_title: Aspose.Slides for Python via .NET API Referansı
description: 
type: docs
url: /tr/aspose.slides/streamwrapper/
---
## StreamWrapper sınıfı

Aspose.IO.Stream wrapper for COM interface.

The StreamWrapper type exposes the following members:

## Özellikler

| Property | Description |
| :- | :- |
| [`stream`](/slides/python-net/tr/aspose.slides/streamwrapper/stream/) | Akışı alır.<br/>            Yalnızca-okunur **io.RawIOBase**. |
| [`can_read`](/slides/python-net/tr/aspose.slides/streamwrapper/can_read/) | Mevcut akışın okuma destekleyip desteklemediğini gösteren bir değer alır.<br/>            Yalnızca-okunur **bool**. |
| [`can_seek`](/slides/python-net/tr/aspose.slides/streamwrapper/can_seek/) | Mevcut akışın konumlama destekleyip desteklemediğini gösteren bir değer alır.<br/>            Yalnızca-okunur **bool**. |
| [`can_write`](/slides/python-net/tr/aspose.slides/streamwrapper/can_write/) | Mevcut akışın yazma destekleyip desteklemediğini gösteren bir değer alır.<br/>            Yalnızca-okunur **bool**. |
| [`length`](/slides/python-net/tr/aspose.slides/streamwrapper/length/) | Akışın bayt cinsinden uzunluğunu alır.<br/>            Yalnızca-okunur **int**. |
| [`position`](/slides/python-net/tr/aspose.slides/streamwrapper/position/) | Mevcut akış içindeki konumu alır veya ayarlar.<br/>            Yalnızca-okunur **int**. |

## Yöntemler

| Method | Description |
| :- | :- |
| [`close(self)`](/slides/python-net/tr/aspose.slides/streamwrapper/close/#) | Mevcut akışı kapatır ve tüm kaynakları serbest bırakır. |
| [`flush(self)`](/slides/python-net/tr/aspose.slides/streamwrapper/flush/#) | Bu akış için tüm tamponları temizler ve tamponlanmış verilerin alt aygıta yazılmasını sağlar. |
| [`read(self, buffer, offset, count)`](/slides/python-net/tr/aspose.slides/streamwrapper/read/#bytes-int-int) | Mevcut akıştan bir dizi bayt okur ve akış içindeki konumu okunan bayt sayısı kadar ilerletir. |
| [`read_byte(self)`](/slides/python-net/tr/aspose.slides/streamwrapper/read_byte/#) | Akıştan bir bayt okur ve konumu bir bayt ilerletir; akışın sonundayken -1 döndürür. |
| [`seek(self, offset, origin)`](/slides/python-net/tr/aspose.slides/streamwrapper/seek/#int-systemioseekorigin) | Mevcut akış içindeki konumu ayarlar |
| [`write(self, buffer, offset, count)`](/slides/python-net/tr/aspose.slides/streamwrapper/write/#bytes-int-int) | Mevcut akışa bir dizi bayt yazar ve bu akıştaki konumu yazılan bayt sayısı kadar ilerletir. |
| [`write_byte(self, value)`](/slides/python-net/tr/aspose.slides/streamwrapper/write_byte/#int) | Akıştaki mevcut konuma bir bayt yazar ve konumu bir bayt ilerletir. |

### Diğer Bağlantılar
* modül [`aspose.slides`](/slides/python-net/tr/aspose.slides)
* kütüphane [`Aspose.Slides`](/slides/python-net)