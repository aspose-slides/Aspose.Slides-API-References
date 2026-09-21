---
title: MasterNotesSlide class
second_title: Aspose.Slides สำหรับ Python ผ่าน .NET API Reference
description: 
type: docs
url: /th/aspose.slides/masternotesslide/
---
## MasterNotesSlide คลาส

แทนสไลด์หลักสำหรับบันทึกย่อ.

**Inheritance:**[`MasterNotesSlide`](/slides/python-net/th/aspose.slides/masternotesslide) → [`BaseSlide`](/slides/python-net/th/aspose.slides/baseslide)

ประเภท MasterNotesSlide เปิดเผยสมาชิกต่อไปนี้:

## คุณสมบัติ

| คุณสมบัติ | คำอธิบาย |
| :- | :- |
| [`shapes`](/slides/python-net/th/aspose.slides/masternotesslide/shapes/) | Returns the shapes of a slide.<br/>            อ่านอย่างเดียว [`IShapeCollection`](/slides/python-net/th/aspose.slides/ishapecollection). |
| [`controls`](/slides/python-net/th/aspose.slides/masternotesslide/controls/) | Returns the collection of ActiveX controls on a slide.<br/>            อ่านอย่างเดียว [`IControlCollection`](/slides/python-net/th/aspose.slides/icontrolcollection). |
| [`name`](/slides/python-net/th/aspose.slides/masternotesslide/name/) | Returns or sets the name of a slide.<br/>            อ่าน/เขียน **str**. |
| [`slide_id`](/slides/python-net/th/aspose.slides/masternotesslide/slide_id/) | Returns the ID of a slide.<br/>            อ่านอย่างเดียว **int**. |
| [`custom_data`](/slides/python-net/th/aspose.slides/masternotesslide/custom_data/) | Returns the slide's custom data.<br/>            อ่านอย่างเดียว [`ICustomData`](/slides/python-net/th/aspose.slides/icustomdata). |
| [`timeline`](/slides/python-net/th/aspose.slides/masternotesslide/timeline/) | Returns animation timeline object.<br/>            อ่านอย่างเดียว [`IAnimationTimeLine`](/slides/python-net/th/aspose.slides/ianimationtimeline). |
| [`slide_show_transition`](/slides/python-net/th/aspose.slides/masternotesslide/slide_show_transition/) | Returns the Transition object which contains information about<br/>            how the specified slide advances during a slide show.<br/>            อ่านอย่างเดียว [`ISlideShowTransition`](/slides/python-net/th/aspose.slides/islideshowtransition). |
| [`background`](/slides/python-net/th/aspose.slides/masternotesslide/background/) | Returns slide's background.<br/>            อ่านอย่างเดียว [`IBackground`](/slides/python-net/th/aspose.slides/ibackground). |
| [`hyperlink_queries`](/slides/python-net/th/aspose.slides/masternotesslide/hyperlink_queries/) | Provides easy access to contained hyperlinks.<br/>            อ่านอย่างเดียว [`IHyperlinkQueries`](/slides/python-net/th/aspose.slides/ihyperlinkqueries). |
| [`show_master_shapes`](/slides/python-net/th/aspose.slides/masternotesslide/show_master_shapes/) | Specifies if shapes on the master slide should be shown on slides or not.<br/>            For master slide itself this property always returns `false`.<br/>            อ่าน/เขียน **bool**. |
| [`presentation`](/slides/python-net/th/aspose.slides/masternotesslide/presentation/) | Returns IPresentation interface.<br/>            อ่านอย่างเดียว [`IPresentation`](/slides/python-net/th/aspose.slides/ipresentation). |
| [`header_footer_manager`](/slides/python-net/th/aspose.slides/masternotesslide/header_footer_manager/) | Returns HeaderFooter manager of the master notes slide.<br/>            อ่านอย่างเดียว [`IMasterHandoutSlideHeaderFooterManager`](/slides/python-net/th/aspose.slides/imasterhandoutslideheaderfootermanager). |
| [`theme_manager`](/slides/python-net/th/aspose.slides/masternotesslide/theme_manager/) | Returns the theme manager.<br/>            อ่านอย่างเดียว [`IMasterThemeManager`](/slides/python-net/th/aspose.slides.theme/imasterthememanager). |
| [`notes_style`](/slides/python-net/th/aspose.slides/masternotesslide/notes_style/) | Returns the style of a notes text.<br/>            อ่านอย่างเดียว [`ITextStyle`](/slides/python-net/th/aspose.slides/itextstyle). |
| [`drawing_guides`](/slides/python-net/th/aspose.slides/masternotesslide/drawing_guides/) | Returns a collection of drawing guides for the master notes slide.<br/>            อ่านอย่างเดียว [`IDrawingGuidesCollection`](/slides/python-net/th/aspose.slides/idrawingguidescollection) |
| [`slide`](/slides/python-net/th/aspose.slides/masternotesslide/slide/) |  |

## เมธอด

| เมธอด | คำอธิบาย |
| :- | :- |
| [`join_portions_with_same_formatting(self)`](/slides/python-net/th/aspose.slides/masternotesslide/join_portions_with_same_formatting/#) | Joins runs with same formatting in all paragraphs all acceptable shapes. |
| [`join_portions_with_same_formatting(self, collection)`](/slides/python-net/th/aspose.slides/masternotesslide/join_portions_with_same_formatting/#ishapecollection) | Joins runs with same formatting in all paragraphs in all acceptable shapes. |
| [`equals(self, slide)`](/slides/python-net/th/aspose.slides/masternotesslide/equals/#ibaseslide) | Determines whether the two IBaseSlide instances are equal.<br/>            Returning value is calculated based on slide's structure and static content.<br/>            Two slides are equal if all shapes, styles, texts, animation and other settings. etc. are equal. The comparison doesn't take into account unique identifier values, e.g. SlideId and dynamic content, e.g. current date value in Date Placeholder. |
| [`create_theme_effective(self)`](/slides/python-net/th/aspose.slides/masternotesslide/create_theme_effective/#) | Returns an effective theme for this slide. |
| [`find_shape_by_alt_text(self, alt_text)`](/slides/python-net/th/aspose.slides/masternotesslide/find_shape_by_alt_text/#str) | Finds first occurrence of a shape with the specified alternative text. |


### ดูเพิ่มเติม
* คลาส [`BaseSlide`](/slides/python-net/th/aspose.slides/baseslide)
* คลาส [`MasterNotesSlide`](/slides/python-net/th/aspose.slides/masternotesslide)
* โมดูล [`aspose.slides`](/slides/python-net/th/aspose.slides)
* ไลบรารี [`Aspose.Slides`](/slides/python-net)