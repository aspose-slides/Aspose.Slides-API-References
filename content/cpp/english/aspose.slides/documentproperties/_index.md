---
title: DocumentProperties
second_title: Aspose.Slides for C++ API Reference
description: Represents properties of a presentation.
type: docs
weight: 794
url: /aspose.slides/documentproperties/
---
## DocumentProperties class


Represents properties of a presentation.

```cpp
class DocumentProperties : public Aspose::Slides::IDocumentProperties,
                           public Aspose::Slides::IGenericCloneable<System::SharedPtr<Aspose::Slides::IDocumentProperties>>
```

## Methods

| Method | Description |
| --- | --- |
| void [ClearBuiltInProperties](./clearbuiltinproperties/)() override | Clears and sets default values for all builtIn properties. |
| void [ClearCustomProperties](./clearcustomproperties/)() override | Removes all custom properties. |
| [System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\> [Clone](./clone/)() override | Clones current object |
| [System::SharedPtr](../../system/sharedptr/)\<[IDocumentProperties](../idocumentproperties/)\> [CloneT](./clonet/)() override | Clones current object |
| **bool** [ContainsCustomProperty](./containscustomproperty/)([System::String](../../system/string/)) override | Check presents of a custom property with a specified name. |
|  [DocumentProperties](./documentproperties/)() | Initializes new instance of class [DocumentProperties](./). |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Compares objects using C# [Object.Equals](../../system/object/equals/) semantics. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Compares reference type objects in C# style. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Compares value type objects in C# style. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emulates C#-style floating point comparison where two NaNs are considered equal even though according to IEC 60559:1989 NaN is not equal to any value, including NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emulates C#-style floating point comparison where two NaNs are considered equal even though according to IEC 60559:1989 NaN is not equal to any value, including NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | For internal purposes only. |
| [System::String](../../system/string/) [get_ApplicationTemplate](./get_applicationtemplate/)() override | Returns the template of a application. Read [System::String](../../system/string/). |
| [System::String](../../system/string/) [get_AppVersion](./get_appversion/)() override | Returns the app version. Read-only [System::String](../../system/string/). |
| [System::String](../../system/string/) [get_Author](./get_author/)() override | Returns the author of a presentation. Read [System::String](../../system/string/). |
| [System::String](../../system/string/) [get_Category](./get_category/)() override | Returns the category of a presentation. Read [System::String](../../system/string/). |
| [System::String](../../system/string/) [get_Comments](./get_comments/)() override | Returns the comments of a presentation. Read [System::String](../../system/string/). |
| [System::String](../../system/string/) [get_Company](./get_company/)() override | Returns the company property. Read [System::String](../../system/string/). |
| [System::String](../../system/string/) [get_ContentStatus](./get_contentstatus/)() override | Returns the content status of a presentation. Read [System::String](../../system/string/). |
| [System::String](../../system/string/) [get_ContentType](./get_contenttype/)() override | Returns the content type of a presentation. Read [System::String](../../system/string/). |
| **int32_t** [get_CountOfCustomProperties](./get_countofcustomproperties/)() override | Returns the number of custom properties actually contained in a collection. Read-only **int32_t**. |
| [System::DateTime](../../system/datetime/) [get_CreatedTime](./get_createdtime/)() override | Returns the date a presentation was created. Values are in UTC. Read [System::DateTime](../../system/datetime/). |
| [System::ArrayPtr](../../system/arrayptr/)\<[System::SharedPtr](../../system/sharedptr/)\<[IHeadingPair](../iheadingpair/)\>\> [get_HeadingPairs](./get_headingpairs/)() override | Indicates the grouping of document parts and the number of parts in each group. Read-only [System::ArrayPtr<System::SharedPtr<IHeadingPair>>](../../system/arrayptr/). |
| **int32_t** [get_HiddenSlides](./get_hiddenslides/)() override | Returns the number of hidden slides in a presentation document. Read-only **int32_t**. |
| [System::String](../../system/string/) [get_HyperlinkBase](./get_hyperlinkbase/)() override | Returns the HyperlinkBase document property. Read [System::String](../../system/string/). |
| **bool** [get_HyperlinksChanged](./get_hyperlinkschanged/)() override | Specifies that one or more hyperlinks in this part were updated exclusively in this part by a producer. The next producer to open this document shall update the hyperlink relationships with the new hyperlinks specified in this part. Read **bool**. |
| [System::String](../../system/string/) [get_Keywords](./get_keywords/)() override | Returns the keywords of a presentation. Read [System::String](../../system/string/). |
| [System::DateTime](../../system/datetime/) [get_LastPrinted](./get_lastprinted/)() override | Returns the date when a presentation was printed last time. Read [System::DateTime](../../system/datetime/). |
| [System::String](../../system/string/) [get_LastSavedBy](./get_lastsavedby/)() override | Returns the name of a last person who modified a presentation. Read [System::String](../../system/string/). |
| [System::DateTime](../../system/datetime/) [get_LastSavedTime](./get_lastsavedtime/)() override | Returns the date a presentation was last modified. Values are in UTC. Read-only in case of [Presentation::get_DocumentProperties](../presentation/get_documentproperties/) (because it will be updated internally while [IPresentation](../ipresentation/) object saving process). Can be changed via [DocumentProperties](./) instance returning by method [IPresentationInfo::ReadDocumentProperties](../ipresentationinfo/readdocumentproperties/) Please see the example in [IPresentationInfo::UpdateDocumentProperties](../ipresentationinfo/updatedocumentproperties/) method summary. |
| **bool** [get_LinksUpToDate](./get_linksuptodate/)() override | Indicates whether hyperlinks in a document are up-to-date. Set this element to **true** to indicate that hyperlinks are updated. Set this element to **false** to indicate that hyperlinks are outdated. Read **bool**. |
| [System::String](../../system/string/) [get_Manager](./get_manager/)() override | Returns the manager property. Read [System::String](../../system/string/). |
| **int32_t** [get_MultimediaClips](./get_multimediaclips/)() override | Returns the total number of sound or video clips that are present in the document. Read-only **int32_t**. |
| [System::String](../../system/string/) [get_NameOfApplication](./get_nameofapplication/)() override | Returns the name of the application. Read [System::String](../../system/string/). |
| **int32_t** [get_Notes](./get_notes/)() override | Returns the number of slides in a presentation containing notes. Read-only **int32_t**. |
| **int32_t** [get_Paragraphs](./get_paragraphs/)() override | Returns the total number of paragraphs found in a document if applicable. Read-only **int32_t**. |
| [System::String](../../system/string/) [get_PresentationFormat](./get_presentationformat/)() override | Returns the intended format of a presentation. Read [System::String](../../system/string/). |
| **int32_t** [get_RevisionNumber](./get_revisionnumber/)() override | Returns the presentation revision number. Read **int32_t**. |
| **bool** [get_ScaleCrop](./get_scalecrop/)() override | Indicates the display mode of the document thumbnail. Set this element to **true** to enable scaling of the document thumbnail to the display. Set this element to **false** to enable cropping of the document thumbnail to show only sections that fits the display. Read **bool**. |
| **bool** [get_SharedDoc](./get_shareddoc/)() override | Determines whether the presentation is shared between multiple people. Read **bool**. |
| **int32_t** [get_Slides](./get_slides/)() override | Returns the total number of slides in a presentation document. Read-only **int32_t**. |
| [System::String](../../system/string/) [get_Subject](./get_subject/)() override | Returns the subject of a presentation. Read [System::String](../../system/string/). |
| [System::String](../../system/string/) [get_Title](./get_title/)() override | Returns the title of a presentation. Read [System::String](../../system/string/). |
| [System::ArrayPtr](../../system/arrayptr/)\<[System::String](../../system/string/)\> [get_TitlesOfParts](./get_titlesofparts/)() override | Specifies the title of each document part. These parts are not document parts but conceptual representations of document sections. Read-only [System::ArrayPtr<System::String>](../../system/arrayptr/). |
| [System::TimeSpan](../../system/timespan/) [get_TotalEditingTime](./get_totaleditingtime/)() override | Total editing time of a presentation. Read [System::TimeSpan](../../system/timespan/). |
| **int32_t** [get_Words](./get_words/)() override | Returns the total number of words contained in a document. Read-only **int32_t**. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Gets reference counter data structure associated with the object. |
| [System::String](../../system/string/) [GetCustomPropertyName](./getcustompropertyname/)(**int32_t**) override | Return a custom property name at the specified index. |
| void [GetCustomPropertyValue](./getcustompropertyvalue/)([System::String](../../system/string/), **bool**\&) override | Gets a named boolean value from the custom properties. |
| void [GetCustomPropertyValue](./getcustompropertyvalue/)([System::String](../../system/string/), **int32_t**\&) override | Gets a named integer value from the custom properties. |
| void [GetCustomPropertyValue](./getcustompropertyvalue/)([System::String](../../system/string/), [System::DateTime](../../system/datetime/)\&) override | Gets a named DateTime value from the custom properties. |
| void [GetCustomPropertyValue](./getcustompropertyvalue/)([System::String](../../system/string/), [System::String](../../system/string/)\&) override | Gets a named string value from the custom properties. |
| void [GetCustomPropertyValue](./getcustompropertyvalue/)([System::String](../../system/string/), **float**\&) override | Gets a named float value from the custom properties. |
| void [GetCustomPropertyValue](./getcustompropertyvalue/)([System::String](../../system/string/), **double**\&) override | Gets a named double value from the custom properties. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analog of C# [Object.GetHashCode()](../../system/object/gethashcode/) method. Enables hashing of custom objects. |
| [System::ArrayPtr](../../system/arrayptr/)\<[System::SharedPtr](../../system/sharedptr/)\<[ISensitivityLabel](../isensitivitylabel/)\>\> [GetSensitivityLabels](./getsensitivitylabels/)() override | Gets an array of sensitivity labels from the custom document properties (Microsoft Information Protection SDK Metadata). |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Gets actual type of object. Analog of C# [System.Object.GetType()](../../system/object/gettype/) call. |
| [System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\> [idx_get](./idx_get/)([System::String](../../system/string/)) override | Returns the custom property associated with a specified name. Read [System::Object](../../system/object/). |
| void [idx_set](./idx_set/)([System::String](../../system/string/), [System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\>) override | Sets the custom property associated with a specified name. Write [System::Object](../../system/object/). |
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
| **bool** [RemoveCustomProperty](./removecustomproperty/)([System::String](../../system/string/)) override | Remove a custom property associated with a specified name. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Decreases shared reference count by specified value. |
| void [set_ApplicationTemplate](./set_applicationtemplate/)([System::String](../../system/string/)) override | Sets the template of a application. Write [System::String](../../system/string/). |
| void [set_Author](./set_author/)([System::String](../../system/string/)) override | Sets the author of a presentation. Write [System::String](../../system/string/). |
| void [set_Category](./set_category/)([System::String](../../system/string/)) override | Sets the category of a presentation. Write [System::String](../../system/string/). |
| void [set_Comments](./set_comments/)([System::String](../../system/string/)) override | Sets the comments of a presentation. Write [System::String](../../system/string/). |
| void [set_Company](./set_company/)([System::String](../../system/string/)) override | Sets the company property. Write [System::String](../../system/string/). |
| void [set_ContentStatus](./set_contentstatus/)([System::String](../../system/string/)) override | Sets the content status of a presentation. Write [System::String](../../system/string/). |
| void [set_ContentType](./set_contenttype/)([System::String](../../system/string/)) override | Sets the content type of a presentation. Write [System::String](../../system/string/). |
| void [set_CreatedTime](./set_createdtime/)([System::DateTime](../../system/datetime/)) override | Returns the date a presentation was created. Values are in UTC. Write [System::DateTime](../../system/datetime/). |
| void [set_HyperlinkBase](./set_hyperlinkbase/)([System::String](../../system/string/)) override | Sets the HyperlinkBase document property. Write [System::String](../../system/string/). |
| void [set_HyperlinksChanged](./set_hyperlinkschanged/)(**bool**) override | Specifies that one or more hyperlinks in this part were updated exclusively in this part by a producer. The next producer to open this document shall update the hyperlink relationships with the new hyperlinks specified in this part. Write **bool**. |
| void [set_Keywords](./set_keywords/)([System::String](../../system/string/)) override | Sets the keywords of a presentation. Write [System::String](../../system/string/). |
| void [set_LastPrinted](./set_lastprinted/)([System::DateTime](../../system/datetime/)) override | Returns the date when a presentation was printed last time. Write [System::DateTime](../../system/datetime/). |
| void [set_LastSavedBy](./set_lastsavedby/)([System::String](../../system/string/)) override | Sets the name of a last person who modified a presentation. Write [System::String](../../system/string/). |
| void [set_LastSavedTime](./set_lastsavedtime/)([System::DateTime](../../system/datetime/)) override | Returns the date a presentation was last modified. Values are in UTC. Read-only in case of [Presentation::get_DocumentProperties](../presentation/get_documentproperties/) (because it will be updated internally while [IPresentation](../ipresentation/) object saving process). Can be changed via [DocumentProperties](./) instance returning by method [IPresentationInfo::ReadDocumentProperties](../ipresentationinfo/readdocumentproperties/) Please see the example in [IPresentationInfo::UpdateDocumentProperties](../ipresentationinfo/updatedocumentproperties/) method summary. |
| void [set_LinksUpToDate](./set_linksuptodate/)(**bool**) override | Indicates whether hyperlinks in a document are up-to-date. Set this element to **true** to indicate that hyperlinks are updated. Set this element to **false** to indicate that hyperlinks are outdated. Write **bool**. |
| void [set_Manager](./set_manager/)([System::String](../../system/string/)) override | Sets the manager property. Write [System::String](../../system/string/). |
| void [set_NameOfApplication](./set_nameofapplication/)([System::String](../../system/string/)) override | Sets the name of the application. Write [System::String](../../system/string/). |
| void [set_PresentationFormat](./set_presentationformat/)([System::String](../../system/string/)) override | Sets the intended format of a presentation. Write [System::String](../../system/string/). |
| void [set_RevisionNumber](./set_revisionnumber/)(**int32_t**) override | Sets the presentation revision number. Write **int32_t**. |
| void [set_ScaleCrop](./set_scalecrop/)(**bool**) override | Indicates the display mode of the document thumbnail. Set this element to **true** to enable scaling of the document thumbnail to the display. Set this element to **false** to enable cropping of the document thumbnail to show only sections that fits the display. Write **bool**. |
| void [set_SharedDoc](./set_shareddoc/)(**bool**) override | Determines whether the presentation is shared between multiple people. Write **bool**. |
| void [set_Subject](./set_subject/)([System::String](../../system/string/)) override | Sets the subject of a presentation. Write [System::String](../../system/string/). |
| void [set_Title](./set_title/)([System::String](../../system/string/)) override | Sets the title of a presentation. Write [System::String](../../system/string/). |
| void [set_TotalEditingTime](./set_totaleditingtime/)([System::TimeSpan](../../system/timespan/)) override | Total editing time of a presentation. Write [System::TimeSpan](../../system/timespan/). |
| void [SetCustomPropertyValue](./setcustompropertyvalue/)([System::String](../../system/string/), **bool**) override | Sets a named boolean custom property. |
| void [SetCustomPropertyValue](./setcustompropertyvalue/)([System::String](../../system/string/), **int32_t**) override | Sets a named integer custom property. |
| void [SetCustomPropertyValue](./setcustompropertyvalue/)([System::String](../../system/string/), [System::DateTime](../../system/datetime/)) override | Sets a named DateTime custom property. |
| void [SetCustomPropertyValue](./setcustompropertyvalue/)([System::String](../../system/string/), [System::String](../../system/string/)) override | Sets a named string custom property. |
| void [SetCustomPropertyValue](./setcustompropertyvalue/)([System::String](../../system/string/), **float**) override | Sets a named float custom property. |
| void [SetCustomPropertyValue](./setcustompropertyvalue/)([System::String](../../system/string/), **double**) override | Sets a named double custom property. |
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
## Remarks


The following example shows how to access built-in Properties of PowerPoint [Presentation](../presentation/). 
```cpp
// Instantiate the Presentation class that represents the presentation
auto pres = System::MakeObject<Presentation>(dataDir + u"AccessBuiltin Properties.pptx");

// Create a reference to IDocumentProperties object associated with Presentation
System::SharedPtr<IDocumentProperties> documentProperties = pres->get_DocumentProperties();
// Display the builtin properties
System::Console::WriteLine(System::String(u"Category : ") + documentProperties->get_Category());
System::Console::WriteLine(System::String(u"Current Status : ") + documentProperties->get_ContentStatus());
System::Console::WriteLine(System::String(u"Creation Date : ") + documentProperties->get_CreatedTime());
System::Console::WriteLine(System::String(u"Author : ") + documentProperties->get_Author());
System::Console::WriteLine(System::String(u"Description : ") + documentProperties->get_Comments());
```
 The following example shows how to modify built-in Properties of PowerPoint [Presentation](../presentation/). 
```cpp
// Instantiate the Presentation class that represents the Presentation
auto presentation = System::MakeObject<Presentation>(dataDir + u"ModifyBuiltinProperties.pptx");

// Create a reference to IDocumentProperties object associated with Presentation
System::SharedPtr<IDocumentProperties> documentProperties = presentation->get_DocumentProperties();
// Set the builtin properties
documentProperties->set_Author(u"Aspose.Slides for .NET");
documentProperties->set_Title(u"Modifying Presentation Properties");
documentProperties->set_Subject(u"Aspose Subject");
// Save your presentation to a file
presentation->Save(u"DocumentProperties_out.pptx", SaveFormat::Pptx);
```

## See Also

* Class [IDocumentProperties](../idocumentproperties/)
* Class [IGenericCloneable](../igenericcloneable/)
* Namespace [Aspose::Slides](../)
* Library [Aspose.Slides](../../)