---
title: GraphicsPath
second_title: Aspose.Slides for C++ API 參考
description: "表示一組相連的直線與曲線。本類別的物件應只使用 System::MakeObject() 函式分配。切勿在堆疊上或使用 operator new 建立此類型的實例，因為會導致執行時錯誤和/或斷言失敗。請始終將此類別包裝成 System::SmartPtr 指標，並使用該指標作為參數傳遞給函式。"
type: docs
weight: 66
url: /zh-hant/system.drawing.drawing2d/graphicspath/
---
## GraphicsPath 類別

表示一組相連的直線與曲線。此類別的物件只能使用 [System::MakeObject()](../../system/makeobject/) 函式分配。切勿在堆疊上或使用 operator new 建立此類型的實例，否則會導致執行時錯誤和/或斷言失敗。請始終將此類別包裝成 [System::SmartPtr](../../system/smartptr/) 指標，並使用該指標作為參數傳遞給函式。

```cpp
class GraphicsPath : public System::Object
```

## 方法

| 方法 | 描述 |
| --- | --- |
| void [AddArc](./addarc/)(**float**, **float**, **float**, **float**, **float**, **float**) | 將指定的橢圓弧段加入目前物件所代表的路徑。 |
| void [AddArc](./addarc/)(int, int, int, int, **float**, **float**) | 將指定的橢圓弧段加入目前物件所代表的路徑。 |
| void [AddArc](./addarc/)(const [RectangleF](../../system.drawing/rectanglef/)\&, **float**, **float**) | 將指定的橢圓弧段加入目前物件所代表的路徑。 |
| void [AddArc](./addarc/)(const [Rectangle](../../system.drawing/rectangle/)\&, **float**, **float**) | 將指定的橢圓弧段加入目前物件所代表的路徑。 |
| void [AddBezier](./addbezier/)(const [Point](../../system.drawing/point/)\&, const [Point](../../system.drawing/point/)\&, const [Point](../../system.drawing/point/)\&, const [Point](../../system.drawing/point/)\&) | 將指定的三次貝茲曲線加入目前物件所代表的路徑。 |
| void [AddBezier](./addbezier/)(const [PointF](../../system.drawing/pointf/)\&, const [PointF](../../system.drawing/pointf/)\&, const [PointF](../../system.drawing/pointf/)\&, const [PointF](../../system.drawing/pointf/)\&) | 將指定的三次貝茲曲線加入目前物件所代表的路徑。 |
| void [AddBezier](./addbezier/)(int, int, int, int, int, int, int, int) | 將指定的三次貝茲曲線加入目前物件所代表的路徑。 |
| void [AddBezier](./addbezier/)(**float**, **float**, **float**, **float**, **float**, **float**, **float**, **float**) | 將指定的三次貝茲曲線加入目前物件所代表的路徑。 |
| void [AddBeziers](./addbeziers/)(const [ArrayPtr](../../system/arrayptr/)\<[Point](../../system.drawing/point/)\>\&) | 將一系列相連的三次貝茲曲線加入目前圖形。 |
| void [AddBeziers](./addbeziers/)(const [ArrayPtr](../../system/arrayptr/)\<[PointF](../../system.drawing/pointf/)\>\&) | 將一系列相連的三次貝茲曲線加入目前圖形。 |
| void [AddClosedCurve](./addclosedcurve/)(const [ArrayPtr](../../system/arrayptr/)\<[PointF](../../system.drawing/pointf/)\>\&, **float**) | 將指定的封閉曲線加入目前物件所代表的路徑。 |
| void [AddClosedCurve](./addclosedcurve/)(const [ArrayPtr](../../system/arrayptr/)\<[Point](../../system.drawing/point/)\>\&, **float**) | 將指定的封閉曲線加入目前物件所代表的路徑。 |
| void [AddCurve](./addcurve/)(const [ArrayPtr](../../system/arrayptr/)\<[PointF](../../system.drawing/pointf/)\>\&, **float**) | 將指定的曲線加入目前物件所代表的路徑。 |
| void [AddCurve](./addcurve/)(const [ArrayPtr](../../system/arrayptr/)\<[Point](../../system.drawing/point/)\>\&, **float**) | 將指定的曲線加入目前物件所代表的路徑。 |
| void [AddCurve](./addcurve/)(const [ArrayPtr](../../system/arrayptr/)\<[PointF](../../system.drawing/pointf/)\>\&, int, int, **float**) | 將指定的曲線加入目前物件所代表的路徑。 |
| void [AddCurve](./addcurve/)(const [ArrayPtr](../../system/arrayptr/)\<[Point](../../system.drawing/point/)\>\&, int, int, **float**) | 將指定的曲線加入目前物件所代表的路徑。 |
| void [AddEllipse](./addellipse/)(**float**, **float**, **float**, **float**) | 將指定的橢圓加入目前物件所代表的路徑。 |
| void [AddEllipse](./addellipse/)(int, int, int, int) | 將指定的橢圓加入目前物件所代表的路徑。 |
| void [AddEllipse](./addellipse/)(const [RectangleF](../../system.drawing/rectanglef/)\&) | 將指定的橢圓加入目前物件所代表的路徑。 |
| void [AddEllipse](./addellipse/)(const [Rectangle](../../system.drawing/rectangle/)\&) | 將指定的橢圓加入目前物件所代表的路徑。 |
| void [AddLine](./addline/)(const [Point](../../system.drawing/point/)\&, const [Point](../../system.drawing/point/)\&) | 將指定的直線加入目前物件所代表的路徑。 |
| void [AddLine](./addline/)(const [PointF](../../system.drawing/pointf/)\&, const [PointF](../../system.drawing/pointf/)\&) | 將指定的直線加入目前物件所代表的路徑。 |
| void [AddLine](./addline/)(int, int, int, int) | 將指定的直線加入目前物件所代表的路徑。 |
| void [AddLine](./addline/)(**float**, **float**, **float**, **float**) | 將指定的直線加入目前物件所代表的路徑。 |
| void [AddLines](./addlines/)(const [ArrayPtr](../../system/arrayptr/)\<[PointF](../../system.drawing/pointf/)\>\&) | 將一系列相連的線段加入目前物件所代表的路徑。 |
| void [AddLines](./addlines/)(const [ArrayPtr](../../system/arrayptr/)\<[Point](../../system.drawing/point/)\>\&) | 將一系列相連的線段加入目前物件所代表的路徑。 |
| void [AddPath](./addpath/)(const [SharedPtr](../../system/sharedptr/)\<[GraphicsPath](./)\>\&, **bool**) | 將指定的路徑加入目前物件所代表的路徑。 |
| void [AddPie](./addpie/)(**float**, **float**, **float**, **float**, **float**, **float**) | 將指定的餅形輪廓加入目前物件所代表的路徑。 |
| void [AddPie](./addpie/)(int, int, int, int, **float**, **float**) | 將指定的餅形輪廓加入目前物件所代表的路徑。 |
| void [AddPie](./addpie/)(const [Rectangle](../../system.drawing/rectangle/)\&, **float**, **float**) | 將指定的餅形輪廓加入目前物件所代表的路徑。 |
| void [AddPolygon](./addpolygon/)(const [ArrayPtr](../../system/arrayptr/)\<[PointF](../../system.drawing/pointf/)\>\&) | 將指定的多邊形加入目前物件所代表的路徑。 |
| void [AddPolygon](./addpolygon/)(const [ArrayPtr](../../system/arrayptr/)\<[Point](../../system.drawing/point/)\>\&) | 將指定的多邊形加入目前物件所代表的路徑。 |
| void [AddRectangle](./addrectangle/)(const [Rectangle](../../system.drawing/rectangle/)\&) | 將指定的矩形加入目前物件所代表的路徑。 |
| void [AddRectangle](./addrectangle/)(const [RectangleF](../../system.drawing/rectanglef/)\&) | 將指定的矩形加入目前物件所代表的路徑。 |
| void [AddRectangles](./addrectangles/)(const [ArrayPtr](../../system/arrayptr/)\<[Rectangle](../../system.drawing/rectangle/)\>\&) | 將一系列矩形加入目前物件所代表的路徑。 |
| void [AddRectangles](./addrectangles/)(const [ArrayPtr](../../system/arrayptr/)\<[RectangleF](../../system.drawing/rectanglef/)\>\&) | 將一系列矩形加入目前物件所代表的路徑。 |
| void [AddString](./addstring/)(const [String](../../system/string/)\&, const [SharedPtr](../../system/sharedptr/)\<[FontFamily](../../system.drawing/fontfamily/)\>\&, int, **float**, [Point](../../system.drawing/point/), const [SharedPtr](../../system/sharedptr/)\<[StringFormat](../../system.drawing/stringformat/)\>\&) | 將文字字串加入目前物件所代表的路徑。 |
| void [AddString](./addstring/)(const [String](../../system/string/)\&, const [SharedPtr](../../system/sharedptr/)\<[FontFamily](../../system.drawing/fontfamily/)\>\&, int, **float**, [PointF](../../system.drawing/pointf/), const [SharedPtr](../../system/sharedptr/)\<[StringFormat](../../system.drawing/stringformat/)\>\&) | 將文字字串加入目前物件所代表的路徑。 |
| void [AddString](./addstring/)(const [String](../../system/string/)\&, const [SharedPtr](../../system/sharedptr/)\<[FontFamily](../../system.drawing/fontfamily/)\>\&, int, **float**, [Rectangle](../../system.drawing/rectangle/), const [SharedPtr](../../system/sharedptr/)\<[StringFormat](../../system.drawing/stringformat/)\>\&) | 將文字字串加入目前物件所代表的路徑。 |
| void [AddString](./addstring/)(const [String](../../system/string/)\&, const [SharedPtr](../../system/sharedptr/)\<[FontFamily](../../system.drawing/fontfamily/)\>\&, int, **float**, [RectangleF](../../system.drawing/rectanglef/), const [SharedPtr](../../system/sharedptr/)\<[StringFormat](../../system.drawing/stringformat/)\>\&) | 將文字字串加入目前物件所代表的路徑。 |
| virtual [SharedPtr](../../system/sharedptr/)\<[GraphicsPath](./)\> [Clone](./clone/)() | 建立目前物件的副本。 |
| void [CloseAllFigures](./closeallfigures/)() | 關閉所有開啟的圖形並開始新圖形。 |
| void [CloseFigure](./closefigure/)() | 關閉目前的圖形並開始新圖形。 |
| void [Dispose](./dispose/)() | 釋放目前物件取得的所有作業系統資源。 |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | 使用 C# [Object.Equals](../../system/object/equals/) 語意比較物件。 |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | 以 C# 方式比較參考型別物件。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | 以 C# 方式比較值型別物件。 |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | 模擬 C# 方式的浮點數比較，將兩個 NaN 視為相等，即使根據 IEC 60559:1989，NaN 不等於任何值，包括 NaN 本身。 |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | 模擬 C# 方式的浮點數比較，將兩個 NaN 視為相等，即使根據 IEC 60559:1989，NaN 不等於任何值，包括 NaN 本身。 |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | 僅供內部使用。 |
| void [Flatten](./flatten/)() | 將路徑中的每條曲線展平為相連的線段序列。使用平坦度值 0.25。 |
| void [Flatten](./flatten/)(const [MatrixPtr](../matrixptr/)\&) | 將路徑中的每條曲線展平為相連的線段序列。使用平坦度值 0.25。 |
| void [Flatten](./flatten/)(const [MatrixPtr](../matrixptr/)\&, **float**) | 將路徑中的每條曲線展平為相連的線段序列。 |
| [FillMode](../fillmode/) [get_FillMode](./get_fillmode/)() | 傳回目前物件的填充模式。 |
| [SharedPtr](../../system/sharedptr/)\<[PathData](../pathdata/)\> [get_PathData](./get_pathdata/)() | 傳回一個 [PathData](../pathdata/) 物件，內含組成目前物件所代表路徑的點及其類型。 |
| [ArrayPtr](../../system/arrayptr/)\<[PointF](../../system.drawing/pointf/)\> [get_PathPoints](./get_pathpoints/)() const | 傳回一個陣列，包含組成目前物件所代表路徑的點。 |
| [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\> [get_PathTypes](./get_pathtypes/)() const | 傳回一個陣列，包含指示組成目前物件所代表路徑之點類型的值。 |
| int [get_PointCount](./get_pointcount/)() const | 傳回目前物件所代表路徑中的點數。 |
| [RectangleF](../../system.drawing/rectanglef/) [GetBounds](./getbounds/)(const [MatrixPtr](../matrixptr/)\&, const [SharedPtr](../../system/sharedptr/)\<[Pen](../../system.drawing/pen/)\>\&) const | 傳回一個 [RectangleF](../../system.drawing/rectanglef/) 物件，代表在使用指定矩陣變換後，包圍目前物件所代表路徑的矩形。 |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | 取得與物件相關聯的參考計數資料結構。 |
| Detail::FigureType [GetFigureFlags](./getfigureflags/)() | 傳回一個值，為 Detail::FigureType 值的位元組合，表示目前物件所代表路徑中包含的圖形類型。 |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | 相當於 C# 的 [Object.GetHashCode()](../../system/object/gethashcode/) 方法，可用於自訂物件的雜湊。 |
| [PointF](../../system.drawing/pointf/) [GetLastPoint](./getlastpoint/)() const | 傳回一個 [PointF](../../system.drawing/pointf/) 物件，表示路徑中的最後一個點。 |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | 取得物件的實際類型。相當於 C# 的 [System.Object.GetType()](../../system/object/gettype/) 呼叫。 |
|  [GraphicsPath](./graphicspath/)([FillMode](../fillmode/)) | 以指定的填充模式建構 [GraphicsPath](./) 類別的新實例。 |
|  [GraphicsPath](./graphicspath/)(const [ArrayPtr](../../system/arrayptr/)\<[Point](../../system.drawing/point/)\>\&, const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&, [FillMode](../fillmode/)) | 建構一個代表指定路徑的 [GraphicsPath](./) 物件實例。 |
|  [GraphicsPath](./graphicspath/)(const [ArrayPtr](../../system/arrayptr/)\<[PointF](../../system.drawing/pointf/)\>\&, const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&, [FillMode](../fillmode/)) | 建構一個代表指定路徑的 [GraphicsPath](./) 物件實例。 |
|  [GraphicsPath](./graphicspath/)(const SkPath\&) |  |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | 檢查物件是否為目標類型的實例。相當於 C# 的 'is' 運算子。 |
| **bool** [IsOutlineVisible](./isoutlinevisible/)(const [PointF](../../system.drawing/pointf/)\&, const [SharedPtr](../../system/sharedptr/)\<[Pen](../../system.drawing/pen/)\>\&) | 指示在使用指定的 [Pen](../../system.drawing/pen/) 繪製此 [GraphicsPath](./) 時，指定的點是否位於其輪廓（下方）。未實作。 |
| **bool** [IsVisible](./isvisible/)(const [PointF](../../system.drawing/pointf/)\&) | 判斷指定的點是否位於目前物件所代表的路徑之內。 |
| **bool** [IsVisible](./isvisible/)(**float**, **float**) | 判斷指定的點是否位於目前物件所代表的路徑之內。 |
| void [Lock](../../system/object/lock/)() | 實作 C# lock() 陳述式的鎖定。可直接呼叫或使用 [LockContext](../../system/lockcontext/) 守衛物件。 |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | 相當於 C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) 方法，可用於克隆自訂型別。 |
|  [Object](../../system/object/object/)() | 建立物件。初始化所有內部資料結構。 |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | 複製建構子。實際上不會複製任何內容，只是初始化新物件並允許子類別的複製建構。 |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | 指派運算子。實際上不會複製任何內容，只是初始化新物件並允許子類別的複製建構。 |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | 以參考方式比較物件。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | 以參考方式比較物件。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | 以參考方式將值型別物件與 nullptr 比較。 |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | [Object::ReferenceEquals](../../system/object/referenceequals/) 的字串與 nullptr 專門化版本。 |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | [Object::ReferenceEquals](../../system/object/referenceequals/) 的字串專門化版本。 |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | 將共享參考計數減少指定的數值。 |
| void [Reset](./reset/)() | 透過移除所有點來清空路徑。 |
| void [Reverse](./reverse/)() | 反轉此 [GraphicsPath](./) 中 PathPoints 陣列的點順序。 |
| void [set_FillMode](./set_fillmode/)([FillMode](../fillmode/)) | 設定目前物件的填充模式。 |
| void [SetMarkers](./setmarkers/)() | 未實作。 |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | 將第 n 個模板參數設定為弱指標（而非共享）。允許在容器中將指標切換為弱模式。 |
| int [SharedCount](../../system/object/sharedcount/)() const | 取得共享參考計數的目前值。 |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | 遞增共享參考計數。不應直接呼叫，請使用智慧指標或 ThisProtector。 |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | 遞減並回傳共享參考計數。不應直接呼叫，請使用智慧指標或 ThisProtector。 |
| void [StartFigure](./startfigure/)() | 開始新圖形。 |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | 相當於 C# [Object.ToString()](../../system/object/tostring/) 方法，可將自訂物件轉換為字串。 |
| void [Transform](./transform/)(const [MatrixPtr](../matrixptr/)\&) | 透過套用指定的變換矩陣來變形目前物件所代表的路徑。 |
| void [Transform](./transform/)(const SkMatrix\&) |  |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | 實作 C# typeof([System.Object](../../system/object/)) 建構式。 |
| void [Unlock](../../system/object/unlock/)() | 實作 C# lock() 陳述式的解鎖。可直接呼叫或使用 [LockContext](../../system/lockcontext/) 守衛物件。 |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | 遞增弱參考計數。不應直接呼叫，請使用智慧指標或 ThisProtector。 |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | 遞減弱參考計數。不應直接呼叫，請使用智慧指標或 ThisProtector。 |
| void [Widen](./widen/)(const [SharedPtr](../../system/sharedptr/)\<[Pen](../../system.drawing/pen/)\>\&) | 將此路徑替換為原始路徑的輪廓。 |
|  [~GraphicsPath](./~graphicspath/)() | 解構子。 |
| virtual  [~Object](../../system/object/~object/)() | 銷毀物件。釋放所有內部資料結構。 |

## 另請參閱

* 類別 [Object](../../system/object/)
* 命名空間 [System::Drawing::Drawing2D](../)
* 函式庫 [Aspose.Slides](../../)