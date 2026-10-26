---
title: StringWriter()
second_title: Aspose.Slides for C++ API リファレンス
description: 指定された StringBuilder と IFormatProvider を使用して StringWriter の新しいインスタンスを作成します。
type: docs
weight: 1
url: /ja/system.io/stringwriter/stringwriter/
---
## StringWriter::StringWriter(const System::SharedPtr\<Text::StringBuilder\>\&, const IFormatProviderPtr\&) コンストラクタ

[StringWriter](../) の新しいインスタンスを、指定された StringBuilder と [IFormatProvider](../../../system/iformatprovider/) を使用して構築します。

```cpp
System::IO::StringWriter::StringWriter(const System::SharedPtr<Text::StringBuilder> &sb, const IFormatProviderPtr &formatProvider)
```

### 引数

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| sb | const [System::SharedPtr](../../../system/sharedptr/)\<[Text::StringBuilder](../../../system.text/stringbuilder/)\>\& | 構築中の [StringWriter](../) が使用する StringBuilder オブジェクト |
| formatProvider | const [IFormatProviderPtr](../../../system/iformatproviderptr/)\& | 構築中のオブジェクトが使用する [IFormatProvider](../../../system/iformatprovider/) オブジェクト |

## StringWriter::StringWriter(const System::SharedPtr\<Text::StringBuilder\>\&) コンストラクタ

[StringWriter](../) の新しいインスタンスを、指定された StringBuilder と現在のカルチャからの [IFormatProvider](../../../system/iformatprovider/) を使用して構築します。

```cpp
System::IO::StringWriter::StringWriter(const System::SharedPtr<Text::StringBuilder> &sb)
```

### 引数

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| sb | const [System::SharedPtr](../../../system/sharedptr/)\<[Text::StringBuilder](../../../system.text/stringbuilder/)\>\& | 構築中の [StringWriter](../) が使用する StringBuilder オブジェクト |

## StringWriter::StringWriter(const IFormatProviderPtr\&) コンストラクタ

[StringWriter](../) の新しいインスタンスを、指定された [IFormatProvider](../../../system/iformatprovider/) を使用して構築します。

```cpp
System::IO::StringWriter::StringWriter(const IFormatProviderPtr &formatProvider)
```

### 引数

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| formatProvider | const [IFormatProviderPtr](../../../system/iformatproviderptr/)\& | 構築中のオブジェクトが使用する [IFormatProvider](../../../system/iformatprovider/) オブジェクト |

## StringWriter::StringWriter() コンストラクタ

[StringWriter](../) の新しいインスタンスを、現在のカルチャからの [IFormatProvider](../../../system/iformatprovider/) を使用して構築します。

```cpp
System::IO::StringWriter::StringWriter()
```

## 参照

* 型定義 [SharedPtr](../../../system/sharedptr/)
* 型定義 [IFormatProviderPtr](../../../system/iformatproviderptr/)
* クラス [StringBuilder](../../../system.text/stringbuilder/)
* クラス [StringWriter](../)
* 名前空間 [System::IO](../../)
* ライブラリ [Aspose.Slides](../../../)