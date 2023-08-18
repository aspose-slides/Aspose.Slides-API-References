---
title: SetWriteProtection()
second_title: Aspose.Slides for C++ API Reference
description: Set write protection for this presentation with specified password.
type: docs
weight: 131
url: /aspose.slides/protectionmanager/setwriteprotection/
---
## ProtectionManager::SetWriteProtection(System::String) method


Set write protection for this presentation with specified password.

```cpp
void Aspose::Slides::ProtectionManager::SetWriteProtection(System::String password) override
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| password | [System::String](../../../system/string/) | The password. |
## Remarks



The following sample code shows you how to set a write protection to a presentation. 
```cpp
auto presentation = System::MakeObject<Presentation>(u"pres.pptx");
presentation->get_ProtectionManager()->SetWriteProtection(u"123123");
presentation->Save(u"write-protected-pres.pptx", SaveFormat::Pptx);
```

## See Also

* Class [String](../../../system/string/)
* Class [ProtectionManager](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)