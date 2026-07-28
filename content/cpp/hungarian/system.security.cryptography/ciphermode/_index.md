---
title: CipherMode
second_title: Aspose.Slides a C++ API Referenciához
description: Blokk titkosítási mód.
type: docs
weight: 885
url: /hu/system.security.cryptography/ciphermode/
---
## CipherMode enum

Block cipher mode.

```cpp
enum class CipherMode
```

### Értékek

| Név | Érték | Leírás |
| --- | --- | --- |
| CBC | 1 | Cipher block chaining, amely a jelenlegi blokkot az előző blokkhoz kapcsolja a titkosítás javítása érdekében. |
| ECB | 2 | Electronic codebook mód, amely nem alkalmaz blokkok közötti hatásokat; gyengébb titkosítást eredményez. |
| OFB | 3 | Output feedback mód, amely nagy bemeneti blokkokat kis darabokra bontva dolgoz fel. |
| CFB | 4 | Cipher feedback mód, amely nagy bemeneti blokkokat kis darabokra bontva dolgoz fel. A manipulációs szabályok különböznek az OFB-től. |
| CTS | 5 | Cipher text stealing mód, amely a szöveg utolsó két blokkja kivételével úgy viselkedik, mint a CBC. |

## Lásd még

* Névtér [System::Security::Cryptography](../)
* Könyvtár [Aspose.Slides](../../)