---
title: CreatePortion()
second_title: Aspose.Slides for C++ API 参考
description: 创建一个空的文本部分。
type: docs
weight: 1
url: /zh/aspose.slides/iportionfactory/createportion/
---
## IPortionFactory::CreatePortion() 方法


创建一个空的文本部分。

```cpp
virtual System::SharedPtr<IPortion> Aspose::Slides::IPortionFactory::CreatePortion()=0
```


### 返回值

[Portion](../../portion/)。

## IPortionFactory::CreatePortion(System::String) 方法


从指定的字符串创建文本部分。

```cpp
virtual System::SharedPtr<IPortion> Aspose::Slides::IPortionFactory::CreatePortion(System::String str)=0
```


### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| str | [System::String](../../../system/string/) | 字符串。 |

### 返回值

[Portion](../../portion/)。

## IPortionFactory::CreatePortion(System::SharedPtr\<IPortion\>) 方法


使用指定的部分数据创建一个部分。

```cpp
virtual System::SharedPtr<IPortion> Aspose::Slides::IPortionFactory::CreatePortion(System::SharedPtr<IPortion> portion)=0
```


### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| portion | [System::SharedPtr](../../../system/sharedptr/)\<[IPortion](../../iportion/)\> | 要使用的部分。 |

### 返回值

[Portion](../../portion/)。

## 另见

* Typedef [SharedPtr](../../../system/sharedptr/)
* 类 [IPortion](../../iportion/)
* 类 [IPortionFactory](../)
* 类 [String](../../../system/string/)
* 命名空间 [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)