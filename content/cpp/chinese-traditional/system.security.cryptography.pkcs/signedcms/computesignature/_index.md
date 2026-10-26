---
title: ComputeSignature()
second_title: Aspose.Slides for C++ API 參考文件
description: 建立簽章。
type: docs
weight: 14
url: /zh-hant/system.security.cryptography.pkcs/signedcms/computesignature/
---
## SignedCms::ComputeSignature(const SharedPtr\<CmsSigner\>\&, bool) 方法

建立簽章。

```cpp
void System::Security::Cryptography::Pkcs::SignedCms::ComputeSignature(const SharedPtr<CmsSigner> &signer, bool silent)
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| signer | const [SharedPtr](../../../system/sharedptr/)\<[CmsSigner](../../cmssigner/)\>\& | 要使用的 signer。 |
| silent | **bool** | 是否在與 **signer** 相關聯的憑證無效時，抑制向使用者詢問有效憑證。 |

## 另請參閱

* 類型定義 [SharedPtr](../../../system/sharedptr/)
* 類別 [CmsSigner](../../cmssigner/)
* 類別 [SignedCms](../)
* 命名空間 [System::Security::Cryptography::Pkcs](../../)
* 程式庫 [Aspose.Slides](../../../)