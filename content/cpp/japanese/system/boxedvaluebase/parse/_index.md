---
title: Parse()
second_title: Aspose.Slides for C++ API リファレンス
description: 指定された名前を持つ列挙型定数の値をボックス化します。列挙型定数の名前を示す文字列を解釈する際に、大文字と小文字を無視するかどうかを指定するパラメータです。
type: docs
weight: 53
url: /ja/system/boxedvaluebase/parse/
---
## BoxedValueBase::Parse(const TypeInfo\&, const String\&, bool) method

指定された名前を持つ列挙型定数の値をボックス化します。列挙型定数の名前を表す文字列を解釈する際に、大文字小文字を無視するかどうかを指定するパラメータです。

```cpp
static SharedPtr<Object> System::BoxedValueBase::Parse(const TypeInfo &type, const String &str, bool ignoreCase)
```

### Arguments

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| type | const [TypeInfo](../../typeinfo/)\& | 列挙型の型を指定します |
| str | const [String](../../string/)\& | ボックス化する列挙型定数の名前 |
| ignoreCase | **bool** | 列挙型定数の名前を表す文字列を解釈する際に大文字小文字を無視するかどうかを指定します |

### Return Value

指定された列挙型定数のボックス化された値を表すオブジェクトへの共有ポインタ

## BoxedValueBase::Parse(const TypeInfo\&, const String\&) method

指定された名前を持つ列挙型定数の値をボックス化します。

```cpp
static SharedPtr<Object> System::BoxedValueBase::Parse(const TypeInfo &type, const String &str)
```

### Arguments

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| type | const [TypeInfo](../../typeinfo/)\& | 列挙型の型を指定します |
| str | const [String](../../string/)\& | ボックス化する列挙型定数の名前 |

### Return Value

指定された列挙型定数のボックス化された値を表すオブジェクトへの共有ポインタ

## See Also

* Typedef [SharedPtr](../../sharedptr/)
* クラス [Object](../../object/)
* クラス [TypeInfo](../../typeinfo/)
* クラス [String](../../string/)
* クラス [BoxedValueBase](../)
* 名前空間 [System](../../)
* Library [Aspose.Slides](../../../)