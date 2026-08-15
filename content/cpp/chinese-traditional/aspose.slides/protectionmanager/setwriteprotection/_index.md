---
title: SetWriteProtection()
second_title: Aspose.Slides for C++ API 參考文件
description: 使用指定的密碼為此簡報設定寫入保護。
type: docs
weight: 131
url: /zh-hant/aspose.slides/protectionmanager/setwriteprotection/
---
## ProtectionManager::SetWriteProtection(System::String) 方法


使用指定密碼為此簡報設定寫入保護。

```cpp
void Aspose::Slides::ProtectionManager::SetWriteProtection(System::String password) override
```


### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| password | [System::String](../../../system/string/) | 密碼。 |
## 備註



以下範例程式碼示範如何為簡報設定寫入保護。 
```cpp
auto presentation = System::MakeObject<Presentation>(u"pres.pptx");
presentation->get_ProtectionManager()->SetWriteProtection(u"123123");
presentation->Save(u"write-protected-pres.pptx", SaveFormat::Pptx);
```

## 另見

* 類別 [String](../../../system/string/)
* 類別 [ProtectionManager](../)
* 命名空間 [Aspose::Slides](../../)
* 程式庫 [Aspose.Slides](../../../)