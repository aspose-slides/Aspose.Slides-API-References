---
title: MasterSlide class
second_title: Tham chiếu API Aspose.Slides cho Python qua .NET
description: 
type: docs
url: /vi/aspose.slides/masterslide/
---
## MasterSlide lớp

Biểu thị một slide chủ trong một bản trình chiếu.

**Kế thừa:**[`MasterSlide`](/slides/python-net/vi/aspose.slides/masterslide) → [`BaseSlide`](/slides/python-net/vi/aspose.slides/baseslide)

Kiểu MasterSlide cung cấp các thành viên sau:

## Thuộc tính

| Property | Description |
| :- | :- |
| [`shapes`](/slides/python-net/vi/aspose.slides/masterslide/shapes/) | Returns the shapes of a slide.<br/>            Chỉ đọc [`IShapeCollection`](/slides/python-net/vi/aspose.slides/ishapecollection). |
| [`controls`](/slides/python-net/vi/aspose.slides/masterslide/controls/) | Returns the collection of ActiveX controls on a slide.<br/>            Chỉ đọc [`IControlCollection`](/slides/python-net/vi/aspose.slides/icontrolcollection). |
| [`name`](/slides/python-net/vi/aspose.slides/masterslide/name/) | Returns or sets the name of a master slide.<br/>            Đọc/ghi **str**. |
| [`slide_id`](/slides/python-net/vi/aspose.slides/masterslide/slide_id/) | Returns the ID of a slide.<br/>            Chỉ đọc **int**. |
| [`custom_data`](/slides/python-net/vi/aspose.slides/masterslide/custom_data/) | Returns the slide's custom data.<br/>            Chỉ đọc [`ICustomData`](/slides/python-net/vi/aspose.slides/icustomdata). |
| [`timeline`](/slides/python-net/vi/aspose.slides/masterslide/timeline/) | Returns animation timeline object.<br/>            Chỉ đọc [`IAnimationTimeLine`](/slides/python-net/vi/aspose.slides/ianimationtimeline). |
| [`slide_show_transition`](/slides/python-net/vi/aspose.slides/masterslide/slide_show_transition/) | Returns the Transition object which contains information about<br/>            how the specified slide advances during a slide show.<br/>            Chỉ đọc [`ISlideShowTransition`](/slides/python-net/vi/aspose.slides/islideshowtransition). |
| [`background`](/slides/python-net/vi/aspose.slides/masterslide/background/) | Returns slide's background.<br/>            Chỉ đọc [`IBackground`](/slides/python-net/vi/aspose.slides/ibackground). |
| [`hyperlink_queries`](/slides/python-net/vi/aspose.slides/masterslide/hyperlink_queries/) | Provides easy access to contained hyperlinks.<br/>            Chỉ đọc [`IHyperlinkQueries`](/slides/python-net/vi/aspose.slides/ihyperlinkqueries). |
| [`show_master_shapes`](/slides/python-net/vi/aspose.slides/masterslide/show_master_shapes/) | Specifies if shapes on the master slide should be shown on slides or not.<br/>            For master slide itself this property always returns `false`.<br/>            Đọc/ghi **bool**. |
| [`presentation`](/slides/python-net/vi/aspose.slides/masterslide/presentation/) | Returns IPresentation interface.<br/>            Chỉ đọc [`IPresentation`](/slides/python-net/vi/aspose.slides/ipresentation). |
| [`header_footer_manager`](/slides/python-net/vi/aspose.slides/masterslide/header_footer_manager/) | Returns HeaderFooter manager of the master slide.<br/>            Chỉ đọc [`IMasterSlideHeaderFooterManager`](/slides/python-net/vi/aspose.slides/imasterslideheaderfootermanager). |
| [`title_style`](/slides/python-net/vi/aspose.slides/masterslide/title_style/) | Returns the style of a title text.<br/>            Chỉ đọc [`ITextStyle`](/slides/python-net/vi/aspose.slides/itextstyle). |
| [`body_style`](/slides/python-net/vi/aspose.slides/masterslide/body_style/) | Returns the style of a body text.<br/>            Chỉ đọc [`ITextStyle`](/slides/python-net/vi/aspose.slides/itextstyle). |
| [`other_style`](/slides/python-net/vi/aspose.slides/masterslide/other_style/) | Returns the style of an other text.<br/>            Chỉ đọc [`ITextStyle`](/slides/python-net/vi/aspose.slides/itextstyle). |
| [`layout_slides`](/slides/python-net/vi/aspose.slides/masterslide/layout_slides/) | Returns the collection of child layout slides for this master slide.<br/>            Chỉ đọc [`IMasterLayoutSlideCollection`](/slides/python-net/vi/aspose.slides/imasterlayoutslidecollection). |
| [`preserve`](/slides/python-net/vi/aspose.slides/masterslide/preserve/) | Determines whether the corresponding master is deleted when all the slides that follow that master are deleted.<br/>            Note: Aspose.Slides will never remove any unused master by itself, to actually remove unused masters call **Aspose.Slides.MasterSlideCollection.RemoveUnused(Syste**<br/>            Đọc/ghi **bool**. |
| [`has_depending_slides`](/slides/python-net/vi/aspose.slides/masterslide/has_depending_slides/) | Returns true if there exists at least one slide that depends on this master slide.<br/>            Chỉ đọc **bool**. |
| [`theme_manager`](/slides/python-net/vi/aspose.slides/masterslide/theme_manager/) | Returns the theme manager.<br/>            Chỉ đọc [`IMasterThemeManager`](/slides/python-net/vi/aspose.slides.theme/imasterthememanager). |
| [`drawing_guides`](/slides/python-net/vi/aspose.slides/masterslide/drawing_guides/) | Returns a collection of drawing guides for the master slide.<br/>            Chỉ đọc [`IDrawingGuidesCollection`](/slides/python-net/vi/aspose.slides/idrawingguidescollection) |
| [`slide`](/slides/python-net/vi/aspose.slides/masterslide/slide/) |  |

## Phương thức

| Method | Description |
| :- | :- |
| [`join_portions_with_same_formatting(self)`](/slides/python-net/vi/aspose.slides/masterslide/join_portions_with_same_formatting/#) | Joins runs with same formatting in all paragraphs all acceptable shapes. |
| [`join_portions_with_same_formatting(self, collection)`](/slides/python-net/vi/aspose.slides/masterslide/join_portions_with_same_formatting/#ishapecollection) | Joins runs with same formatting in all paragraphs in all acceptable shapes. |
| [`equals(self, slide)`](/slides/python-net/vi/aspose.slides/masterslide/equals/#ibaseslide) | Determines whether the two IBaseSlide instances are equal.<br/>            Returning value is calculated based on slide's structure and static content.<br/>            Two slides are equal if all shapes, styles, texts, animation and other settings. etc. are equal. The comparison doesn't take into account unique identifier values, e.g. SlideId and dynamic content, e.g. current date value in Date Placeholder. |
| [`create_theme_effective(self)`](/slides/python-net/vi/aspose.slides/masterslide/create_theme_effective/#) | Returns an effective theme for this slide. |
| [`find_shape_by_alt_text(self, alt_text)`](/slides/python-net/vi/aspose.slides/masterslide/find_shape_by_alt_text/#str) | Finds first occurrence of a shape with the specified alternative text. |
| [`apply_external_theme_to_depending_slides(self, fname)`](/slides/python-net/vi/aspose.slides/masterslide/apply_external_theme_to_depending_slides/#str) | Creates a new master slide based on the current one, applying an external theme to it <br/>            and applies the created master slide to all dependent slides. |
| [`get_depending_slides(self)`](/slides/python-net/vi/aspose.slides/masterslide/get_depending_slides/#) | Returns an array with all slides, which depend on this master slide. |


### Xem thêm
* lớp [`BaseSlide`](/slides/python-net/vi/aspose.slides/baseslide)
* lớp [`MasterSlide`](/slides/python-net/vi/aspose.slides/masterslide)
* module [`aspose.slides`](/slides/python-net/vi/aspose.slides)
* thư viện [`Aspose.Slides`](/slides/python-net)