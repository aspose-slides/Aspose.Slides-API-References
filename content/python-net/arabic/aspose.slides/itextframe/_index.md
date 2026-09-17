---
title: ITextFrame class
second_title: Aspose.Slides للـ Python عبر .NET مرجع API
description: 
type: docs
url: /ar/aspose.slides/itextframe/
---
## ITextFrame فئة

يمثّل TextFrame.

نوع ITextFrame يوفّر الأعضاء التالية:

## الخصائص

| الخاصية | الوصف |
| :- | :- |
| [`paragraphs`](/slides/python-net/ar/aspose.slides/itextframe/paragraphs/) | يُعيد قائمة بجميع الفقرات في الإطار.<br/>            للقراءة فقط [`IParagraphCollection`](/slides/python-net/ar/aspose.slides/iparagraphcollection). |
| [`text`](/slides/python-net/ar/aspose.slides/itextframe/text/) | يحصل أو يعيّن النص العادي لـ TextFrame.<br/>            قراءة/كتابة **str**. |
| [`text_frame_format`](/slides/python-net/ar/aspose.slides/itextframe/text_frame_format/) | يُعيد كائن التنسيق لهذا الكائن TextFrame.<br/>            للقراءة فقط [`ITextFrameFormat`](/slides/python-net/ar/aspose.slides/itextframeformat). |
| [`hyperlink_queries`](/slides/python-net/ar/aspose.slides/itextframe/hyperlink_queries/) | يوفّر وصولاً سهلاً إلى الروابط التشعبية المحتواة.<br/>            للقراءة فقط [`IHyperlinkQueries`](/slides/python-net/ar/aspose.slides/ihyperlinkqueries). |
| [`parent_shape`](/slides/python-net/ar/aspose.slides/itextframe/parent_shape/) | يُعيد الشكل الأب أو None إذا لم يُنفّذ الكائن الأب واجهة IShape<br/>            للقراءة فقط [`IShape`](/slides/python-net/ar/aspose.slides/ishape). |
| [`parent_cell`](/slides/python-net/ar/aspose.slides/itextframe/parent_cell/) | يُعيد الخلية الأب أو None إذا لم يُنفّذ الكائن الأب واجهة ICell.<br/>            للقراءة فقط [`ICell`](/slides/python-net/ar/aspose.slides/icell). |
| [`slide`](/slides/python-net/ar/aspose.slides/itextframe/slide/) |  |
| [`presentation`](/slides/python-net/ar/aspose.slides/itextframe/presentation/) |  |

## الأساليب

| الطريقة | الوصف |
| :- | :- |
| [`highlight_text(self, text, highlight_color)`](/slides/python-net/ar/aspose.slides/itextframe/highlight_text/#str-asposepydrawingcolor) | يُبرز جميع مطابقة النص العيني باللون المحدد. |
| [`highlight_text(self, text, highlight_color, options)`](/slides/python-net/ar/aspose.slides/itextframe/highlight_text/#str-asposepydrawingcolor-itexthighlightingoptions) | يُبرز جميع مطابقة النص العيني باللون المحدد. |
| [`highlight_text(self, text, highlight_color, options, callback)`](/slides/python-net/ar/aspose.slides/itextframe/highlight_text/#str-asposepydrawingcolor-itextsearchoptions-ifindresultcallback) | يُبرز جميع مطابقة النص العيني باللون المحدد. |
| [`highlight_regex(self, regex, highlight_color)`](/slides/python-net/ar/aspose.slides/itextframe/highlight_regex/#str-asposepydrawingcolor) | يُبرز جميع مطابقة التعبير النمطي باللون المحدد. |
| [`highlight_regex(self, regex, highlight_color, options)`](/slides/python-net/ar/aspose.slides/itextframe/highlight_regex/#str-asposepydrawingcolor-itexthighlightingoptions) | يُبرز جميع مطابقة التعبير النمطي باللون المحدد. |
| [`join_portions_with_same_formatting(self)`](/slides/python-net/ar/aspose.slides/itextframe/join_portions_with_same_formatting/#) | يجمع الجُمل ذات التنسيق المتطابق في جميع الفقرات. |
| [`split_text_by_columns(self)`](/slides/python-net/ar/aspose.slides/itextframe/split_text_by_columns/#) | يقسم محتوى النص لـ [`ITextFrame`](/slides/python-net/ar/aspose.slides/itextframe) إلى مصفوفة من السلاسل،  <br/>            حيث كل عنصر يت对应 إلى عمود نص منفصل داخل الإطار. |
| [`replace_text(self, old_text, new_text, options, callback)`](/slides/python-net/ar/aspose.slides/itextframe/replace_text/#str-str-itextsearchoptions-ifindresultcallback) | يستبدل جميع تكرارات النص المحدد بنص آخر محدد. |
| [`replace_regex(self, regex, new_text)`](/slides/python-net/ar/aspose.slides/itextframe/replace_regex/#str-str) | يستبدل جميع مطابقة التعبير النمطي بالسلسلة المحددة. |


### أنظر أيضاً
* الوحدة [`aspose.slides`](/slides/python-net/ar/aspose.slides)
* المكتبة [`Aspose.Slides`](/slides/python-net)