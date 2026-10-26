---
title: CopyPixelOperation
second_title: Aspose.Slides for C++ API Referansı
description: Bir piksel kopyalama işlemi sırasında kaynak rengin hedef renk ile nasıl birleştirildiğini ve nihai bir renk elde edildiğini belirtir.
type: docs
weight: 391
url: /tr/system.drawing/copypixeloperation/
---
## CopyPixelOperation enum

Bir piksel kopyalama işlemi sırasında kaynak rengin, hedef renk ile nasıl birleştirilerek nihai bir renk elde edildiğini belirtir.

```cpp
enum class CopyPixelOperation
```

### Values

| Ad | Değer | Açıklama |
| --- | --- | --- |
| NoMirrorBitmap | n/a | Bit haritası yansıtılmaz. |
| Blackness | 66 | Hedef bölge, fiziksel palet içinde indeks 0 olan renk kullanılarak doldurulur. |
| NotSourceErase | 1114278 | Kaynak ve hedef renkler OR işlemine tabi tutulur ve ortaya çıkan renk daha sonra ters çevrilir. |
| NotSourceCopy | 3342344 | Kaynak bölge ters çevrilir ve ardından hedefe kopyalanır. |
| SourceErase | 4457256 | Hedef bölgenin ters çevrilmiş renkleri, kaynak bölgenin renkleriyle AND işlemine tabi tutulur. |
| DestinationInvert | 5570569 | Hedef bölge ters çevrilir. |
| PatInvert | 5898313 | Hedef cihaz bağlamında şu anda seçili fırçanın renkleri, hedefin renkleriyle XOR işlemine tabi tutulur. |
| SourceInvert | 6684742 | Kaynak ve hedef bölgelerin renkleri XOR işlemine tabi tutulur. |
| SourceAnd | 8913094 | Kaynak ve hedef bölgelerin renkleri AND işlemine tabi tutulur. |
| MergePaint | 12255782 | Ters çevrilmiş kaynak bölgenin renkleri, hedef bölgenin renkleriyle OR işlemine tabi tutulur. |
| MergeCopy | 12583114 | Kaynak bölgenin renkleri, hedef cihaz bağlamında seçili fırçanın renkleriyle AND işlemine tabi tutulur. |
| SourceCopy | 13369376 | Kaynak bölge doğrudan hedef bölgeye kopyalanır. |
| SourcePaint | 15597702 | Kaynak ve hedef bölgelerin renkleri OR işlemine tabi tutulur. |
| PatCopy | 15728673 | Hedef cihaz bağlamında şu anda seçili fırça, hedef bit haritasına kopyalanır. |
| PatPaint | 16452105 | Hedef cihaz bağlamında şu anda seçili fırçanın renkleri, ters çevrilmiş kaynak bölgenin renkleriyle OR işlemine tabi tutulur. Bu işlemin sonucu, hedef bölgenin renkleriyle OR işlemine tabi tutulur. |
| Whiteness | 16711778 | Hedef bölge, fiziksel palet içinde indeks 1 olan renk kullanılarak doldurulur. |
| CaptureBlt | 1073741824 | [Windows](../../system.windows/) uygulama penceresinin üstüne katmanlananlar sonuç görüntüsüne dahil edilir. |

## İlgili

* Ad alanı [System::Drawing](../)
* Kütüphane [Aspose.Slides](../../)