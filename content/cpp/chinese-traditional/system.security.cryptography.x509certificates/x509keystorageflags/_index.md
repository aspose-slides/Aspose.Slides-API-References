---
title: X509KeyStorageFlags
second_title: Aspose.Slides for C++ API 參考
description: 定義金鑰的儲存方式。
type: docs
weight: 261
url: /zh-hant/system.security.cryptography.x509certificates/x509keystorageflags/
---
## X509KeyStorageFlags 列舉

定義金鑰的儲存方式。

```cpp
enum class X509KeyStorageFlags : int32_t
```

### 值

| 名稱 | 值 | 描述 |
| --- | --- | --- |
| DefaultKeySet | 0 | 使用預設金鑰集合。 |
| UserKeySet | 1 | 使用與使用者相關的儲存區，而非機器本機的。 |
| MachineKeySet | 2 | 使用本機機器儲存區，而非使用者的。 |
| Exportable | 4 | 將匯入的金鑰標記為可匯出。 |
| UserProtected | 8 | 通知使用者金鑰正在被使用。 |
| PersistKeySet | 16 | 匯入憑證時會持久保存金鑰。 |

## 另請參閱

* 命名空間 [System::Security::Cryptography::X509Certificates](../)
* 函式庫 [Aspose.Slides](../../)