---
title: FileOptions
second_title: Aspose.Slides for C++ API Referansı
description: FileStream nesnesi oluşturmak için gelişmiş seçenekleri temsil eder.
type: docs
weight: 521
url: /tr/system.io/fileoptions/
---
## FileOptions enum

[FileStream](../filestream/) nesnesi oluşturmak için gelişmiş seçenekleri temsil eder.

```cpp
enum class FileOptions
```

### Değerler

| Ad | Değer | Açıklama |
| --- | --- | --- |
| None | 0 | Ek bir seçenek yok. |
| Encrypted | 16384 | Dosya şifrelenmiştir. UYGULANMADI. |
| DeleteOnClose | 67108864 | Dosya, artık kullanılmadığında otomatik olarak silinmelidir. |
| SequentialScan | 134217728 | Dosyanın sıralı olarak erişilmesi gerekir. |
| RandomAccess | 268435456 | Dosya rastgele erişilir. |
| Asynchronous | 1073741824 | Dosya, eşzamanlı olmayan I/O işlemleri için kullanılabilir. |
| WriteThrough | n/a | Tüm yazmalar, ara önbelleği atlayarak doğrudan diske gitmelidir. |

## Bakınız

* Namespace [System::IO](../)
* Kütüphane [Aspose.Slides](../../)