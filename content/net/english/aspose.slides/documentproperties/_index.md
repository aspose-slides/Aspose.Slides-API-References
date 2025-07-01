---
title: DocumentProperties
second_title: Aspose.Sildes for .NET API Reference
description: Represents properties of a presentation.
type: docs
weight: 2760
url: /aspose.slides/documentproperties/
---

## DocumentProperties class

Represents properties of a presentation.

```csharp
public class DocumentProperties : IDocumentProperties, IGenericCloneable<IDocumentProperties>
```

## Constructors

| Name | Description |
| --- | --- |
| [DocumentProperties](documentproperties)() | Initializes new instance of class [`DocumentProperties`](../documentproperties). |

## Properties

| Name | Description |
| --- | --- |
| [ApplicationTemplate](../../aspose.slides/documentproperties/applicationtemplate) { get; set; } | Returns or sets the template of a application. Read/write String. |
| [AppVersion](../../aspose.slides/documentproperties/appversion) { get; } | Returns the app version. Read-only String. |
| [Author](../../aspose.slides/documentproperties/author) { get; set; } | Returns or sets the author of a presentation. Read/write String. |
| [Category](../../aspose.slides/documentproperties/category) { get; set; } | Returns or sets the category of a presentation. Read/write String. |
| [Comments](../../aspose.slides/documentproperties/comments) { get; set; } | Returns or sets the comments of a presentation. Read/write String. |
| [Company](../../aspose.slides/documentproperties/company) { get; set; } | Returns or sets the company property. Read/write String. |
| [ContentStatus](../../aspose.slides/documentproperties/contentstatus) { get; set; } | Returns or sets the content status of a presentation. Read/write String. |
| [ContentType](../../aspose.slides/documentproperties/contenttype) { get; set; } | Returns or sets the content type of a presentation. Read/write String. |
| [CountOfCustomProperties](../../aspose.slides/documentproperties/countofcustomproperties) { get; } | Returns the number of custom properties actually contained in a collection. Read-only Int32. |
| [CreatedTime](../../aspose.slides/documentproperties/createdtime) { get; set; } | Returns the date a presentation was created. Values are in UTC. Read/write DateTime. |
| [HeadingPairs](../../aspose.slides/documentproperties/headingpairs) { get; } | Indicates the grouping of document parts and the number of parts in each group. Read-only IHeadingPair[]. |
| [HiddenSlides](../../aspose.slides/documentproperties/hiddenslides) { get; } | Returns the number of hidden slides in a presentation document. Read-only Int32. |
| [HyperlinkBase](../../aspose.slides/documentproperties/hyperlinkbase) { get; set; } | Returns or sets the HyperlinkBase document property. Read/write String. |
| [HyperlinksChanged](../../aspose.slides/documentproperties/hyperlinkschanged) { get; set; } | Specifies that one or more hyperlinks in this part were updated exclusively in this part by a producer. The next producer to open this document shall update the hyperlink relationships with the new hyperlinks specified in this part. Read/write Boolean. |
| [Item](../../aspose.slides/documentproperties/item) { get; set; } | Returns or sets the custom property associated with a specified name. Read/write Object. |
| [Keywords](../../aspose.slides/documentproperties/keywords) { get; set; } | Returns or sets the keywords of a presentation. Read/write String. |
| [LastPrinted](../../aspose.slides/documentproperties/lastprinted) { get; set; } | Returns the date when a presentation was printed last time. Read/write DateTime. |
| [LastSavedBy](../../aspose.slides/documentproperties/lastsavedby) { get; set; } | Returns or sets the name of a last person who modified a presentation. Read/write String. |
| [LastSavedTime](../../aspose.slides/documentproperties/lastsavedtime) { get; set; } | Returns the date a presentation was last modified. Values are in UTC. Read-only in case of Presentation.DocumentProperties (because it will be updated internally while IPresentation object saving process). Can be changed via DocumentProperties instance returning by method [`ReadDocumentProperties`](../ipresentationinfo/readdocumentproperties) Please see the example in [`UpdateDocumentProperties`](../ipresentationinfo/updatedocumentproperties) method summary. |
| [LinksUpToDate](../../aspose.slides/documentproperties/linksuptodate) { get; set; } | Indicates whether hyperlinks in a document are up-to-date. Set this element to **true** to indicate that hyperlinks are updated. Set this element to **false** to indicate that hyperlinks are outdated. Read/write Boolean. |
| [Manager](../../aspose.slides/documentproperties/manager) { get; set; } | Returns or sets the manager property. Read/write String. |
| [MultimediaClips](../../aspose.slides/documentproperties/multimediaclips) { get; } | Returns the total number of sound or video clips that are present in the document. Read-only Int32. |
| [NameOfApplication](../../aspose.slides/documentproperties/nameofapplication) { get; set; } | Returns or sets the name of the application. Read/write String. |
| [Notes](../../aspose.slides/documentproperties/notes) { get; } | Returns the number of slides in a presentation containing notes. Read-only Int32. |
| [Paragraphs](../../aspose.slides/documentproperties/paragraphs) { get; } | Returns the total number of paragraphs found in a document if applicable. Read-only Int32. |
| [PresentationFormat](../../aspose.slides/documentproperties/presentationformat) { get; set; } | Returns or sets the intended format of a presentation. Read/write String. |
| [RevisionNumber](../../aspose.slides/documentproperties/revisionnumber) { get; set; } | Returns or sets the presentation revision number. Read/write Int32. |
| [ScaleCrop](../../aspose.slides/documentproperties/scalecrop) { get; set; } | Indicates the display mode of the document thumbnail. Set this element to **true** to enable scaling of the document thumbnail to the display. Set this element to **false** to enable cropping of the document thumbnail to show only sections that fits the display. Read/write Boolean. |
| [SharedDoc](../../aspose.slides/documentproperties/shareddoc) { get; set; } | Determines whether the presentation is shared between multiple people. Read/write Boolean. |
| [Slides](../../aspose.slides/documentproperties/slides) { get; } | Returns the total number of slides in a presentation document. Read-only Int32. |
| [Subject](../../aspose.slides/documentproperties/subject) { get; set; } | Returns or sets the subject of a presentation. Read/write String. |
| [Title](../../aspose.slides/documentproperties/title) { get; set; } | Returns or sets the title of a presentation. Read/write String. |
| [TitlesOfParts](../../aspose.slides/documentproperties/titlesofparts) { get; } | Specifies the title of each document part. These parts are not document parts but conceptual representations of document sections. Read-only string[]. |
| [TotalEditingTime](../../aspose.slides/documentproperties/totaleditingtime) { get; set; } | Total editing time of a presentation. Read/write TimeSpan. |
| [Words](../../aspose.slides/documentproperties/words) { get; } | Returns the total number of words contained in a document. Read-only Int32. |

