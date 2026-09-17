---
title: TextFrame class
second_title: مرجع API لـ Aspose.Slides للـ Python عبر .NET
description: 
type: docs
url: /ar/aspose.slides/textframe/
---
## فئة TextFrame

يمثل TextFrame.

يعرض نوع TextFrame الأعضاء التالية:

## الخصائص

| Property | Description |
| :- | :- |
| [`paragraphs`](/slides/python-net/ar/aspose.slides/textframe/paragraphs/) | يُرجع قائمة بجميع الفقرات في الإطار.<br/>            للقراءة فقط [`IParagraphCollection`](/slides/python-net/ar/aspose.slides/iparagraphcollection). |
| [`text`](/slides/python-net/ar/aspose.slides/textframe/text/) | يحصل أو يحدد النص العادي لـ TextFrame.<br/>            قابل للقراءة والكتابة **str**. |
| [`text_frame_format`](/slides/python-net/ar/aspose.slides/textframe/text_frame_format/) | يُرجع كائن التنسيق لهذا الكائن TextFrame.<br/>            للقراءة فقط [`ITextFrameFormat`](/slides/python-net/ar/aspose.slides/itextframeformat). |
| [`hyperlink_queries`](/slides/python-net/ar/aspose.slides/textframe/hyperlink_queries/) | يُوفر وصولًا سهلاً إلى الروابط التشعبية المتضمنة.<br/>            للقراءة فقط [`IHyperlinkQueries`](/slides/python-net/ar/aspose.slides/ihyperlinkqueries). |
| [`slide`](/slides/python-net/ar/aspose.slides/textframe/slide/) | يُرجع الشريحة الأم لـ TextFrame.<br/>            للقراءة فقط [`IBaseSlide`](/slides/python-net/ar/aspose.slides/ibaseslide). |
| [`presentation`](/slides/python-net/ar/aspose.slides/textframe/presentation/) | يُرجع العرض التقديمي الأم لـ TextFrame.<br/>            للقراءة فقط [`IPresentation`](/slides/python-net/ar/aspose.slides/ipresentation). |
| [`parent_shape`](/slides/python-net/ar/aspose.slides/textframe/parent_shape/) | يُرجع الشكل الأب أو None إذا لم يُطبق الكائن الأب واجهة IShape<br/>            للقراءة فقط [`IShape`](/slides/python-net/ar/aspose.slides/ishape). |
| [`parent_cell`](/slides/python-net/ar/aspose.slides/textframe/parent_cell/) | يُرجع الخلية الأم أو None إذا لم يُطبق الكائن الأب واجهة ICell.<br/>            للقراءة فقط [`ICell`](/slides/python-net/ar/aspose.slides/icell). |

## الطرق

| Method | Description |
| :- | :- |
| [`highlight_text(self, text, highlight_color)`](/slides/python-net/ar/aspose.slides/textframe/highlight_text/#str-asposepydrawingcolor) | يسلط الضوء على جميع التطابقات للنص العيني باللون المحدد. |
| [`highlight_text(self, text, highlight_color, options)`](/slides/python-net/ar/aspose.slides/textframe/highlight_text/#str-asposepydrawingcolor-itexthighlightingoptions) | يسلط الضوء على جميع التطابقات للنص العيني باللون المحدد. |
| [`highlight_text(self, text, highlight_color, options, callback)`](/slides/python-net/ar/aspose.slides/textframe/highlight_text/#str-asposepydrawingcolor-itextsearchoptions-ifindresultcallback) | يسلط الضوء على جميع التطابقات للنص العيني باللون المحدد. |
| [`highlight_regex(self, regex, highlight_color, options)`](/slides/python-net/ar/aspose.slides/textframe/highlight_regex/#str-asposepydrawingcolor-itexthighlightingoptions) | يسلط الضوء على جميع التطابقات للتعبير النمطي باللون المحدد. |
| [`highlight_regex(self, regex, highlight_color)`](/slides/python-net/ar/aspose.slides/textframe/highlight_regex/#str-asposepydrawingcolor) | يسلط الضوء على جميع التطابقات للتعبير النمطي باللون المحدد. |
| [`join_portions_with_same_formatting(self)`](/slides/python-net/ar/aspose.slides/textframe/join_portions_with_same_formatting/#) | ينضم المقاطع ذات التنسيق المتطابق في جميع الفقرات. |
| [`split_text_by_columns(self)`](/slides/python-net/ar/aspose.slides/textframe/split_text_by_columns/#) | يقسم محتوى النص لـ [`ITextFrame`](/slides/python-net/ar/aspose.slides/itextframe) إلى مصفوفة من السلاسل،  <br/>            حيث يتطابق كل عنصر مع عمود نص منفصل داخل الإطار. |
| [`replace_text(self, old_text, new_text, options, callback)`](/slides/python-net/ar/aspose.slides/textframe/replace_text/#str-str-itextsearchoptions-ifindresultcallback) | يستبدل جميعOccurrences للنص المحدد بنص آخر محدد. |
| [`replace_regex(self, regex, new_text)`](/slides/python-net/ar/aspose.slides/textframe/replace_regex/#str-str) | يستبدل جميع التطابقات للتعبير النمطي بالسلسلة المحددة. |

### انظر أيضًا
* الوحدة [`aspose.slides`](/slides/python-net/ar/aspose.slides)
* المكتبة [`Aspose.Slides`](/slides/python-net)