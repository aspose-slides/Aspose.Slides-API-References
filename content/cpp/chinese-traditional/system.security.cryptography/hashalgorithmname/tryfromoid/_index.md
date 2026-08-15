---
title: TryFromOid()
second_title: Aspose.Slides for C++ API 參考
description: 嘗試從 OID 值建立 HashAlgorithmName。
type: docs
weight: 66
url: /zh-hant/system.security.cryptography/hashalgorithmname/tryfromoid/
---
## HashAlgorithmName::TryFromOid(const String&, HashAlgorithmName&) 方法

嘗試從 OID-value 建立 [HashAlgorithmName](../)。

```cpp
static bool System::Security::Cryptography::HashAlgorithmName::TryFromOid(const String &oid_value, HashAlgorithmName &value)
```

### 參數

| 參數 | 類型 | 描述 |
| --- | --- | --- |
| oid_value | const [String](../../../system/string/)\& | OID 值。 |
| value | [HashAlgorithmName](../)\& | 輸出 [HashAlgorithmName](../)。 |

### 返回值

如果指定的 OID 是有效的雜湊演算法則返回 true，否則返回 false。

## 另請參閱

* Class [String](../../../system/string/)
* Struct [HashAlgorithmName](../)
* Namespace [System::Security::Cryptography](../../)
* Library [Aspose.Slides](../../../)