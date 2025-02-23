---
title: Password
second_title: Aspose.Sildes for .NET API Reference
description: Gets or sets the password. Read/write String.
type: docs
weight: 120
url: /aspose.slides/loadoptions/password/
---

## LoadOptions.Password property

Gets or sets the password. Read/write String.

```csharp
public string Password { get; set; }
```

### Property Value

The password.

### Examples

The following sample code shows how to open password protected PowerPoint Presentation.

```csharp
[C#]
	LoadOptions loadOptions = new LoadOptions {Password = "YOUR_PASSWORD"};
	using (Presentation presentation = new Presentation("pres.pptx", loadOptions))
	{
	  // work with decrypted presentation
	}
```

### See Also

* class [LoadOptions](../../loadoptions)
* namespace [Aspose.Slides](../../loadoptions)
* assembly [Aspose.Slides](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->
