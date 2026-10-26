---
title: Hyperlink()
second_title: Aspose.Slides C++ API 参考
description: 创建一个超链接实例。
type: docs
weight: 339
url: /zh/aspose.slides/hyperlink/hyperlink/
---
## Hyperlink::Hyperlink(System::String) 构造函数


创建一个超链接实例。

```cpp
Aspose::Slides::Hyperlink::Hyperlink(System::String url)
```


### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| url | [System::String](../../../system/string/) | [Hyperlink](../) URL. |

## Hyperlink::Hyperlink(System::SharedPtr\<ISlide\>) 构造函数


创建一个指向特定幻灯片的超链接实例。注意：创建的超链接应分配给同一演示文稿中的某个对象，否则链接将保存为 NoAction。

```cpp
Aspose::Slides::Hyperlink::Hyperlink(System::SharedPtr<ISlide> slide)
```


### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| slide | [System::SharedPtr](../../../system/sharedptr/)\<[ISlide](../../islide/)\> | 目标幻灯片。 |

## Hyperlink::Hyperlink(System::SharedPtr\<Hyperlink\>, System::String, System::String, bool, bool, bool) 构造函数


使用另一个超链接作为来源创建超链接实例，覆盖次要属性。

```cpp
Aspose::Slides::Hyperlink::Hyperlink(System::SharedPtr<Hyperlink> source, System::String targetFrame, System::String tooltip, bool history, bool stopSoundsOnClick, bool highlightClick)
```


### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| source | [System::SharedPtr](../../../system/sharedptr/)\<[Hyperlink](../)\> | 源超链接 |
| targetFrame | [System::String](../../../system/string/) | 目标框架 |
| tooltip | [System::String](../../../system/string/) | 工具提示文本 |
| history | **bool** |  |
| stopSoundsOnClick | **bool** |  |
| highlightClick | **bool** |  |

## 另见

* 类型别名 [SharedPtr](../../../system/sharedptr/)
* 类 [String](../../../system/string/)
* 类 [Hyperlink](../)
* 类 [ISlide](../../islide/)
* 命名空间 [Aspose::Slides](../../)
* 库 [Aspose.Slides](../../../)