## Methods

| Name | Description |
| --- | --- |
| [ClearBuiltInProperties](../../aspose.slides/documentproperties/clearbuiltinproperties)() | Clears and sets default values for all builtIn properties. |
| [ClearCustomProperties](../../aspose.slides/documentproperties/clearcustomproperties)() | Removes all custom properties. |
| [Clone](../../aspose.slides/documentproperties/clone)() | Clones current object |
| [CloneT](../../aspose.slides/documentproperties/clonet)() | Clones current object |
| [ContainsCustomProperty](../../aspose.slides/documentproperties/containscustomproperty)(string) | Check presents of a custom property with a specified name. |
| [GetCustomPropertyName](../../aspose.slides/documentproperties/getcustompropertyname)(int) | Return a custom property name at the specified index. |
| [GetCustomPropertyValue](../../aspose.slides/documentproperties/getcustompropertyvalue#getcustompropertyvalue)(string, out bool) | Gets a named boolean value from the custom properties. |
| [GetCustomPropertyValue](../../aspose.slides/documentproperties/getcustompropertyvalue#getcustompropertyvalue_4)(string, out DateTime) | Gets a named DateTime value from the custom properties. |
| [GetCustomPropertyValue](../../aspose.slides/documentproperties/getcustompropertyvalue#getcustompropertyvalue_1)(string, out double) | Gets a named double value from the custom properties. |
| [GetCustomPropertyValue](../../aspose.slides/documentproperties/getcustompropertyvalue#getcustompropertyvalue_3)(string, out float) | Gets a named float value from the custom properties. |
| [GetCustomPropertyValue](../../aspose.slides/documentproperties/getcustompropertyvalue#getcustompropertyvalue_2)(string, out int) | Gets a named integer value from the custom properties. |
| [GetCustomPropertyValue](../../aspose.slides/documentproperties/getcustompropertyvalue#getcustompropertyvalue_5)(string, out string) | Gets a named string value from the custom properties. |
| [RemoveCustomProperty](../../aspose.slides/documentproperties/removecustomproperty)(string) | Remove a custom property associated with a specified name. |
| [SetCustomPropertyValue](../../aspose.slides/documentproperties/setcustompropertyvalue#setcustompropertyvalue)(string, bool) | Sets a named boolean custom property. |
| [SetCustomPropertyValue](../../aspose.slides/documentproperties/setcustompropertyvalue#setcustompropertyvalue_4)(string, DateTime) | Sets a named DateTime custom property. |
| [SetCustomPropertyValue](../../aspose.slides/documentproperties/setcustompropertyvalue#setcustompropertyvalue_1)(string, double) | Sets a named double custom property. |
| [SetCustomPropertyValue](../../aspose.slides/documentproperties/setcustompropertyvalue#setcustompropertyvalue_3)(string, float) | Sets a named float custom property. |
| [SetCustomPropertyValue](../../aspose.slides/documentproperties/setcustompropertyvalue#setcustompropertyvalue_2)(string, int) | Sets a named integer custom property. |
| [SetCustomPropertyValue](../../aspose.slides/documentproperties/setcustompropertyvalue#setcustompropertyvalue_5)(string, string) | Sets a named string custom property. |

### Examples

The following example shows how to access built-in Properties of PowerPoint Presentation.

```csharp
[C#]
// Instantiate the Presentation class that represents the presentation
using (Presentation pres = new Presentation(dataDir + "AccessBuiltin Properties.pptx"))
{
	// Create a reference to IDocumentProperties object associated with Presentation
	IDocumentProperties documentProperties = pres.DocumentProperties;
	// Display the builtin properties
	Console.WriteLine("Category : " + documentProperties.Category);
	Console.WriteLine("Current Status : " + documentProperties.ContentStatus);
	Console.WriteLine("Creation Date : " + documentProperties.CreatedTime);
	Console.WriteLine("Author : " + documentProperties.Author);
	Console.WriteLine("Description : " + documentProperties.Comments);
}
```

The following example shows how to modify built-in Properties of PowerPoint Presentation.

```csharp
[C#]
// Instantiate the Presentation class that represents the Presentation
using (Presentation presentation = new Presentation(dataDir + "ModifyBuiltinProperties.pptx"))
{
	// Create a reference to IDocumentProperties object associated with Presentation
	IDocumentProperties documentProperties = presentation.DocumentProperties;
	// Set the builtin properties
	documentProperties.Author = "Aspose.Slides for .NET";
	documentProperties.Title = "Modifying Presentation Properties";
	documentProperties.Subject = "Aspose Subject";
	// Save your presentation to a file
	presentation.Save(dataDir + "DocumentProperties_out.pptx", SaveFormat.Pptx);
}
```

### See Also

* interface [IDocumentProperties](../idocumentproperties)
* interface [IGenericCloneable&lt;T&gt;](../igenericcloneable-1)
* namespace [Aspose.Slides](../../aspose.slides)
* assembly [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->
