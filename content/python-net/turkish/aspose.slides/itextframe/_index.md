---
title: ITextFrame class
second_title: Aspose.Slides for Python via .NET API Referansı
description: 
type: docs
url: /tr/aspose.slides/itextframe/
---
## ITextFrame sınıf

Bir TextFrame'i temsil eder.

ITextFrame türü aşağıdaki üyeleri sunar:

## Özellikler

| Özellik | Açıklama |
| :- | :- |
| [`paragraphs`](/slides/python-net/tr/aspose.slides/itextframe/paragraphs/) | Bir çerçevedeki tüm paragrafarın listesini döndürür.<br/>            Salt okunur [`IParagraphCollection`](/slides/python-net/tr/aspose.slides/iparagraphcollection). |
| [`text`](/slides/python-net/tr/aspose.slides/itextframe/text/) | Bir TextFrame için düz metni alır veya ayarlar.<br/>            Okunur/yazılabilir **str**. |
| [`text_frame_format`](/slides/python-net/tr/aspose.slides/itextframe/text_frame_format/) | Bu TextFrame nesnesi için biçimlendirme nesnesini döndürür.<br/>            Salt okunur [`ITextFrameFormat`](/slides/python-net/tr/aspose.slides/itextframeformat). |
| [`hyperlink_queries`](/slides/python-net/tr/aspose.slides/itextframe/hyperlink_queries/) | İçerdiği hiperlinklere kolay erişim sağlar.<br/>            Salt okunur [`IHyperlinkQueries`](/slides/python-net/tr/aspose.slides/ihyperlinkqueries). |
| [`parent_shape`](/slides/python-net/tr/aspose.slides/itextframe/parent_shape/) | Üst şekli döndürür veya ebeveyn nesne IShape arayüzünü uygulamıyorsa None döndürür<br/>            Salt okunur [`IShape`](/slides/python-net/tr/aspose.slides/ishape). |
| [`parent_cell`](/slides/python-net/tr/aspose.slides/itextframe/parent_cell/) | Üst hücreyi döndürür veya ebeveyn nesne ICell arayüzünü uygulamıyorsa None döndürür.<br/>            Salt okunur [`ICell`](/slides/python-net/tr/aspose.slides/icell). |
| [`slide`](/slides/python-net/tr/aspose.slides/itextframe/slide/) |  |
| [`presentation`](/slides/python-net/tr/aspose.slides/itextframe/presentation/) |  |

## Yöntemler

| Yöntem | Açıklama |
| :- | :- |
| [`highlight_text(self, text, highlight_color)`](/slides/python-net/tr/aspose.slides/itextframe/highlight_text/#str-asposeslidescolor) | Örnek metnin tüm eşleşmelerini belirtilen renk ile vurgular. |
| [`highlight_text(self, text, highlight_color, options)`](/slides/python-net/tr/aspose.slides/itextframe/highlight_text/#str-asposeslidescolor-itexthighlightingoptions) | Örnek metnin tüm eşleşmelerini belirtilen renk ile vurgular. |
| [`highlight_text(self, text, highlight_color, options, callback)`](/slides/python-net/tr/aspose.slides/itextframe/highlight_text/#str-asposeslidescolor-itextsearchoptions-ifindresultcallback) | Örnek metnin tüm eşleşmelerini belirtilen renk ile vurgular. |
| [`highlight_regex(self, regex, highlight_color)`](/slides/python-net/tr/aspose.slides/itextframe/highlight_regex/#str-asposeslidescolor) | Düzenli ifadenin tüm eşleşmelerini belirtilen renk ile vurgular. |
| [`highlight_regex(self, regex, highlight_color, options)`](/slides/python-net/tr/aspose.slides/itextframe/highlight_regex/#str-asposeslidescolor-itexthighlightingoptions) | Düzenli ifadenin tüm eşleşmelerini belirtilen renk ile vurgular. |
| [`get_text_rect(self)`](/slides/python-net/tr/aspose.slides/itextframe/get_text_rect/#) | Üst şeklin geometrisi tarafından tanımlanan metin dikdörtgenini alır. |
| [`join_portions_with_same_formatting(self)`](/slides/python-net/tr/aspose.slides/itextframe/join_portions_with_same_formatting/#) | Tüm paragraflarda aynı biçimlendirmeye sahip koşu parçalarını birleştirir. |
| [`split_text_by_columns(self)`](/slides/python-net/tr/aspose.slides/itextframe/split_text_by_columns/#) | [`ITextFrame`](/slides/python-net/tr/aspose.slides/itextframe)'nin metin içeriğini dize dizisine böler, <br/>            burada her öğe çerçeve içinde ayrı bir metin sütununa karşılık gelir. |
| [`replace_text(self, old_text, new_text, options, callback)`](/slides/python-net/tr/aspose.slides/itextframe/replace_text/#str-str-itextsearchoptions-ifindresultcallback) | Belirtilen metnin tüm oluşumlarını başka bir belirtilen metinle değiştirir. |
| [`replace_regex(self, regex, new_text)`](/slides/python-net/tr/aspose.slides/itextframe/replace_regex/#str-str) | Düzenli ifadenin tüm eşleşmelerini belirtilen dizeyle değiştirir. |

### Ayrıca Bakınız
* modül [`aspose.slides`](/slides/python-net/tr/aspose.slides)
* kütüphane [`Aspose.Slides`](/slides/python-net)