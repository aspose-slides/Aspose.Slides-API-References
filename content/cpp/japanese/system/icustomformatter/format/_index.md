---
title: Format()
second_title: Aspose.Slides for C++ API リファレンス
description: 指定された書式を使用して、現在のオブジェクトが表す値の文字列表現を返します。
type: docs
weight: 1
url: /ja/system/icustomformatter/format/
---
## ICustomFormatter::Format(System::String, System::SharedPtr\<System::Object\>, System::SharedPtr\<System::IFormatProvider\>) method

指定された書式を使用して、現在のオブジェクトが表す値の文字列表現を返します。

```cpp
virtual System::String System::ICustomFormatter::Format(System::String format, System::SharedPtr<System::Object> arg, System::SharedPtr<System::IFormatProvider> formatProvider)=0
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| format | [System::String](../../string/) | 文字列書式 |
| arg | [System::SharedPtr](../../sharedptr/)\<[System::Object](../../object/)\> | フォーマット対象のオブジェクト |
| formatProvider | [System::SharedPtr](../../sharedptr/)\<[System::IFormatProvider](../../iformatprovider/)\> | 書式情報を提供するオブジェクト |

### 戻り値

**arg** を **format** と **formatProvider** で指定された書式に従ってフォーマットした文字列表現

## 参照

* Typedef [SharedPtr](../../sharedptr/)
* Class [String](../../string/)
* Class [Object](../../object/)
* Class [IFormatProvider](../../iformatprovider/)
* Class [ICustomFormatter](../)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)