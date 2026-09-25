---
title: TextFrame class
second_title: Aspose.Slides for Python via .NET API Referansı
description: 
type: docs
url: /tr/aspose.slides/textframe/
---
## TextFrame sınıfı

Bir TextFrame'i temsil eder.

TextFrame türü aşağıdaki üyeleri içerir:

## Özellikler

| Özellik | Açıklama |
| :- | :- |
| [`paragraphs`](/slides/python-net/tr/aspose.slides/textframe/paragraphs/) | Bir çerçevedeki tüm paragrafların listesini döndürür.<br/>            Yalnızca okuma [`IParagraphCollection`](/slides/python-net/tr/aspose.slides/iparagraphcollection). |
| [`text`](/slides/python-net/tr/aspose.slides/textframe/text/) | Bir TextFrame için düz metni alır veya ayarlar.<br/>            Okuma/yazma **str**. |
| [`text_frame_format`](/slides/python-net/tr/aspose.slides/textframe/text_frame_format/) | Bu TextFrame nesnesi için biçimlendirme nesnesini döndürür.<br/>            Yalnızca okuma [`ITextFrameFormat`](/slides/python-net/tr/aspose.slides/itextframeformat). |
| [`hyperlink_queries`](/slides/python-net/tr/aspose.slides/textframe/hyperlink_queries/) | İçerilen bağlantılara kolay erişim sağlar.<br/>            Yalnızca okuma [`IHyperlinkQueries`](/slides/python-net/tr/aspose.slides/ihyperlinkqueries). |
| [`slide`](/slides/python-net/tr/aspose.slides/textframe/slide/) | Bir TextFrame'in üst slaytını döndürür.<br/>            Yalnızca okuma [`IBaseSlide`](/slides/python-net/tr/aspose.slides/ibaseslide). |
| [`presentation`](/slides/python-net/tr/aspose.slides/textframe/presentation/) | Bir TextFrame'in üst sunumunu döndürür.<br/>            Yalnızca okuma [`IPresentation`](/slides/python-net/tr/aspose.slides/ipresentation). |
| [`parent_shape`](/slides/python-net/tr/aspose.slides/textframe/parent_shape/) | Üst şekli döndürür veya üst nesne IShape arabirimini uygulamıyorsa None döndürür<br/>            Yalnızca okuma [`IShape`](/slides/python-net/tr/aspose.slides/ishape). |
| [`parent_cell`](/slides/python-net/tr/aspose.slides/textframe/parent_cell/) | Üst hücreyi döndürür veya üst nesne ICell arabirimini uygulamıyorsa None döndürür.<br/>            Yalnızca okuma [`ICell`](/slides/python-net/tr/aspose.slides/icell). |

## Yöntemler

| Yöntem | Açıklama |
| :- | :- |
| [`highlight_text(self, text, highlight_color)`](/slides/python-net/tr/aspose.slides/textframe/highlight_text/#str-asposeslidescolor) | Örnek metnin tüm eşleşmelerini belirtilen renk ile vurgular. |
| [`highlight_text(self, text, highlight_color, options)`](/slides/python-net/tr/aspose.slides/textframe/highlight_text/#str-asposeslidescolor-itexthighlightingoptions) | Örnek metnin tüm eşleşmelerini belirtilen renk ile vurgular. |
| [`highlight_text(self, text, highlight_color, options, callback)`](/slides/python-net/tr/aspose.slides/textframe/highlight_text/#str-asposeslidescolor-itextsearchoptions-ifindresultcallback) | Örnek metnin tüm eşleşmelerini belirtilen renk ile vurgular. |
| [`highlight_regex(self, regex, highlight_color, options)`](/slides/python-net/tr/aspose.slides/textframe/highlight_regex/#str-asposeslidescolor-itexthighlightingoptions) | Düzenli ifadenin tüm eşleşmelerini belirtilen renk ile vurgular. |
| [`highlight_regex(self, regex, highlight_color)`](/slides/python-net/tr/aspose.slides/textframe/highlight_regex/#str-asposeslidescolor) | Düzenli ifadenin tüm eşleşmelerini belirtilen renk ile vurgular. |
| [`join_portions_with_same_formatting(self)`](/slides/python-net/tr/aspose.slides/textframe/join_portions_with_same_formatting/#) | Tüm paragraflarda aynı biçimlendirmeye sahip bölümleri birleştirir. |
| [`split_text_by_columns(self)`](/slides/python-net/tr/aspose.slides/textframe/split_text_by_columns/#) | [`ITextFrame`](/slides/python-net/tr/aspose.slides/itextframe) metin içeriğini bir dizi stringe ayırır,  <br/>            burada her öğe çerçevedeki ayrı bir metin sütununa karşılık gelir. |
| [`replace_text(self, old_text, new_text, options, callback)`](/slides/python-net/tr/aspose.slides/textframe/replace_text/#str-str-itextsearchoptions-ifindresultcallback) | Belirtilen metnin tüm görünümlerini başka bir belirtilen metinle değiştirir. |
| [`replace_regex(self, regex, new_text)`](/slides/python-net/tr/aspose.slides/textframe/replace_regex/#str-str) | Düzenli ifadenin tüm eşleşmelerini belirtilen string ile değiştirir. |

### Ayrıca Bakınız
* modül [`aspose.slides`](/slides/python-net/tr/aspose.slides)
* kütüphane [`Aspose.Slides`](/slides/python-net)