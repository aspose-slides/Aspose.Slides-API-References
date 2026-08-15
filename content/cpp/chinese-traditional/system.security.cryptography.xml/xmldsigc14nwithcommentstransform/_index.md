---
title: XmlDsigC14NWithCommentsTransform
second_title: Aspose.Slides for C++ API 參考文件
description: "表示用於帶有註釋的數位簽章的 C14N XML 正規化轉換。此類別的物件應僅使用 System::MakeObject() 函式配置。切勿在堆疊上或使用 new 運算子建立此類型的實例，因為會導致執行時錯誤和/或斷言失敗。請始終將此類別包裝成 System::SmartPtr 指標，並使用該指標作為參數傳遞給函式。"
type: docs
weight: 183
url: /zh-hant/system.security.cryptography.xml/xmldsigc14nwithcommentstransform/
---
## XmlDsigC14NWithCommentsTransform 類別


表示用於帶有註釋的數位簽章的 C14N XML 正規化轉換。此類別的物件應僅使用 [System::MakeObject()](../../system/makeobject/) 函式進行配置。切勿在堆疊上或使用 new 運算子建立此類型的實例，因為會導致執行時錯誤和/或斷言失敗。請始終將此類別包裝成 [System::SmartPtr](../../system/smartptr/) 指標，並使用該指標作為參數傳遞給函式。

```cpp
class XmlDsigC14NWithCommentsTransform : public System::Security::Cryptography::Xml::XmlDsigC14NTransform
```

## 方法

| 方法 | 說明 |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | 使用 C# [Object.Equals](../../system/object/equals/) 語意比較物件。 |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | 以 C# 風格比較參考型別物件。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | 以 C# 風格比較值型別物件。 |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | 模擬 C# 風格的浮點比較，其中即使依 IEC 60559:1989，NaN 不等於任何值（包括 NaN），兩個 NaN 仍被視為相等。 |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | 模擬 C# 風格的浮點比較，其中即使依 IEC 60559:1989，NaN 不等於任何值（包括 NaN），兩個 NaN 仍被視為相等。 |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | 僅供內部使用。 |
| [String](../../system/string/) [get_Algorithm](../transform/get_algorithm/)() |  |
| [SharedPtr](../../system/sharedptr/)\<[System::Xml::XmlElement](../../system.xml/xmlelement/)\> [get_Context](../transform/get_context/)() |  |
| [ArrayPtr](../../system/arrayptr/)\<[TypeInfo](../../system/typeinfo/)\> [get_InputTypes](../xmldsigc14ntransform/get_inputtypes/)() override |  |
| [ArrayPtr](../../system/arrayptr/)\<[TypeInfo](../../system/typeinfo/)\> [get_OutputTypes](../xmldsigc14ntransform/get_outputtypes/)() override |  |
| [SharedPtr](../../system/sharedptr/)\<[Collections::Generic::IDictionary](../../system.collections.generic/idictionary/)\<[String](../../system/string/), [String](../../system/string/)\>\> [get_PropagatedNamespaces](../transform/get_propagatednamespaces/)() |  |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | 取得與物件關聯的參考計數資料結構。 |
| [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\> [GetDigestedOutput](../xmldsigc14ntransform/getdigestedoutput/)([SharedPtr](../../system/sharedptr/)\<[HashAlgorithm](../../system.security.cryptography/hashalgorithm/)\>) override |  |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | 相當於 C# [Object.GetHashCode()](../../system/object/gethashcode/) 方法。啟用自訂物件的雜湊。 |
| [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [GetOutput](../xmldsigc14ntransform/getoutput/)() override |  |
| [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [GetOutput](../xmldsigc14ntransform/getoutput/)(const [TypeInfo](../../system/typeinfo/)\&) override |  |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | 取得物件的實際型別。相當於 C# [System.Object.GetType()](../../system/object/gettype/) 呼叫。 |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | 檢查物件是否為 targetType 所描述型別的實例。相當於 C# 'is' 運算子。 |
| void [LoadInnerXml](../xmldsigc14ntransform/loadinnerxml/)([SharedPtr](../../system/sharedptr/)\<[System::Xml::XmlNodeList](../../system.xml/xmlnodelist/)\>) override |  |
| void [LoadInput](../xmldsigc14ntransform/loadinput/)([SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>) override |  |
| void [Lock](../../system/object/lock/)() | 實作 C# lock() 敘述的鎖定。直接呼叫或使用 [LockContext](../../system/lockcontext/) 監視器物件。 |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | 相當於 C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) 方法。啟用自訂型別的克隆。 |
|  [Object](../../system/object/object/)() | 建立物件。初始化所有內部資料結構。 |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | 複製建構函式。實際上不會複製任何內容，只是初始化新物件並允許子類別的複製建構。 |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | 賦值運算子。實際上不會複製任何內容，只是初始化新物件並允許子類別的複製建構。 |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | 以參考方式比較物件。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | 以參考方式比較物件。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | 將值型別物件與 nullptr 作參考比較。 |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | [Object::ReferenceEquals](../../system/object/referenceequals/) 的特化版，用於字串與 nullptr 的情況。 |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | [Object::ReferenceEquals](../../system/object/referenceequals/) 的特化版，用於字串情況。 |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | 將共享參考計數減少指定的值。 |
| void [set_Algorithm](../transform/set_algorithm/)([String](../../system/string/)) |  |
| void [set_Context](../transform/set_context/)([SharedPtr](../../system/sharedptr/)\<[System::Xml::XmlElement](../../system.xml/xmlelement/)\>) |  |
| void [set_Resolver](../transform/set_resolver/)([SharedPtr](../../system/sharedptr/)\<[System::Xml::XmlResolver](../../system.xml/xmlresolver/)\>) |  |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | 將第 n 個模板參數設定為弱指標（而非共享）。允許在容器中將指標切換為弱模式。 |
| int [SharedCount](../../system/object/sharedcount/)() const | 取得共享參考計數的目前值。 |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | 遞增共享參考計數。不應直接呼叫；請改用智慧指標或 ThisProtector。 |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | 遞減並回傳共享參考計數。不應直接呼叫；請改用智慧指標或 ThisProtector。 |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | 相當於 C# [Object.ToString()](../../system/object/tostring/) 方法。啟用自訂物件轉為字串。 |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | 實作 C# typeof([System.Object](../../system/object/)) 結構。 |
| void [Unlock](../../system/object/unlock/)() | 實作 C# lock() 敘述的解鎖。直接呼叫或使用 [LockContext](../../system/lockcontext/) 監視器物件。 |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | 遞增弱參考計數。不應直接呼叫；請改用智慧指標或 ThisProtector。 |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | 遞減弱參考計數。不應直接呼叫；請改用智慧指標或 ThisProtector。 |
|  [XmlDsigC14NTransform](../xmldsigc14ntransform/xmldsigc14ntransform/)() |  |
|  [XmlDsigC14NTransform](../xmldsigc14ntransform/xmldsigc14ntransform/)(**bool**) |  |
|  [XmlDsigC14NWithCommentsTransform](./xmldsigc14nwithcommentstransform/)() |  |
| virtual  [~Object](../../system/object/~object/)() | 銷毀物件。釋放所有內部資料結構。 |

## 另請參閱

* 類別 [XmlDsigC14NTransform](../xmldsigc14ntransform/)
* 命名空間 [System::Security::Cryptography::Xml](../)
* 函式庫 [Aspose.Slides](../../)