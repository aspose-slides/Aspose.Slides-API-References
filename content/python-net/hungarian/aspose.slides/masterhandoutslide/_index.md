---
title: MasterHandoutSlide class
second_title: Aspose.Slides Pythonhoz .NET API-referencia
description: 
type: docs
url: /hu/aspose.slides/masterhandoutslide/
---
## MasterHandoutSlide osztály

A nyomtatványokhoz tartozó mesterdiát képviseli.

**Öröklődés:**[`MasterHandoutSlide`](/slides/python-net/hu/aspose.slides/masterhandoutslide) → [`BaseSlide`](/slides/python-net/hu/aspose.slides/baseslide)

A MasterHandoutSlide típus a következő tagokat teszi elérhetővé:

## Tulajdonságok

| Tulajdonság | Leírás |
| :- | :- |
| [`shapes`](/slides/python-net/hu/aspose.slides/masterhandoutslide/shapes/) | Returns the shapes of a slide.<br/>            Csak olvasható [`IShapeCollection`](/slides/python-net/hu/aspose.slides/ishapecollection). |
| [`controls`](/slides/python-net/hu/aspose.slides/masterhandoutslide/controls/) | Returns the collection of ActiveX controls on a slide.<br/>            Csak olvasható [`IControlCollection`](/slides/python-net/hu/aspose.slides/icontrolcollection). |
| [`name`](/slides/python-net/hu/aspose.slides/masterhandoutslide/name/) | Returns or sets the name of a slide.<br/>            Olvasás/írás **str**. |
| [`slide_id`](/slides/python-net/hu/aspose.slides/masterhandoutslide/slide_id/) | Returns the ID of a slide.<br/>            Csak olvasható **int**. |
| [`custom_data`](/slides/python-net/hu/aspose.slides/masterhandoutslide/custom_data/) | Returns the slide's custom data.<br/>            Csak olvasható [`ICustomData`](/slides/python-net/hu/aspose.slides/icustomdata). |
| [`timeline`](/slides/python-net/hu/aspose.slides/masterhandoutslide/timeline/) | Returns animation timeline object.<br/>            Csak olvasható [`IAnimationTimeLine`](/slides/python-net/hu/aspose.slides/ianimationtimeline). |
| [`slide_show_transition`](/slides/python-net/hu/aspose.slides/masterhandoutslide/slide_show_transition/) | Returns the Transition object which contains information about<br/>            how the specified slide advances during a slide show.<br/>            Csak olvasható [`ISlideShowTransition`](/slides/python-net/hu/aspose.slides/islideshowtransition). |
| [`background`](/slides/python-net/hu/aspose.slides/masterhandoutslide/background/) | Returns slide's background.<br/>            Csak olvasható [`IBackground`](/slides/python-net/hu/aspose.slides/ibackground). |
| [`hyperlink_queries`](/slides/python-net/hu/aspose.slides/masterhandoutslide/hyperlink_queries/) | Provides easy access to contained hyperlinks.<br/>            Csak olvasható [`IHyperlinkQueries`](/slides/python-net/hu/aspose.slides/ihyperlinkqueries). |
| [`show_master_shapes`](/slides/python-net/hu/aspose.slides/masterhandoutslide/show_master_shapes/) | Specifies if shapes on the master slide should be shown on slides or not.<br/>            For master slide itself this property always returns `false`.<br/>            Olvasás/írás **bool**. |
| [`presentation`](/slides/python-net/hu/aspose.slides/masterhandoutslide/presentation/) | Returns IPresentation interface.<br/>            Csak olvasható [`IPresentation`](/slides/python-net/hu/aspose.slides/ipresentation). |
| [`header_footer_manager`](/slides/python-net/hu/aspose.slides/masterhandoutslide/header_footer_manager/) | Returns HeaderFooter manager of the master handout slide.<br/>            Csak olvasható [`IMasterHandoutSlideHeaderFooterManager`](/slides/python-net/hu/aspose.slides/imasterhandoutslideheaderfootermanager). |
| [`theme_manager`](/slides/python-net/hu/aspose.slides/masterhandoutslide/theme_manager/) | Returns the theme manager.<br/>            Csak olvasható [`IMasterThemeManager`](/slides/python-net/hu/aspose.slides.theme/imasterthememanager). |
| [`drawing_guides`](/slides/python-net/hu/aspose.slides/masterhandoutslide/drawing_guides/) | Returns a collection of drawing guides for the master handout slide.<br/>            Csak olvasható [`IDrawingGuidesCollection`](/slides/python-net/hu/aspose.slides/idrawingguidescollection) |
| [`slide`](/slides/python-net/hu/aspose.slides/masterhandoutslide/slide/) |  |

## Metódusok

| Metódus | Leírás |
| :- | :- |
| [`join_portions_with_same_formatting(self)`](/slides/python-net/hu/aspose.slides/masterhandoutslide/join_portions_with_same_formatting/#) | Joins runs with same formatting in all paragraphs all acceptable shapes. |
| [`join_portions_with_same_formatting(self, collection)`](/slides/python-net/hu/aspose.slides/masterhandoutslide/join_portions_with_same_formatting/#ishapecollection) | Joins runs with same formatting in all paragraphs in all acceptable shapes. |
| [`equals(self, slide)`](/slides/python-net/hu/aspose.slides/masterhandoutslide/equals/#ibaseslide) | Determines whether the two IBaseSlide instances are equal.<br/>            Returning value is calculated based on slide's structure and static content.<br/>            Two slides are equal if all shapes, styles, texts, animation and other settings. etc. are equal. The comparison doesn't take into account unique identifier values, e.g. SlideId and dynamic content, e.g. current date value in Date Placeholder. |
| [`create_theme_effective(self)`](/slides/python-net/hu/aspose.slides/masterhandoutslide/create_theme_effective/#) | Returns an effective theme for this slide. |
| [`find_shape_by_alt_text(self, alt_text)`](/slides/python-net/hu/aspose.slides/masterhandoutslide/find_shape_by_alt_text/#str) | Finds first occurrence of a shape with the specified alternative text. |

### Lásd még
* osztály [`BaseSlide`](/slides/python-net/hu/aspose.slides/baseslide)
* osztály [`MasterHandoutSlide`](/slides/python-net/hu/aspose.slides/masterhandoutslide)
* modul [`aspose.slides`](/slides/python-net/hu/aspose.slides)
* könyvtár [`Aspose.Slides`](/slides/python-net)