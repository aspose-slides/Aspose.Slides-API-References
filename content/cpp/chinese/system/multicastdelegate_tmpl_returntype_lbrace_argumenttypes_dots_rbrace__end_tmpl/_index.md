---
title: MulticastDelegate< ReturnType(ArgumentTypes...)>
second_title: Aspose.Slides for C++ API 参考
description: "表示委托的集合。此类型应分配在栈上，并通过值或引用传递给函数。切勿使用 System::SmartPtr 类来管理此类型的对象。"
type: docs
weight: 1080
url: /zh/system/multicastdelegate_tmpl_returntype_lbrace_argumenttypes_dots_rbrace__end_tmpl/
---
## MulticastDelegate< ReturnType(ArgumentTypes...)> 类

表示委托的集合。此类型应分配在栈上，并通过值或引用传递给函数。切勿使用 [System::SmartPtr](../smartptr/) 类来管理此类型的对象。

```cpp
template<class ReturnType,class...>class MulticastDelegate< ReturnType(ArgumentTypes...)> : public System::Details::DelegateHoldingVariables
```

### 模板参数

| Parameter | Description |
| --- | --- |
| ReturnType | Return type of the invokable entities pointed to by each delegate in the collection |
| ArgumentTypes | Argument list of the invokable entities pointed to by each delegate in the collection |

## 方法

