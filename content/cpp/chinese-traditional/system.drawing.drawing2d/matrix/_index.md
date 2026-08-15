---
title: Matrix
second_title: Aspose.Slides for C++ API 參考
description: "表示一個定義變換操作的 3x3 矩陣。此類別的物件應僅使用 System::MakeObject() 函式分配。絕不要在堆疊上或使用 operator new 建立此類型的實例，因為這會導致執行時錯誤和/或斷言失敗。始終將此類別包裝成 System::SmartPtr 指標，並使用該指標作為參數傳遞給函式。"
type: docs
weight: 118
url: /zh-hant/system.drawing.drawing2d/matrix/
---
## Matrix 類別


表示一個定義變換操作的 3x3 矩陣。此類別的物件應僅使用 [System::MakeObject()](../../system/makeobject/) 函式分配。絕不要在堆疊上或使用 operator new 建立此類型的實例，因為這會導致執行時錯誤和/或斷言失敗。始終將此類別包裝成 [System::SmartPtr](../../system/smartptr/) 指標，並使用該指標作為參數傳遞給函式。

```cpp
class Matrix : public System::Object
```

## 方法

| 方法 | 說明 |
| --- | --- |
| [SharedPtr](../../system/sharedptr/)\<[Matrix](./)\> [Clone](./clone/)() const | 建立目前物件的副本。 |
| void [Dispose](./dispose/)() | 釋放目前物件取得的所有作業系統資源。 |
| **bool** [Equals](./equals/)([ptr](../../system/object/ptr/)) override | 測試指定的物件是否為一個 [Matrix](./) 且與此物件相同。 |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | 以 C# 風格比較參考型別物件。 |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | 模擬 C# 風格的浮點比較，將兩個 NaN 視為相等，即使根據 IEC 60559:1989，NaN 與任何值（包括 NaN）皆不相等。 |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | 模擬 C# 風格的浮點比較，將兩個 NaN 視為相等，即使根據 IEC 60559:1989，NaN 與任何值（包括 NaN）皆不相等。 |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | 僅供內部使用。 |
| [System::ArrayPtr](../../system/arrayptr/)\<**float**\> [get_Elements](./get_elements/)() const | 回傳一個陣列，包含矩陣的元素，順序為：m11、m12、m21、m22、dx、dy。 |
| **bool** [get_IsIdentity](./get_isidentity/)() const | 判斷目前物件所代表的矩陣是否為單位矩陣。 |
| **bool** [get_IsInvertible](./get_isinvertible/)() const | 判斷目前物件所代表的矩陣是否可逆。 |
| **float** [get_OffsetX](./get_offsetx/)() const | 回傳目前物件所代表的矩陣的 X 平移值。 |
| **float** [get_OffsetY](./get_offsety/)() const | 回傳目前物件所代表的矩陣的 Y 平移值。 |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | 取得與物件相關的參考計數資料結構。 |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | 相當於 C# [Object.GetHashCode()](../../system/object/gethashcode/) 方法。啟用自訂物件的雜湊。 |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | 取得物件的實際類型。相當於 C# [System.Object.GetType()](../../system/object/gettype/) 呼叫。 |
| void [Invert](./invert/)() | 反轉目前物件所代表的矩陣。 |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | 檢查物件是否為 targetType 所描述類型的實例。相當於 C# 的 'is' 運算子。 |
| void [Lock](../../system/object/lock/)() | 實作 C# lock() 陳述式的鎖定。直接呼叫或使用 [LockContext](../../system/lockcontext/) 監視物件。 |
|  [Matrix](./matrix/)() | 建構一個代表單位矩陣的 [Matrix](./) 類別新實例。 |
|  [Matrix](./matrix/)(**float**, **float**, **float**, **float**, **float**, **float**) | 建構一個 [Matrix](./) 類別的新實例，並使用指定的值進行初始化。 |
|  [Matrix](./matrix/)(const [Rectangle](../../system.drawing/rectangle/)\&, const [ArrayPtr](../../system/arrayptr/)\<[Point](../../system.drawing/point/)\>\&) | 根據指定的矩形和點陣列定義的幾何變換，建構 [Matrix](./) 類別的新實例。 |
|  [Matrix](./matrix/)(const [RectangleF](../../system.drawing/rectanglef/)\&, const [ArrayPtr](../../system/arrayptr/)\<[PointF](../../system.drawing/pointf/)\>\&) | 根據指定的矩形和點陣列定義的幾何變換，建構 [Matrix](./) 類別的新實例。 |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | 相當於 C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) 方法。啟用自訂類型的複製。 |
| void [Multiply](./multiply/)(const [SharedPtr](../../system/sharedptr/)\<[Matrix](./)\>\&) | 將目前物件所代表的矩陣與指定的矩陣相乘。 |
| void [Multiply](./multiply/)(const [SharedPtr](../../system/sharedptr/)\<[Matrix](./)\>\&, [MatrixOrder](../matrixorder/)) | 將目前物件所代表的矩陣與指定的矩陣相乘。 |
|  [Object](../../system/object/object/)() | 建立物件。初始化所有內部資料結構。 |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | 拷貝建構子。實際上不會拷貝任何內容，只是初始化新物件，並允許子類別的拷貝建構。 |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | 賦值運算子。實際上不會拷貝任何內容，只是初始化新物件，並允許子類別的拷貝建構。 |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | 以參考方式比較物件。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | 以參考方式比較物件。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | 將值型別物件與 nullptr 以參考方式比較。 |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | [Object::ReferenceEquals](../../system/object/referenceequals/) 的特殊化，用於字串與 nullptr 的情況。 |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | [Object::ReferenceEquals](../../system/object/referenceequals/) 的特殊化，用於字串的情況。 |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | 將共享參考計數減少指定的值。 |
| void [Reset](./reset/)() | 重設目前物件所代表的矩陣，使其變為單位矩陣。 |
| void [Rotate](./rotate/)(**float**) | 將目前物件所代表的矩陣以指定角度順時針旋轉。 |
| void [Rotate](./rotate/)(**float**, [MatrixOrder](../matrixorder/)) | 將目前物件所代表的矩陣以指定角度繞原點順時針旋轉。 |
| void [RotateAt](./rotateat/)(**float**, const [PointF](../../system.drawing/pointf/)\&) | 將目前物件所代表的矩陣以指定角度繞指定點順時針旋轉。 |
| void [RotateAt](./rotateat/)(**float**, const [PointF](../../system.drawing/pointf/)\&, [MatrixOrder](../matrixorder/)) | 將目前物件所代表的矩陣以指定角度繞指定點順時針旋轉。 |
| void [Scale](./scale/)(**float**, **float**) | 將指定的縮放向量套用到目前物件所代表的矩陣。 |
| void [Scale](./scale/)(**float**, **float**, [MatrixOrder](../matrixorder/)) | 將指定的縮放向量套用到目前物件所代表的矩陣。 |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | 設定第 n 個模板參數為弱指標（而非共享指標）。允許在容器中將指標切換為弱模式。 |
| int [SharedCount](../../system/object/sharedcount/)() const | 取得共享參考計數的目前值。 |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | 遞增共享參考計數。不應直接呼叫；請改用智慧指標或 ThisProtector。 |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | 遞減並回傳共享參考計數。不應直接呼叫；請改用智慧指標或 ThisProtector。 |
| void [Shear](./shear/)(**float**, **float**) | 將指定的剪切向量套用到目前物件所代表的矩陣。 |
| void [Shear](./shear/)(**float**, **float**, [MatrixOrder](../matrixorder/)) | 將指定的剪切向量套用到目前物件所代表的矩陣。 |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | 相當於 C# [Object.ToString()](../../system/object/tostring/) 方法。啟用將自訂物件轉換為字串。 |
| void [TransformPoints](./transformpoints/)(const [ArrayPtr](../../system/arrayptr/)\<[Point](../../system.drawing/point/)\>\&) | 將目前物件所代表的矩陣所定義的幾何變換套用到指定的點。 |
| void [TransformPoints](./transformpoints/)(const System::Details::ArrayView\<[Point](../../system.drawing/point/)\>\&) | 將目前物件所代表的矩陣所定義的幾何變換套用到指定的點。 |
| void [TransformPoints](./transformpoints/)(const [ArrayPtr](../../system/arrayptr/)\<[PointF](../../system.drawing/pointf/)\>\&) | 將目前物件所代表的矩陣所定義的幾何變換套用到指定的點。 |
| void [TransformPoints](./transformpoints/)(const System::Details::ArrayView\<[PointF](../../system.drawing/pointf/)\>\&) | 將目前物件所代表的矩陣所定義的幾何變換套用到指定的點。 |
| void [TransformVectors](./transformvectors/)(const [ArrayPtr](../../system/arrayptr/)\<[Point](../../system.drawing/point/)\>\&) | 僅將目前物件所代表的矩陣的縮放與旋轉元件套用到指定的點。 |
| void [TransformVectors](./transformvectors/)(const System::Details::ArrayView\<[Point](../../system.drawing/point/)\>\&) | 僅將目前物件所代表的矩陣的縮放與旋轉元件套用到指定的點。 |
| void [TransformVectors](./transformvectors/)(const [ArrayPtr](../../system/arrayptr/)\<[PointF](../../system.drawing/pointf/)\>\&) | 僅將目前物件所代表的矩陣的縮放與旋轉元件套用到指定的點。 |
| void [TransformVectors](./transformvectors/)(const System::Details::ArrayView\<[PointF](../../system.drawing/pointf/)\>\&) | 僅將目前物件所代表的矩陣的縮放與旋轉元件套用到指定的點。 |
| void [Translate](./translate/)(**float**, **float**) | 將指定的平移向量套用到目前物件所代表的矩陣。 |
| void [Translate](./translate/)(**float**, **float**, [MatrixOrder](../matrixorder/)) | 將指定的平移向量套用到目前物件所代表的矩陣。 |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | 實作 C# typeof([System.Object](../../system/object/)) 語法。 |
| void [Unlock](../../system/object/unlock/)() | 實作 C# lock() 陳述式的解鎖。直接呼叫或使用 [LockContext](../../system/lockcontext/) 監視物件。 |
| void [VectorTransformPoints](./vectortransformpoints/)(const [ArrayPtr](../../system/arrayptr/)\<[Point](../../system.drawing/point/)\>\&) | 將陣列中的每個向量以目前物件所代表的矩陣相乘。 |
| void [VectorTransformPoints](./vectortransformpoints/)(const System::Details::ArrayView\<[Point](../../system.drawing/point/)\>\&) | 將陣列中的每個向量以目前物件所代表的矩陣相乘。 |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | 遞增弱參考計數。不應直接呼叫；請改用智慧指標或 ThisProtector。 |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | 遞減弱參考計數。不應直接呼叫；請改用智慧指標或 ThisProtector。 |
| virtual  [~Matrix](./~matrix/)() | 解構子。 |
| virtual  [~Object](../../system/object/~object/)() | 銷毀物件。釋放所有內部資料結構。 |

## 參見

* 類別 [Object](../../system/object/)
* 命名空間 [System::Drawing::Drawing2D](../)
* 函式庫 [Aspose.Slides](../../)