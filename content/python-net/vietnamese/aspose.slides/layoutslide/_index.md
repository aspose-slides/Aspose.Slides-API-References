---
title: LayoutSlide class
second_title: Tham chiếu API Aspose.Slides cho Python qua .NET
description: 
type: docs
url: /vi/aspose.slides/layoutslide/
---
## LayoutSlide lớp

Biểu diễn một layout slide.

**Kế thừa:**[`LayoutSlide`](/slides/python-net/vi/aspose.slides/layoutslide) → [`BaseSlide`](/slides/python-net/vi/aspose.slides/baseslide)

Kiểu LayoutSlide cung cấp các thành viên sau:

## Thuộc tính

| Property | Description |
| :- | :- |
| [`shapes`](/slides/python-net/vi/aspose.slides/layoutslide/shapes/) | Returns the shapes of a slide.<br/>            Chỉ-đọc [`IShapeCollection`](/slides/python-net/vi/aspose.slides/ishapecollection). |
| [`controls`](/slides/python-net/vi/aspose.slides/layoutslide/controls/) | Returns the collection of ActiveX controls on a slide.<br/>            Chỉ-đọc [`IControlCollection`](/slides/python-net/vi/aspose.slides/icontrolcollection). |
| [`name`](/slides/python-net/vi/aspose.slides/layoutslide/name/) | Returns or sets the name of a slide.<br/>            Đọc/ghi **str**. |
| [`slide_id`](/slides/python-net/vi/aspose.slides/layoutslide/slide_id/) | Returns the ID of a slide.<br/>            Chỉ-đọc **int**. |
| [`custom_data`](/slides/python-net/vi/aspose.slides/layoutslide/custom_data/) | Returns the slide's custom data.<br/>            Chỉ-đọc [`ICustomData`](/slides/python-net/vi/aspose.slides/icustomdata). |
| [`timeline`](/slides/python-net/vi/aspose.slides/layoutslide/timeline/) | Returns animation timeline object.<br/>            Chỉ-đọc [`IAnimationTimeLine`](/slides/python-net/vi/aspose.slides/ianimationtimeline). |
| [`slide_show_transition`](/slides/python-net/vi/aspose.slides/layoutslide/slide_show_transition/) | Returns the Transition object which contains information about<br/>            how the specified slide advances during a slide show.<br/>            Chỉ-đọc [`ISlideShowTransition`](/slides/python-net/vi/aspose.slides/islideshowtransition). |
| [`background`](/slides/python-net/vi/aspose.slides/layoutslide/background/) | Returns slide's background.<br/>            Chỉ-đọc [`IBackground`](/slides/python-net/vi/aspose.slides/ibackground). |
| [`hyperlink_queries`](/slides/python-net/vi/aspose.slides/layoutslide/hyperlink_queries/) | Provides easy access to contained hyperlinks.<br/>            Chỉ-đọc [`IHyperlinkQueries`](/slides/python-net/vi/aspose.slides/ihyperlinkqueries). |
| [`show_master_shapes`](/slides/python-net/vi/aspose.slides/layoutslide/show_master_shapes/) | Specifies if shapes on the master slide should be shown on slides or not.<br/>            Đọc/ghi **bool**. |
| [`presentation`](/slides/python-net/vi/aspose.slides/layoutslide/presentation/) | Returns IPresentation interface.<br/>            Chỉ-đọc [`IPresentation`](/slides/python-net/vi/aspose.slides/ipresentation). |
| [`header_footer_manager`](/slides/python-net/vi/aspose.slides/layoutslide/header_footer_manager/) | Returns HeaderFooter manager of the layout slide.<br/>            Chỉ-đọc [`ILayoutSlideHeaderFooterManager`](/slides/python-net/vi/aspose.slides/ilayoutslideheaderfootermanager). |
| [`placeholder_manager`](/slides/python-net/vi/aspose.slides/layoutslide/placeholder_manager/) | Returns the placeholder manager of the layout slide.<br/>            Chỉ-đọc [`ILayoutPlaceholderManager`](/slides/python-net/vi/aspose.slides/ilayoutplaceholdermanager). |
| [`master_slide`](/slides/python-net/vi/aspose.slides/layoutslide/master_slide/) | Returns or sets the master slide for a layout.<br/>            Đọc/ghi [`IMasterSlide`](/slides/python-net/vi/aspose.slides/imasterslide). |
| [`theme_manager`](/slides/python-net/vi/aspose.slides/layoutslide/theme_manager/) | Returns the overriding theme manager.<br/>            Chỉ-đọc [`IOverrideThemeManager`](/slides/python-net/vi/aspose.slides.theme/ioverridethememanager). |
| [`layout_type`](/slides/python-net/vi/aspose.slides/layoutslide/layout_type/) | Returns layout type of this layout slide.<br/>            Chỉ-đọc [`SlideLayoutType`](/slides/python-net/vi/aspose.slides/slidelayouttype). |
| [`has_depending_slides`](/slides/python-net/vi/aspose.slides/layoutslide/has_depending_slides/) | Returns true if there exists at least one slide that depends on this layout slide.<br/>            Chỉ-đọc **bool**. |
| [`drawing_guides`](/slides/python-net/vi/aspose.slides/layoutslide/drawing_guides/) | Returns a collection of drawing guides for the layout slide.<br/>            Chỉ-đọc [`IDrawingGuidesCollection`](/slides/python-net/vi/aspose.slides/idrawingguidescollection) |
| [`slide`](/slides/python-net/vi/aspose.slides/layoutslide/slide/) |  |

## Phương thức

| Method | Description |
| :- | :- |
| [`join_portions_with_same_formatting(self)`](/slides/python-net/vi/aspose.slides/layoutslide/join_portions_with_same_formatting/#) | Joins runs with same formatting in all paragraphs all acceptable shapes. |
| [`join_portions_with_same_formatting(self, collection)`](/slides/python-net/vi/aspose.slides/layoutslide/join_portions_with_same_formatting/#ishapecollection) | Joins runs with same formatting in all paragraphs in all acceptable shapes. |
| [`equals(self, slide)`](/slides/python-net/vi/aspose.slides/layoutslide/equals/#ibaseslide) | Determines whether the two IBaseSlide instances are equal.<br/>            Returning value is calculated based on slide's structure and static content.<br/>            Two slides are equal if all shapes, styles, texts, animation and other settings. etc. are equal. The comparison doesn't take into account unique identifier values, e.g. SlideId and dynamic content, e.g. current date value in Date Placeholder. |
| [`create_theme_effective(self)`](/slides/python-net/vi/aspose.slides/layoutslide/create_theme_effective/#) | Returns an effective theme for this slide. |
| [`find_shape_by_alt_text(self, alt_text)`](/slides/python-net/vi/aspose.slides/layoutslide/find_shape_by_alt_text/#str) | Finds first occurrence of a shape with the specified alternative text. |
| [`remove(self)`](/slides/python-net/vi/aspose.slides/layoutslide/remove/#) | Removes layout from presentation. |
| [`get_depending_slides(self)`](/slides/python-net/vi/aspose.slides/layoutslide/get_depending_slides/#) | Returns an array with all slides, which depend on this layout slide. |


### Xem thêm
* lớp [`BaseSlide`](/slides/python-net/vi/aspose.slides/baseslide)
* lớp [`LayoutSlide`](/slides/python-net/vi/aspose.slides/layoutslide)
* module [`aspose.slides`](/slides/python-net/vi/aspose.slides)
* thư viện [`Aspose.Slides`](/slides/python-net)