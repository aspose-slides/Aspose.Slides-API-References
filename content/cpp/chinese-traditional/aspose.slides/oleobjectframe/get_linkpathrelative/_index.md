---
title: get_LinkPathRelative()
second_title: Aspose.Slides for C++ API 參考
description: "如果存在，返回指向連結檔案的相對路徑；否則返回空字串。唯讀 System::String."
type: docs
weight: 131
url: /zh-hant/aspose.slides/oleobjectframe/get_linkpathrelative/
---
## OleObjectFrame::get_LinkPathRelative() 方法


如果存在，返回指向連結檔案的相對路徑；否則返回空字串。唯讀 [System::String](../../../system/string/).

```cpp
System::String Aspose::Slides::OleObjectFrame::get_LinkPathRelative() override
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
* 類別 [OleObjectFrame](../)
* 命名空間 [Aspose::Slides](../../)
* 函式庫 [Aspose.Slides](../../../)