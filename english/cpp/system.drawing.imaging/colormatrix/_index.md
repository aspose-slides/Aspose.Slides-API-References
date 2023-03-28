---
title: ColorMatrix
second_title: Aspose.Slides for C++ API Reference
description: "Represents a 5x5 matrix that contains the coordinates for the RGBAW color space. Objects of this class should only be allocated using System::MakeObject() function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into System::SmartPtr pointer and use this pointer to pass it to functions as argument."
type: docs
weight: 27
url: /cpp/system.drawing.imaging/colormatrix/
---
## ColorMatrix class


Represents a 5x5 matrix that contains the coordinates for the RGBAW color space. Objects of this class should only be allocated using [System::MakeObject()](../../system/makeobject/) function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into [System::SmartPtr](../../system/smartptr/) pointer and use this pointer to pass it to functions as argument.

```cpp
class ColorMatrix : public System::Object
```

## Methods

| Method | Description |
| --- | --- |
|  [ColorMatrix](./colormatrix/)() | Constructs a new instance of [ColorMatrix](./) class and initializes it with the values of identity matrix. |
|  [ColorMatrix](./colormatrix/)(const [System::ArrayPtr](../../system/arrayptr/)\<[System::ArrayPtr](../../system/arrayptr/)\<**float**\>\>\&) | Constructs a new instance of [ColorMatrix](./) class and initializes it with the specified values. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Compares objects using C# [Object.Equals](../../system/object/equals/) semantics. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Compares reference type objects in C# style. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Compares value type objects in C# style. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emulates C#-style floating point comparison where two NaNs are considered equal even though according to IEC 60559:1989 NaN is not equal to any value, including NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emulates C#-style floating point comparison where two NaNs are considered equal even though according to IEC 60559:1989 NaN is not equal to any value, including NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | For internal purposes only. |
| **float** [get_Matrix00](./get_matrix00/)() const | Returns a value in 0-th row and 0-th column. |
| **float** [get_Matrix01](./get_matrix01/)() const | Returns a value in 0-th row and 1-st column. |
| **float** [get_Matrix02](./get_matrix02/)() const | Returns a value in 0-th row and 2-nd column. |
| **float** [get_Matrix03](./get_matrix03/)() const | Returns a value in 0-th row and 3-rd column. |
| **float** [get_Matrix04](./get_matrix04/)() const | Returns a value in 0-th row and 4-th column. |
| **float** [get_Matrix10](./get_matrix10/)() const | Returns a value in 1-st row and 0-th column. |
| **float** [get_Matrix11](./get_matrix11/)() const | Returns a value in 1-st row and 1-st column. |
| **float** [get_Matrix12](./get_matrix12/)() const | Returns a value in 1-st row and 2-nd column. |
| **float** [get_Matrix13](./get_matrix13/)() const | Returns a value in 1-st row and 3-rd column. |
| **float** [get_Matrix14](./get_matrix14/)() const | Returns a value in 1-st row and 4-th column. |
| **float** [get_Matrix20](./get_matrix20/)() const | Returns a value in 2-nd row and 0-th column. |
| **float** [get_Matrix21](./get_matrix21/)() const | Returns a value in 2-nd row and 1-st column. |
| **float** [get_Matrix22](./get_matrix22/)() const | Returns a value in 2-nd row and 2-nd column. |
| **float** [get_Matrix23](./get_matrix23/)() const | Returns a value in 2-nd row and 3-rd column. |
| **float** [get_Matrix24](./get_matrix24/)() const | Returns a value in 2-nd row and 4-th column. |
| **float** [get_Matrix30](./get_matrix30/)() const | Returns a value in 3-rd row and 0-th column. |
| **float** [get_Matrix31](./get_matrix31/)() const | Returns a value in 3-rd row and 1-st column. |
| **float** [get_Matrix32](./get_matrix32/)() const | Returns a value in 3-rd row and 2-nd column. |
| **float** [get_Matrix33](./get_matrix33/)() const | Returns a value in 3-rd row and 3-rd column. |
| **float** [get_Matrix34](./get_matrix34/)() const | Returns a value in 3-rd row and 4-th column. |
| **float** [get_Matrix40](./get_matrix40/)() const | Returns a value in 4-th row and 0-th column. |
| **float** [get_Matrix41](./get_matrix41/)() const | Returns a value in 4-th row and 1-st column. |
| **float** [get_Matrix42](./get_matrix42/)() const | Returns a value in 4-th row and 2-nd column. |
| **float** [get_Matrix43](./get_matrix43/)() const | Returns a value in 4-th row and 3-rd column. |
| **float** [get_Matrix44](./get_matrix44/)() const | Returns a value in 4-th row and 4-th column. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Gets reference counter data structure associated with the object. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analog of C# [Object.GetHashCode()](../../system/object/gethashcode/) method. Enables hashing of custom objects. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Gets actual type of object. Analog of C# [System.Object.GetType()](../../system/object/gettype/) call. |
| **float** [idx_get](./idx_get/)(int, int) | Returns a value at the specified row and column. |
| **float** [idx_set](./idx_set/)(int, int, **float**) | Sets the specifie value at the specified location in the matrix. |
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
| void [set_Matrix00](./set_matrix00/)(**float**) | Sets a value in the 0-th row and 0-th column. |
| void [set_Matrix01](./set_matrix01/)(**float**) | Sets a value in the 0-th row and 1-st column. |
| void [set_Matrix02](./set_matrix02/)(**float**) | Sets a value in the 0-th row and 2-nd column. |
| void [set_Matrix03](./set_matrix03/)(**float**) | Sets a value in the 0-th row and 3-rd column. |
| void [set_Matrix04](./set_matrix04/)(**float**) | Sets a value in the 0-th row and 4-th column. |
| void [set_Matrix10](./set_matrix10/)(**float**) | Sets a value in the 1-st row and 0-th column. |
| void [set_Matrix11](./set_matrix11/)(**float**) | Sets a value in the 1-st row and 1-st column. |
| void [set_Matrix12](./set_matrix12/)(**float**) | Sets a value in the 1-st row and 2-nd column. |
| void [set_Matrix13](./set_matrix13/)(**float**) | Sets a value in the 1-st row and 3-rd column. |
| void [set_Matrix14](./set_matrix14/)(**float**) | Sets a value in the 1-st row and 4-th column. |
| void [set_Matrix20](./set_matrix20/)(**float**) | Sets a value in the 2-nd row and 0-th column. |
| void [set_Matrix21](./set_matrix21/)(**float**) | Sets a value in the 2-nd row and 1-st column. |
| void [set_Matrix22](./set_matrix22/)(**float**) | Sets a value in the 2-nd row and 2-nd column. |
| void [set_Matrix23](./set_matrix23/)(**float**) | Sets a value in the 2-nd row and 3-rd column. |
| void [set_Matrix24](./set_matrix24/)(**float**) | Sets a value in the 2-nd row and 4-th column. |
| void [set_Matrix30](./set_matrix30/)(**float**) | Sets a value in the 3-rd row and 0-th column. |
| void [set_Matrix31](./set_matrix31/)(**float**) | Sets a value in the 3-rd row and 1-st column. |
| void [set_Matrix32](./set_matrix32/)(**float**) | Sets a value in the 3-rd row and 2-nd column. |
| void [set_Matrix33](./set_matrix33/)(**float**) | Sets a value in the 3-rd row and 3-rd column. |
| void [set_Matrix34](./set_matrix34/)(**float**) | Sets a value in the 3-rd row and 4-th column. |
| void [set_Matrix40](./set_matrix40/)(**float**) | Sets a value in the 4-th row and 0-th column. |
| void [set_Matrix41](./set_matrix41/)(**float**) | Sets a value in the 4-th row and 1-st column. |
| void [set_Matrix42](./set_matrix42/)(**float**) | Sets a value in the 4-th row and 2-nd column. |
| void [set_Matrix43](./set_matrix43/)(**float**) | Sets a value in the 4-th row and 3-rd column. |
| void [set_Matrix44](./set_matrix44/)(**float**) | Sets a value in the 4-th row and 4-th column. |
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
* Namespace [System::Drawing::Imaging](../)
* Library [Aspose.Slides](../../)
