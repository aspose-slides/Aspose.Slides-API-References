---
title: IDocumentProperties
second_title: Aspose.Sildes for .NET API Reference
description: Represents properties of a presentation.
type: docs
weight: 5510
url: /aspose.slides/idocumentproperties/
---

## IDocumentProperties interface

Represents properties of a presentation.

```csharp
public interface IDocumentProperties
```

## Properties

| Name | Description |
| --- | --- |
| [ApplicationTemplate](../../aspose.slides/idocumentproperties/applicationtemplate) { get; set; } | Returns or sets the template of a application. Read/write String. |
| [AppVersion](../../aspose.slides/idocumentproperties/appversion) { get; } | Returns the app version. Read-only String. |
| [Author](../../aspose.slides/idocumentproperties/author) { get; set; } | Returns or sets the author of a presentation. Read/write String. |
| [Category](../../aspose.slides/idocumentproperties/category) { get; set; } | Returns or sets the category of a presentation. Read/write String. |
| [Comments](../../aspose.slides/idocumentproperties/comments) { get; set; } | Returns or sets the comments of a presentation. Read/write String. |
| [Company](../../aspose.slides/idocumentproperties/company) { get; set; } | Returns or sets the company property. Read/write String. |
| [ContentStatus](../../aspose.slides/idocumentproperties/contentstatus) { get; set; } | Returns or sets the content status of a presentation. Read/write String. |
| [ContentType](../../aspose.slides/idocumentproperties/contenttype) { get; set; } | Returns or sets the content type of a presentation. Read/write String. |
| [CountOfCustomProperties](../../aspose.slides/idocumentproperties/countofcustomproperties) { get; } | Returns the number of custom properties actually contained in a collection. Read-only Int32. |
| [CreatedTime](../../aspose.slides/idocumentproperties/createdtime) { get; set; } | Returns the date a presentation was created. Values are in UTC. Read/write DateTime. |
| [HeadingPairs](../../aspose.slides/idocumentproperties/headingpairs) { get; } | Indicates the grouping of document parts and the number of parts in each group. Read-only IHeadingPair[]. |
| [HiddenSlides](../../aspose.slides/idocumentproperties/hiddenslides) { get; } | Specifies the number of hidden slides in a presentation document. Read-only Int32. |
| [HyperlinkBase](../../aspose.slides/idocumentproperties/hyperlinkbase) { get; set; } | Returns or sets the HyperlinkBase document property. Read/write String. |
| [HyperlinksChanged](../../aspose.slides/idocumentproperties/hyperlinkschanged) { get; set; } | Specifies that one or more hyperlinks in this part were updated exclusively in this part by a producer. The next producer to open this document shall update the hyperlink relationships with the new hyperlinks specified in this part. Read/write Boolean. |
| [Item](../../aspose.slides/idocumentproperties/item) { get; set; } | Returns or sets the custom property associated with a specified name. Read/write Object. |
| [Keywords](../../aspose.slides/idocumentproperties/keywords) { get; set; } | Returns or sets the keywords of a presentation. Read/write String. |
| [LastPrinted](../../aspose.slides/idocumentproperties/lastprinted) { get; set; } | Returns the date when a presentation was printed last time. Read/write DateTime. |
| [LastSavedBy](../../aspose.slides/idocumentproperties/lastsavedby) { get; set; } | Returns or sets the name of a last person who modified a presentation. Read/write String. |
| [LastSavedTime](../../aspose.slides/idocumentproperties/lastsavedtime) { get; set; } | Returns the date a presentation was last modified. Values are in UTC.P Read-only in case of Presentation.DocumentProperties (because it will be updated internally while IPresentation object saving process). Can be changed via DocumentProperties instance returning by method [`ReadDocumentProperties`](../ipresentationinfo/readdocumentproperties) Please see the example in [`UpdateDocumentProperties`](../ipresentationinfo/updatedocumentproperties) method summary. |
| [LinksUpToDate](../../aspose.slides/idocumentproperties/linksuptodate) { get; set; } | Indicates whether hyperlinks in a document are up-to-date. Set this element to **true** to indicate that hyperlinks are updated. Set this element to **false** to indicate that hyperlinks are outdated. Read/write Boolean. |
| [Manager](../../aspose.slides/idocumentproperties/manager) { get; set; } | Returns or sets the manager property. Read/write String. |
| [MultimediaClips](../../aspose.slides/idocumentproperties/multimediaclips) { get; } | Specifies the total number of sound or video clips that are present in the document. Read-only Int32. |
| [NameOfApplication](../../aspose.slides/idocumentproperties/nameofapplication) { get; set; } | Returns or sets the name of the application. Read/write String. |
| [Notes](../../aspose.slides/idocumentproperties/notes) { get; } | Specifies the number of slides in a presentation containing notes. Read-only Int32. |
| [Paragraphs](../../aspose.slides/idocumentproperties/paragraphs) { get; } | Specifies the total number of paragraphs found in a document if applicable. Read-only Int32. |
| [PresentationFormat](../../aspose.slides/idocumentproperties/presentationformat) { get; set; } | Returns or sets the intended format of a presentation. Read/write String. |
| [RevisionNumber](../../aspose.slides/idocumentproperties/revisionnumber) { get; set; } | Returns or sets the presentation revision number. Read/write Int32. |
| [ScaleCrop](../../aspose.slides/idocumentproperties/scalecrop) { get; set; } | Indicates the display mode of the document thumbnail. Set this element to **true** to enable scaling of the document thumbnail to the display. Set this element to **false** to enable cropping of the document thumbnail to show only sections that fits the display. Read/write Boolean. |
| [SharedDoc](../../aspose.slides/idocumentproperties/shareddoc) { get; set; } | Determines whether the presentation is shared between multiple people. Read/write Boolean. |
| [Slides](../../aspose.slides/idocumentproperties/slides) { get; } | Specifies the total number of slides in a presentation document. Read-only Int32. |
| [Subject](../../aspose.slides/idocumentproperties/subject) { get; set; } | Returns or sets the subject of a presentation. Read/write String. |
| [Title](../../aspose.slides/idocumentproperties/title) { get; set; } | Returns or sets the title of a presentation. Read/write String. |
| [TitlesOfParts](../../aspose.slides/idocumentproperties/titlesofparts) { get; } | Specifies the title of each document part. These parts are not document parts but conceptual representations of document sections. Read-only string[]. |
| [TotalEditingTime](../../aspose.slides/idocumentproperties/totaleditingtime) { get; set; } | Total editing time of a presentation. Read/write TimeSpan. |
| [Words](../../aspose.slides/idocumentproperties/words) { get; } | Specifies the total number of words contained in a document. Read-only Int32. |

