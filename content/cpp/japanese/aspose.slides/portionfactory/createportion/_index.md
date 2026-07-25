---
title: CreatePortion()
second_title: Aspose.Slides for C++ API リファレンス
description: 空のテキストポーションを作成します。
type: docs
weight: 1
url: /ja/aspose.slides/portionfactory/createportion/
---
## PortionFactory::CreatePortion() メソッド

空のテキストポーションを作成します。

```cpp
System::SharedPtr<IPortion> Aspose::Slides::PortionFactory::CreatePortion() override
```

### 戻り値

[Portion](../../portion/).

## PortionFactory::CreatePortion(System::String) メソッド

指定された文字列からテキストポーションを作成します。

```cpp
System::SharedPtr<IPortion> Aspose::Slides::PortionFactory::CreatePortion(System::String str) override
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| str | [System::String](../../../system/string/) | String. |

### 戻り値

[Portion](../../portion/).

## PortionFactory::CreatePortion(System::SharedPtr\<IPortion\>) メソッド

指定されたポーションデータを使用してポーションを作成します。

```cpp
System::SharedPtr<IPortion> Aspose::Slides::PortionFactory::CreatePortion(System::SharedPtr<IPortion> portion) override
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| portion | [System::SharedPtr](../../../system/sharedptr/)\<[IPortion](../../iportion/)\> | 使用するポーション。 |

### 戻り値

[Portion](../../portion/).

## 参照

* Typedef [SharedPtr](../../../system/sharedptr/)
* クラス [IPortion](../../iportion/)
* クラス [PortionFactory](../)
* クラス [String](../../../system/string/)
* 名前空間 [Aspose::Slides](../../)
* ライブラリ [Aspose.Slides](../../../)