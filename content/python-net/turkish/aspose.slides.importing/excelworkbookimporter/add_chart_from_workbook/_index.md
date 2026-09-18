---
title: add_chart_from_workbook method
second_title: Aspose.Slides for Python via .NET API Referansı
description: 
type: docs
url: /tr/aspose.slides.importing/excelworkbookimporter/add_chart_from_workbook/
weight: 10
---
## add_chart_from_workbook(shapes, x, y, workbook, worksheet_name, chart_index, embed_all_workbook) {#ishapecollection-float-float-asposeslidesexceliexceldataworkbook-str-int-bool}
Belirtilen Excel çalışma kitabından bir grafik alır ve belirtilen koordinatlarda verilen şekil koleksiyonunun sonuna ekler.

### Döndürür

Şekil koleksiyonuna eklenen grafik.



```python
@staticmethod
def add_chart_from_workbook(shapes, x, y, workbook, worksheet_name, chart_index, embed_all_workbook):
    ...
```


| Parametre | Tür | Açıklama |
| :- | :- | :- |
| shapes | [`IShapeCollection`](/slides/python-net/tr/aspose.slides/ishapecollection) | Grafiğin ekleneceği şekil koleksiyonu. |
| x | **float** | Grafiği konumlandırmak için X koordinatı. |
| y | **float** | Grafiği konumlandırmak için Y koordinatı. |
| workbook | [`IExcelDataWorkbook`](/slides/python-net/tr/aspose.slides.excel/iexceldataworkbook) | Excel çalışma kitabı. |
| worksheet_name | **str** | Grafiği içeren çalışma sayfasının adı. |
| chart_index | **int** | Eklenecek grafik şeklinin sıfır tabanlı indeksi. <br/><br/>            Bu indeks, **Aspose.Slides.Excel.IExcelDataWorkbook.GetChartsFromWorksheet(Syste** yöntemi kullanılarak elde edilebilir. |
| embed_all_workbook | **bool** | `true` ise, tüm çalışma kitabı grafiğe gömülür; <br/><br/>            `false` ise, yalnızca grafik verileri gömülür. |

### İstisnalar

| İstisna | Açıklama |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** | Gerekli bir parametre None, boş olduğunda veya grafik çalışma kitabında bulunamadığında fırlatılır. |


## add_chart_from_workbook(shapes, x, y, workbook, worksheet_name, chart_name, embed_all_workbook) {#ishapecollection-float-float-asposeslidesexceliexceldataworkbook-str-str-bool}
Belirtilen Excel çalışma kitabından bir grafik alır ve belirtilen koordinatlarda verilen şekil koleksiyonunun sonuna ekler.

### Döndürür

Şekil koleksiyonuna eklenen grafik.



```python
@staticmethod
def add_chart_from_workbook(shapes, x, y, workbook, worksheet_name, chart_name, embed_all_workbook):
    ...
```


| Parametre | Tür | Açıklama |
| :- | :- | :- |
| shapes | [`IShapeCollection`](/slides/python-net/tr/aspose.slides/ishapecollection) | Grafiğin ekleneceği şekil koleksiyonu. |
| x | **float** | Grafiği konumlandırmak için X koordinatı. |
| y | **float** | Grafiği konumlandırmak için Y koordinatı. |
| workbook | [`IExcelDataWorkbook`](/slides/python-net/tr/aspose.slides.excel/iexceldataworkbook) | Excel çalışma kitabı. |
| worksheet_name | **str** | Grafiği içeren çalışma sayfasının adı. |
| chart_name | **str** | Eklenecek grafiğin adı. |
| embed_all_workbook | **bool** | `true` ise, tüm çalışma kitabı grafiğe gömülür; <br/><br/>            `false` ise, yalnızca grafik verileri gömülür. |

### İstisnalar

| İstisna | Açıklama |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** | Gerekli bir parametre None, boş olduğunda veya grafik çalışma kitabında bulunamadığında fırlatılır. |


## add_chart_from_workbook(shapes, x, y, workbook_stream, worksheet_name, chart_name, embed_all_workbook) {#ishapecollection-float-float-iorawiobase-str-str-bool}
Belirtilen Excel çalışma kitabından bir grafik alır ve belirtilen koordinatlarda verilen şekil koleksiyonunun sonuna ekler.

### Döndürür

Şekil koleksiyonuna eklenen grafik.



```python
@staticmethod
def add_chart_from_workbook(shapes, x, y, workbook_stream, worksheet_name, chart_name, embed_all_workbook):
    ...
```


| Parametre | Tür | Açıklama |
| :- | :- | :- |
| shapes | [`IShapeCollection`](/slides/python-net/tr/aspose.slides/ishapecollection) | Grafiğin ekleneceği şekil koleksiyonu. |
| x | **float** | Grafiği konumlandırmak için X koordinatı. |
| y | **float** | Grafiği konumlandırmak için Y koordinatı. |
| workbook_stream | **io.RawIOBase** | Çalışma kitabı verilerini içeren akış. |
| worksheet_name | **str** | Grafiği içeren çalışma sayfasının adı. |
| chart_name | **str** | Eklenecek grafiğin adı. |
| embed_all_workbook | **bool** | `true` ise, tüm çalışma kitabı grafiğe gömülür; <br/><br/>            `false` ise, yalnızca grafik verileri gömülür. |

### İstisnalar

| İstisna | Açıklama |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** | Gerekli bir parametre None, boş olduğunda veya grafik çalışma kitabında bulunamadığında fırlatılır. |
| **RuntimeError(Proxy error(InvalidOperationException))** | Giriş verileri desteklenmeyen bir formatta olduğunda fırlatılır. |


## add_chart_from_workbook(shapes, x, y, workbook_path, worksheet_name, chart_name, embed_workbook) {#ishapecollection-float-float-str-str-str-bool}
Belirtilen Excel çalışma kitabından bir grafik alır ve belirtilen koordinatlarda verilen şekil koleksiyonunun sonuna ekler.

### Döndürür

Şekil koleksiyonuna eklenen grafik.



```python
@staticmethod
def add_chart_from_workbook(shapes, x, y, workbook_path, worksheet_name, chart_name, embed_workbook):
    ...
```


| Parametre | Tür | Açıklama |
| :- | :- | :- |
| shapes | [`IShapeCollection`](/slides/python-net/tr/aspose.slides/ishapecollection) | Grafiğin ekleneceği şekil koleksiyonu. |
| x | **float** | Grafiği konumlandırmak için X koordinatı. |
| y | **float** | Grafiği konumlandırmak için Y koordinatı. |
| workbook_path | **str** | Grafiği içeren çalışma kitabının dosya yolu. |
| worksheet_name | **str** | Grafiği içeren çalışma sayfasının adı. |
| chart_name | **str** | Eklenecek grafiğin adı. |
| embed_workbook | **bool** | `true` ise, çalışma kitabı grafiğe gömülür; <br/><br/>            `false` ise, grafik harici çalışma kitabına bağlanır. |

### İstisnalar

| İstisna | Açıklama |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** | Gerekli bir parametre None, boş olduğunda veya grafik çalışma kitabında bulunamadığında fırlatılır. |
| **RuntimeError(Proxy error(IOException))** | Dosyaya erişilirken bir I/O hatası oluştuğunda fırlatılır. |
| **RuntimeError(Proxy error(InvalidOperationException))** | Giriş verileri desteklenmeyen bir formatta olduğunda fırlatılır. |



### Ayrıca Bakınız
* sınıf [`ExcelWorkbookImporter`](/slides/python-net/tr/aspose.slides.importing/excelworkbookimporter)
* sınıf [`IExcelDataWorkbook`](/slides/python-net/tr/aspose.slides.excel/iexceldataworkbook)
* sınıf [`IShapeCollection`](/slides/python-net/tr/aspose.slides/ishapecollection)
* modül [`aspose.slides.importing`](/slides/python-net/tr/aspose.slides.importing)
* kütüphane [`Aspose.Slides`](/slides/python-net)