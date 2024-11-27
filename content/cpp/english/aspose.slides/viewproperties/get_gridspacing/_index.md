---
title: get_GridSpacing()
second_title: Aspose.Slides for C++ API Reference
description: Returns the grid spacing that should be used for the grid underlying the presentation document, in points. Read float.
type: docs
weight: 92
url: /aspose.slides/viewproperties/get_gridspacing/
---
## ViewProperties::get_GridSpacing() method


Returns the grid spacing that should be used for the grid underlying the presentation document, in points. Read **float**.

```cpp
float Aspose::Slides::ViewProperties::get_GridSpacing() override
```

## Remarks


The grid spacing value must be a positive number . The typical value range is from 1 mm (2.8349607 points) to 2 inches (144 points). 

The following sample code shows how to change the grid spacing in a PowerPoint presentation. 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();
pres->get_ViewProperties()->set_GridSpacing(72.0f);
pres->Save(u"GridSpacing_out.pptx", SaveFormat::Pptx);
```

## See Also

* Class [ViewProperties](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)