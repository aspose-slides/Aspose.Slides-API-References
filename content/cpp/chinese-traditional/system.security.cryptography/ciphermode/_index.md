---
title: CipherMode
second_title: Aspose.Slides for C++ API 參考
description: 區塊加密模式。
type: docs
weight: 885
url: /zh-hant/system.security.cryptography/ciphermode/
---
## CipherMode 列舉

區塊加密模式。

```cpp
enum class CipherMode
```

### 值

| 名稱 | 值 | 說明 |
| --- | --- | --- |
| CBC | 1 | 密碼區塊鏈結（Cipher block chaining），將當前區塊與前一個區塊結合以提升加密效果。 |
| ECB | 2 | 電子代碼本模式（Electronic codebook），沒有區塊間的相互影響；導致較弱的加密。 |
| OFB | 3 | 輸出回授模式（Output feedback），將大輸入區塊分割成小塊處理。 |
| CFB | 4 | 密碼回授模式（Cipher feedback），將大輸入區塊分割成小塊處理。其混淆規則與 OFB 不同。 |
| CTS | 5 | 密碼文字盜取模式（Cipher text stealing），除了最後兩個區塊外，行為與 CBC 相同。 |

## 另請參閱

* 命名空間 [System::Security::Cryptography](../)
* 函式庫 [Aspose.Slides](../../)