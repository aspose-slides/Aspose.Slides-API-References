---
title: CipherMode
second_title: Aspose.Slides for C++ API Reference
description: Block cipher mode.
type: docs
weight: 885
url: /system.security.cryptography/ciphermode/
---
## CipherMode enum


Block cipher mode.

```cpp
enum class CipherMode
```

### Values

| Name | Value | Description |
| --- | --- | --- |
| CBC | 1 | Cipher block chaining which combines current block with previous block to improve encryption. |
| ECB | 2 | Electronic codebook mode with no inter-block influences; results in weaker encryption. |
| OFB | 3 | Output feedback mode that handles large input blocks in small pieces. |
| CFB | 4 | Cipher feedback mode that handles large input blocks in small pieces. Mangling rules differ from such of OFB. |
| CTS | 5 | Cipher text stealing mode, behaves like CBC for all but two last blocks of text. |

## See Also

* Namespace [System::Security::Cryptography](../)
* Library [Aspose.Slides](../../)