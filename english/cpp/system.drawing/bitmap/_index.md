---
title: Bitmap
second_title: Aspose.Slides for C++ API Reference
description: "Represents a GDI+ bitmap image. Objects of this class should only be allocated using System::MakeObject() function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into System::SmartPtr pointer and use this pointer to pass it to functions as argument."
type: docs
weight: 1
url: /cpp/system.drawing/bitmap/
---
## Bitmap class


Represents a GDI+ bitmap image. Objects of this class should only be allocated using [System::MakeObject()](../../system/makeobject/) function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into [System::SmartPtr](../../system/smartptr/) pointer and use this pointer to pass it to functions as argument.

```cpp
class Bitmap : public System::Drawing::Image
```

## Methods

| Method | Description |
| --- | --- |
| **bool** [BeginPixelProcessing](./beginpixelprocessing/)(**bool**) | Enables pixel processing mode. |
|  [Bitmap](./bitmap/)(const [SharedPtr](../../system/sharedptr/)\<[Image](../image/)\>\&) | Constructs a new [Bitmap](./) object from the specified existing image. |
|  [Bitmap](./bitmap/)(const [SharedPtr](../../system/sharedptr/)\<[System::IO::Stream](../../system.io/stream/)\>\&, **bool**) | Constructs a new [Bitmap](./) object from the specified stream. |
|  [Bitmap](./bitmap/)(const [String](../../system/string/)\&) | Constructs a new [Bitmap](./) object from the specified file. |
|  [Bitmap](./bitmap/)(const [String](../../system/string/)\&, **bool**) | Constructs a new [Bitmap](./) object from the specified file. |
|  [Bitmap](./bitmap/)(int, int, [Imaging::PixelFormat](../../system.drawing.imaging/pixelformat/)) | Constructs a new [Bitmap](./) object that represents a bitmap image with the specified width, height, pixel format and pixel data. |
|  [Bitmap](./bitmap/)(const [SharedPtr](../../system/sharedptr/)\<[Image](../image/)\>\&, const [Size](../size/)\&) | Constructs a new [Bitmap](./) object from the specified existing image, scaled to the specified size. |
|  [Bitmap](./bitmap/)(const [SharedPtr](../../system/sharedptr/)\<[Image](../image/)\>\&, int, int) | Constructs a new [Bitmap](./) object from the specified existing image with width and height scaled to the specified values. |
| [SharedPtr](../../system/sharedptr/)\<[Image](../image/)\> [Clone](./clone/)() override | Creates a copy of the current object. |
| [SharedPtr](../../system/sharedptr/)\<[Bitmap](./)\> [Clone](./clone/)([Rectangle](../rectangle/), [Imaging::PixelFormat](../../system.drawing.imaging/pixelformat/)) | Creates a [Bitmap](./) object that represents a copy of a region of the bitmap image represented by the current object. |
| [SharedPtr](../../system/sharedptr/)\<[Bitmap](./)\> [Clone](./clone/)([RectangleF](../rectanglef/), [Imaging::PixelFormat](../../system.drawing.imaging/pixelformat/)) | Creates a [Bitmap](./) object that represents a copy of a region of the bitmap image represented by the current object. |
| [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\> [ComputeHash](./computehash/)() | Computes the SHA1 hash value. |
| static [SharedPtr](../../system/sharedptr/)\<[Bitmap](./)\> [ConvertToARGBImage](./converttoargbimage/)(const [SharedPtr](../../system/sharedptr/)\<[Bitmap](./)\>\&) | Creates a copy of the specified bitmap image with pixel format changed to Format32bppArgb. |
| void [Dispose](../image/dispose/)() override | Releases all resources aquired by the current object. |
| **bool** [EndPixelProcessing](./endpixelprocessing/)(**bool**) | Disables pixel processing mode. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Compares objects using C# [Object.Equals](../../system/object/equals/) semantics. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Compares reference type objects in C# style. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Compares value type objects in C# style. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emulates C#-style floating point comparison where two NaNs are considered equal even though according to IEC 60559:1989 NaN is not equal to any value, including NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emulates C#-style floating point comparison where two NaNs are considered equal even though according to IEC 60559:1989 NaN is not equal to any value, including NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | For internal purposes only. |
| static [SharedPtr](../../system/sharedptr/)\<[Image](../image/)\> [FromFile](../image/fromfile/)(const [String](../../system/string/)\&, **bool**) | Creates an [Image](../image/) object from the specified file. |
| static [SharedPtr](../../system/sharedptr/)\<[Bitmap](./)\> [FromHbitmap](../image/fromhbitmap/)(IntPtr) | Constructs a [Bitmap](./) object from the specified GDI bitmap. |
| static [SharedPtr](../../system/sharedptr/)\<[Image](../image/)\> [FromStream](../image/fromstream/)(const [SharedPtr](../../system/sharedptr/)\<[System::IO::Stream](../../system.io/stream/)\>\&, **bool**, **bool**) | Creates an [Image](../image/) object from the specified stream. |
| virtual **int32_t** [get_Flags](../image/get_flags/)() const | Returns a bit-wise combination of ImageFlags enum values that represents the attributes of the image. |
| [ArrayPtr](../../system/arrayptr/)\<[Guid](../../system/guid/)\> [get_FrameDimensionsList](../image/get_framedimensionslist/)() const | Returns an array of GUIDs that represent the dimensions of frames within the image represented by the current object. |
| int [get_Height](./get_height/)() const override | Returns the height of the image in pixels. |
| **float** [get_HorizontalResolution](../image/get_horizontalresolution/)() const | Returns the horizontal resolution of the image represented by the current object in pixels per inch. |
| [Imaging::ColorPalettePtr](../../system.drawing.imaging/colorpaletteptr/) [get_Palette](./get_palette/)() const override | Returns the color palette used by the image represented by the current object. |
| [Imaging::PixelFormat](../../system.drawing.imaging/pixelformat/) [get_PixelFormat](./get_pixelformat/)() const override | Returns the pixel format of the image represented by the current object. |
| virtual [ArrayPtr](../../system/arrayptr/)\<int\> [get_PropertyIdList](../image/get_propertyidlist/)() const | Gets IDs of the property items stored in this image. |
| virtual [ArrayPtr](../../system/arrayptr/)\<[SharedPtr](../../system/sharedptr/)\<[Imaging::PropertyItem](../../system.drawing.imaging/propertyitem/)\>\> [get_PropertyItems](../image/get_propertyitems/)() const | Gets all the property items(pieces of metadata) stored in this image. |
| [Imaging::ImageFormatPtr](../../system.drawing.imaging/imageformatptr/) [get_RawFormat](./get_rawformat/)() const override | Returns the file format of the image represented by the current object. |
| [Size](../size/) [get_Size](../image/get_size/)() const | Returns a [Size](../size/) object that represents the width and height of the image in pixels. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\> [get_Tag](../image/get_tag/)() const | Gets an object that provides additional data about the image. |
| **float** [get_VerticalResolution](../image/get_verticalresolution/)() const | Returns the vertical resolution of the image represented by the current object in pixels per inch. |
| int [get_Width](./get_width/)() const override | Returns the width of the image in pixels. |
| [RectangleF](../rectanglef/) [GetBounds](../image/getbounds/)([GraphicsUnit](../graphicsunit/)\&) | Returns the image bounds in the specified measurement units. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Gets reference counter data structure associated with the object. |
| int [GetFrameCount](../image/getframecount/)(const [Imaging::FrameDimensionPtr](../../system.drawing.imaging/framedimensionptr/)\&) | Returns the number of frames of the specified frame dimension. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analog of C# [Object.GetHashCode()](../../system/object/gethashcode/) method. Enables hashing of custom objects. |
| IntPtr [GetHbitmap](./gethbitmap/)() | Creates a GDI bitmap object from the bitmap represented by the current object. |
| [Color](../color/) [GetPixel](./getpixel/)(int, int) | Returns the color of the specified pixel. |
| static int [GetPixelFormatSize](../image/getpixelformatsize/)([Imaging::PixelFormat](../../system.drawing.imaging/pixelformat/)) | Returns the number of bits used to represent the color depth in the specified pixel format. |
| const SkBitmap * [GetSkBitmap](./getskbitmap/)() const override | Returns a raw pointer to the underlying SkBitmap object. |
| [SharedPtr](../../system/sharedptr/)\<[Image](../image/)\> [GetThumbnailImage](../image/getthumbnailimage/)(int, int, [Image::GetThumbnailImageAbort](../image/getthumbnailimageabort/), IntPtr) | Gets a thumbnail for this [System::Drawing::Image](../image/) object. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Gets actual type of object. Analog of C# [System.Object.GetType()](../../system/object/gettype/) call. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Check if object represents an instance of type described by targetType. Analog of C# 'is' operator. |
| static **bool** [IsAlphaPixelFormat](../image/isalphapixelformat/)([Imaging::PixelFormat](../../system.drawing.imaging/pixelformat/)) | Determines if the specified pixel format contains alpha information. |
| **bool** [IsMultiImage](./ismultiimage/)() const override | Returns whether the original format is a multi-image. |
| void [Lock](../../system/object/lock/)() | Implements C# lock() statement locking. Call directly or use [LockContext](../../system/lockcontext/) sentry object. |
| [Imaging::BitmapDataPtr](../../system.drawing.imaging/bitmapdataptr/) [LockBits](./lockbits/)(const [Rectangle](../rectangle/)\&, [Imaging::ImageLockMode](../../system.drawing.imaging/imagelockmode/), [Imaging::PixelFormat](../../system.drawing.imaging/pixelformat/)) | Locks a [Bitmap](./) into system memory. |
| [Imaging::BitmapDataPtr](../../system.drawing.imaging/bitmapdataptr/) [LockBits](./lockbits/)(const [Rectangle](../rectangle/)\&, [Imaging::ImageLockMode](../../system.drawing.imaging/imagelockmode/), [Imaging::PixelFormat](../../system.drawing.imaging/pixelformat/), const [Imaging::BitmapDataPtr](../../system.drawing.imaging/bitmapdataptr/)\&) | Locks a [Bitmap](./) into system memory. |
| void [MakeTransparent](./maketransparent/)([Color](../color/)) | Changes the color of all pixels with the specified color to transparent. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analog of C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) method. Enables cloning custom types. |
|  [Object](../../system/object/object/)() | Creates object. Initializes all internal data structures. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Copy constructor. Doesn't copy anything, really, just initializes new object and enables copy constructing subclasses. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Assignment operator. Doesn't copy anything, really, just initializes new object and enables copy constructing subclasses. |
| void [PremultipleColors](./premultiplecolors/)() | Premultiplies the colors of the pixels of the image represented by the current object. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Compares objects by reference. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Compares objects by reference. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Reference-compares value type object with nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Specialization of [Object::ReferenceEquals](../../system/object/referenceequals/) for case of string and nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Specialization of [Object::ReferenceEquals](../../system/object/referenceequals/) for case of strings. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Decreases shared reference count by specified value. |
| void [RotateFlip](./rotateflip/)([RotateFlipType](../rotatefliptype/)) override | Rotates image to multiple of 90 degrees and flips. |
| void [Save](../image/save/)(const [String](../../system/string/)\&) | Saves the image represented by the current object to the specified file in PNG format. |
| void [Save](../image/save/)(const [String](../../system/string/)\&, const [Imaging::ImageFormatPtr](../../system.drawing.imaging/imageformatptr/)\&) | Saves the image represented by the current object to the specified file in the specified format. |
| void [Save](../image/save/)(const [SharedPtr](../../system/sharedptr/)\<[System::IO::Stream](../../system.io/stream/)\>\&, const [Imaging::ImageFormatPtr](../../system.drawing.imaging/imageformatptr/)\&) | Saves the image represented by the current object to the specified stream in the specified format. |
| void [Save](../image/save/)(const [String](../../system/string/)\&, const [Imaging::ImageCodecInfoPtr](../../system.drawing.imaging/imagecodecinfoptr/)\&, const [Imaging::EncoderParametersPtr](../../system.drawing.imaging/encoderparametersptr/)\&) | Saves the image represented by the current object to the specified file using the specified encoder and encoder parameters. |
| void [Save](../image/save/)(const [SharedPtr](../../system/sharedptr/)\<[System::IO::Stream](../../system.io/stream/)\>\&, const [Imaging::ImageCodecInfoPtr](../../system.drawing.imaging/imagecodecinfoptr/)\&, const [Imaging::EncoderParametersPtr](../../system.drawing.imaging/encoderparametersptr/)\&) | Saves the image represented by the current object to the specified stream using the specified encoder and encoder parameters. |
| void [SaveAdd](../image/saveadd/)(const [Imaging::EncoderParametersPtr](../../system.drawing.imaging/encoderparametersptr/)\&) | Adds a frame to the file or stream specified in a previous call to the [Save()](../image/save/) method. |
| void [SaveAdd](../image/saveadd/)(const [SharedPtr](../../system/sharedptr/)\<[Image](../image/)\>\&, const [Imaging::EncoderParametersPtr](../../system.drawing.imaging/encoderparametersptr/)\&) | Adds a frame to the file or stream specified in a previous call to the [Save()](../image/save/) method. |
| int [SelectActiveFrame](../image/selectactiveframe/)(const [Imaging::FrameDimensionPtr](../../system.drawing.imaging/framedimensionptr/)\&, int) | Selects the specified frame. |
| void [set_Palette](./set_palette/)([Imaging::ColorPalettePtr](../../system.drawing.imaging/colorpaletteptr/)) override | Sets the color palette used by the image represented by the current object. |
| virtual void [set_Tag](../image/set_tag/)(const [System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\>) | Sets an object that provides additional data about the image. |
| void [SetPixel](./setpixel/)(int, int, [Color](../color/)) | Sets the color of the specified pixel in the bitmap image represented by the current object. |
| void [SetResolution](./setresolution/)(**float**, **float**) | Sets the resolution of the image. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Set n'th template argument a weak pointer (rather than shared). Allows switching pointers in containers to weak mode. |
| int [SharedCount](../../system/object/sharedcount/)() const | Gets current value of shared reference counter. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Increments shared reference count. Shouldn't be called directly; instead, use smart pointers or ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Decrements and returns shared reference count. Shouldn't be called directly; instead, use smart pointers or ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analog of C# [Object.ToString()](../../system/object/tostring/) method. Enables converting custom objects to string. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implements C# typeof([System.Object](../../system/object/)) construct. |
| void [Unlock](../../system/object/unlock/)() | Implements C# lock() statement unlocking. Call directly or use [LockContext](../../system/lockcontext/) sentry object. |
| void [UnlockBits](./unlockbits/)(const [Imaging::BitmapDataPtr](../../system.drawing.imaging/bitmapdataptr/)\&) | Unlocks the specified bitmap from system memory. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Increments weak reference count. Shouldn't be called directly; instead, use smart pointers or ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Decrements weak reference count. Shouldn't be called directly; instead, use smart pointers or ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | Destroys object. Frees all internal data structures. |
## See Also

* Class [Image](../image/)
* Namespace [System::Drawing](../)
* Library [Aspose.Slides](../../)