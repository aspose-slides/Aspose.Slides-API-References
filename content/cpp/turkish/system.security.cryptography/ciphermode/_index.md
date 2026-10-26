---
title: CipherMode
second_title: Aspose.Slides for C++ API Referansı
description: Blok şifreleme modu.
type: docs
weight: 885
url: /tr/system.security.cryptography/ciphermode/
---
## CipherMode enum

Blok şifreleme modu.

```cpp
enum class CipherMode
```

### Değerler

| Ad | Değer | Açıklama |
| --- | --- | --- |
| CBC | 1 | Cipher block chaining, mevcut bloğu önceki blokla birleştirerek şifrelemeyi iyileştirir. |
| ECB | 2 | Electronic codebook modu; bloklar arası etkileşimi yoktur, daha zayıf şifrelemeye yol açar. |
| OFB | 3 | Output feedback modu, büyük giriş bloklarını küçük parçalar halinde işler. |
| CFB | 4 | Cipher feedback modu, büyük giriş bloklarını küçük parçalar halinde işler. Mangling kuralları OFB'den farklıdır. |
| CTS | 5 | Cipher text stealing modu, son iki blok dışındaki tüm bloklar için CBC gibi davranır. |

## See Also

* Ad Alanı [System::Security::Cryptography](../)
* Kütüphane [Aspose.Slides](../../)