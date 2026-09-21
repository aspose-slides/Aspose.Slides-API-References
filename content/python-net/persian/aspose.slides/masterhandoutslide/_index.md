---
title: MasterHandoutSlide class
second_title: مرجع API Aspose.Slides برای پایتون از طریق .NET
description: 
type: docs
url: /fa/aspose.slides/masterhandoutslide/
---
## MasterHandoutSlide کلاس

نمایش‌دهنده اسلاید اصلی برای جزوه‌ها.

**ارث‌بری:**[`MasterHandoutSlide`](/slides/python-net/fa/aspose.slides/masterhandoutslide) → [`BaseSlide`](/slides/python-net/fa/aspose.slides/baseslide)

نوع MasterHandoutSlide اعضای زیر را در اختیار می‌گذارد:

## خصوصیات

| خاصیت | توضیح |
| :- | :- |
| [`shapes`](/slides/python-net/fa/aspose.slides/masterhandoutslide/shapes/) | Returns the shapes of a slide.<br/>            فقط خواندنی [`IShapeCollection`](/slides/python-net/fa/aspose.slides/ishapecollection). |
| [`controls`](/slides/python-net/fa/aspose.slides/masterhandoutslide/controls/) | Returns the collection of ActiveX controls on a slide.<br/>            فقط خواندنی [`IControlCollection`](/slides/python-net/fa/aspose.slides/icontrolcollection). |
| [`name`](/slides/python-net/fa/aspose.slides/masterhandoutslide/name/) | Returns or sets the name of a slide.<br/>            قابل خواندن و نوشتن **str**. |
| [`slide_id`](/slides/python-net/fa/aspose.slides/masterhandoutslide/slide_id/) | Returns the ID of a slide.<br/>            فقط خواندنی **int**. |
| [`custom_data`](/slides/python-net/fa/aspose.slides/masterhandoutslide/custom_data/) | Returns the slide's custom data.<br/>            فقط خواندنی [`ICustomData`](/slides/python-net/fa/aspose.slides/icustomdata). |
| [`timeline`](/slides/python-net/fa/aspose.slides/masterhandoutslide/timeline/) | Returns animation timeline object.<br/>            فقط خواندنی [`IAnimationTimeLine`](/slides/python-net/fa/aspose.slides/ianimationtimeline). |
| [`slide_show_transition`](/slides/python-net/fa/aspose.slides/masterhandoutslide/slide_show_transition/) | Returns the Transition object which contains information about<br/>            how the specified slide advances during a slide show.<br/>            فقط خواندنی [`ISlideShowTransition`](/slides/python-net/fa/aspose.slides/islideshowtransition). |
| [`background`](/slides/python-net/fa/aspose.slides/masterhandoutslide/background/) | Returns slide's background.<br/>            فقط خواندنی [`IBackground`](/slides/python-net/fa/aspose.slides/ibackground). |
| [`hyperlink_queries`](/slides/python-net/fa/aspose.slides/masterhandoutslide/hyperlink_queries/) | Provides easy access to contained hyperlinks.<br/>            فقط خواندنی [`IHyperlinkQueries`](/slides/python-net/fa/aspose.slides/ihyperlinkqueries). |
| [`show_master_shapes`](/slides/python-net/fa/aspose.slides/masterhandoutslide/show_master_shapes/) | Specifies if shapes on the master slide should be shown on slides or not.<br/>            For master slide itself this property always returns `false`.<br/>            قابل خواندن و نوشتن **bool**. |
| [`presentation`](/slides/python-net/fa/aspose.slides/masterhandoutslide/presentation/) | Returns IPresentation interface.<br/>            فقط خواندنی [`IPresentation`](/slides/python-net/fa/aspose.slides/ipresentation). |
| [`header_footer_manager`](/slides/python-net/fa/aspose.slides/masterhandoutslide/header_footer_manager/) | Returns HeaderFooter manager of the master handout slide.<br/>            فقط خواندنی [`IMasterHandoutSlideHeaderFooterManager`](/slides/python-net/fa/aspose.slides/imasterhandoutslideheaderfootermanager). |
| [`theme_manager`](/slides/python-net/fa/aspose.slides/masterhandoutslide/theme_manager/) | Returns the theme manager.<br/>            فقط خواندنی [`IMasterThemeManager`](/slides/python-net/fa/aspose.slides.theme/imasterthememanager). |
| [`drawing_guides`](/slides/python-net/fa/aspose.slides/masterhandoutslide/drawing_guides/) | Returns a collection of drawing guides for the master handout slide.<br/>            فقط خواندنی [`IDrawingGuidesCollection`](/slides/python-net/fa/aspose.slides/idrawingguidescollection) |
| [`slide`](/slides/python-net/fa/aspose.slides/masterhandoutslide/slide/) |  |

## متدها

| متد | توضیح |
| :- | :- |
| [`join_portions_with_same_formatting(self)`](/slides/python-net/fa/aspose.slides/masterhandoutslide/join_portions_with_same_formatting/#) | Joins runs with same formatting in all paragraphs all acceptable shapes. |
| [`join_portions_with_same_formatting(self, collection)`](/slides/python-net/fa/aspose.slides/masterhandoutslide/join_portions_with_same_formatting/#ishapecollection) | Joins runs with same formatting in all paragraphs in all acceptable shapes. |
| [`equals(self, slide)`](/slides/python-net/fa/aspose.slides/masterhandoutslide/equals/#ibaseslide) | Determines whether the two IBaseSlide instances are equal.<br/>            Returning value is calculated based on slide's structure and static content.<br/>            Two slides are equal if all shapes, styles, texts, animation and other settings. etc. are equal. The comparison doesn't take into account unique identifier values, e.g. SlideId and dynamic content, e.g. current date value in Date Placeholder. |
| [`create_theme_effective(self)`](/slides/python-net/fa/aspose.slides/masterhandoutslide/create_theme_effective/#) | Returns an effective theme for this slide. |
| [`find_shape_by_alt_text(self, alt_text)`](/slides/python-net/fa/aspose.slides/masterhandoutslide/find_shape_by_alt_text/#str) | Finds first occurrence of a shape with the specified alternative text. |


### همچنین ببینید
* کلاس [`BaseSlide`](/slides/python-net/fa/aspose.slides/baseslide)
* کلاس [`MasterHandoutSlide`](/slides/python-net/fa/aspose.slides/masterhandoutslide)
* ماژول [`aspose.slides`](/slides/python-net/fa/aspose.slides)
* کتابخانه [`Aspose.Slides`](/slides/python-net)