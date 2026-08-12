---
title: PdfOptions
second_title: Aspose.Slides for C++ API संदर्भ
description: विकल्प प्रदान करता है जो यह नियंत्रित करते हैं कि प्रस्तुति को Pdf प्रारूप में कैसे सहेजा जाता है।
type: docs
weight: 573
url: /hi/aspose.slides.export/pdfoptions/
---
## PdfOptions क्लास

एक प्रस्तुति को Pdf प्रारूप में सहेजने के तरीके को नियंत्रित करने वाले विकल्प प्रदान करता है।

```cpp
class PdfOptions : public Aspose::Slides::Export::SaveOptions,
                   public Aspose::Slides::Export::IPdfOptions
```

## विधियाँ

| मेथड | विवरण |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Compares objects using C# [Object.Equals](../../system/object/equals/) semantics. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Compares reference type objects in C# style. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Compares value type objects in C# style. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emulates C#-style floating point comparison where two NaNs are considered equal even though according to IEC 60559:1989 NaN is not equal to any value, including NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emulates C#-style floating point comparison where two NaNs are considered equal even though according to IEC 60559:1989 NaN is not equal to any value, including NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | For internal purposes only. |
| [PdfAccessPermissions](../pdfaccesspermissions/) [get_AccessPermissions](./get_accesspermissions/)() override | Contains a set of flags specifying which access permissions should be granted when the document is opened with user access. See [PdfAccessPermissions](../pdfaccesspermissions/). |
| [System::ArrayPtr](../../system/arrayptr/)\<[System::String](../../system/string/)\> [get_AdditionalCommonFontFamilies](./get_additionalcommonfontfamilies/)() override | Returns an array of user-defined names of font families which [Aspose.Slides](../../aspose.slides/) should consider common. Read [System::String](../../system/string/)[]. |
| **bool** [get_ApplyImageTransparent](./get_applyimagetransparent/)() override | Applies the specified transparent color to an image if **true**. |
| **bool** [get_BestImagesCompressionRatio](./get_bestimagescompressionratio/)() override | Indicates if the most effective compression (instead of the default one) for each image must be selected automatically. If set to **bool**.true, for every image in presentation the most appropriate compression algorithm will be chosen, what will lead to the smaller size of the resulting PDF document. |
| [PdfCompliance](../pdfcompliance/) [get_Compliance](./get_compliance/)() override | Desired conformance level for generated PDF document. Read [PdfCompliance](../pdfcompliance/). |
| [System::String](../../system/string/) [get_DefaultRegularFont](../saveoptions/get_defaultregularfont/)() override | Returns font used in case source font is not found. Reads [System::String](../../system/string/). |
| **bool** [get_DrawSlidesFrame](./get_drawslidesframe/)() override | True to draw black frame around each slide. Read **bool**. |
| **bool** [get_EmbedFullFonts](./get_embedfullfonts/)() override | Determines if all characters of font should be embedded or only used subset. Read **bool**. |
| **bool** [get_EmbedTrueTypeFontsForASCII](./get_embedtruetypefontsforascii/)() override | Determines if [Aspose.Slides](../../aspose.slides/) will embed common fonts for ASCII (33..127 code range) text. [Fonts](../../aspose.slides/fonts/) for character codes greater than 127 are always embedded. Common fonts list includes PDF's base 14 fonts and additional user specified fonts. Read **bool**. |
| [Aspose::Slides::GradientStyle](../../aspose.slides/gradientstyle/) [get_GradientStyle](../saveoptions/get_gradientstyle/)() override | Returns the visual style of the gradient. Read [GradientStyle](../../aspose.slides/gradientstyle/). |
| [System::Drawing::Color](../../system.drawing/color/) [get_ImageTransparentColor](./get_imagetransparentcolor/)() override | Gets the image transparent color. |
| **bool** [get_IncludeOleData](./get_includeoledata/)() override | True to convert all OLE data from the presentation to embedded files in the resulting PDF. Read **bool**. |
| [System::SharedPtr](../../system/sharedptr/)\<[IInkOptions](../iinkoptions/)\> [get_InkOptions](./get_inkoptions/)() override | Provides options that control the look of [Ink](../../aspose.slides.ink/) objects in exported document. Read-only [IInkOptions](../iinkoptions/) |
| **uint8_t** [get_JpegQuality](./get_jpegquality/)() override | Returns a value determining the quality of the JPEG images inside PDF document. Read **uint8_t**. |
| [System::String](../../system/string/) [get_Password](./get_password/)() override | Setting user password to protect the PDF document. Read [System::String](../../system/string/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IProgressCallback](../../aspose.slides/iprogresscallback/)\> [get_ProgressCallback](../saveoptions/get_progresscallback/)() override | Represents a callback object for saving progress updates in percentage. See [IProgressCallback](../../aspose.slides/iprogresscallback/). |
| **bool** [get_RasterizeUnsupportedFontStyles](./get_rasterizeunsupportedfontstyles/)() override | Indicates whether text should be rasterized as a bitmap and saved to PDF when the font does not support bold styling. This approach can enhance the quality of text in the resulting PDF for certain fonts. Read **bool**. |
| **bool** [get_SaveMetafilesAsPng](./get_savemetafilesaspng/)() override | True to convert all metafiles used in a presentation to the PNG images. Read **bool**. |
| **bool** [get_ShowHiddenSlides](./get_showhiddenslides/)() override | Specifies whether the generated document should include hidden slides or not. Default is **false**. |
| **bool** [get_SkipJavaScriptLinks](../saveoptions/get_skipjavascriptlinks/)() override | Specifies whether to skip hyperlinks with JavaScript calls when saving the presentation. Read **bool**. The default value is **false**. |
| [System::SharedPtr](../../system/sharedptr/)\<[ISlidesLayoutOptions](../islideslayoutoptions/)\> [get_SlidesLayoutOptions](./get_slideslayoutoptions/)() override | Gets the mode in which slides are placed on the page when exporting a presentation [ISlidesLayoutOptions](../islideslayoutoptions/). |
| **float** [get_SufficientResolution](./get_sufficientresolution/)() override | Returns a value determining resolution of images inside PDF document. |
| [PdfTextCompression](../pdftextcompression/) [get_TextCompression](./get_textcompression/)() override | Specifies compression type to be used for all textual content in the document. Read [PdfTextCompression](../pdftextcompression/). |
| [System::SharedPtr](../../system/sharedptr/)\<[Aspose::Slides::Warnings::IWarningCallback](../../aspose.slides.warnings/iwarningcallback/)\> [get_WarningCallback](../saveoptions/get_warningcallback/)() override | Returns of sets an object which receives warnings and decides whether loading process will continue or will be aborted. Read [Aspose::Slides::Warnings::IWarningCallback](../../aspose.slides.warnings/iwarningcallback/). |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Gets reference counter data structure associated with the object. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analog of C# [Object.GetHashCode()](../../system/object/gethashcode/) method. Enables hashing of custom objects. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Gets actual type of object. Analog of C# [System.Object.GetType()](../../system/object/gettype/) call. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Check if object represents an instance of type described by targetType. Analog of C# 'is' operator. |
| void [Lock](../../system/object/lock/)() | Implements C# lock() statement locking. Call directly or use [LockContext](../../system/lockcontext/) sentry object. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analog of C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) method. Enables cloning custom types. |
|  [Object](../../system/object/object/)() | Creates object. Initializes all internal data structures. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Copy constructor. Doesn't copy anything, really, just initializes new object and enables copy constructing subclasses. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Assignment operator. Doesn't copy anything, really, just initializes new object and enables copy constructing subclasses. |
|  [PdfOptions](./pdfoptions/)() | Default constructor. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Compares objects by reference. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Compares objects by reference. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Reference-compares value type object with nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Specialization of [Object::ReferenceEquals](../../system/object/referenceequals/) for case of string and nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Specialization of [Object::ReferenceEquals](../../system/object/referenceequals/) for case of strings. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Decreases shared reference count by specified value. |
|  [SaveOptions](../saveoptions/saveoptions/)() |  |
| void [set_AccessPermissions](./set_accesspermissions/)([PdfAccessPermissions](../pdfaccesspermissions/)) override | Contains a set of flags specifying which access permissions should be granted when the document is opened with user access. See [PdfAccessPermissions](../pdfaccesspermissions/). |
| void [set_AdditionalCommonFontFamilies](./set_additionalcommonfontfamilies/)([System::ArrayPtr](../../system/arrayptr/)\<[System::String](../../system/string/)\>) override | Sets an array of user-defined names of font families which [Aspose.Slides](../../aspose.slides/) should consider common. Write [System::String](../../system/string/)[]. |
| void [set_ApplyImageTransparent](./set_applyimagetransparent/)(**bool**) override | Applies the specified transparent color to an image if **true**. |
| void [set_BestImagesCompressionRatio](./set_bestimagescompressionratio/)(**bool**) override | Indicates if the most effective compression (instead of the default one) for each image must be selected automatically. If set to **bool**.true, for every image in presentation the most appropriate compression algorithm will be chosen, what will lead to the smaller size of the resulting PDF document. |
| void [set_Compliance](./set_compliance/)([PdfCompliance](../pdfcompliance/)) override | Desired conformance level for generated PDF document. Write [PdfCompliance](../pdfcompliance/). |
| void [set_DefaultRegularFont](../saveoptions/set_defaultregularfont/)([System::String](../../system/string/)) override | Sets font used in case source font is not found. Writes [System::String](../../system/string/). |
| void [set_DrawSlidesFrame](./set_drawslidesframe/)(**bool**) override | True to draw black frame around each slide. Write **bool**. |
| void [set_EmbedFullFonts](./set_embedfullfonts/)(**bool**) override | Determines if all characters of font should be embedded or only used subset. Write **bool**. |
| void [set_EmbedTrueTypeFontsForASCII](./set_embedtruetypefontsforascii/)(**bool**) override | Determines if [Aspose.Slides](../../aspose.slides/) will embed common fonts for ASCII (33..127 code range) text. [Fonts](../../aspose.slides/fonts/) for character codes greater than 127 are always embedded. Common fonts list includes PDF's base 14 fonts and additional user specified fonts. Write **bool**. |
| void [set_GradientStyle](../saveoptions/set_gradientstyle/)([Aspose::Slides::GradientStyle](../../aspose.slides/gradientstyle/)) override | Sets the visual style of the gradient. Write [GradientStyle](../../aspose.slides/gradientstyle/). |
| void [set_ImageTransparentColor](./set_imagetransparentcolor/)([System::Drawing::Color](../../system.drawing/color/)) override | Sets the image transparent color. |
| void [set_IncludeOleData](./set_includeoledata/)(**bool**) override | True to convert all OLE data from the presentation to embedded files in the resulting PDF. Write **bool**. |
| void [set_JpegQuality](./set_jpegquality/)(**uint8_t**) override | Sets a value determining the quality of the JPEG images inside PDF document. Write **uint8_t**. |
| void [set_Password](./set_password/)([System::String](../../system/string/)) override | Setting user password to protect the PDF document. Write [System::String](../../system/string/). |
| void [set_ProgressCallback](../saveoptions/set_progresscallback/)([System::SharedPtr](../../system/sharedptr/)\<[IProgressCallback](../../aspose.slides/iprogresscallback/)\>) override | Represents a callback object for saving progress updates in percentage. See [IProgressCallback](../../aspose.slides/iprogresscallback/). |
| void [set_RasterizeUnsupportedFontStyles](./set_rasterizeunsupportedfontstyles/)(**bool**) override | Indicates whether text should be rasterized as a bitmap and saved to PDF when the font does not support bold styling. This approach can enhance the quality of text in the resulting PDF for certain fonts. Write **bool**. |
| void [set_SaveMetafilesAsPng](./set_savemetafilesaspng/)(**bool**) override | True to convert all metafiles used in a presentation to the PNG images. Write **bool**. |
| void [set_ShowHiddenSlides](./set_showhiddenslides/)(**bool**) override | Specifies whether the generated document should include hidden slides or not. Default is **false**. |
| void [set_SkipJavaScriptLinks](../saveoptions/set_skipjavascriptlinks/)(**bool**) override | Specifies whether to skip hyperlinks with JavaScript calls when saving the presentation. Write **bool**. The default value is **false**. |
| void [set_SlidesLayoutOptions](./set_slideslayoutoptions/)([System::SharedPtr](../../system/sharedptr/)\<[ISlidesLayoutOptions](../islideslayoutoptions/)\>) override | Sets the mode in which slides are placed on the page when exporting a presentation [ISlidesLayoutOptions](../islideslayoutoptions/). |
| void [set_SufficientResolution](./set_sufficientresolution/)(**float**) override | Sets a value determining resolution of images inside PDF document. |
| void [set_TextCompression](./set_textcompression/)([PdfTextCompression](../pdftextcompression/)) override | Specifies compression type to be used for all textual content in the document. Write [PdfTextCompression](../pdftextcompression/). |
| void [set_WarningCallback](../saveoptions/set_warningcallback/)([System::SharedPtr](../../system/sharedptr/)\<[Aspose::Slides::Warnings::IWarningCallback](../../aspose.slides.warnings/iwarningcallback/)\>) override | Returns of sets an object which receives warnings and decides whether loading process will continue or will be aborted. Write [Aspose::Slides::Warnings::IWarningCallback](../../aspose.slides.warnings/iwarningcallback/). |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Set n'th template argument a weak pointer (rather than shared). Allows switching pointers in containers to weak mode. |
| int [SharedCount](../../system/object/sharedcount/)() const | Gets current value of shared reference counter. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Increments shared reference count. Shouldn't be called directly; instead, use smart pointers or ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Decrements and returns shared reference count. Shouldn't be called directly; instead, use smart pointers or ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analog of C# [Object.ToString()](../../system/object/tostring/) method. Enables converting custom objects to string. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implements C# typeof([System.Object](../../system/object/)) construct. |
| void [Unlock](../../system/object/unlock/)() | Implements C# lock() statement unlocking. Call directly or use [LockContext](../../system/lockcontext/) sentry object. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Increments weak reference count. Shouldn't be called directly; instead, use smart pointers or ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Decrements weak reference count. Shouldn't be called directly; instead, use smart pointers or ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | Destroys object. Frees all internal data structures. |

