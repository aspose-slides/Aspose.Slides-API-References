---
title: NotesSlide class
second_title: Aspose.Slides for Python via .NET API 參考
description: 
type: docs
url: /zh-hant/aspose.slides/notesslide/
---
## NotesSlide 類別

Represents a notes slide in a presentation.

**繼承:**[`NotesSlide`](/slides/python-net/zh-hant/aspose.slides/notesslide) → [`BaseSlide`](/slides/python-net/zh-hant/aspose.slides/baseslide)

The NotesSlide type exposes the following members:

## 屬性

| Property | 說明 |
| :- | :- |
| [`shapes`](/slides/python-net/zh-hant/aspose.slides/notesslide/shapes/) | Returns the shapes of a slide.<br/>            唯讀 [`IShapeCollection`](/slides/python-net/zh-hant/aspose.slides/ishapecollection). |
| [`controls`](/slides/python-net/zh-hant/aspose.slides/notesslide/controls/) | Returns the collection of ActiveX controls on a slide.<br/>            唯讀 [`IControlCollection`](/slides/python-net/zh-hant/aspose.slides/icontrolcollection). |
| [`name`](/slides/python-net/zh-hant/aspose.slides/notesslide/name/) | Returns or sets the name of a slide.<br/>            可讀寫 **str**. |
| [`slide_id`](/slides/python-net/zh-hant/aspose.slides/notesslide/slide_id/) | Returns the ID of a slide.<br/>            唯讀 **int**. |
| [`custom_data`](/slides/python-net/zh-hant/aspose.slides/notesslide/custom_data/) | Returns the slide's custom data.<br/>            唯讀 [`ICustomData`](/slides/python-net/zh-hant/aspose.slides/icustomdata). |
| [`timeline`](/slides/python-net/zh-hant/aspose.slides/notesslide/timeline/) | Returns animation timeline object.<br/>            唯讀 [`IAnimationTimeLine`](/slides/python-net/zh-hant/aspose.slides/ianimationtimeline). |
| [`slide_show_transition`](/slides/python-net/zh-hant/aspose.slides/notesslide/slide_show_transition/) | Returns the Transition object which contains information about<br/>            how the specified slide advances during a slide show.<br/>            唯讀 [`ISlideShowTransition`](/slides/python-net/zh-hant/aspose.slides/islideshowtransition). |
| [`background`](/slides/python-net/zh-hant/aspose.slides/notesslide/background/) | Returns slide's background.<br/>            唯讀 [`IBackground`](/slides/python-net/zh-hant/aspose.slides/ibackground). |
| [`hyperlink_queries`](/slides/python-net/zh-hant/aspose.slides/notesslide/hyperlink_queries/) | Provides easy access to contained hyperlinks.<br/>            唯讀 [`IHyperlinkQueries`](/slides/python-net/zh-hant/aspose.slides/ihyperlinkqueries). |
| [`show_master_shapes`](/slides/python-net/zh-hant/aspose.slides/notesslide/show_master_shapes/) | Specifies if shapes on the master slide should be shown on slides or not.<br/>            可讀寫 **bool**. |
| [`presentation`](/slides/python-net/zh-hant/aspose.slides/notesslide/presentation/) | Returns IPresentation interface.<br/>            唯讀 [`IPresentation`](/slides/python-net/zh-hant/aspose.slides/ipresentation). |
| [`header_footer_manager`](/slides/python-net/zh-hant/aspose.slides/notesslide/header_footer_manager/) | Returns HeaderFooter manager of the notes slide.<br/>            唯讀 [`INotesSlideHeaderFooterManager`](/slides/python-net/zh-hant/aspose.slides/inotesslideheaderfootermanager). |
| [`notes_text_frame`](/slides/python-net/zh-hant/aspose.slides/notesslide/notes_text_frame/) | Returns a TextFrame with notes' text if there is one.<br/>            唯讀 [`ITextFrame`](/slides/python-net/zh-hant/aspose.slides/itextframe). |
| [`theme_manager`](/slides/python-net/zh-hant/aspose.slides/notesslide/theme_manager/) | Returns the overriding theme manager.<br/>            唯讀 [`IOverrideThemeManager`](/slides/python-net/zh-hant/aspose.slides.theme/ioverridethememanager). |
| [`parent_slide`](/slides/python-net/zh-hant/aspose.slides/notesslide/parent_slide/) | Returns the parent slide.<br/>            唯讀 [`ISlide`](/slides/python-net/zh-hant/aspose.slides/islide). |
| [`slide`](/slides/python-net/zh-hant/aspose.slides/notesslide/slide/) |  |

## 方法

| Method | 說明 |
| :- | :- |
| [`join_portions_with_same_formatting(self)`](/slides/python-net/zh-hant/aspose.slides/notesslide/join_portions_with_same_formatting/#) | Joins runs with same formatting in all paragraphs all acceptable shapes. |
| [`join_portions_with_same_formatting(self, collection)`](/slides/python-net/zh-hant/aspose.slides/notesslide/join_portions_with_same_formatting/#ishapecollection) | Joins runs with same formatting in all paragraphs in all acceptable shapes. |
| [`equals(self, slide)`](/slides/python-net/zh-hant/aspose.slides/notesslide/equals/#ibaseslide) | Determines whether the two IBaseSlide instances are equal.<br/>            Returning value is calculated based on slide's structure and static content.<br/>            Two slides are equal if all shapes, styles, texts, animation and other settings. etc. are equal. The comparison doesn't take into account unique identifier values, e.g. SlideId and dynamic content, e.g. current date value in Date Placeholder. |
| [`create_theme_effective(self)`](/slides/python-net/zh-hant/aspose.slides/notesslide/create_theme_effective/#) | Returns an effective theme for this slide. |
| [`find_shape_by_alt_text(self, alt_text)`](/slides/python-net/zh-hant/aspose.slides/notesslide/find_shape_by_alt_text/#str) | Finds first occurrence of a shape with the specified alternative text. |


### 另見
* 類別 [`BaseSlide`](/slides/python-net/zh-hant/aspose.slides/baseslide)
* 類別 [`NotesSlide`](/slides/python-net/zh-hant/aspose.slides/notesslide)
* 模組 [`aspose.slides`](/slides/python-net/zh-hant/aspose.slides)
* 函式庫 [`Aspose.Slides`](/slides/python-net)