---
title: UnboxToNullable()
second_title: Aspose.Slides for C++ API リファレンス
description: オブジェクトを nullable 型にアンボックスします。
type: docs
weight: 79
url: /ja/system/objectext/unboxtonullable/
---
## ObjectExt::UnboxToNullable(const SmartPtr\<Object\>\&, bool) メソッド


オブジェクトを nullable 型にアンボックスします。

```cpp
template<class T> static Nullable<T> System::ObjectExt::UnboxToNullable(const SmartPtr<Object> &obj, bool safe=1)
```


### テンプレート パラメータ

| パラメータ | 説明 |
| --- | --- |
| T | 対象の型。 |

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| obj | const [SmartPtr](../../smartptr/)\<[Object](../../object/)\>\& | [Object](../../object/)をアンボックスする。 |
| safe | **bool** | true の場合、失敗時に nullptr を返し、そうでない場合は InvalidCastException をスローします。 |

### 戻り値

アンボックスされた nullable 値（null になる可能性があります）。

## 関連項目

* クラス [Nullable](../../nullable/)
* クラス [SmartPtr](../../smartptr/)
* クラス [Object](../../object/)
* クラス [ObjectExt](../)
* 名前空間 [System](../../)
* ライブラリ [Aspose.Slides](../../../)