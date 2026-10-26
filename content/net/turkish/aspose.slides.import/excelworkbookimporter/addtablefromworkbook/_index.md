---
title: AddTableFromWorkbook
second_title: Aspose.Slides for .NET API Referansı
description: Belirtilen Excel çalışma kitabından bir tablo alır ve belirtilen koordinatlarda verilen şekil koleksiyonunun sonuna ekler.
type: docs
weight: 20
url: /tr/aspose.slides.import/excelworkbookimporter/addtablefromworkbook/
---
## AddTableFromWorkbook(IShapeCollection, float, float, IExcelDataWorkbook, string, string) {#addtablefromworkbook}

Belirtilen Excel çalışma kitabından bir tablo alır ve belirtilen koordinatlarda verilen şekil koleksiyonunun sonuna ekler.

```csharp
public static ITable AddTableFromWorkbook(IShapeCollection shapes, float x, float y, 
    IExcelDataWorkbook workbook, string worksheetName, string cellRange)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| shapes | IShapeCollection | Tablonun ekleneceği şekil koleksiyonu. |
| x | Single | Tablonun konumlandırılması için X koordinatı. |
| y | Single | Tablonun konumlandırılması için Y koordinatı. |
| workbook | IExcelDataWorkbook | Excel çalışma kitabı. |
| worksheetName | String | Tabloyu içeren çalışma sayfasının adı. |
| cellRange | String | Tabloyu tanımlayan hücre aralığı (örneğin, "A1:D10"). |

### Dönüş Değeri

Şekil koleksiyonuna eklenen tablo.

### İstisnalar

| exception | condition |
| --- | --- |
| ArgumentException | Gerekli bir parametre null veya boş olduğunda veya belirtilen çalışma sayfası ya da hücre aralığı geçersiz olduğunda fırlatılır. |
| InvalidOperationException | Girdi verileri desteklenmeyen bir biçimde olduğunda fırlatılır. |

### Örnekler

```csharp
[C#]
IExcelDataWorkbook workbook = new ExcelDataWorkbook(testFile);
using (var pres = new Presentation())
{
    ExcelWorkbookImporter.AddTableFromWorkbook(pres.Slides[0].Shapes, 10, 10, workbook, worksheetName, "A1:D10");
    pres.Save("result.pptx", SaveFormat.Pptx);
}
```

### İlgili

* arayüz [ITable](../../../aspose.slides/itable)
* arayüz [IShapeCollection](../../../aspose.slides/ishapecollection)
* arayüz [IExcelDataWorkbook](../../../aspose.slides.excel/iexceldataworkbook)
* sınıf [ExcelWorkbookImporter](../../excelworkbookimporter)
* ad alanı [Aspose.Slides.Import](../../excelworkbookimporter)
* derleme [Aspose.Slides](../../../)

---

## AddTableFromWorkbook(IShapeCollection, float, float, string, string, string) {#addtablefromworkbook_2}

Belirtilen Excel çalışma kitabı dosyasından bir tablo alır ve belirtilen koordinatlarda verilen şekil koleksiyonunun sonuna ekler.

```csharp
public static ITable AddTableFromWorkbook(IShapeCollection shapes, float x, float y, 
    string workbookPath, string worksheetName, string cellRange)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| shapes | IShapeCollection | Tablonun ekleneceği şekil koleksiyonu. |
| x | Single | Tablonun konumlandırılması için X koordinatı. |
| y | Single | Tablonun konumlandırılması için Y koordinatı. |
| workbookPath | String | Excel çalışma kitabı dosyasının yolu. |
| worksheetName | String | Tabloyu içeren çalışma sayfasının adı. |
| cellRange | String | Tabloyu tanımlayan hücre aralığı (örneğin, "A1:D10"). |

### Dönüş Değeri

Şekil koleksiyonuna eklenen tablo.

### İstisnalar

| exception | condition |
| --- | --- |
| ArgumentException | Gerekli bir parametre null veya boş olduğunda veya belirtilen çalışma sayfası ya da hücre aralığı geçersiz olduğunda fırlatılır. |
| IOException | Çalışma kitabı dosyasına erişilirken bir I/O hatası oluştuğunda fırlatılır. |
| InvalidOperationException | Girdi verileri desteklenmeyen bir biçimde olduğunda fırlatılır. |

### Örnekler

```csharp
[C#]
using (var pres = new Presentation())
{
    ExcelWorkbookImporter.AddTableFromWorkbook(pres.Slides[0].Shapes, 10, 10, workbookPath, worksheetName, "A1:D10");
    pres.Save("result.pptx", SaveFormat.Pptx);
}
```

### İlgili

* arayüz [ITable](../../../aspose.slides/itable)
* arayüz [IShapeCollection](../../../aspose.slides/ishapecollection)
* sınıf [ExcelWorkbookImporter](../../excelworkbookimporter)
* ad alanı [Aspose.Slides.Import](../../excelworkbookimporter)
* derleme [Aspose.Slides](../../../)

---

## AddTableFromWorkbook(IShapeCollection, float, float, Stream, string, string) {#addtablefromworkbook_1}

Belirtilen Excel çalışma kitabı dosyasından bir tablo alır ve belirtilen koordinatlarda verilen şekil koleksiyonunun sonuna ekler.

```csharp
public static ITable AddTableFromWorkbook(IShapeCollection shapes, float x, float y, 
    Stream workbookStream, string worksheetName, string cellRange)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| shapes | IShapeCollection | Tablonun ekleneceği şekil koleksiyonu. |
| x | Single | Tablonun konumlandırılması için X koordinatı. |
| y | Single | Tablonun konumlandırılması için Y koordinatı. |
| workbookStream | Stream | Çalışma kitabı verilerini içeren akış. |
| worksheetName | String | Tabloyu içeren çalışma sayfasının adı. |
| cellRange | String | Tabloyu tanımlayan hücre aralığı (örneğin, "A1:D10"). |

### Dönüş Değeri

Şekil koleksiyonuna eklenen tablo.

### İstisnalar

| exception | condition |
| --- | --- |
| ArgumentException | Gerekli bir parametre null veya boş olduğunda veya belirtilen çalışma sayfası ya da hücre aralığı geçersiz olduğunda fırlatılır. |
| InvalidOperationException | Girdi verileri desteklenmeyen bir biçimde olduğunda fırlatılır. |

### Örnekler

```csharp
[C#]
using (var fStream = new FileStream(workbookPath, FileMode.Open, FileAccess.Read))
using (var pres = new Presentation())
{
    ExcelWorkbookImporter.AddTableFromWorkbook(pres.Slides[0].Shapes, 10, 10, fStream, worksheetName, "A1:D10");
    pres.Save("result.pptx", SaveFormat.Pptx);
}
```

### İlgili

* arayüz [ITable](../../../aspose.slides/itable)
* arayüz [IShapeCollection](../../../aspose.slides/ishapecollection)
* sınıf [ExcelWorkbookImporter](../../excelworkbookimporter)
* ad alanı [Aspose.Slides.Import](../../excelworkbookimporter)
* derleme [Aspose.Slides](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->