---
title: CreatePortion()
second_title: Aspose.Slides for C++ API 參考文件
description: 建立空的文字區段。
type: docs
weight: 1
url: /zh-hant/aspose.slides/portionfactory/createportion/
---
## PortionFactory::CreatePortion() 方法


建立空的文字區段。

```cpp
System::SharedPtr<IPortion> Aspose::Slides::PortionFactory::CreatePortion() override
```


### 返回值

[Portion](../../portion/).

## PortionFactory::CreatePortion(System::String) 方法


從指定的字串建立文字區段。

```cpp
System::SharedPtr<IPortion> Aspose::Slides::PortionFactory::CreatePortion(System::String str) override
```


### 參數

| 參數 | 類型 | 描述 |
| --- | --- | --- |
| str | [System::String](../../../system/string/) | String. |

### 返回值

[Portion](../../portion/).

## PortionFactory::CreatePortion(System::SharedPtr\<IPortion\>) 方法


使用指定的區段資料建立區段。

```cpp
System::SharedPtr<IPortion> Aspose::Slides::PortionFactory::CreatePortion(System::SharedPtr<IPortion> portion) override
```


### 參數

| 參數 | 類型 | 描述 |
| --- | --- | --- |
| portion | [System::SharedPtr](../../../system/sharedptr/)\<[IPortion](../../iportion/)\> | A portion to use. |

### 返回值

[Portion](../../portion/).

## 另見

* Typedef [SharedPtr](../../../system/sharedptr/)
* 類別 [IPortion](../../iportion/)
* 類別 [PortionFactory](../)
* 類別 [String](../../../system/string/)
* 命名空間 [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)