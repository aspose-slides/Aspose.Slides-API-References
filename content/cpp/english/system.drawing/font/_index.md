---
title: Font
second_title: Aspose.Slides for C++ API Reference
description: "Represents a particular format for text, including font face, size, and style. Objects of this class should only be allocated using System::MakeObject() function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into System::SmartPtr pointer and use this pointer to pass it to functions as argument."
type: docs
weight: 79
url: /system.drawing/font/
---
## Font class


Represents a particular format for text, including font face, size, and style. Objects of this class should only be allocated using [System::MakeObject()](../../system/makeobject/) function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into [System::SmartPtr](../../system/smartptr/) pointer and use this pointer to pass it to functions as argument.

```cpp
class Font : public System::Object
```

## Methods

| Method | Description |
| --- | --- |
| [SharedPtr](../../system/sharedptr/)\<[Font](./)\> [Clone](./clone/)() | Returns a copy of the current font. |
| void [Dispose](./dispose/)() | Releases all operating system resources acquired by the current object. |
| **bool** [Equals](./equals/)([System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\>) override | Determines if the current and the specified objects are identical. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Compares objects using C# [Object.Equals](../../system/object/equals/) semantics. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Compares reference type objects in C# style. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emulates C#-style floating point comparison where two NaNs are considered equal even though according to IEC 60559:1989 NaN is not equal to any value, including NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emulates C#-style floating point comparison where two NaNs are considered equal even though according to IEC 60559:1989 NaN is not equal to any value, including NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | For internal purposes only. |
|  [Font](./font/)(const [SharedPtr](../../system/sharedptr/)\<[Font](./)\>\&, [FontStyle](../fontstyle/)) | Constructs a new instance of [Font](./) class that represents the specified existing font with the specified font style. |
|  [Font](./font/)(const [SharedPtr](../../system/sharedptr/)\<[FontFamily](../fontfamily/)\>\&, **float**, [FontStyle](../fontstyle/), [GraphicsUnit](../graphicsunit/), **uint8_t**, **bool**) | Constructs a new instance of [Font](./) class. |
|  [Font](./font/)(const [SharedPtr](../../system/sharedptr/)\<[FontFamily](../fontfamily/)\>\&, **float**, [GraphicsUnit](../graphicsunit/)) | Constructs a new instance of [Font](./) class. |
|  [Font](./font/)(const [String](../../system/string/)\&, **float**, [FontStyle](../fontstyle/), [GraphicsUnit](../graphicsunit/), **uint8_t**, **bool**) | Constructs a new instance of [Font](./) class. |
|  [Font](./font/)(const [String](../../system/string/)\&, **float**, [GraphicsUnit](../graphicsunit/)) | Constructs a new instance of [Font](./) class. |
| static [SharedPtr](../../system/sharedptr/)\<[Font](./)\> [FromLogFont](./fromlogfont/)(const [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>\&) | NOT IMPLEMENTED. |
| **bool** [get_Bold](./get_bold/)() | Determines if the font represented by the current object has the bold style applied. |
| [SharedPtr](../../system/sharedptr/)\<[FontFamily](../fontfamily/)\> [get_FontFamily](./get_fontfamily/)() | Returns the font family of the font represented by the current object. |
| [FontStyle](../fontstyle/) [get_FontStyle](./get_fontstyle/)() | Returns the font style of the font represneted by the current object. |
| **uint8_t** [get_GdiCharSet](./get_gdicharset/)() | Returns a value that indicates the GDI character set used by the font represented by the current object. |
| int [get_Height](./get_height/)() | Returns the line spacing of the font represented by the current object in pixels. |
| **bool** [get_Italic](./get_italic/)() | Determines if the font represented by the current object has the italic style applied. |
| [String](../../system/string/) [get_Name](./get_name/)() | Returns the face name of the font represented by the current object. |
| [String](../../system/string/) [get_OriginalFontName](./get_originalfontname/)() | Returns the originally specified name of the font. |
| **float** [get_Size](./get_size/)() | Returns the em size of the font represented by the current object measured in the units specified by the Unit property. |
| **float** [get_SizeInPoints](./get_sizeinpoints/)() | Returns the em size of the font represented by the current object in points. |
| **bool** [get_Strikeout](./get_strikeout/)() | Determines if the font represented by the current object has the strikeout style applied. |
| [FontStyle](../fontstyle/) [get_Style](./get_style/)() | Returns the font style of the font represented by the current object. |
| **bool** [get_Underline](./get_underline/)() | Determines if the font represented by the current object has the underline style applied. |
| [GraphicsUnit](../graphicsunit/) [get_Unit](./get_unit/)() | Returns the measurement unit for the font represented by the current object. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Gets reference counter data structure associated with the object. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analog of C# [Object.GetHashCode()](../../system/object/gethashcode/) method. Enables hashing of custom objects. |
| **float** [GetHeight](./getheight/)(const [SharedPtr](../../system/sharedptr/)\<[Graphics](../graphics/)\>\&) | Returns the line spacing of the font represented by the current object, in the current unit of a specified [Graphics](../graphics/) object. |
| **float** [GetHeight](./getheight/)(**float**) | Returns the height of the font represented by the current object when drawn to a display device with the specified vertical resolution. |
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

* Class [Object](../../system/object/)
* Namespace [System::Drawing](../)
* Library [Aspose.Slides](../../)