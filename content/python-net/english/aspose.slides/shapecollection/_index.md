﻿---
title: ShapeCollection class
second_title: Aspose.Slides for Python via .NET API Reference
description: 
type: docs
url: /aspose.slides/shapecollection/
---


## ShapeCollection class

Represents a collection of a shapes.

The ShapeCollection type exposes the following members:

## Properties

| Property | Description |
| :- | :- |
| [`parent_group`](/slides/python-net/aspose.slides/shapecollection/parent_group/) | Returns parent GroupShape object for a shapes collection.<br/>            Read-only [`IGroupShape`](/slides/python-net/aspose.slides/igroupshape). |

Gets the element at the specified index.
            Read-only [`IShape`](/slides/python-net/aspose.slides/ishape).

## Indexer

| Name | Description |
| :- | :- |
| [`[index]`](/slides/python-net/aspose.slides/shapecollection/__getitem__/) |  |

## Methods

| Method | Description |
| :- | :- |
| [`add_chart`](/slides/python-net/aspose.slides/shapecollection/add_chart/#asposeslideschartscharttype-float-float-float-float) | Creates a new Chart, initialize it with sample series data and settings and adds <br/>            it to the end of the collection. |
| [`add_chart`](/slides/python-net/aspose.slides/shapecollection/add_chart/#asposeslideschartscharttype-float-float-float-float-bool) | Creates a new Chart and adds it to the end of the collection. |
| [`insert_chart`](/slides/python-net/aspose.slides/shapecollection/insert_chart/#asposeslideschartscharttype-float-float-float-float-int) | Creates a new Chart, initialize it with sample series data and settings and inserts <br/>            it to the specified position in the collection. |
| [`insert_chart`](/slides/python-net/aspose.slides/shapecollection/insert_chart/#asposeslideschartscharttype-float-float-float-float-int-bool) | Creates a new Chart and inserts it to the specified position in the collection. |
| [`add_zoom_frame`](/slides/python-net/aspose.slides/shapecollection/add_zoom_frame/#float-float-float-float-islide) | Adds a new Zoom object to the end of a collection. |
| [`add_zoom_frame`](/slides/python-net/aspose.slides/shapecollection/add_zoom_frame/#float-float-float-float-islide-ippimage) | Adds a new Zoom object to the end of a collection. |
| [`insert_zoom_frame`](/slides/python-net/aspose.slides/shapecollection/insert_zoom_frame/#int-float-float-float-float-islide) | Creates a new Zoom object and inserts it to a collection at the specified index. |
| [`insert_zoom_frame`](/slides/python-net/aspose.slides/shapecollection/insert_zoom_frame/#int-float-float-float-float-islide-ippimage) | Creates a new Zoom object and inserts it to a collection at the specified index. |
| [`add_section_zoom_frame`](/slides/python-net/aspose.slides/shapecollection/add_section_zoom_frame/#float-float-float-float-isection) | Adds a new Section Zoom object to the end of a collection. |
| [`add_section_zoom_frame`](/slides/python-net/aspose.slides/shapecollection/add_section_zoom_frame/#float-float-float-float-isection-ippimage) | Adds a new Section Zoom object to the end of a collection with a predefined image. |
| [`insert_section_zoom_frame`](/slides/python-net/aspose.slides/shapecollection/insert_section_zoom_frame/#int-float-float-float-float-isection) | Creates a new Section Zoom object and inserts into to a collection at the specified index. |
| [`insert_section_zoom_frame`](/slides/python-net/aspose.slides/shapecollection/insert_section_zoom_frame/#int-float-float-float-float-isection-ippimage) | Creates a new Section Zoom object and inserts it to a collection at the specified index. |
| [`add_ole_object_frame`](/slides/python-net/aspose.slides/shapecollection/add_ole_object_frame/#float-float-float-float-ioleembeddeddatainfo) | Adds a new OLE object to the end of a collection. |
| [`add_ole_object_frame`](/slides/python-net/aspose.slides/shapecollection/add_ole_object_frame/#float-float-float-float-str-str) | Adds a new OLE object to the end of a collection. |
| [`insert_ole_object_frame`](/slides/python-net/aspose.slides/shapecollection/insert_ole_object_frame/#int-float-float-float-float-ioleembeddeddatainfo) | Creates a new OLE object and inserts it to a collection at the specified index. |
| [`insert_ole_object_frame`](/slides/python-net/aspose.slides/shapecollection/insert_ole_object_frame/#int-float-float-float-float-str-str) | Creates a new OLE object and inserts it to a collection at the specified index. |
| [`add_video_frame`](/slides/python-net/aspose.slides/shapecollection/add_video_frame/#float-float-float-float-str) | Adds a new video frame to the end of a collection. |
| [`add_video_frame`](/slides/python-net/aspose.slides/shapecollection/add_video_frame/#float-float-float-float-ivideo) | Adds a new video frame to the end of a collection. |
| [`add_audio_frame_embedded`](/slides/python-net/aspose.slides/shapecollection/add_audio_frame_embedded/#float-float-float-float-iorawiobase) | Adds a new audio frame with embedded audio file to the end of a collection.<br/>            Embedded audio file can be a WAV only.<br/>            It adds new audio into Presentation.Audios list. |
| [`add_audio_frame_embedded`](/slides/python-net/aspose.slides/shapecollection/add_audio_frame_embedded/#float-float-float-float-iaudio) | Adds a new audio frame with embedded audio file to the end of a collection.<br/>            It uses audio file from Presentation.Audios list. |
| [`insert_audio_frame_embedded`](/slides/python-net/aspose.slides/shapecollection/insert_audio_frame_embedded/#int-float-float-float-float-iorawiobase) | Insert an AudioFrame with embedded audio file.<br/>            Embedded audio file sound can be a WAV only. |
| [`insert_audio_frame_embedded`](/slides/python-net/aspose.slides/shapecollection/insert_audio_frame_embedded/#int-float-float-float-float-iaudio) | Insert an AudioFrame with embedded audio file.<br/>            It uses audio file from Presentation.Audios list. |
| [`to_array`](/slides/python-net/aspose.slides/shapecollection/to_array/#) | Creates and returns an array with all shapse in it. |
| [`to_array`](/slides/python-net/aspose.slides/shapecollection/to_array/#int-int) | Creates and returns an array with all shapes from the specified range in it.<br/>An index of a first shape to return.A number of shapes to return. |
| [`reorder`](/slides/python-net/aspose.slides/shapecollection/reorder/#int-ishape) | Moves a shape from the collection to the specified position. |
| [`reorder`](/slides/python-net/aspose.slides/shapecollection/reorder/#int-listishape) | Moves shapes from the collection to the specified position.<br/>            Shapes will be placed starting from index in order they appear in list. |
| [`add_auto_shape`](/slides/python-net/aspose.slides/shapecollection/add_auto_shape/#shapetype-float-float-float-float) | Creates a new AutoShape, tunes it from default template and adds it to the end of the collection. |
| [`add_auto_shape`](/slides/python-net/aspose.slides/shapecollection/add_auto_shape/#shapetype-float-float-float-float-bool) | Creates a new AutoShape and adds it to the end of the collection. |
| [`insert_auto_shape`](/slides/python-net/aspose.slides/shapecollection/insert_auto_shape/#int-shapetype-float-float-float-float) | Creates a new AutoShape, tunes it from default template and inserts it to <br/>            the collection at the specified index.<br/>            Note: the type of the shape will be determined by the shapeType parameter. |
| [`insert_auto_shape`](/slides/python-net/aspose.slides/shapecollection/insert_auto_shape/#int-shapetype-float-float-float-float-bool) | Creates a new AutoShape and inserts it to the collection at the specified index.<br/>            Note: the type of the shape will be determined by the shapeType parameter. |
| [`add_group_shape`](/slides/python-net/aspose.slides/shapecollection/add_group_shape/#) | Creates a new GroupShape and adds it to the end of the collection.<br/>            GroupShape frame size and position will be fitted to content when new shape will be added into the GroupShape. |
| [`add_group_shape`](/slides/python-net/aspose.slides/shapecollection/add_group_shape/#isvgimage-float-float-float-float) | Creates a new GroupShape, fills it with converted shapes from SVG and adds it to the end of the collection. |
| [`add_connector`](/slides/python-net/aspose.slides/shapecollection/add_connector/#shapetype-float-float-float-float) | Creates a new Connector, tunes it from default template and adds it to the end of the collection. |
| [`add_connector`](/slides/python-net/aspose.slides/shapecollection/add_connector/#shapetype-float-float-float-float-bool) | Creates a new Connector and adds it to the end of the collection. |
| [`insert_connector`](/slides/python-net/aspose.slides/shapecollection/insert_connector/#int-shapetype-float-float-float-float) | Creates a new Connector, tunes it from default template and inserts it to <br/>            the collection at the specified index. |
| [`insert_connector`](/slides/python-net/aspose.slides/shapecollection/insert_connector/#int-shapetype-float-float-float-float-bool) | Creates a new Connector and inserts it to the collection at the specified index. |
| [`add_clone`](/slides/python-net/aspose.slides/shapecollection/add_clone/#ishape-float-float-float-float) | Adds a copy of a specified shape to the end of the collection. |
| [`add_clone`](/slides/python-net/aspose.slides/shapecollection/add_clone/#ishape-float-float) | Adds a copy of a specified shape to the end of the collection.<br/>            Width and Height of the new shape are equal to Width and Height of the `source_shape`. |
| [`add_clone`](/slides/python-net/aspose.slides/shapecollection/add_clone/#ishape) | Adds a copy of a specified shape to the end of the collection.<br/>            X, Y, Width and Height of the new shape are equal to X, Y, Width and Height of the `source_shape`. |
| [`insert_clone`](/slides/python-net/aspose.slides/shapecollection/insert_clone/#int-ishape-float-float-float-float) | Inserts a copy of a specified shape to specified position of the collection. |
| [`insert_clone`](/slides/python-net/aspose.slides/shapecollection/insert_clone/#int-ishape-float-float) | Inserts a copy of a specified shape to specified position of the collection.<br/>            Width and Height of the new shape are equal to Width and Height of the `source_shape`. |
| [`insert_clone`](/slides/python-net/aspose.slides/shapecollection/insert_clone/#int-ishape) | Inserts a copy of a specified shape to specified position of the collection.<br/>            X, Y, Width and Height of the new shape are equal to X, Y, Width and Height of the `source_shape`. |
| [`add_smart_art`](/slides/python-net/aspose.slides/shapecollection/add_smart_art/#float-float-float-float-asposeslidessmartartsmartartlayouttype) | Add SmartArt diagram. |
| [`add_summary_zoom_frame`](/slides/python-net/aspose.slides/shapecollection/add_summary_zoom_frame/#float-float-float-float) | Adds a new Summary Zoom object to the end of a collection. |
| [`insert_summary_zoom_frame`](/slides/python-net/aspose.slides/shapecollection/insert_summary_zoom_frame/#int-float-float-float-float) | Creates a new Summary Zoom object and inserts it to a collection at the specified index. |
| [`insert_video_frame`](/slides/python-net/aspose.slides/shapecollection/insert_video_frame/#int-float-float-float-float-str) | Creates a new video frame and inserts it to a collection at the specified index. |
| [`add_audio_frame_cd`](/slides/python-net/aspose.slides/shapecollection/add_audio_frame_cd/#float-float-float-float) | Adds an AudioFrame with CD to the end of collection. |
| [`insert_audio_frame_cd`](/slides/python-net/aspose.slides/shapecollection/insert_audio_frame_cd/#int-float-float-float-float) | Insert an AudioFrame with CD. |
| [`add_audio_frame_linked`](/slides/python-net/aspose.slides/shapecollection/add_audio_frame_linked/#float-float-float-float-str) | Adds a new audio frame with linked audio file to the end of a collection. |
| [`insert_audio_frame_linked`](/slides/python-net/aspose.slides/shapecollection/insert_audio_frame_linked/#int-float-float-float-float-str) | Creates a new audio frame with linked audio file and inserts it to a collection at the specified index. |
| [`index_of`](/slides/python-net/aspose.slides/shapecollection/index_of/#ishape) | Returns the zero-based index of the first occurrence of a shape in the collection. |
| [`add_math_shape`](/slides/python-net/aspose.slides/shapecollection/add_math_shape/#float-float-float-float) | Creates a new Autoshape tuned from default template to math content and adds it to the end of the collection. |
| [`insert_group_shape`](/slides/python-net/aspose.slides/shapecollection/insert_group_shape/#int) | Creates a new GroupShape and inserts it to the collection at the specified index.<br/>            GroupShape frame size and position will be fitted to content when new shape will be added into the GroupShape. |
| [`add_picture_frame`](/slides/python-net/aspose.slides/shapecollection/add_picture_frame/#shapetype-float-float-float-float-ippimage) | Creates a new PictureFrame and adds it to the end of the collection. |
| [`insert_picture_frame`](/slides/python-net/aspose.slides/shapecollection/insert_picture_frame/#int-shapetype-float-float-float-float-ippimage) | Creates a new PictureFrame and inserts it to the collection at the specified index. |
| [`add_table`](/slides/python-net/aspose.slides/shapecollection/add_table/#float-float-listfloat-listfloat) | Creates a new Table and adds it to the end of the collection. |
| [`insert_table`](/slides/python-net/aspose.slides/shapecollection/insert_table/#int-float-float-listfloat-listfloat) | Creates a new Table and inserts it to the collection at the specified index. |
| [`remove_at`](/slides/python-net/aspose.slides/shapecollection/remove_at/#int) | Removes the element at the specified index of the collection. |
| [`remove`](/slides/python-net/aspose.slides/shapecollection/remove/#ishape) | Removes the first occurrence of a specific shape from the collection. |
| [`clear`](/slides/python-net/aspose.slides/shapecollection/clear/#) | Removes all shapes from the collection. |


### See Also
* class [`IShape`](/slides/python-net/aspose.slides/ishape)
* module [`aspose.slides`](/slides/python-net/aspose.slides)
* library [`Aspose.Slides`](/slides/python-net)

