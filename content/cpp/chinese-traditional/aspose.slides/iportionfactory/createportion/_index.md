---
title: CreatePortion()
second_title: Aspose.Slides for C++ API 參考
description: 建立一個空的文字區塊。
type: docs
weight: 1
url: /zh-hant/aspose.slides/iportionfactory/createportion/
---
## IPortionFactory::CreatePortion() 方法

建立一個空的文字區塊。

```cpp
virtual System::SharedPtr<IPortion> Aspose::Slides::IPortionFactory::CreatePortion()=0
```

### 返回值

[Portion](../../portion/).

## IPortionFactory::CreatePortion(System::String) 方法

建立一個文字區塊，內容來自指定的字串。

```cpp
virtual System::SharedPtr<IPortion> Aspose::Slides::IPortionFactory::CreatePortion(System::String str)=0
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| str | [System::String](../../../system/string/) | 字串。 |

### 返回值

[Portion](../../portion/).

## IPortionFactory::CreatePortion(System::SharedPtr\<IPortion\>) 方法

建立一個使用指定區塊資料的區塊。

```cpp
virtual System::SharedPtr<IPortion> Aspose::Slides::IPortionFactory::CreatePortion(System::SharedPtr<IPortion> portion)=0
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| portion | [System::SharedPtr](../../../system/sharedptr/)\<[IPortion](../../iportion/)\> | 要使用的區塊。 |

### 返回值

[Portion](../../portion/).

## 參見

* 型別別名 [SharedPtr](../../../system/sharedptr/)
* 類別 [IPortion](../../iportion/)
* 類別 [IPortionFactory](../)
* 類別 [String](../../../system/string/)
* 命名空間 [Aspose::Slides](../../)
* 函式庫 [Aspose.Slides](../../../)