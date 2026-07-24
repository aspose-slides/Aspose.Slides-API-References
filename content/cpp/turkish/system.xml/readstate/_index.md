---
title: ReadState
second_title: Aspose.Slides için C++ API Referansı
description: Okuyucunun durumunu belirtir.
type: docs
weight: 703
url: /tr/system.xml/readstate/
---
## ReadState enum

Okuyucunun durumunu belirtir.

```cpp
enum class ReadState
```

### Değerler

| Ad | Değer | Açıklama |
| --- | --- | --- |
| Initial | 0 | [XmlReader::Read](../xmlreader/read/) yöntemi çağrılmadı. |
| Interactive | 1 | [XmlReader::Read](../xmlreader/read/) yöntemi çağrıldı. Okuyucu üzerinde ek yöntemler çağrılabilir. |
| Error | 2 | Okuma işleminin devam etmesini engelleyen bir hata oluştu. |
| EndOfFile | 3 | Dosyanın sonuna başarıyla ulaşıldı. |
| Closed | 4 | [XmlReader::Close](../xmlreader/close/) yöntemi çağrıldı. |

## Ayrıca Bakınız

* Ad alanı [System::Xml](../)
* Kütüphane [Aspose.Slides](../../)