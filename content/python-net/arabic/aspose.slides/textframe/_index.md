---
title: TextFrame class
second_title: Aspose.Slides للـ Python عبر .NET API Reference
description: 
type: docs
url: /ar/aspose.slides/textframe/
---
## فئة TextFrame

يمثل TextFrame.

يوفر نوع TextFrame الأعضاء التالية:

## الخصائص

| خاصية | وصف |
| :- | :- |
| [`paragraphs`](/slides/python-net/ar/aspose.slides/textframe/paragraphs/) | يعيد قائمة بجميع الفقرات في الإطار.<br/>            للقراءة فقط [`IParagraphCollection`](/slides/python-net/ar/aspose.slides/iparagraphcollection). |
| [`text`](/slides/python-net/ar/aspose.slides/textframe/text/) | يحصل أو يضع النص العادي لـ TextFrame.<br/>            للقراءة والكتابة **str**. |
| [`text_frame_format`](/slides/python-net/ar/aspose.slides/textframe/text_frame_format/) | يعيد كائن التنسيق لهذا الكائن TextFrame.<br/>            للقراءة فقط [`ITextFrameFormat`](/slides/python-net/ar/aspose.slides/itextframeformat). |
| [`hyperlink_queries`](/slides/python-net/ar/aspose.slides/textframe/hyperlink_queries/) | يوفر وصولًا سهلاً إلى الروابط التشعبية المحتواة.<br/>            للقراءة فقط [`IHyperlinkQueries`](/slides/python-net/ar/aspose.slides/ihyperlinkqueries). |
| [`slide`](/slides/python-net/ar/aspose.slides/textframe/slide/) | يعيد الشريحة الأصلية لـ TextFrame.<br/>            للقراءة فقط [`IBaseSlide`](/slides/python-net/ar/aspose.slides/ibaseslide). |
| [`presentation`](/slides/python-net/ar/aspose.slides/textframe/presentation/) | يعيد العرض الأصلي لـ TextFrame.<br/>            للقراءة فقط [`IPresentation`](/slides/python-net/ar/aspose.slides/ipresentation). |
| [`parent_shape`](/slides/python-net/ar/aspose.slides/textframe/parent_shape/) | يعيد الشكل الأصل أو None إذا لم ينفذ الكائن الأصلي واجهة IShape<br/>            للقراءة فقط [`IShape`](/slides/python-net/ar/aspose.slides/ishape). |
| [`parent_cell`](/slides/python-net/ar/aspose.slides/textframe/parent_cell/) | يعيد الخلية الأصل أو None إذا لم ينفذ الكائن الأصلي واجهة ICell.<br/>            للقراءة فقط [`ICell`](/slides/python-net/ar/aspose.slides/icell). |

## الطرق

| طريقة | وصف |
| :- | :- |
| [`highlight_text(self, text, highlight_color)`](/slides/python-net/ar/aspose.slides/textframe/highlight_text/#str-asposeslidescolor) | يُبرز جميع التطابقات للنص العيني باللون المحدد. |
| [`highlight_text(self, text, highlight_color, options)`](/slides/python-net/ar/aspose.slides/textframe/highlight_text/#str-asposeslidescolor-itexthighlightingoptions) | يُبرز جميع التطابقات للنص العيني باللون المحدد. |
| [`highlight_text(self, text, highlight_color, options, callback)`](/slides/python-net/ar/aspose.slides/textframe/highlight_text/#str-asposeslidescolor-itextsearchoptions-ifindresultcallback) | يُبرز جميع التطابقات للنص العيني باللون المحدد. |
| [`highlight_regex(self, regex, highlight_color, options)`](/slides/python-net/ar/aspose.slides/textframe/highlight_regex/#str-asposeslidescolor-itexthighlightingoptions) | يُبرز جميع التطابقات للتعبير النمطي باللون المحدد. |
| [`highlight_regex(self, regex, highlight_color)`](/slides/python-net/ar/aspose.slides/textframe/highlight_regex/#str-asposeslidescolor) | يُبرز جميع التطابقات للتعبير النمطي باللون المحدد. |
| [`join_portions_with_same_formatting(self)`](/slides/python-net/ar/aspose.slides/textframe/join_portions_with_same_formatting/#) | يدمج المقاطع ذات التنسيق نفسه في جميع الفقرات. |
| [`split_text_by_columns(self)`](/slides/python-net/ar/aspose.slides/textframe/split_text_by_columns/#) | يفصل محتوى النص للـ [`ITextFrame`](/slides/python-net/ar/aspose.slides/itextframe) إلى مصفوفة من السلاسل،  <br/>            حيث يتطابق كل عنصر مع عمود نص منفصل داخل الإطار. |
| [`replace_text(self, old_text, new_text, options, callback)`](/slides/python-net/ar/aspose.slides/textframe/replace_text/#str-str-itextsearchoptions-ifindresultcallback) | يستبدل جميع مرات ظهور النص المحدد بنص آخر محدد. |
| [`replace_regex(self, regex, new_text)`](/slides/python-net/ar/aspose.slides/textframe/replace_regex/#str-str) | يستبدل جميع تطابقات التعبير النمطي بالسلسلة المحددة. |
| [`get_text_rect(self)`](/slides/python-net/ar/aspose.slides/textframe/get_text_rect/#) | يحصل على مستطيل النص المحدد بواسطة هندسة الشكل الأصلي. |

### انظر أيضًا
* وحدة [`aspose.slides`](/slides/python-net/ar/aspose.slides)
* مكتبة [`Aspose.Slides`](/slides/python-net)