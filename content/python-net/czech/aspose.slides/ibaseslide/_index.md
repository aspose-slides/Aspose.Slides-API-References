---
title: IBaseSlide class
second_title: Aspose.Slides pro Python přes .NET referenci API
description: 
type: docs
url: /cs/aspose.slides/ibaseslide/
---
## IBaseSlide třída

Represents common data for all slide types.

The IBaseSlide type exposes the following members:

## Vlastnosti

| Property | Description |
| :- | :- |
| [`shapes`](/slides/python-net/cs/aspose.slides/ibaseslide/shapes/) | Returns the shapes of a slide.<br/>            Pouze pro čtení [`IShapeCollection`](/slides/python-net/cs/aspose.slides/ishapecollection). |
| [`controls`](/slides/python-net/cs/aspose.slides/ibaseslide/controls/) | Returns the collection of ActiveX controls on a slide.<br/>            Pouze pro čtení [`IControlCollection`](/slides/python-net/cs/aspose.slides/icontrolcollection). |
| [`name`](/slides/python-net/cs/aspose.slides/ibaseslide/name/) | Returns or sets the name of a slide.<br/>            Čtení/zápis **str**. |
| [`slide_id`](/slides/python-net/cs/aspose.slides/ibaseslide/slide_id/) | Returns the ID of a slide.<br/>            Pouze pro čtení **int**. |
| [`custom_data`](/slides/python-net/cs/aspose.slides/ibaseslide/custom_data/) | Returns the slide's custom data.<br/>            Pouze pro čtení [`ICustomData`](/slides/python-net/cs/aspose.slides/icustomdata). |
| [`timeline`](/slides/python-net/cs/aspose.slides/ibaseslide/timeline/) | Returns animation timeline object.<br/>            Pouze pro čtení [`IAnimationTimeLine`](/slides/python-net/cs/aspose.slides/ianimationtimeline). |
| [`slide_show_transition`](/slides/python-net/cs/aspose.slides/ibaseslide/slide_show_transition/) | Returns the TransitionEx object which contains information about<br/>            how the specified slide advances during a slide show.<br/>            Pouze pro čtení [`ISlideShowTransition`](/slides/python-net/cs/aspose.slides/islideshowtransition). |
| [`background`](/slides/python-net/cs/aspose.slides/ibaseslide/background/) | Returns slide's background.<br/>            Pouze pro čtení [`IBackground`](/slides/python-net/cs/aspose.slides/ibackground). |
| [`hyperlink_queries`](/slides/python-net/cs/aspose.slides/ibaseslide/hyperlink_queries/) | Provides easy access to contained hyperlinks.<br/>            Pouze pro čtení [`IHyperlinkQueries`](/slides/python-net/cs/aspose.slides/ihyperlinkqueries). |
| [`show_master_shapes`](/slides/python-net/cs/aspose.slides/ibaseslide/show_master_shapes/) | Specifies if shapes on the master slide should be shown on slides or not.<br/>            For master slide itself this property always returns `false`.<br/>            Čtení/zápis **bool**. |
| [`slide`](/slides/python-net/cs/aspose.slides/ibaseslide/slide/) |  |
| [`presentation`](/slides/python-net/cs/aspose.slides/ibaseslide/presentation/) |  |

## Metody

| Method | Description |
| :- | :- |
| [`find_shape_by_alt_text(self, alt_text)`](/slides/python-net/cs/aspose.slides/ibaseslide/find_shape_by_alt_text/#str) | Finds first occurrence of a shape with the specified alternative text. |
| [`join_portions_with_same_formatting(self)`](/slides/python-net/cs/aspose.slides/ibaseslide/join_portions_with_same_formatting/#) | Joins runs with same formatting in all paragraphs in all acceptable shapes. |
| [`equals(self, slide)`](/slides/python-net/cs/aspose.slides/ibaseslide/equals/#ibaseslide) | Determines whether the two IBaseSlide instances are equal.<br/>            Returning value is calculated based on slide's structure and static content.<br/>            Two slides are equal if all shapes, styles, texts, animation and other settings. etc. are equal. The comparison doesn't take into account unique identifier values, e.g. SlideId and dynamic content, e.g. current date value in Date Placeholder. |
| [`create_theme_effective(self)`](/slides/python-net/cs/aspose.slides/ibaseslide/create_theme_effective/#) |  |

### Viz také
* modul [`aspose.slides`](/slides/python-net/cs/aspose.slides)
* knihovna [`Aspose.Slides`](/slides/python-net)