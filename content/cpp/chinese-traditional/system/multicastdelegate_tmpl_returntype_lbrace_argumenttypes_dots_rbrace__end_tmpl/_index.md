---
title: MulticastDelegate< ReturnType(ArgumentTypes...)>
second_title: Aspose.Slides for C++ API 參考
description: "代表委派的集合。此類型應在堆疊上分配，並以值或參考傳遞給函式。切勿使用 System::SmartPtr 類別來管理此類型的物件。"
type: docs
weight: 1093
url: /zh-hant/system/multicastdelegate_tmpl_returntype_lbrace_argumenttypes_dots_rbrace__end_tmpl/
---
## MulticastDelegate< ReturnType(ArgumentTypes...)> 類別


表示委派的集合。此類型應該在堆疊上分配，並以值或引用傳遞給函式。切勿使用 [System::SmartPtr](../smartptr/) 類別來管理此類型的物件。

```cpp
template<class ReturnType,class...>class MulticastDelegate< ReturnType(ArgumentTypes...)> : public System::Details::DelegateHoldingVariables
```


### 模板參數

| 參數 | 說明 |
| --- | --- |
| ReturnType | 集合中每個委派指向的可呼叫實體的返回類型 |
| ArgumentTypes | 集合中每個委派指向的可呼叫實體的參數清單 |
## 方法