## टिप्पणियाँ





निम्नलिखित उदाहरण दिखाता है कि कैसे PowerPoint को कस्टम विकल्पों के साथ PDF में बदलें।
```cpp
auto presentation = System::MakeObject<Presentation>(u"PowerPoint.pptx");

// PdfOptions क्लास का उदाहरण बनाता है
System::SharedPtr<PdfOptions> pdfOptions = System::MakeObject<PdfOptions>();
// Jpeg गुणवत्ता सेट करता है
pdfOptions->set_JpegQuality(90);
// मेटाफाइलों के व्यवहार को सेट करता है
pdfOptions->set_SaveMetafilesAsPng(true);
// पाठ संपीड़न स्तर सेट करता है
pdfOptions->set_TextCompression(PdfTextCompression::Flate);
// PDF मानक को परिभाषित करता है
pdfOptions->set_Compliance(PdfCompliance::Pdf15);
// प्रस्तुति को PDF के रूप में सहेजता है
presentation->Save(u"PowerPoint-to-PDF.pdf", SaveFormat::Pdf, pdfOptions);
```
निम्नलिखित उदाहरण दिखाता है कि कैसे PowerPoint को छिपी स्लाइडों के साथ PDF में बदलें।
```cpp
// एक Presentation क्लास का उदाहरण बनाता है जो PowerPoint फ़ाइल का प्रतिनिधित्व करता है
auto presentation = System::MakeObject<Presentation>(u"PowerPoint.pptx");

// PdfOptions क्लास का उदाहरण बनाता है
System::SharedPtr<PdfOptions> pdfOptions = System::MakeObject<PdfOptions>();
// छिपी स्लाइड्स जोड़ता है
pdfOptions->set_ShowHiddenSlides(true);
// प्रस्तुति को PDF के रूप में सहेजता है
presentation->Save(u"PowerPoint-to-PDF.pdf", SaveFormat::Pdf, pdfOptions);
```
निम्नलिखित उदाहरण दिखाता है कि कैसे PowerPoint को पासवर्ड संरक्षित PDF में बदलें।
```cpp
// एक Presentation ऑब्जेक्ट का उदाहरण बनाता है जो PowerPoint फ़ाइल का प्रतिनिधित्व करता है
auto presentation = System::MakeObject<Presentation>(u"PowerPoint.pptx");

System::SharedPtr<PdfOptions> pdfOptions = System::MakeObject<PdfOptions>();

// PDF पासवर्ड और एक्सेस अनुमतियाँ सेट करता है
pdfOptions->set_Password(u"password");
pdfOptions->set_AccessPermissions(PdfAccessPermissions::PrintDocument | PdfAccessPermissions::HighQualityPrint);
// प्रस्तुति को PDF के रूप में सहेजता है
presentation->Save(u"PPTX-to-PDF.pdf", SaveFormat::Pdf, pdfOptions);
```
निम्नलिखित उदाहरण दिखाता है कि कैसे PowerPoint को नोट्स के साथ PDF में बदलें।
```cpp
// एक Presentation ऑब्जेक्ट का उदाहरण बनाता है जो प्रस्तुति फ़ाइल का प्रतिनिधित्व करता है
auto presentation = System::MakeObject<Presentation>(u"SelectedSlides.pptx");

auto auxPresentation = System::MakeObject<Presentation>();

auto slide = presentation->get_Slides()->idx_get(0);
auxPresentation->get_Slides()->InsertClone(0, slide);

// स्लाइड प्रकार और आकार सेट करना
auxPresentation->get_SlideSize()->SetSize(612.F, 792.F, SlideSizeScaleType::EnsureFit);

System::SharedPtr<PdfOptions> pdfOptions = System::MakeObject<PdfOptions>();
System::SharedPtr<NotesCommentsLayoutingOptions> slidesLayoutOptions = System::MakeObject<NotesCommentsLayoutingOptions>();
slidesLayoutOptions->set_NotesPosition(NotesPositions::BottomFull);
pdfOptions->set_SlidesLayoutOptions(slidesLayoutOptions);
auxPresentation->Save(u"PDFnotes_out.pdf", SaveFormat::Pdf, pdfOptions);
```

## देखें

* क्लास [SaveOptions](../saveoptions/)
* क्लास [IPdfOptions](../ipdfoptions/)
* नामस्थान [Aspose::Slides::Export](../)
* लाइब्रेरी [Aspose.Slides](../../)