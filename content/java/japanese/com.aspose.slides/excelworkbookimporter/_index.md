---
title: ExcelWorkbookImporter
second_title: Aspose.Slides for Java API リファレンス
description: Excel ワークブックからコンテンツをインポートし、プレゼンテーションに追加する機能を提供します。
type: docs
url: /ja/com.aspose.slides/excelworkbookimporter/
---
**継承:**  
java.lang.Object
```
public class ExcelWorkbookImporter
```

Excel ワークブックからコンテンツをインポートしてプレゼンテーションに追加する機能を提供します。

## メソッド

| メソッド | 説明 |
| --- | --- |
| [addChartFromWorkbook(IShapeCollection shapes, float x, float y, IExcelDataWorkbook workbook, String worksheetName, int chartIndex, boolean embedAllWorkbook)](#addChartFromWorkbook-com.aspose.slides.IShapeCollection-float-float-com.aspose.slides.IExcelDataWorkbook-java.lang.String-int-boolean-) | Retrieves a chart from the specified Excel workbook and adds it to the end of the given shape collection at the specified coordinates. |
| [addChartFromWorkbook(IShapeCollection shapes, float x, float y, IExcelDataWorkbook workbook, String worksheetName, String chartName, boolean embedAllWorkbook)](#addChartFromWorkbook-com.aspose.slides.IShapeCollection-float-float-com.aspose.slides.IExcelDataWorkbook-java.lang.String-java.lang.String-boolean-) | Retrieves a chart from the specified Excel workbook and adds it to the end of the given shape collection at the specified coordinates. |
| [addChartFromWorkbook(IShapeCollection shapes, float x, float y, InputStream workbookStream, String worksheetName, String chartName, boolean embedAllWorkbook)](#addChartFromWorkbook-com.aspose.slides.IShapeCollection-float-float-java.io.InputStream-java.lang.String-java.lang.String-boolean-) | Retrieves a chart from the specified Excel workbook and adds it to the end of the given shape collection at the specified coordinates. |
| [addChartFromWorkbook(IShapeCollection shapes, float x, float y, String workbookPath, String worksheetName, String chartName, boolean embedWorkbook)](#addChartFromWorkbook-com.aspose.slides.IShapeCollection-float-float-java.lang.String-java.lang.String-java.lang.String-boolean-) | Retrieves a chart from the specified Excel workbook and adds it to the end of the given shape collection at the specified coordinates. |
| [addTableFromWorkbook(IShapeCollection shapes, float x, float y, IExcelDataWorkbook workbook, String worksheetName, String cellRange)](#addTableFromWorkbook-com.aspose.slides.IShapeCollection-float-float-com.aspose.slides.IExcelDataWorkbook-java.lang.String-java.lang.String-) | Retrieves a table from the specified Excel workbook and adds it to the end of the given shape collection at the specified coordinates. |
| [addTableFromWorkbook(IShapeCollection shapes, float x, float y, String workbookPath, String worksheetName, String cellRange)](#addTableFromWorkbook-com.aspose.slides.IShapeCollection-float-float-java.lang.String-java.lang.String-java.lang.String-) | Retrieves a table from the specified Excel workbook file and adds it to the end of the given shape collection at the specified coordinates. |
| [addTableFromWorkbook(IShapeCollection shapes, float x, float y, InputStream workbookStream, String worksheetName, String cellRange)](#addTableFromWorkbook-com.aspose.slides.IShapeCollection-float-float-java.io.InputStream-java.lang.String-java.lang.String-) | Retrieves a table from the specified Excel workbook file and adds it to the end of the given shape collection at the specified coordinates. |

### addChartFromWorkbook(IShapeCollection shapes, float x, float y, IExcelDataWorkbook workbook, String worksheetName, int chartIndex, boolean embedAllWorkbook) {#addChartFromWorkbook-com.aspose.slides.IShapeCollection-float-float-com.aspose.slides.IExcelDataWorkbook-java.lang.String-int-boolean-}
```
public static IChart addChartFromWorkbook(IShapeCollection shapes, float x, float y, IExcelDataWorkbook workbook, String worksheetName, int chartIndex, boolean embedAllWorkbook)
```

指定された Excel ワークブックからチャートを取得し、指定された座標で対象のシェイプコレクションの末尾に追加します。

--------------------

> ```
> Example:
>  
>  IExcelDataWorkbook wb = new ExcelDataWorkbook(testFile);
>  Presentation pres = new Presentation();
>  try {
>      ExcelWorkbookImporter.addChartFromWorkbook(pres.getSlides().get_Item(0).getShapes(), 10, 10, wb, worksheetName, chartName, false);
>      pres.save("result.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| shapes | [IShapeCollection](../../com.aspose.slides/ishapecollection) | チャートが追加されるシェイプコレクション。 |
| x | float | チャートの配置座標 X。 |
| y | float | チャートの配置座標 Y。 |
| workbook | [IExcelDataWorkbook](../../com.aspose.slides/iexceldataworkbook) | Excel ワークブック。 |
| worksheetName | java.lang.String | チャートが含まれるワークシートの名前。 |
| chartIndex | int | 挿入するチャートシェイプの 0 ベースインデックス。このインデックスは [IExcelDataWorkbook.getChartsFromWorksheet(String)](../../com.aspose.slides/iexceldataworkbook\#getChartsFromWorksheet-String-) メソッドで取得できます。 |
| embedAllWorkbook | boolean | true の場合、ワークブック全体がチャートに埋め込まれます。false の場合、チャートデータのみが埋め込まれます。 |

**戻り値:**
[IChart](../../com.aspose.slides/ichart) - シェイプコレクションに追加されたチャート。

### addChartFromWorkbook(IShapeCollection shapes, float x, float y, IExcelDataWorkbook workbook, String worksheetName, String chartName, boolean embedAllWorkbook) {#addChartFromWorkbook-com.aspose.slides.IShapeCollection-float-float-com.aspose.slides.IExcelDataWorkbook-java.lang.String-java.lang.String-boolean-}
```
public static IChart addChartFromWorkbook(IShapeCollection shapes, float x, float y, IExcelDataWorkbook workbook, String worksheetName, String chartName, boolean embedAllWorkbook)
```

指定された Excel ワークブックからチャートを取得し、指定された座標で対象のシェイプコレクションの末尾に追加します。

--------------------

> ```
> Example:
>  
>  IExcelDataWorkbook wb = new ExcelDataWorkbook(testFile);
>  Presentation pres = new Presentation();
>  try {
>      String worksheetName = "worksheet name";
>      Dictionary.Enumerator<Integer, String> worksheetCharts = wb.getChartsFromWorksheet(worksheetName).iterator();
>      while (worksheetCharts.hasNext())
>      {
>          KeyValuePair<Integer, String> chart = worksheetCharts.next();
>          ISlide slide = pres.getSlides().addEmptySlide(pres.getLayoutSlides().get_Item(0));
>          ExcelWorkbookImporter.addChartFromWorkbook(slide.getShapes(), 10, 10, wb, worksheetName, chart.getKey(), false);
>      }
>      pres.save("result.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| shapes | [IShapeCollection](../../com.aspose.slides/ishapecollection) | チャートが追加されるシェイプコレクション。 |
| x | float | チャートの配置座標 X。 |
| y | float | チャートの配置座標 Y。 |
| workbook | [IExcelDataWorkbook](../../com.aspose.slides/iexceldataworkbook) | Excel ワークブック。 |
| worksheetName | java.lang.String | チャートが含まれるワークシートの名前。 |
| chartName | java.lang.String | 追加されるチャートの名前。 |
| embedAllWorkbook | boolean | true の場合、ワークブック全体がチャートに埋め込まれます。false の場合、チャートデータのみが埋め込まれます。 |

**戻り値:**
[IChart](../../com.aspose.slides/ichart) - シェイプコレクションに追加されたチャート。

### addChartFromWorkbook(IShapeCollection shapes, float x, float y, InputStream workbookStream, String worksheetName, String chartName, boolean embedAllWorkbook) {#addChartFromWorkbook-com.aspose.slides.IShapeCollection-float-float-java.io.InputStream-java.lang.String-java.lang.String-boolean-}
```
public static IChart addChartFromWorkbook(IShapeCollection shapes, float x, float y, InputStream workbookStream, String worksheetName, String chartName, boolean embedAllWorkbook)
```

指定された Excel ワークブックからチャートを取得し、指定された座標で対象のシェイプコレクションの末尾に追加します。

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation();
>  try {
>      FileInputStream fStream = new FileInputStream(workbookPath);
>      ExcelWorkbookImporter.addChartFromWorkbook(pres.getLayoutSlides().get_Item(0).getShapes(), 10, 10, fStream, worksheetName, chartName, true);
>      fStream.close();
>      pres.save("result.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| shapes | [IShapeCollection](../../com.aspose.slides/ishapecollection) | チャートが追加されるシェイプコレクション。 |
| x | float | チャートの配置座標 X。 |
| y | float | チャートの配置座標 Y。 |
| workbookStream | java.io.InputStream | ワークブックデータを含むストリーム。 |
| worksheetName | java.lang.String | チャートが含まれるワークシートの名前。 |
| chartName | java.lang.String | 追加されるチャートの名前。 |
| embedAllWorkbook | boolean | true の場合、ワークブック全体がチャートに埋め込まれます。false の場合、チャートデータのみが埋め込まれます。 |

**戻り値:**
[IChart](../../com.aspose.slides/ichart) - シェイプコレクションに追加されたチャート。

### addChartFromWorkbook(IShapeCollection shapes, float x, float y, String workbookPath, String worksheetName, String chartName, boolean embedWorkbook) {#addChartFromWorkbook-com.aspose.slides.IShapeCollection-float-float-java.lang.String-java.lang.String-java.lang.String-boolean-}
```
public static IChart addChartFromWorkbook(IShapeCollection shapes, float x, float y, String workbookPath, String worksheetName, String chartName, boolean embedWorkbook)
```

指定された Excel ワークブックからチャートを取得し、指定された座標で対象のシェイプコレクションの末尾に追加します。

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation();
>  try {
>      ExcelWorkbookImporter.addChartFromWorkbook(pres.getSlides().get_Item(0).getShapes(), 10, 10, workbookPath, worksheetName, chartName, false);
>      pres.save("result.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| shapes | [IShapeCollection](../../com.aspose.slides/ishapecollection) | チャートが追加されるシェイプコレクション。 |
| x | float | チャートの配置座標 X。 |
| y | float | チャートの配置座標 Y。 |
| workbookPath | java.lang.String | チャートを含むワークブックへのファイルパス。 |
| worksheetName | java.lang.String | チャートが含まれるワークシートの名前。 |
| chartName | java.lang.String | 追加されるチャートの名前。 |
| embedWorkbook | boolean | true の場合、ワークブックがチャートに埋め込まれます。false の場合、チャートは外部ワークブックへのリンクになります。 |

**戻り値:**
[IChart](../../com.aspose.slides/ichart) - シェイプコレクションに追加されたチャート。

### addTableFromWorkbook(IShapeCollection shapes, float x, float y, IExcelDataWorkbook workbook, String worksheetName, String cellRange) {#addTableFromWorkbook-com.aspose.slides.IShapeCollection-float-float-com.aspose.slides.IExcelDataWorkbook-java.lang.String-java.lang.String-}
```
public static ITable addTableFromWorkbook(IShapeCollection shapes, float x, float y, IExcelDataWorkbook workbook, String worksheetName, String cellRange)
```

指定された Excel ワークブックからテーブルを取得し、指定された座標で対象のシェイプコレクションの末尾に追加します。

--------------------

> ```
> IExcelDataWorkbook workbook = new ExcelDataWorkbook(testFile);
>  Presentation pres = new Presentation();
>  try {
>      ExcelWorkbookImporter.addTableFromWorkbook(pres.getSlides().get_Item(0).getShapes(), 10, 10, workbook, worksheetName, "A1:D10");
>      pres.save("result.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| shapes | [IShapeCollection](../../com.aspose.slides/ishapecollection) | テーブルが追加されるシェイプコレクション。 |
| x | float | テーブルの配置座標 X。 |
| y | float | テーブルの配置座標 Y。 |
| workbook | [IExcelDataWorkbook](../../com.aspose.slides/iexceldataworkbook) | Excel ワークブック。 |
| worksheetName | java.lang.String | テーブルが含まれるワークシートの名前。 |
| cellRange | java.lang.String | テーブルを定義するセル範囲（例: "A1:D10"）。 |

**戻り値:**
[ITable](../../com.aspose.slides/itable) - シェイプコレクションに追加されたテーブル。

### addTableFromWorkbook(IShapeCollection shapes, float x, float y, String workbookPath, String worksheetName, String cellRange) {#addTableFromWorkbook-com.aspose.slides.IShapeCollection-float-float-java.lang.String-java.lang.String-java.lang.String-}
```
public static ITable addTableFromWorkbook(IShapeCollection shapes, float x, float y, String workbookPath, String worksheetName, String cellRange)
```

指定された Excel ワークブックファイルからテーブルを取得し、指定された座標で対象のシェイプコレクションの末尾に追加します。

--------------------

> ```
> Presentation pres = new Presentation();
>  try {
>      ExcelWorkbookImporter.addTableFromWorkbook(pres.getSlides().get_Item(0).getShapes(), 10, 10, workbookPath, worksheetName, "A1:D10");
>      pres.save("result.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| shapes | [IShapeCollection](../../com.aspose.slides/ishapecollection) | テーブルが追加されるシェイプコレクション。 |
| x | float | テーブルの配置座標 X。 |
| y | float | テーブルの配置座標 Y。 |
| workbookPath | java.lang.String | Excel ワークブックファイルへのパス。 |
| worksheetName | java.lang.String | テーブルが含まれるワークシートの名前。 |
| cellRange | java.lang.String | テーブルを定義するセル範囲（例: "A1:D10"）。 |

**戻り値:**
[ITable](../../com.aspose.slides/itable) - シェイプコレクションに追加されたテーブル。

### addTableFromWorkbook(IShapeCollection shapes, float x, float y, InputStream workbookStream, String worksheetName, String cellRange) {#addTableFromWorkbook-com.aspose.slides.IShapeCollection-float-float-java.io.InputStream-java.lang.String-java.lang.String-}
```
public static ITable addTableFromWorkbook(IShapeCollection shapes, float x, float y, InputStream workbookStream, String worksheetName, String cellRange)
```

指定された Excel ワークブックファイルからテーブルを取得し、指定された座標で対象のシェイプコレクションの末尾に追加します。

--------------------

> ```
> FileInputStream fStream = new FileInputStream(workbookPath);
>  Presentation pres = new Presentation();
>  try {
>      ExcelWorkbookImporter.addTableFromWorkbook(pres.getSlides().get_Item(0).getShapes(), 10, 10, fStream, worksheetName, "A1:D10");
>      pres.save("result.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| shapes | [IShapeCollection](../../com.aspose.slides/ishapecollection) | テーブルが追加されるシェイプコレクション。 |
| x | float | テーブルの配置座標 X。 |
| y | float | テーブルの配置座標 Y。 |
| workbookStream | java.io.InputStream | ワークブックデータを含むストリーム。 |
| worksheetName | java.lang.String | テーブルが含まれるワークシートの名前。 |
| cellRange | java.lang.String | テーブルを定義するセル範囲（例: "A1:D10"）。 |

**戻り値:**
[ITable](../../com.aspose.slides/itable) - シェイプコレクションに追加されたテーブル。