---
title: IBulletFormat class
second_title: Aspose.Slides for Python via .NET API Referansı
description: 
type: docs
url: /tr/aspose.slides/ibulletformat/
---
## IBulletFormat sınıfı

Paragraf madde işareti biçimlendirme özelliklerini temsil eder.

IBulletFormat türü aşağıdaki üyeleri sunar:

## Özellikler

| Property | Description |
| :- | :- |
| [`type`](/slides/python-net/tr/aspose.slides/ibulletformat/type/) | Kalıtım olmadan bir paragrafta madde işareti tipini alır veya ayarlar.<br/>            Okunur/Yazılır [`BulletType`](/slides/python-net/tr/aspose.slides/bullettype). |
| [`char`](/slides/python-net/tr/aspose.slides/ibulletformat/char/) | Kalıtım olmadan bir paragrafta madde işareti karakterini alır veya ayarlar.<br/>            Okunur/Yazılır **System.Char**. |
| [`font`](/slides/python-net/tr/aspose.slides/ibulletformat/font/) | Kalıtım olmadan bir paragrafta madde işareti yazı tipini alır veya ayarlar.<br/>            Okunur/Yazılır [`IFontData`](/slides/python-net/tr/aspose.slides/ifontdata). |
| [`height`](/slides/python-net/tr/aspose.slides/ibulletformat/height/) | Kalıtım olmadan bir paragrafta madde işareti yüksekliğini alır veya ayarlar.<br/>            float.NaN değeri, madde işaretinin yüksekliğinin paragraftaki ilk bölüme kalıtıldığını belirler.<br/>            Okunur/Yazılır **float**. |
| [`color`](/slides/python-net/tr/aspose.slides/ibulletformat/color/) | Kalıtım olmadan bir paragrafta madde işaretinin renk biçimini alır.<br/>            Salt Okunur [`IColorFormat`](/slides/python-net/tr/aspose.slides/icolorformat). |
| [`picture`](/slides/python-net/tr/aspose.slides/ibulletformat/picture/) | Kalıtım olmadan bir paragrafta madde işareti olarak kullanılan resmi alır.<br/>            Salt Okunur [`ISlidesPicture`](/slides/python-net/tr/aspose.slides/islidespicture). |
| [`numbered_bullet_start_with`](/slides/python-net/tr/aspose.slides/ibulletformat/numbered_bullet_start_with/) | Kalıtım olmadan numaralı maddeler grubunda kullanılan ilk sayıyı alır veya ayarlar.<br/>            Okunur/Yazılır **int**. |
| [`numbered_bullet_style`](/slides/python-net/tr/aspose.slides/ibulletformat/numbered_bullet_style/) | Kalıtım olmadan numaralı bir madde işaretinin stilini alır veya ayarlar.<br/>            Okunur/Yazılır [`IBulletFormat.numbered_bullet_style`](/slides/python-net/tr/aspose.slides/ibulletformat/numbered_bullet_style). |
| [`is_bullet_hard_color`](/slides/python-net/tr/aspose.slides/ibulletformat/is_bullet_hard_color/) | Madde işaretinin kendi renginin olup olmadığını veya paragraftaki ilk bölüme kalıtılıp kalıtılmadığını belirler.<br/>            **NullableBool.True**  madde işareti kendi rengine sahipse ve **NullableBool.False**  madde işareti<br/>            paragraftaki ilk bölüme rengini kalıtıyorsa.<br/>            Okunur/Yazılır [`NullableBool`](/slides/python-net/tr/aspose.slides/nullablebool). |
| [`is_bullet_hard_font`](/slides/python-net/tr/aspose.slides/ibulletformat/is_bullet_hard_font/) | Madde işaretinin kendi yazı tipine sahip olup olmadığını veya paragraftaki ilk bölüme kalıtılıp kalıtılmadığını belirler.<br/>            **NullableBool.True**  madde işareti kendi yazı tipine sahipse ve **NullableBool.False**  madde işareti<br/>            paragraftaki ilk bölüme yazı tipini kalıtıyorsa.<br/>            Okunur/Yazılır [`NullableBool`](/slides/python-net/tr/aspose.slides/nullablebool). |

## Yöntemler

| Method | Description |
| :- | :- |
| [`apply_default_paragraph_indents_shifts(self)`](/slides/python-net/tr/aspose.slides/ibulletformat/apply_default_paragraph_indents_shifts/#) | Madde işaretleri etkin olduğunda etkili paragraf Girintisi (Indent) ve Sol Kenar Boşluğu (MarginLeft) için varsayılan sıfır olmayan kaymaları ayarlar (PowerPoint'te paragraf madde işaretleri/numaralandırması etkinleştirildiğinde yaptığı gibi). Madde işaretleri devre dışı bırakıldığında sadece paragraf Girintisi ve Sol Kenar Boşluğunu sıfırlar (PowerPoint'te paragraf madde işaretleri/numaralandırması devre dışı bırakıldığında yaptığı gibi). Girinti kaymaları mevcut madde işareti bağlamına — IBulletFormat.Type, .NumberedBulletStyle ve ilk bölümün FontHeight'ına — göre uygulanır. Sıfır olmayan girinti kaymaları mevcut paragrafın etkili Girintisi ve Sol Kenar Boşluğuna uygulanır (sonuç değerlerini yerel değerler yapar). |
| [`get_effective(self)`](/slides/python-net/tr/aspose.slides/ibulletformat/get_effective/#) | Kalıtım uygulanmış etkili madde işareti biçimlendirme verilerini alır. |

### Ayrıca Bakınız
* modül [`aspose.slides`](/slides/python-net/tr/aspose.slides)
* kütüphane [`Aspose.Slides`](/slides/python-net)