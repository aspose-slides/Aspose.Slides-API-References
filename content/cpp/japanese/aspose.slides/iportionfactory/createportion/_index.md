---
title: CreatePortion()
second_title: Aspose.Slides の C++ API リファレンス
description: 空のテキスト部分を作成します。
type: docs
weight: 1
url: /ja/aspose.slides/iportionfactory/createportion/
---
## IPortionFactory::CreatePortion() メソッド

空のテキスト部分を作成します。

```cpp
virtual System::SharedPtr<IPortion> Aspose::Slides::IPortionFactory::CreatePortion()=0
```

### 戻り値

[Portion](../../portion/).

## IPortionFactory::CreatePortion(System::String) メソッド

指定された文字列からテキスト部分を作成します。

```cpp
virtual System::SharedPtr<IPortion> Aspose::Slides::IPortionFactory::CreatePortion(System::String str)=0
```

### 引数

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| str | [System::String](../../../system/string/) | 文字列。 |

### 戻り値

[Portion](../../portion/).

## IPortionFactory::CreatePortion(System::SharedPtr\<IPortion\>) メソッド

指定された部分データを使用して部分を作成します。

```cpp
virtual System::SharedPtr<IPortion> Aspose::Slides::IPortionFactory::CreatePortion(System::SharedPtr<IPortion> portion)=0
```

### 引数

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| portion | [System::SharedPtr](../../../system/sharedptr/)\<[IPortion](../../iportion/)\> | 使用する部分。 |

### 戻り値

[Portion](../../portion/).

## 参照

* 型定義 [SharedPtr](../../../system/sharedptr/)
* クラス [IPortion](../../iportion/)
* クラス [IPortionFactory](../)
* クラス [String](../../../system/string/)
* 名前空間 [Aspose::Slides](../../)
* ライブラリ [Aspose.Slides](../../../)