---
title: get_IsPasswordProtected()
second_title: Aspose.Slides สำหรับ C++ อ้างอิง API
description: บ่งชี้ว่า VBAProject ถูกป้องกันด้วยรหัสผ่านเพื่อดูคุณสมบัติโปรเจกต์หรือไม่ อ่านอย่างเดียว bool.
type: docs
weight: 40
url: /th/aspose.slides.vba/ivbaproject/get_ispasswordprotected/
---
## IVbaProject::get_IsPasswordProtected() วิธีการ


บ่งชี้ว่า VBAProject ถูกป้องกันด้วยรหัสผ่านเพื่อดูคุณสมบัติโปรเจกต์หรือไม่ อ่านอย่างเดียว **bool**.

```cpp
virtual bool Aspose::Slides::Vba::IVbaProject::get_IsPasswordProtected()=0
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

* คลาส [IVbaProject](../)
* เนมสเปซ [Aspose::Slides::Vba](../../)
* ไลบรารี [Aspose.Slides](../../../)