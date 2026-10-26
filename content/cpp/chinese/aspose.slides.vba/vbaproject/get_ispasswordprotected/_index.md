---
title: get_IsPasswordProtected()
second_title: Aspose.Slides C++ API 参考
description: 指示 VBAProject 是否受密码保护以查看项目属性。只读 bool。
type: docs
weight: 40
url: /zh/aspose.slides.vba/vbaproject/get_ispasswordprotected/
---
## VbaProject::get_IsPasswordProtected() 方法

指示 VBAProject 是否受到密码保护以查看项目属性。只读 **bool**。

```cpp
bool Aspose::Slides::Vba::VbaProject::get_IsPasswordProtected() override
```

## 备注

```cpp
auto presentation = System::MakeObject<Presentation>(path + u"demo.pptm");

if (presentation->get_VbaProject()->get_IsPasswordProtected())
{
    System::Console::WriteLine(System::String(u"The VBAProject '") + presentation->get_VbaProject()->get_Name() + u"' is protected by password to view project properties.");
}
```

## 参见

* 类 [VbaProject](../)
* 命名空间 [Aspose::Slides::Vba](../../)
* 库 [Aspose.Slides](../../../)