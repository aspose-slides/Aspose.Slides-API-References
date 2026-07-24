---
title: Zip64Mode
second_title: Aspose.Slides for C++ API Referansı
description: OpenXML dosyası için ZIP64 format uzantılarını ne zaman kullanılacağını belirtir.
type: docs
weight: 1119
url: /tr/aspose.slides.export/zip64mode/
---
## Zip64Mode enum

Specifies when to use ZIP64 format extensions for OpenXML file.

```cpp
enum class Zip64Mode
```

### Değerler

| Ad | Değer | Açıklama |
| --- | --- | --- |
| Never | 0 | ZIP64 biçim uzantılarını kullanma. |
| IfNecessary | 1 | Gerekirse ZIP64 biçim uzantılarını kullan. |
| Always | 2 | Her zaman ZIP64 biçim uzantılarını kullan. |

## Açıklamalar

OpenXML dosyası, bir dosyanın sıkıştırılmamış boyutu, sıkıştırılmış boyutu ve arşivin toplam boyutu için 4 GB (2^32 bayt) ve arşivdeki dosya sayısı için 65.535 (2^16-1) sınırlamaya sahip bir ZIP arşividir. ZIP64 biçim uzantıları bu sınırlamaları 2^64'e yükseltir. 

## Ayrıca Bakınız

* İsim Alanı [Aspose::Slides::Export](../)
* Kütüphane [Aspose.Slides](../../)