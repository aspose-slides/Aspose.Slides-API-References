---
title: CheckPassword()
second_title: Aspose.Slides C++ API 參考
description: 檢查受開啟密碼保護的簡報，其密碼是否正確。
type: docs
weight: 53
url: /zh-hant/aspose.slides/ipresentationinfo/checkpassword/
---
## IPresentationInfo::CheckPassword(System::String) method

檢查受開啟密碼保護的簡報，其密碼是否正確。

```cpp
virtual bool Aspose::Slides::IPresentationInfo::CheckPassword(System::String password)=0
```

### Arguments

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| password | [System::String](../../../system/string/) | 要檢查的密碼。 |

### Return Value

如果簡報受到開啟密碼保護且密碼正確，則傳回 true；否則傳回 false。

## Remarks

```cpp
auto info = PresentationFactory::get_Instance()->GetPresentationInfo(u"pres.pptx");
bool isPasswordCorrect = info->CheckPassword(u"my_password");
```

當密碼為 null 或空字串時，此方法傳回 false。

## See Also

* 類別 [String](../../../system/string/)
* 類別 [IPresentationInfo](../)
* 命名空間 [Aspose::Slides](../../)
* 程式庫 [Aspose.Slides](../../../)