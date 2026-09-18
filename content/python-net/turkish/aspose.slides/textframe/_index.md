---
title: TextFrame class
second_title: Aspose.Slides for Python via .NET API Referansı
description: 
type: docs
url: /tr/aspose.slides/textframe/
---
## TextFrame sınıfı

Bir TextFrame temsil eder.

TextFrame türü aşağıdaki üyeleri sunar:

## Özellikler

| Özellik | Açıklama |
| :- | :- |
| [`paragraphs`](/slides/python-net/tr/aspose.slides/textframe/paragraphs/) | Bir çerçevedeki tüm paragrafların listesini döndürür.<br/>            Salt-okunur [`IParagraphCollection`](/slides/python-net/tr/aspose.slides/iparagraphcollection). |
| [`text`](/slides/python-net/tr/aspose.slides/textframe/text/) | Bir TextFrame için düz metni alır veya ayarlar.<br/>            Okunur/yazılabilir **str**. |
| [`text_frame_format`](/slides/python-net/tr/aspose.slides/textframe/text_frame_format/) | Bu TextFrame nesnesi için biçimlendirme nesnesini döndürür.<br/>            Salt-okunur [`ITextFrameFormat`](/slides/python-net/tr/aspose.slides/itextframeformat). |
| [`hyperlink_queries`](/slides/python-net/tr/aspose.slides/textframe/hyperlink_queries/) | İçerilen köprü bağlantılarına kolay erişim sağlar.<br/>            Salt-okunur [`IHyperlinkQueries`](/slides/python-net/tr/aspose.slides/ihyperlinkqueries). |
| [`slide`](/slides/python-net/tr/aspose.slides/textframe/slide/) | Bir TextFrame'in üst slaytını döndürür.<br/>            Salt-okunur [`IBaseSlide`](/slides/python-net/tr/aspose.slides/ibaseslide). |
| [`presentation`](/slides/python-net/tr/aspose.slides/textframe/presentation/) | Bir TextFrame'in üst sunumunu döndürür.<br/>            Salt-okunur [`IPresentation`](/slides/python-net/tr/aspose.slides/ipresentation). |
| [`parent_shape`](/slides/python-net/tr/aspose.slides/textframe/parent_shape/) | Üst şekli döndürür veya üst nesne IShape arayüzünü uygulamıyorsa None döndürür<br/>            Salt-okunur [`IShape`](/slides/python-net/tr/aspose.slides/ishape). |
| [`parent_cell`](/slides/python-net/tr/aspose.slides/textframe/parent_cell/) | Üst hücreyi döndürür veya üst nesne ICell arayüzünü uygulamıyorsa None döndürür.<br/>            Salt-okunur [`ICell`](/slides/python-net/tr/aspose.slides/icell). |

## Yöntemler

| Yöntem | Açıklama |
| :- | :- |
| [`highlight_text(self, text, highlight_color)`](/slides/python-net/tr/aspose.slides/textframe/highlight_text/#str-asposepydrawingcolor) | Belirtilen renk ile örnek metnin tüm eşleşmelerini vurgular. |
| [`highlight_text(self, text, highlight_color, options)`](/slides/python-net/tr/aspose.slides/textframe/highlight_text/#str-asposepydrawingcolor-itexthighlightingoptions) | Belirtilen renk ile örnek metnin tüm eşleşmelerini vurgular. |
| [`highlight_text(self, text, highlight_color, options, callback)`](/slides/python-net/tr/aspose.slides/textframe/highlight_text/#str-asposepydrawingcolor-itextsearchoptions-ifindresultcallback) | Belirtilen renk ile örnek metnin tüm eşleşmelerini vurgular. |
| [`highlight_regex(self, regex, highlight_color, options)`](/slides/python-net/tr/aspose.slides/textframe/highlight_regex/#str-asposepydrawingcolor-itexthighlightingoptions) | Belirtilen renk ile düzenli ifadenin tüm eşleşmelerini vurgular. |
| [`highlight_regex(self, regex, highlight_color)`](/slides/python-net/tr/aspose.slides/textframe/highlight_regex/#str-asposepydrawingcolor) | Belirtilen renk ile düzenli ifadenin tüm eşleşmelerini vurgular. |
| [`join_portions_with_same_formatting(self)`](/slides/python-net/tr/aspose.slides/textframe/join_portions_with_same_formatting/#) | Tüm paragraflarda aynı biçimlendirmeye sahip yürüyüşleri birleştirir. |
| [`split_text_by_columns(self)`](/slides/python-net/tr/aspose.slides/textframe/split_text_by_columns/#) | Metin içeriğini [`ITextFrame`](/slides/python-net/tr/aspose.slides/itextframe) bir dizi stringe böler, <br/>            burada her öğe çerçeve içinde ayrı bir metin sütununa karşılık gelir. |
| [`replace_text(self, old_text, new_text, options, callback)`](/slides/python-net/tr/aspose.slides/textframe/replace_text/#str-str-itextsearchoptions-ifindresultcallback) | Belirtilen metnin tüm görünümlerini başka bir belirtilen metinle değiştirir. |
| [`replace_regex(self, regex, new_text)`](/slides/python-net/tr/aspose.slides/textframe/replace_regex/#str-str) | Düzenli ifadenin tüm eşleşmelerini belirtilen string ile değiştirir. |


### Ayrıca Bakınız
* modül [`aspose.slides`](/slides/python-net/tr/aspose.slides)
* kütüphane [`Aspose.Slides`](/slides/python-net)