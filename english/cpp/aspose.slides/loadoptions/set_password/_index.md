---
title: set_Password()
second_title: Aspose.Slides for C++ API Reference
description: "Sets the password. Write System::String."
type: docs
weight: 118
url: /cpp/aspose.slides/loadoptions/set_password/
---
## LoadOptions::set_Password(System::String) method


Sets the password. Write [System::String](../../../system/string/).

```cpp
void Aspose::Slides::LoadOptions::set_Password(System::String value) override
```

## Remarks


The password. 

The following sample code shows how to open password protected PowerPoint [Presentation](../../presentation/). 
```cpp
System::SharedPtr<LoadOptions> loadOptions = System::MakeObject<LoadOptions>();
loadOptions->set_Password(u"YOUR_PASSWORD");
auto presentation = System::MakeObject<Presentation>(u"pres.pptx", loadOptions);
// work with decrypted presentation
```

## See Also

* Class [String](../../../system/string/)
* Class [LoadOptions](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)