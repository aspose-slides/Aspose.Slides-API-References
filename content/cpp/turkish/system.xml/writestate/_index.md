---
title: WriteState
second_title: Aspose.Slides için C++ API Referansı
description: XmlWriter'ın durumunu belirler.
type: docs
weight: 755
url: /tr/system.xml/writestate/
---
## WriteState enum

[XmlWriter](../xmlwriter/)'in durumunu belirler.

```cpp
enum class WriteState
```

### Değerler

| Ad | Değer | Açıklama |
| --- | --- | --- |
| Start | 0 | XmlWriter::Write yöntemi henüz çağrılmadığını gösterir. |
| Prolog | 1 | Prologun yazıldığını gösterir. |
| Element | 2 | Bir öğe başlangıç etiketinin yazıldığını gösterir. |
| Attribute | 3 | Bir öznitelik değerinin yazıldığını gösterir. |
| Content | 4 | Öğe içeriğinin yazıldığını gösterir. |
| Closed | 5 | [XmlWriter::Close](../xmlwriter/close/) yönteminin çağrıldığını gösterir. |
| Error | 6 | Bir istisna fırlatıldı ve bu, [XmlWriter](../xmlwriter/)'ı geçersiz bir duruma bıraktı. [XmlWriter::Close](../xmlwriter/close/) yöntemini çağırarak [XmlWriter](../xmlwriter/)'ı [WriteState::Closed](./) durumuna getirebilirsiniz. Başka herhangi bir [XmlWriter](../xmlwriter/) yöntemi çağrısı InvalidOperationException ile sonuçlanır. |

## Ayrıca Bakınız

* Ad alanı [System::Xml](../)
* Kütüphane [Aspose.Slides](../../)