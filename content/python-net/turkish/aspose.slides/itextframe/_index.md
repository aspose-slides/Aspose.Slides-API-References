---
title: ITextFrame class
second_title: Aspose.Slides for Python via .NET API Referansı
description: 
type: docs
url: /tr/aspose.slides/itextframe/
---
## ITextFrame sınıfı

Bir TextFrame'i temsil eder.

ITextFrame tipi aşağıdaki üyeleri ortaya çıkar.

## Özellikler

| Özellik | Açıklama |
| :- | :- |
| [`paragraphs`](/slides/python-net/tr/aspose.slides/itextframe/paragraphs/) | Bir çerçevedeki tüm paragrafların listesini döndürür.<br/>            Yalnızca okuma [`IParagraphCollection`](/slides/python-net/tr/aspose.slides/iparagraphcollection). |
| [`text`](/slides/python-net/tr/aspose.slides/itextframe/text/) | Bir TextFrame için düz metni alır veya ayarlar.<br/>            Okuma/Yazma **str**. |
| [`text_frame_format`](/slides/python-net/tr/aspose.slides/itextframe/text_frame_format/) | Bu TextFrame nesnesi için biçimlendirme nesnesini döndürür.<br/>            Yalnızca okuma [`ITextFrameFormat`](/slides/python-net/tr/aspose.slides/itextframeformat). |
| [`hyperlink_queries`](/slides/python-net/tr/aspose.slides/itextframe/hyperlink_queries/) | İçerilen köprülere kolay erişim sağlar.<br/>            Yalnızca okuma [`IHyperlinkQueries`](/slides/python-net/tr/aspose.slides/ihyperlinkqueries). |
| [`parent_shape`](/slides/python-net/tr/aspose.slides/itextframe/parent_shape/) | Üst şekli döndürür veya üst nesne IShape arayüzünü uygulamıyorsa None döndürür<br/>            Yalnızca okuma [`IShape`](/slides/python-net/tr/aspose.slides/ishape). |
| [`parent_cell`](/slides/python-net/tr/aspose.slides/itextframe/parent_cell/) | Üst hücreyi döndürür veya üst nesne ICell arayüzünü uygulamıyorsa None döndürür.<br/>            Yalnızca okuma [`ICell`](/slides/python-net/tr/aspose.slides/icell). |
| [`slide`](/slides/python-net/tr/aspose.slides/itextframe/slide/) |  |
| [`presentation`](/slides/python-net/tr/aspose.slides/itextframe/presentation/) |  |

## Yöntemler

| Yöntem | Açıklama |
| :- | :- |
| [`highlight_text(self, text, highlight_color)`](/slides/python-net/tr/aspose.slides/itextframe/highlight_text/#str-asposepydrawingcolor) | Örnek metnin tüm eşleşmelerini belirtilen renk ile vurgular. |
| [`highlight_text(self, text, highlight_color, options)`](/slides/python-net/tr/aspose.slides/itextframe/highlight_text/#str-asposepydrawingcolor-itexthighlightingoptions) | Örnek metnin tüm eşleşmelerini belirtilen renk ile vurgular. |
| [`highlight_text(self, text, highlight_color, options, callback)`](/slides/python-net/tr/aspose.slides/itextframe/highlight_text/#str-asposepydrawingcolor-itextsearchoptions-ifindresultcallback) | Örnek metnin tüm eşleşmelerini belirtilen renk ile vurgular. |
| [`highlight_regex(self, regex, highlight_color)`](/slides/python-net/tr/aspose.slides/itextframe/highlight_regex/#str-asposepydrawingcolor) | Düzenli ifadenin tüm eşleşmelerini belirtilen renk ile vurgular. |
| [`highlight_regex(self, regex, highlight_color, options)`](/slides/python-net/tr/aspose.slides/itextframe/highlight_regex/#str-asposepydrawingcolor-itexthighlightingoptions) | Düzenli ifadenin tüm eşleşmelerini belirtilen renk ile vurgular. |
| [`join_portions_with_same_formatting(self)`](/slides/python-net/tr/aspose.slides/itextframe/join_portions_with_same_formatting/#) | Tüm paragraflardaki aynı biçimlendirmeye sahip koşuları birleştirir. |
| [`split_text_by_columns(self)`](/slides/python-net/tr/aspose.slides/itextframe/split_text_by_columns/#) | [`ITextFrame`](/slides/python-net/tr/aspose.slides/itextframe) öğesinin metin içeriğini dize dizisine ayırır, <br/>            her öğe çerçeve içinde ayrı bir metin sütununa karşılık gelir. |
| [`replace_text(self, old_text, new_text, options, callback)`](/slides/python-net/tr/aspose.slides/itextframe/replace_text/#str-str-itextsearchoptions-ifindresultcallback) | Belirtilen metnin tüm olaylarını başka bir belirtilen metinle değiştirir. |
| [`replace_regex(self, regex, new_text)`](/slides/python-net/tr/aspose.slides/itextframe/replace_regex/#str-str) | Düzenli ifadenin tüm eşleşmelerini belirtilen dizeyle değiştirir. |

### Ayrıca Bakınız
* modül [`aspose.slides`](/slides/python-net/tr/aspose.slides)
* kütüphane [`Aspose.Slides`](/slides/python-net)