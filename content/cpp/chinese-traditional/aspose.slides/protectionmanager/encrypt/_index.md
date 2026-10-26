---
title: Encrypt()
second_title: Aspose.Slides for C++ API 參考文件
description: 使用指定的密碼加密簡報。
type: docs
weight: 105
url: /zh-hant/aspose.slides/protectionmanager/encrypt/
---
## ProtectionManager::Encrypt(System::String) 方法

使用指定的密碼加密 [Presentation](../../presentation/)。

```cpp
void Aspose::Slides::ProtectionManager::Encrypt(System::String encryptionPassword) override
```

### 參數

| 參數 | 型別 | 說明 |
| --- | --- | --- |
| encryptionPassword | [System::String](../../../system/string/) | 密碼。 |
## 備註

以下範例程式碼示範如何加密 PowerPoint [Presentation](../../presentation/)。 
```cpp
auto presentation = System::MakeObject<Presentation>(u"pres.pptx");
presentation->get_ProtectionManager()->Encrypt(u"123123");
presentation->Save(u"encrypted-pres.pptx", SaveFormat::Pptx);
```

## 另見

* 類別 [String](../../../system/string/)
* 類別 [ProtectionManager](../)
* 命名空間 [Aspose::Slides](../../)
* 函式庫 [Aspose.Slides](../../../)