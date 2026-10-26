---
title: AddChartFromWorkbook
second_title: Aspose.Sildes için .NET API Referansı
description: Belirtilen Excel çalışma kitabından bir grafik alır ve verilen şekil koleksiyonunun sonuna belirtilen koordinatlarda ekler.
type: docs
weight: 10
url: /tr/aspose.slides.import/excelworkbookimporter/addchartfromworkbook/
---
## AddChartFromWorkbook(IShapeCollection, float, float, IExcelDataWorkbook, string, int, bool) {#addchartfromworkbook}

Belirtilen Excel çalışma kitabından bir grafik alır ve verilen şekil koleksiyonunun sonuna belirtilen koordinatlarda ekler.

```csharp
public static IChart AddChartFromWorkbook(IShapeCollection shapes, float x, float y, 
    IExcelDataWorkbook workbook, string worksheetName, int chartIndex, bool embedAllWorkbook)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| shapes | IShapeCollection | Grafiğin ekleneceği şekil koleksiyonu. |
| x | Single | Grafiği konumlandırmak için X koordinatı. |
| y | Single | Grafiği konumlandırmak için Y koordinatı. |
| workbook | IExcelDataWorkbook | Excel çalışma kitabı. |
| worksheetName | String | Grafiği içeren çalışma sayfasının adı. |
| chartIndex | Int32 | Eklenmek istenen grafik şeklinin sıfır tabanlı indeksi. Bu indeks, [`GetChartsFromWorksheet`](../../../aspose.slides.excel/iexceldataworkbook/getchartsfromworksheet) yöntemi kullanılarak elde edilebilir. |
| embedAllWorkbook | Boolean | `true` ise, tüm çalışma kitabı grafiğe gömülür; `false` ise yalnızca grafik verileri gömülür. |

### Dönüş Değeri

Şekil koleksiyonuna eklenen grafik.

### İstisnalar

| İstisna | Koşul |
| --- | --- |
| ArgumentException | Gerekli bir parametre null veya boş olduğunda ya da grafik çalışma kitabında bulunamadığında fırlatılır. |

### Örnekler

Örnek:

```csharp
[C#]
IExcelDataWorkbook wb = new ExcelDataWorkbook(testFile);
using (var pres = new Presentation())
{
    ExcelWorkbookImporter.AddChartFromWorkbook(pres.Slides[0].Shapes, 10, 10, wb, worksheetName, chartName, false);
    pres.Save("result.pptx", SaveFormat.Pptx);
}
```

### Diğer Bağlantılar

* arayüz [IChart](../../../aspose.slides.charts/ichart)
* arayüz [IShapeCollection](../../../aspose.slides/ishapecollection)
* arayüz [IExcelDataWorkbook](../../../aspose.slides.excel/iexceldataworkbook)
* sınıf [ExcelWorkbookImporter](../../excelworkbookimporter)
* ad alanı [Aspose.Slides.Import](../../excelworkbookimporter)
* derleme [Aspose.Slides](../../../)

---

## AddChartFromWorkbook(IShapeCollection, float, float, IExcelDataWorkbook, string, string, bool) {#addchartfromworkbook_1}

Belirtilen Excel çalışma kitabından bir grafik alır ve verilen şekil koleksiyonunun sonuna belirtilen koordinatlarda ekler.

```csharp
public static IChart AddChartFromWorkbook(IShapeCollection shapes, float x, float y, 
    IExcelDataWorkbook workbook, string worksheetName, string chartName, bool embedAllWorkbook)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| shapes | IShapeCollection | Grafiğin ekleneceği şekil koleksiyonu. |
| x | Single | Grafiği konumlandırmak için X koordinatı. |
| y | Single | Grafiği konumlandırmak için Y koordinatı. |
| workbook | IExcelDataWorkbook | Excel çalışma kitabı. |
| worksheetName | String | Grafiği içeren çalışma sayfasının adı. |
| chartName | String | Eklenmek istenen grafiğin adı. |
| embedAllWorkbook | Boolean | `true` ise, tüm çalışma kitabı grafiğe gömülür; `false` ise yalnızca grafik verileri gömülür. |

### Dönüş Değeri

Şekil koleksiyonuna eklenen grafik.

### İstisnalar

| İstisna | Koşul |
| --- | --- |
| ArgumentException | Gerekli bir parametre null veya boş olduğunda ya da grafik çalışma kitabında bulunamadığında fırlatılır. |

### Örnekler

Örnek:

```csharp
[C#]
IExcelDataWorkbook wb = new ExcelDataWorkbook(testFile);
using (var pres = new Presentation())
{
    string worksheetName = "worksheet name";
    var worksheetCharts = wb.GetChartsFromWorksheet(worksheetName);
    foreach (var chart in worksheetCharts)
    {
        ISlide slide = pres.Slides.AddEmptySlide(pres.LayoutSlides[0]);
        ExcelWorkbookImporter.AddChartFromWorkbook(slide.Shapes, 10, 10, wb, worksheetName, chart.Key, false);
    }
    pres.Save("result.pptx", SaveFormat.Pptx);
}
```

### Diğer Bağlantılar

* arayüz [IChart](../../../aspose.slides.charts/ichart)
* arayüz [IShapeCollection](../../../aspose.slides/ishapecollection)
* arayüz [IExcelDataWorkbook](../../../aspose.slides.excel/iexceldataworkbook)
* sınıf [ExcelWorkbookImporter](../../excelworkbookimporter)
* ad alanı [Aspose.Slides.Import](../../excelworkbookimporter)
* derleme [Aspose.Slides](../../../)

---

## AddChartFromWorkbook(IShapeCollection, float, float, Stream, string, string, bool) {#addchartfromworkbook_2}

Belirtilen Excel çalışma kitabından bir grafik alır ve verilen şekil koleksiyonunun sonuna belirtilen koordinatlarda ekler.

```csharp
public static IChart AddChartFromWorkbook(IShapeCollection shapes, float x, float y, 
    Stream workbookStream, string worksheetName, string chartName, bool embedAllWorkbook)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| shapes | IShapeCollection | Grafiğin ekleneceği şekil koleksiyonu. |
| x | Single | Grafiği konumlandırmak için X koordinatı. |
| y | Single | Grafiği konumlandırmak için Y koordinatı. |
| workbookStream | Stream | Çalışma kitabı verilerini içeren akış. |
| worksheetName | String | Grafiği içeren çalışma sayfasının adı. |
| chartName | String | Eklenmek istenen grafiğin adı. |
| embedAllWorkbook | Boolean | `true` ise, tüm çalışma kitabı grafiğe gömülür; `false` ise yalnızca grafik verileri gömülür. |

### Dönüş Değeri

Şekil koleksiyonuna eklenen grafik.

### İstisnalar

| İstisna | Koşul |
| --- | --- |
| ArgumentException | Gerekli bir parametre null veya boş olduğunda ya da grafik çalışma kitabında bulunamadığında fırlatılır. |
| InvalidOperationException | Giriş verileri desteklenmeyen bir biçimde olduğunda fırlatılır. |

### Örnekler

Örnek:

```csharp
[C#]
using (var fStream = new FileStream(workbookPath, FileMode.Open, FileAccess.Read))
using (var pres = new Presentation())
{
    ExcelWorkbookImporter.AddChartFromWorkbook(pres.LayoutSlides[0].Shapes, 10, 10, fStream, worksheetName, chartName, true);
    pres.Save("result.pptx", SaveFormat.Pptx);
}
```

### Diğer Bağlantılar

* arayüz [IChart](../../../aspose.slides.charts/ichart)
* arayüz [IShapeCollection](../../../aspose.slides/ishapecollection)
* sınıf [ExcelWorkbookImporter](../../excelworkbookimporter)
* ad alanı [Aspose.Slides.Import](../../excelworkbookimporter)
* derleme [Aspose.Slides](../../../)

---

## AddChartFromWorkbook(IShapeCollection, float, float, string, string, string, bool) {#addchartfromworkbook_3}

Belirtilen Excel çalışma kitabından bir grafik alır ve verilen şekil koleksiyonunun sonuna belirtilen koordinatlarda ekler.

```csharp
public static IChart AddChartFromWorkbook(IShapeCollection shapes, float x, float y, 
    string workbookPath, string worksheetName, string chartName, bool embedWorkbook)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| shapes | IShapeCollection | Grafiğin ekleneceği şekil koleksiyonu. |
| x | Single | Grafiği konumlandırmak için X koordinatı. |
| y | Single | Grafiği konumlandırmak için Y koordinatı. |
| workbookPath | String | Grafiği içeren çalışma kitabının dosya yolu. |
| worksheetName | String | Grafiği içeren çalışma sayfasının adı. |
| chartName | String | Eklenmek istenen grafiğin adı. |
| embedWorkbook | Boolean | `true` ise, çalışma kitabı grafiğe gömülür; `false` ise grafik dış çalışma kitabına bağlanır. |

### Dönüş Değeri

Şekil koleksiyonuna eklenen grafik.

### İstisnalar

| İstisna | Koşul |
| --- | --- |
| ArgumentException | Gerekli bir parametre null veya boş olduğunda ya da grafik çalışma kitabında bulunamadığında fırlatılır. |
| IOException | Dosyaya erişilirken bir I/O hatası oluştuğunda fırlatılır. |
| InvalidOperationException | Giriş verileri desteklenmeyen bir biçimde olduğunda fırlatılır. |

### Örnekler

Örnek:

```csharp
[C#]
using (var pres = new Presentation())
{
    ExcelWorkbookImporter.AddChartFromWorkbook(pres.Slides[0].Shapes, 10, 10, workbookPath, worksheetName, chartName, false);
    pres.Save("result.pptx", SaveFormat.Pptx);
}
```

### Diğer Bağlantılar

* arayüz [IChart](../../../aspose.slides.charts/ichart)
* arayüz [IShapeCollection](../../../aspose.slides/ishapecollection)
* sınıf [ExcelWorkbookImporter](../../excelworkbookimporter)
* ad alanı [Aspose.Slides.Import](../../excelworkbookimporter)
* derleme [Aspose.Slides](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->