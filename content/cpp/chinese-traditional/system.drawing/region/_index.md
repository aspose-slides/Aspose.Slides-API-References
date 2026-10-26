---
title: Region
second_title: "Aspose.Slides for C++ API 參考文件"
description: "代表圖形形狀的內部。此類別的物件應僅使用 System::MakeObject() 函式分配。切勿在堆疊上或使用 operator new 建立此類型的實例，因為會導致執行時錯誤和/或斷言失敗。始終將此類別包裝為 System::SmartPtr 指標，並使用該指標將其作為參數傳遞給函式。"
type: docs
weight: 261
url: /zh-hant/system.drawing/region/
---
## Region 類別

Represents the interior of a graphic shape. Objects of this class should only be allocated using [System::MakeObject()](../../system/makeobject/) function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into [System::SmartPtr](../../system/smartptr/) pointer and use this pointer to pass it to functions as argument.

```cpp
class Region : public System::Object
```

## 方法

| 方法 | 描述 |
| --- | --- |
| [SharedPtr](../../system/sharedptr/)\<[Region](./)\> [Clone](./clone/)() const | 返回目前物件的副本。 |
| void [Complement](./complement/)(const [RectangleF](../rectanglef/)\&) | 將目前物件所代表的區域取代為由指定矩形定義、且不與此區域相交的區域部分。 |
| void [Complement](./complement/)(const [Rectangle](../rectangle/)\&) | 將目前物件所代表的區域取代為由指定矩形定義、且不與此區域相交的區域部分。 |
| void [Complement](./complement/)(const [SharedPtr](../../system/sharedptr/)\<[Drawing2D::GraphicsPath](../../system.drawing.drawing2d/graphicspath/)\>\&) | 將目前物件所代表的區域取代為由指定路徑定義、且不與此區域相交的區域部分。 |
| void [Complement](./complement/)(const [SharedPtr](../../system/sharedptr/)\<[Region](./)\>\&) | 將目前物件所代表的區域取代為指定區域中不與此區域相交的部分。 |
| void [Dispose](./dispose/)() | 釋放目前物件取得的所有作業系統資源。 |
| **bool** [Equals](./equals/)(const [SharedPtr](../../system/sharedptr/)\<[Region](./)\>\&, const [SharedPtr](../../system/sharedptr/)\<[Graphics](../graphics/)\>\&) | 判斷指定的區域是否與目前物件在指定繪圖表面上所代表的區域相同。 |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | 使用 C# [Object.Equals](../../system/object/equals/) 語意比較物件。 |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | 以 C# 風格比較參考型別物件。 |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | 模擬 C# 風格的浮點比較，將兩個 NaN 視為相等，即使根據 IEC 60559:1989 NaN 不等於任何值，包括 NaN 本身。 |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | 模擬 C# 風格的浮點比較，將兩個 NaN 視為相等，即使根據 IEC 60559:1989 NaN 不等於任何值，包括 NaN 本身。 |
| void [Exclude](./exclude/)(const [RectangleF](../rectanglef/)\&) | 將目前物件所代表的區域取代為從中排除由指定矩形定義的區域後的結果。 |
| void [Exclude](./exclude/)(const [Rectangle](../rectangle/)\&) | 將目前物件所代表的區域取代為從中排除由指定矩形定義的區域後的結果。 |
| void [Exclude](./exclude/)(const [SharedPtr](../../system/sharedptr/)\<[Drawing2D::GraphicsPath](../../system.drawing.drawing2d/graphicspath/)\>\&) | 將目前物件所代表的區域取代為從中排除由指定路徑定義的區域後的結果。 |
| void [Exclude](./exclude/)(const [SharedPtr](../../system/sharedptr/)\<[Region](./)\>\&) | 將目前物件所代表的區域取代為從中排除指定區域後的結果。 |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | 僅供內部使用。 |
| [RectangleF](../rectanglef/) [GetBounds](./getbounds/)(const [SharedPtr](../../system/sharedptr/)\<[Graphics](../graphics/)\>\&) const | 取得一個 [RectangleF](../rectanglef/) 結構，該結構表示在 [Graphics](../graphics/) 物件的繪圖表面上界定此 [Region](./) 的矩形。 |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | 取得與物件關聯的參考計數資料結構。 |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | 相當於 C# [Object.GetHashCode()](../../system/object/gethashcode/) 方法。啟用自訂物件的雜湊。 |
| [SharedPtr](../../system/sharedptr/)\<[Drawing2D::RegionData](../../system.drawing.drawing2d/regiondata/)\> [GetRegionData](./getregiondata/)() const | 傳回一個 RegionData 物件，內含定義目前物件所代表區域的資料。 |
| [ArrayPtr](../../system/arrayptr/)\<[RectangleF](../rectanglef/)\> [GetRegionScans](./getregionscans/)(const [SharedPtr](../../system/sharedptr/)\<[Drawing2D::Matrix](../../system.drawing.drawing2d/matrix/)\>\&) const | 傳回一個 [RectangleF](../rectanglef/) 結構陣列，該陣列在套用指定矩陣變換後近似此 [Region](./)。 |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | 取得物件的實際型別。相當於 C# [System.Object.GetType()](../../system/object/gettype/) 呼叫。 |
| void [Intersect](./intersect/)(const [RectangleF](../rectanglef/)\&) | 將目前物件所代表的區域取代為此區域與由指定矩形定義之區域的交集結果。 |
| void [Intersect](./intersect/)(const [Rectangle](../rectangle/)\&) | 將目前物件所代表的區域取代為此區域與由指定矩形定義之區域的交集結果。 |
| void [Intersect](./intersect/)(const [SharedPtr](../../system/sharedptr/)\<[Drawing2D::GraphicsPath](../../system.drawing.drawing2d/graphicspath/)\>\&) | 將目前物件所代表的區域取代為此區域與由指定路徑定義之區域的交集結果。 |
| void [Intersect](./intersect/)(const [SharedPtr](../../system/sharedptr/)\<[Region](./)\>\&) | 將目前物件所代表的區域取代為此區域與指定區域的交集結果。 |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | 檢查物件是否為 targetType 所描述型別的實例。相當於 C# 'is' 運算子。 |
| **bool** [IsEmpty](./isempty/)(const [SharedPtr](../../system/sharedptr/)\<[Graphics](../graphics/)\>\&) const | 判斷目前物件所代表的區域在指定繪圖表面上是否具有空的內部。 |
| **bool** [IsInfinite](./isinfinite/)(const [SharedPtr](../../system/sharedptr/)\<[Graphics](../graphics/)\>\&) const | 判斷目前物件所代表的區域在指定繪圖表面上是否具有無限的內部。 |
| **bool** [IsVisible](./isvisible/)(const [Point](../point/)\&) const | 判斷指定點是否包含於目前物件所代表的區域內。 |
| **bool** [IsVisible](./isvisible/)(const [PointF](../pointf/)\&) const | 判斷指定點是否包含於目前物件所代表的區域內。 |
| **bool** [IsVisible](./isvisible/)(const [Rectangle](../rectangle/)\&) | 判斷指定矩形的任何部分是否包含於目前物件所代表的區域內。 |
| **bool** [IsVisible](./isvisible/)(const [RectangleF](../rectanglef/)\&) | 判斷指定矩形的任何部分是否包含於目前物件所代表的區域內。 |
| **bool** [IsVisible](./isvisible/)(const [Point](../point/)\&, const [SharedPtr](../../system/sharedptr/)\<[Graphics](../graphics/)\>\&) const | 使用指定的圖形，判斷指定點是否包含於目前物件所代表的區域內。 |
| **bool** [IsVisible](./isvisible/)(const [PointF](../pointf/)\&, const [SharedPtr](../../system/sharedptr/)\<[Graphics](../graphics/)\>\&) const | 使用指定的圖形，判斷指定點是否包含於目前物件所代表的區域內。 |
| **bool** [IsVisible](./isvisible/)(const [Rectangle](../rectangle/)\&, const [SharedPtr](../../system/sharedptr/)\<[Graphics](../graphics/)\>\&) | 使用指定的圖形，判斷指定矩形的任何部分是否包含於目前物件所代表的區域內。 |
| **bool** [IsVisible](./isvisible/)(const [RectangleF](../rectanglef/)\&, const [SharedPtr](../../system/sharedptr/)\<[Graphics](../graphics/)\>\&) | 使用指定的圖形，判斷指定矩形的任何部分是否包含於目前物件所代表的區域內。 |
| **bool** [IsVisible](./isvisible/)(**float**, **float**) const | 判斷指定點是否包含於目前物件所代表的區域內。 |
| **bool** [IsVisible](./isvisible/)(**float**, **float**, const [SharedPtr](../../system/sharedptr/)\<[Graphics](../graphics/)\>\&) const | 使用指定的圖形，判斷指定點是否包含於目前物件所代表的區域內。 |
| void [Lock](../../system/object/lock/)() | 實作 C# lock() 陳述式的鎖定。直接呼叫或使用 [LockContext](../../system/lockcontext/) 哨兵物件。 |
| void [MakeEmpty](./makeempty/)() | 將目前物件初始化為空的內部。 |
| void [MakeInfinite](./makeinfinite/)() | 將此區域物件初始化為無限的內部。 |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | 相當於 C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) 方法。啟用自訂型別的克隆。 |
|  [Object](../../system/object/object/)() | 建立物件。初始化所有內部資料結構。 |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | 複製建構函式。實際上不會複製任何內容，只是初始化新物件並允許子類別的複製建構。 |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | 指派運算子。實際上不會複製任何內容，只是初始化新物件並允許子類別的複製建構。 |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | 以參考方式比較物件。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | 以參考方式比較物件。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | 以參考方式比較值型別物件與 nullptr。 |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | [Object::ReferenceEquals](../../system/object/referenceequals/) 的特化，用於 string 與 nullptr 情況。 |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | [Object::ReferenceEquals](../../system/object/referenceequals/) 的特化，用於字串情況。 |
|  [Region](./region/)() | 建構 [Region](./) 類別的新實例。 |
|  [Region](./region/)(const [RectangleF](../rectanglef/)\&) | 建構 [Region](./) 類別的新實例，該類別代表由指定矩形定義的區域。 |
|  [Region](./region/)(const [Rectangle](../rectangle/)\&) | 建構 [Region](./) 類別的新實例，該類別代表由指定矩形定義的區域。 |
|  [Region](./region/)(const [SharedPtr](../../system/sharedptr/)\<[Drawing2D::GraphicsPath](../../system.drawing.drawing2d/graphicspath/)\>\&) | 建構 [Region](./) 類別的新實例，該類別代表由指定路徑定義的區域。 |
|  [Region](./region/)(const SkPath\&) |  |
|  [Region](./region/)(const [SharedPtr](../../system/sharedptr/)\<[Drawing2D::RegionData](../../system.drawing.drawing2d/regiondata/)\>\&) | 建構 [Region](./) 類別的新實例，該類別代表由指定 RegionData 物件定義的區域。 |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | 將共享參考計數減少指定的值。 |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | 將第 n 個模板參數設定為弱指標（而非共享）。允許在容器中將指標切換為弱模式。 |
| int [SharedCount](../../system/object/sharedcount/)() const | 取得共享參考計數器的目前值。 |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | 遞增共享參考計數。不應直接呼叫；請改用智慧指標或 ThisProtector。 |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | 遞減並回傳共享參考計數。不應直接呼叫；請改用智慧指標或 ThisProtector。 |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | 相當於 C# [Object.ToString()](../../system/object/tostring/) 方法。啟用將自訂物件轉換為字串。 |
| void [Transform](./transform/)(const [SharedPtr](../../system/sharedptr/)\<[Drawing2D::Matrix](../../system.drawing.drawing2d/matrix/)\>\&) | 以指定的矩陣變換此區域。 |
| void [Transform](./transform/)(const SkMatrix\&) | 以指定的矩陣變換此區域。 |
| void [Translate](./translate/)(int, int) | 將區域的座標依指定的量移動。 |
| void [Translate](./translate/)(**float**, **float**) | 將區域的座標依指定的量移動。 |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | 實作 C# typeof([System.Object](../../system/object/)) 結構。 |
| void [Union](./union/)(const [RectangleF](../rectanglef/)\&) | 將目前物件所代表的區域取代為此區域與由指定矩形定義之區域的聯集結果。 |
| void [Union](./union/)(const [Rectangle](../rectangle/)\&) | 將目前物件所代表的區域取代為此區域與由指定矩形定義之區域的聯集結果。 |
| void [Union](./union/)(const [SharedPtr](../../system/sharedptr/)\<[Drawing2D::GraphicsPath](../../system.drawing.drawing2d/graphicspath/)\>\&) | 將目前物件所代表的區域取代為此區域與由指定路徑定義之區域的聯集結果。 |
| void [Union](./union/)(const [SharedPtr](../../system/sharedptr/)\<[Region](./)\>\&) | 將目前物件所代表的區域取代為此區域與指定區域的聯集結果。 |
| void [Unlock](../../system/object/unlock/)() | 實作 C# lock() 陳述式的解鎖。直接呼叫或使用 [LockContext](../../system/lockcontext/) 哨兵物件。 |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | 遞增弱參考計數。不應直接呼叫；請改用智慧指標或 ThisProtector。 |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | 遞減弱參考計數。不應直接呼叫；請改用智慧指標或 ThisProtector。 |
| void [Xor](./xor/)(const [RectangleF](../rectanglef/)\&) | 將目前物件所代表的區域取代為此區域與由指定矩形定義之區域中不相交的部分。 |
| void [Xor](./xor/)(const [Rectangle](../rectangle/)\&) | 將目前物件所代表的區域取代為此區域與由指定矩形定義之區域中不相交的部分。 |
| void [Xor](./xor/)(const [SharedPtr](../../system/sharedptr/)\<[Drawing2D::GraphicsPath](../../system.drawing.drawing2d/graphicspath/)\>\&) | 將目前物件所代表的區域取代為此區域與由指定路徑定義之區域中不相交的部分。 |
| void [Xor](./xor/)(const [SharedPtr](../../system/sharedptr/)\<[Region](./)\>\&) | 將目前物件所代表的區域取代為此區域與指定區域中不相交的部分。 |
| virtual  [~Object](../../system/object/~object/)() | 銷毀物件。釋放所有內部資料結構。 |
| virtual  [~Region](./~region/)() | 解構子。 |

## 另請參閱

* 類別 [Object](../../system/object/)
* 命名空間 [System::Drawing](../)
* 函式庫 [Aspose.Slides](../../)