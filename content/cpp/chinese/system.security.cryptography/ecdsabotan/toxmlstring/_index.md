---
title: ToXmlString()
second_title: Aspose.Slides C++ API 参考
description: 以 XML 格式导出所有参数。未实现。
type: docs
weight: 157
url: /zh/system.security.cryptography/ecdsabotan/toxmlstring/
---
## ECDsaBotan::ToXmlString(bool) 方法

以 XML 格式导出所有参数。未实现。

```cpp
String System::Security::Cryptography::ECDsaBotan::ToXmlString(bool include_private_parameters) override
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| include_private_parameters | **bool** | True 导出私有和公共参数，false 仅导出公共参数。 |

### 返回值

XML 编码的参数。

## ECDsaBotan::ToXmlString(ECKeyXmlFormat) 方法

以 XML 格式导出所有参数。

```cpp
String System::Security::Cryptography::ECDsaBotan::ToXmlString(ECKeyXmlFormat format)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| format | [ECKeyXmlFormat](../../eckeyxmlformat/) | 结果 XML 字符串的格式。 |

### 返回值

XML 编码的参数。

## 另请参见

* Enum [ECKeyXmlFormat](../../eckeyxmlformat/)
* 类 [String](../../../system/string/)
* 类 [ECDsaBotan](../)
* 命名空间 [System::Security::Cryptography](../../)
* 库 [Aspose.Slides](../../../)