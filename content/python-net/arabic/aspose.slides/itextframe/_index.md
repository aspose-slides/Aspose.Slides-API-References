---
title: ITextFrame class
second_title: مرجع API Aspose.Slides للبايثون عبر .NET
description: 
type: docs
url: /ar/aspose.slides/itextframe/
---
## ITextFrame فئة

يمثّل TextFrame.

يكشف نوع ITextFrame عن الأعضاء التالية:

## الخصائص

| الخاصية | الوصف |
| :- | :- |
| [`paragraphs`](/slides/python-net/ar/aspose.slides/itextframe/paragraphs/) | يعيد قائمة كل الفقرات في الإطار.<br/>            للقراءة فقط [`IParagraphCollection`](/slides/python-net/ar/aspose.slides/iparagraphcollection). |
| [`text`](/slides/python-net/ar/aspose.slides/itextframe/text/) | يحصل أو يضبط النص البسيط لـ TextFrame.<br/>            قابل للقراءة والكتابة **str**. |
| [`text_frame_format`](/slides/python-net/ar/aspose.slides/itextframe/text_frame_format/) | يعيد كائن التنسيق لهذا الكائن TextFrame.<br/>            للقراءة فقط [`ITextFrameFormat`](/slides/python-net/ar/aspose.slides/itextframeformat). |
| [`hyperlink_queries`](/slides/python-net/ar/aspose.slides/itextframe/hyperlink_queries/) | يوفر وصولاً سهلاً إلى الروابط التشعبية الموجودة.<br/>            للقراءة فقط [`IHyperlinkQueries`](/slides/python-net/ar/aspose.slides/ihyperlinkqueries). |
| [`parent_shape`](/slides/python-net/ar/aspose.slides/itextframe/parent_shape/) | يعيد الشكل الأب أو None إذا لم ينفّذ الكائن الأب واجهة IShape<br/>            للقراءة فقط [`IShape`](/slides/python-net/ar/aspose.slides/ishape). |
| [`parent_cell`](/slides/python-net/ar/aspose.slides/itextframe/parent_cell/) | يعيد الخلية الأم أو None إذا لم ينفّذ الكائن الأب واجهة ICell.<br/>            للقراءة فقط [`ICell`](/slides/python-net/ar/aspose.slides/icell). |
| [`slide`](/slides/python-net/ar/aspose.slides/itextframe/slide/) |  |
| [`presentation`](/slides/python-net/ar/aspose.slides/itextframe/presentation/) |  |

## الطرق

| الطريقة | الوصف |
| :- | :- |
| [`highlight_text(self, text, highlight_color)`](/slides/python-net/ar/aspose.slides/itextframe/highlight_text/#str-asposeslidescolor) | يبرز جميع التطابقات للنص العيني باللون المحدد. |
| [`highlight_text(self, text, highlight_color, options)`](/slides/python-net/ar/aspose.slides/itextframe/highlight_text/#str-asposeslidescolor-itexthighlightingoptions) | يبرز جميع التطابقات للنص العيني باللون المحدد. |
| [`highlight_text(self, text, highlight_color, options, callback)`](/slides/python-net/ar/aspose.slides/itextframe/highlight_text/#str-asposeslidescolor-itextsearchoptions-ifindresultcallback) | يبرز جميع التطابقات للنص العيني باللون المحدد. |
| [`highlight_regex(self, regex, highlight_color)`](/slides/python-net/ar/aspose.slides/itextframe/highlight_regex/#str-asposeslidescolor) | يبرز جميع التطابقات للتعبير النمطي باللون المحدد. |
| [`highlight_regex(self, regex, highlight_color, options)`](/slides/python-net/ar/aspose.slides/itextframe/highlight_regex/#str-asposeslidescolor-itexthighlightingoptions) | يبرز جميع التطابقات للتعبير النمطي باللون المحدد. |
| [`get_text_rect(self)`](/slides/python-net/ar/aspose.slides/itextframe/get_text_rect/#) | يحصل على مستطيل النص المحدد بواسطة هندسة الشكل الأب. |
| [`join_portions_with_same_formatting(self)`](/slides/python-net/ar/aspose.slides/itextframe/join_portions_with_same_formatting/#) | ينضمّ المقاطع ذات التنسيق نفسه في جميع الفقرات. |
| [`split_text_by_columns(self)`](/slides/python-net/ar/aspose.slides/itextframe/split_text_by_columns/#) | يقسم محتوى النص لـ [`ITextFrame`](/slides/python-net/ar/aspose.slides/itextframe) إلى مصفوفة من السلاسل،  <br/>            حيث يتطابق كل عنصر مع عمود نص منفصل داخل الإطار. |
| [`replace_text(self, old_text, new_text, options, callback)`](/slides/python-net/ar/aspose.slides/itextframe/replace_text/#str-str-itextsearchoptions-ifindresultcallback) | يستبدل جميع حدوث النص المحدد بنص محدد آخر. |
| [`replace_regex(self, regex, new_text)`](/slides/python-net/ar/aspose.slides/itextframe/replace_regex/#str-str) | يستبدل جميع التطابقات للتعبير النمطي بالسلسلة المحددة. |

### انظر أيضًا
* الوحدة [`aspose.slides`](/slides/python-net/ar/aspose.slides)
* المكتبة [`Aspose.Slides`](/slides/python-net)