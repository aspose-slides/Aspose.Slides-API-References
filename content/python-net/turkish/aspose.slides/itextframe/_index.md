---
title: ITextFrame class
second_title: Aspose.Slides for Python via .NET API Referansı
description: 
type: docs
url: /tr/aspose.slides/itextframe/
---
## ITextFrame sınıfı

Bir TextFrame'i temsil eder.

ITextFrame türü aşağıdaki üyeleri gösterir:

## Özellikler

| Property | Description |
| :- | :- |
| [`paragraphs`](/slides/python-net/tr/aspose.slides/itextframe/paragraphs/) | Çerçevedeki tüm paragrafların listesini döndürür.<br/>            Salt okunur [`IParagraphCollection`](/slides/python-net/tr/aspose.slides/iparagraphcollection). |
| [`text`](/slides/python-net/tr/aspose.slides/itextframe/text/) | Bir TextFrame için düz metni alır veya ayarlar.<br/>            Okunabilir/Yazılabilir **str**. |
| [`text_frame_format`](/slides/python-net/tr/aspose.slides/itextframe/text_frame_format/) | Bu TextFrame nesnesi için biçimlendirme nesnesini döndürür.<br/>            Salt okunur [`ITextFrameFormat`](/slides/python-net/tr/aspose.slides/itextframeformat). |
| [`hyperlink_queries`](/slides/python-net/tr/aspose.slides/itextframe/hyperlink_queries/) | İçerilen hiperlinklere kolay erişim sağlar.<br/>            Salt okunur [`IHyperlinkQueries`](/slides/python-net/tr/aspose.slides/ihyperlinkqueries). |
| [`parent_shape`](/slides/python-net/tr/aspose.slides/itextframe/parent_shape/) | Üst şekli döndürür veya üst nesne IShape arayüzünü uygulamıyorsa None döndürür.<br/>            Salt okunur [`IShape`](/slides/python-net/tr/aspose.slides/ishape). |
| [`parent_cell`](/slides/python-net/tr/aspose.slides/itextframe/parent_cell/) | Üst hücreyi döndürür veya üst nesne ICell arayüzünü uygulamıyorsa None döndürür.<br/>            Salt okunur [`ICell`](/slides/python-net/tr/aspose.slides/icell). |
| [`slide`](/slides/python-net/tr/aspose.slides/itextframe/slide/) |  |
| [`presentation`](/slides/python-net/tr/aspose.slides/itextframe/presentation/) |  |

## Yöntemler

| Method | Description |
| :- | :- |
| [`highlight_text(self, text, highlight_color)`](/slides/python-net/tr/aspose.slides/itextframe/highlight_text/#str-asposeslidescolor) | Örnek metnin tüm eşleşmelerini belirtilen renkle vurgular. |
| [`highlight_text(self, text, highlight_color, options)`](/slides/python-net/tr/aspose.slides/itextframe/highlight_text/#str-asposeslidescolor-itexthighlightingoptions) | Örnek metnin tüm eşleşmelerini belirtilen renkle vurgular. |
| [`highlight_text(self, text, highlight_color, options, callback)`](/slides/python-net/tr/aspose.slides/itextframe/highlight_text/#str-asposeslidescolor-itextsearchoptions-ifindresultcallback) | Örnek metnin tüm eşleşmelerini belirtilen renkle vurgular. |
| [`highlight_regex(self, regex, highlight_color)`](/slides/python-net/tr/aspose.slides/itextframe/highlight_regex/#str-asposeslidescolor) | Düzenli ifadenin tüm eşleşmelerini belirtilen renkle vurgular. |
| [`highlight_regex(self, regex, highlight_color, options)`](/slides/python-net/tr/aspose.slides/itextframe/highlight_regex/#str-asposeslidescolor-itexthighlightingoptions) | Düzenli ifadenin tüm eşleşmelerini belirtilen renkle vurgular. |
| [`join_portions_with_same_formatting(self)`](/slides/python-net/tr/aspose.slides/itextframe/join_portions_with_same_formatting/#) | Tüm paragraflardaki aynı biçimlendirmeye sahip koşulları birleştirir. |
| [`split_text_by_columns(self)`](/slides/python-net/tr/aspose.slides/itextframe/split_text_by_columns/#) | Metin içeriğini [`ITextFrame`](/slides/python-net/tr/aspose.slides/itextframe) içinde bir dizi stringe ayırır, <br/>            burada her öğe çerçeve içindeki ayrı bir metin sütununa karşılık gelir. |
| [`replace_text(self, old_text, new_text, options, callback)`](/slides/python-net/tr/aspose.slides/itextframe/replace_text/#str-str-itextsearchoptions-ifindresultcallback) | Belirtilen metnin tüm oluşumlarını başka bir belirtilen metinle değiştirir. |
| [`replace_regex(self, regex, new_text)`](/slides/python-net/tr/aspose.slides/itextframe/replace_regex/#str-str) | Düzenli ifadenin tüm eşleşmelerini belirtilen dizeyle değiştirir. |

### Diğer Bağlantılar
* modül [`aspose.slides`](/slides/python-net/tr/aspose.slides)
* kütüphane [`Aspose.Slides`](/slides/python-net)