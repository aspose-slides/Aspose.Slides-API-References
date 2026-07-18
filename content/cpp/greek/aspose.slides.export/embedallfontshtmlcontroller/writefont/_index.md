---
title: WriteFont()
second_title: Αναφορά API του Aspose.Slides για C++
description: Γράφει δεδομένα ως base64 στο ίδιο έγγραφο HTML
type: docs
weight: 105
url: /el/aspose.slides.export/embedallfontshtmlcontroller/writefont/
---
## EmbedAllFontsHtmlController::WriteFont(System::SharedPtr\<IHtmlGenerator\>, System::SharedPtr\<IFontData\>, System::SharedPtr\<IFontData\>, System::String, System::String, System::ArrayPtr\<uint8_t\>) μέθοδος

Γράφει τα δεδομένα ως base64 στο ίδιο έγγραφο HTML

```cpp
virtual void Aspose::Slides::Export::EmbedAllFontsHtmlController::WriteFont(System::SharedPtr<IHtmlGenerator> generator, System::SharedPtr<IFontData> originalFont, System::SharedPtr<IFontData> substitutedFont, System::String fontStyle, System::String fontWeight, System::ArrayPtr<uint8_t> fontData)
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| generator | [System::SharedPtr](../../../system/sharedptr/)\<[IHtmlGenerator](../../ihtmlgenerator/)\> | Γεννήτρια HTML |
| originalFont | [System::SharedPtr](../../../system/sharedptr/)\<[IFontData](../../../aspose.slides/ifontdata/)\> | Font προς σειριοποίηση |
| substitutedFont | [System::SharedPtr](../../../system/sharedptr/)\<[IFontData](../../../aspose.slides/ifontdata/)\> | Font που αντικαταστάθηκε (αν έγινε αντικατάσταση font), null διαφορετικά |
| fontStyle | [System::String](../../../system/string/) | Στυλ Font |
| fontWeight | [System::String](../../../system/string/) | Βάρος Font |
| fontData | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Δεδομένα Font |

## Δείτε επίσης

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Κλάση [IHtmlGenerator](../../ihtmlgenerator/)
* Κλάση [IFontData](../../../aspose.slides/ifontdata/)
* Κλάση [String](../../../system/string/)
* Κλάση [EmbedAllFontsHtmlController](../)
* Χώρος ονομάτων [Aspose::Slides::Export](../../)
* Library [Aspose.Slides](../../../)