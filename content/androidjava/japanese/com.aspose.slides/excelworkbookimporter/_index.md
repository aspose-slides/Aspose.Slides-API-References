---
title: ExcelWorkbookImporter
second_title: Java API リファレンスによる Android 用 Aspose.Slides
description: Excel ブックからコンテンツをインポートしてプレゼンテーションに追加する機能を提供します。
type: docs
url: /ja/com.aspose.slides/excelworkbookimporter/
---
**継承:**  
java.lang.Object  
```
public class ExcelWorkbookImporter
```

Excel ブックからコンテンツをインポートしてプレゼンテーションに追加する機能を提供します。

## メソッド

| メソッド | 説明 |
| --- | --- |
| [addChartFromWorkbook(IShapeCollection shapes, float x, float y, IExcelDataWorkbook workbook, String worksheetName, int chartIndex, boolean embedAllWorkbook)](#addChartFromWorkbook-com.aspose.slides.IShapeCollection-float-float-com.aspose.slides.IExcelDataWorkbook-java.lang.String-int-boolean-) | 指定された Excel ブックからチャートを取得し、指定された座標で対象のシェイプ コレクションの末尾に追加します。 |
| [addChartFromWorkbook(IShapeCollection shapes, float x, float y, IExcelDataWorkbook workbook, String worksheetName, String chartName, boolean embedAllWorkbook)](#addChartFromWorkbook-com.aspose.slides.IShapeCollection-float-float-com.aspose.slides.IExcelDataWorkbook-java.lang.String-java.lang.String-boolean-) | 指定された Excel ブックからチャートを取得し、指定された座標で対象のシェイプ コレクションの末尾に追加します。 |
| [addChartFromWorkbook(IShapeCollection shapes, float x, float y, InputStream workbookStream, String worksheetName, String chartName, boolean embedAllWorkbook)](#addChartFromWorkbook-com.aspose.slides.IShapeCollection-float-float-java.io.InputStream-java.lang.String-java.lang.String-boolean-) | 指定された Excel ブックからチャートを取得し、指定された座標で対象のシェイプ コレクションの末尾に追加します。 |
| [addChartFromWorkbook(IShapeCollection shapes, float x, float y, String workbookPath, String worksheetName, String chartName, boolean embedWorkbook)](#addChartFromWorkbook-com.aspose.slides.IShapeCollection-float-float-java.lang.String-java.lang.String-java.lang.String-boolean-) | 指定された Excel ブックからチャートを取得し、指定された座標で対象のシェイプ コレクションの末尾に追加します。 |
| [addTableFromWorkbook(IShapeCollection shapes, float x, float y, IExcelDataWorkbook workbook, String worksheetName, String cellRange)](#addTableFromWorkbook-com.aspose.slides.IShapeCollection-float-float-com.aspose.slides.IExcelDataWorkbook-java.lang.String-java.lang.String-) | 指定された Excel ブックからテーブルを取得し、指定された座標で対象のシェイプ コレクションの末尾に追加します。 |
| [addTableFromWorkbook(IShapeCollection shapes, float x, float y, String workbookPath, String worksheetName, String cellRange)](#addTableFromWorkbook-com.aspose.slides.IShapeCollection-float-float-java.lang.String-java.lang.String-java.lang.String-) | 指定された Excel ブック ファイルからテーブルを取得し、指定された座標で対象のシェイプ コレクションの末尾に追加します。 |
| [addTableFromWorkbook(IShapeCollection shapes, float x, float y, InputStream workbookStream, String worksheetName, String cellRange)](#addTableFromWorkbook-com.aspose.slides.IShapeCollection-float-float-java.io.InputStream-java.lang.String-java.lang.String-) | 指定された Excel ブック ファイルからテーブルを取得し、指定された座標で対象のシェイプ コレクションの末尾に追加します。 |

### addChartFromWorkbook(IShapeCollection shapes, float x, float y, IExcelDataWorkbook workbook, String worksheetName, int chartIndex, boolean embedAllWorkbook) {#addChartFromWorkbook-com.aspose.slides.IShapeCollection-float-float-com.aspose.slides.IExcelDataWorkbook-java.lang.String-int-boolean-}
```
public static IChart addChartFromWorkbook(IShapeCollection shapes, float x, float y, IExcelDataWorkbook workbook, String worksheetName, int chartIndex, boolean embedAllWorkbook)
```

指定された Excel ブックからチャートを取得し、指定された座標で対象のシェイプ コレクションの末尾に追加します。

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
| shapes | [IShapeCollection](../../com.aspose.slides/ishapecollection) | チャートが追加されるシェイプ コレクション。 |
| x | float | チャートの配置に使用する X 座標。 |
| y | float | チャートの配置に使用する Y 座標。 |
| workbook | [IExcelDataWorkbook](../../com.aspose.slides/iexceldataworkbook) | Excel ブック。 |
| worksheetName | java.lang.String | チャートが含まれるワークシートの名前。 |
| chartIndex | int | 挿入するチャート シェイプのゼロベース インデックス。このインデックスは [IExcelDataWorkbook.getChartsFromWorksheet(String)](../../com.aspose.slides/iexceldataworkbook\#getChartsFromWorksheet-String-) メソッドで取得できます。 |
| embedAllWorkbook | boolean | true の場合、ブック全体がチャートに埋め込まれます。false の場合、チャート データのみが埋め込まれます。 |

**戻り値:**
[IChart](../../com.aspose.slides/ichart) - 形状コレクションに追加されたチャート。

### addChartFromWorkbook(IShapeCollection shapes, float x, float y, IExcelDataWorkbook workbook, String worksheetName, String chartName, boolean embedAllWorkbook) {#addChartFromWorkbook-com.aspose.slides.IShapeCollection-float-float-com.aspose.slides.IExcelDataWorkbook-java.lang.String-java.lang.String-boolean-}
```
public static IChart addChartFromWorkbook(IShapeCollection shapes, float x, float y, IExcelDataWorkbook workbook, String worksheetName, String chartName, boolean embedAllWorkbook)
```

指定された Excel ブックからチャートを取得し、指定された座標で対象のシェイプ コレクションの末尾に追加します。

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
| shapes | [IShapeCollection](../../com.aspose.slides/ishapecollection) | チャートが追加されるシェイプ コレクション。 |
| x | float | チャートの配置に使用する X 座標。 |
| y | float | チャートの配置に使用する Y 座標。 |
| workbook | [IExcelDataWorkbook](../../com.aspose.slides/iexceldataworkbook) | Excel ブック。 |
| worksheetName | java.lang.String | チャートが含まれるワークシートの名前。 |
| chartName | java.lang.String | 追加するチャートの名前。 |
| embedAllWorkbook | boolean | true の場合、ブック全体がチャートに埋め込まれます。false の場合、チャート データのみが埋め込まれます。 |

**戻り値:**
[IChart](../../com.aspose.slides/ichart) - 形状コレクションに追加されたチャート。

### addChartFromWorkbook(IShapeCollection shapes, float x, float y, InputStream workbookStream, String worksheetName, String chartName, boolean embedAllWorkbook) {#addChartFromWorkbook-com.aspose.slides.IShapeCollection-float-float-java.io.InputStream-java.lang.String-java.lang.String-boolean-}
```
public static IChart addChartFromWorkbook(IShapeCollection shapes, float x, float y, InputStream workbookStream, String worksheetName, String chartName, boolean embedAllWorkbook)
```

指定された Excel ブックからチャートを取得し、指定された座標で対象のシェイプ コレクションの末尾に追加します。

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
| shapes | [IShapeCollection](../../com.aspose.slides/ishapecollection) | チャートが追加されるシェイプ コレクション。 |
| x | float | チャートの配置に使用する X 座標。 |
| y | float | チャートの配置に使用する Y 座標。 |
| workbookStream | java.io.InputStream | ブック データを含むストリーム。 |
| worksheetName | java.lang.String | チャートが含まれるワークシートの名前。 |
| chartName | java.lang.String | 追加するチャートの名前。 |
| embedAllWorkbook | boolean | true の場合、ブック全体がチャートに埋め込まれます。false の場合、チャート データのみが埋め込まれます。 |

**戻り値:**
[IChart](../../com.aspose.slides/ichart) - 形状コレクションに追加されたチャート。

### addChartFromWorkbook(IShapeCollection shapes, float x, float y, String workbookPath, String worksheetName, String chartName, boolean embedWorkbook) {#addChartFromWorkbook-com.aspose.slides.IShapeCollection-float-float-java.lang.String-java.lang.String-java.lang.String-boolean-}
```
public static IChart addChartFromWorkbook(IShapeCollection shapes, float x, float y, String workbookPath, String worksheetName, String chartName, boolean embedWorkbook)
```

指定された Excel ブックからチャートを取得し、指定された座標で対象のシェイプ コレクションの末尾に追加します。

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
| shapes | [IShapeCollection](../../com.aspose.slides/ishapecollection) | チャートが追加されるシェイプ コレクション。 |
| x | float | チャートの配置に使用する X 座標。 |
| y | float | チャートの配置に使用する Y 座標。 |
| workbookPath | java.lang.String | チャートを含むブックへのファイル パス。 |
| worksheetName | java.lang.String | チャートが含まれるワークシートの名前。 |
| chartName | java.lang.String | 追加するチャートの名前。 |
| embedWorkbook | boolean | true の場合、ブックがチャートに埋め込まれます。false の場合、チャートは外部ブックへのリンクになります。 |

**戻り値:**
[IChart](../../com.aspose.slides/ichart) - 形状コレクションに追加されたチャート。

### addTableFromWorkbook(IShapeCollection shapes, float x, float y, IExcelDataWorkbook workbook, String worksheetName, String cellRange) {#addTableFromWorkbook-com.aspose.slides.IShapeCollection-float-float-com.aspose.slides.IExcelDataWorkbook-java.lang.String-java.lang.String-}
```
public static ITable addTableFromWorkbook(IShapeCollection shapes, float x, float y, IExcelDataWorkbook workbook, String worksheetName, String cellRange)
```

指定された Excel ブックからテーブルを取得し、指定された座標で対象のシェイプ コレクションの末尾に追加します。

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
| shapes | [IShapeCollection](../../com.aspose.slides/ishapecollection) | テーブルが追加されるシェイプ コレクション。 |
| x | float | テーブルの配置に使用する X 座標。 |
| y | float | テーブルの配置に使用する Y 座標。 |
| workbook | [IExcelDataWorkbook](../../com.aspose.slides/iexceldataworkbook) | Excel ブック。 |
| worksheetName | java.lang.String | テーブルが含まれるワークシートの名前。 |
| cellRange | java.lang.String | テーブルを定義するセル範囲（例: "A1:D10"）。 |

**戻り値:**
[ITable](../../com.aspose.slides/itable) - 形状コレクションに追加されたテーブル。

### addTableFromWorkbook(IShapeCollection shapes, float x, float y, String workbookPath, String worksheetName, String cellRange) {#addTableFromWorkbook-com.aspose.slides.IShapeCollection-float-float-java.lang.String-java.lang.String-java.lang.String-}
```
public static ITable addTableFromWorkbook(IShapeCollection shapes, float x, float y, String workbookPath, String worksheetName, String cellRange)
```

指定された Excel ブック ファイルからテーブルを取得し、指定された座標で対象のシェイプ コレクションの末尾に追加します。

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
| shapes | [IShapeCollection](../../com.aspose.slides/ishapecollection) | テーブルが追加されるシェイプ コレクション。 |
| x | float | テーブルの配置に使用する X 座標。 |
| y | float | テーブルの配置に使用する Y 座標。 |
| workbookPath | java.lang.String | Excel ブック ファイルへのパス。 |
| worksheetName | java.lang.String | テーブルが含まれるワークシートの名前。 |
| cellRange | java.lang.String | テーブルを定義するセル範囲（例: "A1:D10"）。 |

**戻り値:**
[ITable](../../com.aspose.slides/itable) - 形状コレクションに追加されたテーブル。

### addTableFromWorkbook(IShapeCollection shapes, float x, float y, InputStream workbookStream, String worksheetName, String cellRange) {#addTableFromWorkbook-com.aspose.slides.IShapeCollection-float-float-java.io.InputStream-java.lang.String-java.lang.String-}
```
public static ITable addTableFromWorkbook(IShapeCollection shapes, float x, float y, InputStream workbookStream, String worksheetName, String cellRange)
```

指定された Excel ブック ファイルからテーブルを取得し、指定された座標で対象のシェイプ コレクションの末尾に追加します。

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
| shapes | [IShapeCollection](../../com.aspose.slides/ishapecollection) | テーブルが追加されるシェイプ コレクション。 |
| x | float | テーブルの配置に使用する X 座標。 |
| y | float | テーブルの配置に使用する Y 座標。 |
| workbookStream | java.io.InputStream | ブック データを含むストリーム。 |
| worksheetName | java.lang.String | テーブルが含まれるワークシートの名前。 |
| cellRange | java.lang.String | テーブルを定義するセル範囲（例: "A1:D10"）。 |

**戻り値:**
[ITable](../../com.aspose.slides/itable) - 形状コレクションに追加されたテーブル。