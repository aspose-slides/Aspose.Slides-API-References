---
title: "System::Text::RegularExpressions"
second_title: Aspose.Slides C++ API 参考
description: 
type: docs
weight: 989
url: /zh/system.text.regularexpressions/
---
## 类

| 类 | 描述 |
| --- | --- |
| [Capture](./capture/) | 单子表达式匹配的结果。该类的对象只能使用 [System::MakeObject()](../system/makeobject/) 函数分配。绝不要在栈上或使用 operator new 创建此类型的实例，因为会导致运行时错误和/或断言故障。始终将此类包装成 [System::SmartPtr](../system/smartptr/) 指针，并使用该指针作为参数传递给函数。 |
| [CaptureCollection](./capturecollection/) | 单个捕获组完成的捕获列表。该类的对象只能使用 [System::MakeObject()](../system/makeobject/) 函数分配。绝不要在栈上或使用 operator new 创建此类型的实例，因为会导致运行时错误和/或断言故障。始终将此类包装成 [System::SmartPtr](../system/smartptr/) 指针，并使用该指针作为参数传递给函数。 |
| [Group](./group/) | 单个捕获组完成的匹配结果。该类的对象只能使用 [System::MakeObject()](../system/makeobject/) 函数分配。绝不要在栈上或使用 operator new 创建此类型的实例，因为会导致运行时错误和/或断言故障。始终将此类包装成 [System::SmartPtr](../system/smartptr/) 指针，并使用该指针作为参数传递给函数。 |
| [GroupCollection](./groupcollection/) | 单次匹配中的捕获组列表。该类的对象只能使用 [System::MakeObject()](../system/makeobject/) 函数分配。绝不要在栈上或使用 operator new 创建此类型的实例，因为会导致运行时错误和/或断言故障。始终将此类包装成 [System::SmartPtr](../system/smartptr/) 指针，并使用该指针作为参数传递给函数。 |
| [GroupCollectionPtr](./groupcollectionptr/) | [Group](./group/) 集合指针。此类型是用于管理其他对象删除的指针。应在栈上分配，并通过值或 const 引用传递给函数。 |
| [Match](./match/) | [Single](../system/single/) 正则表达式在字符串上的匹配。该类的对象只能使用 [System::MakeObject()](../system/makeobject/) 函数分配。绝不要在栈上或使用 operator new 创建此类型的实例，因为会导致运行时错误和/或断言故障。始终将此类包装成 [System::SmartPtr](../system/smartptr/) 指针，并使用该指针作为参数传递给函数。 |
| [MatchCollection](./matchcollection/) | 通过反复将正则表达式应用于字符串而完成的匹配集合。该类的对象只能使用 [System::MakeObject()](../system/makeobject/) 函数分配。绝不要在栈上或使用 operator new 创建此类型的实例，因为会导致运行时错误和/或断言故障。始终将此类包装成 [System::SmartPtr](../system/smartptr/) 指针，并使用该指针作为参数传递给函数。 |
| [Regex](./regex/) | 遵循 C# 样式语法的正则表达式。该类的对象只能使用 [System::MakeObject()](../system/makeobject/) 函数分配。绝不要在栈上或使用 operator new 创建此类型的实例，因为会导致运行时错误和/或断言故障。始终将此类包装成 [System::SmartPtr](../system/smartptr/) 指针，并使用该指针作为参数传递给函数。 |
## 函数

| 函数 | 描述 |
| --- | --- |
|   [ASPOSECPP_3RD_PARTY_UNCOPYBALE_TYPE_HOLDER](./asposecpp_3rd_party_uncopybale_type_holder/)(Detail::MatchHolder, MatchHolder, sizeof(Detail::DummyMatchHolder), Detail::DummyMatchHolder, MatchHolderAlias) | 包装以保持 MatchHolder 类而不包括它以及 PCRE2。 |
## 枚举

| 枚举 | 描述 |
| --- | --- |
| [RegexOptions](./regexoptions/) | [Regex](./regex/) 选项。 |
## 类型别名

| 类型别名 | 描述 |
| --- | --- |
| [UStringPtr](./ustringptr/) | 共享 UnicodeString 以避免复制。 |
| [CapturePtr](./captureptr/) | 指向单个捕获对象的指针。 |
| [CaptureCollectionPtr](./capturecollectionptr/) | 指向捕获集合的指针。 |
| [GroupPtr](./groupptr/) | 指向组的指针。 |
| [RegexPtr](./regexptr/) | [Regex](./regex/) 指针。 |
| [MatchPtr](./matchptr/) | [Match](./match/) 指针。 |
| [MatchCollectionPtr](./matchcollectionptr/) | [Match](./match/) 集合指针。 |
| [MatchEvaluator](./matchevaluator/) | 用于评估匹配的委托类型。