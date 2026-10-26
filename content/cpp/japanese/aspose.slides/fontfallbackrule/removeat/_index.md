---
title: RemoveAt()
second_title: Aspose.Slides for C++ API リファレンス
description: 指定されたインデックスのリストからFallBackフォントを削除します。
type: docs
weight: 131
url: /ja/aspose.slides/fontfallbackrule/removeat/
---
## FontFallBackRule::RemoveAt(int32_t) メソッド

指定されたインデックスのリストからFallBackフォントを削除します。

```cpp
void Aspose::Slides::FontFallBackRule::RemoveAt(int32_t index) override
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| index | **int32_t** | 削除するフォントのゼロベースインデックス。 |

## 備考

```cpp
// フォントのリストを含むルールを作成します。
auto newRule = MakeObject<FontFallBackRule>(0x3040, 0x309F, u"MS Mincho, MS Gothic, Tahoma, Times New Roman");
// リストからTahomaを削除します。
newRule->RemoveAt(2);
```

## 参照

* クラス [FontFallBackRule](../)
* 名前空間 [Aspose::Slides](../../)
* ライブラリ [Aspose.Slides](../../../)