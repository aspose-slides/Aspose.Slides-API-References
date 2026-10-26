---
title: HasOperatorEqualsHelper()
second_title: Aspose.Slides for C++ API リファレンス
description: 特定のクラスが operator == を持つかどうかを判定するヘルパー関数。
type: docs
weight: 235
url: /ja/system.collections.generic.details/hasoperatorequalshelper/
---
## System::Collections::Generic::Details::HasOperatorEqualsHelper(T *, T *) 関数

特定のクラスが operator == を持つかどうかを判定するヘルパー関数。

```cpp
template<class T,typename Dummy> std::true_type System::Collections::Generic::Details::HasOperatorEqualsHelper(T *, T *)
```

### テンプレート パラメータ

| パラメータ | 説明 |
| --- | --- |
| T | Type to check. |
| Dummy | Dummy argument for SFINAE magic. |

### 戻り値

operator == が存在する場合は std::true_type、そうでない場合は false が返されます。

## System::Collections::Generic::Details::HasOperatorEqualsHelper(void *, void *) 関数

特定のクラスが operator == を持つかどうかを判定するヘルパー関数。

```cpp
std::false_type System::Collections::Generic::Details::HasOperatorEqualsHelper(void *, void *)
```

### 戻り値

operator == が存在する場合は std::true_type、そうでない場合は false が返されます。

## 参照

* 名前空間 [System::Collections::Generic::Details](../)
* ライブラリ [Aspose.Slides](../../)