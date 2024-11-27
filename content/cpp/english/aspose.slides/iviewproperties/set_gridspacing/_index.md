---
title: set_GridSpacing()
second_title: Aspose.Slides for C++ API Reference
description: Sets the grid spacing that should be used for the grid underlying the presentation document, in points. Write float.
type: docs
weight: 105
url: /aspose.slides/iviewproperties/set_gridspacing/
---
## IViewProperties::set_GridSpacing(float) method


Sets the grid spacing that should be used for the grid underlying the presentation document, in points. Write **float**.

```cpp
virtual void Aspose::Slides::IViewProperties::set_GridSpacing(float value)=0
```

## Remarks


The grid spacing value must be a positive number. The typical value range is from 1 mm (2.8349607 points) to 2 inches (144 points). 

The following sample code shows how to change the grid spacing in a PowerPoint presentation. 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();
pres->get_ViewProperties()->set_GridSpacing(72.0f);
pres->Save(u"GridSpacing_out.pptx", SaveFormat::Pptx);
```

## See Also

* Class [IViewProperties](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)