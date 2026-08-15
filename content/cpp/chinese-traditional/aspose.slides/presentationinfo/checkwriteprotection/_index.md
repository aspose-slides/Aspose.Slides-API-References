---
title: CheckWriteProtection()
second_title: Aspose.Slides for C++ API 參考
description: 檢查修改受寫入保護的簡報的密碼是否正確。
type: docs
weight: 66
url: /zh-hant/aspose.slides/presentationinfo/checkwriteprotection/
---
## PresentationInfo::CheckWriteProtection(System::String) 方法

檢查修改受寫入保護的簡報的密碼是否正確。

```cpp
bool Aspose::Slides::PresentationInfo::CheckWriteProtection(System::String password) override
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| password | [System::String](../../../system/string/) | 要檢查的密碼。 |

### 返回值

如果簡報已寫入受保護且密碼正確，則返回 True；否則返回 False。

## 備註

```cpp
auto info = PresentationFactory::get_Instance()->GetPresentationInfo(presentationFilePath);
if (info->get_IsWriteProtected() == NullableBool::True)
{
    bool isWriteProtectedByPassword = info->CheckWriteProtection(u"my_password");
}
```

1. 在呼叫此方法之前，應先檢查 [PresentationInfo::get_IsWriteProtected](../get_iswriteprotected/) 屬性。
1. 當密碼為 null 或空字串時，此方法返回 false。

## 另請參閱

* 類別 [String](../../../system/string/)
* 類別 [PresentationInfo](../)
* 命名空間 [Aspose::Slides](../../)
* 程式庫 [Aspose.Slides](../../../)