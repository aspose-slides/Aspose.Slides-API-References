---
title: PdfOptions
second_title: Aspose.Slides for C++ API Reference
description: Provides options that control how a presentation is saved in Pdf format.
type: docs
weight: 521
url: /cpp/aspose.slides.export/pdfoptions/
---
## PdfOptions class


Provides options that control how a presentation is saved in Pdf format.

```cpp
class PdfOptions : public Aspose::Slides::Export::SaveOptions,
                   public Aspose::Slides::Export::IPdfOptions
```

## Methods

| Method | Description |
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
| [System::Drawing::Color](../../system.drawing/color/) [get_ImageTransparentColor](./get_imagetransparentcolor/)() override | Gets the image transparent color. |
| **uint8_t** [get_JpegQuality](./get_jpegquality/)() override | Returns a value determining the quality of the JPEG images inside PDF document. Read **uint8_t**. |
| [System::SharedPtr](../../system/sharedptr/)\<[INotesCommentsLayoutingOptions](../inotescommentslayoutingoptions/)\> [get_NotesCommentsLayouting](./get_notescommentslayouting/)() override | Provides options that control how notes and comments is placed in exported document. |
| [System::String](../../system/string/) [get_Password](./get_password/)() override | Setting user password to protect the PDF document. Read [System::String](../../system/string/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IProgressCallback](../../aspose.slides/iprogresscallback/)\> [get_ProgressCallback](../saveoptions/get_progresscallback/)() override | Represents a callback object for saving progress updates in percentage. See [IProgressCallback](../../aspose.slides/iprogresscallback/). |
| **bool** [get_SaveMetafilesAsPng](./get_savemetafilesaspng/)() override | True to convert all metafiles used in a presentation to the PNG images. Read **bool**. |
| **bool** [get_ShowHiddenSlides](./get_showhiddenslides/)() override | Specifies whether the generated document should include hidden slides or not. Default is **false**. |
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
| void [set_AccessPermissions](./set_accesspermissions/)([PdfAccessPermissions](../pdfaccesspermissions/)) override | Contains a set of flags specifying which access permissions should be granted when the document is opened with user access. See [PdfAccessPermissions](../pdfaccesspermissions/). |
| void [set_AdditionalCommonFontFamilies](./set_additionalcommonfontfamilies/)([System::ArrayPtr](../../system/arrayptr/)\<[System::String](../../system/string/)\>) override | Sets an array of user-defined names of font families which [Aspose.Slides](../../aspose.slides/) should consider common. Write [System::String](../../system/string/)[]. |
| void [set_ApplyImageTransparent](./set_applyimagetransparent/)(**bool**) override | Applies the specified transparent color to an image if **true**. |
| void [set_BestImagesCompressionRatio](./set_bestimagescompressionratio/)(**bool**) override | Indicates if the most effective compression (instead of the default one) for each image must be selected automatically. If set to **bool**.true, for every image in presentation the most appropriate compression algorithm will be chosen, what will lead to the smaller size of the resulting PDF document. |
| void [set_Compliance](./set_compliance/)([PdfCompliance](../pdfcompliance/)) override | Desired conformance level for generated PDF document. Write [PdfCompliance](../pdfcompliance/). |
| void [set_DefaultRegularFont](../saveoptions/set_defaultregularfont/)([System::String](../../system/string/)) override | Sets font used in case source font is not found. Writes [System::String](../../system/string/). |
| void [set_DrawSlidesFrame](./set_drawslidesframe/)(**bool**) override | True to draw black frame around each slide. Write **bool**. |
| void [set_EmbedFullFonts](./set_embedfullfonts/)(**bool**) override | Determines if all characters of font should be embedded or only used subset. Write **bool**. |
| void [set_EmbedTrueTypeFontsForASCII](./set_embedtruetypefontsforascii/)(**bool**) override | Determines if [Aspose.Slides](../../aspose.slides/) will embed common fonts for ASCII (33..127 code range) text. [Fonts](../../aspose.slides/fonts/) for character codes greater than 127 are always embedded. Common fonts list includes PDF's base 14 fonts and additional user specified fonts. Write **bool**. |
| void [set_ImageTransparentColor](./set_imagetransparentcolor/)([System::Drawing::Color](../../system.drawing/color/)) override | Sets the image transparent color. |
| void [set_JpegQuality](./set_jpegquality/)(**uint8_t**) override | Sets a value determining the quality of the JPEG images inside PDF document. Write **uint8_t**. |
| void [set_Password](./set_password/)([System::String](../../system/string/)) override | Setting user password to protect the PDF document. Write [System::String](../../system/string/). |
| void [set_ProgressCallback](../saveoptions/set_progresscallback/)([System::SharedPtr](../../system/sharedptr/)\<[IProgressCallback](../../aspose.slides/iprogresscallback/)\>) override | Represents a callback object for saving progress updates in percentage. See [IProgressCallback](../../aspose.slides/iprogresscallback/). |
| void [set_SaveMetafilesAsPng](./set_savemetafilesaspng/)(**bool**) override | True to convert all metafiles used in a presentation to the PNG images. Write **bool**. |
| void [set_ShowHiddenSlides](./set_showhiddenslides/)(**bool**) override | Specifies whether the generated document should include hidden slides or not. Default is **false**. |
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
## Remarks





