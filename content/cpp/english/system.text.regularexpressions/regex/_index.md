---
title: Regex
second_title: Aspose.Slides for C++ API Reference
description: "Regular expression that follows C#-like syntax. Objects of this class should only be allocated using System::MakeObject() function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into System::SmartPtr pointer and use this pointer to pass it to functions as argument."
type: docs
weight: 92
url: /system.text.regularexpressions/regex/
---
## Regex class


Regular expression that follows C#-like syntax. Objects of this class should only be allocated using [System::MakeObject()](../../system/makeobject/) function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into [System::SmartPtr](../../system/smartptr/) pointer and use this pointer to pass it to functions as argument.

```cpp
class Regex : public System::Object
```

## Methods

| Method | Description |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Compares objects using C# [Object.Equals](../../system/object/equals/) semantics. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Compares reference type objects in C# style. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Compares value type objects in C# style. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emulates C#-style floating point comparison where two NaNs are considered equal even though according to IEC 60559:1989 NaN is not equal to any value, including NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emulates C#-style floating point comparison where two NaNs are considered equal even though according to IEC 60559:1989 NaN is not equal to any value, including NaN. |
| static [String](../../system/string/) [Escape](./escape/)(const [String](../../system/string/)\&) | Escapes special characters to use string as part of the pattern. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | For internal purposes only. |
| [TimeSpan](../../system/timespan/) [get_MatchTimeout](./get_matchtimeout/)() | Gets matching timeout. |
| [RegexOptions](../regexoptions/) [get_Options](./get_options/)() | Gets regex options. |
| **bool** [get_RightToLeft](./get_righttoleft/)() | Checks if matching is done in right-to-left mode. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Gets reference counter data structure associated with the object. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analog of C# [Object.GetHashCode()](../../system/object/gethashcode/) method. Enables hashing of custom objects. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Gets actual type of object. Analog of C# [System.Object.GetType()](../../system/object/gettype/) call. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Check if object represents an instance of type described by targetType. Analog of C# 'is' operator. |
| **bool** [IsMatch](./ismatch/)(const [String](../../system/string/)\&, int) | Matches regex against string. |
| static **bool** [IsMatch](./ismatch/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, [RegexOptions](../regexoptions/), [TimeSpan](../../system/timespan/), int) | Checks if string matches pattern. |
| void [Lock](../../system/object/lock/)() | Implements C# lock() statement locking. Call directly or use [LockContext](../../system/lockcontext/) sentry object. |
| [MatchPtr](../matchptr/) [Match](./match/)(const [String](../../system/string/)\&) | Matches regex against string. |
| [MatchPtr](../matchptr/) [Match](./match/)(const [String](../../system/string/)\&, int, int) | Matches regex against string. |
| static [MatchPtr](../matchptr/) [Match](./match/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, [RegexOptions](../regexoptions/), [TimeSpan](../../system/timespan/), int, int) | Matches string and pattern. |
| [MatchCollectionPtr](../matchcollectionptr/) [Matches](./matches/)(const [String](../../system/string/)\&, int) | Gets all matches of regex in given string by matching repeatedly. |
| static [MatchCollectionPtr](../matchcollectionptr/) [Matches](./matches/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, [RegexOptions](../regexoptions/), [TimeSpan](../../system/timespan/), int, int) | Gets all matches between string and pattern. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analog of C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) method. Enables cloning custom types. |
|  [Object](../../system/object/object/)() | Creates object. Initializes all internal data structures. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Copy constructor. Doesn't copy anything, really, just initializes new object and enables copy constructing subclasses. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Assignment operator. Doesn't copy anything, really, just initializes new object and enables copy constructing subclasses. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Compares objects by reference. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Compares objects by reference. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Reference-compares value type object with nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Specialization of [Object::ReferenceEquals](../../system/object/referenceequals/) for case of string and nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Specialization of [Object::ReferenceEquals](../../system/object/referenceequals/) for case of strings. |
|  [Regex](./regex/)() | Constructs empty regexp. |
|  [Regex](./regex/)(const [String](../../system/string/)\&) | Constructor. |
|  [Regex](./regex/)(const [String](../../system/string/)\&, [RegexOptions](../regexoptions/)) | Constructor. |
|  [Regex](./regex/)(const [String](../../system/string/)\&, [RegexOptions](../regexoptions/), [TimeSpan](../../system/timespan/)) | Constructor. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Decreases shared reference count by specified value. |
| [String](../../system/string/) [Replace](./replace/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&) | Replaces all matches of regex in string with replacement string. |
| [String](../../system/string/) [Replace](./replace/)(const [String](../../system/string/)\&, const char_t *) | Replaces all matches of regex in string with replacement string. |
| static [String](../../system/string/) [Replace](./replace/)(const [String](../../system/string/)\&, const char_t *, const char_t *) | Replaces all matches of regex in string with replacement string. |
| static [String](../../system/string/) [Replace](./replace/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, const char_t *) | Replaces all matches of regex in string with replacement string. |
| [String](../../system/string/) [Replace](./replace/)(const [String](../../system/string/)\&, const [MatchEvaluator](../matchevaluator/)\&) | Replaces all matches in string with delegate-generated replacement strings. |
| [String](../../system/string/) [Replace](./replace/)(const [String](../../system/string/)\&, const [MatchEvaluator](../matchevaluator/)\&, int) | Replaces all matches in string with delegate-generated replacement strings. |
| [String](../../system/string/) [Replace](./replace/)(const [String](../../system/string/)\&, const [MatchEvaluator](../matchevaluator/)\&, int, int) | Replaces all matches in string with delegate-generated replacement strings. |
| static [String](../../system/string/) [Replace](./replace/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, const [MatchEvaluator](../matchevaluator/)\&, [RegexOptions](../regexoptions/)) | Replaces all matches in string with delegate-generated replacement strings (static function). |
| static [String](../../system/string/) [Replace](./replace/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, const [String](../../system/string/)\&, [RegexOptions](../regexoptions/)) | Replaces all matches of regex in string with replacement string. |
| static [String](../../system/string/) [Replace](./replace/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, int) | Replaces substrings in string. Not implemented. |
| static [String](../../system/string/) [Replace](./replace/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, int, int) | Replaces substrings in string. Not implemented. |
| static [String](../../system/string/) [Replace](./replace/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, const [String](../../system/string/)\&) | Replaces regex matches. |
| static [String](../../system/string/) [Replace](./replace/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, const [MatchEvaluator](../matchevaluator/)\&) | Replaces regex matches. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Set n'th template argument a weak pointer (rather than shared). Allows switching pointers in containers to weak mode. |
| int [SharedCount](../../system/object/sharedcount/)() const | Gets current value of shared reference counter. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Increments shared reference count. Shouldn't be called directly; instead, use smart pointers or ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Decrements and returns shared reference count. Shouldn't be called directly; instead, use smart pointers or ThisProtector. |
| [ArrayPtr](../../system/arrayptr/)\<[String](../../system/string/)\> [Split](./split/)(const [String](../../system/string/)\&) | Splits string by regex matches. |
| [ArrayPtr](../../system/arrayptr/)\<[String](../../system/string/)\> [Split](./split/)(const [String](../../system/string/)\&, int) | Splits string by regex matches. |
| [ArrayPtr](../../system/arrayptr/)\<[String](../../system/string/)\> [Split](./split/)(const [String](../../system/string/)\&, int, int) | Splits an input string a specified maximum number of times into an array of substrings, at the positions defined by a regular expression specified in the [Regex](./) constructor. The search for the regular expression pattern starts at a specified character position in the input string. |
| static [ArrayPtr](../../system/arrayptr/)\<[String](../../system/string/)\> [Split](./split/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, [RegexOptions](../regexoptions/), [TimeSpan](../../system/timespan/)) | Splits string by regexp. |
| static [ArrayPtr](../../system/arrayptr/)\<[String](../../system/string/)\> [Split](./split/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, int, [RegexOptions](../regexoptions/), [TimeSpan](../../system/timespan/)) | Splits string by regexp. |
| [String](../../system/string/) [ToString](./tostring/)() const override | Converts regex to string. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implements C# typeof([System.Object](../../system/object/)) construct. |
| static [String](../../system/string/) [Unescape](./unescape/)(const [String](../../system/string/)\&) | Unescapes special characters in string used as part of the pattern. |
| void [Unlock](../../system/object/unlock/)() | Implements C# lock() statement unlocking. Call directly or use [LockContext](../../system/lockcontext/) sentry object. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Increments weak reference count. Shouldn't be called directly; instead, use smart pointers or ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Decrements weak reference count. Shouldn't be called directly; instead, use smart pointers or ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | Destroys object. Frees all internal data structures. |
## Fields

| Field | Description |
| --- | --- |
| static [InfiniteMatchTimeout](./infinitematchtimeout/) | Special timeout value to disable match break by timeout. |
## See Also

* Class [Object](../../system/object/)
* Namespace [System::Text::RegularExpressions](../)
* Library [Aspose.Slides](../../)