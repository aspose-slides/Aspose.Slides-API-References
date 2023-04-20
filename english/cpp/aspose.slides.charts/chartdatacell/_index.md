---
title: ChartDataCell
second_title: Aspose.Slides for C++ API Reference
description: Represents cell for chart data.
type: docs
weight: 131
url: /cpp/aspose.slides.charts/chartdatacell/
---
## ChartDataCell class


Represents cell for chart data.

```cpp
class ChartDataCell : public Aspose::Slides::Charts::IChartDataCell
```

## Methods

| Method | Description |
| --- | --- |
| void [Calculate](./calculate/)(**bool**) override | If the cell contains a formula, the value will be updated base on that formula. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Compares objects using C# [Object.Equals](../../system/object/equals/) semantics. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Compares reference type objects in C# style. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Compares value type objects in C# style. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emulates C#-style floating point comparison where two NaNs are considered equal even though according to IEC 60559:1989 NaN is not equal to any value, including NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emulates C#-style floating point comparison where two NaNs are considered equal even though according to IEC 60559:1989 NaN is not equal to any value, including NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | For internal purposes only. |
| [System::SharedPtr](../../system/sharedptr/)\<[IChartDataWorksheet](../ichartdataworksheet/)\> [get_ChartDataWorksheet](./get_chartdataworksheet/)() override | Gets the worksheet. Read-only [IChartDataWorksheet](../ichartdataworksheet/). |
| **int32_t** [get_Column](./get_column/)() override | Returns the index of the column of worksheet in which the cell is located. Read-only **int32_t**. |
| [System::String](../../system/string/) [get_CustomNumberFormat](./get_customnumberformat/)() override | Gets the custom display format of numbers and dates. If value is empty will be used PresetNumberFormat value. Read [System::String](../../system/string/). |
| [System::String](../../system/string/) [get_Formula](./get_formula/)() override | Gets the formula in A1-style. |
| **bool** [get_IsHidden](./get_ishidden/)() override | Determines whether the cell is hidden. Read-only **bool**. |
| **uint8_t** [get_PresetNumberFormat](./get_presetnumberformat/)() override | Gets the built-in display format of numbers and dates. Preset number must be in [0..22] or [37..49]. Read **uint8_t**. |
| [System::String](../../system/string/) [get_R1C1Formula](./get_r1c1formula/)() override | Gets the formula in R1C1-style. |
| **int32_t** [get_Row](./get_row/)() override | Returns the index of the row of worksheet in which the cell is located. Read-only **int32_t**. |
| [System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\> [get_Value](./get_value/)() override | Gets the value of a cell. Read [System::Object](../../system/object/). |
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
| void [set_CustomNumberFormat](./set_customnumberformat/)([System::String](../../system/string/)) override | Sets the custom display format of numbers and dates. If value is empty will be used PresetNumberFormat value. Write [System::String](../../system/string/). |
| void [set_Formula](./set_formula/)([System::String](../../system/string/)) override | Sets the formula in A1-style. |
| void [set_PresetNumberFormat](./set_presetnumberformat/)(**uint8_t**) override | Sets the built-in display format of numbers and dates. Preset number must be in [0..22] or [37..49]. Write **uint8_t**. |
| void [set_R1C1Formula](./set_r1c1formula/)([System::String](../../system/string/)) override | Sets the formula in R1C1-style. |
| void [set_Value](./set_value/)([System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\>) override | Sets the value of a cell. Write [System::Object](../../system/object/). |
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

* Class [IChartDataCell](../ichartdatacell/)
* Namespace [Aspose::Slides::Charts](../)
* Library [Aspose.Slides](../../)