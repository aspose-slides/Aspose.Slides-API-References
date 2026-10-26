---
title: PaddingMode
second_title: Aspose.Slides C++ API 参考
description: 定义如何处理比加密操作所需块更短的消息。
type: docs
weight: 950
url: /zh/system.security.cryptography/paddingmode/
---
## PaddingMode 枚举

Defines how to treat messages that is shorter than block required by crypto operation.s.

```cpp
enum class PaddingMode
```

### 值

| Name | Value | Description |
| --- | --- | --- |
| None | 1 | No padding. |
| PKCS7 | 2 | Use PKCS #7 padding string. |
| Zeros | 3 | Use zero bytes. |
| ANSIX923 | 4 | Use ANSIX923 padding string. |
| ISO10126 | 5 | Use ISO10126 padding string. |

## 另请参见

* 命名空间 [System::Security::Cryptography](../)
* 库 [Aspose.Slides](../../)