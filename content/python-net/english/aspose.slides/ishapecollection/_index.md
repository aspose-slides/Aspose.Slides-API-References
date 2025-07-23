---
title: IShapeCollection class
second_title: Aspose.Slides for Python via .NET API Reference
description: 
type: docs
url: /aspose.slides/ishapecollection/
---


## IShapeCollection class

Represents a collection of shapes.

The IShapeCollection type exposes the following members:

## Properties

| Property | Description |
| :- | :- |
| [`parent_group`](/slides/python-net/aspose.slides/ishapecollection/parent_group/) | Gets the parent group shape object for the shapes collection.<br/>            Read-only [`IGroupShape`](/slides/python-net/aspose.slides/igroupshape). |

Gets the element at the specified index.
            Read-only [`IShape`](/slides/python-net/aspose.slides/ishape).

## Indexer

| Name | Description |
| :- | :- |
| [`[index]`](/slides/python-net/aspose.slides/ishapecollection/__getitem__/) |  |

## Methods

| Method | Description |
| :- | :- |
| [`add_chart`](/slides/python-net/aspose.slides/ishapecollection/add_chart/#asposeslideschartscharttype-float-float-float-float) | Creates a new chart, initializes it with sample series data and settings, and adds<br/>            it to the end of the shape collection. |
| [`add_chart`](/slides/python-net/aspose.slides/ishapecollection/add_chart/#asposeslideschartscharttype-float-float-float-float-bool) | Creates a new chart, initializes it with sample series data and settings, and adds<br/>            it to the end of the shape collection. |
| [`insert_chart`](/slides/python-net/aspose.slides/ishapecollection/insert_chart/#asposeslideschartscharttype-float-float-float-float-int) | Creates a new chart, initializes it with sample series data and settings,<br/>            and inserts it into the shape collection at the specified index. |
| [`insert_chart`](/slides/python-net/aspose.slides/ishapecollection/insert_chart/#asposeslideschartscharttype-float-float-float-float-int-bool) | Creates a new chart, initializes it with sample series data and settings,<br/>            and inserts it into the shape collection at the specified index. |
| [`add_ole_object_frame`](/slides/python-net/aspose.slides/ishapecollection/add_ole_object_frame/#float-float-float-float-ioleembeddeddatainfo) | Creates a new OLE object frame and adds it to the end of the shape collection. |
| [`add_ole_object_frame`](/slides/python-net/aspose.slides/ishapecollection/add_ole_object_frame/#float-float-float-float-str-str) | Creates a new OLE object frame and adds it to the end of the shape collection. |
| [`insert_ole_object_frame`](/slides/python-net/aspose.slides/ishapecollection/insert_ole_object_frame/#int-float-float-float-float-ioleembeddeddatainfo) | Creates a new OLE object frame and inserts it into the shape collection at the specified index. |
| [`insert_ole_object_frame`](/slides/python-net/aspose.slides/ishapecollection/insert_ole_object_frame/#int-float-float-float-float-str-str) | Creates a new OLE object frame and inserts it into the shape collection at the specified index. |
| [`add_zoom_frame`](/slides/python-net/aspose.slides/ishapecollection/add_zoom_frame/#float-float-float-float-islide) | Creates a new Zoom frame and adds it to the end of the shape collection. |
| [`add_zoom_frame`](/slides/python-net/aspose.slides/ishapecollection/add_zoom_frame/#float-float-float-float-islide-ippimage) | Creates a new Zoom frame and adds it to the end of the shape collection. |
| [`insert_zoom_frame`](/slides/python-net/aspose.slides/ishapecollection/insert_zoom_frame/#int-float-float-float-float-islide) | Creates a new Zoom frame and inserts it into the shape collection at the specified index. |
| [`insert_zoom_frame`](/slides/python-net/aspose.slides/ishapecollection/insert_zoom_frame/#int-float-float-float-float-islide-ippimage) | Creates a new Zoom frame with a predefined image and inserts it into the shape collection<br/>            at the specified index. |
| [`add_section_zoom_frame`](/slides/python-net/aspose.slides/ishapecollection/add_section_zoom_frame/#float-float-float-float-isection) | Creates a new Section Zoom frame and adds it to the end of the shape collection. |
| [`add_section_zoom_frame`](/slides/python-net/aspose.slides/ishapecollection/add_section_zoom_frame/#float-float-float-float-isection-ippimage) | Creates a new Section Zoom frame with a predefined image and adds it to the end of the<br/>            shape collection. |
| [`insert_section_zoom_frame`](/slides/python-net/aspose.slides/ishapecollection/insert_section_zoom_frame/#int-float-float-float-float-isection) | Creates a new Section Zoom frame and inserts it into to the shape collection at the<br/>            specified index. |
| [`insert_section_zoom_frame`](/slides/python-net/aspose.slides/ishapecollection/insert_section_zoom_frame/#int-float-float-float-float-isection-ippimage) | Creates a new Section Zoom frame with a predefined image and inserts it into to the shape<br/>            collection at the specified index. |
| [`add_video_frame`](/slides/python-net/aspose.slides/ishapecollection/add_video_frame/#float-float-float-float-str) | Creates a new video frame and adds it to the end of the shape collection. |
| [`add_video_frame`](/slides/python-net/aspose.slides/ishapecollection/add_video_frame/#float-float-float-float-ivideo) | Creates a new video frame and adds it to the end of the shape collection. |
| [`add_audio_frame_embedded`](/slides/python-net/aspose.slides/ishapecollection/add_audio_frame_embedded/#float-float-float-float-iorawiobase) | Creates a new audio frame with an embedded WAV file and adds it to the end of the<br/>            shape collection. The embedded audio is added to the Presentation.Audios collection. |
| [`add_audio_frame_embedded`](/slides/python-net/aspose.slides/ishapecollection/add_audio_frame_embedded/#float-float-float-float-iaudio) | Creates a new audio frame and adds it to the end of the shape collection using an<br/>            existing audio object from the Presentation.Audios list. |
| [`insert_audio_frame_embedded`](/slides/python-net/aspose.slides/ishapecollection/insert_audio_frame_embedded/#int-float-float-float-float-iorawiobase) | Creates a new audio frame with an embedded WAV file and inserts it into the shape<br/>            collection at the specified index. The embedded audio is added to the Presentation.Audios<br/>            collection. |
| [`insert_audio_frame_embedded`](/slides/python-net/aspose.slides/ishapecollection/insert_audio_frame_embedded/#int-float-float-float-float-iaudio) | Creates a new audio frame and inserts it into the shape collection at the specified index<br/>            using an existing audio object from the Presentation.Audios list. |
| [`to_array`](/slides/python-net/aspose.slides/ishapecollection/to_array/#) | Creates and returns an array that contains all shapes. |
| [`to_array`](/slides/python-net/aspose.slides/ishapecollection/to_array/#int-int) | Creates and returns an array that contains all shapes in the specified range. |
| [`reorder`](/slides/python-net/aspose.slides/ishapecollection/reorder/#int-ishape) | Moves the specified shape to a new position within the shape collection. |
| [`reorder`](/slides/python-net/aspose.slides/ishapecollection/reorder/#int-listishape) | Moves the specified shapes within the shape collection, placing them starting at the given index. |
| [`add_auto_shape`](/slides/python-net/aspose.slides/ishapecollection/add_auto_shape/#shapetype-float-float-float-float) | Creates a new auto shape with default formatting and adds it to the end of the<br/>            shape collection. |
| [`add_auto_shape`](/slides/python-net/aspose.slides/ishapecollection/add_auto_shape/#shapetype-float-float-float-float-bool) | Creates a new auto shape and adds it to the end of the shape collection, optionally<br/>            initializing it with default template formatting. |
| [`insert_auto_shape`](/slides/python-net/aspose.slides/ishapecollection/insert_auto_shape/#int-shapetype-float-float-float-float) | Creates a new auto shape and inserts it into the shape collection at the specified index,<br/>            applying default template formatting. |
| [`insert_auto_shape`](/slides/python-net/aspose.slides/ishapecollection/insert_auto_shape/#int-shapetype-float-float-float-float-bool) | Creates a new auto shape and inserts it into the shape collection at the specified index,<br/>            optionally initializing it with default template styling. |
| [`add_group_shape`](/slides/python-net/aspose.slides/ishapecollection/add_group_shape/#) | Creates a new empty group shape and adds it to the end of the shape collection.<br/>            The group’s frame will automatically adjust to fit any shapes added to it. |
| [`add_group_shape`](/slides/python-net/aspose.slides/ishapecollection/add_group_shape/#isvgimage-float-float-float-float) | Creates a new group shape, converts the specified SVG image into individual shapes,<br/>            and adds the resulting group to the end of the shape collection. |
| [`add_connector`](/slides/python-net/aspose.slides/ishapecollection/add_connector/#shapetype-float-float-float-float) | Creates a new connector shape with default template styling and adds it to the end of the<br/>            shape collection. |
| [`add_connector`](/slides/python-net/aspose.slides/ishapecollection/add_connector/#shapetype-float-float-float-float-bool) | Creates a new connector shape and adds it to the end of the shape collection,<br/>            optionally applying default template styling. |
| [`insert_connector`](/slides/python-net/aspose.slides/ishapecollection/insert_connector/#int-shapetype-float-float-float-float) | Creates a new connector shape and inserts it into the shape collection at the specified index,<br/>            applying default template styling. |
| [`insert_connector`](/slides/python-net/aspose.slides/ishapecollection/insert_connector/#int-shapetype-float-float-float-float-bool) | Creates a new connector shape and inserts it into the shape collection at the specified index,<br/>            optionally applying default template styling. |
| [`add_clone`](/slides/python-net/aspose.slides/ishapecollection/add_clone/#ishape-float-float-float-float) | Creates a copy of the specified shape and adds it to the end of the shape collection. |
| [`add_clone`](/slides/python-net/aspose.slides/ishapecollection/add_clone/#ishape-float-float) | Creates a copy of the specified shape and adds it to the end of the shape collection.<br/>            The new shape retains the width and height of the `source_shape`. |
| [`add_clone`](/slides/python-net/aspose.slides/ishapecollection/add_clone/#ishape) | Creates a copy of the specified shape and adds it to the end of the shape collection.<br/>            The cloned shape retains the original’s position and size. |
| [`insert_clone`](/slides/python-net/aspose.slides/ishapecollection/insert_clone/#int-ishape-float-float-float-float) | Creates a copy of the specified shape and inserts it into the shape collection at the specified index. |
| [`insert_clone`](/slides/python-net/aspose.slides/ishapecollection/insert_clone/#int-ishape-float-float) | Creates a copy of the specified shape and inserts it into the shape collection at the specified index.<br/>            The new shape retains the width and height of the `source_shape`. |
| [`insert_clone`](/slides/python-net/aspose.slides/ishapecollection/insert_clone/#int-ishape) | Creates a copy of the specified shape and inserts it into the shape collection at the specified index.<br/>            The cloned shape retains the original’s position and size. |
| [`add_smart_art`](/slides/python-net/aspose.slides/ishapecollection/add_smart_art/#float-float-float-float-asposeslidessmartartsmartartlayouttype) | Creates a SmartArt diagram and adds it to the end of the shape collection. |
| [`add_summary_zoom_frame`](/slides/python-net/aspose.slides/ishapecollection/add_summary_zoom_frame/#float-float-float-float) | Creates a new Summary Zoom frame and adds it to the end of the shape collection. |
| [`insert_summary_zoom_frame`](/slides/python-net/aspose.slides/ishapecollection/insert_summary_zoom_frame/#int-float-float-float-float) | Creates a new Summary Zoom frame and inserts it into the shape collection at the specified index. |
| [`insert_video_frame`](/slides/python-net/aspose.slides/ishapecollection/insert_video_frame/#int-float-float-float-float-str) | Creates a new video frame and inserts it into the shape collection at the specified index. |
| [`add_audio_frame_cd`](/slides/python-net/aspose.slides/ishapecollection/add_audio_frame_cd/#float-float-float-float) | Creates a new audio frame linked to a CD track and adds it to the end of the shape collection. |
| [`insert_audio_frame_cd`](/slides/python-net/aspose.slides/ishapecollection/insert_audio_frame_cd/#int-float-float-float-float) | Creates a new audio frame linked to a CD track and inserts it into the shape collection<br/>            at the specified index. |
| [`add_audio_frame_linked`](/slides/python-net/aspose.slides/ishapecollection/add_audio_frame_linked/#float-float-float-float-str) | Creates a new audio frame linked to an external audio file and adds it to the end of<br/>            the shape collection. |
| [`insert_audio_frame_linked`](/slides/python-net/aspose.slides/ishapecollection/insert_audio_frame_linked/#int-float-float-float-float-str) | Creates a new audio frame linked to an external audio file and inserts it into the shape<br/>            collection at the specified index. |
| [`index_of`](/slides/python-net/aspose.slides/ishapecollection/index_of/#ishape) | Returns the zero-based index of the first occurrence of the specified shape in the collection. |
| [`add_math_shape`](/slides/python-net/aspose.slides/ishapecollection/add_math_shape/#float-float-float-float) | Creates a new rectangle auto shape to host mathematical content and adds it to the<br/>            end of the shape collection. |
| [`insert_group_shape`](/slides/python-net/aspose.slides/ishapecollection/insert_group_shape/#int) | Creates a new empty group shape and inserts it to the shape collection at the specified index.<br/>            The group’s frame will automatically adjust to fit any shapes added to it. |
| [`add_picture_frame`](/slides/python-net/aspose.slides/ishapecollection/add_picture_frame/#shapetype-float-float-float-float-ippimage) | Creates a new picture frame containing the specified image and adds it to the end of the<br/>            shape collection. |
| [`insert_picture_frame`](/slides/python-net/aspose.slides/ishapecollection/insert_picture_frame/#int-shapetype-float-float-float-float-ippimage) | Creates a new picture frame containing the specified image and inserts it into the shape<br/>            collection at the specified index. |
| [`add_table`](/slides/python-net/aspose.slides/ishapecollection/add_table/#float-float-listfloat-listfloat) | Creates a new table and adds it to the end of the shape collection. |
| [`insert_table`](/slides/python-net/aspose.slides/ishapecollection/insert_table/#int-float-float-listfloat-listfloat) | Creates a new table and inserts it into the shape collection at the specified index. |
| [`remove_at`](/slides/python-net/aspose.slides/ishapecollection/remove_at/#int) | Removes the shape at the specified index from the shape collection. |
| [`remove`](/slides/python-net/aspose.slides/ishapecollection/remove/#ishape) | Removes the first occurrence of the specified shape from the shape collection. |
| [`clear`](/slides/python-net/aspose.slides/ishapecollection/clear/#) | Removes all shapes from the shape collection. |


### See Also
* class [`IShape`](/slides/python-net/aspose.slides/ishape)
* module [`aspose.slides`](/slides/python-net/aspose.slides)
* library [`Aspose.Slides`](/slides/python-net)

