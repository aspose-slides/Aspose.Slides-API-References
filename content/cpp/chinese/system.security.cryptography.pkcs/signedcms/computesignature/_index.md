---
title: ComputeSignature()
second_title: Aspose.Slides C++ API 参考
description: 创建签名。
type: docs
weight: 14
url: /zh/system.security.cryptography.pkcs/signedcms/computesignature/
---
## SignedCms::ComputeSignature(const SharedPtr\<CmsSigner\>\&, bool) 方法

创建签名。

```cpp
void System::Security::Cryptography::Pkcs::SignedCms::ComputeSignature(const SharedPtr<CmsSigner> &signer, bool silent)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| signer | const [SharedPtr](../../../system/sharedptr/)\<[CmsSigner](../../cmssigner/)\>\& | 要使用的签名者。 |
| silent | **bool** | 如果与 **signer** 关联的证书无效，是否抑制向用户请求有效证书。 |

## 另见

* Typedef [SharedPtr](../../../system/sharedptr/)
* 类 [CmsSigner](../../cmssigner/)
* 类 [SignedCms](../)
* 命名空间 [System::Security::Cryptography::Pkcs](../../)
* 库 [Aspose.Slides](../../../)