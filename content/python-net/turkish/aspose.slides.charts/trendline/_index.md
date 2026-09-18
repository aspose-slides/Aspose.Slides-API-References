---
title: Trendline class
second_title: Aspose.Slides for Python via .NET API Referansı
description: 
type: docs
url: /tr/aspose.slides.charts/trendline/
---
## Trendline sınıfı

Sınıf, grafik serisinin trend çizgisini temsil eder.

Trendline türü aşağıdaki üyeleri sunar:

## Özellikler

| Özellik | Açıklama |
| :- | :- |
| [`trendline_name`](/slides/python-net/tr/aspose.slides.charts/trendline/trendline_name/) | Trend çizgisinin adını alır veya ayarlar.<br/>            Okuma/Yazma **str**. |
| [`trendline_type`](/slides/python-net/tr/aspose.slides.charts/trendline/trendline_type/) | Trend çizgisinin tipini alır veya ayarlar.<br/>            Okuma/Yazma [`TrendlineType`](/slides/python-net/tr/aspose.slides.charts/trendlinetype). |
| [`format`](/slides/python-net/tr/aspose.slides.charts/trendline/format/) | Trend çizgisinin biçimini temsil eder.<br/>            Okuma/Yazma [`IFormat`](/slides/python-net/tr/aspose.slides.charts/iformat). |
| [`backward`](/slides/python-net/tr/aspose.slides.charts/trendline/backward/) | Trend çizgisinin, trendi izlenen serinin verilerinden önce uzadığı kategori (veya dağılım grafiğindeki birim) sayısını belirtir.<br/>            Dağılım ve dağılım olmayan grafiklerde, değer herhangi bir negatif olmayan sayı olmalıdır.<br/>            Okuma/Yazma **float**. |
| [`forward`](/slides/python-net/tr/aspose.slides.charts/trendline/forward/) | Trend çizgisinin, trendi izlenen serinin verilerinden sonra uzadığı kategori (veya dağılım grafiğindeki birim) sayısını belirtir.<br/>            Dağılım ve dağılım olmayan grafiklerde, değer herhangi bir negatif olmayan sayı olmalıdır.<br/>            Okuma/Yazma **float**. |
| [`intercept`](/slides/python-net/tr/aspose.slides.charts/trendline/intercept/) | Trend çizgisinin y eksenini kestiği değeri belirtir. Bu özellik yalnızca trend çizgisi türü exp, linear veya poly olduğunda desteklenir.<br/>            Okuma/Yazma **float**. |
| [`display_equation`](/slides/python-net/tr/aspose.slides.charts/trendline/display_equation/) | Trend çizgisinin denkleminin grafikte (Rsquaredvalue ile aynı etikette) görüntülenmesini belirtir.<br/>            Okuma/Yazma **bool**. |
| [`order`](/slides/python-net/tr/aspose.slides.charts/trendline/order/) | Polinom trend çizgisinin derecesini belirtir. Diğer trend çizgi türleri için yok sayılır. Değer 2 ile 6 arasında olmalıdır.<br/>            Okuma/Yazma **int**. |
| [`period`](/slides/python-net/tr/aspose.slides.charts/trendline/period/) | Hareketli ortalama trend çizgisi için trend çizgisinin periyodunu belirtir. Diğer trend çizgi varyantları için yok sayılır. Değer 2 ile 255 arasında olmalıdır.<br/>            Okuma/Yazma **int**. |
| [`display_r_squared_value`](/slides/python-net/tr/aspose.slides.charts/trendline/display_r_squared_value/) | Trend çizgisinin R-kare değerinin grafikte (denklemin aynı etiketi içinde) görüntülenmesini belirtir.<br/>            Okuma/Yazma **bool**. |
| [`related_legend_entry`](/slides/python-net/tr/aspose.slides.charts/trendline/related_legend_entry/) | Bu trend çizgisiyle ilgili gösterge girişini temsil eder<br/>            Sadece okunur [`ILegendEntryProperties`](/slides/python-net/tr/aspose.slides.charts/ilegendentryproperties). |
| [`text_frame_for_overriding`](/slides/python-net/tr/aspose.slides.charts/trendline/text_frame_for_overriding/) | Zengin biçimlendirilmiş metin içerebilir. Bu özellik None değilse, bu <br/>            biçimlendirilmiş metin değeri veri etiketi için otomatik oluşturulan metni geçersiz kılar.<br/>            Otomatik oluşturulan veri etiketi metni, ShowSeriesName, <br/>            ShowValue, ... özellikleri tarafından yönetilen ve TextFormatManager.TextFormat özelliğiyle biçimlendirilmiş metni ifade eder.<br/>            Sadece okunur [`ITextFrame`](/slides/python-net/tr/aspose.slides/itextframe). |
| [`text_format`](/slides/python-net/tr/aspose.slides.charts/trendline/text_format/) | Metin biçimini döndürür.<br/>            Sadece okunur [`IChartTextFormat`](/slides/python-net/tr/aspose.slides.charts/icharttextformat). |
| [`chart`](/slides/python-net/tr/aspose.slides.charts/trendline/chart/) | Üst grafiği döndürür.<br/>            Sadece okunur [`IChart`](/slides/python-net/tr/aspose.slides.charts/ichart). |
| [`slide`](/slides/python-net/tr/aspose.slides.charts/trendline/slide/) |  |
| [`presentation`](/slides/python-net/tr/aspose.slides.charts/trendline/presentation/) |  |

## Yöntemler

| Yöntem | Açıklama |
| :- | :- |
| [`add_text_frame_for_overriding(self, text)`](/slides/python-net/tr/aspose.slides.charts/trendline/add_text_frame_for_overriding/#str) | TextFrameForOverriding'i parametre "text" içindeki metinle başlatır.<br/>            TextFrameForOverriding zaten başlatılmışsa sadece metnini değiştirir. |

### Ayrıca Bakınız
* modül [`aspose.slides.charts`](/slides/python-net/tr/aspose.slides.charts)
* kütüphane [`Aspose.Slides`](/slides/python-net)