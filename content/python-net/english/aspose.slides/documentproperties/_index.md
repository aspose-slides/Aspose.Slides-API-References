﻿---
title: DocumentProperties class
second_title: Aspose.Slides for Python via .NET API Reference
description: 
type: docs
url: /aspose.slides/documentproperties/
---


## DocumentProperties class

Represents properties of a presentation.

The DocumentProperties type exposes the following members:

## Constructors

| Constructor | Description |
| :- | :- |
| [`__init__`](/slides/python-net/aspose.slides/documentproperties/__init__/#) | Initializes new instance of class [`DocumentProperties`](/slides/python-net/aspose.slides/documentproperties). |

## Properties

| Property | Description |
| :- | :- |
| [`app_version`](/slides/python-net/aspose.slides/documentproperties/app_version/) | Returns the app version.<br/>            Read-only **str**. |
| [`name_of_application`](/slides/python-net/aspose.slides/documentproperties/name_of_application/) | Returns or sets the name of the application.<br/>            Read/write **str**. |
| [`company`](/slides/python-net/aspose.slides/documentproperties/company/) | Returns or sets the company property.<br/>            Read/write **str**. |
| [`manager`](/slides/python-net/aspose.slides/documentproperties/manager/) | Returns or sets the manager property.<br/>            Read/write **str**. |
| [`presentation_format`](/slides/python-net/aspose.slides/documentproperties/presentation_format/) | Returns or sets the intended format of a presentation.<br/>            Read/write **str**. |
| [`shared_doc`](/slides/python-net/aspose.slides/documentproperties/shared_doc/) | Determines whether the presentation is shared between multiple people.<br/>            Read/write **bool**. |
| [`application_template`](/slides/python-net/aspose.slides/documentproperties/application_template/) | Returns or sets the template of a application.<br/>            Read/write **str**. |
| [`total_editing_time`](/slides/python-net/aspose.slides/documentproperties/total_editing_time/) | Total editing time of a presentation.<br/>            Read/write **System.TimeSpan**. |
| [`title`](/slides/python-net/aspose.slides/documentproperties/title/) | Returns or sets the title of a presentation.<br/>            Read/write **str**. |
| [`subject`](/slides/python-net/aspose.slides/documentproperties/subject/) | Returns or sets the subject of a presentation.<br/>            Read/write **str**. |
| [`author`](/slides/python-net/aspose.slides/documentproperties/author/) | Returns or sets the author of a presentation.<br/>            Read/write **str**. |
| [`keywords`](/slides/python-net/aspose.slides/documentproperties/keywords/) | Returns or sets the keywords of a presentation.<br/>            Read/write **str**. |
| [`comments`](/slides/python-net/aspose.slides/documentproperties/comments/) | Returns or sets the comments of a presentation.<br/>            Read/write **str**. |
| [`category`](/slides/python-net/aspose.slides/documentproperties/category/) | Returns or sets the category of a presentation.<br/>            Read/write **str**. |
| [`created_time`](/slides/python-net/aspose.slides/documentproperties/created_time/) | Returns the date a presentation was created.<br/>            Values are in UTC.<br/>            Read/write **System.DateTime**. |
| [`last_saved_time`](/slides/python-net/aspose.slides/documentproperties/last_saved_time/) | Returns the date a presentation was last modified.<br/>            Values are in UTC.<br/>            Read-only in case of Presentation.DocumentProperties (because it will be updated internally while IPresentation object saving process). <br/>            Can be changed via DocumentProperties instance returning by method [`IPresentationInfo.read_document_properties`](/slides/python-net/aspose.slides/ipresentationinfo/read_document_properties)<br/>            Please see the example in [`IPresentationInfo.update_document_properties`](/slides/python-net/aspose.slides/ipresentationinfo/update_document_properties) method summary. |
| [`last_printed`](/slides/python-net/aspose.slides/documentproperties/last_printed/) | Returns the date when a presentation was printed last time.<br/>            Read/write **System.DateTime**. |
| [`last_saved_by`](/slides/python-net/aspose.slides/documentproperties/last_saved_by/) | Returns or sets the name of a last person who modified a presentation.<br/>            Read/write **str**. |
| [`revision_number`](/slides/python-net/aspose.slides/documentproperties/revision_number/) | Returns or sets the presentation revision number.<br/>            Read/write **int**. |
| [`content_status`](/slides/python-net/aspose.slides/documentproperties/content_status/) | Returns or sets the content status of a presentation.<br/>            Read/write **str**. |
| [`content_type`](/slides/python-net/aspose.slides/documentproperties/content_type/) | Returns or sets the content type of a presentation.<br/>            Read/write **str**. |
| [`hyperlink_base`](/slides/python-net/aspose.slides/documentproperties/hyperlink_base/) | Returns or sets the HyperlinkBase document property.<br/>            Read/write **str**. |
| [`count_of_custom_properties`](/slides/python-net/aspose.slides/documentproperties/count_of_custom_properties/) | Returns the number of custom properties actually contained in a collection.<br/>            Read-only **int**. |
| [`scale_crop`](/slides/python-net/aspose.slides/documentproperties/scale_crop/) | Indicates the display mode of the document thumbnail. <br/>            Set this element to **true**  to enable scaling of the document thumbnail to the display. <br/>            Set this element to **false**  to enable cropping of the document thumbnail to show only sections that fits the display.<br/>            Read/write **bool**. |
| [`links_up_to_date`](/slides/python-net/aspose.slides/documentproperties/links_up_to_date/) | Indicates whether hyperlinks in a document are up-to-date. <br/>            Set this element to **true**  to indicate that hyperlinks are updated. <br/>            Set this element to **false**  to indicate that hyperlinks are outdated.<br/>            Read/write **bool**. |
| [`hyperlinks_changed`](/slides/python-net/aspose.slides/documentproperties/hyperlinks_changed/) | Specifies that one or more hyperlinks in this part were updated exclusively in this part by a producer. <br/>            The next producer to open this document shall update the hyperlink relationships with the new hyperlinks specified in this part.<br/>            Read/write **bool**. |
| [`slides`](/slides/python-net/aspose.slides/documentproperties/slides/) | Returns the total number of slides in a presentation document.<br/>            Read-only **int**. |
| [`hidden_slides`](/slides/python-net/aspose.slides/documentproperties/hidden_slides/) | Returns the number of hidden slides in a presentation document.<br/>            Read-only **int**. |
| [`notes`](/slides/python-net/aspose.slides/documentproperties/notes/) | Returns the number of slides in a presentation containing notes.<br/>            Read-only **int**. |
| [`paragraphs`](/slides/python-net/aspose.slides/documentproperties/paragraphs/) | Returns the total number of paragraphs found in a document if applicable.<br/>            Read-only **int**. |
| [`words`](/slides/python-net/aspose.slides/documentproperties/words/) | Returns the total number of words contained in a document.<br/>            Read-only **int**. |
| [`multimedia_clips`](/slides/python-net/aspose.slides/documentproperties/multimedia_clips/) | Returns the total number of sound or video clips that are present in the document.<br/>            Read-only **int**. |
| [`titles_of_parts`](/slides/python-net/aspose.slides/documentproperties/titles_of_parts/) | Specifies the title of each document part. <br/>            These parts are not document parts but conceptual representations of document sections.<br/>            Read-only **List[str]**. |
| [`heading_pairs`](/slides/python-net/aspose.slides/documentproperties/heading_pairs/) | Indicates the grouping of document parts and the number of parts in each group.<br/>            Read-only **List[IHeadingPair]**. |

## Methods

| Method | Description |
| :- | :- |
| [`get_custom_property_value`](/slides/python-net/aspose.slides/documentproperties/get_custom_property_value/#str-any) | Gets a named boolean value from the custom properties. |
| [`get_custom_property_value`](/slides/python-net/aspose.slides/documentproperties/get_custom_property_value/#str-any) | Gets a named integer value from the custom properties. |
| [`get_custom_property_value`](/slides/python-net/aspose.slides/documentproperties/get_custom_property_value/#str-any) | Gets a named DateTime value from the custom properties. |
| [`get_custom_property_value`](/slides/python-net/aspose.slides/documentproperties/get_custom_property_value/#str-any) |  |
| [`get_custom_property_value`](/slides/python-net/aspose.slides/documentproperties/get_custom_property_value/#str-any) |  |
| [`get_custom_property_value`](/slides/python-net/aspose.slides/documentproperties/get_custom_property_value/#str-any) |  |
| [`set_custom_property_value`](/slides/python-net/aspose.slides/documentproperties/set_custom_property_value/#str-bool) | Sets a named boolean custom property. |
| [`set_custom_property_value`](/slides/python-net/aspose.slides/documentproperties/set_custom_property_value/#str-int) | Sets a named integer custom property. |
| [`set_custom_property_value`](/slides/python-net/aspose.slides/documentproperties/set_custom_property_value/#str-datetime) | Sets a named DateTime custom property. |
| [`set_custom_property_value`](/slides/python-net/aspose.slides/documentproperties/set_custom_property_value/#str-str) | Sets a named string custom property. |
| [`set_custom_property_value`](/slides/python-net/aspose.slides/documentproperties/set_custom_property_value/#str-float) | Sets a named float custom property. |
| [`set_custom_property_value`](/slides/python-net/aspose.slides/documentproperties/set_custom_property_value/#str-float) | Sets a named double custom property. |
| [`get_custom_property_name`](/slides/python-net/aspose.slides/documentproperties/get_custom_property_name/#int) | Return a custom property name at the specified index. |
| [`remove_custom_property`](/slides/python-net/aspose.slides/documentproperties/remove_custom_property/#str) | Remove a custom property associated with a specified name. |
| [`contains_custom_property`](/slides/python-net/aspose.slides/documentproperties/contains_custom_property/#str) | Check presents of a custom property with a specified name. |
| [`clear_custom_properties`](/slides/python-net/aspose.slides/documentproperties/clear_custom_properties/#) | Removes all custom properties. |
| [`clear_built_in_properties`](/slides/python-net/aspose.slides/documentproperties/clear_built_in_properties/#) | Clears and sets default values for all builtIn properties. |
| [`clone`](/slides/python-net/aspose.slides/documentproperties/clone/#) | Clones current object |
| [`clone_t`](/slides/python-net/aspose.slides/documentproperties/clone_t/#) | Clones current object |


### Examples

The following example shows how to access built-in Properties of PowerPoint Presentation.

            The following example shows how to modify built-in Properties of PowerPoint Presentation.


### See Also
* class [`DocumentProperties`](/slides/python-net/aspose.slides/documentproperties)
* module [`aspose.slides`](/slides/python-net/aspose.slides)
* library [`Aspose.Slides`](/slides/python-net)

