---
title: GetSensitivityLabels()
second_title: Aspose.Slides for C++ API Reference
description: Gets an array of sensitivity labels from the custom document properties (Microsoft Information Protection SDK Metadata).
type: docs
weight: 872
url: /aspose.slides/idocumentproperties/getsensitivitylabels/
---
## IDocumentProperties::GetSensitivityLabels() method


Gets an array of sensitivity labels from the custom document properties (Microsoft Information Protection SDK Metadata).

```cpp
virtual System::ArrayPtr<System::SharedPtr<ISensitivityLabel>> Aspose::Slides::IDocumentProperties::GetSensitivityLabels()=0
```

## Remarks


The following code shows how to move the sensitivity labels information from the custom document properties to the modern SensitivityLabels collection: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"SomePresentation.pptx");

// Get sensitivity labels from the custom document properties
auto mipSensitivityLabels = pres->get_DocumentProperties()->GetSensitivityLabels();

auto sensitivityLabels = pres->get_SensitivityLabels();
for (auto&& sensitivityLabel : mipSensitivityLabels)
{
    // Add label to the collection
    // Here you can add a check for the validity of the label information (the label is available, etc)
    sensitivityLabels->Add(sensitivityLabel);
}

pres->Save(u"SensitivityLabel.pptx", SaveFormat::Pptx);
```

## See Also

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [ISensitivityLabel](../../isensitivitylabel/)
* Class [IDocumentProperties](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)