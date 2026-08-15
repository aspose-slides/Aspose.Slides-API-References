---
title: SecureStringToGlobalAllocAnsi()
second_title: Aspose.Slides for C++ API 參考
description: 將指定安全字串的內容複製到非受管理的記憶體中，並轉換為 ANSI 格式。
type: docs
weight: 157
url: /zh-hant/system.runtime.interopservices/marshal/securestringtoglobalallocansi/
---
## Marshal::SecureStringToGlobalAllocAnsi(const SharedPtr\<Security::SecureString\>\&) 方法

將指定的安全字串內容複製到非受管理的記憶體中，並轉換為 ANSI 格式。

```cpp
static IntPtr System::Runtime::InteropServices::Marshal::SecureStringToGlobalAllocAnsi(const SharedPtr<Security::SecureString> &s)
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| s | const [SharedPtr](../../../system/sharedptr/)\<[Security::SecureString](../../../system.security/securestring/)\>\& | 安全字串。 |

### 傳回值

非受管理記憶體中的位址。

## 參見

* Typedef [SharedPtr](../../../system/sharedptr/)
* 類別 [SecureString](../../../system.security/securestring/)
* 類別 [Marshal](../)
* 命名空間 [System::Runtime::InteropServices](../../)
* 函式庫 [Aspose.Slides](../../../)