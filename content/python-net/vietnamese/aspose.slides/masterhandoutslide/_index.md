---
title: MasterHandoutSlide class
second_title: Tham khảo API Aspose.Slides cho Python qua .NET
description: 
type: docs
url: /vi/aspose.slides/masterhandoutslide/
---
## MasterHandoutSlide lớp

Represents master slide for handouts.

**Inheritance:**[`MasterHandoutSlide`](/slides/python-net/vi/aspose.slides/masterhandoutslide) → [`BaseSlide`](/slides/python-net/vi/aspose.slides/baseslide)

The MasterHandoutSlide type exposes the following members:

## Thuộc tính

| Property | Description |
| :- | :- |
| [`shapes`](/slides/python-net/vi/aspose.slides/masterhandoutslide/shapes/) | Returns the shapes of a slide.<br/>            Chỉ đọc [`IShapeCollection`](/slides/python-net/vi/aspose.slides/ishapecollection). |
| [`controls`](/slides/python-net/vi/aspose.slides/masterhandoutslide/controls/) | Returns the collection of ActiveX controls on a slide.<br/>            Chỉ đọc [`IControlCollection`](/slides/python-net/vi/aspose.slides/icontrolcollection). |
| [`name`](/slides/python-net/vi/aspose.slides/masterhandoutslide/name/) | Returns or sets the name of a slide.<br/>            Đọc/ghi **str**. |
| [`slide_id`](/slides/python-net/vi/aspose.slides/masterhandoutslide/slide_id/) | Returns the ID of a slide.<br/>            Chỉ đọc **int**. |
| [`custom_data`](/slides/python-net/vi/aspose.slides/masterhandoutslide/custom_data/) | Returns the slide's custom data.<br/>            Chỉ đọc [`ICustomData`](/slides/python-net/vi/aspose.slides/icustomdata). |
| [`timeline`](/slides/python-net/vi/aspose.slides/masterhandoutslide/timeline/) | Returns animation timeline object.<br/>            Chỉ đọc [`IAnimationTimeLine`](/slides/python-net/vi/aspose.slides/ianimationtimeline). |
| [`slide_show_transition`](/slides/python-net/vi/aspose.slides/masterhandoutslide/slide_show_transition/) | Returns the Transition object which contains information about<br/>            how the specified slide advances during a slide show.<br/>            Chỉ đọc [`ISlideShowTransition`](/slides/python-net/vi/aspose.slides/islideshowtransition). |
| [`background`](/slides/python-net/vi/aspose.slides/masterhandoutslide/background/) | Returns slide's background.<br/>            Chỉ đọc [`IBackground`](/slides/python-net/vi/aspose.slides/ibackground). |
| [`hyperlink_queries`](/slides/python-net/vi/aspose.slides/masterhandoutslide/hyperlink_queries/) | Provides easy access to contained hyperlinks.<br/>            Chỉ đọc [`IHyperlinkQueries`](/slides/python-net/vi/aspose.slides/ihyperlinkqueries). |
| [`show_master_shapes`](/slides/python-net/vi/aspose.slides/masterhandoutslide/show_master_shapes/) | Specifies if shapes on the master slide should be shown on slides or not.<br/>            For master slide itself this property always returns `false`.<br/>            Đọc/ghi **bool**. |
| [`presentation`](/slides/python-net/vi/aspose.slides/masterhandoutslide/presentation/) | Returns IPresentation interface.<br/>            Chỉ đọc [`IPresentation`](/slides/python-net/vi/aspose.slides/ipresentation). |
| [`header_footer_manager`](/slides/python-net/vi/aspose.slides/masterhandoutslide/header_footer_manager/) | Returns HeaderFooter manager of the master handout slide.<br/>            Chỉ đọc [`IMasterHandoutSlideHeaderFooterManager`](/slides/python-net/vi/aspose.slides/imasterhandoutslideheaderfootermanager). |
| [`theme_manager`](/slides/python-net/vi/aspose.slides/masterhandoutslide/theme_manager/) | Returns the theme manager.<br/>            Chỉ đọc [`IMasterThemeManager`](/slides/python-net/vi/aspose.slides.theme/imasterthememanager). |
| [`drawing_guides`](/slides/python-net/vi/aspose.slides/masterhandoutslide/drawing_guides/) | Returns a collection of drawing guides for the master handout slide.<br/>            Chỉ đọc [`IDrawingGuidesCollection`](/slides/python-net/vi/aspose.slides/idrawingguidescollection) |
| [`slide`](/slides/python-net/vi/aspose.slides/masterhandoutslide/slide/) |  |

## Phương thức

| Method | Description |
| :- | :- |
| [`join_portions_with_same_formatting(self)`](/slides/python-net/vi/aspose.slides/masterhandoutslide/join_portions_with_same_formatting/#) | Joins runs with same formatting in all paragraphs all acceptable shapes. |
| [`join_portions_with_same_formatting(self, collection)`](/slides/python-net/vi/aspose.slides/masterhandoutslide/join_portions_with_same_formatting/#ishapecollection) | Joins runs with same formatting in all paragraphs in all acceptable shapes. |
| [`equals(self, slide)`](/slides/python-net/vi/aspose.slides/masterhandoutslide/equals/#ibaseslide) | Determines whether the two IBaseSlide instances are equal.<br/>            Returning value is calculated based on slide's structure and static content.<br/>            Two slides are equal if all shapes, styles, texts, animation and other settings. etc. are equal. The comparison doesn't take into account unique identifier values, e.g. SlideId and dynamic content, e.g. current date value in Date Placeholder. |
| [`create_theme_effective(self)`](/slides/python-net/vi/aspose.slides/masterhandoutslide/create_theme_effective/#) | Returns an effective theme for this slide. |
| [`find_shape_by_alt_text(self, alt_text)`](/slides/python-net/vi/aspose.slides/masterhandoutslide/find_shape_by_alt_text/#str) | Finds first occurrence of a shape with the specified alternative text. |


### Xem thêm
* lớp [`BaseSlide`](/slides/python-net/vi/aspose.slides/baseslide)
* lớp [`MasterHandoutSlide`](/slides/python-net/vi/aspose.slides/masterhandoutslide)
* module [`aspose.slides`](/slides/python-net/vi/aspose.slides)
* thư viện [`Aspose.Slides`](/slides/python-net)