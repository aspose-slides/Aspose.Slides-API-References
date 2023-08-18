---
title: get_RootDirectoryClsid()
second_title: Aspose.Slides for C++ API Reference
description: Represents the object class GUID (CLSID) that is stored in the root directory entry. Can be used for COM activation of the document's application. The default value is '64818D11-4F9B-11CF-86EA-00AA00B929E8' that corresponds to 'Microsoft Powerpoint.Slide.8'.
type: docs
weight: 1
url: /aspose.slides.export/ipptoptions/get_rootdirectoryclsid/
---
## IPptOptions::get_RootDirectoryClsid() method


Represents the object class GUID (CLSID) that is stored in the root directory entry. Can be used for COM activation of the document's application. The default value is '64818D11-4F9B-11CF-86EA-00AA00B929E8' that corresponds to 'Microsoft Powerpoint.Slide.8'.

```cpp
virtual System::Guid Aspose::Slides::Export::IPptOptions::get_RootDirectoryClsid()=0
```

## Remarks



```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();

System::SharedPtr<PptOptions> pptOptions = System::MakeObject<PptOptions>();

pptOptions->set_RootDirectoryClsid(System::Guid(u"64818D10-4F9B-11CF-86EA-00AA00B929E8"));

pres->Save(u"pres.ppt", Aspose::Slides::Export::SaveFormat::Ppt, pptOptions);
```




## See Also

* Class [Guid](../../../system/guid/)
* Class [IPptOptions](../)
* Namespace [Aspose::Slides::Export](../../)
* Library [Aspose.Slides](../../../)