## Methods

| Name | Description |
| --- | --- |
| [ClearBuiltInProperties](../../aspose.slides/idocumentproperties/clearbuiltinproperties)() | Clears and sets default values for all builtIn properties. |
| [ClearCustomProperties](../../aspose.slides/idocumentproperties/clearcustomproperties)() | Removes all custom properties. |
| [ContainsCustomProperty](../../aspose.slides/idocumentproperties/containscustomproperty)(string) | Check presents of a custom property with a specified name. |
| [GetCustomPropertyName](../../aspose.slides/idocumentproperties/getcustompropertyname)(int) | Return a custom property name at the specified index. |
| [GetCustomPropertyValue](../../aspose.slides/idocumentproperties/getcustompropertyvalue#getcustompropertyvalue)(string, out bool) | Gets a named boolean value from the custom properties. |
| [GetCustomPropertyValue](../../aspose.slides/idocumentproperties/getcustompropertyvalue#getcustompropertyvalue_4)(string, out DateTime) | Gets a named DateTime value from the custom properties. |
| [GetCustomPropertyValue](../../aspose.slides/idocumentproperties/getcustompropertyvalue#getcustompropertyvalue_1)(string, out double) | Gets a named double value from the custom properties. |
| [GetCustomPropertyValue](../../aspose.slides/idocumentproperties/getcustompropertyvalue#getcustompropertyvalue_3)(string, out float) | Gets a named float value from the custom properties. |
| [GetCustomPropertyValue](../../aspose.slides/idocumentproperties/getcustompropertyvalue#getcustompropertyvalue_2)(string, out int) | Gets a named integer value from the custom properties. |
| [GetCustomPropertyValue](../../aspose.slides/idocumentproperties/getcustompropertyvalue#getcustompropertyvalue_5)(string, out string) | Gets a named string value from the custom properties. |
| [RemoveCustomProperty](../../aspose.slides/idocumentproperties/removecustomproperty)(string) | Remove a custom property associated with a specified name. |
| [SetCustomPropertyValue](../../aspose.slides/idocumentproperties/setcustompropertyvalue#setcustompropertyvalue)(string, bool) | Sets a named boolean custom property. |
| [SetCustomPropertyValue](../../aspose.slides/idocumentproperties/setcustompropertyvalue#setcustompropertyvalue_4)(string, DateTime) | Sets a named DateTime custom property. |
| [SetCustomPropertyValue](../../aspose.slides/idocumentproperties/setcustompropertyvalue#setcustompropertyvalue_1)(string, double) | Sets a named double custom property. |
| [SetCustomPropertyValue](../../aspose.slides/idocumentproperties/setcustompropertyvalue#setcustompropertyvalue_3)(string, float) | Sets a named float custom property. |
| [SetCustomPropertyValue](../../aspose.slides/idocumentproperties/setcustompropertyvalue#setcustompropertyvalue_2)(string, int) | Sets a named integer custom property. |
| [SetCustomPropertyValue](../../aspose.slides/idocumentproperties/setcustompropertyvalue#setcustompropertyvalue_5)(string, string) | Sets a named string custom property. |

### See Also

* namespace [Aspose.Slides](../../aspose.slides)
* assembly [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->
