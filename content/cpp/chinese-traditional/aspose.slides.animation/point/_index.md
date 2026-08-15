---
title: Point
second_title: Aspose.Slides for C++ API 參考
description: 表示動畫點。
type: docs
weight: 495
url: /zh-hant/aspose.slides.animation/point/
---
## Point 類別

表示動畫點。

```cpp
class Point : public Aspose::Slides::Animation::IPoint
```

## 方法

| 方法 | 說明 |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | 使用 C# [Object.Equals](../../system/object/equals/) 語意比較物件。 |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | 使用 C# 風格比較參考型別物件。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | 使用 C# 風格比較值型別物件。 |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | 模擬 C# 風格的浮點比較，當兩個 NaN 被視為相等，即使根據 IEC 60559:1989，NaN 與任何值（包括 NaN）均不相等。 |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | 模擬 C# 風格的浮點比較，當兩個 NaN 被視為相等，即使根據 IEC 60559:1989，NaN 與任何值（包括 NaN）均不相等。 |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | 僅供內部使用。 |
| [System::String](../../system/string/) [get_Formula](./get_formula/)() override | 值、from、to、by 屬性中的公式可以由以下組成：標準算術運算子：\\u2018+\\u2019、\\u2018-\\u2018、\\u2018*\\u2019、\\u2018/\\u2019、\\u2018^\\u2019、\\u2018\\u2019（mod）常數：\\u2018pi\\u2019 \\u2018e\\u2019 條件運算子：\\u2018abs\\u2019、\\u2018min\\u2019、\\u2018max\\u2019、\\u2018?\\u2019（if）比較運算子：'==', '>=', '', '!=', '!' 三角函數運算子：\\u2018sin()\\u2019、\\u2018cos()\\u2019、\\u2018tan()\\u2019、\\u2018asin()\\u2019、\\u2018acos()\\u2019、\\u2018atan()\\u2019 自然對數 \\u2018ln()\\u2019 屬性參考（主機支援的屬性） |
| **float** [get_Time](./get_time/)() override | 表示時間值。讀取 **float**。 |
| [System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\> [get_Value](./get_value/)() override | 表示點值。僅限：bool、[ColorFormat](../../aspose.slides/colorformat/)、float、int、string。讀取 [System::Object](../../system/object/)。 |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | 取得與物件關聯的參考計數器資料結構。 |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | 相當於 C# [Object.GetHashCode()](../../system/object/gethashcode/) 方法。啟用自訂物件的雜湊。 |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | 取得物件的實際型別。相當於 C# [System.Object.GetType()](../../system/object/gettype/) 呼叫。 |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | 檢查物件是否為 targetType 所描述型別的實例。相當於 C# 'is' 運算子。 |
| void [Lock](../../system/object/lock/)() | 實作 C# lock() 陳述式的鎖定。直接呼叫或使用 [LockContext](../../system/lockcontext/) 監視物件。 |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | 相當於 C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) 方法。啟用自訂型別的複製。 |
|  [Object](../../system/object/object/)() | 建立物件。初始化所有內部資料結構。 |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | 複製建構函式。實際上不會複製任何內容，只是初始化新物件並允許子類別的複製建構。 |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | 賦值運算子。實際上不會複製任何內容，只是初始化新物件並允許子類別的複製建構。 |
|  [Point](./point/)() | 預設建構函式。 |
|  [Point](./point/)(**float**, [System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\>, [System::String](../../system/string/)) | 建立具有時間、值和公式的動畫點。 |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | 依參考比較物件。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | 依參考比較物件。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | 以參考方式比較值型別物件與 nullptr。 |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | [Object::ReferenceEquals](../../system/object/referenceequals/) 的特化，用於 string 與 nullptr 的情況。 |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | [Object::ReferenceEquals](../../system/object/referenceequals/) 的特化，用於字串的情況。 |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | 將共享參考計數減少指定的值。 |
| void [set_Formula](./set_formula/)([System::String](../../system/string/)) override | 值、from、to、by 屬性中的公式可以由以下組成：標準算術運算子：\\u2018+\\u2019、\\u2018-\\u2018、\\u2018*\\u2019、\\u2018/\\u2019、\\u2018^\\u2019、\\u2018\\u2019（mod）常數：\\u2018pi\\u2019 \\u2018e\\u2019 條件運算子：\\u2018abs\\u2019、\\u2018min\\u2019、\\u2018max\\u2019、\\u2018?\\u2019（if）比較運算子：'==', '>=', '', '!=', '!' 三角函數運算子：\\u2018sin()\\u2019、\\u2018cos()\\u2019、\\u2018tan()\\u2019、\\u2018asin()\\u2019、\\u2018acos()\\u2019、\\u2018atan()\\u2019 自然對數 \\u2018ln()\\u2019 屬性參考（主機支援的屬性） |
| void [set_Time](./set_time/)(**float**) override | 表示時間值。寫入 **float**。 |
| void [set_Value](./set_value/)([System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\>) override | 表示點值。僅限：bool、[ColorFormat](../../aspose.slides/colorformat/)、float、int、string。寫入 [System::Object](../../system/object/)。 |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | 將第 n 個模板參數設為弱指標（而非共享）。允許在容器中將指標切換為弱模式。 |
| int [SharedCount](../../system/object/sharedcount/)() const | 取得共享參考計數器的當前值。 |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | 遞增共享參考計數。不應直接呼叫；請改用智慧指標或 ThisProtector。 |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | 遞減並回傳共享參考計數。不應直接呼叫；請改用智慧指標或 ThisProtector。 |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | 相當於 C# [Object.ToString()](../../system/object/tostring/) 方法。啟用自訂物件轉換為字串。 |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | 實作 C# typeof([System.Object](../../system/object/)) 結構。 |
| void [Unlock](../../system/object/unlock/)() | 實作 C# lock() 陳述式的解鎖。直接呼叫或使用 [LockContext](../../system/lockcontext/) 監視物件。 |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | 遞增弱參考計數。不應直接呼叫；請改用智慧指標或 ThisProtector。 |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | 遞減弱參考計數。不應直接呼叫；請改用智慧指標或 ThisProtector。 |
| virtual  [~Object](../../system/object/~object/)() | 銷毀物件。釋放所有內部資料結構。 |

## 另請參閱

* 類別 [IPoint](../ipoint/)
* 命名空間 [Aspose::Slides::Animation](../)
* 函式庫 [Aspose.Slides](../../)