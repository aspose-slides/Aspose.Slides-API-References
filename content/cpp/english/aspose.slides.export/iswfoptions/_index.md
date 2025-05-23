---
title: ISwfOptions
second_title: Aspose.Slides for C++ API Reference
description: Provides options that control how a presentation is saved in SWF format.
type: docs
weight: 482
url: /aspose.slides.export/iswfoptions/
---
## ISwfOptions class


Provides options that control how a presentation is saved in SWF format.

```cpp
class ISwfOptions : public virtual Aspose::Slides::Export::ISaveOptions
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
| virtual **bool** [get_Compressed](./get_compressed/)() | Specifies whether the generated SWF document should be compressed or not. Default is **true**. |
| virtual [System::String](../../system/string/) [get_DefaultRegularFont](../isaveoptions/get_defaultregularfont/)() | Returns font used in case source font is not found. Reads [System::String](../../system/string/). |
| virtual **bool** [get_EnableContextMenu](./get_enablecontextmenu/)() | Enable/disable context menu. Default is true. |
| virtual [Aspose::Slides::GradientStyle](../../aspose.slides/gradientstyle/) [get_GradientStyle](../isaveoptions/get_gradientstyle/)() | Returns the visual style of the gradient. Read [GradientStyle](../../aspose.slides/gradientstyle/). |
| virtual **int32_t** [get_JpegQuality](./get_jpegquality/)() | Specifies the quality of JPEG images. 

 Default is 95. |
| virtual [System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\> [get_LogoImageBytes](./get_logoimagebytes/)() | Image that will be displayed as logo in the top right corner of the viewer. 

 Image should be 32x64 pixels PNG image, otherwise logo can be displayed improperly. |
| virtual [System::String](../../system/string/) [get_LogoLink](./get_logolink/)() | Gets the full hyperlink address for a logo. Has an effect only if a [set_LogoImageBytes()](../swfoptions/set_logoimagebytes/) is specified. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[INotesCommentsLayoutingOptions](../inotescommentslayoutingoptions/)\> [get_NotesCommentsLayouting](./get_notescommentslayouting/)() | Provides options that control how notes and comments is placed in exported document. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IProgressCallback](../../aspose.slides/iprogresscallback/)\> [get_ProgressCallback](../isaveoptions/get_progresscallback/)() | Represents a callback object for saving progress updates in percentage. See [IProgressCallback](../../aspose.slides/iprogresscallback/). |
| virtual **bool** [get_ShowBottomPane](./get_showbottompane/)() | Show/hide bottom pane. Can be overridden in flashvars. Default is true. |
| virtual **bool** [get_ShowFullScreen](./get_showfullscreen/)() | Show/hide fullscreen button. Can be overridden in flashvars. Default is true. |
| virtual **bool** [get_ShowHiddenSlides](./get_showhiddenslides/)() | Specifies whether the generated document should include hidden slides or not. Default is **false**. |
| virtual **bool** [get_ShowLeftPane](./get_showleftpane/)() | Show/hide left pane. Can be overridden in flashvars. Default is true. |
| virtual **bool** [get_ShowPageBorder](./get_showpageborder/)() | Specifies whether border around pages should be shown. Default is true. |
| virtual **bool** [get_ShowPageStepper](./get_showpagestepper/)() | Show/hide page stepper. Can be overridden in flashvars. Default is true. |
| virtual **bool** [get_ShowSearch](./get_showsearch/)() | Show/hide search section. Can be overridden in flashvars. Default is true. |
| virtual **bool** [get_ShowTopPane](./get_showtoppane/)() | Show/hide whole top pane. Can be overridden in flashvars. Default is true. |
| virtual **bool** [get_SkipJavaScriptLinks](../isaveoptions/get_skipjavascriptlinks/)() | Specifies whether to skip hyperlinks with JavaScript calls when saving the presentation. Read **bool**. The default value is **false**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ISlidesLayoutOptions](../islideslayoutoptions/)\> [get_SlidesLayoutOptions](./get_slideslayoutoptions/)() | Gets the mode in which slides are placed on the page when exporting a presentation [ISlidesLayoutOptions](../islideslayoutoptions/). This property doesn't support assigning objects of type **[Aspose.Slides.Export.HandoutLayoutingOptions](../handoutlayoutingoptions/)** |
| virtual **bool** [get_StartOpenLeftPane](./get_startopenleftpane/)() | Start with opened left pane. Can be overridden in flashvars. Default is false. |
| virtual **bool** [get_ViewerIncluded](./get_viewerincluded/)() | Specifies whether the generated SWF document should include the integrated document viewer or not. Default is **true**. |
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
| virtual void [set_Compressed](./set_compressed/)(**bool**) | Specifies whether the generated SWF document should be compressed or not. Default is **true**. |
| virtual void [set_DefaultRegularFont](../isaveoptions/set_defaultregularfont/)([System::String](../../system/string/)) | Sets font used in case source font is not found. Writes [System::String](../../system/string/). |
| virtual void [set_EnableContextMenu](./set_enablecontextmenu/)(**bool**) | Enable/disable context menu. Default is true. |
| virtual void [set_GradientStyle](../isaveoptions/set_gradientstyle/)([Aspose::Slides::GradientStyle](../../aspose.slides/gradientstyle/)) | Sets the visual style of the gradient. Write [GradientStyle](../../aspose.slides/gradientstyle/). |
| virtual void [set_JpegQuality](./set_jpegquality/)(**int32_t**) | Specifies the quality of JPEG images. 

 Default is 95. |
| virtual void [set_LogoImageBytes](./set_logoimagebytes/)([System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>) | Image that will be displayed as logo in the top right corner of the viewer. 

 Image should be 32x64 pixels PNG image, otherwise logo can be displayed improperly. |
| virtual void [set_LogoLink](./set_logolink/)([System::String](../../system/string/)) | Sets the full hyperlink address for a logo. Has an effect only if a [set_LogoImageBytes()](../swfoptions/set_logoimagebytes/) is specified. |
| virtual void [set_ProgressCallback](../isaveoptions/set_progresscallback/)([System::SharedPtr](../../system/sharedptr/)\<[IProgressCallback](../../aspose.slides/iprogresscallback/)\>) | Represents a callback object for saving progress updates in percentage. See [IProgressCallback](../../aspose.slides/iprogresscallback/). |
| virtual void [set_ShowBottomPane](./set_showbottompane/)(**bool**) | Show/hide bottom pane. Can be overridden in flashvars. Default is true. |
| virtual void [set_ShowFullScreen](./set_showfullscreen/)(**bool**) | Show/hide fullscreen button. Can be overridden in flashvars. Default is true. |
| virtual void [set_ShowHiddenSlides](./set_showhiddenslides/)(**bool**) | Specifies whether the generated document should include hidden slides or not. Default is **false**. |
| virtual void [set_ShowLeftPane](./set_showleftpane/)(**bool**) | Show/hide left pane. Can be overridden in flashvars. Default is true. |
| virtual void [set_ShowPageBorder](./set_showpageborder/)(**bool**) | Specifies whether border around pages should be shown. Default is true. |
| virtual void [set_ShowPageStepper](./set_showpagestepper/)(**bool**) | Show/hide page stepper. Can be overridden in flashvars. Default is true. |
| virtual void [set_ShowSearch](./set_showsearch/)(**bool**) | Show/hide search section. Can be overridden in flashvars. Default is true. |
| virtual void [set_ShowTopPane](./set_showtoppane/)(**bool**) | Show/hide whole top pane. Can be overridden in flashvars. Default is true. |
| virtual void [set_SkipJavaScriptLinks](../isaveoptions/set_skipjavascriptlinks/)(**bool**) | Specifies whether to skip hyperlinks with JavaScript calls when saving the presentation. Write **bool**. The default value is **false**. |
| virtual void [set_SlidesLayoutOptions](./set_slideslayoutoptions/)([System::SharedPtr](../../system/sharedptr/)\<[ISlidesLayoutOptions](../islideslayoutoptions/)\>) | Sets the mode in which slides are placed on the page when exporting a presentation [ISlidesLayoutOptions](../islideslayoutoptions/). This property doesn't support assigning objects of type **[Aspose.Slides.Export.HandoutLayoutingOptions](../handoutlayoutingoptions/)** |
| virtual void [set_StartOpenLeftPane](./set_startopenleftpane/)(**bool**) | Start with opened left pane. Can be overridden in flashvars. Default is false. |
| virtual void [set_ViewerIncluded](./set_viewerincluded/)(**bool**) | Specifies whether the generated SWF document should include the integrated document viewer or not. Default is **true**. |
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