---
title: Add()
second_title: Aspose.Slides for C++ API リファレンス
description: 新しいカスタム XML パートを追加します。
type: docs
weight: 53
url: /ja/aspose.slides/customxmlpartcollection/add/
---
## CustomXmlPartCollection::Add(System::String) メソッド


新しいカスタム XML パートを追加します。

```cpp
System::SharedPtr<ICustomXmlPart> Aspose::Slides::CustomXmlPartCollection::Add(System::String xmlString) override
```


### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| xmlString | [System::String](../../../system/string/) | 追加される新しいパートの XML 文字列。 |

### 戻り値

作成されたカスタム XML パート。

## CustomXmlPartCollection::Add(System::ArrayPtr\<uint8_t\>) メソッド


新しいカスタム XML パートを追加します。

```cpp
System::SharedPtr<ICustomXmlPart> Aspose::Slides::CustomXmlPartCollection::Add(System::ArrayPtr<uint8_t> xmlData) override
```


### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| xmlData | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | 追加される新しいパートの XML データ。 |

### 戻り値

作成されたカスタム XML パート。

## CustomXmlPartCollection::Add(System::SharedPtr\<System::IO::Stream\>) メソッド


新しいカスタム XML パートを追加します。

```cpp
System::SharedPtr<ICustomXmlPart> Aspose::Slides::CustomXmlPartCollection::Add(System::SharedPtr<System::IO::Stream> inputStream) override
```


### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| inputStream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | 追加される新しいパートの XML データを含む inputStream。 |

### 戻り値

作成されたカスタム XML パート。

## 参照

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [ICustomXmlPart](../../icustomxmlpart/)
* Class [String](../../../system/string/)
* Class [CustomXmlPartCollection](../)
* Class [Stream](../../../system.io/stream/)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)