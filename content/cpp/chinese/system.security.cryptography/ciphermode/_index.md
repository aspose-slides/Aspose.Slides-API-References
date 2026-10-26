---
title: CipherMode
second_title: Aspose.Slides C++ API 参考
description: 块密码模式。
type: docs
weight: 885
url: /zh/system.security.cryptography/ciphermode/
---
## CipherMode 枚举

块密码模式。

```cpp
enum class CipherMode
```

### 值

| 名称 | 值 | 描述 |
| --- | --- | --- |
| CBC | 1 | 密码块链式模式，将当前块与前一个块组合以改进加密。 |
| ECB | 2 | 电子密码本模式，没有块间影响；导致加密强度较弱。 |
| OFB | 3 | 输出反馈模式，将大输入块分成小块处理。 |
| CFB | 4 | 密码反馈模式，将大输入块分成小块处理。其混淆规则与 OFB 不同。 |
| CTS | 5 | 密文窃取模式，对除最后两个块之外的所有块表现同 CBC。 |

## 另见

* 命名空间 [System::Security::Cryptography](../)
* 库 [Aspose.Slides](../../)