| Method | Description |
| --- | --- |
| [SharedPtr](../sharedptr/)\<[IAsyncResult](../iasyncresult/)\> [BeginInvoke](./begininvoke/)(ArgumentTypes..., const [AsyncCallback](../asynccallback/)\&, const CallbackArgumentType\&) | 未实现。 |
| [MulticastDelegate](./multicastdelegate/)\& [connect](./connect/)([Callback](./callback/)) | 将指定的委托添加到集合中。 |
| [MulticastDelegate](./multicastdelegate/)\& [connect](./connect/)(std::function\<R(Args...)>) | 将指定的函数对象添加到委托集合中。在添加到集合之前，函数对象会被转换为 Callback 委托类型。 |
| [MulticastDelegate](./multicastdelegate/)\& [connect](./connect/)([MulticastDelegate](./multicastdelegate/)\&) | 将指定的 MulticastDelegate 对象添加到委托集合中。 |
| [MulticastDelegate](./multicastdelegate/)\& [connect](./connect/)(MemberType ClassType::*, ClassType *) | 将指定对象的指定非静态方法添加到委托集合中。 |
| [MulticastDelegate](./multicastdelegate/)\& [connect](./connect/)(MemberType ClassType::*, const [SharedPtr](../sharedptr/)\<ClassType\>\&) | 将指定对象的指定非静态方法添加到委托集合中。 |
| [MulticastDelegate](./multicastdelegate/)\& [disconnect](./disconnect/)([Callback](./callback/)) | 从委托集合中移除指定的委托。 |
| [MulticastDelegate](./multicastdelegate/)\& [disconnect](./disconnect/)(MemberType ClassType::*, ClassType *) | 从委托集合中移除指定对象的指定非静态方法。 |
| [MulticastDelegate](./multicastdelegate/)\& [disconnect](./disconnect/)(MemberType ClassType::*, const [SharedPtr](../sharedptr/)\<ClassType\>\&) | 从委托集合中移除指定对象的指定非静态方法。 |
| [MulticastDelegate](./multicastdelegate/)\& [disconnect](./disconnect/)([MulticastDelegate](./multicastdelegate/)\&) | 从委托集合中移除指定的 MulticastDelegate 对象。 |
| [MulticastDelegate](./multicastdelegate/)\& [disconnect_all_slots](./disconnect_all_slots/)() | 从委托集合中移除所有委托。 |
| **bool** [empty](./empty/)() const | 确定委托集合是否为空。 |
| ReturnType [EndInvoke](./endinvoke/)(const [SharedPtr](../sharedptr/)\<[IAsyncResult](../iasyncresult/)\>\&) | 未实现。 |
| **bool** [Equals](./equals/)(const [MulticastDelegate](./multicastdelegate/)\&) |  |
| int [GetHashCode](./gethashcode/)() const |  |
| const [TypeInfo](../typeinfo/)\& [GetType](./gettype/)() const |  |
| ReturnType [invoke](./invoke/)(ArgumentTypes...) const | 调用委托集合中当前存在的所有委托。委托按照添加到集合的顺序被调用。该方法在委托执行期间会阻塞。 |
| **bool** [IsNull](./isnull/)() const | 确定委托集合是否为空。 |
|  [MulticastDelegate](./multicastdelegate/)() | 构造一个空集合。 |
|  [MulticastDelegate](./multicastdelegate/)(std::nullptr_t) | 等同于默认构造函数。 |
|  [MulticastDelegate](./multicastdelegate/)(const MulticastDelegate\&) | 对委托集合执行浅拷贝。 |
|  [MulticastDelegate](./multicastdelegate/)(MulticastDelegate\&&) | 移动构造函数。 |
|  [MulticastDelegate](./multicastdelegate/)([Callback](./callback/)\&&) | 构造实例并将指定的委托放入委托集合中。 |
|  [MulticastDelegate](./multicastdelegate/)(T) | 构造实例并将指定的值放入委托集合中。 |
|  [MulticastDelegate](./multicastdelegate/)(std::function\<ReturnType(ArgumentTypes...)>) | 构造实例并将指定的值放入委托集合中。 |
| **bool** [operator!=](./operator_not_equal/)(const std::nullptr_t\&) const | 确定委托集合是否非空。 |
| **bool** [operator!=](./operator_not_equal/)(const [MulticastDelegate](./multicastdelegate/)\&) const | 确定两个 MulticastDelegate 实例——当前对象和指定对象——是否不相等。 |
| ReturnType [operator()](./operator_call/)(ArgumentTypes...) const | 调用委托集合中当前存在的所有委托。委托按照添加到集合的顺序被调用。该运算符在委托执行期间会阻塞。 |
| [MulticastDelegate](./multicastdelegate/)\& [operator+=](./operator_plus_equal/)([Callback](./callback/)) | 将指定的委托添加到集合中。 |
| [MulticastDelegate](./multicastdelegate/)\& [operator-=](./operator_minus_equal/)([Callback](./callback/)) | 从委托集合中移除指定的委托。 |
| [MulticastDelegate](./multicastdelegate/)\& [operator=](./operator_equal/)(const [MulticastDelegate](./multicastdelegate/)\&) | 将指定对象表示的委托集合分配给当前对象。因此两个对象指向同一个委托集合。 |
| [MulticastDelegate](./multicastdelegate/)\& [operator=](./operator_equal/)([MulticastDelegate](./multicastdelegate/)\&&) | 移动赋值运算符。 |
| **bool** [operator==](./operator_equal_equal/)(const std::nullptr_t\&) const | 确定委托集合是否为空。 |
| **bool** [operator==](./operator_equal_equal/)(const [MulticastDelegate](./multicastdelegate/)\&) const | 确定两个 MulticastDelegate 实例——当前对象和指定对象——是否相等。 |
| void [remove_empty_callbacks](./remove_empty_callbacks/)() const | 清除为空的已包含回调（实际不调用任何内容）。 |
| [String](../string/) [ToString](./tostring/)() const |  |
| static const [TypeInfo](../typeinfo/)\& [Type](./type/)() | 返回对 [TypeInfo](../typeinfo/) 对象的引用，该对象表示 MulticastDelegate 类的类型信息。 |
|  [~MulticastDelegate](./~multicastdelegate/)() | 析构函数。 |

## 类型别名

| Typedef | Description |
| --- | --- |
| [Callback](./callback/) | 由 MulticastDelegate 类表示的委托的类型。 |
| [Function](./function/) | 与委托签名相关的函数的类型。 |

## 另请参见

* 命名空间 [System](../)
* 库 [Aspose.Slides](../../)