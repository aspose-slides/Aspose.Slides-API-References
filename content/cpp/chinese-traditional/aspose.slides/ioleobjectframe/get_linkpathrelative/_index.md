---
title: get_LinkPathRelative()
second_title: Aspose.Slides for C++ API 參考文件
description: "如果存在已連結的檔案，返回其相對路徑；否則返回空字串。Readonly System::String."
type: docs
weight: 118
url: /zh-hant/aspose.slides/ioleobjectframe/get_linkpathrelative/
---
## IOleObjectFrame::get_LinkPathRelative() 方法

返回已存在的已連結檔案的相對路徑，如果不存在則返回空字串。唯讀 [System::String](../../../system/string/).

```cpp
virtual System::String Aspose::Slides::IOleObjectFrame::get_LinkPathRelative()=0
```

## 備註

在 Ppt 簡報中，某些 Ole 物件連結可能具有相對表示方式。

```cpp
auto presentation = System::MakeObject<Presentation>(u"demo.ppt");

auto oleFrame = System::AsCast<Aspose::Slides::IOleObjectFrame>(presentation->get_Slides()->idx_get(0)->get_Shapes()->idx_get(0));

if (oleFrame != nullptr)
{
    System::Console::WriteLine(System::String(u"The relative path: ") + oleFrame->get_LinkPathRelative());
}
```

## 另見

* 類別 [String](../../../system/string/)
* 類別 [IOleObjectFrame](../)
* 命名空間 [Aspose::Slides](../../)
* 函式庫 [Aspose.Slides](../../../)