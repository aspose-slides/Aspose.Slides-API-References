---
title: ShapeStyle
second_title: Aspose.Slides C++ API 參考
description: 表示形狀樣式的參考。
type: docs
weight: 5149
url: /zh-hant/aspose.slides/shapestyle/
---
## ShapeStyle 類別

Represent shape's style reference.

```cpp
class ShapeStyle : public Aspose::Slides::DomObject<System::SharedPtr<Aspose::Slides::Shape>>,
                   public Aspose::Slides::IShapeStyle
```

## 方法

| Method | Description |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | 使用 C# [Object.Equals](../../system/object/equals/) 語意比較物件。 |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | 以 C# 風格比較參考型別物件。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | 以 C# 風格比較值型別物件。 |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | 模擬 C# 風格的浮點比較，兩個 NaN 被視為相等，即使根據 IEC 60559:1989，NaN 不等於任何值，包括 NaN。 |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | 模擬 C# 風格的浮點比較，兩個 NaN 被視為相等，即使根據 IEC 60559:1989，NaN 不等於任何值，包括 NaN。 |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | 僅供內部使用。 |
| [System::SharedPtr](../../system/sharedptr/)\<[IColorFormat](../icolorformat/)\> [get_EffectColor](./get_effectcolor/)() override | 傳回形狀的效果顏色。唯讀 [IColorFormat](../icolorformat/)。 |
| **uint32_t** [get_EffectStyleIndex](./get_effectstyleindex/)() override | 傳回形狀在樣式矩陣中的效果欄索引。讀取 **uint32_t**。 |
| [System::SharedPtr](../../system/sharedptr/)\<[IColorFormat](../icolorformat/)\> [get_FillColor](./get_fillcolor/)() override | 傳回形狀的填充顏色。唯讀 [IColorFormat](../icolorformat/)。 |
| **int16_t** [get_FillStyleIndex](./get_fillstyleindex/)() override | 傳回形狀在樣式矩陣中的填充欄索引。0 表示無填充，正值為主題填充樣式的索引，負值為主題背景樣式的索引。讀取 **int16_t**。 |
| [Aspose::Slides::FontCollectionIndex](../fontcollectionindex/) [get_FontCollectionIndex](./get_fontcollectionindex/)() override | 傳回形狀在字型集合中的字型索引。讀取 [Slides::FontCollectionIndex](../fontcollectionindex/)。 |
| [System::SharedPtr](../../system/sharedptr/)\<[IColorFormat](../icolorformat/)\> [get_FontColor](./get_fontcolor/)() override | 傳回形狀的字型顏色。唯讀 [IColorFormat](../icolorformat/)。 |
| [System::SharedPtr](../../system/sharedptr/)\<[IColorFormat](../icolorformat/)\> [get_LineColor](./get_linecolor/)() override | 傳回形狀的輪廓顏色。唯讀 [IColorFormat](../icolorformat/)。 |
| **uint16_t** [get_LineStyleIndex](./get_linestyleindex/)() override | 傳回線條在樣式矩陣中的欄索引。讀取 **uint16_t**。 |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | 取得與物件相關聯的參考計數資料結構。 |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | 相當於 C# [Object.GetHashCode()](../../system/object/gethashcode/) 方法。啟用自訂物件的雜湊。 |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | 取得物件的實際類型。相當於 C# [System.Object.GetType()](../../system/object/gettype/) 呼叫。 |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | 檢查物件是否為 targetType 所描述的類型之實例。相當於 C# 'is' 運算子。 |
| void [Lock](../../system/object/lock/)() | 實作 C# lock() 陳述式的鎖定。直接呼叫或使用 [LockContext](../../system/lockcontext/) 哨兵物件。 |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | 相當於 C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) 方法。啟用自訂類型的複製。 |
|  [Object](../../system/object/object/)() | 建立物件。初始化所有內部資料結構。 |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | 拷貝建構函式。實際上不會拷貝任何內容，只是初始化新物件並允許子類別的拷貝建構。 |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | 指派運算子。實際上不會拷貝任何內容，只是初始化新物件並允許子類別的拷貝建構。 |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | 以參考方式比較物件。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | 以參考方式比較物件。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | 以參考方式比較值型別物件與 nullptr。 |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | [Object::ReferenceEquals](../../system/object/referenceequals/) 的特化，用於字串與 nullptr 的情況。 |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | [Object::ReferenceEquals](../../system/object/referenceequals/) 的特化，用於字串的情況。 |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | 將共享參考計數減少指定的值。 |
| void [set_EffectStyleIndex](./set_effectstyleindex/)(**uint32_t**) override | 設定形狀在樣式矩陣中的效果欄索引。寫入 **uint32_t**。 |
| void [set_FillStyleIndex](./set_fillstyleindex/)(**int16_t**) override | 設定形狀在樣式矩陣中的填充欄索引。0 表示無填充，正值為主題填充樣式的索引，負值為主題背景樣式的索引。寫入 **int16_t**。 |
| void [set_FontCollectionIndex](./set_fontcollectionindex/)([Aspose::Slides::FontCollectionIndex](../fontcollectionindex/)) override | 設定形狀在字型集合中的字型索引。寫入 [Slides::FontCollectionIndex](../fontcollectionindex/)。 |
| void [set_LineStyleIndex](./set_linestyleindex/)(**uint16_t**) override | 設定線條在樣式矩陣中的欄索引。寫入 **uint16_t**。 |
| void [SetTemplateWeakPtr](./settemplateweakptr/)(**uint32_t**) override | 將第 n 個模板參數設為弱指標（而非共享）。允許在容器中將指標切換為弱模式。 |
| int [SharedCount](../../system/object/sharedcount/)() const | 取得共享參考計數的目前值。 |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | 增加共享參考計數。不應直接呼叫；請改用智慧指標或 ThisProtector。 |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | 遞減並返回共享參考計數。不應直接呼叫；請改用智慧指標或 ThisProtector。 |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | 相當於 C# [Object.ToString()](../../system/object/tostring/) 方法。啟用將自訂物件轉換為字串。 |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | 實作 C# typeof([System.Object](../../system/object/)) 建構式。 |
| void [Unlock](../../system/object/unlock/)() | 實作 C# lock() 陳述式的解鎖。直接呼叫或使用 [LockContext](../../system/lockcontext/) 哨兵物件。 |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | 增加弱參考計數。不應直接呼叫；請改用智慧指標或 ThisProtector。 |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | 遞減弱參考計數。不應直接呼叫；請改用智慧指標或 ThisProtector。 |
| virtual  [~Object](../../system/object/~object/)() | 銷毀物件。釋放所有內部資料結構。 |

## 另見

* 類別 [DomObject](../domobject/)
* 類別 [IShapeStyle](../ishapestyle/)
* 命名空間 [Aspose::Slides](../)
* 函式庫 [Aspose.Slides](../../)