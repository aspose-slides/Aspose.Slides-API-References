---
title: CheckWriteProtection()
second_title: Aspose.Slides for C++ API 參考
description: 判斷簡報是否受到密碼保護以進行修改。
type: docs
weight: 157
url: /zh-hant/aspose.slides/protectionmanager/checkwriteprotection/
---
## ProtectionManager::CheckWriteProtection(System::String) 方法

判斷簡報是否受到密碼保護以進行修改。

```cpp
bool Aspose::Slides::ProtectionManager::CheckWriteProtection(System::String password) override
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| password | [System::String](../../../system/string/) | 用於檢查的密碼。 |

### 返回值

如果密碼有效則為 true；否則為 false。

## 備註

```cpp
auto presentation = System::MakeObject<Presentation>(presentationFilePath);
bool isWriteProtected = presentation->get_ProtectionManager()->CheckWriteProtection(u"my_password");
```

1. 在呼叫此方法之前，應檢查 [ProtectionManager::get_IsWriteProtected](../get_iswriteprotected/) 屬性。
1. 當密碼為 null 或空字串時，此方法會回傳 false。

## 另請參閱

* 類別 [String](../../../system/string/)
* 類別 [ProtectionManager](../)
* 命名空間 [Aspose::Slides](../../)
* 函式庫 [Aspose.Slides](../../../)