| 方法 | 說明 |
| --- | --- |
| [SharedPtr](../sharedptr/)\<[IAsyncResult](../iasyncresult/)\> [BeginInvoke](./begininvoke/)(ArgumentTypes..., const [AsyncCallback](../asynccallback/)\&, const CallbackArgumentType\&) | 未實作。 |
| [MulticastDelegate](./multicastdelegate/)\& [connect](./connect/)([Callback](./callback/)) | 將指定的委派加入集合。 |
| [MulticastDelegate](./multicastdelegate/)\& [connect](./connect/)(std::function\<R(Args...)>) | 將指定的函式物件加入委派集合。加入集合前，該函式物件會轉換為 Callback 委派型別。 |
| [MulticastDelegate](./multicastdelegate/)\& [connect](./connect/)([MulticastDelegate](./multicastdelegate/)\&) | 將指定的 MulticastDelegate 物件加入委派集合。 |
| [MulticastDelegate](./multicastdelegate/)\& [connect](./connect/)(MemberType ClassType::*, ClassType *) | 將指定物件的非靜態方法加入委派集合。 |
| [MulticastDelegate](./multicastdelegate/)\& [connect](./connect/)(MemberType ClassType::*, const [SharedPtr](../sharedptr/)\<ClassType\>\&) | 將指定物件的非靜態方法加入委派集合。 |
| [MulticastDelegate](./multicastdelegate/)\& [disconnect](./disconnect/)([Callback](./callback/)) | 從委派集合中移除指定的委派。 |
| [MulticastDelegate](./multicastdelegate/)\& [disconnect](./disconnect/)(MemberType ClassType::*, ClassType *) | 從委派集合中移除指定物件的非靜態方法。 |
| [MulticastDelegate](./multicastdelegate/)\& [disconnect](./disconnect/)(MemberType ClassType::*, const [SharedPtr](../sharedptr/)\<ClassType\>\&) | 從委派集合中移除指定物件的非靜態方法。 |
| [MulticastDelegate](./multicastdelegate/)\& [disconnect](./disconnect/)([MulticastDelegate](./multicastdelegate/)\&) | 從委派集合中移除指定的 MulticastDelegate 物件。 |
| [MulticastDelegate](./multicastdelegate/)\& [disconnect_all_slots](./disconnect_all_slots/)() | 從委派集合中移除所有委派。 |
| **bool** [empty](./empty/)() const | 判斷委派集合是否為空。 |
| ReturnType [EndInvoke](./endinvoke/)(const [SharedPtr](../sharedptr/)\<[IAsyncResult](../iasyncresult/)\>\&) | 未實作。 |
| **bool** [Equals](./equals/)(const [MulticastDelegate](./multicastdelegate/)\&) |  |
| int [GetHashCode](./gethashcode/)() const |  |
| const [TypeInfo](../typeinfo/)\& [GetType](./gettype/)() const |  |
| ReturnType [invoke](./invoke/)(ArgumentTypes...) const | 呼叫目前委派集合中所有的委派。委派會依加入集合的順序依序被呼叫。此方法會在委派執行期間阻塞。 |
| **bool** [IsNull](./isnull/)() const | 判斷委派集合是否為空。 |
|  [MulticastDelegate](./multicastdelegate/)() | 建構一個空的集合。 |
|  [MulticastDelegate](./multicastdelegate/)(std::nullptr_t) | 等同於預設建構函式。 |
|  [MulticastDelegate](./multicastdelegate/)(const MulticastDelegate\&) | 執行委派集合的淺層拷貝。 |
|  [MulticastDelegate](./multicastdelegate/)(MulticastDelegate\&&) | 移動建構函式。 |
|  [MulticastDelegate](./multicastdelegate/)([Callback](./callback/)\&&) | 建構實例並將指定的委派放入委派集合。 |
|  [MulticastDelegate](./multicastdelegate/)(T) | 建構實例並將指定的值放入委派集合。 |
|  [MulticastDelegate](./multicastdelegate/)(std::function\<ReturnType(ArgumentTypes...)>) | 建構實例並將指定的值放入委派集合。 |
| **bool** [operator!=](./operator_not_equal/)(const std::nullptr_t\&) const | 判斷委派集合是否非空。 |
| **bool** [operator!=](./operator_not_equal/)(const [MulticastDelegate](./multicastdelegate/)\&) const | 判斷兩個 MulticastDelegate 實例（目前物件與指定物件）是否不相等。 |
| ReturnType [operator()](./operator_call/)(ArgumentTypes...) const | 呼叫目前委派集合中所有的委派。委派會依加入集合的順序依序被呼叫。此運算子會在委派執行期間阻塞。 |
| [MulticastDelegate](./multicastdelegate/)\& [operator+=](./operator_plus_equal/)([Callback](./callback/)) | 將指定的委派加入集合。 |
| [MulticastDelegate](./multicastdelegate/)\& [operator-=](./operator_minus_equal/)([Callback](./callback/)) | 從委派集合中移除指定的委派。 |
| [MulticastDelegate](./multicastdelegate/)\& [operator=](./operator_equal/)(const [MulticastDelegate](./multicastdelegate/)\&) | 將由指定物件所代表的委派集合指派給目前物件。結果是兩個物件指向相同的委派集合。 |
| [MulticastDelegate](./multicastdelegate/)\& [operator=](./operator_equal/)([MulticastDelegate](./multicastdelegate/)\&&) | 移動指派運算子。 |
| **bool** [operator==](./operator_equal_equal/)(const std::nullptr_t\&) const | 判斷委派集合是否為空。 |
| **bool** [operator==](./operator_equal_equal/)(const [MulticastDelegate](./multicastdelegate/)\&) const | 判斷兩個 MulticastDelegate 實例（目前物件與指定物件）是否相等。 |
| void [remove_empty_callbacks](./remove_empty_callbacks/)() const | 清除空的回呼（實際上不會呼叫任何東西）。 |
| [String](../string/) [ToString](./tostring/)() const |  |
| static const [TypeInfo](../typeinfo/)\& [Type](./type/)() | 傳回表示 MulticastDelegate 類別型別資訊之 [TypeInfo](../typeinfo/) 物件的參考。 |
|  [~MulticastDelegate](./~multicastdelegate/)() | 解構函式。 |
## 型別別名

| 型別別名 | 說明 |
| --- | --- |
| [Callback](./callback/) | MulticastDelegate 類別所代表的委派型別。 |
| [Function](./function/) | 與委派簽名相關的函式型別。 |

## 另請參閱

* 命名空間 [System](../)
* 函式庫 [Aspose.Slides](../../)