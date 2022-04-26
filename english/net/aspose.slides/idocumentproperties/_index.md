---
title: IDocumentProperties
second_title: Aspose.Sildes for .NET API Reference
description: 
type: docs
weight: 5210
url: /net/aspose.slides/idocumentproperties/
---
## IDocumentProperties interface

Represents properties of a presentation.

```csharp
public interface IDocumentProperties
```

## Properties

| Name | Description |
| --- | --- |
| [ApplicationTemplate](applicationtemplate) { get; set; } | Returns or sets the template of a application. Read/write String. |
| [AppVersion](appversion) { get; } | Returns the app version. Read-only String. |
| [Author](author) { get; set; } | Returns or sets the author of a presentation. Read/write String. |
| [Category](category) { get; set; } | Returns or sets the category of a presentation. Read/write String. |
| [Comments](comments) { get; set; } | Returns or sets the comments of a presentation. Read/write String. |
| [Company](company) { get; set; } | Returns or sets the company property. Read/write String. |
| [ContentStatus](contentstatus) { get; set; } | Returns or sets the content status of a presentation. Read/write String. |
| [ContentType](contenttype) { get; set; } | Returns or sets the content type of a presentation. Read/write String. |
| [CountOfCustomProperties](countofcustomproperties) { get; } | Returns the number of custom properties actually contained in a collection. Read-only Int32. |
| [CreatedTime](createdtime) { get; set; } | Returns the date when a presentation was created. Read/write DateTime. |
| [HyperlinkBase](hyperlinkbase) { get; set; } | Returns or sets the HyperlinkBase document property. Read/write String. |
| [Item](item) { get; set; } | Returns or sets the custom property associated with a specified name. Read/write Object. |
| [Keywords](keywords) { get; set; } | Returns or sets the keywords of a presentation. Read/write String. |
| [LastPrinted](lastprinted) { get; set; } | Returns the date when a presentation was printed last time. Read/write DateTime. |
| [LastSavedBy](lastsavedby) { get; set; } | Returns or sets the name of a last person who modified a presentation. Read/write String. |
| [LastSavedTime](lastsavedtime) { get; set; } | Returns the date when a presentation was modified last time. Read-only in case of Presentation.DocumentProperties (because it will be updated internally while IPresentation object saving process). Can be changed via DocumentProperties instance returning by method [`ReadDocumentProperties`](../ipresentationinfo/readdocumentproperties) Please see the example in [`UpdateDocumentProperties`](../ipresentationinfo/updatedocumentproperties) method summary. |
| [Manager](manager) { get; set; } | Returns or sets the manager property. Read/write String. |
| [NameOfApplication](nameofapplication) { get; set; } | Returns or sets the name of the application. Read/write String. |
| [PresentationFormat](presentationformat) { get; set; } | Returns or sets the intended format of a presentation. Read/write String. |
| [RevisionNumber](revisionnumber) { get; set; } | Returns or sets the presentation revision number. Read/write Int32. |
| [SharedDoc](shareddoc) { get; set; } | Determines whether the presentation is shared between multiple people. Read/write Boolean. |
| [Subject](subject) { get; set; } | Returns or sets the subject of a presentation. Read/write String. |
| [Title](title) { get; set; } | Returns or sets the title of a presentation. Read/write String. |
| [TotalEditingTime](totaleditingtime) { get; set; } | Total editing time of a presentation. Read/write TimeSpan. |

## Methods

| Name | Description |
| --- | --- |
| [ClearBuiltInProperties](clearbuiltinproperties)() | Clears and sets default values for all builtIn properties. |
| [ClearCustomProperties](clearcustomproperties)() | Removes all custom properties. |
| [ContainsCustomProperty](containscustomproperty)(string) | Check presents of a custom property with a specified name. |
| [GetCustomPropertyName](getcustompropertyname)(int) | Return a custom property name at the specified index. |
| [GetCustomPropertyValue](getcustompropertyvalue)(string, out bool) | Gets a named boolean value from the custom properties. |
| [GetCustomPropertyValue](getcustompropertyvalue)(string, out DateTime) | Gets a named DateTime value from the custom properties. |
| [GetCustomPropertyValue](getcustompropertyvalue)(string, out double) | Gets a named double value from the custom properties. |
| [GetCustomPropertyValue](getcustompropertyvalue)(string, out float) | Gets a named float value from the custom properties. |
| [GetCustomPropertyValue](getcustompropertyvalue)(string, out int) | Gets a named integer value from the custom properties. |
| [GetCustomPropertyValue](getcustompropertyvalue)(string, out string) | Gets a named string value from the custom properties. |
| [RemoveCustomProperty](removecustomproperty)(string) | Remove a custom property associated with a specified name. |
| [SetCustomPropertyValue](setcustompropertyvalue)(string, bool) | Sets a named boolean custom property. |
| [SetCustomPropertyValue](setcustompropertyvalue)(string, DateTime) | Sets a named DateTime custom property. |
| [SetCustomPropertyValue](setcustompropertyvalue)(string, double) | Sets a named double custom property. |
| [SetCustomPropertyValue](setcustompropertyvalue)(string, float) | Sets a named float custom property. |
| [SetCustomPropertyValue](setcustompropertyvalue)(string, int) | Sets a named integer custom property. |
| [SetCustomPropertyValue](setcustompropertyvalue)(string, string) | Sets a named string custom property. |

### See Also

* namespace [Aspose.Slides](../../aspose.slides)
* assembly [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->
