---
title: get_GridSpacing()
second_title: Aspose.Slides for C++ API Reference
description: Returns the grid spacing that should be used for the grid underlying the presentation document, in points. Read float.
type: docs
weight: 92
url: /aspose.slides/iviewproperties/get_gridspacing/
---
## IViewProperties::get_GridSpacing() method


Returns the grid spacing that should be used for the grid underlying the presentation document, in points. Read **float**.

```cpp
virtual float Aspose::Slides::IViewProperties::get_GridSpacing()=0
```

## Remarks


The grid spacing value must be a positive number. The typical value range is from 1 mm (2.8349607 points) to 2 inches (144 points). 

The following sample code shows how to change the grid spacing in a PowerPoint presentation. 
```cpp
[C#]
using (Presentation pres = new Presentation())
{
    pres.ViewProperties.GridSpacing = 72f;
    pres.Save("GridSpacing_out.pptx", SaveFormat.Pptx);
}
```

## See Also

* Class [IViewProperties](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)