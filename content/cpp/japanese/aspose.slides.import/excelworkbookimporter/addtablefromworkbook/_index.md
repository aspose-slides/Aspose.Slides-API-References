---
title: AddTableFromWorkbook()
second_title: Aspose.Slides for C++ API リファレンス
description: 指定された Excel ワークブックからテーブルを取得し、指定された座標で対象のシェイプコレクションの末尾に追加します。
type: docs
weight: 14
url: /ja/aspose.slides.import/excelworkbookimporter/addtablefromworkbook/
---
## ExcelWorkbookImporter::AddTableFromWorkbook(System::SharedPtr\<Aspose::Slides::IShapeCollection\>, float, float, System::SharedPtr\<Aspose::Slides::Excel::IExcelDataWorkbook\>, System::String, System::String) メソッド


指定された[Excel](../../../aspose.slides.excel/)ワークブックからテーブルを取得し、指定された座標で対象のシェイプコレクションの末尾に追加します。

```cpp
static System::SharedPtr<Aspose::Slides::ITable> Aspose::Slides::Import::ExcelWorkbookImporter::AddTableFromWorkbook(System::SharedPtr<Aspose::Slides::IShapeCollection> shapes, float x, float y, System::SharedPtr<Aspose::Slides::Excel::IExcelDataWorkbook> workbook, System::String worksheetName, System::String cellRange)
```


### 引数

| Parameter | Type | Description |
| --- | --- | --- |
| shapes | [System::SharedPtr](../../../system/sharedptr/)\<[Aspose::Slides::IShapeCollection](../../../aspose.slides/ishapecollection/)\> | テーブルが追加されるシェイプコレクション。 |
| x | **float** | テーブルの配置のための X 座標。 |
| y | **float** | テーブルの配置のための Y 座標。 |
| workbook | [System::SharedPtr](../../../system/sharedptr/)\<[Aspose::Slides::Excel::IExcelDataWorkbook](../../../aspose.slides.excel/iexceldataworkbook/)\> | [Excel](../../../aspose.slides.excel/) ワークブック。 |
| worksheetName | [System::String](../../../system/string/) | テーブルを含むワークシートの名前。 |
| cellRange | [System::String](../../../system/string/) | テーブルを定義するセル範囲（例: "A1:D10"）。 |

### 戻り値

シェイプコレクションに追加されたテーブル。

## 備考




```cpp
auto pres = System::MakeObject<Presentation>();
ExcelWorkbookImporter::AddChartFromWorkbook(pres->get_Slide(0)->get_Shapes(), 10.0f, 10.0f, workbook, worksheetName, cellRange);
pres->Save(u"result.pptx", SaveFormat::Pptx);
```

## ExcelWorkbookImporter::AddTableFromWorkbook(System::SharedPtr\<Aspose::Slides::IShapeCollection\>, float, float, System::String, System::String, System::String) メソッド


指定された[Excel](../../../aspose.slides.excel/)ワークブックファイルからテーブルを取得し、指定された座標で対象のシェイプコレクションの末尾に追加します。

```cpp
static System::SharedPtr<Aspose::Slides::ITable> Aspose::Slides::Import::ExcelWorkbookImporter::AddTableFromWorkbook(System::SharedPtr<Aspose::Slides::IShapeCollection> shapes, float x, float y, System::String workbookPath, System::String worksheetName, System::String cellRange)
```


### 引数

| Parameter | Type | Description |
| --- | --- | --- |
| shapes | [System::SharedPtr](../../../system/sharedptr/)\<[Aspose::Slides::IShapeCollection](../../../aspose.slides/ishapecollection/)\> | テーブルが追加されるシェイプコレクション。 |
| x | **float** | テーブルの配置のための X 座標。 |
| y | **float** | テーブルの配置のための Y 座標。 |
| workbookPath | [System::String](../../../system/string/) | [Excel](../../../aspose.slides.excel/) ワークブックファイルへのパス。 |
| worksheetName | [System::String](../../../system/string/) | テーブルを含むワークシートの名前。 |
| cellRange | [System::String](../../../system/string/) | テーブルを定義するセル範囲（例: "A1:D10"）。 |

### 戻り値

シェイプコレクションに追加されたテーブル。

## 備考




```cpp
auto pres = System::MakeObject<Presentation>();
ExcelWorkbookImporter::AddChartFromWorkbook(pres->get_Slide(0)->get_Shapes(), 10.0f, 10.0f, workbookPath, worksheetName, cellRange);
pres->Save(u"result.pptx", SaveFormat::Pptx);
```

## ExcelWorkbookImporter::AddTableFromWorkbook(System::SharedPtr\<Aspose::Slides::IShapeCollection\>, float, float, System::SharedPtr\<System::IO::Stream\>, System::String, System::String) メソッド


指定された[Excel](../../../aspose.slides.excel/)ワークブックファイルからテーブルを取得し、指定された座標で対象のシェイプコレクションの末尾に追加します。

```cpp
static System::SharedPtr<Aspose::Slides::ITable> Aspose::Slides::Import::ExcelWorkbookImporter::AddTableFromWorkbook(System::SharedPtr<Aspose::Slides::IShapeCollection> shapes, float x, float y, System::SharedPtr<System::IO::Stream> workbookStream, System::String worksheetName, System::String cellRange)
```


### 引数

| Parameter | Type | Description |
| --- | --- | --- |
| shapes | [System::SharedPtr](../../../system/sharedptr/)\<[Aspose::Slides::IShapeCollection](../../../aspose.slides/ishapecollection/)\> | テーブルが追加されるシェイプコレクション。 |
| x | **float** | テーブルの配置のための X 座標。 |
| y | **float** | テーブルの配置のための Y 座標。 |
| workbookStream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | ワークブックデータを含むストリーム。 |
| worksheetName | [System::String](../../../system/string/) | テーブルを含むワークシートの名前。 |
| cellRange | [System::String](../../../system/string/) | テーブルを定義するセル範囲（例: "A1:D10"）。 |

### 戻り値

シェイプコレクションに追加されたテーブル。

## 備考




```cpp
auto pres = System::MakeObject<Presentation>();
ExcelWorkbookImporter::AddChartFromWorkbook(pres->get_Slide(0)->get_Shapes(), 10.0f, 10.0f, fStream, worksheetName, cellRange);
pres->Save(u"result.pptx", SaveFormat::Pptx);
```

## 参照

* Typedef [SharedPtr](../../../system/sharedptr/)
* クラス [ITable](../../../aspose.slides/itable/)
* クラス [IShapeCollection](../../../aspose.slides/ishapecollection/)
* クラス [IExcelDataWorkbook](../../../aspose.slides.excel/iexceldataworkbook/)
* クラス [String](../../../system/string/)
* クラス [ExcelWorkbookImporter](../)
* クラス [Stream](../../../system.io/stream/)
* 名前空間 [Aspose::Slides::Import](../../)
* ライブラリ [Aspose.Slides](../../../)