---
title: GetEffective
second_title: Aspose.Slides für .NET-API-Referenz
description: Ruft effektive Absatzformatierungsdaten mit angewendeter Vererbung ab.
type: docs
weight: 160
url: /de/net/aspose.slides/paragraphformat/geteffective/
---
## ParagraphFormat.GetEffective method

Ruft effektive Absatzformatierungsdaten mit angewendeter Vererbung ab.

```csharp
public IParagraphFormatEffectiveData GetEffective()
```

### Rückgabewert

EIN[`IParagraphFormatEffectiveData`](../../iparagraphformateffectivedata).

### Beispiele

Dieses Beispiel demonstriert das Abrufen einiger effektiver Absatzformateigenschaften.

```csharp
[C#]
using (Presentation pres = new Presentation(@"MyPresentation.pptx"))
{
	IAutoShape shape = pres.Slides[0].Shapes[0] as IAutoShape;
	IParagraphFormatEffectiveData effectiveParagraphFormat = shape.TextFrame.Paragraphs[0].ParagraphFormat.GetEffective();

	Console.WriteLine("Text alignment: " + effectiveParagraphFormat.Alignment);
	Console.WriteLine("Indent: " + effectiveParagraphFormat.Indent);
	Console.WriteLine("Bullet type: " + effectiveParagraphFormat.Bullet.Type);
}
```

### Siehe auch

* interface [IParagraphFormatEffectiveData](../../iparagraphformateffectivedata)
* class [ParagraphFormat](../../paragraphformat)
* namensraum [Aspose.Slides](../../paragraphformat)
* Montage [Aspose.Slides](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->