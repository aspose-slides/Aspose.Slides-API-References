---
title: NotesSlide class
second_title: Aspose.Slides for Python via .NET API referenciája
description: 
type: docs
url: /hu/aspose.slides/notesslide/
---
## NotesSlide osztály

Egy megjegyzésdiát képvisel egy prezentációban.

**Inheritance:**[`NotesSlide`](/slides/python-net/hu/aspose.slides/notesslide) → [`BaseSlide`](/slides/python-net/hu/aspose.slides/baseslide)

A NotesSlide típus a következő tagokat teszi közzé:

## Tulajdonságok

| Property | Description |
| :- | :- |
| [`shapes`](/slides/python-net/hu/aspose.slides/notesslide/shapes/) | Returns the shapes of a slide.<br/>            Csak olvasható [`IShapeCollection`](/slides/python-net/hu/aspose.slides/ishapecollection). |
| [`controls`](/slides/python-net/hu/aspose.slides/notesslide/controls/) | Returns the collection of ActiveX controls on a slide.<br/>            Csak olvasható [`IControlCollection`](/slides/python-net/hu/aspose.slides/icontrolcollection). |
| [`name`](/slides/python-net/hu/aspose.slides/notesslide/name/) | Returns or sets the name of a slide.<br/>            Olvasás/írás **str**. |
| [`slide_id`](/slides/python-net/hu/aspose.slides/notesslide/slide_id/) | Returns the ID of a slide.<br/>            Csak olvasható **int**. |
| [`custom_data`](/slides/python-net/hu/aspose.slides/notesslide/custom_data/) | Returns the slide's custom data.<br/>            Csak olvasható [`ICustomData`](/slides/python-net/hu/aspose.slides/icustomdata). |
| [`timeline`](/slides/python-net/hu/aspose.slides/notesslide/timeline/) | Returns animation timeline object.<br/>            Csak olvasható [`IAnimationTimeLine`](/slides/python-net/hu/aspose.slides/ianimationtimeline). |
| [`slide_show_transition`](/slides/python-net/hu/aspose.slides/notesslide/slide_show_transition/) | Returns the Transition object which contains information about<br/>            how the specified slide advances during a slide show.<br/>            Csak olvasható [`ISlideShowTransition`](/slides/python-net/hu/aspose.slides/islideshowtransition). |
| [`background`](/slides/python-net/hu/aspose.slides/notesslide/background/) | Returns slide's background.<br/>            Csak olvasható [`IBackground`](/slides/python-net/hu/aspose.slides/ibackground). |
| [`hyperlink_queries`](/slides/python-net/hu/aspose.slides/notesslide/hyperlink_queries/) | Provides easy access to contained hyperlinks.<br/>            Csak olvasható [`IHyperlinkQueries`](/slides/python-net/hu/aspose.slides/ihyperlinkqueries). |
| [`show_master_shapes`](/slides/python-net/hu/aspose.slides/notesslide/show_master_shapes/) | Specifies if shapes on the master slide should be shown on slides or not.<br/>            Olvasás/írás **bool**. |
| [`presentation`](/slides/python-net/hu/aspose.slides/notesslide/presentation/) | Returns IPresentation interface.<br/>            Csak olvasható [`IPresentation`](/slides/python-net/hu/aspose.slides/ipresentation). |
| [`header_footer_manager`](/slides/python-net/hu/aspose.slides/notesslide/header_footer_manager/) | Returns HeaderFooter manager of the notes slide.<br/>            Csak olvasható [`INotesSlideHeaderFooterManager`](/slides/python-net/hu/aspose.slides/inotesslideheaderfootermanager). |
| [`notes_text_frame`](/slides/python-net/hu/aspose.slides/notesslide/notes_text_frame/) | Returns a TextFrame with notes' text if there is one.<br/>            Csak olvasható [`ITextFrame`](/slides/python-net/hu/aspose.slides/itextframe). |
| [`theme_manager`](/slides/python-net/hu/aspose.slides/notesslide/theme_manager/) | Returns the overriding theme manager.<br/>            Csak olvasható [`IOverrideThemeManager`](/slides/python-net/hu/aspose.slides.theme/ioverridethememanager). |
| [`parent_slide`](/slides/python-net/hu/aspose.slides/notesslide/parent_slide/) | Returns the parent slide.<br/>            Csak olvasható [`ISlide`](/slides/python-net/hu/aspose.slides/islide). |
| [`slide`](/slides/python-net/hu/aspose.slides/notesslide/slide/) |  |

## Módszerek

| Method | Description |
| :- | :- |
| [`join_portions_with_same_formatting(self)`](/slides/python-net/hu/aspose.slides/notesslide/join_portions_with_same_formatting/#) | Joins runs with same formatting in all paragraphs all acceptable shapes. |
| [`join_portions_with_same_formatting(self, collection)`](/slides/python-net/hu/aspose.slides/notesslide/join_portions_with_same_formatting/#ishapecollection) | Joins runs with same formatting in all paragraphs in all acceptable shapes. |
| [`equals(self, slide)`](/slides/python-net/hu/aspose.slides/notesslide/equals/#ibaseslide) | Determines whether the two IBaseSlide instances are equal.<br/>            Returning value is calculated based on slide's structure and static content.<br/>            Two slides are equal if all shapes, styles, texts, animation and other settings. etc. are equal. The comparison doesn't take into account unique identifier values, e.g. SlideId and dynamic content, e.g. current date value in Date Placeholder. |
| [`create_theme_effective(self)`](/slides/python-net/hu/aspose.slides/notesslide/create_theme_effective/#) | Returns an effective theme for this slide. |
| [`find_shape_by_alt_text(self, alt_text)`](/slides/python-net/hu/aspose.slides/notesslide/find_shape_by_alt_text/#str) | Finds first occurrence of a shape with the specified alternative text. |


### Lásd még
* osztály [`BaseSlide`](/slides/python-net/hu/aspose.slides/baseslide)
* osztály [`NotesSlide`](/slides/python-net/hu/aspose.slides/notesslide)
* modul [`aspose.slides`](/slides/python-net/hu/aspose.slides)
* könyvtár [`Aspose.Slides`](/slides/python-net)