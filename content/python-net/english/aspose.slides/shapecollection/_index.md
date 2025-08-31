---
title: ShapeCollection class
second_title: Aspose.Slides for Python via .NET API Reference
description: 
type: docs
url: /aspose.slides/shapecollection/
---


## ShapeCollection class

Represents a collection of shapes.

The ShapeCollection type exposes the following members:

## Properties

| Property | Description |
| :- | :- |
| [`parent_group`](/slides/python-net/aspose.slides/shapecollection/parent_group/) | Gets the parent group shape object for the shapes collection.<br/>            Read-only [`IGroupShape`](/slides/python-net/aspose.slides/igroupshape). |

Gets the element at the specified index.
            Read-only [`IShape`](/slides/python-net/aspose.slides/ishape).

## Indexer

| Name | Description |
| :- | :- |
| [`[index]`](/slides/python-net/aspose.slides/shapecollection/__getitem__/) |  |

## Methods

| Method | Description |
| :- | :- |
| [`add_chart`](/slides/python-net/aspose.slides/shapecollection/add_chart/#asposeslideschartscharttype-float-float-float-float) | Creates a new chart, initializes it with sample series data and settings, and adds<br/>            it to the end of the shape collection. |
| [`add_chart`](/slides/python-net/aspose.slides/shapecollection/add_chart/#asposeslideschartscharttype-float-float-float-float-bool) | Creates a new chart, initializes it with sample series data and settings, and adds<br/>            it to the end of the shape collection. |
| [`insert_chart`](/slides/python-net/aspose.slides/shapecollection/insert_chart/#asposeslideschartscharttype-float-float-float-float-int) | Creates a new chart, initializes it with sample series data and settings,<br/>            and inserts it into the shape collection at the specified index. |
| [`insert_chart`](/slides/python-net/aspose.slides/shapecollection/insert_chart/#asposeslideschartscharttype-float-float-float-float-int-bool) | Creates a new chart, initializes it with sample series data and settings,<br/>            and inserts it into the shape collection at the specified index. |
| [`add_zoom_frame`](/slides/python-net/aspose.slides/shapecollection/add_zoom_frame/#float-float-float-float-asposeslidesislide) | Creates a new Zoom frame and adds it to the end of the shape collection. |
| [`add_zoom_frame`](/slides/python-net/aspose.slides/shapecollection/add_zoom_frame/#float-float-float-float-asposeslidesislide-asposeslidesippimage) | Creates a new Zoom frame and adds it to the end of the shape collection. |
| [`insert_zoom_frame`](/slides/python-net/aspose.slides/shapecollection/insert_zoom_frame/#int-float-float-float-float-asposeslidesislide) | Creates a new Zoom frame and inserts it into the shape collection at the specified index. |
| [`insert_zoom_frame`](/slides/python-net/aspose.slides/shapecollection/insert_zoom_frame/#int-float-float-float-float-asposeslidesislide-asposeslidesippimage) | Creates a new Zoom frame with a predefined image and inserts it into the shape collection<br/>            at the specified index. |
| [`add_section_zoom_frame`](/slides/python-net/aspose.slides/shapecollection/add_section_zoom_frame/#float-float-float-float-asposeslidesisection) | Creates a new Section Zoom frame and adds it to the end of the shape collection. |
| [`add_section_zoom_frame`](/slides/python-net/aspose.slides/shapecollection/add_section_zoom_frame/#float-float-float-float-asposeslidesisection-asposeslidesippimage) | Creates a new Section Zoom frame with a predefined image and adds it to the end of the shape collection. |
| [`insert_section_zoom_frame`](/slides/python-net/aspose.slides/shapecollection/insert_section_zoom_frame/#int-float-float-float-float-asposeslidesisection) | Creates a new Section Zoom frame and inserts it into to the shape collection at the specified index. |
| [`insert_section_zoom_frame`](/slides/python-net/aspose.slides/shapecollection/insert_section_zoom_frame/#int-float-float-float-float-asposeslidesisection-asposeslidesippimage) | Creates a new Section Zoom frame with a predefined image and inserts it into to the shape<br/>            collection at the specified index. |
| [`add_ole_object_frame`](/slides/python-net/aspose.slides/shapecollection/add_ole_object_frame/#float-float-float-float-asposeslidesioleembeddeddatainfo) | Creates a new OLE object frame and adds it to the end of the shape collection. |
| [`add_ole_object_frame`](/slides/python-net/aspose.slides/shapecollection/add_ole_object_frame/#float-float-float-float-str-str) | Creates a new OLE object frame and adds it to the end of the shape collection. |
| [`insert_ole_object_frame`](/slides/python-net/aspose.slides/shapecollection/insert_ole_object_frame/#int-float-float-float-float-asposeslidesioleembeddeddatainfo) | Creates a new OLE object frame and inserts it into the shape collection at the specified index. |
| [`insert_ole_object_frame`](/slides/python-net/aspose.slides/shapecollection/insert_ole_object_frame/#int-float-float-float-float-str-str) | Creates a new OLE object frame and inserts it into the shape collection at the specified index. |
| [`add_video_frame`](/slides/python-net/aspose.slides/shapecollection/add_video_frame/#float-float-float-float-str) | Creates a new video frame and adds it to the end of the shape collection. |
| [`add_video_frame`](/slides/python-net/aspose.slides/shapecollection/add_video_frame/#float-float-float-float-asposeslidesivideo) | Creates a new video frame and adds it to the end of the shape collection. |
| [`add_audio_frame_embedded`](/slides/python-net/aspose.slides/shapecollection/add_audio_frame_embedded/#float-float-float-float-iorawiobase) | Creates a new audio frame with an embedded WAV file and adds it to the end of the<br/>            shape collection. The embedded audio is added to the Presentation.Audios collection. |
| [`add_audio_frame_embedded`](/slides/python-net/aspose.slides/shapecollection/add_audio_frame_embedded/#float-float-float-float-asposeslidesiaudio) | Creates a new audio frame and adds it to the end of the shape collection using an<br/>            existing audio object from the Presentation.Audios list. |
| [`insert_audio_frame_embedded`](/slides/python-net/aspose.slides/shapecollection/insert_audio_frame_embedded/#int-float-float-float-float-iorawiobase) | Creates a new audio frame with an embedded WAV file and inserts it into the shape<br/>            collection at the specified index. The embedded audio is added to the Presentation.Audios<br/>            collection. |
| [`insert_audio_frame_embedded`](/slides/python-net/aspose.slides/shapecollection/insert_audio_frame_embedded/#int-float-float-float-float-asposeslidesiaudio) | Creates a new audio frame and inserts it into the shape collection at the specified index<br/>            using an existing audio object from the Presentation.Audios list. |
| [`to_array`](/slides/python-net/aspose.slides/shapecollection/to_array/#) | Creates and returns an array that contains all shapes. |
| [`to_array`](/slides/python-net/aspose.slides/shapecollection/to_array/#int-int) | Creates and returns an array that contains all shapes in the specified range. |
| [`reorder`](/slides/python-net/aspose.slides/shapecollection/reorder/#int-asposeslidesishape) | Moves the specified shape to a new position within the shape collection. |
| [`reorder`](/slides/python-net/aspose.slides/shapecollection/reorder/#int-listasposeslidesishape) | Moves the specified shapes within the shape collection, placing them starting at the given index. |
| [`add_auto_shape`](/slides/python-net/aspose.slides/shapecollection/add_auto_shape/#asposeslidesshapetype-float-float-float-float) | Creates a new auto shape with default formatting and adds it to the end of the<br/>            shape collection. |
| [`add_auto_shape`](/slides/python-net/aspose.slides/shapecollection/add_auto_shape/#asposeslidesshapetype-float-float-float-float-bool) | Creates a new auto shape and adds it to the end of the shape collection, optionally<br/>            initializing it with default template formatting. |
| [`insert_auto_shape`](/slides/python-net/aspose.slides/shapecollection/insert_auto_shape/#int-asposeslidesshapetype-float-float-float-float) | Creates a new auto shape and inserts it into the shape collection at the specified index,<br/>            applying default template formatting. |
| [`insert_auto_shape`](/slides/python-net/aspose.slides/shapecollection/insert_auto_shape/#int-asposeslidesshapetype-float-float-float-float-bool) | Creates a new auto shape and inserts it into the shape collection at the specified index,<br/>            optionally initializing it with default template styling. |
| [`add_group_shape`](/slides/python-net/aspose.slides/shapecollection/add_group_shape/#) | Creates a new empty group shape and adds it to the end of the shape collection.<br/>            The group’s frame will automatically adjust to fit any shapes added to it. |
| [`add_group_shape`](/slides/python-net/aspose.slides/shapecollection/add_group_shape/#asposeslidesisvgimage-float-float-float-float) | Creates a new group shape, converts the specified SVG image into individual shapes,<br/>            and adds the resulting group to the end of the shape collection. |
| [`add_connector`](/slides/python-net/aspose.slides/shapecollection/add_connector/#asposeslidesshapetype-float-float-float-float) | Creates a new connector shape with default template styling and adds it to the end of the<br/>            shape collection. |
| [`add_connector`](/slides/python-net/aspose.slides/shapecollection/add_connector/#asposeslidesshapetype-float-float-float-float-bool) | Creates a new connector shape and adds it to the end of the shape collection,<br/>            optionally applying default template styling. |
| [`insert_connector`](/slides/python-net/aspose.slides/shapecollection/insert_connector/#int-asposeslidesshapetype-float-float-float-float) | Creates a new connector shape and inserts it into the shape collection at the specified index,<br/>            applying default template styling. |
| [`insert_connector`](/slides/python-net/aspose.slides/shapecollection/insert_connector/#int-asposeslidesshapetype-float-float-float-float-bool) | Creates a new connector shape and inserts it into the shape collection at the specified index,<br/>            optionally applying default template styling. |
| [`add_clone`](/slides/python-net/aspose.slides/shapecollection/add_clone/#asposeslidesishape-float-float-float-float) | Creates a copy of the specified shape and adds it to the end of the shape collection. |
| [`add_clone`](/slides/python-net/aspose.slides/shapecollection/add_clone/#asposeslidesishape-float-float) | Creates a copy of the specified shape and adds it to the end of the shape collection.<br/>            The new shape retains the width and height of the `source_shape`. |
| [`add_clone`](/slides/python-net/aspose.slides/shapecollection/add_clone/#asposeslidesishape) | Creates a copy of the specified shape and adds it to the end of the shape collection.<br/>            The cloned shape retains the original’s position and size. |
| [`insert_clone`](/slides/python-net/aspose.slides/shapecollection/insert_clone/#int-asposeslidesishape-float-float-float-float) | Creates a copy of the specified shape and inserts it into the shape collection at the specified index. |
| [`insert_clone`](/slides/python-net/aspose.slides/shapecollection/insert_clone/#int-asposeslidesishape-float-float) | Creates a copy of the specified shape and inserts it into the shape collection at the specified index.<br/>            The new shape retains the width and height of the `source_shape`. |
| [`insert_clone`](/slides/python-net/aspose.slides/shapecollection/insert_clone/#int-asposeslidesishape) | Creates a copy of the specified shape and inserts it into the shape collection at the specified index.<br/>            The cloned shape retains the original’s position and size. |
| [`add_smart_art`](/slides/python-net/aspose.slides/shapecollection/add_smart_art/#float-float-float-float-asposeslidessmartartsmartartlayouttype) | Creates a SmartArt diagram and adds it to the end of the shape collection. |
| [`add_summary_zoom_frame`](/slides/python-net/aspose.slides/shapecollection/add_summary_zoom_frame/#float-float-float-float) | Creates a new Summary Zoom frame and adds it to the end of the shape collection. |
| [`insert_summary_zoom_frame`](/slides/python-net/aspose.slides/shapecollection/insert_summary_zoom_frame/#int-float-float-float-float) | Creates a new Summary Zoom frame and inserts it into the shape collection at the specified index. |
| [`insert_video_frame`](/slides/python-net/aspose.slides/shapecollection/insert_video_frame/#int-float-float-float-float-str) | Creates a new video frame and inserts it into the shape collection at the specified index. |
| [`add_audio_frame_cd`](/slides/python-net/aspose.slides/shapecollection/add_audio_frame_cd/#float-float-float-float) | Creates a new audio frame linked to a CD track and adds it to the end of the shape collection. |
| [`insert_audio_frame_cd`](/slides/python-net/aspose.slides/shapecollection/insert_audio_frame_cd/#int-float-float-float-float) | Creates a new audio frame linked to a CD track and inserts it into the shape collection<br/>            at the specified index. |
| [`add_audio_frame_linked`](/slides/python-net/aspose.slides/shapecollection/add_audio_frame_linked/#float-float-float-float-str) | Creates a new audio frame linked to an external audio file and adds it to the end of<br/>            the shape collection. |
| [`insert_audio_frame_linked`](/slides/python-net/aspose.slides/shapecollection/insert_audio_frame_linked/#int-float-float-float-float-str) | Creates a new audio frame linked to an external audio file and inserts it into the shape<br/>            collection at the specified index. |
| [`index_of`](/slides/python-net/aspose.slides/shapecollection/index_of/#asposeslidesishape) | Returns the zero-based index of the first occurrence of the specified shape in the collection. |
| [`add_math_shape`](/slides/python-net/aspose.slides/shapecollection/add_math_shape/#float-float-float-float) | Creates a new rectangle auto shape to host mathematical content and adds it to the<br/>            end of the shape collection. |
| [`insert_group_shape`](/slides/python-net/aspose.slides/shapecollection/insert_group_shape/#int) | Creates a new empty group shape and inserts it to the shape collection at the specified index.<br/>            The group’s frame will automatically adjust to fit any shapes added to it. |
| [`add_picture_frame`](/slides/python-net/aspose.slides/shapecollection/add_picture_frame/#asposeslidesshapetype-float-float-float-float-asposeslidesippimage) | Creates a new picture frame containing the specified image and adds it to the end of the<br/>            shape collection. |
| [`insert_picture_frame`](/slides/python-net/aspose.slides/shapecollection/insert_picture_frame/#int-asposeslidesshapetype-float-float-float-float-asposeslidesippimage) | Creates a new picture frame containing the specified image and inserts it into the shape<br/>            collection at the specified index. |
| [`add_table`](/slides/python-net/aspose.slides/shapecollection/add_table/#float-float-listfloat-listfloat) | Creates a new table and adds it to the end of the shape collection. |
| [`insert_table`](/slides/python-net/aspose.slides/shapecollection/insert_table/#int-float-float-listfloat-listfloat) | Creates a new table and inserts it into the shape collection at the specified index. |
| [`remove_at`](/slides/python-net/aspose.slides/shapecollection/remove_at/#int) | Removes the shape at the specified index from the shape collection. |
| [`remove`](/slides/python-net/aspose.slides/shapecollection/remove/#asposeslidesishape) | Removes the first occurrence of the specified shape from the shape collection. |
| [`clear`](/slides/python-net/aspose.slides/shapecollection/clear/#) | Removes all shapes from the shape collection. |


### See Also
* class [`IShape`](/slides/python-net/aspose.slides/ishape)
* module [`aspose.slides`](/slides/python-net/aspose.slides)
* library [`Aspose.Slides`](/slides/python-net)

