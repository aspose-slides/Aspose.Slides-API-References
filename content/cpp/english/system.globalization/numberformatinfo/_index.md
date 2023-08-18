---
title: NumberFormatInfo
second_title: Aspose.Slides for C++ API Reference
description: "Holds information on how to format numbers. Setter operations are only enabled on non-read-only objects. Objects of this class should only be allocated using System::MakeObject() function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into System::SmartPtr pointer and use this pointer to pass it to functions as argument."
type: docs
weight: 248
url: /system.globalization/numberformatinfo/
---
## NumberFormatInfo class


Holds information on how to format numbers. Setter operations are only enabled on non-read-only objects. Objects of this class should only be allocated using [System::MakeObject()](../../system/makeobject/) function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into [System::SmartPtr](../../system/smartptr/) pointer and use this pointer to pass it to functions as argument.

```cpp
class NumberFormatInfo : public virtual System::Object,
                         public System::IFormatProvider,
                         public System::ICloneable
```

## Methods

| Method | Description |
| --- | --- |
| [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [Clone](./clone/)() override | Clones format info. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Compares objects using C# [Object.Equals](../../system/object/equals/) semantics. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Compares reference type objects in C# style. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Compares value type objects in C# style. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emulates C#-style floating point comparison where two NaNs are considered equal even though according to IEC 60559:1989 NaN is not equal to any value, including NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emulates C#-style floating point comparison where two NaNs are considered equal even though according to IEC 60559:1989 NaN is not equal to any value, including NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | For internal purposes only. |
| int [get_CurrencyDecimalDigits](./get_currencydecimaldigits/)() const | Gets number of currency decimal digits. |
| [String](../../system/string/) [get_CurrencyDecimalSeparator](./get_currencydecimalseparator/)() const | Gets currency decimal separator. |
| [String](../../system/string/) [get_CurrencyGroupSeparator](./get_currencygroupseparator/)() const | Gets currency group separator. |
| [ArrayPtr](../../system/arrayptr/)\<int\> [get_CurrencyGroupSizes](./get_currencygroupsizes/)() const | Gets number of currency decimal digits per group. |
| int [get_CurrencyNegativePattern](./get_currencynegativepattern/)() const | Gets currency negative pattern. |
| int [get_CurrencyPositivePattern](./get_currencypositivepattern/)() const | Gets currency positive pattern. |
| [String](../../system/string/) [get_CurrencySymbol](./get_currencysymbol/)() const | Gets currency symbol. |
| static [NumberFormatInfoPtr](../numberformatinfoptr/) [get_CurrentInfo](./get_currentinfo/)() | Gets current thread culture-defined number format info. |
| [DigitShapes](../digitshapes/) [get_DigitSubstitution](./get_digitsubstitution/)() const | Gets a value that specifies how to display shape of a digit. |
| static const [NumberFormatInfoPtr](../numberformatinfoptr/)\& [get_InvariantInfo](./get_invariantinfo/)() | Gets invariant culture-defined number format info. |
| **bool** [get_IsReadOnly](./get_isreadonly/)() const | Checks if format is read-only. |
| [String](../../system/string/) [get_NaNSymbol](./get_nansymbol/)() const | Gets Not-a-Number symbol. |
| [ArrayPtr](../../system/arrayptr/)\<[String](../../system/string/)\> [get_NativeDigits](./get_nativedigits/)() const | Gets digits symbols (0 through 9). |
| [String](../../system/string/) [get_NegativeInfinitySymbol](./get_negativeinfinitysymbol/)() const | Gets negative infinity symbol. |
| [String](../../system/string/) [get_NegativeSign](./get_negativesign/)() const | Gets negative sign. |
| int [get_NumberDecimalDigits](./get_numberdecimaldigits/)() const | Gets number of decimal digits. |
| [String](../../system/string/) [get_NumberDecimalSeparator](./get_numberdecimalseparator/)() const | Gets decimal separator. |
| [String](../../system/string/) [get_NumberGroupSeparator](./get_numbergroupseparator/)() const | Gets number group separator. |
| [ArrayPtr](../../system/arrayptr/)\<int\> [get_NumberGroupSizes](./get_numbergroupsizes/)() const | Gets numbers of digits per group. |
| int [get_NumberNegativePattern](./get_numbernegativepattern/)() const | Gets number negative pattern. |
| int [get_PercentDecimalDigits](./get_percentdecimaldigits/)() const | Gets number of decimal places in percent values. |
| [String](../../system/string/) [get_PercentDecimalSeparator](./get_percentdecimalseparator/)() const | Gets decimal separator in percent values. |
| [String](../../system/string/) [get_PercentGroupSeparator](./get_percentgroupseparator/)() const | Gets group separator in percent values. |
| [ArrayPtr](../../system/arrayptr/)\<int\> [get_PercentGroupSizes](./get_percentgroupsizes/)() const | Gets numbers of digits per percent value group. |
| int [get_PercentNegativePattern](./get_percentnegativepattern/)() const | Gets percent negative pattern. |
| int [get_PercentPositivePattern](./get_percentpositivepattern/)() const | Gets percent positive pattern. |
| [String](../../system/string/) [get_PercentSymbol](./get_percentsymbol/)() const | Gets percent symbol. |
| [String](../../system/string/) [get_PerMilleSymbol](./get_permillesymbol/)() const | Gets permille symbol. |
| [String](../../system/string/) [get_PositiveInfinitySymbol](./get_positiveinfinitysymbol/)() const | Gets positive infinity symbol. |
| [String](../../system/string/) [get_PositiveSign](./get_positivesign/)() const | Gets positive sign. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Gets reference counter data structure associated with the object. |
| [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [GetFormat](./getformat/)(const [TypeInfo](../../system/typeinfo/)\&) override | Gets formatter of specific type. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analog of C# [Object.GetHashCode()](../../system/object/gethashcode/) method. Enables hashing of custom objects. |
| static [NumberFormatInfoPtr](../numberformatinfoptr/) [GetInstance](./getinstance/)(const [IFormatProviderPtr](../../system/iformatproviderptr/)\&) | Gets formatter associated with format provider. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Gets actual type of object. Analog of C# [System.Object.GetType()](../../system/object/gettype/) call. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Check if object represents an instance of type described by targetType. Analog of C# 'is' operator. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analog of C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) method. Enables cloning custom types. |
|  [NumberFormatInfo](./numberformatinfo/)() | Default constructor (invariant [NumberFormatInfo](./)). |
|  [Object](../../system/object/object/)() | Creates object. Initializes all internal data structures. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Copy constructor. Doesn't copy anything, really, just initializes new object and enables copy constructing subclasses. |
| [NumberFormatInfo](./)\& [operator=](./operator_equal/)(const [NumberFormatInfo](./)\&) |  |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Assignment operator. Doesn't copy anything, really, just initializes new object and enables copy constructing subclasses. |
| static [NumberFormatInfoPtr](../numberformatinfoptr/) [ReadOnly](./readonly/)([NumberFormatInfoPtr](../numberformatinfoptr/)) | Gets read-only version of formatter. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Compares objects by reference. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Compares objects by reference. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Reference-compares value type object with nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Specialization of [Object::ReferenceEquals](../../system/object/referenceequals/) for case of string and nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Specialization of [Object::ReferenceEquals](../../system/object/referenceequals/) for case of strings. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Decreases shared reference count by specified value. |
| void [set_CurrencyDecimalDigits](./set_currencydecimaldigits/)(int) | Sets number of currency decimal digits. |
| void [set_CurrencyDecimalSeparator](./set_currencydecimalseparator/)(const [String](../../system/string/)\&) | Sets currency decimal separator. |
| void [set_CurrencyGroupSeparator](./set_currencygroupseparator/)(const [String](../../system/string/)\&) | Sets currency group separator. |
| void [set_CurrencyGroupSizes](./set_currencygroupsizes/)(const [ArrayPtr](../../system/arrayptr/)\<int\>\&) | Sets number of currency decimal digits per group. |
| void [set_CurrencyNegativePattern](./set_currencynegativepattern/)(int) | Sets currency negative pattern. |
| void [set_CurrencyPositivePattern](./set_currencypositivepattern/)(int) | Sets currency positive pattern. |
| void [set_CurrencySymbol](./set_currencysymbol/)(const [String](../../system/string/)\&) | Sets currency symbol. |
| void [set_DigitSubstitution](./set_digitsubstitution/)([DigitShapes](../digitshapes/)) | Sets a value that specifies how to display shape of a digit. |
| void [set_NaNSymbol](./set_nansymbol/)(const [String](../../system/string/)\&) | Sets Not-a-Number symbol. |
| void [set_NativeDigits](./set_nativedigits/)(const [ArrayPtr](../../system/arrayptr/)\<[String](../../system/string/)\>\&) | Sets digits symbols (0 through 9). |
| void [set_NegativeInfinitySymbol](./set_negativeinfinitysymbol/)(const [String](../../system/string/)\&) | Sets negative infinity symbol. |
| void [set_NegativeSign](./set_negativesign/)(const [String](../../system/string/)\&) | Sets negative sign. |
| void [set_NumberDecimalDigits](./set_numberdecimaldigits/)(int) | Sets number of decimal digits. |
| void [set_NumberDecimalSeparator](./set_numberdecimalseparator/)(const [String](../../system/string/)\&) | Sets decimal separator. |
| void [set_NumberGroupSeparator](./set_numbergroupseparator/)(const [String](../../system/string/)\&) | Sets number group separator. |
| void [set_NumberGroupSizes](./set_numbergroupsizes/)(const [ArrayPtr](../../system/arrayptr/)\<int\>\&) | Sets numbers of digits per group. |
| void [set_NumberNegativePattern](./set_numbernegativepattern/)(int) | Sets number negative pattern. |
| void [set_PercentDecimalDigits](./set_percentdecimaldigits/)(int) | Sets number of decimal places in percent values. |
| void [set_PercentDecimalSeparator](./set_percentdecimalseparator/)(const [String](../../system/string/)\&) | Sets decimal separator in percent values. |
| void [set_PercentGroupSeparator](./set_percentgroupseparator/)(const [String](../../system/string/)\&) | Sets group separator in percent values. |
| void [set_PercentGroupSizes](./set_percentgroupsizes/)(const [ArrayPtr](../../system/arrayptr/)\<int\>\&) | Sets numbers of digits per percent value group. |
| void [set_PercentNegativePattern](./set_percentnegativepattern/)(int) | Sets percent negative pattern. |
| void [set_PercentPositivePattern](./set_percentpositivepattern/)(int) | Sets percent positive pattern. |
| void [set_PercentSymbol](./set_percentsymbol/)(const [String](../../system/string/)\&) | Sets percent symbol. |
| void [set_PerMilleSymbol](./set_permillesymbol/)(const [String](../../system/string/)\&) | Sets permille symbol. |
| void [set_PositiveInfinitySymbol](./set_positiveinfinitysymbol/)(const [String](../../system/string/)\&) | Sets positive infinity symbol. |
| void [set_PositiveSign](./set_positivesign/)(const [String](../../system/string/)\&) | Sets positive sign. |
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
* Class [IFormatProvider](../../system/iformatprovider/)
* Class [ICloneable](../../system/icloneable/)
* Namespace [System::Globalization](../)
* Library [Aspose.Slides](../../)