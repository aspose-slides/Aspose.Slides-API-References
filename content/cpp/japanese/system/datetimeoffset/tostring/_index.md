---
title: ToString()
second_title: Aspose.Slides for C++ APIリファレンス
description: 指定された形式と書式提供者を使用して、現在のオブジェクトを文字列に変換します。
type: docs
weight: 443
url: /ja/system/datetimeoffset/tostring/
---
## DateTimeOffset::ToString(const String\&, const SharedPtr\<IFormatProvider\>\&) const method

指定された形式と書式提供者を使用して、現在のオブジェクトを文字列に変換します。

```cpp
String System::DateTimeOffset::ToString(const String &format, const SharedPtr<IFormatProvider> &provider) const
```

### Arguments

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| format | const [String](../../string/)\& | 形式文字列。 |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | 書式提供者。 |

### Return Value

[String](../../string/) の現在の [DateTimeOffset](../) オブジェクトの表現。

## DateTimeOffset::ToString(const SharedPtr\<IFormatProvider\>\&) const method

指定された書式提供者を使用して、現在のオブジェクトを文字列に変換します。

```cpp
String System::DateTimeOffset::ToString(const SharedPtr<IFormatProvider> &provider) const
```

### Arguments

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | 書式提供者。 |

### Return Value

[String](../../string/) の現在の [DateTimeOffset](../) オブジェクトの表現。

## DateTimeOffset::ToString(const String\&) const method

指定された形式を使用して、現在のオブジェクトを文字列に変換します。

```cpp
String System::DateTimeOffset::ToString(const String &format) const
```

### Arguments

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| format | const [String](../../string/)\& | 形式文字列。 |

### Return Value

[String](../../string/) の現在の [DateTimeOffset](../) オブジェクトの表現。

## DateTimeOffset::ToString() const method

現在のオブジェクトを文字列に変換します。

```cpp
String System::DateTimeOffset::ToString() const
```

### Return Value

[String](../../string/) の現在の [DateTimeOffset](../) オブジェクトの表現。

## See Also

* Typedef [SharedPtr](../../sharedptr/)
* Class [String](../../string/)
* Class [IFormatProvider](../../iformatprovider/)
* Class [DateTimeOffset](../)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)