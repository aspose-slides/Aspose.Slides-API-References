---
title: AddChartFromWorkbook
second_title: Aspose.Sildes for .NET API リファレンス
description: 指定された Excel ワークブックからチャートを取得し、指定された座標で指定されたシェイプ コレクションの末尾に追加します。
type: docs
weight: 10
url: /ja/aspose.slides.import/excelworkbookimporter/addchartfromworkbook/
---
## AddChartFromWorkbook(IShapeCollection, float, float, IExcelDataWorkbook, string, int, bool) {#addchartfromworkbook}

指定された Excel ワークブックからチャートを取得し、指定された座標で指定されたシェイプ コレクションの末尾に追加します。

```csharp
public static IChart AddChartFromWorkbook(IShapeCollection shapes, float x, float y, 
    IExcelDataWorkbook workbook, string worksheetName, int chartIndex, bool embedAllWorkbook)
```

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| shapes | IShapeCollection | チャートを追加するシェイプ コレクション。 |
| x | Single | チャートの配置に使用する X 座標。 |
| y | Single | チャートの配置に使用する Y 座標。 |
| workbook | IExcelDataWorkbook | Excel ワークブック。 |
| worksheetName | String | チャートが含まれるワークシートの名前。 |
| chartIndex | Int32 | 挿入するチャート シェイプのゼロベース インデックス。このインデックスは [`GetChartsFromWorksheet`](../../../aspose.slides.excel/iexceldataworkbook/getchartsfromworksheet) メソッドを使用して取得できます。 |
| embedAllWorkbook | Boolean | `true` の場合、ワークブック全体がチャートに埋め込まれます。`false` の場合、チャート データのみが埋め込まれます。 |

### 戻り値

シェイプ コレクションに追加されたチャート。

### 例外

| 例外 | 条件 |
| --- | --- |
| ArgumentException | 必要なパラメータが null または空である、またはワークブック内にチャートが見つからない場合にスローされます。 |

### 例

例:

```csharp
[C#]
IExcelDataWorkbook wb = new ExcelDataWorkbook(testFile);
using (var pres = new Presentation())
{
    ExcelWorkbookImporter.AddChartFromWorkbook(pres.Slides[0].Shapes, 10, 10, wb, worksheetName, chartName, false);
    pres.Save("result.pptx", SaveFormat.Pptx);
}
```

### 関連項目

* インターフェイス [IChart](../../../aspose.slides.charts/ichart)
* インターフェイス [IShapeCollection](../../../aspose.slides/ishapecollection)
* インターフェイス [IExcelDataWorkbook](../../../aspose.slides.excel/iexceldataworkbook)
* クラス [ExcelWorkbookImporter](../../excelworkbookimporter)
* 名前空間 [Aspose.Slides.Import](../../excelworkbookimporter)
* アセンブリ [Aspose.Slides](../../../)

---

## AddChartFromWorkbook(IShapeCollection, float, float, IExcelDataWorkbook, string, string, bool) {#addchartfromworkbook_1}

指定された Excel ワークブックからチャートを取得し、指定された座標で指定されたシェイプ コレクションの末尾に追加します。

```csharp
public static IChart AddChartFromWorkbook(IShapeCollection shapes, float x, float y, 
    IExcelDataWorkbook workbook, string worksheetName, string chartName, bool embedAllWorkbook)
```

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| shapes | IShapeCollection | チャートを追加するシェイプ コレクション。 |
| x | Single | チャートの配置に使用する X 座標。 |
| y | Single | チャートの配置に使用する Y 座標。 |
| workbook | IExcelDataWorkbook | Excel ワークブック。 |
| worksheetName | String | チャートが含まれるワークシートの名前。 |
| chartName | String | 追加するチャートの名前。 |
| embedAllWorkbook | Boolean | `true` の場合、ワークブック全体がチャートに埋め込まれます。`false` の場合、チャート データのみが埋め込まれます。 |

### 戻り値

シェイプ コレクションに追加されたチャート。

### 例外

| 例外 | 条件 |
| --- | --- |
| ArgumentException | 必要なパラメータが null または空である、またはワークブック内にチャートが見つからない場合にスローされます。 |

### 例

例:

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

### 関連項目

* インターフェイス [IChart](../../../aspose.slides.charts/ichart)
* インターフェイス [IShapeCollection](../../../aspose.slides/ishapecollection)
* インターフェイス [IExcelDataWorkbook](../../../aspose.slides.excel/iexceldataworkbook)
* クラス [ExcelWorkbookImporter](../../excelworkbookimporter)
* 名前空間 [Aspose.Slides.Import](../../excelworkbookimporter)
* アセンブリ [Aspose.Slides](../../../)

