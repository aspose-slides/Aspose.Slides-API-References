---
title: RemoveWriteProtection
second_title: Aspose.Sildes for .NET API Reference
description: Removes write protection for this presentation.
type: docs
weight: 100
url: /aspose.slides/protectionmanager/removewriteprotection/
---

## ProtectionManager.RemoveWriteProtection method

Removes write protection for this presentation.

```csharp
public void RemoveWriteProtection()
```

### Examples

This sample code shows you how to remove the write protection from a PowerPoint Presentation.

```csharp
[C#]
using (Presentation presentation = new Presentation("pres.pptx"))
{
    presentation.ProtectionManager.RemoveWriteProtection();
    presentation.Save("write-protection-removed.pptx", SaveFormat.Pptx);
}
```

### See Also

* class [ProtectionManager](../../protectionmanager)
* namespace [Aspose.Slides](../../protectionmanager)
* assembly [Aspose.Slides](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->
