---
title: ICommentCollection class
second_title: Aspose.Slides for Python via .NET API Referansı
description: 
type: docs
url: /tr/aspose.slides/icommentcollection/
---
## ICommentCollection sınıf

Tek bir yazarın yorumlarının bir koleksiyonunu temsil eder.

ICommentCollection türü aşağıdaki üyeleri sunar:

Belirtilen dizindeki öğeyi alır.
            Yalnızca okuma [`IComment`](/slides/python-net/tr/aspose.slides/icomment).

## Dizinleyici

| Ad | Açıklama |
| :- | :- |
| [`[index]`](/slides/python-net/tr/aspose.slides/icommentcollection/__getitem__/) |  |

## Yöntemler

| Yöntem | Açıklama |
| :- | :- |
| [`to_array(self)`](/slides/python-net/tr/aspose.slides/icommentcollection/to_array/#) | Tüm yorumları içeren bir dizi oluşturur ve döndürür. |
| [`to_array(self, start_index, count)`](/slides/python-net/tr/aspose.slides/icommentcollection/to_array/#int-int) | Belirtilen aralıktaki tüm yorumları içeren bir dizi oluşturur ve döndürür. |
| [`add_comment(self, text, slide, position, creation_time)`](/slides/python-net/tr/aspose.slides/icommentcollection/add_comment/#str-islide-asposeslidespointf-datetime) | Koleksiyonun sonuna yeni bir yorum ekler. |
| [`add_modern_comment(self, text, slide, shape, position, creation_time)`](/slides/python-net/tr/aspose.slides/icommentcollection/add_modern_comment/#str-islide-ishape-asposeslidespointf-datetime) | Koleksiyonun sonuna yeni modern bir yorum ekler. |
| [`insert_comment(self, index, text, slide, position, creation_time)`](/slides/python-net/tr/aspose.slides/icommentcollection/insert_comment/#int-str-islide-asposeslidespointf-datetime) | Belirtilen dizine bir koleksiyona yeni yorum ekler. |
| [`insert_modern_comment(self, index, text, slide, shape, position, creation_time)`](/slides/python-net/tr/aspose.slides/icommentcollection/insert_modern_comment/#int-str-islide-ishape-asposeslidespointf-datetime) | Belirtilen dizinde bir koleksiyona yeni modern yorum ekler. |
| [`remove_at(self, index)`](/slides/python-net/tr/aspose.slides/icommentcollection/remove_at/#int) | Koleksiyonda belirtilen dizindeki öğeyi kaldırır. |
| [`remove(self, comment)`](/slides/python-net/tr/aspose.slides/icommentcollection/remove/#icomment) | Koleksiyondaki belirtilen yorumun ilk oluşumunu kaldırır. |
| [`clear(self)`](/slides/python-net/tr/aspose.slides/icommentcollection/clear/#) | Koleksiyondan tüm yorumları kaldırır. |


### Bakınız
* sınıf [`IComment`](/slides/python-net/tr/aspose.slides/icomment)
* modül [`aspose.slides`](/slides/python-net/tr/aspose.slides)
* kütüphane [`Aspose.Slides`](/slides/python-net)