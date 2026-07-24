---
title: FileMode
second_title: Aspose.Slides for C++ API Referansı
description: Bir dosyanın nasıl açılması gerektiğini belirtir.
type: docs
weight: 508
url: /tr/system.io/filemode/
---
## FileMode enum

Bir dosyanın nasıl açılması gerektiğini belirtir.

```cpp
enum class FileMode
```

### Değerler

| Ad | Değer | Açıklama |
| --- | --- | --- |
| CreateNew | 1 | Yeni bir dosya oluşturur. Dosya zaten mevcutsa bir istisna fırlatılır. |
| Create | 2 | Yeni bir dosya oluşturur. Dosya zaten mevcutsa üzerine yazılır. |
| Open | 3 | Mevcut bir dosyayı açar. Dosya mevcut değilse bir istisna fırlatılır. |
| OpenOrCreate | 4 | Mevcut bir dosyayı açar veya dosya mevcut değilse yeni bir tane oluşturur. |
| Truncate | 5 | Mevcut bir dosyayı açar ve boş olacağı şekilde kesin küçültür. Dosya mevcut değilse bir istisna fırlatılır. |
| Append | 6 | Mevcut bir dosyayı açar ve sonuna konumlanır veya dosya mevcut değilse yeni bir tane oluşturur. |

## Ayrıca Bakınız

* AdAlanı [System::IO](../)
* Kitaplık [Aspose.Slides](../../)