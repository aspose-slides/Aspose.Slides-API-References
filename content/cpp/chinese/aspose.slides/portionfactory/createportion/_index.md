---
title: CreatePortion()
second_title: Aspose.Slides C++ API 参考
description: 创建一个空的文本段落。
type: docs
weight: 1
url: /zh/aspose.slides/portionfactory/createportion/
---
## PortionFactory::CreatePortion() 方法


创建一个空的文本段落。

```cpp
System::SharedPtr<IPortion> Aspose::Slides::PortionFactory::CreatePortion() override
```


### 返回值

[Portion](../../portion/).

## PortionFactory::CreatePortion(System::String) 方法


根据指定的字符串创建文本段落。

```cpp
System::SharedPtr<IPortion> Aspose::Slides::PortionFactory::CreatePortion(System::String str) override
```


### 参数

| Parameter | Type | Description |
| --- | --- | --- |
| str | [System::String](../../../system/string/) | 字符串。 |

### 返回值

[Portion](../../portion/).

## PortionFactory::CreatePortion(System::SharedPtr\<IPortion\>) 方法


使用指定的段落数据创建段落。

```cpp
System::SharedPtr<IPortion> Aspose::Slides::PortionFactory::CreatePortion(System::SharedPtr<IPortion> portion) override
```


### 参数

| Parameter | Type | Description |
| --- | --- | --- |
| portion | [System::SharedPtr](../../../system/sharedptr/)\<[IPortion](../../iportion/)\> | 要使用的段落。 |

### 返回值

[Portion](../../portion/).

## 另请参见

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IPortion](../../iportion/)
* Class [PortionFactory](../)
* Class [String](../../../system/string/)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)