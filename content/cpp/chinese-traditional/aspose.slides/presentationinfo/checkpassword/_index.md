---
title: CheckPassword()
second_title: Aspose.Slides for C++ API 參考
description: 檢查受開放密碼保護的簡報，其密碼是否正確。
type: docs
weight: 53
url: /zh-hant/aspose.slides/presentationinfo/checkpassword/
---
## PresentationInfo::CheckPassword(System::String) 方法

檢查受開放密碼保護的簡報，其密碼是否正確。

```cpp
bool Aspose::Slides::PresentationInfo::CheckPassword(System::String password) override
```

### 參數

| Parameter | Type | Description |
| --- | --- | --- |
| password | [System::String](../../../system/string/) | 要檢查的密碼。 |

### 回傳值

如果簡報受到開放密碼保護且密碼正確，則返回 true，否則返回 false。

## 備註

```cpp
auto info = PresentationFactory::get_Instance()->GetPresentationInfo(u"pres.pptx");
bool isPasswordCorrect = info->CheckPassword(u"my_password");
```

當密碼為 null 或空字串時，此方法返回 false。

## 另見

* 類別 [String](../../../system/string/)
* 類別 [PresentationInfo](../)
* 命名空間 [Aspose::Slides](../../)
* 函式庫 [Aspose.Slides](../../../)