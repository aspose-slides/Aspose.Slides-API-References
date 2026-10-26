---
title: IBaseSlide class
second_title: Aspose.Slides per Python via .NET Riferimento API
description: 
type: docs
url: /it/aspose.slides/ibaseslide/
---
## IBaseSlide classe

Rappresenta i dati comuni per tutti i tipi di diapositiva.

Il tipo IBaseSlide espone i seguenti membri:

## Proprietà

| Property | Description |
| :- | :- |
| [`shapes`](/slides/python-net/it/aspose.slides/ibaseslide/shapes/) | Returns the shapes of a slide.<br/>            Sola lettura [`IShapeCollection`](/slides/python-net/it/aspose.slides/ishapecollection). |
| [`controls`](/slides/python-net/it/aspose.slides/ibaseslide/controls/) | Returns the collection of ActiveX controls on a slide.<br/>            Sola lettura [`IControlCollection`](/slides/python-net/it/aspose.slides/icontrolcollection). |
| [`name`](/slides/python-net/it/aspose.slides/ibaseslide/name/) | Returns or sets the name of a slide.<br/>            Lettura/scrittura **str**. |
| [`slide_id`](/slides/python-net/it/aspose.slides/ibaseslide/slide_id/) | Returns the ID of a slide.<br/>            Sola lettura **int**. |
| [`custom_data`](/slides/python-net/it/aspose.slides/ibaseslide/custom_data/) | Returns the slide's custom data.<br/>            Sola lettura [`ICustomData`](/slides/python-net/it/aspose.slides/icustomdata). |
| [`timeline`](/slides/python-net/it/aspose.slides/ibaseslide/timeline/) | Returns animation timeline object.<br/>            Sola lettura [`IAnimationTimeLine`](/slides/python-net/it/aspose.slides/ianimationtimeline). |
| [`slide_show_transition`](/slides/python-net/it/aspose.slides/ibaseslide/slide_show_transition/) | Returns the TransitionEx object which contains information about<br/>            how the specified slide advances during a slide show.<br/>            Sola lettura [`ISlideShowTransition`](/slides/python-net/it/aspose.slides/islideshowtransition). |
| [`background`](/slides/python-net/it/aspose.slides/ibaseslide/background/) | Returns slide's background.<br/>            Sola lettura [`IBackground`](/slides/python-net/it/aspose.slides/ibackground). |
| [`hyperlink_queries`](/slides/python-net/it/aspose.slides/ibaseslide/hyperlink_queries/) | Provides easy access to contained hyperlinks.<br/>            Sola lettura [`IHyperlinkQueries`](/slides/python-net/it/aspose.slides/ihyperlinkqueries). |
| [`show_master_shapes`](/slides/python-net/it/aspose.slides/ibaseslide/show_master_shapes/) | Specifies if shapes on the master slide should be shown on slides or not.<br/>            For master slide itself this property always returns `false`.<br/>            Lettura/scrittura **bool**. |
| [`slide`](/slides/python-net/it/aspose.slides/ibaseslide/slide/) |  |
| [`presentation`](/slides/python-net/it/aspose.slides/ibaseslide/presentation/) |  |

## Metodi

| Method | Description |
| :- | :- |
| [`find_shape_by_alt_text(self, alt_text)`](/slides/python-net/it/aspose.slides/ibaseslide/find_shape_by_alt_text/#str) | Finds first occurrence of a shape with the specified alternative text. |
| [`join_portions_with_same_formatting(self)`](/slides/python-net/it/aspose.slides/ibaseslide/join_portions_with_same_formatting/#) | Joins runs with same formatting in all paragraphs in all acceptable shapes. |
| [`equals(self, slide)`](/slides/python-net/it/aspose.slides/ibaseslide/equals/#ibaseslide) | Determines whether the two IBaseSlide instances are equal.<br/>            Returning value is calculated based on slide's structure and static content.<br/>            Two slides are equal if all shapes, styles, texts, animation and other settings. etc. are equal. The comparison doesn't take into account unique identifier values, e.g. SlideId and dynamic content, e.g. current date value in Date Placeholder. |
| [`create_theme_effective(self)`](/slides/python-net/it/aspose.slides/ibaseslide/create_theme_effective/#) |  |


### Vedi anche
* modulo [`aspose.slides`](/slides/python-net/it/aspose.slides)
* libreria [`Aspose.Slides`](/slides/python-net)