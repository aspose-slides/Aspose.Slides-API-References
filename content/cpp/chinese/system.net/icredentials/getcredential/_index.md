---
title: GetCredential()
second_title: Aspose.Slides C++ API 参考
description: 返回指定 URI 和身份验证类型的凭据。
type: docs
weight: 1
url: /zh/system.net/icredentials/getcredential/
---
## ICredentials::GetCredential(System::SharedPtr\<Uri\>, String) 方法

返回指定 URI 和身份验证类型的凭据。

```cpp
virtual System::SharedPtr<NetworkCredential> System::Net::ICredentials::GetCredential(System::SharedPtr<Uri> uri, String authType)=0
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| uri | [System::SharedPtr](../../../system/sharedptr/)\<[Uri](../../../system/uri/)\> | 客户端为其提供身份验证类型的 URI。 |
| authType | [String](../../../system/string/) | 身份验证类型。 |

## 另请参见

* Typedef [SharedPtr](../../../system/sharedptr/)
* 类 [NetworkCredential](../../networkcredential/)
* 类 [Uri](../../../system/uri/)
* 类 [String](../../../system/string/)
* 类 [ICredentials](../)
* 命名空间 [System::Net](../../)
* Library [Aspose.Slides](../../../)