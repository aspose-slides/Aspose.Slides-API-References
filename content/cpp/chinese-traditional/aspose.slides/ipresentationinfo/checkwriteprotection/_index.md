---
title: CheckWriteProtection()
second_title: Aspose.Slides for C++ API 參考
description: 檢查針對受寫入保護的簡報，修改密碼是否正確。
type: docs
weight: 66
url: /zh-hant/aspose.slides/ipresentationinfo/checkwriteprotection/
---
## IPresentationInfo::CheckWriteProtection(System::String) 方法


檢查針對受寫入保護的簡報，修改密碼是否正確。

```cpp
virtual bool Aspose::Slides::IPresentationInfo::CheckWriteProtection(System::String password)=0
```


### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| password | [System::String](../../../system/string/) | 要檢查的密碼。 |

### 返回值

如果簡報已受寫入保護且密碼正確，則返回 True；否則返回 False。

## 備註



```cpp
auto info = PresentationFactory::get_Instance()->GetPresentationInfo(presentationFilePath);
if (info->get_IsWriteProtected() == NullableBool::True)
{
    bool isWriteProtectedByPassword = info->CheckWriteProtection(u"my_password");
}
```



1. 在呼叫此方法之前，應檢查 [IPresentationInfo::get_IsWriteProtected](../get_iswriteprotected/) 屬性。
1. 當 password 為 null 或空字串時，此方法會回傳 false。



## 參見

* 類別 [String](../../../system/string/)
* 類別 [IPresentationInfo](../)
* 命名空間 [Aspose::Slides](../../)
* 函式庫 [Aspose.Slides](../../../)