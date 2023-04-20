---
title: get_Password()
second_title: Aspose.Slides for C++ API Reference
description: "Gets the password. Read System::String."
type: docs
weight: 105
url: /cpp/aspose.slides/loadoptions/get_password/
---
## LoadOptions::get_Password() method


Gets the password. Read [System::String](../../../system/string/).

```cpp
System::String Aspose::Slides::LoadOptions::get_Password() override
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