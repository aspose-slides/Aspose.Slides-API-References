---
title: Slide class
second_title: Aspose.Slides for Python via .NET API リファレンス
description: 
type: docs
url: /ja/aspose.slides/slide/
---
## Slide クラス

プレゼンテーション内のスライドを表します。

**継承:**[`Slide`](/slides/python-net/ja/aspose.slides/slide) → [`BaseSlide`](/slides/python-net/ja/aspose.slides/baseslide)

Slide タイプは次のメンバーを公開します。

## プロパティ

| プロパティ | 説明 |
| :- | :- |
| [`shapes`](/slides/python-net/ja/aspose.slides/slide/shapes/) | Returns the shapes of a slide.<br/> 読み取り専用 [`IShapeCollection`](/slides/python-net/ja/aspose.slides/ishapecollection)。 |
| [`controls`](/slides/python-net/ja/aspose.slides/slide/controls/) | Returns the collection of ActiveX controls on a slide.<br/> 読み取り専用 [`IControlCollection`](/slides/python-net/ja/aspose.slides/icontrolcollection)。 |
| [`name`](/slides/python-net/ja/aspose.slides/slide/name/) | Returns or sets the name of a slide.<br/> 読み取り/書き込み **str**。 |
| [`slide_id`](/slides/python-net/ja/aspose.slides/slide/slide_id/) | Returns the ID of a slide.<br/> 読み取り専用 **int**。 |
| [`custom_data`](/slides/python-net/ja/aspose.slides/slide/custom_data/) | Returns the slide's custom data.<br/> 読み取り専用 [`ICustomData`](/slides/python-net/ja/aspose.slides/icustomdata)。 |
| [`timeline`](/slides/python-net/ja/aspose.slides/slide/timeline/) | Returns animation timeline object.<br/> 読み取り専用 [`IAnimationTimeLine`](/slides/python-net/ja/aspose.slides/ianimationtimeline)。 |
| [`slide_show_transition`](/slides/python-net/ja/aspose.slides/slide/slide_show_transition/) | Returns the Transition object which contains information about<br/> how the specified slide advances during a slide show.<br/> 読み取り専用 [`ISlideShowTransition`](/slides/python-net/ja/aspose.slides/islideshowtransition)。 |
| [`background`](/slides/python-net/ja/aspose.slides/slide/background/) | Returns slide's background.<br/> 読み取り専用 [`IBackground`](/slides/python-net/ja/aspose.slides/ibackground)。 |
| [`hyperlink_queries`](/slides/python-net/ja/aspose.slides/slide/hyperlink_queries/) | Provides easy access to contained hyperlinks.<br/> 読み取り専用 [`IHyperlinkQueries`](/slides/python-net/ja/aspose.slides/ihyperlinkqueries)。 |
| [`show_master_shapes`](/slides/python-net/ja/aspose.slides/slide/show_master_shapes/) | Specifies if shapes on the master slide should be shown on slides or not.<br/> 読み取り/書き込み **bool**。 |
| [`presentation`](/slides/python-net/ja/aspose.slides/slide/presentation/) | Returns IPresentation interface.<br/> 読み取り専用 [`IPresentation`](/slides/python-net/ja/aspose.slides/ipresentation)。 |
| [`header_footer_manager`](/slides/python-net/ja/aspose.slides/slide/header_footer_manager/) | Returns HeaderFooter manager of the slide.<br/> 読み取り専用 [`ISlideHeaderFooterManager`](/slides/python-net/ja/aspose.slides/islideheaderfootermanager)。 |
| [`theme_manager`](/slides/python-net/ja/aspose.slides/slide/theme_manager/) | Returns the overriding theme manager.<br/> 読み取り専用 [`IOverrideThemeManager`](/slides/python-net/ja/aspose.slides.theme/ioverridethememanager)。 |
| [`slide_number`](/slides/python-net/ja/aspose.slides/slide/slide_number/) | Returns a number of slide.<br/> Index of slide in [`Presentation.slides`](/slides/python-net/ja/aspose.slides/presentation/slides) collection is always equal to SlideNumber - Presentation.FirstSlideNumber.<br/> 読み取り/書き込み **int**。 |
| [`hidden`](/slides/python-net/ja/aspose.slides/slide/hidden/) | Determines whether the specified slide is hidden during a slide show.<br/> 読み取り/書き込み **bool**。 |
| [`layout_slide`](/slides/python-net/ja/aspose.slides/slide/layout_slide/) | Returns or sets the layout slide for the current slide.<br/> 読み取り/書き込み [`ILayoutSlide`](/slides/python-net/ja/aspose.slides/ilayoutslide)。 |
| [`notes_slide_manager`](/slides/python-net/ja/aspose.slides/slide/notes_slide_manager/) | Allow to access notes slide, add and remove it.<br/> 読み取り専用 [`INotesSlideManager`](/slides/python-net/ja/aspose.slides/inotesslidemanager)。 |
| [`slide`](/slides/python-net/ja/aspose.slides/slide/slide/) |  |

