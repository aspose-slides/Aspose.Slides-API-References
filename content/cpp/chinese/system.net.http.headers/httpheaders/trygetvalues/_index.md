---
title: TryGetValues()
second_title: Aspose.Slides for C++ API 参考
description: 尝试通过指定的名称获取相应的值。
type: docs
weight: 66
url: /zh/system.net.http.headers/httpheaders/trygetvalues/
---
## HttpHeaders::TryGetValues(String, System::SharedPtr\<Collections::Generic::IEnumerable\<String\>\>\&) method

尝试通过指定的名称获取相应的值。

```cpp
bool System::Net::Http::Headers::HttpHeaders::TryGetValues(String name, System::SharedPtr<Collections::Generic::IEnumerable<String>> &values)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| name | [String](../../../system/string/) | 标头名称。 |
| values | [System::SharedPtr](../../../system/sharedptr/)\<[Collections::Generic::IEnumerable](../../../system.collections.generic/ienumerable/)\<[String](../../../system/string/)\>\>\& | 将分配相应值的实例。 |

### 返回值

当通过指定的名称找到标头值时返回 True，否则返回 false。

## 另请参见

* 类型定义 [SharedPtr](../../../system/sharedptr/)
* 类 [String](../../../system/string/)
* 类 [IEnumerable](../../../system.collections.generic/ienumerable/)
* 类 [HttpHeaders](../)
* 命名空间 [System::Net::Http::Headers](../../)
* 库 [Aspose.Slides](../../../)