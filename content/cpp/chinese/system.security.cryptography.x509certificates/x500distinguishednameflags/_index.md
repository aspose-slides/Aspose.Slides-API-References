---
title: X500DistinguishedNameFlags
second_title: Aspose.Slides C++ API 参考
description: X509 证书可辨识名称的格式规则。
type: docs
weight: 209
url: /zh/system.security.cryptography.x509certificates/x500distinguishednameflags/
---
## X500DistinguishedNameFlags 枚举

X509 证书的可辨识名称格式规则。

```cpp
enum class X500DistinguishedNameFlags
```

### 值

| 名称 | 值 | 描述 |
| --- | --- | --- |
| None | 0 | 没有特殊特性。 |
| Reversed | 1 | 名称已保留。 |
| UseSemicolons | 16 | 使用分号。 |
| DoNotUsePlusSign | 32 | 名称不使用加号。 |
| DoNotUseQuotes | 64 | 禁用名称中的引号。 |
| UseCommas | 128 | 启用使用逗号。 |
| UseNewLines | 256 | 启用使用换行。 |
| UseUTF8Encoding | 4096 | 从使用 Unicode 切换为使用 UTF-8 编码。 |
| UseT61Encoding | 8192 | 切换到 T61 编码。 |
| ForceUTF8Encoding | 16384 | 在对特定 X500 键进行编码时强制使用 UTF-8。 |

## 参见

* 命名空间 [System::Security::Cryptography::X509Certificates](../)
* 库 [Aspose.Slides](../../)