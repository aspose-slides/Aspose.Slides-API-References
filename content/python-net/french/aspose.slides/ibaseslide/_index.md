---
title: IBaseSlide class
second_title: Aspose.Slides pour Python via .NET Référence de l'API
description: 
type: docs
url: /fr/aspose.slides/ibaseslide/
---
## IBaseSlide classe

Represents common data for all slide types.

The IBaseSlide type exposes the following members:

## Propriétés

| Property | Description |
| :- | :- |
| [`shapes`](/slides/python-net/fr/aspose.slides/ibaseslide/shapes/) | Returns the shapes of a slide.<br/>            Lecture seule [`IShapeCollection`](/slides/python-net/fr/aspose.slides/ishapecollection). |
| [`controls`](/slides/python-net/fr/aspose.slides/ibaseslide/controls/) | Returns the collection of ActiveX controls on a slide.<br/>            Lecture seule [`IControlCollection`](/slides/python-net/fr/aspose.slides/icontrolcollection). |
| [`name`](/slides/python-net/fr/aspose.slides/ibaseslide/name/) | Returns or sets the name of a slide.<br/>            Lecture/écriture **str**. |
| [`slide_id`](/slides/python-net/fr/aspose.slides/ibaseslide/slide_id/) | Returns the ID of a slide.<br/>            Lecture seule **int**. |
| [`custom_data`](/slides/python-net/fr/aspose.slides/ibaseslide/custom_data/) | Returns the slide's custom data.<br/>            Lecture seule [`ICustomData`](/slides/python-net/fr/aspose.slides/icustomdata). |
| [`timeline`](/slides/python-net/fr/aspose.slides/ibaseslide/timeline/) | Returns animation timeline object.<br/>            Lecture seule [`IAnimationTimeLine`](/slides/python-net/fr/aspose.slides/ianimationtimeline). |
| [`slide_show_transition`](/slides/python-net/fr/aspose.slides/ibaseslide/slide_show_transition/) | Returns the TransitionEx object which contains information about<br/>            la façon dont la diapositive spécifiée progresse pendant une présentation.<br/>            Lecture seule [`ISlideShowTransition`](/slides/python-net/fr/aspose.slides/islideshowtransition). |
| [`background`](/slides/python-net/fr/aspose.slides/ibaseslide/background/) | Returns slide's background.<br/>            Lecture seule [`IBackground`](/slides/python-net/fr/aspose.slides/ibackground). |
| [`hyperlink_queries`](/slides/python-net/fr/aspose.slides/ibaseslide/hyperlink_queries/) | Provides easy access to contained hyperlinks.<br/>            Lecture seule [`IHyperlinkQueries`](/slides/python-net/fr/aspose.slides/ihyperlinkqueries). |
| [`show_master_shapes`](/slides/python-net/fr/aspose.slides/ibaseslide/show_master_shapes/) | Specifies if shapes on the master slide should be shown on slides or not.<br/>            For master slide itself this property always returns `false`.<br/>            Lecture/écriture **bool**. |
| [`slide`](/slides/python-net/fr/aspose.slides/ibaseslide/slide/) |  |
| [`presentation`](/slides/python-net/fr/aspose.slides/ibaseslide/presentation/) |  |

## Méthodes

| Method | Description |
| :- | :- |
| [`find_shape_by_alt_text(self, alt_text)`](/slides/python-net/fr/aspose.slides/ibaseslide/find_shape_by_alt_text/#str) | Finds first occurrence of a shape with the specified alternative text. |
| [`join_portions_with_same_formatting(self)`](/slides/python-net/fr/aspose.slides/ibaseslide/join_portions_with_same_formatting/#) | Joins runs with same formatting in all paragraphs in all acceptable shapes. |
| [`equals(self, slide)`](/slides/python-net/fr/aspose.slides/ibaseslide/equals/#ibaseslide) | Determines whether the two IBaseSlide instances are equal.<br/>            Returning value is calculated based on slide's structure and static content.<br/>            Two slides are equal if all shapes, styles, texts, animation and other settings. etc. are equal. The comparison doesn't take into account unique identifier values, e.g. SlideId and dynamic content, e.g. current date value in Date Placeholder. |
| [`create_theme_effective(self)`](/slides/python-net/fr/aspose.slides/ibaseslide/create_theme_effective/#) |  |


### Voir aussi
* module [`aspose.slides`](/slides/python-net/fr/aspose.slides)
* bibliothèque [`Aspose.Slides`](/slides/python-net)