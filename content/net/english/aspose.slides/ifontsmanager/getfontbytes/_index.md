---
title: GetFontBytes
second_title: Aspose.Sildes for .NET API Reference
description: Retrieves the byte array representing the font data for a specified font style and font data.
type: docs
weight: 50
url: /aspose.slides/ifontsmanager/getfontbytes/
---

## IFontsManager.GetFontBytes method

Retrieves the byte array representing the font data for a specified font style and font data.

```csharp
public byte[] GetFontBytes(IFontData fontData, FontStyle fontStyle)
```

| Parameter | Type | Description |
| --- | --- | --- |
| fontData | IFontData | The font data object containing the information about the font [`IFontData`](../../ifontdata). |
| fontStyle | FontStyle | The style of the font for which the data is to be retrieved FontStyle. |

### Return Value

A byte array containing the font data for the specified font style. If the font data or style is not found, returns null.

### Examples

```csharp
[C#]
using (Presentation pres = new Presentation ("Presentation.pptx"))
{
    // Retrieve all fonts used in the presentation
    IFontData[] fonts = pres.FontsManager.GetFonts();

    // Get the byte array representing the regular style of the first font in the presentation
    byte[] bytes = pres.FontsManager.GetFontBytes(fonts[0], FontStyle.Regular);
}
```

### See Also

* interface [IFontData](../../ifontdata)
* interface [IFontsManager](../../ifontsmanager)
* namespace [Aspose.Slides](../../ifontsmanager)
* assembly [Aspose.Slides](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->
