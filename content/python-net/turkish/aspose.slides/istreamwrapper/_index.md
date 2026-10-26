---
title: IStreamWrapper class
second_title: Aspose.Slides for Python via .NET API Referansı
description: 
type: docs
url: /tr/aspose.slides/istreamwrapper/
---
## IStreamWrapper sınıf

Aspose.IO.Stream sarmalayıcısı için COM arabirimi.

IStreamWrapper türü aşağıdaki üyeleri sunar:

## Özellikler

| Özellik | Açıklama |
| :- | :- |
| [`stream`](/slides/python-net/tr/aspose.slides/istreamwrapper/stream/) | Bir akış alır.<br/>            Yalnızca okuma **io.RawIOBase**. |
| [`can_read`](/slides/python-net/tr/aspose.slides/istreamwrapper/can_read/) | Mevcut akışın okuma desteği olup olmadığını gösteren bir değer alır.<br/>            Yalnızca okuma **bool**. |
| [`can_seek`](/slides/python-net/tr/aspose.slides/istreamwrapper/can_seek/) | Mevcut akışın konumlandırma desteği olup olmadığını gösteren bir değer alır.<br/>            Yalnızca okuma **bool**. |
| [`can_write`](/slides/python-net/tr/aspose.slides/istreamwrapper/can_write/) | Mevcut akışın yazma desteği olup olmadığını gösteren bir değer alır.<br/>            Yalnızca okuma **bool**. |
| [`length`](/slides/python-net/tr/aspose.slides/istreamwrapper/length/) | Akışın bayt cinsinden uzunluğunu alır.<br/>            Yalnızca okuma **int**. |
| [`position`](/slides/python-net/tr/aspose.slides/istreamwrapper/position/) | Mevcut akış içindeki konumu alır.<br/>            Yalnızca okuma **int**. |

## Yöntemler

| Yöntem | Açıklama |
| :- | :- |
| [`close(self)`](/slides/python-net/tr/aspose.slides/istreamwrapper/close/#) | Mevcut akışı kapatır ve tüm kaynakları serbest bırakır. |
| [`flush(self)`](/slides/python-net/tr/aspose.slides/istreamwrapper/flush/#) | Bu akış için tüm tamponları temizler ve tamponlanmış verilerin temel cihaza yazılmasını sağlar. |
| [`read(self, buffer, offset, count)`](/slides/python-net/tr/aspose.slides/istreamwrapper/read/#bytes-int-int) | Mevcut akıştan bir bayt dizisi okur ve okunan bayt sayısı kadar akış konumunu ilerletir. |
| [`read_byte(self)`](/slides/python-net/tr/aspose.slides/istreamwrapper/read_byte/#) | Akıştan bir bayt okur ve akış konumunu bir bayt ilerletir; akışın sonunda ise -1 döndürür. |
| [`seek(self, offset, origin)`](/slides/python-net/tr/aspose.slides/istreamwrapper/seek/#int-systemioseekorigin) | Mevcut akış içindeki konumu ayarlar |
| [`write(self, buffer, offset, count)`](/slides/python-net/tr/aspose.slides/istreamwrapper/write/#bytes-int-int) | akışa bir bayt dizisi yazar ve bu akıştaki mevcut konumu yazılan bayt sayısı kadar ilerletir. |
| [`write_byte(self, value)`](/slides/python-net/tr/aspose.slides/istreamwrapper/write_byte/#int) | Akıştaki mevcut konuma bir bayt yazar ve akış konumunu bir bayt ilerletir. |


### Ayrıca Bakınız
* modül [`aspose.slides`](/slides/python-net/tr/aspose.slides)
* kütüphane [`Aspose.Slides`](/slides/python-net)