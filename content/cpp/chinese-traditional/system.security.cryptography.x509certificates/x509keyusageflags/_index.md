---
title: X509KeyUsageFlags
second_title: Aspose.Slides for C++ API 參考文件
description: 定義憑證金鑰的使用方式。
type: docs
weight: 274
url: /zh-hant/system.security.cryptography.x509certificates/x509keyusageflags/
---
## X509KeyUsageFlags 列舉

定義憑證金鑰的使用方式。

```cpp
enum class X509KeyUsageFlags : int32_t
```

### 值

| 名稱 | 值 | 描述 |
| --- | --- | --- |
| None | 0 | 無金鑰使用參數。 |
| EncipherOnly | 1 | 金鑰只能用於加密。 |
| CrlSign | 2 | 金鑰可用於簽署憑證撤銷清單。 |
| KeyCertSign | 4 | 金鑰可用於簽署憑證。 |
| KeyAgreement | 8 | 金鑰可用於協商金鑰。 |
| DataEncipherment | 16 | 金鑰可用於資料加密。 |
| KeyEncipherment | 32 | 金鑰可用於金鑰加密。 |
| NonRepudiation | 64 | 金鑰可用於驗證。 |
| DigitalSignature | 128 | 金鑰可用於數位簽章。 |
| DecipherOnly | 32768 | 金鑰只能用於解密。 |

## 另見

* 命名空間 [System::Security::Cryptography::X509Certificates](../)
* 函式庫 [Aspose.Slides](../../)