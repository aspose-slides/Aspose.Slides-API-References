---
title: ISVGOptions
second_title: Aspose.Slides for C++ API Reference
description: Represents an SVG options.
type: docs
weight: 365
url: /cpp/aspose.slides.export/isvgoptions/
---
## ISVGOptions class


Represents an SVG options.

```cpp
class ISVGOptions : public virtual Aspose::Slides::Export::ISaveOptions
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
| virtual [System::String](../../system/string/) [get_DefaultRegularFont](../isaveoptions/get_defaultregularfont/)() | Returns font used in case source font is not found. Reads [System::String](../../system/string/). |
| virtual **bool** [get_DeletePicturesCroppedAreas](./get_deletepicturescroppedareas/)() | A boolean flag indicates if the cropped parts remain as part of the document. If true the cropped parts will removed, if false they will be serialized in the document (which can possible lead to a larger file) Read **bool**. |
| virtual **bool** [get_Disable3DText](./get_disable3dtext/)() | Determines whether the 3D text is disabled in SVG. Read **bool**. |
| virtual **bool** [get_DisableGradientSplit](./get_disablegradientsplit/)() | Disables splitting FromCornerX and FromCenter gradients. Read **bool**. |
| virtual **bool** [get_DisableLineEndCropping](./get_disablelineendcropping/)() | SVG 1.1 lacks ability to define insets for markers. [Aspose.Slides](../../aspose.slides/) SVG writing engine has workaround for that problem: it crops end of line with arrow, so, line doesn't overlap markers. This option switches off such behavior. Read **bool**. |
| virtual [SvgExternalFontsHandling](../svgexternalfontshandling/) [get_ExternalFontsHandling](./get_externalfontshandling/)() | Determines a way of handling externally loaded fonts. Read [SvgExternalFontsHandling](../svgexternalfontshandling/). |
| virtual **int32_t** [get_JpegQuality](./get_jpegquality/)() | Determines JPEG encoding quality. Read **int32_t**. |
| virtual **int32_t** [get_MetafileRasterizationDpi](./get_metafilerasterizationdpi/)() | Returns the lower resolution limit for metafile rasterization. Read **int32_t**. |
| virtual [Aspose::Slides::Export::PicturesCompression](../picturescompression/) [get_PicturesCompression](./get_picturescompression/)() | Represents the pictures compression level Read [PicturesCompression](../picturescompression/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IProgressCallback](../../aspose.slides/iprogresscallback/)\> [get_ProgressCallback](../isaveoptions/get_progresscallback/)() | Represents a callback object for saving progress updates in percentage. See [IProgressCallback](../../aspose.slides/iprogresscallback/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ISvgShapeFormattingController](../isvgshapeformattingcontroller/)\> [get_ShapeFormattingController](./get_shapeformattingcontroller/)() | Returns and sets a callback interface which allows user to control shape conversion. Read [ISvgShapeFormattingController](../isvgshapeformattingcontroller/). |
| virtual **bool** [get_UseFrameRotation](./get_useframerotation/)() | Determines whether to perform the specified rotation of the shape when rendering or not. Read **bool**. Default value is true. |
| virtual **bool** [get_UseFrameSize](./get_useframesize/)() | Determines whether the text frame will be included in a rendering area or not. Read **bool**. Default value is false. |
| virtual **bool** [get_VectorizeText](./get_vectorizetext/)() | Determines whether the text on a slide will be saved as graphics. Read **bool**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[Aspose::Slides::Warnings::IWarningCallback](../../aspose.slides.warnings/iwarningcallback/)\> [get_WarningCallback](../isaveoptions/get_warningcallback/)() | Returns an object which receives warnings and decides whether loading process will continue or will be aborted. Read [Aspose::Slides::Warnings::IWarningCallback](../../aspose.slides.warnings/iwarningcallback/). |
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
| virtual void [set_DefaultRegularFont](../isaveoptions/set_defaultregularfont/)([System::String](../../system/string/)) | Sets font used in case source font is not found. Writes [System::String](../../system/string/). |
| virtual void [set_DeletePicturesCroppedAreas](./set_deletepicturescroppedareas/)(**bool**) | A boolean flag indicates if the cropped parts remain as part of the document. If true the cropped parts will removed, if false they will be serialized in the document (which can possible lead to a larger file) Write **bool**. |
| virtual void [set_Disable3DText](./set_disable3dtext/)(**bool**) | Determines whether the 3D text is disabled in SVG. Write **bool**. |
| virtual void [set_DisableGradientSplit](./set_disablegradientsplit/)(**bool**) | Disables splitting FromCornerX and FromCenter gradients. Write **bool**. |
| virtual void [set_DisableLineEndCropping](./set_disablelineendcropping/)(**bool**) | SVG 1.1 lacks ability to define insets for markers. [Aspose.Slides](../../aspose.slides/) SVG writing engine has workaround for that problem: it crops end of line with arrow, so, line doesn't overlap markers. This option switches off such behavior. Write **bool**. |
| virtual void [set_ExternalFontsHandling](./set_externalfontshandling/)([SvgExternalFontsHandling](../svgexternalfontshandling/)) | Determines a way of handling externally loaded fonts. Write [SvgExternalFontsHandling](../svgexternalfontshandling/). |
| virtual void [set_JpegQuality](./set_jpegquality/)(**int32_t**) | Determines JPEG encoding quality. Write **int32_t**. |
| virtual void [set_MetafileRasterizationDpi](./set_metafilerasterizationdpi/)(**int32_t**) | Sets the lower resolution limit for metafile rasterization. Write **int32_t**. |
| virtual void [set_PicturesCompression](./set_picturescompression/)([Aspose::Slides::Export::PicturesCompression](../picturescompression/)) | Represents the pictures compression level Write [PicturesCompression](../picturescompression/). |
| virtual void [set_ProgressCallback](../isaveoptions/set_progresscallback/)([System::SharedPtr](../../system/sharedptr/)\<[IProgressCallback](../../aspose.slides/iprogresscallback/)\>) | Represents a callback object for saving progress updates in percentage. See [IProgressCallback](../../aspose.slides/iprogresscallback/). |
| virtual void [set_ShapeFormattingController](./set_shapeformattingcontroller/)([System::SharedPtr](../../system/sharedptr/)\<[ISvgShapeFormattingController](../isvgshapeformattingcontroller/)\>) | Returns and sets a callback interface which allows user to control shape conversion. Write [ISvgShapeFormattingController](../isvgshapeformattingcontroller/). |
| virtual void [set_UseFrameRotation](./set_useframerotation/)(**bool**) | Determines whether to perform the specified rotation of the shape when rendering or not. Write **bool**. Default value is true. |
| virtual void [set_UseFrameSize](./set_useframesize/)(**bool**) | Determines whether the text frame will be included in a rendering area or not. Write **bool**. Default value is false. |
| virtual void [set_VectorizeText](./set_vectorizetext/)(**bool**) | Determines whether the text on a slide will be saved as graphics. Write **bool**. |
| virtual void [set_WarningCallback](../isaveoptions/set_warningcallback/)([System::SharedPtr](../../system/sharedptr/)\<[Aspose::Slides::Warnings::IWarningCallback](../../aspose.slides.warnings/iwarningcallback/)\>) | Sets an object which receives warnings and decides whether loading process will continue or will be aborted. Write [Aspose::Slides::Warnings::IWarningCallback](../../aspose.slides.warnings/iwarningcallback/). |
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
## See Also

* Class [ISaveOptions](../isaveoptions/)
* Namespace [Aspose::Slides::Export](../)
* Library [Aspose.Slides](../../)