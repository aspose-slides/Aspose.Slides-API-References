---
title: AddRange()
second_title: Aspose.Slides for C++ API 参考
description: 向当前请求添加 'Range' 标头。
type: docs
weight: 690
url: /zh/system.net/httpwebrequest/addrange/
---
## HttpWebRequest::AddRange(int32_t) 方法

向当前请求添加 'Range' 标头。

```cpp
virtual void System::Net::HttpWebRequest::AddRange(int32_t range)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| range | **int32_t** | 请求范围的开始或结束。 |

## HttpWebRequest::AddRange(System::String, int32_t, int32_t) 方法

向当前请求添加 'Range' 标头。

```cpp
virtual void System::Net::HttpWebRequest::AddRange(System::String rangeSpecifier, int32_t from, int32_t to)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| rangeSpecifier | [System::String](../../../system/string/) | 指定范围的单位。 |
| from | **int32_t** | 请求范围的开始。 |
| to | **int32_t** | 请求范围的结束。 |

## 另见

* 类 [HttpWebRequest](../)
* 类 [String](../../../system/string/)
* 命名空间 [System::Net](../../)
* 库 [Aspose.Slides](../../../)