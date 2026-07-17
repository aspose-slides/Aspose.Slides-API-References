---
title: TryParse()
second_title: Aspose.Slides for C++ API 参考
description: 尝试将指定的字符串转换为 Guid 对象。
type: docs
weight: 157
url: /zh/system/guid/tryparse/
---
## Guid::TryParse(const String\&, Guid\&) 方法

尝试将指定的字符串转换为 [Guid](../) 对象。

```cpp
static bool System::Guid::TryParse(const String &input, Guid &g)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| input | const [String](../../string/)\& | 要转换的字符串 |
| g | [Guid](../)\& | 如果成功，则输出 [Guid](../) 对象。 |

### 返回值

如果输入字符串表示有效的 [Guid](../)，则返回 true；否则返回 false。

## 另请参见

* 类 [String](../../string/)
* 类 [Guid](../)
* 命名空间 [System](../../)
* 库 [Aspose.Slides](../../../)