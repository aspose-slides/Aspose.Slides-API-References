---
title: IDocumentProperties class
second_title: Aspose.Slides for Python via .NET API Reference
description: 
type: docs
url: /aspose.slides/idocumentproperties/
---


## IDocumentProperties class

Represents properties of a presentation.

The IDocumentProperties type exposes the following members:

## Properties

| Property | Description |
| :- | :- |
| [`app_version`](/slides/python-net/aspose.slides/idocumentproperties/app_version/) | Returns the app version.<br/>            Read-only **str**. |
| [`name_of_application`](/slides/python-net/aspose.slides/idocumentproperties/name_of_application/) | Returns or sets the name of the application.<br/>            Read/write **str**. |
| [`company`](/slides/python-net/aspose.slides/idocumentproperties/company/) | Returns or sets the company property.<br/>            Read/write **str**. |
| [`manager`](/slides/python-net/aspose.slides/idocumentproperties/manager/) | Returns or sets the manager property.<br/>            Read/write **str**. |
| [`presentation_format`](/slides/python-net/aspose.slides/idocumentproperties/presentation_format/) | Returns or sets the intended format of a presentation.<br/>            Read/write **str**. |
| [`shared_doc`](/slides/python-net/aspose.slides/idocumentproperties/shared_doc/) | Determines whether the presentation is shared between multiple people.<br/>            Read/write **bool**. |
| [`application_template`](/slides/python-net/aspose.slides/idocumentproperties/application_template/) | Returns or sets the template of a application.<br/>            Read/write **str**. |
| [`total_editing_time`](/slides/python-net/aspose.slides/idocumentproperties/total_editing_time/) | Total editing time of a presentation.<br/>            Read/write **System.TimeSpan**. |
| [`title`](/slides/python-net/aspose.slides/idocumentproperties/title/) | Returns or sets the title of a presentation.<br/>            Read/write **str**. |
| [`subject`](/slides/python-net/aspose.slides/idocumentproperties/subject/) | Returns or sets the subject of a presentation.<br/>            Read/write **str**. |
| [`author`](/slides/python-net/aspose.slides/idocumentproperties/author/) | Returns or sets the author of a presentation.<br/>            Read/write **str**. |
| [`keywords`](/slides/python-net/aspose.slides/idocumentproperties/keywords/) | Returns or sets the keywords of a presentation.<br/>            Read/write **str**. |
| [`comments`](/slides/python-net/aspose.slides/idocumentproperties/comments/) | Returns or sets the comments of a presentation.<br/>            Read/write **str**. |
| [`category`](/slides/python-net/aspose.slides/idocumentproperties/category/) | Returns or sets the category of a presentation.<br/>            Read/write **str**. |
| [`created_time`](/slides/python-net/aspose.slides/idocumentproperties/created_time/) | Returns the date a presentation was created. <br/>            Values are in UTC.<br/>            Read/write **System.DateTime**. |
| [`last_saved_time`](/slides/python-net/aspose.slides/idocumentproperties/last_saved_time/) | Returns the date a presentation was last modified.<br/>            Values are in UTC.P<br/>            Read-only in case of Presentation.DocumentProperties (because it will be updated internally while IPresentation object saving process). <br/>            Can be changed via DocumentProperties instance returning by method [`IPresentationInfo.read_document_properties`](/slides/python-net/aspose.slides/ipresentationinfo/read_document_properties)<br/>Please see the example in **Aspose.Slides.IPresentationInfo.UpdateDocumentProperties(Aspose.Slide** method summary. |
| [`last_printed`](/slides/python-net/aspose.slides/idocumentproperties/last_printed/) | Returns the date when a presentation was printed last time.<br/>            Read/write **System.DateTime**. |
| [`last_saved_by`](/slides/python-net/aspose.slides/idocumentproperties/last_saved_by/) | Returns or sets the name of a last person who modified a presentation.<br/>            Read/write **str**. |
| [`revision_number`](/slides/python-net/aspose.slides/idocumentproperties/revision_number/) | Returns or sets the presentation revision number.<br/>            Read/write **int**. |
| [`content_status`](/slides/python-net/aspose.slides/idocumentproperties/content_status/) | Returns or sets the content status of a presentation.<br/>            Read/write **str**. |
| [`content_type`](/slides/python-net/aspose.slides/idocumentproperties/content_type/) | Returns or sets the content type of a presentation.<br/>            Read/write **str**. |
| [`hyperlink_base`](/slides/python-net/aspose.slides/idocumentproperties/hyperlink_base/) | Returns or sets the HyperlinkBase document property.<br/>            Read/write **str**. |
| [`count_of_custom_properties`](/slides/python-net/aspose.slides/idocumentproperties/count_of_custom_properties/) | Returns the number of custom properties actually contained in a collection.<br/>            Read-only **int**. |

## Methods

| Method | Description |
| :- | :- |
| [`get_custom_property_value`](/slides/python-net/aspose.slides/idocumentproperties/get_custom_property_value/#str-any) | Gets a named boolean value from the custom properties. |
| [`get_custom_property_value`](/slides/python-net/aspose.slides/idocumentproperties/get_custom_property_value/#str-any) | Gets a named integer value from the custom properties. |
| [`get_custom_property_value`](/slides/python-net/aspose.slides/idocumentproperties/get_custom_property_value/#str-any) | Gets a named DateTime value from the custom properties. |
| [`get_custom_property_value`](/slides/python-net/aspose.slides/idocumentproperties/get_custom_property_value/#str-any) |  |
| [`get_custom_property_value`](/slides/python-net/aspose.slides/idocumentproperties/get_custom_property_value/#str-any) |  |
| [`get_custom_property_value`](/slides/python-net/aspose.slides/idocumentproperties/get_custom_property_value/#str-any) |  |
| [`set_custom_property_value`](/slides/python-net/aspose.slides/idocumentproperties/set_custom_property_value/#str-bool) | Sets a named boolean custom property. |
| [`set_custom_property_value`](/slides/python-net/aspose.slides/idocumentproperties/set_custom_property_value/#str-int) | Sets a named integer custom property. |
| [`set_custom_property_value`](/slides/python-net/aspose.slides/idocumentproperties/set_custom_property_value/#str-datetime) | Sets a named DateTime custom property. |
| [`set_custom_property_value`](/slides/python-net/aspose.slides/idocumentproperties/set_custom_property_value/#str-str) | Sets a named string custom property. |
| [`set_custom_property_value`](/slides/python-net/aspose.slides/idocumentproperties/set_custom_property_value/#str-float) | Sets a named float custom property. |
| [`set_custom_property_value`](/slides/python-net/aspose.slides/idocumentproperties/set_custom_property_value/#str-float) | Sets a named double custom property. |
| [`get_custom_property_name`](/slides/python-net/aspose.slides/idocumentproperties/get_custom_property_name/#int) | Return a custom property name at the specified index. |
| [`remove_custom_property`](/slides/python-net/aspose.slides/idocumentproperties/remove_custom_property/#str) | Remove a custom property associated with a specified name. |
| [`contains_custom_property`](/slides/python-net/aspose.slides/idocumentproperties/contains_custom_property/#str) | Check presents of a custom property with a specified name. |
| [`clear_custom_properties`](/slides/python-net/aspose.slides/idocumentproperties/clear_custom_properties/#) | Removes all custom properties. |
| [`clear_built_in_properties`](/slides/python-net/aspose.slides/idocumentproperties/clear_built_in_properties/#) | Clears and sets default values for all builtIn properties. |


### See Also
* module [`aspose.slides`](/slides/python-net/aspose.slides)
* library [`Aspose.Slides`](/slides/python-net)

