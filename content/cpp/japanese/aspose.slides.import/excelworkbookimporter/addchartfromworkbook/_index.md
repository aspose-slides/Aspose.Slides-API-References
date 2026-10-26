---
title: AddChartFromWorkbook()
second_title: Aspose.Slides for C++ API リファレンス
description: 指定された Excel ワークブックからチャートを取得し、指定された座標で指定されたシェイプコレクションの末尾に追加します。
type: docs
weight: 1
url: /ja/aspose.slides.import/excelworkbookimporter/addchartfromworkbook/
---
## ExcelWorkbookImporter::AddChartFromWorkbook(System::SharedPtr\<Aspose::Slides::IShapeCollection\>, float, float, System::SharedPtr\<Aspose::Slides::Excel::IExcelDataWorkbook\>, System::String, int32_t, bool) method


指定された[Excel](../../../aspose.slides.excel/)ワークブックからチャートを取得し、指定された座標にある指定されたシェイプコレクションの末尾に追加します。

```cpp
static System::SharedPtr<Aspose::Slides::Charts::IChart> Aspose::Slides::Import::ExcelWorkbookImporter::AddChartFromWorkbook(System::SharedPtr<Aspose::Slides::IShapeCollection> shapes, float x, float y, System::SharedPtr<Aspose::Slides::Excel::IExcelDataWorkbook> workbook, System::String worksheetName, int32_t chartIndex, bool embedAllWorkbook)
```


### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| shapes | [System::SharedPtr](../../../system/sharedptr/)\<[Aspose::Slides::IShapeCollection](../../../aspose.slides/ishapecollection/)\> | チャートが追加されるシェイプコレクション。 |
| x | **float** | チャートの位置決めのためのX座標。 |
| y | **float** | チャートの位置決めのためのY座標。 |
| workbook | [System::SharedPtr](../../../system/sharedptr/)\<[Aspose::Slides::Excel::IExcelDataWorkbook](../../../aspose.slides.excel/iexceldataworkbook/)\> | [Excel](../../../aspose.slides.excel/)ワークブック。 |
| worksheetName | [System::String](../../../system/string/) | チャートを含むワークシートの名前。 |
| chartIndex | **int32_t** | 挿入するチャートシェイプの0から始まるインデックス。このインデックスは[IExcelDataWorkbook::GetChartsFromWorksheet(string)](../)メソッドで取得できます。 |
| embedAllWorkbook | **bool** | **true** の場合、ワークブック全体がチャートに埋め込まれます。**false** の場合、チャートデータのみが埋め込まれます。 |

### 戻り値

シェイプコレクションに追加されたチャート。

## 備考



例: 
```cpp
System::SharedPtr<IExcelDataWorkbook> wb = System::MakeObject<ExcelDataWorkbook>(testFile);
auto pres = System::MakeObject<Presentation>();
ExcelWorkbookImporter::AddChartFromWorkbook(pres->get_Slide(0)->get_Shapes(), 10.0f, 10.0f, wb, worksheetName, chartName, false);
pres->Save(u"result.pptx", SaveFormat::Pptx);
```

## ExcelWorkbookImporter::AddChartFromWorkbook(System::SharedPtr\<Aspose::Slides::IShapeCollection\>, float, float, System::SharedPtr\<Aspose::Slides::Excel::IExcelDataWorkbook\>, System::String, System::String, bool) method


指定された[Excel](../../../aspose.slides.excel/)ワークブックからチャートを取得し、指定された座標にある指定されたシェイプコレクションの末尾に追加します。

```cpp
static System::SharedPtr<Aspose::Slides::Charts::IChart> Aspose::Slides::Import::ExcelWorkbookImporter::AddChartFromWorkbook(System::SharedPtr<Aspose::Slides::IShapeCollection> shapes, float x, float y, System::SharedPtr<Aspose::Slides::Excel::IExcelDataWorkbook> workbook, System::String worksheetName, System::String chartName, bool embedAllWorkbook)
```


### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| shapes | [System::SharedPtr](../../../system/sharedptr/)\<[Aspose::Slides::IShapeCollection](../../../aspose.slides/ishapecollection/)\> | チャートが追加されるシェイプコレクション。 |
| x | **float** | チャートの位置決めのためのX座標。 |
| y | **float** | チャートの位置決めのためのY座標。 |
| workbook | [System::SharedPtr](../../../system/sharedptr/)\<[Aspose::Slides::Excel::IExcelDataWorkbook](../../../aspose.slides.excel/iexceldataworkbook/)\> | [Excel](../../../aspose.slides.excel/)ワークブック。 |
| worksheetName | [System::String](../../../system/string/) | チャートを含むワークシートの名前。 |
| chartName | [System::String](../../../system/string/) | 追加されるチャートの名前。 |
| embedAllWorkbook | **bool** | **true** の場合、ワークブック全体がチャートに埋め込まれます。**false** の場合、チャートデータのみが埋め込まれます。 |

### 戻り値

シェイプコレクションに追加されたチャート。

## 備考



