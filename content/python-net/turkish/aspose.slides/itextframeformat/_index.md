---
title: ITextFrameFormat class
second_title: Aspose.Slides for Python via .NET API Referansı
description: 
type: docs
url: /tr/aspose.slides/itextframeformat/
---
## ITextFrameFormat sınıfı

Contains the TextFrame's formatting properties.

The ITextFrameFormat type exposes the following members:

## Özellikler

| Özellik | Açıklama |
| :- | :- |
| [`text_style`](/slides/python-net/tr/aspose.slides/itextframeformat/text_style/) | Metnin stilini döndürür.<br/>            Salt okunur [`ITextStyle`](/slides/python-net/tr/aspose.slides/itextstyle). |
| [`margin_left`](/slides/python-net/tr/aspose.slides/itextframeformat/margin_left/) | Bir TextFrame içinde sol kenar boşluğunu (nokta) döndürür veya ayarlar.<br/>            Okunur/yazılır **float**. |
| [`margin_right`](/slides/python-net/tr/aspose.slides/itextframeformat/margin_right/) | Bir TextFrame içinde sağ kenar boşluğunu (nokta) döndürür veya ayarlar.<br/>            Okunur/yazılır **float**. |
| [`margin_top`](/slides/python-net/tr/aspose.slides/itextframeformat/margin_top/) | Bir TextFrame içinde üst kenar boşluğunu (nokta) döndürür veya ayarlar.<br/>            Okunur/yazılır **float**. |
| [`margin_bottom`](/slides/python-net/tr/aspose.slides/itextframeformat/margin_bottom/) | Bir TextFrame içinde alt kenar boşluğunu (nokta) döndürür veya ayarlar.<br/>            Okunur/yazılır **float**. |
| [`wrap_text`](/slides/python-net/tr/aspose.slides/itextframeformat/wrap_text/) | **True** eğer metin TextFrame'in kenarlarında sarılıyorsa.<br/>            Okunur/yazılır [`NullableBool`](/slides/python-net/tr/aspose.slides/nullablebool). |
| [`anchoring_type`](/slides/python-net/tr/aspose.slides/itextframeformat/anchoring_type/) | Bir TextFrame içinde dikey çapa metnini döndürür veya ayarlar.<br/>            Okunur/yazılır [`TextAnchorType`](/slides/python-net/tr/aspose.slides/textanchortype). |
| [`center_text`](/slides/python-net/tr/aspose.slides/itextframeformat/center_text/) | NullableBool.True ise metin kutunun içinde yatay olarak ortalanmalı.<br/>            Okunur/yazılır [`NullableBool`](/slides/python-net/tr/aspose.slides/nullablebool). |
| [`text_vertical_type`](/slides/python-net/tr/aspose.slides/itextframeformat/text_vertical_type/) | Metin yönelimini belirler.<br/>            Bu özellik ve RotationAngle özelliğindeki özel açıdan özetlenen görsel metin döndürme sonucunu verir.<br/>            Okunur/yazılır [`TextVerticalType`](/slides/python-net/tr/aspose.slides/textverticaltype). |
| [`autofit_type`](/slides/python-net/tr/aspose.slides/itextframeformat/autofit_type/) | Metnin otomatik sığdırma modunu döndürür veya ayarlar.<br/>            Okunur/yazılır [`TextAutofitType`](/slides/python-net/tr/aspose.slides/textautofittype). |
| [`column_count`](/slides/python-net/tr/aspose.slides/itextframeformat/column_count/) | Metin alanındaki sütun sayısını döndürür veya ayarlar.<br/>            Bu değer pozitif bir sayı olmalıdır. Aksi takdirde değer sıfıra ayarlanır. <br/>            Değer 0 tanımsız değeri gösterir.<br/>            Okunur/yazılır **int**. |
| [`column_spacing`](/slides/python-net/tr/aspose.slides/itextframeformat/column_spacing/) | Metin alanındaki metin sütunları arasındaki boşluğu (nokta cinsinden) döndürür veya ayarlar. Bu sadece <br/>            birden fazla sütun mevcut olduğunda uygulanmalıdır.<br/>            Bu değer pozitif bir sayı olmalıdır. Aksi takdirde değer sıfıra ayarlanır.<br/>            Okunur/yazılır **float**. |
| [`three_d_format`](/slides/python-net/tr/aspose.slides/itextframeformat/three_d_format/) | Metin için 3d etki özelliklerini temsil eden ThreeDFormat nesnesini döndürür.<br/>            Salt okunur [`IThreeDFormat`](/slides/python-net/tr/aspose.slides/ithreedformat). |
| [`keep_text_flat`](/slides/python-net/tr/aspose.slides/itextframeformat/keep_text_flat/) | Metni tamamen 3D sahneden dışarıda tutmayı döndürür veya ayarlar.<br/>            Okunur/yazılır **bool**. |
| [`rotation_angle`](/slides/python-net/tr/aspose.slides/itextframeformat/rotation_angle/) | Sınırlayıcı kutunun içinde metne uygulanan özel dönüşümü belirtir. Eğer belirtilmemişse<br/>            eşlik eden şeklin dönüşümü kullanılır. Belirtilmişse, bu<br/>            şekilden bağımsız olarak uygulanır. Yani şekil,<br/>            metnin kendisine ek olarak dönüşüm alabilir.<br/>            Bu özellik ve önceden tanımlı<br/>            TextVerticalType özelliğindeki dikey türden özetlenen görsel metin dönüşüm değeri elde edilir.<br/>            Okunur/yazılır **float**. |
| [`transform`](/slides/python-net/tr/aspose.slides/itextframeformat/transform/) | Metin sarma şeklini alır veya ayarlar.<br/>            Okunur/yazılır [`TextShapeType`](/slides/python-net/tr/aspose.slides/textshapetype). |

## Metodlar

| Metod | Açıklama |
| :- | :- |
| [`get_effective(self)`](/slides/python-net/tr/aspose.slides/itextframeformat/get_effective/#) | Miras uygulanmış etkili metin çerçevesi biçimlendirme verilerini alır. |

### Ayrıca Bakınız
* modül [`aspose.slides`](/slides/python-net/tr/aspose.slides)
* kütüphane [`Aspose.Slides`](/slides/python-net)