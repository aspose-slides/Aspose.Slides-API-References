---
title: SwfOptions
second_title: Aspose.Slides for C++ API Reference
description: Provides options that control how a presentation is saved in Swf format.
type: docs
weight: 690
url: /cpp/aspose.slides.export/swfoptions/
---
## SwfOptions class


Provides options that control how a presentation is saved in Swf format.

```cpp
class SwfOptions : public Aspose::Slides::Export::SaveOptions,
                   public Aspose::Slides::Export::ISwfOptions
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
| **bool** [get_Compressed](./get_compressed/)() override | Specifies whether the generated SWF document should be compressed or not. Default is **true**. |
| [System::String](../../system/string/) [get_DefaultRegularFont](../saveoptions/get_defaultregularfont/)() override | Returns font used in case source font is not found. Reads [System::String](../../system/string/). |
| **bool** [get_EnableContextMenu](./get_enablecontextmenu/)() override | Enable/disable context menu. Default is true. |
| **int32_t** [get_JpegQuality](./get_jpegquality/)() override | Specifies the quality of JPEG images. Default is 95. |
| [System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\> [get_LogoImageBytes](./get_logoimagebytes/)() override | Image that will be displayed as logo in the top right corner of the viewer. Image should be 32x64 pixels PNG image, otherwise logo can be displayed improperly. |
| [System::String](../../system/string/) [get_LogoLink](./get_logolink/)() override | Gets the full hyperlink address for a logo. Has an effect only if a [set_LogoImageBytes()](./set_logoimagebytes/) is specified. |
| [System::SharedPtr](../../system/sharedptr/)\<[INotesCommentsLayoutingOptions](../inotescommentslayoutingoptions/)\> [get_NotesCommentsLayouting](./get_notescommentslayouting/)() override | Provides options that control how notes and comments is placed in exported document. |
| [System::SharedPtr](../../system/sharedptr/)\<[IProgressCallback](../../aspose.slides/iprogresscallback/)\> [get_ProgressCallback](../saveoptions/get_progresscallback/)() override | Represents a callback object for saving progress updates in percentage. See [IProgressCallback](../../aspose.slides/iprogresscallback/). |
| **bool** [get_ShowBottomPane](./get_showbottompane/)() override | Show/hide bottom pane. Can be overridden in flashvars. Default is true. |
| **bool** [get_ShowFullScreen](./get_showfullscreen/)() override | Show/hide fullscreen button. Can be overridden in flashvars. Default is true. |
| **bool** [get_ShowHiddenSlides](./get_showhiddenslides/)() override | Specifies whether the generated document should include hidden slides or not. Default is **false**. |
| **bool** [get_ShowLeftPane](./get_showleftpane/)() override | Show/hide left pane. Can be overridden in flashvars. Default is true. |
| **bool** [get_ShowPageBorder](./get_showpageborder/)() override | Specifies whether border around pages should be shown. Default is true. |
| **bool** [get_ShowPageStepper](./get_showpagestepper/)() override | Show/hide page stepper. Can be overridden in flashvars. Default is true. |
| **bool** [get_ShowSearch](./get_showsearch/)() override | Show/hide search section. Can be overridden in flashvars. Default is true. |
| **bool** [get_ShowTopPane](./get_showtoppane/)() override | Show/hide whole top pane. Can be overridden in flashvars. Default is true. |
| **bool** [get_StartOpenLeftPane](./get_startopenleftpane/)() override | Start with opened left pane. Can be overridden in flashvars. Default is false. |
| **bool** [get_ViewerIncluded](./get_viewerincluded/)() override | Specifies whether the generated SWF document should include the integrated document viewer or not. Default is **true**. |
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
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Compares objects by reference. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Compares objects by reference. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Reference-compares value type object with nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Specialization of [Object::ReferenceEquals](../../system/object/referenceequals/) for case of string and nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Specialization of [Object::ReferenceEquals](../../system/object/referenceequals/) for case of strings. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Decreases shared reference count by specified value. |
| void [set_Compressed](./set_compressed/)(**bool**) override | Specifies whether the generated SWF document should be compressed or not. Default is **true**. |
| void [set_DefaultRegularFont](../saveoptions/set_defaultregularfont/)([System::String](../../system/string/)) override | Sets font used in case source font is not found. Writes [System::String](../../system/string/). |
| void [set_EnableContextMenu](./set_enablecontextmenu/)(**bool**) override | Enable/disable context menu. Default is true. |
| void [set_JpegQuality](./set_jpegquality/)(**int32_t**) override | Specifies the quality of JPEG images. Default is 95. |
| void [set_LogoImageBytes](./set_logoimagebytes/)([System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>) override | Image that will be displayed as logo in the top right corner of the viewer. Image should be 32x64 pixels PNG image, otherwise logo can be displayed improperly. |
| void [set_LogoLink](./set_logolink/)([System::String](../../system/string/)) override | Sets the full hyperlink address for a logo. Has an effect only if a [set_LogoImageBytes()](./set_logoimagebytes/) is specified. |
| void [set_ProgressCallback](../saveoptions/set_progresscallback/)([System::SharedPtr](../../system/sharedptr/)\<[IProgressCallback](../../aspose.slides/iprogresscallback/)\>) override | Represents a callback object for saving progress updates in percentage. See [IProgressCallback](../../aspose.slides/iprogresscallback/). |
| void [set_ShowBottomPane](./set_showbottompane/)(**bool**) override | Show/hide bottom pane. Can be overridden in flashvars. Default is true. |
| void [set_ShowFullScreen](./set_showfullscreen/)(**bool**) override | Show/hide fullscreen button. Can be overridden in flashvars. Default is true. |
| void [set_ShowHiddenSlides](./set_showhiddenslides/)(**bool**) override | Specifies whether the generated document should include hidden slides or not. Default is **false**. |
| void [set_ShowLeftPane](./set_showleftpane/)(**bool**) override | Show/hide left pane. Can be overridden in flashvars. Default is true. |
| void [set_ShowPageBorder](./set_showpageborder/)(**bool**) override | Specifies whether border around pages should be shown. Default is true. |
| void [set_ShowPageStepper](./set_showpagestepper/)(**bool**) override | Show/hide page stepper. Can be overridden in flashvars. Default is true. |
| void [set_ShowSearch](./set_showsearch/)(**bool**) override | Show/hide search section. Can be overridden in flashvars. Default is true. |
| void [set_ShowTopPane](./set_showtoppane/)(**bool**) override | Show/hide whole top pane. Can be overridden in flashvars. Default is true. |
| void [set_StartOpenLeftPane](./set_startopenleftpane/)(**bool**) override | Start with opened left pane. Can be overridden in flashvars. Default is false. |
| void [set_ViewerIncluded](./set_viewerincluded/)(**bool**) override | Specifies whether the generated SWF document should include the integrated document viewer or not. Default is **true**. |
| void [set_WarningCallback](../saveoptions/set_warningcallback/)([System::SharedPtr](../../system/sharedptr/)\<[Aspose::Slides::Warnings::IWarningCallback](../../aspose.slides.warnings/iwarningcallback/)\>) override | Returns of sets an object which receives warnings and decides whether loading process will continue or will be aborted. Write [Aspose::Slides::Warnings::IWarningCallback](../../aspose.slides.warnings/iwarningcallback/). |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Set n'th template argument a weak pointer (rather than shared). Allows switching pointers in containers to weak mode. |
| int [SharedCount](../../system/object/sharedcount/)() const | Gets current value of shared reference counter. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Increments shared reference count. Shouldn't be called directly; instead, use smart pointers or ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Decrements and returns shared reference count. Shouldn't be called directly; instead, use smart pointers or ThisProtector. |
|  [SwfOptions](./swfoptions/)() | Default constructor. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analog of C# [Object.ToString()](../../system/object/tostring/) method. Enables converting custom objects to string. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implements C# typeof([System.Object](../../system/object/)) construct. |
| void [Unlock](../../system/object/unlock/)() | Implements C# lock() statement unlocking. Call directly or use [LockContext](../../system/lockcontext/) sentry object. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Increments weak reference count. Shouldn't be called directly; instead, use smart pointers or ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Decrements weak reference count. Shouldn't be called directly; instead, use smart pointers or ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | Destroys object. Frees all internal data structures. |
## Remarks


The following example shows how to convert PowerPoint to SWF Flash. 
```cpp
auto presentation = System::MakeObject<Presentation>(u"HelloWorld.pptx");
auto swfOptions = System::MakeObject<SwfOptions>();

swfOptions->set_ViewerIncluded(false);
auto notesOptions = swfOptions->get_NotesCommentsLayouting();
notesOptions->set_NotesPosition(NotesPositions::BottomFull);

// Saving presentation and notes pages
presentation->Save(u"SaveAsSwf_out.swf", SaveFormat::Swf, swfOptions);
swfOptions->set_ViewerIncluded(true);
presentation->Save(u"SaveNotes_out.swf", SaveFormat::Swf, swfOptions);
```

## See Also

* Class [SaveOptions](../saveoptions/)
* Class [ISwfOptions](../iswfoptions/)
* Namespace [Aspose::Slides::Export](../)
* Library [Aspose.Slides](../../)