The following example shows how to convert PowerPoint to PDF with custom options. 
```cpp
auto presentation = System::MakeObject<Presentation>(u"PowerPoint.pptx");

// Instantiates the PdfOptions class
System::SharedPtr<PdfOptions> pdfOptions = System::MakeObject<PdfOptions>();
// Sets the Jpeg quality
pdfOptions->set_JpegQuality(90);
// Sets the behavior for metafiles
pdfOptions->set_SaveMetafilesAsPng(true);
// Sets the text compression level
pdfOptions->set_TextCompression(PdfTextCompression::Flate);
// Defines the PDF standard
pdfOptions->set_Compliance(PdfCompliance::Pdf15);
// Saves the presentation as a PDF
presentation->Save(u"PowerPoint-to-PDF.pdf", SaveFormat::Pdf, pdfOptions);
```
 The following example shows how to convert PowerPoint to PDF with hidden slides. 
```cpp
// Instantiates a Presentation class that represents a PowerPoint file
auto presentation = System::MakeObject<Presentation>(u"PowerPoint.pptx");

// Instantiates the PdfOptions class
System::SharedPtr<PdfOptions> pdfOptions = System::MakeObject<PdfOptions>();
// Adds hidden slides
pdfOptions->set_ShowHiddenSlides(true);
// Saves the presentation as a PDF
presentation->Save(u"PowerPoint-to-PDF.pdf", SaveFormat::Pdf, pdfOptions);
```
 The following example shows how to convert PowerPoint to password protected PDF. 
```cpp
// Instantiates a Presentation object that represents a PowerPoint file
auto presentation = System::MakeObject<Presentation>(u"PowerPoint.pptx");

System::SharedPtr<PdfOptions> pdfOptions = System::MakeObject<PdfOptions>();

// Sets PDF password and access permissions
pdfOptions->set_Password(u"password");
pdfOptions->set_AccessPermissions(PdfAccessPermissions::PrintDocument | PdfAccessPermissions::HighQualityPrint);
// Saves the presentation as a PDF
presentation->Save(u"PPTX-to-PDF.pdf", SaveFormat::Pdf, pdfOptions);
```
 The following example shows how to convert PowerPoint to PDF with notes. 
```cpp
// Instantiate a Presentation object that represents a presentation file
auto presentation = System::MakeObject<Presentation>(u"SelectedSlides.pptx");

auto auxPresentation = System::MakeObject<Presentation>();

auto slide = presentation->get_Slides()->idx_get(0);
auxPresentation->get_Slides()->InsertClone(0, slide);

// Setting Slide Type and Size
auxPresentation->get_SlideSize()->SetSize(612.F, 792.F, SlideSizeScaleType::EnsureFit);

System::SharedPtr<PdfOptions> pdfOptions = System::MakeObject<PdfOptions>();
pdfOptions->get_NotesCommentsLayouting()->set_NotesPosition(NotesPositions::BottomFull);
auxPresentation->Save(u"PDFnotes_out.pdf", SaveFormat::Pdf, pdfOptions);
```

## See Also

* Class [SaveOptions](../saveoptions/)
* Class [IPdfOptions](../ipdfoptions/)
* Namespace [Aspose::Slides::Export](../)
* Library [Aspose.Slides](../../)
