---
title: IPoint class
second_title: Aspose.Slides for Python via .NET API Referansı
description: 
type: docs
url: /tr/aspose.slides.animation/ipoint/
---
## IPoint sınıfı

Animasyon noktasını temsil eder.

IPoint türü aşağıdaki üyeleri sunar:

## Özellikler

| Özellik | Açıklama |
| :- | :- |
| [`time`](/slides/python-net/tr/aspose.slides.animation/ipoint/time/) | Zaman değerini temsil eder.<br/>            Okunur/Yazılır **float**. |
| [`value`](/slides/python-net/tr/aspose.slides.animation/ipoint/value/) | Nokta değerini temsil eder.<br/>            Sadece: bool, ColorFormat, float, int, string.<br/>            Okunur/Yazılır **any**. |
| [`formula`](/slides/python-net/tr/aspose.slides.animation/ipoint/formula/) | Değerler, from, to, by öznitelikleri içindeki formüller aşağıdakilerden oluşabilir:<br/>            Standart aritmetik operatörler: ‘+’, ‘-‘, ‘*’, ‘/’, ‘^’, ‘%’ (mod)<br/>            Sabitler: ‘pi’ ‘e’<br/>            Koşullu operatörler: ‘abs’, ‘min’, ‘max’, ‘?’ (if)<br/>            Karşılaştırma operatörleri: '==', '>=', '', '!=', '!'<br/>            Trigonometrik operatörler: ‘sin()’, ‘cos()’, ‘tan()’, ‘asin()’, ‘acos()’, ‘atan()’<br/>            Doğal logaritma ‘ln()’<br/>            Özellik referansları (host destekli özellikler)<br/>            <br/>            örnek: "#ppt_x+(cos(-2*pi*(1-$))*-#ppt_x-sin(-2*pi*(1-$))*(1-#ppt_y))*(1-$)"<br/>            Okunur/Yazılır **str**. |

### Ayrıca Bakınız
* modül [`aspose.slides.animation`](/slides/python-net/tr/aspose.slides.animation)
* kütüphane [`Aspose.Slides`](/slides/python-net)