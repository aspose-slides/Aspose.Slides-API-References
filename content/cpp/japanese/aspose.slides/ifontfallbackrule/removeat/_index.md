---
title: RemoveAt()
second_title: Aspose.Slides for C++ API リファレンス
description: リストの指定されたインデックスにあるフォールバックフォントを削除します。
type: docs
weight: 92
url: /ja/aspose.slides/ifontfallbackrule/removeat/
---
## IFontFallBackRule::RemoveAt(int32_t) メソッド

指定されたインデックスのリストからフォールバックフォントを削除します。

```cpp
virtual void Aspose::Slides::IFontFallBackRule::RemoveAt(int32_t index)=0
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| index | **int32_t** | 削除するフォントのゼロベースインデックス。 |
## 備考

```cpp
// フォントのリストを含むルールを作成します。
auto newRule = MakeObject<FontFallBackRule>(0x3040, 0x309F, u"MS Mincho, MS Gothic, Tahoma, Times New Roman");
//リストから Tahoma を削除
newRule->RemoveAt(2);
```

## 関連項目

* クラス [IFontFallBackRule](../)
* 名前空間 [Aspose::Slides](../../)
* ライブラリ [Aspose.Slides](../../../)