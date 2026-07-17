---
title: TryParse()
second_title: Aspose.Slides for C++ API 参考
description: 将包含数字字符串表示的指定字符串转换为等效的 Decimal 值。
type: docs
weight: 482
url: /zh/system/decimal/tryparse/
---
## Decimal::TryParse(const String&, Decimal&) 方法


将包含数字字符串表示的指定字符串转换为等效的 [Decimal](../) 值。

```cpp
static bool System::Decimal::TryParse(const String &value, Decimal &result)
```


### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | const [String](../../string/)\& | 要转换的字符串 |
| result | [Decimal](../)\& | 对 [Decimal](../) 变量的引用，用于保存转换结果 |

### 返回值

如果转换成功则为 True，否则为 false

## Decimal::TryParse(const String&, Globalization::NumberStyles, const SharedPtr\<IFormatProvider\>\&, Decimal&) 方法


将包含数字字符串表示的指定字符串转换为等效的 [Decimal](../) 值，使用提供的格式信息和数字样式。

```cpp
static bool System::Decimal::TryParse(const String &value, Globalization::NumberStyles styles, const SharedPtr<IFormatProvider> &provider, Decimal &result)
```


### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | const [String](../../string/)\& | 要转换的字符串 |
| styles | [Globalization::NumberStyles](../../../system.globalization/numberstyles/) | NumberStyles 枚举的位组合，指定数字字符串表示的允许样式 |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | 指向包含字符串格式信息的对象的指针 |
| result | [Decimal](../)\& | 输出参数；包含转换结果 |

### 返回值

如果转换成功则为 True，否则为 false

## 另见

* 枚举 [NumberStyles](../../../system.globalization/numberstyles/)
* 类型定义 [SharedPtr](../../sharedptr/)
* 类 [String](../../string/)
* 类 [Decimal](../)
* 类 [IFormatProvider](../../iformatprovider/)
* 命名空间 [System](../../)
* 库 [Aspose.Slides](../../../)