## メソッド

| メソッド | 説明 |
| :- | :- |
| [`join_portions_with_same_formatting(self)`](/slides/python-net/ja/aspose.slides/slide/join_portions_with_same_formatting/#) | Joins runs with same formatting in all paragraphs in all acceptable shapes. |
| [`join_portions_with_same_formatting(self, collection)`](/slides/python-net/ja/aspose.slides/slide/join_portions_with_same_formatting/#ishapecollection) | Joins runs with same formatting in all paragraphs in all acceptable shapes. |
| [`get_image(self, scale_x, scale_y)`](/slides/python-net/ja/aspose.slides/slide/get_image/#float-float) | Returns a Thumbnail Image object with custom scaling. |
| [`get_image(self)`](/slides/python-net/ja/aspose.slides/slide/get_image/#) | Returns a Thumbnail Image object (20% of real size). |
| [`get_image(self, image_size)`](/slides/python-net/ja/aspose.slides/slide/get_image/#asposeslidessize) | Returns a Thumbnail Image object with specified size. |
| [`get_image(self, options)`](/slides/python-net/ja/aspose.slides/slide/get_image/#asposeslidesexportitiffoptions) | Returns a Thumbnail tiff image object with specified parameters. |
| [`get_image(self, options)`](/slides/python-net/ja/aspose.slides/slide/get_image/#asposeslidesexportirenderingoptions) | Returns a Thumbnail Image object. |
| [`get_image(self, options, scale_x, scale_y)`](/slides/python-net/ja/aspose.slides/slide/get_image/#asposeslidesexportirenderingoptions-float-float) | Returns a Thumbnail Image object with custom scaling. |
| [`get_image(self, options, image_size)`](/slides/python-net/ja/aspose.slides/slide/get_image/#asposeslidesexportirenderingoptions-asposeslidessize) | Returns a Thumbnail Image object with specified size. |
| [`write_as_svg(self, stream)`](/slides/python-net/ja/aspose.slides/slide/write_as_svg/#iorawiobase) | Saves the slide content as an SVG file. |
| [`write_as_svg(self, stream, svg_options)`](/slides/python-net/ja/aspose.slides/slide/write_as_svg/#iorawiobase-asposeslidesexportisvgoptions) | Saves the slide content as an SVG file. |
| [`equals(self, slide)`](/slides/python-net/ja/aspose.slides/slide/equals/#ibaseslide) | Determines whether the two IBaseSlide instances are equal.<br/> Returning value is calculated based on slide's structure and static content.<br/> Two slides are equal if all shapes, styles, texts, animation and other settings. etc. are equal. The comparison doesn't take into account unique identifier values, e.g. SlideId and dynamic content, e.g. current date value in Date Placeholder. |
| [`create_theme_effective(self)`](/slides/python-net/ja/aspose.slides/slide/create_theme_effective/#) | Returns an effective theme for this slide. |
| [`find_shape_by_alt_text(self, alt_text)`](/slides/python-net/ja/aspose.slides/slide/find_shape_by_alt_text/#str) | Finds first occurrence of a shape with the specified alternative text. |
| [`write_as_emf(self, stream)`](/slides/python-net/ja/aspose.slides/slide/write_as_emf/#iorawiobase) | Saves the slide content as an EMF file. |
| [`remove(self)`](/slides/python-net/ja/aspose.slides/slide/remove/#) | Removes slide from presentation. |
| [`reset(self)`](/slides/python-net/ja/aspose.slides/slide/reset/#) | Resets position, size and formatting of every shape that has a prototype on LayoutSlide. |
| [`get_slide_comments(self, author)`](/slides/python-net/ja/aspose.slides/slide/get_slide_comments/#icommentauthor) | Returns all slide comments added by specific author. |

### 参照
* クラス [`BaseSlide`](/slides/python-net/ja/aspose.slides/baseslide)
* クラス [`Slide`](/slides/python-net/ja/aspose.slides/slide)
* モジュール [`aspose.slides`](/slides/python-net/ja/aspose.slides)
* ライブラリ [`Aspose.Slides`](/slides/python-net)