---
title: "System::Net::Security"
second_title: Aspose.Slides for C++ API 參考文件
description: 
type: docs
weight: 716
url: /zh-hant/system.net.security/
---
## 類別

| 類別 | 說明 |
| --- | --- |
| [AuthenticatedStream](./authenticatedstream/) | 包含在串流中傳遞認證的相關方法。此類別的物件應僅透過 [System::MakeObject()](../system/makeobject/) 函式來配置。切勿在堆疊上或使用 operator new 建立此類型的實例，因會導致執行時錯誤和/或斷言失敗。應始終將此類別包裝成 [System::SmartPtr](../system/smartptr/) 指標，並使用該指標作為參數傳遞給函式。 |
| [SslStream](./sslstream/) | 使用 SSL 協定驗證伺服器，並可選擇性驗證客戶端的串流。 |

## 列舉型別

| 列舉 | 說明 |
| --- | --- |
| [AuthenticationLevel](./authenticationlevel/) | WebRequest 專用的驗證旗標。 |
| [SslPolicyErrors](./sslpolicyerrors/) | 列舉 SSL 的政策錯誤。 |
| [EncryptionPolicy](./encryptionpolicy/) | 列舉加密政策。 |

## 型別定義

| 型別定義 | 說明 |
| --- | --- |
| [RemoteCertificateValidationCallback](./remotecertificatevalidationcallback/) | 用於驗證遠端 SSL 憑證的使用者委託。 |
| [LocalCertificateSelectionCallback](./localcertificateselectioncallback/) | 用於選取本機 SSL 憑證的使用者委託。 |