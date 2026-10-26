---
title: Equals()
second_title: Aspose.Slides for C++ API リファレンス
description: 2 つの IBaseSlide インスタンスが等しいかどうかを判定します。返却値はスライドの構造と静的コンテンツに基づいて算出されます。すべてのシェイプ、スタイル、テキスト、アニメーション、その他の設定等が等しい場合、スライドは等しいとみなされます。比較では SlideId などの固有識別子や、Date Placeholder の現在の日付値などの動的コンテンツは考慮されません。
type: docs
weight: 183
url: /ja/aspose.slides/ibaseslide/equals/
---
## IBaseSlide::Equals(System::SharedPtr\<IBaseSlide\>) メソッド

2 つの [IBaseSlide](../) インスタンスが等しいかどうかを判定します。返却値はスライドの構造と静的コンテンツに基づいて計算されます。すべてのシェイプ、スタイル、テキスト、アニメーション、およびその他の設定等が等しい場合、スライドは等しいとみなされます。比較は SlideId などの固有識別子の値や、Date [Placeholder](../../placeholder/) における現在の日付値などの動的コンテンツは考慮しません。

```cpp
virtual bool Aspose::Slides::IBaseSlide::Equals(System::SharedPtr<IBaseSlide> slide)=0
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| slide | [System::SharedPtr](../../../system/sharedptr/)\<[IBaseSlide](../)\> | 現在の [IBaseSlide](../) と比較するための [IBaseSlide](../)。 |

### 戻り値

指定された [IBaseSlide](../) が現在の [IBaseSlide](../) と等しい場合は **true**、それ以外の場合は **false**。

## 参照

* 型定義 [SharedPtr](../../../system/sharedptr/)
* クラス [IBaseSlide](../)
* 名前空間 [Aspose::Slides](../../)
* ライブラリ [Aspose.Slides](../../../)