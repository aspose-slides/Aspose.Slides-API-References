---
title: SVGOptions
second_title: Aspose.Slides for C++ API Reference
description: Represents an SVG options.
type: docs
weight: 651
url: /cpp/aspose.slides.export/svgoptions/
---
## SVGOptions class


Represents an SVG options.

```cpp
class SVGOptions : public Aspose::Slides::Export::SaveOptions,
                   public Aspose::Slides::Export::ISVGOptions
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
| static [System::SharedPtr](../../system/sharedptr/)\<[SVGOptions](./)\> [get_Default](./get_default/)() | Returns default settings. Read-only [SVGOptions](./). |
| [System::String](../../system/string/) [get_DefaultRegularFont](../saveoptions/get_defaultregularfont/)() override | Returns font used in case source font is not found. Reads [System::String](../../system/string/). |
| **bool** [get_DeletePicturesCroppedAreas](./get_deletepicturescroppedareas/)() override | A boolean flag indicates if the cropped parts remain as part of the document. If true the cropped parts will removed, if false they will be serialized in the document (which can possible lead to a larger file) |
| **bool** [get_Disable3DText](./get_disable3dtext/)() override | Determines whether the 3D text is disabled in SVG. Read **bool**. |
| **bool** [get_DisableGradientSplit](./get_disablegradientsplit/)() override | Disables splitting FromCornerX and FromCenter gradients. Read **bool**. |
| **bool** [get_DisableLineEndCropping](./get_disablelineendcropping/)() override | SVG 1.1 lacks ability to define insets for markers. [Aspose.Slides](../../aspose.slides/) SVG writing engine has workaround for that problem: it crops end of line with arrow, so, line doesn't overlap markers. This option switches off such behavior. Read **bool**. |
| [SvgExternalFontsHandling](../svgexternalfontshandling/) [get_ExternalFontsHandling](./get_externalfontshandling/)() override | Determines a way of handling externally loaded fonts. Read [SvgExternalFontsHandling](../svgexternalfontshandling/). |
| **int32_t** [get_JpegQuality](./get_jpegquality/)() override | Determines JPEG encoding quality. Read **int32_t**. |
| **int32_t** [get_MetafileRasterizationDpi](./get_metafilerasterizationdpi/)() override | Returns the lower resolution limit for metafile rasterization. Read **int32_t**. |
| [Aspose::Slides::Export::PicturesCompression](../picturescompression/) [get_PicturesCompression](./get_picturescompression/)() override | Represents the pictures compression level |
| [System::SharedPtr](../../system/sharedptr/)\<[IProgressCallback](../../aspose.slides/iprogresscallback/)\> [get_ProgressCallback](../saveoptions/get_progresscallback/)() override | Represents a callback object for saving progress updates in percentage. See [IProgressCallback](../../aspose.slides/iprogresscallback/). |
| [System::SharedPtr](../../system/sharedptr/)\<[ISvgShapeFormattingController](../isvgshapeformattingcontroller/)\> [get_ShapeFormattingController](./get_shapeformattingcontroller/)() override | Returns and sets a callback interface which allows user to control shape conversion. Read [ISvgShapeFormattingController](../isvgshapeformattingcontroller/). |
| static [System::SharedPtr](../../system/sharedptr/)\<[SVGOptions](./)\> [get_Simple](./get_simple/)() | Returns settings for simpliest and smallest SVG file generation. Read-only [SVGOptions](./). |
| **bool** [get_UseFrameRotation](./get_useframerotation/)() override | Determines whether to perform the specified rotation of the shape when rendering or not. Read **bool**. Default value is true. |
| **bool** [get_UseFrameSize](./get_useframesize/)() override | Determines whether the text frame will be included in a rendering area or not. Read **bool**. Default value is false. |
| **bool** [get_VectorizeText](./get_vectorizetext/)() override | Determines whether the text on a slide will be saved as graphics. Read **bool**. |
| [System::SharedPtr](../../system/sharedptr/)\<[Aspose::Slides::Warnings::IWarningCallback](../../aspose.slides.warnings/iwarningcallback/)\> [get_WarningCallback](../saveoptions/get_warningcallback/)() override | Returns of sets an object which receives warnings and decides whether loading process will continue or will be aborted. Read [Aspose::Slides::Warnings::IWarningCallback](../../aspose.slides.warnings/iwarningcallback/). |
| static [System::SharedPtr](../../system/sharedptr/)\<[SVGOptions](./)\> [get_WYSIWYG](./get_wysiwyg/)() | Returns settings for most accurate SVG file generation. Read-only [SVGOptions](./). |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Gets reference counter data structure associated with the object. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analog of C# [Object.GetHashCode()](../../system/object/gethashcode/) method. Enables hashing of custom objects. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Gets actual type of object. Analog of C# [System.Object.GetType()](../../system/object/gettype/) call. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Check if object represents an instance of type described by targetType. Analog of C# 'is' operator. |
| void [Lock](../../system/object/lock/)() | Implements C# lock() statement locking. Call directly or use [LockContext](../../system/lockcontext/) sentry object. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analog of C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) method. Enables cloning custom types. |
|  [Object](../../system/object/object/)() | Creates object. Initializes all internal data structures. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Copy constructor. Doesn't copy anything, really, just initializes new object and enables copy constructing subclasses. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Assignment operator. Doesn't copy anything, really, just initializes new object and enables copy constructing subclasses. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Compares objects by reference. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Compares objects by reference. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Reference-compares value type object with nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Specialization of [Object::ReferenceEquals](../../system/object/referenceequals/) for case of string and nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Specialization of [Object::ReferenceEquals](../../system/object/referenceequals/) for case of strings. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Decreases shared reference count by specified value. |
| void [set_DefaultRegularFont](../saveoptions/set_defaultregularfont/)([System::String](../../system/string/)) override | Sets font used in case source font is not found. Writes [System::String](../../system/string/). |
| void [set_DeletePicturesCroppedAreas](./set_deletepicturescroppedareas/)(**bool**) override | A boolean flag indicates if the cropped parts remain as part of the document. If true the cropped parts will removed, if false they will be serialized in the document (which can possible lead to a larger file) |
| void [set_Disable3DText](./set_disable3dtext/)(**bool**) override | Determines whether the 3D text is disabled in SVG. Write **bool**. |
| void [set_DisableGradientSplit](./set_disablegradientsplit/)(**bool**) override | Disables splitting FromCornerX and FromCenter gradients. Write **bool**. |
| void [set_DisableLineEndCropping](./set_disablelineendcropping/)(**bool**) override | SVG 1.1 lacks ability to define insets for markers. [Aspose.Slides](../../aspose.slides/) SVG writing engine has workaround for that problem: it crops end of line with arrow, so, line doesn't overlap markers. This option switches off such behavior. Write **bool**. |
| void [set_ExternalFontsHandling](./set_externalfontshandling/)([SvgExternalFontsHandling](../svgexternalfontshandling/)) override | Determines a way of handling externally loaded fonts. Write [SvgExternalFontsHandling](../svgexternalfontshandling/). |
| void [set_JpegQuality](./set_jpegquality/)(**int32_t**) override | Determines JPEG encoding quality. Write **int32_t**. |
| void [set_MetafileRasterizationDpi](./set_metafilerasterizationdpi/)(**int32_t**) override | Sets the lower resolution limit for metafile rasterization. Write **int32_t**. |
| void [set_PicturesCompression](./set_picturescompression/)([Aspose::Slides::Export::PicturesCompression](../picturescompression/)) override | Represents the pictures compression level |
| void [set_ProgressCallback](../saveoptions/set_progresscallback/)([System::SharedPtr](../../system/sharedptr/)\<[IProgressCallback](../../aspose.slides/iprogresscallback/)\>) override | Represents a callback object for saving progress updates in percentage. See [IProgressCallback](../../aspose.slides/iprogresscallback/). |
| void [set_ShapeFormattingController](./set_shapeformattingcontroller/)([System::SharedPtr](../../system/sharedptr/)\<[ISvgShapeFormattingController](../isvgshapeformattingcontroller/)\>) override | Returns and sets a callback interface which allows user to control shape conversion. Write [ISvgShapeFormattingController](../isvgshapeformattingcontroller/). |
| void [set_UseFrameRotation](./set_useframerotation/)(**bool**) override | Determines whether to perform the specified rotation of the shape when rendering or not. Write **bool**. Default value is true. |
| void [set_UseFrameSize](./set_useframesize/)(**bool**) override | Determines whether the text frame will be included in a rendering area or not. Write **bool**. Default value is false. |
| void [set_VectorizeText](./set_vectorizetext/)(**bool**) override | Determines whether the text on a slide will be saved as graphics. Write **bool**. |
| void [set_WarningCallback](../saveoptions/set_warningcallback/)([System::SharedPtr](../../system/sharedptr/)\<[Aspose::Slides::Warnings::IWarningCallback](../../aspose.slides.warnings/iwarningcallback/)\>) override | Returns of sets an object which receives warnings and decides whether loading process will continue or will be aborted. Write [Aspose::Slides::Warnings::IWarningCallback](../../aspose.slides.warnings/iwarningcallback/). |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Set n'th template argument a weak pointer (rather than shared). Allows switching pointers in containers to weak mode. |
| int [SharedCount](../../system/object/sharedcount/)() const | Gets current value of shared reference counter. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Increments shared reference count. Shouldn't be called directly; instead, use smart pointers or ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Decrements and returns shared reference count. Shouldn't be called directly; instead, use smart pointers or ThisProtector. |
|  [SVGOptions](./svgoptions/)() | Initializes a new instance of the [SVGOptions](./) class. |
|  [SVGOptions](./svgoptions/)([System::SharedPtr](../../system/sharedptr/)\<[ILinkEmbedController](../ilinkembedcontroller/)\>) | Initializes a new instance of the [SVGOptions](./) class specifying the link embedding controller object. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analog of C# [Object.ToString()](../../system/object/tostring/) method. Enables converting custom objects to string. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implements C# typeof([System.Object](../../system/object/)) construct. |
| void [Unlock](../../system/object/unlock/)() | Implements C# lock() statement unlocking. Call directly or use [LockContext](../../system/lockcontext/) sentry object. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Increments weak reference count. Shouldn't be called directly; instead, use smart pointers or ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Decrements weak reference count. Shouldn't be called directly; instead, use smart pointers or ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | Destroys object. Frees all internal data structures. |
## See Also

* Class [SaveOptions](../saveoptions/)
* Class [ISVGOptions](../isvgoptions/)
* Namespace [Aspose::Slides::Export](../)
* Library [Aspose.Slides](../../)