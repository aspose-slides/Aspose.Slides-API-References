---
title: Parse()
second_title: Aspose.Slides for C++ API リファレンス
description: 指定された列挙型の列挙定数の値を表すオブジェクトを、指定された名前で返します。
type: docs
weight: 27
url: /ja/system/enumvaluesbase/parse/
---
## EnumValuesBase::Parse(const TypeInfo\&, const String\&, bool) メソッド


指定された列挙型の列挙定数の値を表すオブジェクトを、指定された名前で返します。

```cpp
static SharedPtr<Object> System::EnumValuesBase::Parse(const TypeInfo &type, const String &str, bool ignoreCase)
```


### 引数

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| type | const [TypeInfo](../../typeinfo/)\& | [TypeInfo](../../typeinfo/)オブジェクトは、返す列挙値の型を表します |
| str | const [String](../../string/)\& | 列挙定数の名前 |
| ignoreCase | **bool** | 列挙定数の名前を解釈する際に大文字小文字を無視するかどうかを指定します |

### 戻り値

名前が **str** で指定された列挙定数の値を表すオブジェクトです。

## 参照

* Typedef [SharedPtr](../../sharedptr/)
* クラス [Object](../../object/)
* クラス [TypeInfo](../../typeinfo/)
* クラス [String](../../string/)
* クラス [EnumValuesBase](../)
* 名前空間 [System](../../)
* Library [Aspose.Slides](../../../)