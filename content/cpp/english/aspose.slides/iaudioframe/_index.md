---
title: IAudioFrame
second_title: Aspose.Slides for C++ API Reference
description: Represents an audio clip on a slide.
type: docs
weight: 1353
url: /aspose.slides/iaudioframe/
---
## IAudioFrame class


Represents an audio clip on a slide.

```cpp
class IAudioFrame : public virtual Aspose::Slides::IPictureFrame
```

## Methods

| Method | Description |
| --- | --- |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IPlaceholder](../iplaceholder/)\> [AddPlaceholder](../ishape/addplaceholder/)([System::SharedPtr](../../system/sharedptr/)\<[IPlaceholder](../iplaceholder/)\>) | Adds a new placeholder if there is no and sets placeholder properties to a specified one. |
| virtual [System::ArrayPtr](../../system/arrayptr/)\<[System::SharedPtr](../../system/sharedptr/)\<[IShapeElement](../ishapeelement/)\>\> [CreateShapeElements](../igeometryshape/createshapeelements/)() | Creates and returns array of shape's elements. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Compares objects using C# [Object.Equals](../../system/object/equals/) semantics. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Compares reference type objects in C# style. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Compares value type objects in C# style. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emulates C#-style floating point comparison where two NaNs are considered equal even though according to IEC 60559:1989 NaN is not equal to any value, including NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emulates C#-style floating point comparison where two NaNs are considered equal even though according to IEC 60559:1989 NaN is not equal to any value, including NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | For internal purposes only. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IAdjustValue](../iadjustvalue/)\> [get_Adjustment](../igeometryshape/get_adjustment/)(**int32_t**) | Returns a shape's adjustments value at the specified index. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IAdjustValueCollection](../iadjustvaluecollection/)\> [get_Adjustments](../igeometryshape/get_adjustments/)() | Returns a collection of shape's adjustment values. Read-only [IAdjustValueCollection](../iadjustvaluecollection/). |
| virtual [System::String](../../system/string/) [get_AlternativeText](../ishape/get_alternativetext/)() | Returns the alternative text associated with a shape. Read [System::String](../../system/string/). |
| virtual [System::String](../../system/string/) [get_AlternativeTextTitle](../ishape/get_alternativetexttitle/)() | Returns the title of alternative text associated with a shape. Read [System::String](../../system/string/). |
| virtual **int32_t** [get_AudioCdEndTrack](./get_audiocdendtrack/)() | Returns a last track index Read **int32_t**. |
| virtual **int32_t** [get_AudioCdEndTrackTime](./get_audiocdendtracktime/)() | Returns a last track time. Read **int32_t**. |
| virtual **int32_t** [get_AudioCdStartTrack](./get_audiocdstarttrack/)() | Returns a start track index. Read **int32_t**. |
| virtual **int32_t** [get_AudioCdStartTrackTime](./get_audiocdstarttracktime/)() | Returns a start track time. Read **int32_t**. |
| virtual [Aspose::Slides::BlackWhiteMode](../blackwhitemode/) [get_BlackWhiteMode](../ishape/get_blackwhitemode/)() | Property specifies how a shape will render in black-and-white display mode.. Read [Slides::BlackWhiteMode](../blackwhitemode/). |
| virtual **int32_t** [get_ConnectionSiteCount](../ishape/get_connectionsitecount/)() | Returns the number of connection sites on the shape. Read-only **int32_t**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ICustomData](../icustomdata/)\> [get_CustomData](../ishape/get_customdata/)() | Returns the shape's custom data. Read-only [ICustomData](../icustomdata/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IEffectFormat](../ieffectformat/)\> [get_EffectFormat](../ishape/get_effectformat/)() | Returns the [EffectFormat](../effectformat/) object which contains pixel effects applied to a shape. Read-only [IEffectFormat](../ieffectformat/). |
| virtual **bool** [get_Embedded](./get_embedded/)() | Determines whether a sound is embedded to a presentation. Read-only **bool**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IAudio](../iaudio/)\> [get_EmbeddedAudio](./get_embeddedaudio/)() | Returns embedded audio object. Read [IAudio](../iaudio/). |
| virtual **float** [get_FadeInDuration](./get_fadeinduration/)() | Specifies the time duration for the initial fade-in of the media in milliseconds. Read **float**. |
| virtual **float** [get_FadeOutDuration](./get_fadeoutduration/)() | Specifies the time duration for the ending fade-out of the media in milliseconds. Read **float**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IFillFormat](../ifillformat/)\> [get_FillFormat](../ishape/get_fillformat/)() | Returns the [FillFormat](../fillformat/) object that contains fill formatting properties for a shape. Read-only [IFillFormat](../ifillformat/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../ishapeframe/)\> [get_Frame](../ishape/get_frame/)() | Returns the shape frame's properties. Read [IShapeFrame](../ishapeframe/). |
| virtual **float** [get_Height](../ishape/get_height/)() | Gets the height of the shape, measured in points. Read **float**. |
| virtual **bool** [get_Hidden](../ishape/get_hidden/)() | Determines whether the shape is hidden. Read **bool**. |
| virtual **bool** [get_HideAtShowing](./get_hideatshowing/)() | Determines whether an [AudioFrame](../audioframe/) is hidden. Read **bool**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../ihyperlink/)\> [get_HyperlinkClick](../ihyperlinkcontainer/get_hyperlinkclick/)() | Returns the hyperlink defined for mouse click. Read [IHyperlink](../ihyperlink/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IHyperlinkManager](../ihyperlinkmanager/)\> [get_HyperlinkManager](../ihyperlinkcontainer/get_hyperlinkmanager/)() | Hyperlinks manager Read-only [IHyperlinkManager](../ihyperlinkmanager/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../ihyperlink/)\> [get_HyperlinkMouseOver](../ihyperlinkcontainer/get_hyperlinkmouseover/)() | Returns the hyperlink defined for mouse over. Read [IHyperlink](../ihyperlink/). |
| virtual **bool** [get_IsDecorative](../ishape/get_isdecorative/)() | Gets 'Mark as decorative' option Reed/write **bool**. |
| virtual **bool** [get_IsGrouped](../ishape/get_isgrouped/)() | Determines whether the shape is grouped. Read-only **bool**. |
| virtual **bool** [get_IsTextHolder](../ishape/get_istextholder/)() | Determines whether the shape is TextHolder. Read-only **bool**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ILineFormat](../ilineformat/)\> [get_LineFormat](../ishape/get_lineformat/)() | Returns the [LineFormat](../lineformat/) object that contains line formatting properties for a shape. Read-only [ILineFormat](../ilineformat/). |
| virtual [System::String](../../system/string/) [get_LinkPathLong](./get_linkpathlong/)() | Returns the name of an audio file which is linked to an [AudioFrame](../audioframe/). Read [System::String](../../system/string/). |
| virtual [System::String](../../system/string/) [get_Name](../ishape/get_name/)() | Returns the name of a shape. Read [System::String](../../system/string/). |
| virtual **uint32_t** [get_OfficeInteropShapeId](../ishape/get_officeinteropshapeid/)() | Returns a slide-scoped unique identifier that remains constant for the lifetime of the shape and lets PowerPoint or interop code reliably reference the shape from anywhere in the document. Read-only **uint32_t**. See also [IShape::get_UniqueId](../ishape/get_uniqueid/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IGroupShape](../igroupshape/)\> [get_ParentGroup](../ishape/get_parentgroup/)() | Returns parent [GroupShape](../groupshape/) object if shape is grouped. Otherwise returns null. Read-only [IGroupShape](../igroupshape/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IPictureFillFormat](../ipicturefillformat/)\> [get_PictureFormat](../ipictureframe/get_pictureformat/)() | Returns the [PictureFillFormat](../picturefillformat/) object for a picture frame. Read-only [IPictureFillFormat](../ipicturefillformat/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IPictureFrameLock](../ipictureframelock/)\> [get_PictureFrameLock](../ipictureframe/get_pictureframelock/)() | Returns [PictureFrame](../pictureframe/)'s locks. Read-only [IPictureFrameLock](../ipictureframelock/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IPlaceholder](../iplaceholder/)\> [get_Placeholder](../ishape/get_placeholder/)() | Returns the placeholder for a shape. Read-only [IPlaceholder](../iplaceholder/). |
| virtual **bool** [get_PlayAcrossSlides](./get_playacrossslides/)() | Determines whether an audio is playing across the slides. Read **bool**. |
| virtual **bool** [get_PlayLoopMode](./get_playloopmode/)() | Determines whether an audio is looped. Read **bool**. |
| virtual [AudioPlayModePreset](../audioplaymodepreset/) [get_PlayMode](./get_playmode/)() | Returns the audio play mode. Read [AudioPlayModePreset](../audioplaymodepreset/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IPresentation](../ipresentation/)\> [get_Presentation](../ipresentationcomponent/get_presentation/)() | Returns the presentation. Read-only [IPresentation](../ipresentation/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../ishapeframe/)\> [get_RawFrame](../ishape/get_rawframe/)() | Returns the raw shape frame's properties. Read [IShapeFrame](../ishapeframe/). |
| virtual **float** [get_RelativeScaleHeight](../ipictureframe/get_relativescaleheight/)() | Returns the scale of height(relative to original picture size) of the picture frame. Value 1.0 corresponds to 100%. Read **float**. |
| virtual **float** [get_RelativeScaleWidth](../ipictureframe/get_relativescalewidth/)() | Returns the scale of width (relative to original picture size) of the picture frame. Value 1.0 corresponds to 100%. Read **float**. |
| virtual **bool** [get_RewindAudio](./get_rewindaudio/)() | Determines whether an audio is automatically rewinded to start after playing. Read **bool**. |
| virtual **float** [get_Rotation](../ishape/get_rotation/)() | Returns the number of degrees the specified shape is rotated around the z-axis. A positive value indicates clockwise rotation; a negative value indicates counterclockwise rotation. Read **float**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IBaseShapeLock](../ibaseshapelock/)\> [get_ShapeLock](../ishape/get_shapelock/)() | Returns shape's locks. Read-only [IBaseShapeLock](../ibaseshapelock/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IShapeStyle](../ishapestyle/)\> [get_ShapeStyle](../igeometryshape/get_shapestyle/)() | Returns shape's style object. Read-only [IShapeStyle](../ishapestyle/). |
| virtual [Aspose::Slides::ShapeType](../shapetype/) [get_ShapeType](../igeometryshape/get_shapetype/)() | Returns the geometry preset type. Note: on value changing all adjustment values will reset to their default values. Read [Slides::ShapeType](../shapetype/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IBaseSlide](../ibaseslide/)\> [get_Slide](../islidecomponent/get_slide/)() | Returns the base slide. Read-only [IBaseSlide](../ibaseslide/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IThreeDFormat](../ithreedformat/)\> [get_ThreeDFormat](../ishape/get_threedformat/)() | Returns the [ThreeDFormat](../threedformat/) object that contains line formatting properties for a shape. Read-only [IThreeDFormat](../ithreedformat/). |
| virtual **float** [get_TrimFromEnd](./get_trimfromend/)() | Specifies the time duration to be removed from the end of the media during playback, in milliseconds. Read **float**. |
| virtual **float** [get_TrimFromStart](./get_trimfromstart/)() | Specifies the time duration to be removed from the beginning of the media during playback, in milliseconds. Read **float**. |
| virtual **uint32_t** [get_UniqueId](../ishape/get_uniqueid/)() | Returns an internal, presentation-scoped identifier intended for use by add-ins or other code. Because this value can be reassigned by the user or programmatically, it must not be treated as a persistent unique key. Read-only **uint32_t**. See also [IShape::get_OfficeInteropShapeId](../ishape/get_officeinteropshapeid/). |
| virtual [AudioVolumeMode](../audiovolumemode/) [get_Volume](./get_volume/)() | Returns the audio volume. Read [AudioVolumeMode](../audiovolumemode/). |
| virtual **float** [get_VolumeValue](./get_volumevalue/)() | Returns the audio volume in percents. Read **float**. |
| virtual **float** [get_Width](../ishape/get_width/)() | Gets the width of the shape, measured in points. Read **float**. |
| virtual **float** [get_X](../ishape/get_x/)() | Gets the x-coordinate of the shape's upper-left corner, measured in points. Read **float**. |
| virtual **float** [get_Y](../ishape/get_y/)() | Gets the y-coordinate of the shape's upper-left corner, measured in points. Read **float**. |
| virtual **int32_t** [get_ZOrderPosition](../ishape/get_zorderposition/)() | Returns the position of a shape in the z-order. Shapes[0] returns the shape at the back of the z-order, and Shapes[Shapes.Count - 1] returns the shape at the front of the z-order. Read-only **int32_t**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IShape](../ishape/)\> [GetBasePlaceholder](../ishape/getbaseplaceholder/)() | Returns a basic placeholder shape (shape from the layout and/or master slide that the current shape is inherited from). |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Gets reference counter data structure associated with the object. |
| virtual [System::ArrayPtr](../../system/arrayptr/)\<[System::SharedPtr](../../system/sharedptr/)\<[IGeometryPath](../igeometrypath/)\>\> [GetGeometryPaths](../igeometryshape/getgeometrypaths/)() | Returns the copy of path of the geometry shape. Coordinates are relative to the left top corner of the shape. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analog of C# [Object.GetHashCode()](../../system/object/gethashcode/) method. Enables hashing of custom objects. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IImage](../iimage/)\> [GetImage](../ishape/getimage/)() | Returns shape thumbnail. [ShapeThumbnailBounds::Shape](../shapethumbnailbounds/) shape thumbnail bounds type is used by default. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IImage](../iimage/)\> [GetImage](../ishape/getimage/)([ShapeThumbnailBounds](../shapethumbnailbounds/), **float**, **float**) | Returns shape thumbnail. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[System::Drawing::Bitmap](../../system.drawing/bitmap/)\> [GetThumbnail](../ishape/getthumbnail/)() | Returns shape thumbnail. [ShapeThumbnailBounds::Shape](../shapethumbnailbounds/) shape thumbnail bounds type is used by default. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[System::Drawing::Bitmap](../../system.drawing/bitmap/)\> [GetThumbnail](../ishape/getthumbnail/)([ShapeThumbnailBounds](../shapethumbnailbounds/), **float**, **float**) | Returns shape thumbnail. |
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
| virtual void [RemovePlaceholder](../ishape/removeplaceholder/)() | Defines that this shape isn't a placeholder. |
| virtual void [set_AlternativeText](../ishape/set_alternativetext/)([System::String](../../system/string/)) | Sets the alternative text associated with a shape. Write [System::String](../../system/string/). |
| virtual void [set_AlternativeTextTitle](../ishape/set_alternativetexttitle/)([System::String](../../system/string/)) | Sets the title of alternative text associated with a shape. Write [System::String](../../system/string/). |
| virtual void [set_AudioCdEndTrack](./set_audiocdendtrack/)(**int32_t**) | Sets a last track index Write **int32_t**. |
| virtual void [set_AudioCdEndTrackTime](./set_audiocdendtracktime/)(**int32_t**) | Sets a last track time. Write **int32_t**. |
| virtual void [set_AudioCdStartTrack](./set_audiocdstarttrack/)(**int32_t**) | Sets a start track index. Write **int32_t**. |
| virtual void [set_AudioCdStartTrackTime](./set_audiocdstarttracktime/)(**int32_t**) | Sets a start track time. Write **int32_t**. |
| virtual void [set_BlackWhiteMode](../ishape/set_blackwhitemode/)([Aspose::Slides::BlackWhiteMode](../blackwhitemode/)) | Property specifies how a shape will render in black-and-white display mode.. Write [Slides::BlackWhiteMode](../blackwhitemode/). |
| virtual void [set_EmbeddedAudio](./set_embeddedaudio/)([System::SharedPtr](../../system/sharedptr/)\<[IAudio](../iaudio/)\>) | Sets embedded audio object. Write [IAudio](../iaudio/). |
| virtual void [set_FadeInDuration](./set_fadeinduration/)(**float**) | Specifies the time duration for the initial fade-in of the media in milliseconds. Write **float**. |
| virtual void [set_FadeOutDuration](./set_fadeoutduration/)(**float**) | Specifies the time duration for the ending fade-out of the media in milliseconds. Write **float**. |
| virtual void [set_Frame](../ishape/set_frame/)([System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../ishapeframe/)\>) | Sets the shape frame's properties. Write [IShapeFrame](../ishapeframe/). |
| virtual void [set_Height](../ishape/set_height/)(**float**) | Sets the height of the shape, measured in points. Write **float**. |
| virtual void [set_Hidden](../ishape/set_hidden/)(**bool**) | Determines whether the shape is hidden. Write **bool**. |
| virtual void [set_HideAtShowing](./set_hideatshowing/)(**bool**) | Determines whether an [AudioFrame](../audioframe/) is hidden. Write **bool**. |
| virtual void [set_HyperlinkClick](../ihyperlinkcontainer/set_hyperlinkclick/)([System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../ihyperlink/)\>) | Sets the hyperlink defined for mouse click. Write [IHyperlink](../ihyperlink/). |
| virtual void [set_HyperlinkMouseOver](../ihyperlinkcontainer/set_hyperlinkmouseover/)([System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../ihyperlink/)\>) | Sets the hyperlink defined for mouse over. Write [IHyperlink](../ihyperlink/). |
| virtual void [set_IsDecorative](../ishape/set_isdecorative/)(**bool**) | Sets 'Mark as decorative' option Reed/write **bool**. |
| virtual void [set_LinkPathLong](./set_linkpathlong/)([System::String](../../system/string/)) | Sets the name of an audio file which is linked to an [AudioFrame](../audioframe/). Write [System::String](../../system/string/). |
| virtual void [set_Name](../ishape/set_name/)([System::String](../../system/string/)) | Sets the name of a shape. Write [System::String](../../system/string/). |
| virtual void [set_PlayAcrossSlides](./set_playacrossslides/)(**bool**) | Determines whether an audio is playing across the slides. Write **bool**. |
| virtual void [set_PlayLoopMode](./set_playloopmode/)(**bool**) | Determines whether an audio is looped. Write **bool**. |
| virtual void [set_PlayMode](./set_playmode/)([AudioPlayModePreset](../audioplaymodepreset/)) | Sets the audio play mode. Write [AudioPlayModePreset](../audioplaymodepreset/). |
| virtual void [set_RawFrame](../ishape/set_rawframe/)([System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../ishapeframe/)\>) | Sets the raw shape frame's properties. Write [IShapeFrame](../ishapeframe/). |
| virtual void [set_RelativeScaleHeight](../ipictureframe/set_relativescaleheight/)(**float**) | Sets the scale of height(relative to original picture size) of the picture frame. Value 1.0 corresponds to 100%. Write **float**. |
| virtual void [set_RelativeScaleWidth](../ipictureframe/set_relativescalewidth/)(**float**) | Sets the scale of width (relative to original picture size) of the picture frame. Value 1.0 corresponds to 100%. Write **float**. |
| virtual void [set_RewindAudio](./set_rewindaudio/)(**bool**) | Determines whether an audio is automatically rewinded to start after playing. Write **bool**. |
| virtual void [set_Rotation](../ishape/set_rotation/)(**float**) | Sets the number of degrees the specified shape is rotated around the z-axis. A positive value indicates clockwise rotation; a negative value indicates counterclockwise rotation. Write **float**. |
| virtual void [set_ShapeType](../igeometryshape/set_shapetype/)([Aspose::Slides::ShapeType](../shapetype/)) | Sets the geometry preset type. Note: on value changing all adjustment values will reset to their default values. Write [Slides::ShapeType](../shapetype/). |
| virtual void [set_TrimFromEnd](./set_trimfromend/)(**float**) | Specifies the time duration to be removed from the end of the media during playback, in milliseconds. Write **float**. |
| virtual void [set_TrimFromStart](./set_trimfromstart/)(**float**) | Specifies the time duration to be removed from the beginning of the media during playback, in milliseconds. Write **float**. |
| virtual void [set_Volume](./set_volume/)([AudioVolumeMode](../audiovolumemode/)) | Sets the audio volume. Write [AudioVolumeMode](../audiovolumemode/). |
| virtual void [set_VolumeValue](./set_volumevalue/)(**float**) | Sets the audio volume in percents. Write **float**. |
| virtual void [set_Width](../ishape/set_width/)(**float**) | Sets the width of the shape, measured in points. Write **float**. |
| virtual void [set_X](../ishape/set_x/)(**float**) | Sets the x-coordinate of the shape's upper-left corner, measured in points. Write **float**. |
| virtual void [set_Y](../ishape/set_y/)(**float**) | Sets the y-coordinate of the shape's upper-left corner, measured in points. Write **float**. |
| virtual void [SetGeometryPath](../igeometryshape/setgeometrypath/)([System::SharedPtr](../../system/sharedptr/)\<[IGeometryPath](../igeometrypath/)\>) | Updates shape geometry from [IGeometryPath](../igeometrypath/) object. Coordinates must be relative to the left top corner of the shape. Changes the type of the shape ([ShapeType](../shapetype/)) to [ShapeType::Custom](../shapetype/). |
| virtual void [SetGeometryPaths](../igeometryshape/setgeometrypaths/)([System::ArrayPtr](../../system/arrayptr/)\<[System::SharedPtr](../../system/sharedptr/)\<[IGeometryPath](../igeometrypath/)\>\>) | Updates shape geometry from array of [IGeometryPath](../igeometrypath/). Coordinates must be relative to the left top corner of the shape. Changes the type of the shape ([ShapeType](../shapetype/)) to [ShapeType::Custom](../shapetype/). |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Set n'th template argument a weak pointer (rather than shared). Allows switching pointers in containers to weak mode. |
| int [SharedCount](../../system/object/sharedcount/)() const | Gets current value of shared reference counter. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Increments shared reference count. Shouldn't be called directly; instead, use smart pointers or ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Decrements and returns shared reference count. Shouldn't be called directly; instead, use smart pointers or ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analog of C# [Object.ToString()](../../system/object/tostring/) method. Enables converting custom objects to string. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implements C# typeof([System.Object](../../system/object/)) construct. |
| void [Unlock](../../system/object/unlock/)() | Implements C# lock() statement unlocking. Call directly or use [LockContext](../../system/lockcontext/) sentry object. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Increments weak reference count. Shouldn't be called directly; instead, use smart pointers or ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Decrements weak reference count. Shouldn't be called directly; instead, use smart pointers or ThisProtector. |
| virtual void [WriteAsSvg](../ishape/writeassvg/)([System::SharedPtr](../../system/sharedptr/)\<[System::IO::Stream](../../system.io/stream/)\>) | Saves content of [Shape](../shape/) as SVG file. |
| virtual void [WriteAsSvg](../ishape/writeassvg/)([System::SharedPtr](../../system/sharedptr/)\<[System::IO::Stream](../../system.io/stream/)\>, [System::SharedPtr](../../system/sharedptr/)\<[Export::ISVGOptions](../../aspose.slides.export/isvgoptions/)\>) | Saves content of [Shape](../shape/) as SVG file. |
| virtual  [~Object](../../system/object/~object/)() | Destroys object. Frees all internal data structures. |
## See Also

* Class [IPictureFrame](../ipictureframe/)
* Namespace [Aspose::Slides](../)
* Library [Aspose.Slides](../../)