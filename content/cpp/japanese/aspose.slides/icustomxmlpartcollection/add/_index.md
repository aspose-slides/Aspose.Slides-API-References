---
title: Add()
second_title: Aspose.Slides for C++ API リファレンス
description: 新しいカスタム XML パートを追加します。
type: docs
weight: 14
url: /ja/aspose.slides/icustomxmlpartcollection/add/
---
## ICustomXmlPartCollection::Add(System::ArrayPtr\<uint8_t\>) メソッド

新しいカスタム XML パートを追加します。

```cpp
virtual System::SharedPtr<ICustomXmlPart> Aspose::Slides::ICustomXmlPartCollection::Add(System::ArrayPtr<uint8_t> xmlData)=0
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| xmlData | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | 追加される新しいパートの XML データ。 |

### 戻り値

作成されたカスタム XML パート。

## ICustomXmlPartCollection::Add(System::String) メソッド

新しいカスタム XML パートを追加します。

```cpp
virtual System::SharedPtr<ICustomXmlPart> Aspose::Slides::ICustomXmlPartCollection::Add(System::String xmlString)=0
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| xmlString | [System::String](../../../system/string/) | 追加される新しいパートの XML 文字列。 |

### 戻り値

作成されたカスタム XML パート。

## ICustomXmlPartCollection::Add(System::SharedPtr\<System::IO::Stream\>) メソッド

新しいカスタム XML パートを追加します。

```cpp
virtual System::SharedPtr<ICustomXmlPart> Aspose::Slides::ICustomXmlPartCollection::Add(System::SharedPtr<System::IO::Stream> inputStream)=0
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| inputStream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | 追加される新しいパートの XML データを含む inputStream。 |

### 戻り値

作成されたカスタム XML パート。

## 参照

* 型定義 [SharedPtr](../../../system/sharedptr/)
* 型定義 [ArrayPtr](../../../system/arrayptr/)
* クラス [ICustomXmlPart](../../icustomxmlpart/)
* クラス [ICustomXmlPartCollection](../)
* クラス [String](../../../system/string/)
* クラス [Stream](../../../system.io/stream/)
* 名前空間 [Aspose::Slides](../../)
* ライブラリ [Aspose.Slides](../../../)