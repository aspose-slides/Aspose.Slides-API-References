---
title: get_LinkPathRelative()
second_title: Aspose.Slides C++ API 参考文档
description: "如果存在链接文件，则返回其相对路径；否则返回空字符串。只读 System::String."
type: docs
weight: 131
url: /zh/aspose.slides/oleobjectframe/get_linkpathrelative/
---
## OleObjectFrame::get_LinkPathRelative() 方法

如果存在，则返回链接文件的相对路径；否则返回空字符串。只读 [System::String](../../../system/string/).

```cpp
System::String Aspose::Slides::OleObjectFrame::get_LinkPathRelative() override
```

## 备注

在Ppt演示文稿中，某些Ole对象链接可能采用相对表示方式。

```cpp
auto presentation = System::MakeObject<Presentation>(u"demo.ppt");

auto oleFrame = System::AsCast<Aspose::Slides::IOleObjectFrame>(presentation->get_Slides()->idx_get(0)->get_Shapes()->idx_get(0));

if (oleFrame != nullptr)
{
    System::Console::WriteLine(System::String(u"The relative path: ") + oleFrame->get_LinkPathRelative());
}
```

## 另见

* 类 [String](../../../system/string/)
* 类 [OleObjectFrame](../)
* 命名空间 [Aspose::Slides](../../)
* 库 [Aspose.Slides](../../../)