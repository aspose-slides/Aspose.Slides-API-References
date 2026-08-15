---
title: get_IsPasswordProtected()
second_title: Aspose.Slides for C++ API 參考文件
description: 指示 VBAProject 是否受到密碼保護以檢視專案屬性。唯讀 bool.
type: docs
weight: 40
url: /zh-hant/aspose.slides.vba/ivbaproject/get_ispasswordprotected/
---
## IVbaProject::get_IsPasswordProtected() 方法


指示 VBAProject 是否受到密碼保護，以檢視專案屬性。唯讀 **bool**.

```cpp
virtual bool Aspose::Slides::Vba::IVbaProject::get_IsPasswordProtected()=0
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

* Class [IVbaProject](../)
* Namespace [Aspose::Slides::Vba](../../)
* Library [Aspose.Slides](../../../)