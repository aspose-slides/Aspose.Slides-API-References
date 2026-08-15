---
title: Vector2d64d
second_title: Aspose.Slides for C++ API 參考文件
description: 具有 double 成分的 2D 向量
type: docs
weight: 66
url: /zh-hant/aspose.slides.drawing/vector2d64d/
---
## Vector2d64d 類別

2D 向量，具有 **double** 成分

```cpp
class Vector2d64d : public System::Object,
                    public System::Details::BoxableObjectBase
```

## 方法

| 方法 | 說明 |
| --- | --- |
| **double** [Dot](./dot/)([Vector2d64d](./)) | 計算兩個向量的標量積。 |
| **bool** [Equals](./equals/)(const [Vector2d64d](./)\&) |  |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | 使用 C# [Object.Equals](../../system/object/equals/) 語意比較物件。 |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | 以 C# 風格比較參考型別物件。 |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | 模擬 C# 風格的浮點比較，兩個 NaN 被視為相等，即使根據 IEC 60559:1989，NaN 與任何值（包括 NaN）都不相等。 |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | 模擬 C# 風格的浮點比較，兩個 NaN 被視為相等，即使根據 IEC 60559:1989，NaN 與任何值（包括 NaN）都不相等。 |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | 僅供內部使用。 |
| **double** [get_Length](./get_length/)() | 取得向量的標量長度。唯讀 **double**。 |
| [Vector2d64d](./) [get_Norm](./get_norm/)() | 取得法向量。唯讀 [Vector2d64d](./)。 |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | 取得與物件相關聯的參考計數資料結構。 |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | 相當於 C# [Object.GetHashCode()](../../system/object/gethashcode/) 方法。啟用自訂物件的雜湊。 |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | 取得物件的實際類型。相當於 C# [System.Object.GetType()](../../system/object/gettype/) 呼叫。 |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | 檢查物件是否為 targetType 所描述類型的實例。相當於 C# 'is' 運算子。 |
| **bool** [IsNull](./isnull/)() const |  |
| void [Lock](../../system/object/lock/)() | 實作 C# lock() 陳述式的鎖定。直接呼叫或使用 [LockContext](../../system/lockcontext/) 守護物件。 |
| static [Vector2d64d](./) [Max](./max/)([Vector2d64d](./), [Vector2d64d](./)) |  |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | 相當於 C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) 方法。啟用自訂類型的克隆。 |
| static [Vector2d64d](./) [Min](./min/)([Vector2d64d](./), [Vector2d64d](./)) |  |
| [Vector2d64d](./) [Normalize](./normalize/)() | 建立長度為 1 的共線向量。此向量不應為零長度。 |
| [Object](../../system/object/object/)() | 建立物件。初始化所有內部資料結構。 |
| [Object](../../system/object/object/)([Object](../../system/object/) const\&) | 複製建構函式。實際上不會複製任何東西，只是初始化新物件，並允許子類別的複製建構。 |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | 指派運算子。實際上不會複製任何東西，只是初始化新物件，並允許子類別的複製建構。 |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | 以參考方式比較物件。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | 以參考方式比較物件。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | 以參考方式比較值型別物件與 nullptr。 |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | [Object::ReferenceEquals](../../system/object/referenceequals/) 的特化，用於字串與 nullptr 情況。 |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | [Object::ReferenceEquals](../../system/object/referenceequals/) 的特化，用於字串情況。 |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | 將共同參考計數減少指定的值。 |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | 將第 n 個模板參數設為弱指標（而非共享）。允許在容器中將指標切換為弱模式。 |
| int [SharedCount](../../system/object/sharedcount/)() const | 取得共同參考計數的目前值。 |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | 遞增共同參考計數。不應直接呼叫；請改用智慧指標或 ThisProtector。 |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | 遞減並回傳共同參考計數。不應直接呼叫；請改用智慧指標或 ThisProtector。 |
| void [SwapXY](./swapxy/)() | 交換 X 與 Y。 |
| [System::String](../../system/string/) [ToString](./tostring/)() const override | 相當於 C# [Object.ToString()](../../system/object/tostring/) 方法。啟用自訂物件轉換為字串。 |
| [Vector2d32f](../vector2d32f/) [ToVector2d32f](./tovector2d32f/)() | 至 [Vector2d32f](../vector2d32f/) |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | 實作 C# typeof([System.Object](../../system/object/)) 建構。 |
| void [Unlock](../../system/object/unlock/)() | 實作 C# lock() 陳述式的解鎖。直接呼叫或使用 [LockContext](../../system/lockcontext/) 守護物件。 |
| [Vector2d64d](./vector2d64d/)(**double**, **double**) | 建構函式 |
| [Vector2d64d](./vector2d64d/)([System::Drawing::PointF](../../system.drawing/pointf/)) | 建構函式 |
| [Vector2d64d](./vector2d64d/)() |  |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | 遞增弱參考計數。不應直接呼叫；請改用智慧指標或 ThisProtector。 |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | 遞減弱參考計數。不應直接呼叫；請改用智慧指標或 ThisProtector。 |
| virtual  [~Object](../../system/object/~object/)() | 銷毀物件。釋放所有內部資料結構。 |

## 欄位

| 欄位 | 說明 |
| --- | --- |
| static [One](./one/) |  |
| static [Zero](./zero/) |  |

## 另請參閱

* 類別 [Object](../../system/object/)
* 命名空間 [Aspose::Slides::Drawing](../)
* 函式庫 [Aspose.Slides](../../)