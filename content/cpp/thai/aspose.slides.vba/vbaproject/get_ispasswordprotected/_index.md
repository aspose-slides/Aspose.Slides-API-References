---
title: get_IsPasswordProtected()
second_title: Aspose.Slides สำหรับ C++ API Reference
description: ระบุว่า VBAProject ได้รับการป้องกันด้วยรหัสผ่านเพื่อดูคุณสมบัติโครงการหรือไม่. อ่านอย่างเดียว bool.
type: docs
weight: 40
url: /th/aspose.slides.vba/vbaproject/get_ispasswordprotected/
---
## VbaProject::get_IsPasswordProtected() เมธอด


ระบุว่า VBAProject ได้รับการป้องกันด้วยรหัสผ่านเพื่อดูคุณสมบัติโครงการหรือไม่. อ่านอย่างเดียว **bool**.

```cpp
bool Aspose::Slides::Vba::VbaProject::get_IsPasswordProtected() override
```

## หมายเหตุ



```cpp
auto presentation = System::MakeObject<Presentation>(path + u"demo.pptm");

if (presentation->get_VbaProject()->get_IsPasswordProtected())
{
    System::Console::WriteLine(System::String(u"The VBAProject '") + presentation->get_VbaProject()->get_Name() + u"' is protected by password to view project properties.");
}
```

## ดูเพิ่มเติม

* คลาส [VbaProject](../)
* เนมสเปซ [Aspose::Slides::Vba](../../)
* ไลบรารี [Aspose.Slides](../../../)