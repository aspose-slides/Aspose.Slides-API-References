---
title: Encrypt()
second_title: Aspose.Slides for C++ API Reference
description: Encrypts Presentation with specified password.
type: docs
weight: 105
url: /aspose.slides/protectionmanager/encrypt/
---
## ProtectionManager::Encrypt(System::String) method


Encrypts [Presentation](../../presentation/) with specified password.

```cpp
void Aspose::Slides::ProtectionManager::Encrypt(System::String encryptionPassword) override
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| encryptionPassword | [System::String](../../../system/string/) | The password. |
## Remarks



The following sample code shows you how to encrypt a PowerPoint [Presentation](../../presentation/). 
```cpp
auto presentation = System::MakeObject<Presentation>(u"pres.pptx");
presentation->get_ProtectionManager()->Encrypt(u"123123");
presentation->Save(u"encrypted-pres.pptx", SaveFormat::Pptx);
```

## See Also

* Class [String](../../../system/string/)
* Class [ProtectionManager](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)