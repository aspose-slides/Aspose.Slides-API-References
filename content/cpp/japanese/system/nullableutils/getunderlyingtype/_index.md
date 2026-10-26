---
title: GetUnderlyingType()
second_title: Aspose.Slides for C++ API リファレンス
description: 指定された nullable 型の基になる型引数を返します。
type: docs
weight: 1
url: /ja/system/nullableutils/getunderlyingtype/
---
## NullableUtils::GetUnderlyingType(const System::TypeInfo\&) メソッド


指定された nullable 型の基になる型引数を返します。

```cpp
static const System::TypeInfo & System::NullableUtils::GetUnderlyingType(const System::TypeInfo &nullableType)
```


### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| nullableType | const [System::TypeInfo](../../typeinfo/)\& | 閉じたジェネリック nullable 型を記述する System.Type オブジェクト。 |

### 戻り値

nullableType パラメータが閉じたジェネリック nullable 型である場合はその型引数を返し、そうでない場合は null を返します。

## 関連項目

* クラス [TypeInfo](../../typeinfo/)
* クラス [NullableUtils](../)
* 名前空間 [System](../../)
* ライブラリ [Aspose.Slides](../../../)