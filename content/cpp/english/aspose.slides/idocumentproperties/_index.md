---
title: IDocumentProperties
second_title: Aspose.Slides for C++ API Reference
description: Represents properties of a presentation.
type: docs
weight: 1912
url: /aspose.slides/idocumentproperties/
---
## IDocumentProperties class


Represents properties of a presentation.

```cpp
class IDocumentProperties : public virtual System::Object
```

## Methods

| Method | Description |
| --- | --- |
| virtual void [ClearBuiltInProperties](./clearbuiltinproperties/)() | Clears and sets default values for all builtIn properties. |
| virtual void [ClearCustomProperties](./clearcustomproperties/)() | Removes all custom properties. |
| virtual **bool** [ContainsCustomProperty](./containscustomproperty/)([System::String](../../system/string/)) | Check presents of a custom property with a specified name. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Compares objects using C# [Object.Equals](../../system/object/equals/) semantics. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Compares reference type objects in C# style. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Compares value type objects in C# style. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emulates C#-style floating point comparison where two NaNs are considered equal even though according to IEC 60559:1989 NaN is not equal to any value, including NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emulates C#-style floating point comparison where two NaNs are considered equal even though according to IEC 60559:1989 NaN is not equal to any value, including NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | For internal purposes only. |
| virtual [System::String](../../system/string/) [get_ApplicationTemplate](./get_applicationtemplate/)() | Returns the template of a application. Read [System::String](../../system/string/). |
| virtual [System::String](../../system/string/) [get_AppVersion](./get_appversion/)() | Returns the app version. Read-only [System::String](../../system/string/). |
| virtual [System::String](../../system/string/) [get_Author](./get_author/)() | Returns the author of a presentation. Read [System::String](../../system/string/). |
| virtual [System::String](../../system/string/) [get_Category](./get_category/)() | Returns the category of a presentation. Read [System::String](../../system/string/). |
| virtual [System::String](../../system/string/) [get_Comments](./get_comments/)() | Returns the comments of a presentation. Read [System::String](../../system/string/). |
| virtual [System::String](../../system/string/) [get_Company](./get_company/)() | Returns the company property. Read [System::String](../../system/string/). |
| virtual [System::String](../../system/string/) [get_ContentStatus](./get_contentstatus/)() | Returns the content status of a presentation. Read [System::String](../../system/string/). |
| virtual [System::String](../../system/string/) [get_ContentType](./get_contenttype/)() | Returns the content type of a presentation. Read [System::String](../../system/string/). |
| virtual **int32_t** [get_CountOfCustomProperties](./get_countofcustomproperties/)() | Returns the number of custom properties actually contained in a collection. Read-only **int32_t**. |
| virtual [System::DateTime](../../system/datetime/) [get_CreatedTime](./get_createdtime/)() | Returns the date a presentation was created. Values are in UTC. Read [System::DateTime](../../system/datetime/). |
| virtual [System::String](../../system/string/) [get_HyperlinkBase](./get_hyperlinkbase/)() | Returns the HyperlinkBase document property. Read [System::String](../../system/string/). |
| virtual [System::String](../../system/string/) [get_Keywords](./get_keywords/)() | Returns the keywords of a presentation. Read [System::String](../../system/string/). |
| virtual [System::DateTime](../../system/datetime/) [get_LastPrinted](./get_lastprinted/)() | Returns the date when a presentation was printed last time. Read [System::DateTime](../../system/datetime/). |
| virtual [System::String](../../system/string/) [get_LastSavedBy](./get_lastsavedby/)() | Returns the name of a last person who modified a presentation. Read [System::String](../../system/string/). |
| virtual [System::DateTime](../../system/datetime/) [get_LastSavedTime](./get_lastsavedtime/)() | Returns the date a presentation was last modified. Values are in UTC.P Read-only in case of Presentation.DocumentProperties (because it will be updated internally while [IPresentation](../ipresentation/) object saving process). Can be changed via [DocumentProperties](../documentproperties/) instance returning by method [IPresentationInfo::ReadDocumentProperties](../ipresentationinfo/readdocumentproperties/) Please see the example in [IPresentationInfo::UpdateDocumentProperties](../ipresentationinfo/updatedocumentproperties/) method summary. |
| virtual [System::String](../../system/string/) [get_Manager](./get_manager/)() | Returns the manager property. Read [System::String](../../system/string/). |
| virtual [System::String](../../system/string/) [get_NameOfApplication](./get_nameofapplication/)() | Returns the name of the application. Read [System::String](../../system/string/). |
| virtual [System::String](../../system/string/) [get_PresentationFormat](./get_presentationformat/)() | Returns the intended format of a presentation. Read [System::String](../../system/string/). |
| virtual **int32_t** [get_RevisionNumber](./get_revisionnumber/)() | Returns the presentation revision number. Read **int32_t**. |
| virtual **bool** [get_SharedDoc](./get_shareddoc/)() | Determines whether the presentation is shared between multiple people. Read **bool**. |
| virtual [System::String](../../system/string/) [get_Subject](./get_subject/)() | Returns the subject of a presentation. Read [System::String](../../system/string/). |
| virtual [System::String](../../system/string/) [get_Title](./get_title/)() | Returns the title of a presentation. Read [System::String](../../system/string/). |
| virtual [System::TimeSpan](../../system/timespan/) [get_TotalEditingTime](./get_totaleditingtime/)() | Total editing time of a presentation. Read [System::TimeSpan](../../system/timespan/). |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Gets reference counter data structure associated with the object. |
| virtual [System::String](../../system/string/) [GetCustomPropertyName](./getcustompropertyname/)(**int32_t**) | Return a custom property name at the specified index. |
| virtual void [GetCustomPropertyValue](./getcustompropertyvalue/)([System::String](../../system/string/), **bool**\&) | Gets a named boolean value from the custom properties. |
| virtual void [GetCustomPropertyValue](./getcustompropertyvalue/)([System::String](../../system/string/), **int32_t**\&) | Gets a named integer value from the custom properties. |
| virtual void [GetCustomPropertyValue](./getcustompropertyvalue/)([System::String](../../system/string/), [System::DateTime](../../system/datetime/)\&) | Gets a named DateTime value from the custom properties. |
| virtual void [GetCustomPropertyValue](./getcustompropertyvalue/)([System::String](../../system/string/), [System::String](../../system/string/)\&) | Gets a named string value from the custom properties. |
| virtual void [GetCustomPropertyValue](./getcustompropertyvalue/)([System::String](../../system/string/), **float**\&) | Gets a named float value from the custom properties. |
| virtual void [GetCustomPropertyValue](./getcustompropertyvalue/)([System::String](../../system/string/), **double**\&) | Gets a named double value from the custom properties. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analog of C# [Object.GetHashCode()](../../system/object/gethashcode/) method. Enables hashing of custom objects. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Gets actual type of object. Analog of C# [System.Object.GetType()](../../system/object/gettype/) call. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\> [idx_get](./idx_get/)([System::String](../../system/string/)) | Returns the custom property associated with a specified name. Read [System::Object](../../system/object/). |
| virtual void [idx_set](./idx_set/)([System::String](../../system/string/), [System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\>) | Sets the custom property associated with a specified name. Write [System::Object](../../system/object/). |
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
| virtual **bool** [RemoveCustomProperty](./removecustomproperty/)([System::String](../../system/string/)) | Remove a custom property associated with a specified name. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Decreases shared reference count by specified value. |
| virtual void [set_ApplicationTemplate](./set_applicationtemplate/)([System::String](../../system/string/)) | Sets the template of a application. Write [System::String](../../system/string/). |
| virtual void [set_Author](./set_author/)([System::String](../../system/string/)) | Sets the author of a presentation. Write [System::String](../../system/string/). |
| virtual void [set_Category](./set_category/)([System::String](../../system/string/)) | Sets the category of a presentation. Write [System::String](../../system/string/). |
| virtual void [set_Comments](./set_comments/)([System::String](../../system/string/)) | Sets the comments of a presentation. Write [System::String](../../system/string/). |
| virtual void [set_Company](./set_company/)([System::String](../../system/string/)) | Sets the company property. Write [System::String](../../system/string/). |
| virtual void [set_ContentStatus](./set_contentstatus/)([System::String](../../system/string/)) | Sets the content status of a presentation. Write [System::String](../../system/string/). |
| virtual void [set_ContentType](./set_contenttype/)([System::String](../../system/string/)) | Sets the content type of a presentation. Write [System::String](../../system/string/). |
| virtual void [set_CreatedTime](./set_createdtime/)([System::DateTime](../../system/datetime/)) | Returns the date a presentation was created. Values are in UTC. Write [System::DateTime](../../system/datetime/). |
| virtual void [set_HyperlinkBase](./set_hyperlinkbase/)([System::String](../../system/string/)) | Sets the HyperlinkBase document property. Write [System::String](../../system/string/). |
| virtual void [set_Keywords](./set_keywords/)([System::String](../../system/string/)) | Sets the keywords of a presentation. Write [System::String](../../system/string/). |
| virtual void [set_LastPrinted](./set_lastprinted/)([System::DateTime](../../system/datetime/)) | Returns the date when a presentation was printed last time. Write [System::DateTime](../../system/datetime/). |
| virtual void [set_LastSavedBy](./set_lastsavedby/)([System::String](../../system/string/)) | Sets the name of a last person who modified a presentation. Write [System::String](../../system/string/). |
| virtual void [set_LastSavedTime](./set_lastsavedtime/)([System::DateTime](../../system/datetime/)) | Returns the date a presentation was last modified. Values are in UTC.P Read-only in case of Presentation.DocumentProperties (because it will be updated internally while [IPresentation](../ipresentation/) object saving process). Can be changed via [DocumentProperties](../documentproperties/) instance returning by method [IPresentationInfo::ReadDocumentProperties](../ipresentationinfo/readdocumentproperties/) Please see the example in [IPresentationInfo::UpdateDocumentProperties](../ipresentationinfo/updatedocumentproperties/) method summary. |
| virtual void [set_Manager](./set_manager/)([System::String](../../system/string/)) | Sets the manager property. Write [System::String](../../system/string/). |
| virtual void [set_NameOfApplication](./set_nameofapplication/)([System::String](../../system/string/)) | Sets the name of the application. Write [System::String](../../system/string/). |
| virtual void [set_PresentationFormat](./set_presentationformat/)([System::String](../../system/string/)) | Sets the intended format of a presentation. Write [System::String](../../system/string/). |
| virtual void [set_RevisionNumber](./set_revisionnumber/)(**int32_t**) | Sets the presentation revision number. Write **int32_t**. |
| virtual void [set_SharedDoc](./set_shareddoc/)(**bool**) | Determines whether the presentation is shared between multiple people. Write **bool**. |
| virtual void [set_Subject](./set_subject/)([System::String](../../system/string/)) | Sets the subject of a presentation. Write [System::String](../../system/string/). |
| virtual void [set_Title](./set_title/)([System::String](../../system/string/)) | Sets the title of a presentation. Write [System::String](../../system/string/). |
| virtual void [set_TotalEditingTime](./set_totaleditingtime/)([System::TimeSpan](../../system/timespan/)) | Total editing time of a presentation. Write [System::TimeSpan](../../system/timespan/). |
| virtual void [SetCustomPropertyValue](./setcustompropertyvalue/)([System::String](../../system/string/), **bool**) | Sets a named boolean custom property. |
| virtual void [SetCustomPropertyValue](./setcustompropertyvalue/)([System::String](../../system/string/), **int32_t**) | Sets a named integer custom property. |
| virtual void [SetCustomPropertyValue](./setcustompropertyvalue/)([System::String](../../system/string/), [System::DateTime](../../system/datetime/)) | Sets a named DateTime custom property. |
| virtual void [SetCustomPropertyValue](./setcustompropertyvalue/)([System::String](../../system/string/), [System::String](../../system/string/)) | Sets a named string custom property. |
| virtual void [SetCustomPropertyValue](./setcustompropertyvalue/)([System::String](../../system/string/), **float**) | Sets a named float custom property. |
| virtual void [SetCustomPropertyValue](./setcustompropertyvalue/)([System::String](../../system/string/), **double**) | Sets a named double custom property. |
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
* Namespace [Aspose::Slides](../)
* Library [Aspose.Slides](../../)