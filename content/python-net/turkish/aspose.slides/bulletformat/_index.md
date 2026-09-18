---
title: BulletFormat class
second_title: Aspose.Slides for Python via .NET API Referansı
description: 
type: docs
url: /tr/aspose.slides/bulletformat/
---
## BulletFormat sınıfı

Paragraf madde işareti biçimlendirme özelliklerini temsil eder.

**Inheritance:**[`BulletFormat`](/slides/python-net/tr/aspose.slides/bulletformat) → [`PVIObject`](/slides/python-net/tr/aspose.slides/pviobject)

BulletFormat türü aşağıdaki üyeleri sunar:

## Özellikler

| Property | Description |
| :- | :- |
| [`type`](/slides/python-net/tr/aspose.slides/bulletformat/type/) | Bir paragrafta kalıtım olmadan madde işareti tipini alır veya ayarlar.<br/>            **Okuma/Yazma** [`BulletType`](/slides/python-net/tr/aspose.slides/bullettype). |
| [`char`](/slides/python-net/tr/aspose.slides/bulletformat/char/) | Bir paragrafta kalıtım olmadan madde işareti karakterini alır veya ayarlar.<br/>            **Okuma/Yazma** **System.Char**. |
| [`font`](/slides/python-net/tr/aspose.slides/bulletformat/font/) | Bir paragrafta kalıtım olmadan madde işareti yazı tipini alır veya ayarlar.<br/>            **Okuma/Yazma** [`IFontData`](/slides/python-net/tr/aspose.slides/ifontdata). |
| [`height`](/slides/python-net/tr/aspose.slides/bulletformat/height/) | Bir paragrafta kalıtım olmadan madde işareti yüksekliğini alır veya ayarlar.<br/>            **Değer** float.NaN, madde işaretinin yüksekliğini paragraftaki ilk bölümüden kalıtım alacağını belirler.<br/>            **Okuma/Yazma** **float**. |
| [`color`](/slides/python-net/tr/aspose.slides/bulletformat/color/) | Bir paragrafta kalıtım olmadan bir madde işaretinin renk biçimini alır.<br/>            **Sadece okuma** [`IColorFormat`](/slides/python-net/tr/aspose.slides/icolorformat). |
| [`numbered_bullet_start_with`](/slides/python-net/tr/aspose.slides/bulletformat/numbered_bullet_start_with/) | Kalıtım olmadan numaralı madde işareti grubunda kullanılan ilk sayıyı alır veya ayarlar.<br/>            **Okuma/Yazma** **int**. |
| [`numbered_bullet_style`](/slides/python-net/tr/aspose.slides/bulletformat/numbered_bullet_style/) | Kalıtım olmadan numaralı bir madde işaretinin stilini alır veya ayarlar.<br/>            **Okuma/Yazma** [`NumberedBulletStyle`](/slides/python-net/tr/aspose.slides/numberedbulletstyle). |
| [`is_bullet_hard_color`](/slides/python-net/tr/aspose.slides/bulletformat/is_bullet_hard_color/) | Madde işaretinin kendi renginin olup olmadığını ya da paragraftaki ilk bölümüden kalıtıp kalıtmadığını belirler.<br/>            **NullableBool.True**  eğer madde işaretinin kendi rengi varsa ve **NullableBool.False**  eğer madde işareti<br/>            paragraftaki ilk bölümüden rengi kalıtıyorsa.<br/>            **Okuma/Yazma** [`NullableBool`](/slides/python-net/tr/aspose.slides/nullablebool). |
| [`is_bullet_hard_font`](/slides/python-net/tr/aspose.slides/bulletformat/is_bullet_hard_font/) | Madde işaretinin kendi yazı tipine sahip olup olmadığını ya da paragraftaki ilk bölümüden kalıtıp kalıtmadığını belirler.<br/>            **NullableBool.True**  eğer madde işaretinin kendi yazı tipi varsa ve **NullableBool.False**  eğer madde işareti<br/>            paragraftaki ilk bölümüden yazı tipini kalıtıyorsa.<br/>            **Okuma/Yazma** [`NullableBool`](/slides/python-net/tr/aspose.slides/nullablebool). |
| [`picture`](/slides/python-net/tr/aspose.slides/bulletformat/picture/) | Kalıtım olmadan bir paragrafta madde işareti olarak kullanılan resmi alır.<br/>            **Sadece okuma** [`ISlidesPicture`](/slides/python-net/tr/aspose.slides/islidespicture). |
| [`slide`](/slides/python-net/tr/aspose.slides/bulletformat/slide/) |  |
| [`presentation`](/slides/python-net/tr/aspose.slides/bulletformat/presentation/) |  |

## Yöntemler

| Method | Description |
| :- | :- |
| [`apply_default_paragraph_indents_shifts(self)`](/slides/python-net/tr/aspose.slides/bulletformat/apply_default_paragraph_indents_shifts/#) | Varsayılan sıfır olmayan kaymaları, madde işaretleri etkin olduğunda (PowerPoint'te paragraf madde işaretleri/numaralandırması etkinleştirildiğinde olduğu gibi) etkili paragraf **Indent** ve **MarginLeft** için ayarlar. Madde işaretleri devre dışı bırakıldığında sadece paragraf **Indent** ve **MarginLeft** sıfırlanır (PowerPoint'te paragraf madde işaretleri/numaralandırması devre dışı bırakıldığında olduğu gibi). Girinti kaymaları mevcut madde işareti bağlamına göre uygulanır – **IBulletFormat.Type**, **.NumberedBulletStyle** ve ilk bölümün **FontHeight**'i. Sıfır olmayan girinti kaymaları mevcut paragrafın etkili **Indent** ve **MarginLeft**'ına uygulanır (sonuç değerlerini yerel değerler hâline getirir). |
| [`get_effective(self)`](/slides/python-net/tr/aspose.slides/bulletformat/get_effective/#) | Kalıtım uygulanmış etkili madde işareti biçimlendirme verilerini alır. |


### İlgili Bakınız
* sınıf [`BulletFormat`](/slides/python-net/tr/aspose.slides/bulletformat)
* sınıf [`PVIObject`](/slides/python-net/tr/aspose.slides/pviobject)
* modül [`aspose.slides`](/slides/python-net/tr/aspose.slides)
* kütüphane [`Aspose.Slides`](/slides/python-net)