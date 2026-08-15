---
title: VerifySetDefaults()
second_title: Aspose.Slides for C++ API 參考
description: 驗證並設定預設屬性的值。
type: docs
weight: 482
url: /zh-hant/system.net/cookie/verifysetdefaults/
---
## Cookie::VerifySetDefaults(CookieVariant, System::SharedPtr\<Uri\>, bool, String, bool, bool) 方法

驗證並設定預設屬性的值。

```cpp
bool System::Net::Cookie::VerifySetDefaults(CookieVariant variant, System::SharedPtr<Uri> uri, bool isLocalDomain, String localDomain, bool setDefault, bool shouldThrow)
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| variant | [CookieVariant](../../cookievariant/) | Cookie 的規範。 |
| uri | [System::SharedPtr](../../../system/sharedptr/)\<[Uri](../../../system/uri/)\> | 用於初始化內部欄位的 Uri 類別實例。 |
| isLocalDomain | **bool** | 指示 cookie 是否被推送至本地域的值。 |
| localDomain | [String](../../../system/string/) | 本地域名稱。 |
| setDefault | **bool** | 指示是否必須使用預設值來初始化 cookie 的屬性。 |
| shouldThrow | **bool** | 指示在指定的值無效時是否應拋出例外。 |

### 返回值

當所有值皆有效時為 true，否則為 false。

## 另見

* Enum [CookieVariant](../../cookievariant/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Uri](../../../system/uri/)
* Class [String](../../../system/string/)
* Class [Cookie](../)
* Namespace [System::Net](../../)
* Library [Aspose.Slides](../../../)