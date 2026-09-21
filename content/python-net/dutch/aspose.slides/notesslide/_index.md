---
title: NotesSlide class
second_title: Aspose.Slides voor Python via .NET API-referentie
description: 
type: docs
url: /nl/aspose.slides/notesslide/
---
## NotesSlide klasse

Vertegenwoordigt een notes slide in een presentatie.

**Erfenis:**[`NotesSlide`](/slides/python-net/nl/aspose.slides/notesslide) → [`BaseSlide`](/slides/python-net/nl/aspose.slides/baseslide)

Het NotesSlide-type maakt de volgende leden beschikbaar:

## Eigenschappen

| Property | Description |
| :- | :- |
| [`shapes`](/slides/python-net/nl/aspose.slides/notesslide/shapes/) | Returns the shapes of a slide.<br/>            Alleen-lezen [`IShapeCollection`](/slides/python-net/nl/aspose.slides/ishapecollection). |
| [`controls`](/slides/python-net/nl/aspose.slides/notesslide/controls/) | Returns the collection of ActiveX controls on a slide.<br/>            Alleen-lezen [`IControlCollection`](/slides/python-net/nl/aspose.slides/icontrolcollection). |
| [`name`](/slides/python-net/nl/aspose.slides/notesslide/name/) | Returns or sets the name of a slide.<br/>            Lezen/Schrijven **str**. |
| [`slide_id`](/slides/python-net/nl/aspose.slides/notesslide/slide_id/) | Returns the ID of a slide.<br/>            Alleen-lezen **int**. |
| [`custom_data`](/slides/python-net/nl/aspose.slides/notesslide/custom_data/) | Returns the slide's custom data.<br/>            Alleen-lezen [`ICustomData`](/slides/python-net/nl/aspose.slides/icustomdata). |
| [`timeline`](/slides/python-net/nl/aspose.slides/notesslide/timeline/) | Returns animation timeline object.<br/>            Alleen-lezen [`IAnimationTimeLine`](/slides/python-net/nl/aspose.slides/ianimationtimeline). |
| [`slide_show_transition`](/slides/python-net/nl/aspose.slides/notesslide/slide_show_transition/) | Returns the Transition object which contains information about<br/>            how the specified slide advances during a slide show.<br/>            Alleen-lezen [`ISlideShowTransition`](/slides/python-net/nl/aspose.slides/islideshowtransition). |
| [`background`](/slides/python-net/nl/aspose.slides/notesslide/background/) | Returns slide's background.<br/>            Alleen-lezen [`IBackground`](/slides/python-net/nl/aspose.slides/ibackground). |
| [`hyperlink_queries`](/slides/python-net/nl/aspose.slides/notesslide/hyperlink_queries/) | Provides easy access to contained hyperlinks.<br/>            Alleen-lezen [`IHyperlinkQueries`](/slides/python-net/nl/aspose.slides/ihyperlinkqueries). |
| [`show_master_shapes`](/slides/python-net/nl/aspose.slides/notesslide/show_master_shapes/) | Specifies if shapes on the master slide should be shown on slides or not.<br/>            Lezen/Schrijven **bool**. |
| [`presentation`](/slides/python-net/nl/aspose.slides/notesslide/presentation/) | Returns IPresentation interface.<br/>            Alleen-lezen [`IPresentation`](/slides/python-net/nl/aspose.slides/ipresentation). |
| [`header_footer_manager`](/slides/python-net/nl/aspose.slides/notesslide/header_footer_manager/) | Returns HeaderFooter manager of the notes slide.<br/>            Alleen-lezen [`INotesSlideHeaderFooterManager`](/slides/python-net/nl/aspose.slides/inotesslideheaderfootermanager). |
| [`notes_text_frame`](/slides/python-net/nl/aspose.slides/notesslide/notes_text_frame/) | Returns a TextFrame with notes' text if there is one.<br/>            Alleen-lezen [`ITextFrame`](/slides/python-net/nl/aspose.slides/itextframe). |
| [`theme_manager`](/slides/python-net/nl/aspose.slides/notesslide/theme_manager/) | Returns the overriding theme manager.<br/>            Alleen-lezen [`IOverrideThemeManager`](/slides/python-net/nl/aspose.slides.theme/ioverridethememanager). |
| [`parent_slide`](/slides/python-net/nl/aspose.slides/notesslide/parent_slide/) | Returns the parent slide.<br/>            Alleen-lezen [`ISlide`](/slides/python-net/nl/aspose.slides/islide). |
| [`slide`](/slides/python-net/nl/aspose.slides/notesslide/slide/) |  |

## Methoden

| Method | Description |
| :- | :- |
| [`join_portions_with_same_formatting(self)`](/slides/python-net/nl/aspose.slides/notesslide/join_portions_with_same_formatting/#) | Joins runs with same formatting in all paragraphs all acceptable shapes. |
| [`join_portions_with_same_formatting(self, collection)`](/slides/python-net/nl/aspose.slides/notesslide/join_portions_with_same_formatting/#ishapecollection) | Joins runs with same formatting in all paragraphs in all acceptable shapes. |
| [`equals(self, slide)`](/slides/python-net/nl/aspose.slides/notesslide/equals/#ibaseslide) | Determines whether the two IBaseSlide instances are equal.<br/>            Returning value is calculated based on slide's structure and static content.<br/>            Two slides are equal if all shapes, styles, texts, animation and other settings. etc. are equal. The comparison doesn't take into account unique identifier values, e.g. SlideId and dynamic content, e.g. current date value in Date Placeholder. |
| [`create_theme_effective(self)`](/slides/python-net/nl/aspose.slides/notesslide/create_theme_effective/#) | Returns an effective theme for this slide. |
| [`find_shape_by_alt_text(self, alt_text)`](/slides/python-net/nl/aspose.slides/notesslide/find_shape_by_alt_text/#str) | Finds first occurrence of a shape with the specified alternative text. |

### Zie ook
* klasse [`BaseSlide`](/slides/python-net/nl/aspose.slides/baseslide)
* klasse [`NotesSlide`](/slides/python-net/nl/aspose.slides/notesslide)
* module [`aspose.slides`](/slides/python-net/nl/aspose.slides)
* bibliotheek [`Aspose.Slides`](/slides/python-net)