---
title: EncryptionPolicy
second_title: Aspose.Slides C++ API 參考
description: 列舉加密策略。
type: docs
weight: 53
url: /zh-hant/system.net.security/encryptionpolicy/
---
## EncryptionPolicy 列舉

列舉加密策略。

```cpp
enum class EncryptionPolicy
```

### 值

| 名稱 | 值 | 描述 |
| --- | --- | --- |
| RequireEncryption | 0 | 要求加密，且永不允許 'Null' 密碼。 |
| AllowNoEncryption | 1 | 偏好使用完整加密，但若伺服器同意，可使用 'Null' 密碼。 |
| NoEncryption | 2 | 允許不加密，並請求在另一端點能處理 'Null' 密碼時使用 'Null' 密碼。 |

## 參見

* 命名空間 [System::Net::Security](../)
* 函式庫 [Aspose.Slides](../../)