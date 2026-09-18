---
title: IPortion class
second_title: Aspose.Slides for Python via .NET API Referansı
description: 
type: docs
url: /tr/aspose.slides/iportion/
---
## IPortion sınıfı

Bir metin paragrafı içindeki metin bölümünü temsil eder.

IPortion türü aşağıdaki üyeleri sunar:

## Özellikler

| Özellik | Açıklama |
| :- | :- |
| [`portion_format`](/slides/python-net/tr/aspose.slides/iportion/portion_format/) | Kalıtım uygulanmadan metin bölümünün açıkça ayarlanmış biçimlendirme özelliklerini içeren biçimlendirme nesnesini döndürür.<br/>            Salt okunur [`IPortionFormat`](/slides/python-net/tr/aspose.slides/iportionformat). |
| [`text`](/slides/python-net/tr/aspose.slides/iportion/text/) | Bir bölümün düz metnini alır veya ayarlar.<br/>            Okuma/Yazma **str**. |
| [`field`](/slides/python-net/tr/aspose.slides/iportion/field/) | Bu bölümün bir alanını döndürür.<br/>            Salt okunur [`IField`](/slides/python-net/tr/aspose.slides/ifield). |
| [`slide`](/slides/python-net/tr/aspose.slides/iportion/slide/) |  |
| [`presentation`](/slides/python-net/tr/aspose.slides/iportion/presentation/) |  |

## Yöntemler

| Yöntem | Açıklama |
| :- | :- |
| [`add_field(self, field_type)`](/slides/python-net/tr/aspose.slides/iportion/add_field/#ifieldtype) | Bu bölümü otomatik olarak güncellenen alana dönüştürür. |
| [`add_field(self, internal_string)`](/slides/python-net/tr/aspose.slides/iportion/add_field/#str) | Bu bölümü otomatik olarak güncellenen alana dönüştürür. |
| [`remove_field(self)`](/slides/python-net/tr/aspose.slides/iportion/remove_field/#) | Bu alan bölümünü basit bölüme dönüştürür. |
| [`get_rect(self)`](/slides/python-net/tr/aspose.slides/iportion/get_rect/#) | Bölümü sınırlayan dikdörtgenin koordinatlarını alır. Dikdörtgen, bölümdeki tüm metin satırlarını, boş satırları da içerecek şekilde kapsar.<br/>             |
| [`get_coordinates(self)`](/slides/python-net/tr/aspose.slides/iportion/get_coordinates/#) | Bölümün başlangıcının koordinatlarını alır. Noktanın X koordinatı, sol yan boşluğun dahil olduğu ilk karakterden itibaren bölümün başlangıcını temsil eder.<br/>            Y koordinatı üst yan boşluğu içerir. |


### Ayrıca Bakınız
* modül [`aspose.slides`](/slides/python-net/tr/aspose.slides)
* kütüphane [`Aspose.Slides`](/slides/python-net)