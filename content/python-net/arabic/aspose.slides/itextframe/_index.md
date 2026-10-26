---
title: ITextFrame class
second_title: Aspose.Slides للغة Python عبر .NET مرجع API
description: 
type: docs
url: /ar/aspose.slides/itextframe/
---
## فئة ITextFrame

يمثل TextFrame.

نوع ITextFrame يعرض الأعضاء التالية:

## الخصائص

| الخاصية | الوصف |
| :- | :- |
| [`paragraphs`](/slides/python-net/ar/aspose.slides/itextframe/paragraphs/) | إرجاع قائمة جميع الفقرات في الإطار.<br/>            للقراءة فقط [`IParagraphCollection`](/slides/python-net/ar/aspose.slides/iparagraphcollection). |
| [`text`](/slides/python-net/ar/aspose.slides/itextframe/text/) | الحصول على نص عادي أو تعيينه لإطار النص.<br/>            للقراءة والكتابة **str**. |
| [`text_frame_format`](/slides/python-net/ar/aspose.slides/itextframe/text_frame_format/) | إرجاع كائن التنسيق لهذا كائن TextFrame.<br/>            للقراءة فقط [`ITextFrameFormat`](/slides/python-net/ar/aspose.slides/itextframeformat). |
| [`hyperlink_queries`](/slides/python-net/ar/aspose.slides/itextframe/hyperlink_queries/) | يوفر وصولًا سهلاً إلى الروابط التشعبية المتضمنة.<br/>            للقراءة فقط [`IHyperlinkQueries`](/slides/python-net/ar/aspose.slides/ihyperlinkqueries). |
| [`parent_shape`](/slides/python-net/ar/aspose.slides/itextframe/parent_shape/) | إرجاع الشكل الأب أو None إذا كان الكائن الأب لا يطبق واجهة IShape<br/>            للقراءة فقط [`IShape`](/slides/python-net/ar/aspose.slides/ishape). |
| [`parent_cell`](/slides/python-net/ar/aspose.slides/itextframe/parent_cell/) | إرجاع الخلية الأب أو None إذا كان الكائن الأب لا يطبق واجهة ICell.<br/>            للقراءة فقط [`ICell`](/slides/python-net/ar/aspose.slides/icell). |
| [`slide`](/slides/python-net/ar/aspose.slides/itextframe/slide/) |  |
| [`presentation`](/slides/python-net/ar/aspose.slides/itextframe/presentation/) |  |

## الطرق

| الطريقة | الوصف |
| :- | :- |
| [`highlight_text(self, text, highlight_color)`](/slides/python-net/ar/aspose.slides/itextframe/highlight_text/#str-asposeslidescolor) | يُبرِز جميع مطابقت النص العيني باللون المحدد. |
| [`highlight_text(self, text, highlight_color, options)`](/slides/python-net/ar/aspose.slides/itextframe/highlight_text/#str-asposeslidescolor-itexthighlightingoptions) | يُبرِز جميع مطابقت النص العيني باللون المحدد. |
| [`highlight_text(self, text, highlight_color, options, callback)`](/slides/python-net/ar/aspose.slides/itextframe/highlight_text/#str-asposeslidescolor-itextsearchoptions-ifindresultcallback) | يُبرِز جميع مطابقت النص العيني باللون المحدد. |
| [`highlight_regex(self, regex, highlight_color)`](/slides/python-net/ar/aspose.slides/itextframe/highlight_regex/#str-asposeslidescolor) | يُبرِز جميع مطابقت التعبير النمطي باللون المحدد. |
| [`highlight_regex(self, regex, highlight_color, options)`](/slides/python-net/ar/aspose.slides/itextframe/highlight_regex/#str-asposeslidescolor-itexthighlightingoptions) | يُبرِز جميع مطابقت التعبير النمطي باللون المحدد. |
| [`join_portions_with_same_formatting(self)`](/slides/python-net/ar/aspose.slides/itextframe/join_portions_with_same_formatting/#) | يجمع القطاعات ذات التنسيق نفسه في جميع الفقرات. |
| [`split_text_by_columns(self)`](/slides/python-net/ar/aspose.slides/itextframe/split_text_by_columns/#) | يقسم محتوى النص لـ [`ITextFrame`](/slides/python-net/ar/aspose.slides/itextframe) إلى مصفوفة من السلاسل،<br/>            حيث يتطابق كل عنصر مع عمود نص منفصل داخل الإطار. |
| [`replace_text(self, old_text, new_text, options, callback)`](/slides/python-net/ar/aspose.slides/itextframe/replace_text/#str-str-itextsearchoptions-ifindresultcallback) | يستبدل جميع حدوث النص المحدد بنص محدد آخر. |
| [`replace_regex(self, regex, new_text)`](/slides/python-net/ar/aspose.slides/itextframe/replace_regex/#str-str) | يستبدل جميع مطابقة التعبير النمطي بالسلسلة المحددة. |

### انظر أيضًا
* الوحدة [`aspose.slides`](/slides/python-net/ar/aspose.slides)
* المكتبة [`Aspose.Slides`](/slides/python-net)