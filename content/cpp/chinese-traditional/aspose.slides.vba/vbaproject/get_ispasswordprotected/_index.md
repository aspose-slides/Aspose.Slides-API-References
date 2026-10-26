---
title: get_IsPasswordProtected()
second_title: Aspose.Slides for C++ API 參考
description: 指示 VBAProject 是否受密碼保護以檢視專案屬性。唯讀 bool.
type: docs
weight: 40
url: /zh-hant/aspose.slides.vba/vbaproject/get_ispasswordprotected/
---
## VbaProject::get_IsPasswordProtected() 方法

指示 VBAProject 是否受密碼保護以檢視專案屬性。唯讀 **bool**。

```cpp
bool Aspose::Slides::Vba::VbaProject::get_IsPasswordProtected() override
```
## 備註



```cpp
auto presentation = System::MakeObject<Presentation>(path + u"demo.pptm");

if (presentation->get_VbaProject()->get_IsPasswordProtected())
{
    System::Console::WriteLine(System::String(u"The VBAProject '") + presentation->get_VbaProject()->get_Name() + u"' is protected by password to view project properties.");
}
```
## 另請參閱

* 類別 [VbaProject](../)
* 命名空間 [Aspose::Slides::Vba](../../)
* 函式庫 [Aspose.Slides](../../../)