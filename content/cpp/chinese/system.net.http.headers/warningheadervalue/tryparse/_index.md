---
title: TryParse()
second_title: Aspose.Slides for C++ API 参考
description: 尝试将传入的字符串转换为 WarningHeaderValue 类的实例。 
type: docs
weight: 118
url: /zh/system.net.http.headers/warningheadervalue/tryparse/
---
## WarningHeaderValue::TryParse(String, System::SharedPtr\<WarningHeaderValue\>\&) 方法

尝试将传入的字符串转换为 [WarningHeaderValue](../) 类的实例。

```cpp
static bool System::Net::Http::Headers::WarningHeaderValue::TryParse(String input, System::SharedPtr<WarningHeaderValue> &parsedValue)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| input | [String](../../../system/string/) | 要解析的字符串。 |
| parsedValue | [System::SharedPtr](../../../system/sharedptr/)\<[WarningHeaderValue](../)\>\& | 解析后的对象将被赋值的实例。 |

### 返回值

如果解析成功则返回 true，否则返回 false。

## 另请参见

* 类型定义 [SharedPtr](../../../system/sharedptr/)
* 类 [String](../../../system/string/)
* 类 [WarningHeaderValue](../)
* 命名空间 [System::Net::Http::Headers](../../)
* 库 [Aspose.Slides](../../../)