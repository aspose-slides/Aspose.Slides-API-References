---
title: CheckWriteProtection()
second_title: Aspose.Slides for C++ API 參考
description: 判斷簡報是否受到密碼保護以進行修改。
type: docs
weight: 157
url: /zh-hant/aspose.slides/iprotectionmanager/checkwriteprotection/
---
## IProtectionManager::CheckWriteProtection(System::String) 方法


判斷簡報是否受到密碼保護以進行修改。

```cpp
virtual bool Aspose::Slides::IProtectionManager::CheckWriteProtection(System::String password)=0
```


### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| password | [System::String](../../../system/string/) | 用於檢查的密碼。 |

### 返回值

如果密碼有效則返回 true；否則返回 false。

## 備註



```cpp
auto presentation = System::MakeObject<Presentation>(presentationFilePath);
bool isWriteProtected = presentation->get_ProtectionManager()->CheckWriteProtection(u"my_password");
```



1. 在呼叫此方法之前，應檢查 [IProtectionManager::get_IsWriteProtected](../get_iswriteprotected/) 屬性。
1. 當密碼為 null 或空字串時，此方法返回 false。


## 另見

* 類別 [String](../../../system/string/)
* 類別 [IProtectionManager](../)
* 命名空間 [Aspose::Slides](../../)
* 函式庫 [Aspose.Slides](../../../)