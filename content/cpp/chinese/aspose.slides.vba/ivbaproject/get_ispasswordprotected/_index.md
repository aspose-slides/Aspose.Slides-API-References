---
title: get_IsPasswordProtected()
second_title: Aspose.Slides for C++ API 参考
description: 指示 VBAProject 是否受密码保护以查看项目属性。只读 bool.
type: docs
weight: 40
url: /zh/aspose.slides.vba/ivbaproject/get_ispasswordprotected/
---
## IVbaProject::get_IsPasswordProtected() 方法


指示 VBAProject 是否受密码保护以查看项目属性。只读 **bool**.

```cpp
virtual bool Aspose::Slides::Vba::IVbaProject::get_IsPasswordProtected()=0
```

## 备注



```cpp
auto presentation = System::MakeObject<Presentation>(path + u"demo.pptm");

if (presentation->get_VbaProject()->get_IsPasswordProtected())
{
    System::Console::WriteLine(System::String(u"The VBAProject '") + presentation->get_VbaProject()->get_Name() + u"' is protected by password to view project properties.");
}
```

## 另见

* 类 [IVbaProject](../)
* 命名空间 [Aspose::Slides::Vba](../../)
* 库 [Aspose.Slides](../../../)