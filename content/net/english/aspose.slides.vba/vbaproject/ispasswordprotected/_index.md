---
title: IsPasswordProtected
second_title: Aspose.Sildes for .NET API Reference
description: Indicates whether the VBAProject is protected by a password to view project properties. Read-only Boolean.
type: docs
weight: 20
url: /aspose.slides.vba/vbaproject/ispasswordprotected/
---

## VbaProject.IsPasswordProtected property

Indicates whether the VBAProject is protected by a password to view project properties. Read-only Boolean.

```csharp
public bool IsPasswordProtected { get; }
```

### Examples

```csharp
[C#]
using (var presentation = new Presentation(path + "demo.pptm"))
{
    if (presentation.VbaProject.IsPasswordProtected)
        Console.WriteLine("The VBAProject '" + presentation.VbaProject.Name + 
            "' is protected by password to view project properties.");
}
```

### See Also

* class [VbaProject](../../vbaproject)
* namespace [Aspose.Slides.Vba](../../vbaproject)
* assembly [Aspose.Slides](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->