例: 
```cpp
System::SharedPtr<IExcelDataWorkbook> wb = System::MakeObject<ExcelDataWorkbook>(testFile);
auto pres = System::MakeObject<Presentation>();

System::String worksheetName = u"worksheet name";
auto worksheetCharts = wb->GetChartsFromWorksheet(worksheetName);
for (auto&& chart : worksheetCharts)
{
    System::SharedPtr<ISlide> slide = pres->get_Slides()->AddEmptySlide(pres->get_LayoutSlides()->idx_get(0));
    ExcelWorkbookImporter::AddChartFromWorkbook(slide->get_Shapes(), 10.0f, 10.0f, wb, worksheetName, chart.get_Key(), false);
}
pres->Save(u"result.pptx", SaveFormat::Pptx);
```

## ExcelWorkbookImporter::AddChartFromWorkbook(System::SharedPtr\<Aspose::Slides::IShapeCollection\>, float, float, System::SharedPtr\<System::IO::Stream\>, System::String, System::String, bool) method


指定された[Excel](../../../aspose.slides.excel/)ワークブックからチャートを取得し、指定された座標にある指定されたシェイプコレクションの末尾に追加します。

```cpp
static System::SharedPtr<Aspose::Slides::Charts::IChart> Aspose::Slides::Import::ExcelWorkbookImporter::AddChartFromWorkbook(System::SharedPtr<Aspose::Slides::IShapeCollection> shapes, float x, float y, System::SharedPtr<System::IO::Stream> workbookStream, System::String worksheetName, System::String chartName, bool embedAllWorkbook)
```


### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| shapes | [System::SharedPtr](../../../system/sharedptr/)\<[Aspose::Slides::IShapeCollection](../../../aspose.slides/ishapecollection/)\> | チャートが追加されるシェイプコレクション。 |
| x | **float** | チャートの位置決めのためのX座標。 |
| y | **float** | チャートの位置決めのためのY座標。 |
| workbookStream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | ワークブックデータを含むストリーム。 |
| worksheetName | [System::String](../../../system/string/) | チャートを含むワークシートの名前。 |
| chartName | [System::String](../../../system/string/) | 追加されるチャートの名前。 |
| embedAllWorkbook | **bool** | **true** の場合、ワークブック全体がチャートに埋め込まれます。**false** の場合、チャートデータのみが埋め込まれます。 |

### 戻り値

シェイプコレクションに追加されたチャート。

## 備考



例: 
```cpp
auto fStream = System::MakeObject<System::IO::FileStream>(workbookPath, System::IO::FileMode::Open, System::IO::FileAccess::Read);
auto pres = System::MakeObject<Presentation>();
ExcelWorkbookImporter::AddChartFromWorkbook(pres->get_LayoutSlide(0)->get_Shapes(), 10.0f, 10.0f, fStream, worksheetName, chartName, true);
pres->Save(u"result.pptx", SaveFormat::Pptx);
```

## ExcelWorkbookImporter::AddChartFromWorkbook(System::SharedPtr\<Aspose::Slides::IShapeCollection\>, float, float, System::String, System::String, System::String, bool) method


指定された[Excel](../../../aspose.slides.excel/)ワークブックからチャートを取得し、指定された座標にある指定されたシェイプコレクションの末尾に追加します。

```cpp
static System::SharedPtr<Aspose::Slides::Charts::IChart> Aspose::Slides::Import::ExcelWorkbookImporter::AddChartFromWorkbook(System::SharedPtr<Aspose::Slides::IShapeCollection> shapes, float x, float y, System::String workbookPath, System::String worksheetName, System::String chartName, bool embedWorkbook)
```


### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| shapes | [System::SharedPtr](../../../system/sharedptr/)\<[Aspose::Slides::IShapeCollection](../../../aspose.slides/ishapecollection/)\> | チャートが追加されるシェイプコレクション。 |
| x | **float** | チャートの位置決めのためのX座標。 |
| y | **float** | チャートの位置決めのためのY座標。 |
| workbookPath | [System::String](../../../system/string/) | チャートを含むワークブックへのファイルパス。 |
| worksheetName | [System::String](../../../system/string/) | チャートを含むワークシートの名前。 |
| chartName | [System::String](../../../system/string/) | 追加されるチャートの名前。 |
| embedWorkbook | **bool** | **true** の場合、ワークブックがチャートに埋め込まれます。**false** の場合、チャートは外部ワークブックへのリンクになります。 |

### 戻り値

シェイプコレクションに追加されたチャート。

## 備考



例: 
```cpp
auto pres = System::MakeObject<Presentation>();
ExcelWorkbookImporter::AddChartFromWorkbook(pres->get_Slide(0)->get_Shapes(), 10.0f, 10.0f, workbookPath, worksheetName, chartName, false);
pres->Save(u"result.pptx", SaveFormat::Pptx);
```

## 参照

* 型定義 [SharedPtr](../../../system/sharedptr/)
* クラス [IChart](../../../aspose.slides.charts/ichart/)
* クラス [IShapeCollection](../../../aspose.slides/ishapecollection/)
* クラス [IExcelDataWorkbook](../../../aspose.slides.excel/iexceldataworkbook/)
* クラス [String](../../../system/string/)
* クラス [ExcelWorkbookImporter](../)
* クラス [Stream](../../../system.io/stream/)
* 名前空間 [Aspose::Slides::Import](../../)
* ライブラリ [Aspose.Slides](../../../)