---

## AddChartFromWorkbook(IShapeCollection, float, float, Stream, string, string, bool) {#addchartfromworkbook_2}

指定された Excel ワークブックからチャートを取得し、指定された座標で指定されたシェイプ コレクションの末尾に追加します。

```csharp
public static IChart AddChartFromWorkbook(IShapeCollection shapes, float x, float y, 
    Stream workbookStream, string worksheetName, string chartName, bool embedAllWorkbook)
```

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| shapes | IShapeCollection | チャートを追加するシェイプ コレクション。 |
| x | Single | チャートの配置に使用する X 座標。 |
| y | Single | チャートの配置に使用する Y 座標。 |
| workbookStream | Stream | ワークブック データを含むストリーム。 |
| worksheetName | String | チャートが含まれるワークシートの名前。 |
| chartName | String | 追加するチャートの名前。 |
| embedAllWorkbook | Boolean | `true` の場合、ワークブック全体がチャートに埋め込まれます。`false` の場合、チャート データのみが埋め込まれます。 |

### 戻り値

シェイプ コレクションに追加されたチャート。

### 例外

| 例外 | 条件 |
| --- | --- |
| ArgumentException | 必要なパラメータが null または空である、またはワークブック内にチャートが見つからない場合にスローされます。 |
| InvalidOperationException | 入力データがサポートされていない形式の場合にスローされます。 |

### 例

例:

```csharp
[C#]
using (var fStream = new FileStream(workbookPath, FileMode.Open, FileAccess.Read))
using (var pres = new Presentation())
{
    ExcelWorkbookImporter.AddChartFromWorkbook(pres.LayoutSlides[0].Shapes, 10, 10, fStream, worksheetName, chartName, true);
    pres.Save("result.pptx", SaveFormat.Pptx);
}
```

### 関連項目

* インターフェイス [IChart](../../../aspose.slides.charts/ichart)
* インターフェイス [IShapeCollection](../../../aspose.slides/ishapecollection)
* クラス [ExcelWorkbookImporter](../../excelworkbookimporter)
* 名前空間 [Aspose.Slides.Import](../../excelworkbookimporter)
* アセンブリ [Aspose.Slides](../../../)

---

## AddChartFromWorkbook(IShapeCollection, float, float, string, string, string, bool) {#addchartfromworkbook_3}

指定された Excel ワークブックからチャートを取得し、指定された座標で指定されたシェイプ コレクションの末尾に追加します。

```csharp
public static IChart AddChartFromWorkbook(IShapeCollection shapes, float x, float y, 
    string workbookPath, string worksheetName, string chartName, bool embedWorkbook)
```

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| shapes | IShapeCollection | チャートを追加するシェイプ コレクション。 |
| x | Single | チャートの配置に使用する X 座標。 |
| y | Single | チャートの配置に使用する Y 座標。 |
| workbookPath | String | チャートが含まれるワークブックへのファイル パス。 |
| worksheetName | String | チャートが含まれるワークシートの名前。 |
| chartName | String | 追加するチャートの名前。 |
| embedWorkbook | Boolean | `true` の場合、ワークブックがチャートに埋め込まれます。`false` の場合、チャートは外部ワークブックへのリンクになります。 |

### 戻り値

シェイプ コレクションに追加されたチャート。

### 例外

| 例外 | 条件 |
| --- | --- |
| ArgumentException | 必要なパラメータが null または空である、またはワークブック内にチャートが見つからない場合にスローされます。 |
| IOException | ファイルへのアクセス中に I/O エラーが発生した場合にスローされます。 |
| InvalidOperationException | 入力データがサポートされていない形式の場合にスローされます。 |

### 例

例:

```csharp
[C#]
using (var pres = new Presentation())
{
    ExcelWorkbookImporter.AddChartFromWorkbook(pres.Slides[0].Shapes, 10, 10, workbookPath, worksheetName, chartName, false);
    pres.Save("result.pptx", SaveFormat.Pptx);
}
```

### 関連項目

* インターフェイス [IChart](../../../aspose.slides.charts/ichart)
* インターフェイス [IShapeCollection](../../../aspose.slides/ishapecollection)
* クラス [ExcelWorkbookImporter](../../excelworkbookimporter)
* 名前空間 [Aspose.Slides.Import](../../excelworkbookimporter)
* アセンブリ [Aspose.Slides](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->