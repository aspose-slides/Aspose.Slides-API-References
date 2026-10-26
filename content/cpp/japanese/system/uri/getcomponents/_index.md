---
title: GetComponents()
second_title: Aspose.Slides for C++ API リファレンス
description: 現在のオブジェクトが表す URI の、指定されたエスケープ方式を使用して、指定されたコンポーネントを返します。
type: docs
weight: 378
url: /ja/system/uri/getcomponents/
---
## Uri::GetComponents(UriComponents, UriFormat) const メソッド

現在のオブジェクトが表す URI の、指定されたエスケープ方式を使用して、指定されたコンポーネントを返します。

```cpp
String System::Uri::GetComponents(UriComponents components, UriFormat format) const
```

### 引数

| Parameter | Type | Description |
| --- | --- | --- |
| components | [UriComponents](../../uricomponents/) | 返す URI のどの部分を指定するかを示す UriComponents 値のビット単位の組み合わせ |
| format | [UriFormat](../../uriformat/) | 特殊文字がどのようにエスケープされるかを指定します |

### 戻り値

要求されたコンポーネント

## 参照

* 列挙体 [UriComponents](../../uricomponents/)
* 列挙体 [UriFormat](../../uriformat/)
* クラス [String](../../string/)
* クラス [Uri](../)
* 名前空間 [System](../../)
* ライブラリ [Aspose.Slides](../../../)