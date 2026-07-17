---
title: get_LinkPathRelative()
second_title: Aspose.Slides C++ API 参考
description: "如果存在，则返回链接文件的相对路径；否则返回空字符串。只读 System::String."
type: docs
weight: 118
url: /zh/aspose.slides/ioleobjectframe/get_linkpathrelative/
---
## IOleObjectFrame::get_LinkPathRelative() 方法

返回相对路径到链接文件（如果存在），否则返回空字符串。只读 [System::String](../../../system/string/)。

```cpp
virtual System::String Aspose::Slides::IOleObjectFrame::get_LinkPathRelative()=0
```

## 备注

在 Ppt 演示文稿中，某些 Ole 对象链接可能具有相对表示形式。

```cpp
auto presentation = System::MakeObject<Presentation>(u"demo.ppt");

auto oleFrame = System::AsCast<Aspose::Slides::IOleObjectFrame>(presentation->get_Slides()->idx_get(0)->get_Shapes()->idx_get(0));

if (oleFrame != nullptr)
{
    System::Console::WriteLine(System::String(u"The relative path: ") + oleFrame->get_LinkPathRelative());
}
```

## 另请参见

* 类 [String](../../../system/string/)
* 类 [IOleObjectFrame](../)
* 命名空间 [Aspose::Slides](../../)
* 库 [Aspose.Slides](../../../)