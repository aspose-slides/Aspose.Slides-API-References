---
title: Object
second_title: Aspose.Slides for C++ API 參考
description: 基礎類別，使得能在 C# 中使用 System.Object 類別提供的方法。所有在翻譯環境中使用的非平凡類別都應繼承此類別。
type: docs
weight: 1132
url: /zh-hant/system/object/
---
## 物件類別


Base class that enables using methods available for [System.Object](./) class in C#. All non-trivial classes used with translated environment should inherit it.

```cpp
class Object
```

## 方法

| 方法 | 說明 |
| --- | --- |
| virtual **bool** [Equals](./equals/)([ptr](./ptr/)) | 使用 C# [Object.Equals](./equals/) 語意比較物件。 |
| static std::enable_if\<[IsSmartPtr](../issmartptr/)\<T1\>::value\&&[IsSmartPtr](../issmartptr/)\<T2\>::value, **bool**\>::type [Equals](./equals/)(T1 const\&, T2 const\&) | 以 C# 風格比較參考型別的物件。 |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../issmartptr/)\<T2\>::value, **bool**\>::type [Equals](./equals/)(T1 const\&, T2 const\&) | 以 C# 風格比較值型別的物件。 |
| static **bool** [Equals](./equals/)(**float** const\&, **float** const\&) | 模擬 C# 風格的浮點比較，將兩個 NaN 視為相等，即使依據 IEC 60559:1989，NaN 不等於任何值，包括 NaN 本身。 |
| static **bool** [Equals](./equals/)(**double** const\&, **double** const\&) | 模擬 C# 風格的浮點比較，將兩個 NaN 視為相等，即使依據 IEC 60559:1989，NaN 不等於任何值，包括 NaN 本身。 |
| virtual **bool** [FastCast](./fastcast/)(const Details::FastRttiBase\&, void **) const | 僅供內部使用。 |
| Detail::SmartPtrCounter * [GetCounter](./getcounter/)() | 取得與物件相關聯的參考計數資料結構。 |
| virtual **int32_t** [GetHashCode](./gethashcode/)() const | 相當於 C# [Object.GetHashCode()](./gethashcode/) 方法。啟用自訂物件的雜湊。 |
| virtual const [TypeInfo](../typeinfo/)\& [GetType](./gettype/)() const | 取得物件的實際類型。相當於 C# [System.Object.GetType()](./gettype/) 呼叫。 |
| virtual **bool** [Is](./is/)(const [TypeInfo](../typeinfo/)\&) const | 檢查物件是否為 targetType 所描述類型的實例。相當於 C# 的 'is' 運算子。 |
| void [Lock](./lock/)() | 實作 C# lock() 陳述式的鎖定。直接呼叫或使用 [LockContext](../lockcontext/) 監視物件。 |
| virtual [ptr](./ptr/) [MemberwiseClone](./memberwiseclone/)() const | 相當於 C# [Object.MemberwiseClone()](./memberwiseclone/) 方法。啟用自訂類型的複製。 |
|  [Object](./object/)() | Creates object. Initializes all internal data structures. |
|  [Object](./object/)([Object](./) const\&) | Copy constructor. Doesn't copy anything, really, just initializes new object and enables copy constructing subclasses. |
| [Object](./)\& [operator=](./operator_equal/)([Object](./) const\&) | Assignment operator. Doesn't copy anything, really, just initializes new object and enables copy constructing subclasses. |
| static **bool** [ReferenceEquals](./referenceequals/)([ptr](./ptr/) const\&, [ptr](./ptr/) const\&) | 以參考方式比較物件。 |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](./referenceequals/)(T const\&, T const\&) | 以參考方式比較物件。 |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](./referenceequals/)(T const\&, std::nullptr_t) | 以參考方式將值型別物件與 nullptr 比較。 |
| **bool** [ReferenceEquals](./referenceequals/)([String](../string/) const\&, std::nullptr_t) | [Object::ReferenceEquals](./referenceequals/) 在字串與 nullptr 情況下的特化。 |
| **bool** [ReferenceEquals](./referenceequals/)([String](../string/) const\&, [String](../string/) const\&) | [Object::ReferenceEquals](./referenceequals/) 在字串情況下的特化。 |
| int [RemovedSharedRefs](./removedsharedrefs/)(int) | 將共享參考計數減少指定的數值。 |
| virtual void [SetTemplateWeakPtr](./settemplateweakptr/)(**uint32_t**) | 設定第 n 個模板參數為弱指標（而非共享）。允許在容器中將指標切換為弱模式。 |
| int [SharedCount](./sharedcount/)() const | 取得共享參考計數的目前值。 |
| [Object](./) * [SharedRefAdded](./sharedrefadded/)() | 遞增共享參考計數。不應直接呼叫；請改用智慧指標或 ThisProtector。 |
| int [SharedRefRemovedSafe](./sharedrefremovedsafe/)() | 遞減並回傳共享參考計數。不應直接呼叫；請改用智慧指標或 ThisProtector。 |
| virtual [String](../string/) [ToString](./tostring/)() const | 相當於 C# [Object.ToString()](./tostring/) 方法。啟用將自訂物件轉換為字串。 |
| static const [TypeInfo](../typeinfo/)\& [Type](./type/)() | 實作 C# typeof([System.Object](./)) 結構。 |
| void [Unlock](./unlock/)() | 實作 C# lock() 陳述式的解除鎖定。直接呼叫或使用 [LockContext](../lockcontext/) 監視物件。 |
| Detail::SmartPtrCounter * [WeakRefAdded](./weakrefadded/)() | 遞增弱參考計數。不應直接呼叫；請改用智慧指標或 ThisProtector。 |
| void [WeakRefRemoved](./weakrefremoved/)() | 遞減弱參考計數。不應直接呼叫；請改用智慧指標或 ThisProtector。 |
| virtual  [~Object](./~object/)() | 銷毀物件。釋放所有內部資料結構。 |

## 型別別名

| 型別別名 | 說明 |
| --- | --- |
| [ptr](./ptr/) | 智慧指標類型的別名。 |

## 備註

Alongside with methods available in C# [System.Object](./) class, it also enables support for some concepts specific for translated code environment. This includes reference counting used by smart pointer classes ([System::SmartPtr](../smartptr/), [System::WeakPtr](../weakptr/), [System::DynamicWeakPtr](../dynamicweakptr/)) and other services related to memory management, debug, etc.

每個 [Object](./) 有兩個參考計數器：共享參考計數器與弱參考計數器。弱參考計數器始終儲存在與 [Object](./) 本身分離的資料結構中，從而允許弱指標的壽命超過被參照的物件。智慧參考計數器依據 ENABLE_EXTERNAL_REFCOUNT 巨集狀態，可能儲存在物件本身或相同的分離結構中。預設情況下，於除錯建置中啟用，而在發行建置中停用。若智慧指標計數器儲存在物件本身，僅在存在指向該物件的弱指標時才建立分離資料結構。否則，會與物件本身一起建立。

所有智慧指標均使用這兩個參考計數器，並屬於同一唯一的擁有權群組。

若在堆疊上建立 [Object](./) 子類別，則不得建立指向它的智慧指標，否則會產生堆疊刪除問題。

此類型可以作為值型別在堆疊上配置，或使用 [System::MakeObject()](../makeobject/) 函式在堆上配置。物件配置後，切勿混用這兩種情況：嚴禁將 [SmartPtr](../smartptr/) 指標指向堆疊配置的物件。

## 另請參閱

* 命名空間 [System](../)
* 函式庫 [Aspose.Slides](../../)