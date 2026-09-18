---
title: Point class
second_title: Aspose.Slides için Python üzerinden .NET API Referansı
description: 
type: docs
url: /tr/aspose.slides.animation/point/
---
## Point sınıfı

Animasyon noktasını temsil eder.

Point türü aşağıdaki üyeleri sunar:

## Yapıcılar

| Yapıcı | Açıklama |
| :- | :- |
| [`__init__(self)`](/slides/python-net/tr/aspose.slides.animation/point/__init__/#) | Varsayılan yapıcı. |
| [`__init__(self, time, value, formula)`](/slides/python-net/tr/aspose.slides.animation/point/__init__/#float-any-str) | Zaman, değer ve formülle animasyon noktası oluşturur. |

## Özellikler

| Özellik | Açıklama |
| :- | :- |
| [`time`](/slides/python-net/tr/aspose.slides.animation/point/time/) | Zaman değerini temsil eder.<br/>            Okunur/yazılır **float**. |
| [`value`](/slides/python-net/tr/aspose.slides.animation/point/value/) | Nokta değerini temsil eder.<br/>            Sadece: bool, ColorFormat, float, int, string.<br/>            Okunur/yazılır **any**. |
| [`formula`](/slides/python-net/tr/aspose.slides.animation/point/formula/) | Değerler, from, to, by özniteliklerindeki formüller şunlardan oluşabilir:<br/>            Standart aritmetik operatörler: ‘+’, ‘-‘, ‘*’, ‘/’, ‘^’, ‘%’ (mod)<br/>            Sabitler: ‘pi’ ‘e’<br/>            Koşul operatörleri: ‘abs’, ‘min’, ‘max’, ‘?’ (if)<br/>            Karşılaştırma operatörleri: '==', '>=', '', '!=', '!'<br/>            Trigonometrik operatörler: ‘sin()’, ‘cos()’, ‘tan()’, ‘asin()’, ‘acos()’, ‘atan()’<br/>            Doğal logaritma ‘ln()’<br/>            Özellik referansları (host destekli özellikler)<br/>            <br/>            örnek: "#ppt_x+(cos(-2*pi*(1-$))*-#ppt_x-sin(-2*pi*(1-$))*(1-#ppt_y))*(1-$)"<br/>            Okunur/yazılır **str**. |

### İlgili
* modül [`aspose.slides.animation`](/slides/python-net/tr/aspose.slides.animation)
* kütüphane [`Aspose.Slides`](/slides/python-net)